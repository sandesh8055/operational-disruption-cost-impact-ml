# Operational Disruption & Cost Impact Prediction Using Machine Learning

## Overview
Operational environments such as transportation hubs, infrastructure systems,
and large IT estates are vulnerable to disruptions caused by environmental,
system, and human factors. Even infrequent disruptions can lead to
disproportionately high operational and financial impact.

This project demonstrates how machine learning can be used responsibly
as a **decision-support tool** to:
- Predict the likelihood of operational disruptions
- Estimate the potential cost impact of such disruptions

The focus is on **interpretability, reasoning, and real-world applicability**
rather than maximizing model complexity or accuracy.

---

## Problem Framing
The project addresses two key operational questions:

1. *Is a disruption likely to occur under given operational conditions?*
2. *If a disruption occurs, what is the potential cost impact?*

By separating these objectives, the project mirrors real-world
decision-making workflows where risk assessment and impact estimation
are handled as distinct but related tasks.

---

## Data Strategy
Due to the sensitive and proprietary nature of real operational data,
a **synthetic dataset** is generated to simulate realistic operational scenarios.

The dataset includes:
- Environmental factors (e.g., weather severity)
- System conditions (e.g., system load)
- Human factors (e.g., staffing level)
- Incident characteristics
- Operational delays
- Disruption outcomes
- Estimated cost impact

Synthetic data generation allows transparent control over assumptions
and encourages explicit reasoning about cause–effect relationships.

---

## Methodology

### Exploratory Data Analysis (EDA)
EDA is used to identify:
- Factors associated with higher disruption likelihood
- Relationships between delays, disruptions, and cost impact
- Early operational risk signals

The analysis emphasizes **insight generation** rather than exhaustive visualization.

---

### Modeling Approach
Two simple and interpretable models are used:

- **Logistic Regression** for disruption prediction (classification)
- **Linear Regression** for cost impact estimation (regression)

These models are intentionally chosen to:
- Maximize transparency and explainability
- Support trust and adoption in operational environments
- Avoid black-box decision-making in high-stakes systems

---

## Evaluation
Model performance is evaluated using:
- Classification metrics and confusion matrix for disruption prediction
- MAE and RMSE for cost estimation

Evaluation focuses on **practical usefulness** rather than absolute precision.
In operational contexts, understanding trade-offs (e.g., false negatives vs false positives)
is often more important than marginal accuracy improvements.

---

## Limitations & Ethical Considerations
- The dataset is synthetic and based on assumed relationships.
- Real-world operational data may contain noise, bias, and unexpected dependencies.
- Model outputs should not be used as the sole basis for operational decisions.

Machine learning is positioned as a **supporting tool for human decision-makers**,
not as a replacement for human judgment.

---

## Conclusion
This project illustrates a responsible application of machine learning
to operational disruption and cost impact analysis.

By prioritizing problem framing, interpretability, and limitations,
the project highlights how ML can support proactive, risk-aware decision-making
in complex real-world systems.

---

## Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
## Author
Sandesh Duduskar
