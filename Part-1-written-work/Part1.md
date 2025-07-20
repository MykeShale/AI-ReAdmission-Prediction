# Part 1: Short Answer Questions (30 points)

---

## 1. Problem Definition (6 points)

**Hypothetical AI Problem:**  
**Predicting employee attrition in a large company**

**Objectives:**  
1. Identify employees at high risk of leaving the company.  
2. Reduce turnover rate through early intervention strategies.  
3. Improve HR decision-making using data-driven insights.

**Stakeholders:**  
- Human Resources (HR) Department  
- Company Management/Executives

**Key Performance Indicator (KPI):**  
- Attrition prediction accuracy – The percentage of correctly predicted cases of employee attrition.

---

## 2. Data Collection & Preprocessing (8 points)

**Data Sources:**  
1. Internal HR records (e.g., performance reviews, attendance, promotion history)  
2. Employee engagement survey results

**Potential Bias in Data:**  
- *Performance review bias* – Manager evaluations may be subjective and influenced by personal preferences, leading to inaccurate or skewed data.

**Preprocessing Steps:**  
1. Handle missing data – Impute missing values or remove incomplete records.  
2. Encode categorical variables – Use one-hot or label encoding.  
3. Normalize numerical features – Scale features like salary and years at company using Min-Max or Z-score normalization.

---

## 3. Model Development (8 points)

**Chosen Model:**  
- **Random Forest Classifier** – Handles both numerical and categorical data, robust to overfitting, and provides feature importance.

**Data Split Strategy:**  
- Training Set: 70%  
- Validation Set: 15%  
- Test Set: 15%

**Hyperparameters to Tune:**  
1. `n_estimators` – Number of trees in the forest.  
2. `max_depth` – Controls the depth of each tree to prevent overfitting.

---

## 4. Evaluation & Deployment (8 points)

**Evaluation Metrics:**  
1. **Precision** – Reduces false positives (i.e., wrongly labeling satisfied employees as at-risk).  
2. **Recall** – Helps capture most actual attrition cases for proactive HR action.

**Concept Drift:**  
- A change in the underlying data distribution over time that affects model performance (e.g., changes in employee behavior or job market conditions).

**Monitoring for Drift:**  
- Track model accuracy over time.  
- Use drift detection techniques like DDM (Drift Detection Method) or ADWIN.  
- Regularly retrain the model with new data.

**Technical Challenge – Scalability:**  
- As the business grows, the model must handle increasing data volume and support real-time predictions efficiently.
