---
title: iMPACT-Test
nav: true
---

<img src="images/iMPACT-Test_logo.png" alt="iMPACT-Test logo" style="width:60%;" >

The **iMPACT-Test** is a set of Notebooks explaining and implementing the necessary tasks to calibrate and evaluate a soil erosion model.  These notebooks provide a practical, hands-on approach to understanding and applying key model assessment techniques.

This is the list of the iMPACT-Test Notebooks, along with links to run them online. *This website is under development and we will be gradually adding new Notebooks.*

**1. Soil sampling optimization:** This notebook focuses on selecting the most informative locations for soil sampling points to maximize the information gained for model calibration and validation.

[**Click here to run the Notebook online**](https://mybinder.org/v2/gh/iMPACT-erosion/iMPACT-erosion/HEAD?urlpath=notebooks/iMPACT-Test/1.Optimized_soil_sampling)

**2. Interpolation of spatial data:** This notebook demonstrates various spatial interpolation techniques to create continuous maps of soil properties and soil loss rates from discrete point measurements. It compares different interpolation methods (e.g., nearest neighbor, linear, cubic) and discusses their suitability for different types of data and spatial patterns.

[**Click here to run the Notebook online**](https://mybinder.org/v2/gh/iMPACT-erosion/iMPACT-erosion/HEAD?urlpath=notebooks/iMPACT-Test/2.Spatial_interpolation.ipynb)

**3. Calibration:** This notebook explains how to calibrate a soil erosion model using observed and interpolated spatial data, adjusting parameters to minimize error. The objective is to evaluate and improve the model performance in simulating observed past changes and their corresponding measured/estimated impacts.

**4. Sensitivity analysis:** To test plausibility of the model behaviour, this Notebook use Global Sensitivity Analysis (GSA). GSA can identify the climate variables, parameters and soil erosion processes, that most influence model results and whether these results are consistent with our expectations and empirical evidence. 