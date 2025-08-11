---
id: projects
title: Projects
---

## Intergroup Spatial Integration and Post-Conflict Recovery

Initial work as part of a broader research agenda to develop a novel dataset of urban intergroup integration in post-conflict societies and examine the impacts of physical integration on post-conflict recovery. The work below describes the process of collecting the dataset using Google Maps and historical maps to identify the locations of key religious, cultural, and administrative sites within each post-conflict urban area, and the creation of an intergroup spatial integration measure from these locations. It also demonstrates an initial exploratory analysis using this dataset to evaluate the mitigating impact of spatial integration on conflict following the withdrawal of peacekeepers from post-conflict regions, using the former Yugoslavia as a case study.


<div style="text-align: left">
   <a>
    <img src="ayers-poster-polmeth2025.png" alt="Intergroup Spatial Integration Poster"
    style="width:650px;height:490px;">
       <figcaption> Poster for Political Methodology Conference 2025</figcaption>
   </a>
</div>



<div style="clear: both"></div>

<br /><br />


## Computational Approaches to the Study of Ancient Greek Conflict

Initial work as part of a broader project studying the nature of conflict by applying modern conflict analysis theoretical frameworks and computational methodologies to Ancient Greek conflicts. The work below represents two strands of the computational arm of this research: (1) demonstrating the use of a BERT-based transformer model to generate contextual word embeddings from conflict-based texts and (2) developing a mixed-membership stochastic blockmodel of Greek city-state conflict. The transformer model was implemented in Python using Pytorch and visualized using UMAP with Tensorflow's Embedding Projector. The word embeddings show diverging usages for the same word over authors and time periods, providing avenues for further quantitative and qualitative analysis. The network model indicates that democracy may play a mixed role in driving conflict between and among group members. I'm in the process of further data collection to identify changing levels of democracy, fortifications, and material capabilities over time, which will allow for the same analysis using a dynamic mixed-membership blockmodel (dynMMSBM, Olivella et al. 2022).

<br />

<div style="text-align: left">
  <a href="https://github.com/natalie-ayers/ancient-greek-conflict/blob/main/PolMeth2023-Poster.pdf">
    <img src="polmeth-greek.jpg" alt="Computational Methods Ancient Greek Conflict Poster"
    style="width:650px;height:490px;">
     <figcaption>Poster for Political Methodology Conference 2023</figcaption>
   </a>
</div>

<div style="clear: both"></div>

<br /><br />

## Large-Scale Agent-Based Model of Israeli Counterterrorism

An agent-based model developed with Mesa in Python which models Palestinian sentiment, terrorist attacks, and Israeli counterterrorism actions. This model is inspired by the 2012 paper *"Moving Beyond Deterrence: The Effectiveness of Raising the Expected Utility of Abstaining from Terrorism in Israel"*, by Laura Dugan and Erica Chenoweth, which examined the effect of different Israeli actions on terrorist attacks using logistic regression. I utilize two kinds of agents, Palestinians and the Israeli government, and explore the impact of Israeli actions and Palestinian satisfaction on the number of attacks. To test parameter selection with more than 11,000 possible configurations, I scaled the modeling using both MPI and AWS Lambda functions. Future directions for this project include increasing the complexity of the model to include Israeli terrorist attacks and add nuance to the Palestinian actors and creating Mesa extensions which use Dask and Dask-CUDA to improve the ability of Mesa models to parallelize.

[Github Repo](https://github.com/natalie-ayers/large_scale_agent_based_counterterrorism)

<br />

<div style="text-align: left">
  <a href="https://www.youtube.com/watch?v=8I1WLeRj9hM" target="_blank">
    <img src="http://img.youtube.com/vi/8I1WLeRj9hM/0.jpg" 
    alt="Video Presentation" width="650" height="490" border="10" >
    <figcaption>Video Presentation</figcaption>
  </a>
</div>

<div style="clear: both"></div>

<br /><br />

## Cook County Gunshot Homicide and Opioid Deaths

A Tableau dashboard and presentation on gunshot homicides and opioid deaths in the context of Chicago demographic, budget, geographic, leadership, and crime data. Developed while interning for the Cook County Medical Examiner, Dr. Ponni Arunkumar, in 2021.

<br />

<div style="text-align: left">
  <a href="https://public.tableau.com/app/profile/natalie.ayers/viz/CookCountyGunshotHomicideandOpioidDeaths/GunandOpioidDeaths">
    <img src="cook-county-me-tableau.png" alt="Tableau Dashboard"
    style="width:650px;height:400px;">
    <figcaption>Tableau Dashboard</figcaption>
  </a>
</div>

<br />

<div style="text-align: left">
  <a href="https://docs.google.com/presentation/d/15MvU1IsGYTSDqNEzOoKX-G8zy4eZfAKL26h_HxnBu44/edit?usp=sharing">
    <img src="cook-count-me-presentation.png" alt="Presentation"
    style="width:650px;height:400px;">
    <figcaption>Presentation</figcaption>
  </a>
</div>

<div style="clear: both"></div>

<br /><br />

## Satellite Crop Type Mapping Tutorial (written for Geo4Dev Initiative)

<p>
Written while I was working with the 
<a href="https://cega.berkeley.edu/">Center for Effective Global Action</a> 
on <a href="https://www.geo4.dev/">Geospatial Analysis for Development</a>, an initiative "to promote the use of geospatial and remote sensing data and technologies for global development research”, this Python 
<a href="https://learn.geo4.dev/Satellite%20Crop%20Mapping.html">tutorial</a> 
provides guidance on creating a machine learning model to identify crop types from satellite imagery and other earth observation data. For users with a sample of known crop locations, the tutorial demonstrates and describes the steps required to train a model on the known samples and predict crop locations for a wider area of interest.
</p>

<br />

<div style="text-align: left">
  <a href="https://learn.geo4.dev/Satellite%20Crop%20Mapping.html">
    <img src="geo4dev_malawi_gcvi.png" alt="Sentinel-2 GCVI in Malawi"
    style="width:650px;height:400px;">
    <figcaption>GCVI Levels from Sentinel-2 Satellite Imagery in Malawi</figcaption>
  </a>
</div>









