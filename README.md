Blessingswi Rainfall Trend Analysis (2000–2024)

This project analyzes long-term rainfall variability across Malawi using CHIRPS satellite rainfall 
data covering the period 2000–2024. Using Python, geospatial processing, and pixel-wise linear 
regression, the analysis reveals spatial patterns of increasing and declining rainfall, supporting 
climate risk assessment, water resource planning, and environmental decision-making.

This work demonstrates advanced competency in:
- Climate and environmental data analysis  
- Python-based geospatial modelling  
- GIS and remote sensing workflows  
- Climate risk interpretation for development and humanitarian actors  

**Author: Blessings Master  
Environmental Data Analyst | GIS & Climate Modelling Specialist**

---

## Why This Analysis Matters

Malawi’s economy and livelihoods are highly climate sensitive, especially in:
- Agriculture (80% rainfed)
- Water resources (hydropower, irrigation, drinking water)
- Disaster risk (droughts and floods)
- Food security and rural livelihoods  

Understanding long-term rainfall trends is essential because:
- Rainfall variability is increasing across Malawi.
- Southern Malawi experiences more frequent droughts.
- Rainfall shifts affect groundwater recharge, streamflow, and reservoir performance.
- National and district-level planning requires evidence-based climate intelligence.

This analysis provides a **nationwide, spatially resolved rainfall trend map**, enabling government 
institutions, NGOs, and development partners to plan more effectively for climate resilience.

---

## Organizations That Can Use This Analysis (And How)

### 1. **Government Agencies**

#### **DCCMS (Department of Climate Change & Meteorological Services)**
- Climate trend monitoring  
- Seasonal and long-term rainfall pattern evaluation  
- Early warning systems (EWS)  

#### **DoDMA (Department of Disaster Management Affairs)**
- Evidence-based disaster preparedness  
- Identifying drought-prone districts  
- Climate risk modelling for response planning  

#### **Ministry of Water & NWRA**
- Evaluating impacts of rainfall decline on:
  - groundwater recharge  
  - river flow  
  - catchment hydrology  
- Planning future investments in water supply  

#### **Blantyre Water Board, Lilongwe Water Board, Northern Region Water Board**
- Long-term water resource projections  
- Understanding rainfall-driven hydrological variability  

---

### 2. **International NGOs**

#### **World Vision Malawi**
- Climate-resilient WASH programmes  
- Drought-vulnerability assessments  
- Climate-smart agriculture planning  

#### **WaterAid**
- Securing water supply in rainfall-declining zones  
- Long-term resilience programming  
- Community water access planning  

#### **CARE, CRS, Save the Children**
- Climate adaptation project design  
- Humanitarian response planning  
- Drought early action  

#### **Red Cross / Red Crescent**
- Emergency rainfall deficiency monitoring  
- Drought and flood readiness programs  

---

### 3. **Donor Agencies & Development Partners**

#### **UNDP, UNDRR, GEF**
- Climate resilience investment prioritization  
- National adaptation planning  

#### **World Bank, African Development Bank**
- Hydrological modelling for energy, agriculture, and water  
- Climate-smart infrastructure planning  

#### **USAID (MERIT, DISCOVER, Titukulane)**
- District-level climate vulnerability assessments  
- Rainfall-based resilience programming  

---

### 4. **Academia & Research Institutions**
- Climate modelling research  
- Hydrology and environmental change studies  
- Teaching climate GIS applications  

---

## Key Findings

- **National rainfall trend:** −1.20 mm/year (declining)  
- **Maximum rainfall increase:** +13.96 mm/year  
- **Maximum rainfall decrease:** −20.63 mm/year  

### Spatial Interpretation:
- **Southern Malawi** shows strong negative trends, indicating increasing drought frequency.  
- **Northern & Central Malawi** display mixed patterns, reflecting higher climatic variability.  

Full trend map uploaded-----

## Method Summary

### Data:
- CHIRPS v3.0 Annual Rainfall (2000–2024)  
- Malawi boundary (GADM Level 0)  

### Processing Steps:
1. Load CHIRPS annual GeoTIFFs  
2. Clip rasters to Malawi boundary using rasterio.mask  
3. Extract rainfall values per year  
4. Compute pixel-wise linear regression (slope = trend mm/year)  
5. Generate national summary statistics  
6. Build rainfall trend map  

### Tools Used:
- Python: rasterio, numpy, matplotlib, geopandas, scipy  
- GIS: Clipping, raster alignment, spatial trend analysis  

## Author  
**Madalitso Master**  
Environmental Data Analyst 
Email: mastetblessings.com
