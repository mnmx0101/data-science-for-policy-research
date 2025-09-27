# Data Science: Tools & Projects

Welcome to this repository of resources and projects demonstrating the application of data science.  
This collection is designed to provide **practical examples** and **reusable code** for analyzing complex problems with modern data tools.  

It reflects the know-how and skills I have developed in my role as a researcher and data scientist at the **Food and Agriculture Organization (FAO)**.  
The goal is to share a **practical, ready-to-use toolkit** for anyone interested in applying quantitative analysis to inform **policy decisions**.

---

## About This Repository

This repository is a practical guide to the **data science workflow**, providing reusable code and project examples.  
It is structured in three phases, each designed to build upon the last:

- **Phase 1: Foundations**  
  Covers the essential skills for any data-centric role, focusing on how to manipulate, explore, and visualize data to transform it from raw format into meaningful insight.

- **Phase 2: Applied Methods**  
  Introduces advanced techniques that allow for prediction, pattern discovery, and causal analysis. The focus is on applying machine learning, NLP, and other advanced tools to answer complex questions.

- **Phase 3: Project Development**  
  Synthesizes all skills into the creation of end-to-end projects and data-driven tools, emphasizing translation of findings into actionable outcomes.

The objective is to bridge the gap between **analytical methods** and **real-world policy challenges**.

---

## Repository Organization

- **/tutorials** – Step-by-step Jupyter notebooks on core concepts  
- **/projects** – End-to-end analyses of real-world problems  
- **/resources** – Curated references and readings for deeper exploration  

---

## Toolkit & Methods Covered

### Phase 1: Foundational Tools
- **Python Fundamentals**: variables, control flow, functions, reusable code  
- **Data Wrangling & Analysis**: pandas for structuring and transforming raw data  
- **Data Cleaning & EDA**: handling missing values, outliers, exploratory analysis  
- **Data Visualization**: static plots (matplotlib, seaborn) and interactive (plotly)  
- **Data Acquisition**: APIs and web scraping with BeautifulSoup  
- **Statistical Analysis**: regression and modeling with statsmodels  

### Phase 2: Applied Methods & Advanced Topics
- **Machine Learning**: scikit-learn models (Random Forest, Gradient Boosting)  
- **Model Evaluation, Fairness & Explainable AI**: accuracy, bias auditing (fairlearn), interpretability (SHAP, feature importance)  
- **Natural Language Processing (NLP)**: spaCy and Hugging Face transformers for text extraction, themes, and sentiment  
- **Geospatial Analysis**: geopandas for mapping and spatial analytics  
- **Causal Inference**: methods like Difference-in-Differences and Matching for policy evaluation  
- **Large Language Models (LLMs)**: advanced summarization, thematic analysis, document processing, chatbot development  
- **Responsible AI**: transparency, accountability, and fairness in sensitive domains  

### Phase 3: Applied Policy Projects & Tool Development
- **End-to-End Project Workflow**: from scoping a question to communicating results  
- **Dashboarding & Tool Development**: real-time monitoring tools with Streamlit/Dash  
- **Policy Brief Communication**: translating results into concise, non-technical outputs  

---

## Guideline for Project Development

1. **Scope the Question**  
   Start with a specific, measurable, and policy-relevant question.  
   Example: *"What is the causal impact of a conditional cash transfer program on school attendance rates in District A?"*

2. **Acquire and Prepare Data**  
   Gather, clean, and integrate diverse sources (survey data, remote sensing, administrative records).  
   Real-world data is messy — persistence and creativity are key.

3. **Select Methods**  
   Match tools to questions: machine learning for prediction, causal inference for impact evaluation, geospatial analysis for resource allocation.

4. **Analyze and Interpret**  
   Go beyond numbers. Explain not only what results show but why they matter in context.

5. **Communicate for Impact**  
   Present findings clearly to decision-makers via briefs, dashboards, or reports.  
   Use visuals and concise writing to ensure results are actionable.

---

## Project: Evaluating Humanitarian Aid Responsiveness with AI-NLP and Causal Inference [*Link to sample project*](https://mnmx0101.github.io/chungmann_kim/files/ChungmannKim_IPCAID.pdf)

### Background and Objective

The effective allocation of humanitarian aid is critical for mitigating acute food security crises. However, it remains empirically unclear whether institutional crisis alerts, like the **Integrated Food Security Phase Classification (IPC)**, trigger a timely and sufficient aid response at the subnational level where crises are most acute. This has been historically difficult to assess due to the lack of granular data on financial flows, which are often contained in unstructured formats. This project's objective is to provide the first causal, subnational evaluation of this critical link in the humanitarian system.

---

### Methodology

A multi-stage research design was employed to overcome these data and analytical challenges.

* **Dataset Construction:** A novel, provincial-level panel dataset of humanitarian aid flows in Afghanistan was constructed from the UN's Financial Tracking Service. **Natural Language Processing (NLP)** and geospatial algorithms were used to systematically parse unstructured project descriptions, georeference financial flows to their final destinations, and classify their programmatic purpose. 💻
* **Causal Analysis:** A **Staggered Difference-in-Differences** model was used to estimate the causal impact of an escalation to a severe food security emergency (IPC Phase 4) on the volume and timing of aid allocation, controlling for potential confounding factors.

---

### Key Findings

The analysis reveals that while a crisis alert is an effective trigger, the subsequent response has critical shortcomings.

* An IPC alert is associated with a **rapid and statistically significant** increase in aid.
* However, this response is **transitory**, diminishing quickly after the initial months.
* The aid allocated is also **insufficient**, falling substantially short of the estimated per capita need (the "need gap").
* Finally, aid responsiveness **varies significantly** across different donors and funding types.

---

### Contribution and Impact

This research provides the **first granular, causal evidence** on subnational aid responsiveness to formal crisis signals. The findings offer a data-driven foundation for policymakers and humanitarian organizations to improve aid targeting, enhance transparency, and strengthen accountability in crisis response, highlighting the gap between signaling an emergency and sufficiently addressing it. 🌍

## Getting Started

Clone this repository:

```bash
git clone https://github.com/mnmx0101/data-science-for-policy-research.git
