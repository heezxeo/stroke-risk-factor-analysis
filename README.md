# Stroke Risk Factor Analysis
Predictive Analysis of Stroke Risk Factors using R 

## Introduction
This repository contains analysis on risk factors for Stroke patients using data from Kaggle.
> Programming Language: R /
> Tools: Tidyverse (ggplot, dplyr)

The repository has the following series of contents:
- Data (raw)
- R markdown code
- Final Report

## Problem Statement
Research has shown that if stroke is detected or diagnosed early, death and severe damage to the brain can be prevented in 85% of cases. Therefore, our group was motivated to utilise a dataset that collected different features from patients to predict which parameters may increase the risk of getting a stroke. 

The causal relationship found can be useful in suggesting solutions to decrease the likelihood of suffering from a stroke. Our group used a logistic regression model to investigate the possible causality between getting a stroke with 3 factors: Body Mass Index (BMI), residence type (urban or rural), and average glucose level.

### Benefits from Solution:
With the predictive risk factors, government looking to reducing stroke incidence can implement impactful policies that increases the citizen's health and reducing the stroke incidence. 

## Data Description
12 attributes of a patient have been provided in the dataset:
- id: unique identifier of the patient
- gender: “Male”, “Female” or “Other”
- age: age of the patient
- hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
- heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart
disease
- ever_married: “No” or “Yes”
- work_type: “children”, “Govt_jov”, “Never_worked”, “Private” or “Self-employed”
- Residence_type: “Rural” or “Urban”
- avg_glucose_level: average glucose level in blood of the patient
- bmi: body mass index of the patient
- smoking_status: “formerly smoked”, “never smoked”, “smokes” or “Unknown”
- stroke: 1 if the patient had a stroke , or 0 if not

The **predictive variables** can be grouped into three distinct types:
- Biological: gender, age
- Health: hypertension, heart_disease, avg_glucose_level, bmi
- Lifestyle: ever_married, work_type, Residence_type, smoking_status
