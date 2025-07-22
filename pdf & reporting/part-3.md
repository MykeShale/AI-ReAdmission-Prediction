# Part 3: Critical Thinking (20 points)

## Ethics & Bias (10 points)

**How might biased training data affect patient outcomes in the case study?**

Biased training data can lead to unfair or inaccurate predictions for certain patient groups. For example, if the data underrepresents minorities or specific age groups, the model may not learn patterns relevant to those populations, resulting in poorer care, missed readmission risks, or unequal treatment recommendations.

**Suggest 1 strategy to mitigate this bias.**

One strategy is to perform data auditing and rebalancing: regularly analyze the dataset for representation gaps and use techniques such as oversampling, undersampling, or synthetic data generation to ensure all patient groups are adequately represented before training the model.

---

## Trade-offs (10 points)

**Discuss the trade-off between model interpretability and accuracy in healthcare.**

Highly accurate models (e.g., deep neural networks) are often complex and difficult to interpret, making it challenging for clinicians to understand or trust predictions. Simpler models (e.g., logistic regression) are more interpretable but may sacrifice some predictive accuracy. In healthcare, interpretability is crucial for transparency, regulatory compliance, and clinician trust, so a balance must be struck between accuracy and explainability.

**If the hospital has limited computational resources, how might this impact model choice?**

Limited computational resources may require choosing simpler, less resource-intensive models