# Machine_learning_project
# ✈️ Aircraft Incident Analysis using Machine Learning

## Overview

This project analyzes **historical aircraft incident and accident data** with the objective of studying the relationship between **aircraft models** and **accident severity**, with a particular focus on incidents involving **high numbers of casualties**.

The work is based on a structured dataset extracted from publicly available aviation accident records and is developed as part of an academic machine learning project.

---

## Dataset Description

The analysis relies on the dataset **`Aircraft_Incident_Dataset.csv`**, which contains detailed records of aircraft incidents and accidents worldwide.

Each row corresponds to a single incident and includes operational, technical, and casualty-related information.

### Main Variables

The dataset includes (non-exhaustive list):

* **Incident_Date**: Date of the incident
* **Aircaft_Model**: Aircraft manufacturer and model
* **Aircaft_Registration**: Aircraft registration number
* **Aircaft_Operator**: Airline or operator involved
* **Aircaft_Nature**: Type of operation (passenger, cargo, private, etc.)
* **Incident_Category**: Classification of the incident (accident, damage, etc.)
* **Incident_Cause(es)**: Reported cause(s) of the incident
* **Incident_Location**: Geographic location of the event
* **Aircaft_Damage_Type**: Level of damage sustained by the aircraft
* **Aircraft_Phase**: Phase of flight during the incident
* **Onboard_Crew**: Number of crew members onboard
* **Onboard_Passengers**: Number of passengers onboard
* **Onboard_Total**: Total number of persons onboard
* **Fatalities**: Number of fatalities
* **Ground_Casualties**: Casualties on the ground
* **Collision_Casualties**: Casualties due to collision

Missing values are present for some variables and are handled during preprocessing.

---

## Project Structure

The project follows the structure defined in the accompanying project report and notebooks:

* **Data preprocessing**

  * Cleaning and normalization of aircraft model names
  * Handling missing and inconsistent values
  * Selection of relevant features for analysis

* **Exploratory Data Analysis (EDA)**

  * Distribution of incidents by aircraft model
  * Analysis of fatality and casualty distributions
  * Identification of high-severity incidents

* **Feature Engineering**

  * Construction of severity indicators based on casualties
  * Encoding of categorical variables

* **Machine Learning Analysis**

  * Application of supervised and unsupervised learning methods
  * Analysis of correlations between aircraft models and accident severity

---

## Scope of the Study

This project focuses on:

* Correlational analysis between **aircraft models** and **incident severity**
* Identification of patterns associated with **high-casualty events**
* Statistical and machine learning-based exploration of historical accident data

The results are intended to support data-driven analysis and academic study of aviation incident records.

---

✈️ *Machine learning analysis of historical aircraft incident data*
