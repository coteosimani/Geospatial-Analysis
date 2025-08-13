# Geospatial Analysis of Sexual Street Harassment in Santiago, Chile

**Author:** María José Osimani  
**Date:** May 14, 2024  

This repository contains a geospatial analysis using sample data. You can explore the interactive visualization created from this analysis by clicking the link below:

🔗 **[View Interactive Visualization](https://htmlpreview.github.io/?https://github.com/coteosimani/Geospatial-Analysis/blob/main/Geospatial-analysis.html)**

The visualization was built using R packages to make spatial data exploration accessible directly from your browser.

## Overview
This project analyzes the prevalence and spatial distribution of sexual street harassment in Santiago, Chile, using survey data and geospatial analysis.  
Research questions:
- What proportion of women experience street harassment in each municipality?
- Is there spatial correlation in harassment cases?

---

## Data
- **Survey:** ENVIF-VCM (2017 & 2020, Region 13), n = 2,440 women.  
- **Spatial:** Municipality shapefiles for urban Santiago.

---

## Methods
- Descriptive statistics on prevalence by municipality and harassment type.  
- Spatial autocorrelation: Global & Local Moran’s I.  
- R packages: `tidyverse`, `sf`, `spdep`, `tmap`.

---

## Findings
- ~40% of women reported harassment; 45% first experienced it before age 14.  
- Harassment occurs across neighborhoods, public transport, and streets.  
- No significant global spatial autocorrelation; slight concentration in central areas.

---

## Conclusion
Harassment is widespread across Santiago. Prevention policies should focus on **micro-spatial factors** like lighting and police presence.

---

## License
This project is licensed under the MIT License – see [LICENSE](LICENSE) for details.

