# Asian Tigers Economic Growth Analysis

## Overview

This project analyzes the sources of economic growth in the Four Asian Tigers (Hong Kong, Singapore, South Korea, and Taiwan) from 1960-2019 using growth accounting methodology. 

## Research Question

**Did the Asian Tigers achieve their economic miracle through productivity improvements or through capital and labor accumulation?**

## Data Sources

### Primary Data
**Penn World Table (PWT) 10.01**
- Source: University of Groningen Growth and Development Centre
- Access: Downloaded via FRED
- Coverage: 1950-2019
- Variables:
  - `rgdpna`: Real GDP at constant 2017 national prices (millions of 2017 USD)
  - `rkna`: Capital stock at constant 2017 national prices (millions of 2017 USD)
  - `emp`: Number of persons engaged (millions)
  - `labsh`: Share of labor compensation in GDP
  - `pop`: Population (millions)

### Countries Analyzed
**Four Tigers:**
- Hong Kong
- Singapore
- South Korea
- Taiwan

**Comparison Groups:**
- Developed: United States, Japan
- Latin America: Brazil, Mexico, Argentina
- Southeast Asia: Thailand, Malaysia, Indonesia, Philippines

## Methodology

This project employs growth accounting based on the Solow (1957) framework:
```
ΔY/Y = ΔA/A + α(ΔK/K) + (1-α)(ΔL/L)
```

Where:
- Y = Real GDP
- A = Total Factor Productivity (TFP)
- K = Capital stock
- L = Labor input
- α = Capital share (assumed 0.33)

TFP growth is calculated as the Solow residual.

## Technologies Used

- **Python 3.8+**
- **pandas** 
- **numpy** 
- **matplotlib** 
- **seaborn** 
- **Jupyter** 

## Project Status

**In Progress** 

- [x] Data collection and cleaning
- [x] GDP and per capita analysis
- [ ] Growth accounting and TFP calculation
- [ ] Comparative econometric analysis
- [ ] Paper writing

## Author

Gregory Park  
Economics, UMD '28  

## License

MIT License - see LICENSE file for details
