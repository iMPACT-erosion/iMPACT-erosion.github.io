---
title: iMPACT-Start
nav: true
---

<img src="images/iMPACT-Start_logo.png" alt="iMPACT-Start logo" style="width:60%;" >

The **iMPACT-Start** is a set of Notebooks explaining and implementing the starting soil erosion modelling tasks:

This is the list of the iMPACT-start Notebooks and links to run them online. *This website is under development and we will be gradually adding new Notebooks.*

---

**1. Fill climate data gaps using probability distributions:** Teaches how to fix missing weather records (like rainfall or temperature) using statistics. If a weather station has gaps in its data, this Notebook shows how to estimate those missing days/months by analyzing patterns from existing data.

[**Click here to run the Notebook online**](https://mybinder.org/v2/gh/iMPACT-erosion/iMPACT-erosion/HEAD?urlpath=notebooks/iMPACT-Start/1.Fill_climate_data_gaps.ipynb)

---

**2. Fill sinks of the digital elevation model (DEM):** Fixes "holes" in digital elevation maps that disrupt water flow simulations. These holes (sinks) might be real (like volcanic craters) or errors in the map.

[**Click here to run the Notebook online**](https://mybinder.org/v2/gh/iMPACT-erosion/iMPACT-erosion/HEAD?urlpath=notebooks/iMPACT-Start/2.Fill_sinks.ipynb)

---

**3. Flow accumulation of the surface water flow:** Flow accumulation is a critical step in hydrological modeling and analysis. It indicates how water flows across the terrain, accumulating from higher elevations down to lower elevations. This Notebook includes:
	- Determination of slope gradients and flow directions
	- Shows how water moves downhill across a landscape using two methods:

		D8: Simple "water flows to one neighboring cell"

		Dinf: Realistic "water splits between multiple cells"

[**Click here to run the Notebook online**](https://mybinder.org/v2/gh/iMPACT-erosion/iMPACT-erosion/HEAD?urlpath=notebooks/iMPACT-Start/3.Flow_accumulation.ipynb)

---

**4. Catchment delineation:** Helps users define the area that drains to a specific point, i.e. a catchment or watershed. You pick a point and the Notebook automatically draws the surrounding hills/mountains that feed water to it. This Notebook includes:
	- Definition of the catchment outlet and boundaries. 
	- Determination of flow direction and flow accumulation maps and flow routing of the delineated catchment.
	
[**Click here to run the Notebook online**](https://mybinder.org/v2/gh/iMPACT-erosion/iMPACT-erosion/HEAD?urlpath=notebooks/iMPACT-Start/4.Catchment_delineation.ipynb)

---

**5. Rainfall erosivity (R-factor):**  Measures how much heavy rain contributes to soil loss. Uses rainfall data to calculate the "R-factor" – a number representing rain’s ability to erode the soil.

[**Click here to run the Notebook online**](https://mybinder.org/v2/gh/iMPACT-erosion/iMPACT-erosion/HEAD?urlpath=notebooks/iMPACT-Start/5.Rainfall_erosivity.ipynb)  

---

**6. Soil erodibility (K-factor):**  Determines how easily soil washes away based on:

	- Texture (% sand/silt/clay)
	- Organic matter
	- Permeability
	
Uses USDA’s Nomograph method.

[**Click here to run the Notebook online**](https://mybinder.org/v2/gh/iMPACT-erosion/iMPACT-erosion/HEAD?urlpath=notebooks/iMPACT-Start/6.Soil_erdodibility.ipynb)  

---

**7. Topographic factor (LS-factor):** Calculates how terrain steepness and upslope length increase erosion. Uses elevation maps to identify areas where water gains speed and volume as it flows and concentrates downhill.

[**Click here to run the Notebook online**](https://mybinder.org/v2/gh/iMPACT-erosion/iMPACT-erosion/HEAD?urlpath=notebooks/iMPACT-Start/7.Topographic_factor.ipynb)  

---

**8. Land cover management factors (C & P factors):** Quantifies how land use affects erosion:

	- ***C-factor***: Vegetation cover (forests protect soil better than bare fields)

	- ***P-factor***: Farming practices (contour plowing reduces erosion vs. up/downhill rows)

[**Click here to run the Notebook online**](https://mybinder.org/v2/gh/iMPACT-erosion/iMPACT-erosion/HEAD?urlpath=notebooks/iMPACT-Start/8.Land_Cover_and_Practices_factors.ipynb)

*This website is under development and we will be gradually adding new Notebooks.*

If you find errors/bugs or you would like to contribute, please [contact](./contact.md/) us.
