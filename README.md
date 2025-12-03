# Malawi Rainfall Trend Analysis (2000–2024)
Comprehensive geospatial analysis of long-term rainfall trends across Malawi using CHIRPS satellite rainfall data. The study evaluates spatial variability and long-term changes in annual rainfall using pixel-wise linear regression.

This project demonstrates analytical and technical skills in:
- Climate data analysis
- Remote sensing and geospatial processing
- Trends and environmental change assessment
- Raster data processing using Python
- Climate-risk information for NGOs and government institutions

---

## Key Findings
- **National rainfall trend:** −1.20 mm/year (overall decline)
- **Maximum local increase:** +13.96 mm/year
- **Maximum local decrease:** −20.63 mm/year
- Southern Malawi shows a consistent and significant drying pattern.
- Central and Northern Malawi exhibit a mixed pattern of rainfall increases and decreases, indicating high spatial climate variability.


## Methods Overview
The analysis followed these steps:

1. **Data Preparation**
   - CHIRPS annual rainfall GeoTIFFs (2000–2024)
   - Malawi boundary shapefile (GADM)
   - All data clipped to Malawi borders using `rasterio.mask`

2. **Spatial Trend Computation**
   - Pixel-wise linear regression using SciPy (`linregress`)
   - Trend estimated in **mm/year**
   - National averages + extreme values

3. **Visualization**
   - Trend map produced using matplotlib
   - Blue shades indicate increasing rainfall
   - Red shades indicate decreasing rainfall

