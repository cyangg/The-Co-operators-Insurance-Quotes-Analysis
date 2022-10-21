# CASE STUDY: Bellabeat Fitness Data Analysis 

**Author: Henry Yang**

**Date: Sep 2022**

#

**The case study follows the six step data analysis process:**

### ❓ [Ask](#1-ask)
### 💻 [Prepare](#2-prepare)
### 🛠 [Process](#3-process)
### 📊 [Analyze](#4-analyze)
### 📋 [Share](#5-share)
### 🧗‍♀️ [Act](#6-act)

## Scenario
Since it was founded in 2013, Bellabeat has grown rapidly and quickly positioned itself as a tech-driven wellness company for women. The company has 5 focus products: bellabeat app, leaf, time, spring and bellabeat membership. Bellabeat is a successful small company, but they have the potential to become a larger player in the global smart device market. Our team have been asked to analyze smart device data to gain insight into how consumers are using their smart devices. The insights we discover will then help guide marketing strategy for the company.

## 1. Ask
💡 **BUSINESS TASK: Analyze Fitbit data to gain insight and help guide marketing strategy for Bellabeat to grow as a global player.**

Primary stakeholders: Urška Sršen and Sando Mur, executive team members.

Secondary stakeholders: Bellabeat marketing analytics team.

## 2. Prepare
Data Source: 33 participants FitBit Fitness Tracker Data from Mobius: https://www.kaggle.com/arashnic/fitbit

The dataset has 18 CSV. The data also follow a ROCCC approach:

- Reliability: The data is from 33 FitBit users who consented to the submission of personal tracker data and generated by from a distributed survey via Amazon Mechanical Turk. 
- Original: The data is from 33 FitBit users who consented to the submission of personal tracker data via Amazon  Mechanical Turk.
- Comprehensive: Data minute-level output for physical activity, heart rate, and sleep monitoring. While the data tracks many factors in the user activity and sleep, but the sample size is small and most data is recorded during certain days of the week. 
- Current: Data is from March 2016 to May 2016. Data is not current so the users habit may be different now. 
- Cited: Unknown. 

⛔ The dataset has limitations:

- Data collected from year 2016. Users' daily activity, fitness and sleeping habits, diet and food consumption may have changed since then, hence data may not be timely or relevant.
- Sample size of 30 female FitBit users is not representative of the entire female population.
- As data is collected in a survey, hence unable to ascertain the integrity or accuracy of data.

## 3. Process
I used Python to prepare and process the data.
### 3.1 Preparing the Environment
``` 
# import packages and alias
import numpy as np # data arrays
import pandas as pd # data structure and data analysis
import matplotlib as plt # data visualization
import datetime as dt # date time
```



















