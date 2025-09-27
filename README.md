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

## Project Example: Using AI to Follow the Money in a Humanitarian Crisis [*Link to sample project*](https://mnmx0101.github.io/chungmann_kim/files/ChungmannKim_IPCAID.pdf) 🇦🇫

**The Big Question:** When a food crisis hits a country like Afghanistan, we see headlines and hear about billions in aid. But does that money actually get to the specific regions where people are starving? For decades, answering this was nearly impossible.

**The Challenge:** The data is a mess. Information on where aid goes is buried in thousands of different reports, PDFs, and unstructured text files. There's no single, clean map of financial flows. 

---

**Your Mission: Become a Data Detective** 🕵️

This is where you come in. Your goal is to use cutting-edge data science to find the truth.

* **Unlock the Data:** First, you'll train a **Natural Language Processing (NLP)** model to read and understand thousands of humanitarian reports, automatically pulling out the key information: Who sent the money? How much was it? And most importantly, *where* did it go?
* **Build the Map:** Using this data, you'll construct something that has never existed before: a detailed, **subnational map of aid flows**, showing exactly which provinces received funding and when.
* **Find the Cause:** Finally, you'll use a powerful method called **Staggered Difference-in-Differences** to move beyond correlation. This allows you to prove whether the official crisis alerts are *actually causing* the flow of aid, or if something else is going on.

---

**What You'll Discover:**

Your analysis will likely reveal a complex story. You might find that aid does rush in after an emergency is declared, but that the amount is **critically insufficient** compared to the number of people in need. You could uncover that the response is **short-lived**, fading just when a region's crisis is far from over.

**Your Impact:**

This isn't just a technical exercise. By transforming messy data into clear, causal evidence, your work can provide organizations like the UN and major donors with the proof they need to **improve how aid is delivered**. This is how data science can enhance transparency, save money, and, ultimately, save lives. 🌍

---

## Getting Started

Clone this repository:

```bash
git clone https://github.com/mnmx0101/data-science-for-policy-research.git
