# Project Development Exercise: From Question to Policy Impact

---

## 1. Scope the Question
The first step in any project is to ask a **specific, measurable, and policy-relevant question**.  
A good question should:  
- Be clearly defined and **narrow in scope**.  
- Have measurable outcomes.  
- Relate directly to a decision or policy challenge.  

**Example Questions:**  
- What is the causal impact of a conditional cash transfer program on school attendance rates in District A?  
- How does expanding public transit routes affect employment access in low-income neighborhoods?  
- What are the predictors of hospital readmissions, and which interventions might reduce them?  

The key is to ensure the question can guide method selection and data needs.

---

## 2. Acquire and Prepare Data
Once the question is clear, gather and process the necessary data.  

**Potential data sources:**  
- Administrative records (e.g., school enrollment, hospital visits).  
- Survey data (household, labor force, opinion polls).  
- Remote sensing and geospatial datasets (satellite imagery, GIS layers).  
- Open data portals, APIs, or web scraping.  

**Key tasks:**  
- **Cleaning**: handle missing values, outliers, duplicates.  
- **Integration**: combine multiple sources into a coherent dataset.  
- **Feature engineering**: create new variables to capture important concepts (e.g., poverty index, accessibility measures).  

Real-world data is often messy — persistence, creativity, and documentation are essential.

---

## 3. Select Methods
The methods should follow logically from the research question.  

- **Prediction tasks** (e.g., forecasting student dropout risk):  
  - Machine learning methods such as Random Forests, Gradient Boosting, or Neural Networks.  

- **Causal impact evaluation** (e.g., effect of a policy or program):  
  - Econometric or causal inference methods like Difference-in-Differences, Propensity Score Matching, Instrumental Variables, or Regression Discontinuity.  

- **Resource allocation or spatial planning**:  
  - Geospatial methods such as clustering, spatial regressions, or network analysis.  

The guiding principle: match the **method to the question**, rather than forcing the question into a pre-selected method.

---

## 4. Analyze and Interpret
After applying methods, focus on **interpreting results in context**.  

- Check assumptions and validate models (residuals, robustness checks).  
- Interpret coefficients and effects in plain language.  
- Ask whether results are consistent with theory and prior evidence.  
- Highlight uncertainty and limitations (confidence intervals, external validity).  

**Example:**  
Instead of reporting *“the program increased attendance by 5%”*, provide context:  
- Which groups benefited most?  
- Why might the effect differ across subgroups or regions?  
- What alternative explanations were considered and ruled out?  

---

## 5. Communicate for Impact
Analysis is most valuable when it informs decision-making.  

**Effective communication practices:**  
- **Clear policy briefs**: Summarize methods, findings, and recommendations concisely.  
- **Interactive dashboards**: Allow stakeholders to explore data in real time.  
- **Intuitive visualizations**: Use charts and maps that highlight the story behind the numbers.  
- **Concise writing**: Minimize jargon and emphasize clarity.  

**Final step:** Always connect back to the **original policy question**.  
- Did the analysis answer it?  
- What are the implications?  
- What actions should be considered next?  

---

## Summary
This exercise provides a structured workflow for developing a project from start to finish:  
1. Define a policy-relevant question.  
2. Acquire and prepare data.  
3. Select appropriate methods.  
4. Analyze and interpret results.  
5. Communicate insights for decision-making.  

The ultimate goal is to ensure data-driven analysis leads to **actionable, policy-relevant impact**.  
