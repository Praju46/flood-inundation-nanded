# Flood Inundation Mapping using 2D Rain-on-Grid Model  
**Nanded District, Maharashtra, India**

This repository presents a workflow for **flood inundation mapping** in Nanded district using a **2D Rain-on-Grid (RoG)** hydrodynamic modelling approach integrated with geospatial data.

The study evaluates flood inundation dynamics over a long-term period (**1985–2025**) to assess temporal variability and changing flood patterns under varying rainfall conditions.

---

## Project Overview
Flooding is a recurring hazard in parts of the **Godavari River basin**, including Nanded district, driven by intense monsoonal rainfall, low-gradient floodplains, and limited drainage capacity.

Unlike river-centric flood models, the **Rain-on-Grid (RoG)** approach applies rainfall directly over a gridded terrain surface, enabling simulation of **overland flow routing** and **spatial inundation patterns** across the landscape.

---

## Objectives
- Simulate surface runoff and flood inundation using a **2D Rain-on-Grid** model  
- Delineate spatial extent of **flood-prone areas** (1985–2025)  
- Analyze temporal variability in inundation patterns  
- Generate flood extent and depth information to support risk assessment and planning  

---

## Study Area
- **Nanded District, Maharashtra, India**  
- Part of the **Godavari River basin**  
- Characterized by low-gradient floodplains, agricultural land use, and monsoon-driven hydrology  

---

## Methodology (Summary)
1. Prepare high-resolution **DEM**
2. Derive terrain parameters (slope, flow direction, flow accumulation)
3. Integrate long-term rainfall inputs (**1985–2025**)
4. Run **2D Rain-on-Grid hydrodynamic simulations**
5. Generate flood extent and flood depth outputs
6. Post-process and analyze multi-decadal flood inundation patterns

---

## Data Used
- Digital Elevation Model (DEM)  
- Long-term rainfall datasets (**1985–2025**)  
- Land use / land cover data  
- Drainage network and administrative boundaries  

---

## Tools & Technologies
- **2D Rain-on-Grid (RoG) hydrodynamic modelling** (HEC-RAS framework)  
- ArcGIS / QGIS  
- Python  
- Remote sensing and GIS techniques  

---

## Sample Output (One Map)
Below is a representative flood inundation output from the Rain-on-Grid modelling workflow.

![Flood Inundation Map - Nanded](assets/images/nanded_flood_map.png)

---

## Applications
- Long-term flood hazard assessment  
- Floodplain management and zoning  
- Disaster risk reduction and preparedness  
- Climate-resilient regional planning  

---

## Status
This repository contains the workflow description and representative output.  
Additional scenario-based simulations and extended results may be added in future updates.
