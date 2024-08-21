---
title: iMPACT-Start
nav: true
---

<img src="iMPACT-Start_logo.png" alt="iMPACT-Start logo" style="width:60%;" >

The **iMPACT-Start** is a set of Notebooks explaining and implementing the starting soil erosion modelling tasks:

This is the list of the iMPACT-start Notebooks and links to run them online. *This website is under development and we will be gradually adding new Notebooks.*

**1. Fill sinks of the digital elevation model (DEM):** Filling sinks ensures a continuous representation of surface water flow, which is essential for hydrological modeling.

[**Click here to run the Notebook online**](https://mybinder.org/v2/gh/iMPACT-erosion/iMPACT-erosion/HEAD?urlpath=notebooks/iMPACT-Start/1.Fill_sinks.ipynb)

**2. Flow accumulation of the surface water flow:** Flow accumulation is a critical step in hydrological modeling and analysis. It indicates how water flows across the terrain, accumulating from higher elevations down to lower elevations. This Notebook includes:
	- Determination of slope gradients and flow directions
	- D8 and Dinf flow accumulation methods

[**Click here to run the Notebook online**](https://mybinder.org/v2/gh/iMPACT-erosion/iMPACT-erosion/HEAD?urlpath=notebooks/iMPACT-Start/2.Flow_accumulation.ipynb)

**3. Catchment delineation:** Imagine pouring water onto a piece of land. Where does the water go? Catchment delineation is like drawing lines around the areas where the water collects and flows into streams or rivers. To do this, we look at how the land slopes and where the water would naturally flow downhill. We then calculate which areas are part of the same "catchment" or drainage area by figuring out which areas drain into the same stream or river. This Notebook includes:
	- Definition of the catchment outlet and boundaries. 
	- Determination of flow direction and flow accumulation maps and flow routing of the delineated catchment.
	
[**Click here to run the Notebook online**](https://mybinder.org/v2/gh/iMPACT-erosion/iMPACT-erosion/HEAD?urlpath=notebooks/iMPACT-Start/3.Catchment_delineation.ipynb)

**4. Soil erosion modelling. This includes:

**4.1. Effective rainfall estimation:** Not all rain that falls from the sky ends up causing erosion. Some of it gets caught by trees and other plants before it even reaches the ground. Effective rainfall estimation is about figuring out how much of the rain actually makes it to the ground and can cause erosion. We take into account how much of the rain is blocked by trees and plants.

**4.2. Surface runoff simulation:** We simulate the surface runoff generation and how water moves across the land surface.

**4.3. Soil detachment by rainfall and runoff:** Rain drops and surface runoff can be powerful enough to knock tiny particles of soil loose. This task is about modeling how much soil gets detached or separated from the ground when it rains. We want to understand how rainfall and surface runoff impacts the soil and causes erosion.

**4.4. Soil transport and sedimentation by surface runoff:** When water runs off the land, it carries soil particles along with it. This task is about modeling how these soil particles move with the flowing water and where they end up depositing or settling. We want to understand how soil gets transported across the landscape by surface runoff and where it gets deposited.

If you find errors/bugs or you would like to contribute, please [contact](./contact.md/) us.
