# Quantifying Finfluencer Influence on Generation Z Investment Decisions using Multiple Linear Regression

## Project Overview
This repository contains the research, data analysis, and implementation code for the project **"Quantifying Finfluencer Influence on Generation Z Investment Decisions"**. This work was developed as a semester-long project for the course **Business Research and Data Mining (AF3008)** at **FAST National University of Computing and Emerging Sciences (NUCES)**, Islamabad.

**Author:** Muhammad Haris Khan  
**Academic Standing:** BS Financial Technologies (BSFT), 6th Semester  
**Instructor:** Dr. Usama Arshad  

---

## Abstract
The democratization of financial markets through social networks has introduced significant risks for Generation Z retail investors . This study utilizes a micro-behavioral framework and Multiple Linear Regression (MLR) to isolate the impact of "finfluencers" on individual investment execution . Using an augmented dataset of 546 verified investors, the model confirms that digital influencer trust statistically overrides foundational financial literacy in driving aggressive trading behavior.

## Key Features & Methodology
The project follows a structured analytical pipeline implemented in Python:

* **Data Collection:** Primary data gathered from 546 Gen Z retail investors using a 5-point Likert scale.
* **Variable Selection:** 
    * **Independent Variables (IVs):** Social Media Exposure (SME), Influencer Credibility & Trust (ICT), Herding Behavior (HB), and Overconfidence (OC) .
    * **Control Variables (CVs):** Financial Literacy (FL) and Investment Experience (IE).
    * **Dependent Variable:** Aggressive Investor Behavior (AIB) [cite: 150].
* **Statistical Engine:** Ordinary Least Squares (OLS) regression used to compute mathematical weights ($eta$) for each predictor.

## Results Summary
* **Predictive Power:** The model explains **64.5% of the variance** in aggressive behavior ($R^{2}=0.645$).
* **Dominant Predictors:**
    * **Influencer Trust (ICT):** $eta = 0.5953$ (Most significant positive driver).
    * **Investment Experience (IE):** $eta = -0.4530$ (Primary protective factor).
* **Model Accuracy:** Achieved a **59.56% improvement** in predictive accuracy over baseline methods.
* **The Literacy Paradox:** Financial Literacy (FL) did not independently satisfy the significance threshold, suggesting knowledge alone is often insufficient to counter emotional and algorithmic "nudges".

## Implementation Details
The analysis was executed in a **Python 3.10** environment. 
* **Pandas & NumPy:** Data cleaning, vectorization, and preprocessing.
* **Scikit-learn:** Data partitioning (436 training / 110 testing samples).
* **Statsmodels:** OLS regression and diagnostic tests (p-values, VIF, T-statistics).
* **Matplotlib & Seaborn:** Visualization of Normal Q-Q plots, Correlation Heatmaps, and Forest Plots.

---
*This project was submitted in fulfillment of the requirements for AF3008 - Business Research and Data Mining.*
