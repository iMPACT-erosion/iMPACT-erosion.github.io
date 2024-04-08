---
title: iMPACT-Start
nav: true
---

<img src="iMPACT-Start_logo.png" alt="iMPACT-Start logo" style="width:60%;" >

The **iMPACT-Start** is a set of Notebooks explaining and implementing the starting soil erosion modelling tasks:

This is the list all the Notebooks that are currently available including their description and links to run them online:

**a. Preprocessing of input data:** Before we start working with the data, we need to make sure it's all in good shape. This means filling in any missing bits of information in our climate records, figuring out what the land looks like between the places we have data for (interpolation), and fixing any mistakes in our digital map that shows the height of the land (DEM). Think of it like tidying up a messy room before you can start playing in it. 

Links to the Notebooks:
- Addressing data gaps in climate records 
- Spatial data interpolation 
- [**Resolving digital elevation model (DEM) sinks**](https://mybinder.org/v2/gh/iMPACT-erosion/iMPACT-erosion/HEAD?urlpath=notebooks/iMPACT-Start/Fill_sinks.ipynb)

**b. Catchment delineation:** Imagine pouring water onto a piece of land. Where does the water go? Catchment delineation is like drawing lines around the areas where the water collects and flows into streams or rivers. To do this, we look at how the land slopes and where the water would naturally flow downhill. We then calculate which areas are part of the same "catchment" or drainage area by figuring out which areas drain into the same stream or river.

Links to the Notebooks:
- Addressing data gaps in climate records 
- Spatial data interpolation 
- Resolving digital elevation model (DEM) sinks.

**c. Effective rainfall estimation:** Not all rain that falls from the sky ends up causing erosion. Some of it gets caught by trees and other plants before it even reaches the ground. Effective rainfall estimation is about figuring out how much of the rain actually makes it to the ground and can cause erosion. We take into account how much of the rain is blocked by trees and plants.

Links to the Notebooks:
- Calculating flow direction
- Flow accumulation and flow routing

**d. Soil detachment by rainfall:** When rain falls onto soil, it can be powerful enough to knock tiny particles of soil loose. This task is about modeling how much soil gets detached or separated from the ground when it rains. We want to understand how rainfall impacts the soil and causes erosion.

Links to the Notebooks:
- Crop growth model
- Determination of the canopy cover and rainfall interception

**e. Soil moisture and surface runoff simulation:** Soil needs to be a bit wet for erosion to happen. This task is about predicting how wet the soil gets over time and how much water runs off the surface of the land when it rains really hard. We simulate or predict how water moves through the soil and across the land surface.

Links to the Notebooks:
- Soil moisture model
- Surface runoff model

**f. Soil transport and sedimentation by surface runoff:** When water runs off the land, it carries soil particles along with it. This task is about modeling how these soil particles move with the flowing water and where they end up depositing or settling. We want to understand how soil gets transported across the landscape by surface runoff and where it gets deposited.

Links to the Notebooks:
- Flow routing
- Sediment transport and sedimentation

If you find errors/bugs or you would like to contribute, please [contact](./contact.md/) us.
