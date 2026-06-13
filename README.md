# Churn-analysis-project
E-commerce customer churn analysis project data: https://www.kaggle.com/datasets/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction/data

# Customer Churn Prediction: From Business Problem to Machine Learning Solution

## Why I Chose This Project

During my time working with Marketing teams at Twinkl, customer acquisition, retention, and churn were some of the most important metrics we monitored.

A business can spend significant resources acquiring new customers, but sustainable growth depends on keeping existing customers engaged. This naturally led me to explore churn prediction, one of the most common and valuable use cases in data science.

The objective of this project was not simply to build a machine learning model. Instead, I wanted to follow the same process that would be used in a real business environment:

1. Understand the business problem.
2. Explore and clean the data.
3. Create meaningful features.
4. Compare multiple machine learning approaches.
5. Translate model outputs into actionable business recommendations.

---

## Project Workflow

### Step 1: Understanding the Data

Before building any model, it is important to understand the customers and the available information.

I explored:

* Customer demographics
* Purchase behaviour
* Engagement metrics
* Customer experience indicators

I also investigated missing values and data quality issues to ensure reliable analysis.

### Interactive Visualisations

- [Categorical Distributions](https://smahi3003.github.io/Churn-Prediction-ML/interactive_plots/categorical_distributions.html)

- [Categorical Distributions with Churn](https://smahi3003.github.io/Churn-Prediction-ML/interactive_plots/categorical_distributions_with_churn.html)

### Step 2: Data Cleaning

Machine learning models depend heavily on data quality.

Key cleaning steps included:

* Handling missing values using median imputation.
* Removing unnecessary identifiers such as Customer ID.
* Standardising data formats.
* Validating data quality after cleaning.

### Step 3: Feature Engineering

Raw data often does not contain all the information a model needs.

To improve predictive performance, I:

* Applied one-hot encoding to categorical variables.
* Created interaction features.
* Analysed correlations between variables.
* Identified the strongest churn indicators.

Feature engineering is often where business knowledge and technical skills come together.

### Step 4: Model Comparison

Rather than selecting a model immediately, I compared multiple approaches.

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score

Because churn datasets are usually imbalanced, Recall and F1 Score were especially important.

### Step 5: XGBoost

After comparing traditional models, I implemented XGBoost.

Why XGBoost?

* Strong performance on structured business data.
* Handles complex relationships effectively.
* Widely used in industry.
* Robust against overfitting when configured correctly.

XGBoost is commonly used in customer retention, fraud detection, credit risk, and recommendation systems.

---

## Key Learnings

This project reinforced an important lesson:

Machine learning is only a small part of solving a business problem.

The majority of effort is spent understanding the data, improving data quality, engineering meaningful features, and translating findings into decisions that stakeholders can act upon.

A model may predict who will churn, but the real value comes from understanding why customers leave and what actions can be taken to retain them.

---

## Business Impact

If implemented in a real organisation, this approach could help:

* Reduce customer churn.
* Improve retention campaigns.
* Increase customer lifetime value.
* Prioritise high-risk customers.
* Support data-driven marketing decisions.

The ultimate goal is not prediction itself, but helping businesses build stronger relationships with their customers.
