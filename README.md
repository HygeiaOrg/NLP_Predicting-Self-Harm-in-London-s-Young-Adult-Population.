### Omdena London Chapter: NLP_Predicting-Self-Harm-in-London-s-Young-Adult-Population.

## Background

Omdena is a non-profit group of developers. Local Chapters enable aspiring developers to collaborate with SME's on local social challenges.   

## Content
Self-harm in Children and Young Persons (CYP) aged between 10-24 increased during the Covid pandemic (ONS 2022). More broadly the incidence of mental health conditions in the CYP population has increased from 1-in-9 pre-pandemic to 1-in-6. As such the most recent Global Burden of Disease study published in the Lancet (2022) recommended urgent policy action to address this crisis. Data indicates young girls/adults are particularly vulnerable. A 2018-20 study of ambulance data in wales indicates only 63% of ambulance call-outs related to mental health conditions actually presented to an A&E department. Only 23% of those presenting to A&E were actually admitted. Does this highlight the tip of the iceberg?

! [Global Burden of Disease]()

## The Problem

We can infer from the wales (2018-20) ambulance data that hospital records underestimate self-harm in the community. Furthermore, clinicians are reluctant to code a mental health diagnosis because they are reluctant to label young adults. So coded mental health conditions, such as depression and eating disorders are surely under-reported in their Electronic Patient Records (EPR). However, Natural Language Processing (NLP) techniques can be applied to free text fields within EPR systems, inc. treatment summaries and discharge plans. The same NLP techniques can be applied to social media - a major social outlet for children and young adults.

The challenge is not only in developing AI capabilities but accessing and training predictive models on EPR training data. The recent application of Med-Bert NLP models to the open-sourced MIMIC II EPR data set is very exciting. However, London’s Integrated Health Sytems lack data science capabilities to leverage such innovations.

This project aims to add case study-based knowledge to the Omdena community and the wider National Health Service (NHS) python developer community: NHS-Pycom & NHS AI Labs

## Objective

The primary objective is to develop NLP skills (case study) for project participants. 

The project’s deliverables will be phased. In the first phase, weeks 1-to-4, project participants will scrape social media channels where age, sex and location can be determined as aged between 10-24, female and living in London. The data pipeline will be open-sourced on Github. But the main challenge will be accessing hospital and ambulance data, which will be done in phase two, weeks 5-to-8.  The project team will leverage subject matter expertise to find, wrangle and label Central & Northwest London ambulance data. This project intends to access and extract ambulance records via the NHS API:

- https://digital.nhs.uk/developer
- https://discover-now.co.uk/ 

## Project Goals

Research Question: For 10-24yr old females living in London does the topic of eating disorders predict self-harm?  

The project goals are listed overleaf; 1-to-3 will be done over the first phase, leaving regression analysis, feature engineering and optimisation for phase two. The target is **self-harm injury** recorded in ambulance data.  

# Phase I
1. Data pipeline for scraping social media;
2. Data set representative of Children & Young Adult Women aged 10-24, living in London.            
3. Sentiment Analysis 

# Phase II 
4. Regression analysis: is there any correlation between topic, sentiment and self-harm?

## Project Output
Project team envisage a set of time-series sentiment scores by topic where the central theme is eating disorder mapped to Central and Northwest London ambulance call-out data for self-harm/injury.  

