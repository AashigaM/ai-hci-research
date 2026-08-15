# ai-hci-research

## Adolescent Human-AI Interaction & Behavioral Intentions Framework

**Google Colab Notebook:**  
https://colab.research.google.com/drive/1XFNCMGXhpy8edmgsFX3Wv7HSs7qMxYRB?usp=sharing

---

## Project Overview

This project is an independent computational HCI study exploring how high school students perceive and intend to use generative AI tools for learning.

Using survey microdata from 336 participants, I analyzed several factors related to technology adoption, including Perceived Usefulness (PU), Perceived Ease of Use (PEOU), Self-Efficacy (SE), and Social Influence (SN).

The main goal was to understand which factors are most strongly associated with students' intentions to use conversational AI for learning.

I also built a Python-based data analysis pipeline to clean the survey data, create composite variables, run statistical models, and visualize the results.

---

## Research Focus

This project focuses on the intersection of:

- Human-Computer Interaction (HCI)
- Generative AI
- Technology adoption
- Data science
- Statistical modeling
- Educational technology

The analysis is based on the Technology Acceptance Model (TAM) and related technology-adoption concepts.

---

## Technical Methods

### Data Processing

I used Python and Pandas to:

- Import and inspect the survey dataset
- Clean and organize the data
- Combine multi-item survey questions into composite variables
- Check the structure and quality of the data
- Prepare the dataset for statistical analysis

### Statistical Analysis

I used Statsmodels to perform multivariable Ordinary Least Squares (OLS) regression.

The regression models were used to examine how factors such as perceived usefulness, ease of use, self-efficacy, and social influence were associated with students' behavioral intentions to use generative AI for learning.

The analysis included:

- Regression coefficients
- Statistical significance
- Confidence intervals
- R-squared
- Correlation analysis

### Data Visualization

I used Matplotlib and Seaborn to create visualizations including:

- Correlation heatmaps
- Regression plots
- Confidence intervals
- Effect-size visualizations
- Distribution plots

---

## Key Findings

The main findings from the statistical analysis are presented in the accompanying Google Colab notebook.

The analysis focuses on identifying which technology-adoption factors have the strongest relationship with students' intentions to use generative AI for learning.

*This section will be updated with the final statistical results after the analysis and interpretation are complete.*

---

## Reproducibility

The analysis was developed in Python using Google Colab.

Main libraries include:

- Pandas
- NumPy
- Statsmodels
- Matplotlib
- Seaborn

The notebook contains the data-processing, statistical-analysis, and visualization steps used in the project.

---

## Limitations

This study uses observational survey data, so the results describe statistical associations rather than causal relationships.

The sample may also not represent all high school students, depending on how the original survey participants were recruited.

Because the study relies on self-reported responses, the results may also be affected by reporting or response bias.

---

## Author & Research Details

**Researcher:** Aashiga Moorthy  
**Project Type:** Independent Data Science & HCI Research  
**Year:** Summer 2026  
**Intended Major:** Computer Science
