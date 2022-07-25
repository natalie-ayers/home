---
id: projects
title: Projects
---

## Large-Scale Agent-Based Model of Israeli Counterterrorism  
  
An agent-based model developed with Mesa in Python which models Palestinian sentiment, terrorist attacks, and Israeli counterterrorism actions. This model is inspired by the 2012 paper "Moving Beyond Deterrence: The Effectiveness of Raising the Expected Utility of Abstaining from Terrorism in Israel", by Laura Dugan and Erica Chenoweth, which examined the effect of different Israeli actions on terrorist attacks using logistic regression. I utilize two kinds of agents, Palestinians and the Israeli government, and explore the impact of Israeli actions and Palestinian satisfaction on the number of attacks. To test parameter selection with more than 11,000 possible configurations, I scaled the modeling using both MPI and AWS Lambda functions. Future directions for this project include increasing the complexity of the model to include Israeli terrorist attacks and add nuance to the Palestinian actors and creating Mesa extensions which use Dask and Dask-CUDA to improve the ability of Mesa models to parallelize.   
  
  [Github Repo](https://github.com/natalie-ayers/large_scale_agent_based_counterterrorism)  
 
<div style="text-align: left">
  <a href="https://www.youtube.com/watch?v=8I1WLeRj9hM" target="_blank"><img src="http://img.youtube.com/vi/8I1WLeRj9hM/0.jpg" 
alt="Video Presentation" width="540" height="380" border="10" >
    <figcaption>Video Presentation</figcaption>
  </a>
</div>
  
    
    
## Cook County Gunshot Homicide and Opioid Deaths  
  
 A Tableau dashboard and presentation gunshot homicides and opioid deaths in context of Chicago demographic, budget, geographic, leadership, and crime data. Developed while interning for the Cook County Medical Examiner, Dr. Ponni Arunkumar, in 2021.   

<div style="text-align: left">
  <a href="https://public.tableau.com/app/profile/natalie.ayers/viz/CookCountyGunshotHomicideandOpioidDeaths/GunandOpioidDeaths">
    <img src="./assets/cook-county-me-tableau.png" alt="Tableau Dashboard"
    style="width:540px;height:300px;">
    <figcaption>Tableau Dashboard</figcaption>
   </a>
</div>  
  
&nbsp;
  
<div style="text-align: left">
  <a href="https://docs.google.com/presentation/d/15MvU1IsGYTSDqNEzOoKX-G8zy4eZfAKL26h_HxnBu44/edit?usp=sharing">
    <img src="./assets/cook-count-me-presentation.png" alt="Presentation"
    style="width:540px;height:300px;">
    <figcaption>Presentation</figcaption>
   </a>
</div>


## Satellite Crop Type Mapping Tutorial (written for Geo4Dev Initiative)

Written while I was working with the [Center for Effective Global Action](https://cega.berkeley.edu/) on [Geospatial Analysis for Development](https://www.geo4.dev/), an initiative "to promote the use of geospatial and remote sensing data and technologies for global development research", this Python tutorial provides guidance on creating a machine learning model to identify crop types from satellite imagery and other earth observation data. For users with a sample of known crop locations, the tutorial demonstrates and describes the steps required to train a model on the known samples and predict crop locations for a wider area of interest.

<div style="text-align: left">
  <a href="https://learn.geo4.dev/Satellite%20Crop%20Mapping.html">
    <img src="./assets/geo4dev_malawi_gcvi.png" alt="Sentinel-2 GCVI in Malawi"
    style="width:540px;height:300px;">
    <figcaption>GCVI Levels from Sentinel-2 Satellite Imagery in Malawi</figcaption>
   </a>
</div>

[Tutorial](https://learn.geo4.dev/Satellite%20Crop%20Mapping.html)
