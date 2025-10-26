
# 📘 Impact of Employee Emotions on Productivity with the Role of AI Policy

**Research-Based Project (FYP)**  
**Model:** Partial Least Squares (PLS) Regression  
**Author:** Muhammad Azhar  
**Guided by:** Crescentech Research Team  

---

## 🧭 Project Overview

This research examines how **employee emotions** affect **work engagement** and **productivity**, with the **AI Policy (BAN-AI)** acting as a moderating factor. Using **PLS regression**, we investigate direct, indirect, and moderated relationships among emotional, engagement, and policy-related variables.

---

## 📂 Project Structure

```
Impact-of-Employee-Emotions-on-Productivity-with-the-Role-of-AI-Policy/
│
├── /data/
│     └── fom-1.csv                      # Dataset (306 responses, 26 variables)
│
├── /notebooks/
│     └── analysis_final.ipynb           # Main analysis notebook
│
├── /output/
│     ├── Model_Results.xlsx             # Regression tables
│     ├── Moderation_PosEmotion_WorkEngagement.png
│     ├── Moderation_WorkEngagement_Productivity.png
│
└── README.md / README.html
```

---

## 🧠 Methodology

1. **Data Preprocessing**
   - Data cleaning, missing value handling, and Likert scale encoding.
2. **Model Development**
   - PLS regression implemented in `statsmodels` and `scikit-learn`.
3. **Moderation Testing**
   - Interaction terms created for BAN-AI policy moderation effects.
4. **Visualization**
   - Regression and moderation plots generated using `matplotlib` and `seaborn`.
5. **Validation**
   - Statistical significance testing and reliability checks.

---

## 📊 Key Results

| Output File | Description |
|--------------|-------------|
| `Model_Results.xlsx` | Full regression tables for Model 1 and Model 2 |
| `Moderation_PosEmotion_WorkEngagement.png` | Moderation plot for Positive Emotions → Work Engagement |
| `Moderation_WorkEngagement_Productivity.png` | Moderation plot for Work Engagement → Productivity |

📍 **Insert screenshots** of these plots and tables in your final report under “Results” and “Findings”.

---

## 📈 Interpretation Summary

- **Positive Emotions** significantly enhance **Work Engagement** (β = 0.18, p < 0.01).  
- **Work Engagement** positively influences **Productivity** (β = 0.36, p < 0.001).  
- **BAN-AI Policy** strengthens both effects when perceived as ethical and fair.  

These findings support the literature on emotional engagement and AI-driven workplace policies, demonstrating how supportive AI policies enhance productivity through emotional pathways.

---

## 🧩 How to Run the Analysis

1. Open the main notebook:

   ```bash
   notebooks/analysis_final.ipynb
   ```

2. Install dependencies:

   ```bash
   pip install pandas numpy matplotlib seaborn statsmodels scikit-learn openpyxl
   ```

3. Run all cells sequentially to generate results.  
4. Outputs will be saved automatically in the `/output/` folder.

---

## 📚 Research Paper Integration

When writing your report:

- **Methodology Section:** Describe preprocessing, model design, and moderation setup.  
- **Results Section:** Include regression tables from `Model_Results.xlsx`.  
- **Findings Section:** Add moderation plots (`.png` files).  
- **Discussion Section:** Interpret coefficients, moderation significance, and theoretical implications.

---

## 🏁 Conclusion

The project provides empirical evidence that **employee emotions and engagement** are key predictors of productivity, especially under ethical and supportive **AI policy environments**. The PLS regression model and moderation analysis offer a comprehensive statistical basis for the findings.


