# Monitoring Blood Pressure and Glycemia in Patients with Comorbid Type 2 Diabetes Mellitus and Arterial Hypertension

This project analyzes data from a retrospective study on the self-monitoring of blood glucose (BG) and blood pressure (BP) levels in patients with type 2 diabetes mellitus (T2DM) and arterial hypertension (AH). The primary goal is to explore how regular self-monitoring of BP using a mobile platform affects patients' management of these chronic conditions over time.

## Study context

T2DM and AH are highly prevalent chronic diseases, and the interaction between poorly controlled BG and BP can lead to severe complications. This project examines the effectiveness of real-time monitoring via a mobile platform on the management of these conditions over a six-month follow-up period. The control group data comes from patients who did not engage in BP monitoring over the course of about two years.

## Key objectives

- To analyze changes in BP and BG levels in response to the introduction of self-monitoring via a mobile platform.
To investigate the relationships between BG and BP levels over time and the impact of digital health interventions.
- To compare outcomes between patients who monitored BP and those who did not, to assess the effectiveness of digital health tools.

## Dataset

- mean_BP: Monthly average blood pressure levels across a 30-day interval.
- mean_BG: Monthly average blood glucose levels across a 30-day interval.
- time_centered_bp: A time variable centered around the start of BP monitoring for each patient (ranges from -6 to 6).

Other variables include sociodemographic information, clinical history, and self-reported health measures.

## Statistical methods

- Descriptive statistics: Summarizing the dataset to explore key trends in BP and BG levels.
- Correlation analysis: Investigating the relationships between BP and BG over time.
- Regression models: Evaluating the effect of the mobile platform on BP and BG levels while accounting for sociodemographic factors.
- Group comparison tests: Assessing differences between the experimental group (with BP monitoring) and the control group (without BP monitoring).

## Key findings

- Blood pressure monitoring: Patients who used the mobile platform to monitor their BP showed improvements in controlling both BP and BG levels over time.
- Bidirectional relationships: The data suggest a bidirectional relationship between elevated BG and BP, where poor control of one exacerbates the other.
- Digital health impact: The mobile platform provided significant benefits in managing hypertension and diabetes, enhancing patients' ability to track and control these chronic conditions.

## Requirements

To replicate the analysis, the following software and libraries are required:

- R (version 4.4.0 or later)
- R libraries: ggplot2, dplyr, tidyr, readxl, lme4
