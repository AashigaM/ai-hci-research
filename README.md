# ai-hci-research

## Adolescent Human-AI Interaction & Behavioral Intentions Framework

**Google Colab Notebook:**  
https://colab.research.google.com/drive/1XFNCMGXhpy8edmgsFX3Wv7HSs7qMxYRB?usp=sharing

**Final Research Paper:**  
[📄 Download Full PDF Paper](./Aashiga_Moorthy_Generative_AI_HCI_Research.pdf)

---

## Project Overview

This project is an independent computational Human-Computer Interaction (HCI) and data science study exploring factors associated with students' intentions to use generative AI tools for learning.

Using survey microdata from 336 participants, I analyzed several technology-adoption factors, including Perceived Usefulness (PU), Perceived Ease of Use (PEOU), Self-Efficacy (SE), and Subjective Norms (SN).

The main goal was to understand which factors are most strongly associated with students' intentions to use conversational AI for learning.

I developed a Python-based data analysis pipeline to clean and organize the survey data, construct composite variables from multi-item measures, perform descriptive and statistical analyses, evaluate the regression model, and visualize the results.

The project combines Human-Computer Interaction, Human-AI Interaction, data science, and statistical computing to study how users perceive and choose to interact with emerging AI technologies.

---

## Research Focus

This project focuses on the intersection of:

- Human-Computer Interaction (HCI)
- Human-AI Interaction
- Generative AI
- Technology adoption
- Data science
- Statistical modeling
- Educational technology

The analysis is based on the Technology Acceptance Model (TAM) and related technology-adoption concepts, including perceived usefulness, perceived ease of use, self-efficacy, and subjective norms.

---

## Research Question

The primary research question was:

**What factors are most strongly associated with students' intentions to use generative AI for learning?**

The study examined whether Perceived Usefulness, Perceived Ease of Use, Self-Efficacy, and Subjective Norms were associated with Behavioral Intention when analyzed simultaneously.

Because this project uses observational secondary data, the findings describe statistical associations rather than causal relationships.

---

## Technical Methods

### Data Processing

I used Python and Pandas to:

- Import and inspect the survey dataset
- Examine the structure and data types
- Identify relevant variables
- Check missing and invalid values
- Clean and organize the data
- Combine multi-item survey questions into composite variables
- Prepare the final analysis dataset

### Statistical Analysis

I used Statsmodels to perform multivariable Ordinary Least Squares (OLS) regression.

The regression model examined how Perceived Usefulness, Perceived Ease of Use, Self-Efficacy, and Subjective Norms were associated with students' Behavioral Intention to use generative AI for learning.

The analysis included:

- Regression coefficients
- Standard errors
- t-statistics
- Statistical significance
- 95% confidence intervals
- R-squared and adjusted R-squared
- Correlation analysis
- Regression diagnostics

The primary statistical significance level was α = 0.05.

### Composite Variables

The primary constructs were calculated from multiple survey items using their arithmetic means:

- PU = (PU1 + PU2 + PU3 + PU4) / 4
- PEOU = (PEOU1 + PEOU2 + PEOU3 + PEOU4) / 4
- SE = (SE1 + SE2 + SE3) / 3
- SN = (SN1 + SN2 + SN3) / 3
- BI = (BI1 + BI2 + BI3 + BI4) / 4

### Data Visualization

I used Matplotlib and Seaborn to create visualizations including:

- Correlation heatmaps
- Regression plots
- Confidence intervals
- Effect-size visualizations
- Distribution plots

These visualizations were used to help interpret relationships among the primary constructs and communicate the statistical results.

---

## Key Findings

The final multivariable OLS regression model explained 63.7% of the variance in Behavioral Intention.

**R² = 0.637**  
**Adjusted R² = 0.632**  
**F(4, 331) = 144.9, p < 0.001**

The main findings were:

- **Perceived Usefulness (PU)** was the strongest predictor of Behavioral Intention (β = 0.438, p < 0.001).
- **Self-Efficacy (SE)** was the second strongest predictor (β = 0.324, p < 0.001).
- **Perceived Ease of Use (PEOU)** showed a statistically significant positive association with Behavioral Intention (β = 0.180, p = 0.002).
- **Subjective Norms (SN)** were not statistically significant after controlling for the other predictors (β = 0.029, p = 0.461).

Overall, the findings suggest that students' intentions to use generative AI for learning were more strongly associated with perceived usefulness, self-efficacy, and perceived ease of use than with perceived social expectations in this dataset.

These findings represent statistical associations and should not be interpreted as evidence of causal effects.

---

## Model Diagnostics

Regression diagnostics were included to evaluate the primary assumptions of the OLS model.

The analysis examined:

- Multicollinearity
- Autocorrelation
- Residual normality
- Influential observations
- Regression residuals

Selected diagnostic results included:

- Condition number: 55.1
- Durbin-Watson statistic: 1.747
- Omnibus statistic: 28.999
- Omnibus p-value: < 0.001
- Skewness: -0.507
- Kurtosis: 4.667
- Cook's distance remained below 0.5 across observations

Detailed diagnostic results and their interpretation are provided in the final research paper and Google Colab notebook.

---

## Reproducibility

The analysis was developed in Python using Google Colab.

Main libraries include:

- Pandas
- NumPy
- SciPy
- Statsmodels
- Matplotlib
- Seaborn

The notebook contains the data-processing, composite-variable construction, statistical-analysis, model-diagnostic, and visualization steps used in the project.

The research paper documents the methodology, statistical results, interpretation, limitations, and conclusions of the study.

The goal of the computational workflow is to make the analysis organized, transparent, and reproducible.

---

## Final Research Paper

The complete research manuscript is available as a PDF in this repository.

**[Read the Final Research Paper](./Aashiga_Moorthy_Generative_AI_HCI_Research.pdf)**

The paper includes:

- Research questions and hypotheses
- Research variables
- Dataset description
- Computational methods
- Data processing
- Composite-variable construction
- Statistical analysis
- Descriptive statistics
- OLS regression results
- Model diagnostics
- HCI implications
- Ethical considerations
- Limitations
- Conclusions
- References

---

## Limitations

This study uses observational survey data, so the results describe statistical associations rather than causal relationships.

The sample may also not represent all students, depending on how the original survey participants were recruited.

Because the study relies on self-reported responses, the results may also be affected by response bias or differences in how participants interpret rating scales.

I did not control the original survey design, participant recruitment, or data-collection process. Therefore, limitations of the original dataset may also affect the present analysis.

---

## Ethical Considerations

This project uses existing survey data and does not involve new participant recruitment or direct interaction with human participants.

The analysis is designed to:

- Use data appropriate for secondary analysis
- Report findings in aggregate
- Avoid exposing identifying participant information
- Respect applicable data-use requirements
- Properly acknowledge the original research and dataset
- Avoid uploading confidential participant-level information to the public repository

---

## Author & Research Details

**Researcher:** Aashiga Moorthy  
**Project Type:** Independent Data Science & HCI Research  
**Year:** Summer 2026  
**Intended Major:** Computer Science
