# Sex-Specific Risk Factors for Heart Disease: Advanced Logistic Regressions, Interaction Profiling & Stratified Machine Learning

## Interactive Document
[👉 CLICK HERE TO VIEW THE FULL INTERACTIVE REPORT](https://phyonyeinchan.github.io/sex-specific-heart-disease-factors/)

---

## Background & Objective
This project is strategically designed to align with advanced core methodological paradigms in cardiovascular and nutritional epidemiology.

Clinical and epidemiological evidence strongly indicates that biological sex serves as a pivotal determinant in the pathogenesis and progression of chronic conditions, particularly coronary heart diseases (CHD). The primary objective of this study is to implement Sex-Stratified Multivariable Logistic Regression models alongside multiplicative Product-Term Interaction Profiles to investigate whether traditional risk parameters (e.g., chronological aging, behavior-related smoking, systolic blood pressure, and metabolic markers) display differential cardiovascular risk trajectories between men and women. 

Furthermore, this study leverages advanced diagnostic metrics and state-of-the-art machine learning classification pipelines to establish precision risk stratification models optimized for sex-specific medical applications.

## Dataset
This study utilizes the landmark, prospective cohort from the **Framingham Heart Study**, capturing over 4,240 longitudinal observations across 15 distinct clinical attributes. 
* **Data Source:** [Framingham Cohort Master Repository](https://github.com) (Loaded dynamically via network stream inside the analytical pipeline to ensure automated reproducibility).

## Methods Used
### 1. Traditional Biostatistics & Stratified Epidemiology
- **Analytical Framework:** Sex-Stratified Prospective Analysis, Multivariable Confounding Adjustments.
- **Regression Framework:** Binary Logistic Regression models (`glm`) implementing log-odds multipliers evaluating 10-year Coronary Heart Disease ($CHD$) outcomes.
- **Interaction Assessments:** Explicit Product-Term Modeling (`Risk_Factor * Sex_Label`) evaluated via Wald statistics to mathematically verify formal effect modification thresholds.

### 2. Advanced Diagnostic Profiles & Visual Analytics
- **Variance Inflation Factor (VIF):** Computed multi-collinearity screenings via the `car` package to isolate independent diagnostic signals.
- **ROC-AUC Discriminative Curves:** Plotted stratified Receiver Operating Characteristic (ROC) vectors via `pROC` to score and contrast Area Under the Curve ($AUC$) parameters.
- **Alpha-Blended Density Distributions:** Utilized `ggplot2` smooth density profiling to capture structural physiological variations across cohorts.

### 3. State-of-the-Art Machine Learning (Medical AI)
- **Sex-Stratified Random Forests:** Deployed non-parametric ensemble forests (`randomForest`) analyzing Mean Decrease Gini profiles to uncover gender-specific clinical feature hierarchies.
- **Extreme Gradient Boosting (XGBoost):** Trained an optimized classification pipeline (`xgboost`) processing sparse model matrices across 100 boosting iterations.
- **Confusion Matrix Evaluation:** Deployed custom prevalence-weighted classification boundaries, validating performance via Balanced Accuracy, Sensitivity, and Specificity profiles inside `caret`.

## Key Findings & Comparative Metrics

### Regression Stratification Output:
- **Female Stratum Model:** Displays distinct beta slopes for chronological aging and systolic parameters, with unique sensitivity bounds.
- **Male Stratum Model:** Exhibits sharper absolute risk elevations at earlier life-course segments compared to age-matched females.
- **Interaction Diagnosis ($Age \times Sex$):** Statistically confirms ($p < 0.05$) that biological sex acts as a true structural effect modifier for continuous vascular aging tracks.

### Classification & Diagnostics Performance Summary:


| Diagnostic Framework | Female Cohort Performance | Male Cohort Performance | Global Machine Learning (XGBoost Pipeline) |
| :--- | :---: | :---: | :---: |
| **Model Discrimination (ROC-AUC)** | **AUC = 0.743** | **AUC = 0.704** | **AUC Validation Watchlist = 0.738** |
| **Multicollinearity Safety Check** | All VIF < 1.41 | All VIF < 1.38 | Controlled Sparse Grid Matrix |
| **ML Balanced Classification** | Gini Priority: Age, sysBP | Gini Priority: sysBP, Age | **Balanced Accuracy = 0.695 (Threshold = 0.22)** |

1. **Divergent Pathogenic Tracks:** Formal interaction term testing and stratified logistic tracking verify that cardiovascular risk scores do not scale uniformly. Aging and metabolic loads accumulate with structurally distinct coefficients across sexes, validating the methodological requirement to decouple male and female cohorts.
2. **Distinct Risk Hierarchies:** While classical regressions mark advanced aging and high systolic parameters as persistent risk drivers, stratified Machine Learning Gini profiles reveal subtle structural variations. For instance, metabolic profiles like serum glucose and total cholesterol occupy different priority spots between the male and female diagnostic branches.
3. **Optimized AI Risk Identification:** Traditional classification cutoffs ($0.50$) heavily under-report cardiovascular disease events due to baseline prevalence skewness. By deploying an optimized clinical threshold ($0.22$) via an XGBoost pipeline, the predictive framework reaches an optimal balance of Sensitivity and Specificity, proving highly stable for personalized precision stratifications.

## Portfolio Structure
- `sex_specific_analysis.Rmd`: Self-contained, fully documented R Markdown script executing raw stream loading, regression diagnostics, and automated modeling.
- `index.html`: Web-ready, fully knitted interactive HTML dashboard generated directly from the markdown pipeline.
- `README.md`: Executive summary detailing epidemiological context, analytical methods, and clinical performance data.
