# Beauty Product Review Sentiment Analysis

## Week 1 Internship Project — YuvaIntern

**Author:** Krishna Gurudev  
**Track:** Data Science with Python Analyst Internship  
**Domain:** Beauty & Wellness  
**Project type:** Business problem definition + proposed analytics plan

### 1. Business Problem

Beauty brands and retailers receive large volumes of customer reviews. Star ratings summarize satisfaction but do not explain *why* customers are satisfied or dissatisfied.

This project proposes an NLP-based framework to:

- analyze review sentiment,
- identify recurring product-experience themes,
- compare sentiment across categories/products,
- detect potential pain points,
- translate review evidence into marketing/product questions.

### 2. Research Questions

1. What themes are most associated with positive and negative customer experiences?
2. How closely do review sentiment and star ratings agree?
3. Do sentiment patterns differ across product categories?
4. Which products show unusually negative themes despite acceptable average ratings?
5. Can review text predict coarse sentiment classes using an interpretable ML baseline?
6. How can the findings support marketing and product decisions without making causal claims?

### 3. Proposed Dataset

A possible public starting point is the Kaggle **Sephora Products and Skincare Reviews** dataset.

Dataset discovery:
https://www.kaggle.com/search?q=sephora

Before use, check the dataset's current license/terms, provenance, completeness, and representativeness.

### 4. Planned Workflow

1. Data acquisition and documentation
2. Data-quality audit
3. Exploratory data analysis
4. Text preprocessing
5. TF-IDF feature extraction
6. Baseline sentiment analysis
7. Logistic Regression / Linear SVM comparison
8. Topic or aspect discovery using NMF/LDA
9. Product/category aggregation
10. Error analysis
11. Business interpretation
12. Final report and reproducibility documentation

### 5. Suggested Repository Structure

```text
beauty-product-sentiment-analysis/
├── README.md
├── requirements.txt
├── .gitignore
├── data/
│   └── README.md
├── docs/
│   └── data_dictionary.md
├── notebooks/
│   └── 01_week1_problem_definition.ipynb
├── src/
│   └── text_preprocessing.py
└── reports/
    └── Week_1_Beauty_Wellness_Data_Science_Report.docx
```

### 6. Week 1 Status

Week 1 focuses on conceptual foundation, industry research, research questions, hypotheses, variables, and analysis design. Model results are intentionally not presented as completed results.

### 7. Reproducibility

Create a Python environment and install:

```bash
pip install -r requirements.txt
```

The notebook is a planning/starter notebook. When the dataset is added, keep raw data out of GitHub unless its license explicitly permits redistribution.

### 8. Research Sources

- McKinsey — State of Beauty 2025
- McKinsey — Future of Wellness 2025
- McKinsey — E-commerce and beauty
- Kaggle — Sephora Products and Skincare Reviews
- Research literature on sentiment analysis and recommendation systems

See the Week 1 DOCX report for the full reference list.
