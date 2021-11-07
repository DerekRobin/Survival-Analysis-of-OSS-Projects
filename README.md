# CSC578B-Project
This repository contains materials related to the course project for UVic CSC578B.

At this point we have not determined what our project is on.  
However one idea is to replicate or modify the study found in refs/pdfs/CheatingDeath.pdf.  
This study applies the [Kaplan-Meiers estimator](https://en.wikipedia.org/wiki/Kaplan%E2%80%93Meier_estimator) and the [Cox Proportional-Hazards
model](https://en.wikipedia.org/wiki/Proportional_hazards_model#The_Cox_model) to the [popular-3k-python dataset](https://annex.softwareheritage.org/public/dataset/graph/latest/popular-3k-python/sql/) which is a subset of the [Software Heritage Graph](https://annex.softwareheritage.org/public/dataset/).  

A straight up replication of this study is one route we could go down. However, I believe that relating this study to course material, specifically Bayesian Inference, could produce interesting results. The paper found in refs/pdfs/BayesianSurvivalAnalysis.pdf outlines how to use Bayesian Inference for survival analysis using the STAN programming language and [this Jupyter Notebook](https://docs.pymc.io/notebooks/survival_analysis.html#:~:text=Bayesian%20Survival%20Analysis%C2%B6&text=Survival%20analysis%20studies%20the%20distribution,%2C%20engineering%2C%20and%20social%20science.&text=We%20illustrate%20these%20concepts%20by,from%20R%20's%20HSAUR%20package.) outlines how to do so using Python.

Motivation:
* We agree with authors' motivation (developers should understand attributes that correspond to long lasting projects). Therefore we want to see if the study was credible and if there were any gaps in the study.
* We want to see the differences between the Bayesian approach and the methods used in the paper. Do they both find the same thing?
* If we have time, we would like to see if there are other attributes that can predict longevity of a project (or maybe test other threshold values)

Resources:
https://rviews.rstudio.com/2017/09/25/survival-analysis-with-r/ - Survival Analysis in R
