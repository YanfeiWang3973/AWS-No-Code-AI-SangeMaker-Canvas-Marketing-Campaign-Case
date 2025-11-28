# 📢 Marketing Campaign Prediction with AWS SageMaker Canvas (No-Code ML)

## Overview

This project demonstrates how Amazon SageMaker Canvas can be used to build an end-to-end machine learning workflow for predicting customer conversion outcomes in a marketing campaign — all without writing any code.

The purpose of this project was to simulate a real-world marketing analytics scenario: identifying which prospects are likely to convert based on their web interaction behavior and lead profile data, enabling more efficient campaign targeting and resource allocation.

---

## 🎯 Project Objective

To build a classification model that predicts whether a prospect will convert (Converted = Yes/No) using integrated marketing and lead datasets, helping optimize marketing campaign effectiveness and improve conversion strategy.

---

## 🛠 Tools & Platform

* Amazon SageMaker Canvas
* AWS Data Wrangler
* No-code ML pipeline
* CSV-based structured datasets

---

## 📂 Dataset Description

Two datasets were used and joined:

### 1. Lead Dataset

Contained prospect profile information such as:

* ProspectID
* Lead source
* Demographic and qualification attributes
* Conversion label (Converted)

### 2. Web Marketing Dataset

Contained campaign interaction data, including:

* Web activity metrics
* Campaign engagement indicators
* Behavioral interaction patterns

The datasets were joined using **ProspectID** as the primary key to create a unified modeling dataset.

---

## 🔄 Workflow

1. Uploaded both datasets into SageMaker Canvas
2. Applied Data Wrangler to preprocess and structure data
3. Performed dataset integration using an OUTER JOIN on ProspectID
4. Created a merged dataset for modeling
5. Selected Converted as the target variable
6. Removed ProspectID as a non-predictive identifier
7. Trained a classification model using Quick Build
8. Evaluated model performance
9. Generated predictions for new prospects

---

## 📊 Model Evaluation

The model performance was analyzed using built-in evaluation tools, including:

* Confusion Matrix
* Classification Accuracy
* Precision, Recall, F1-score
* Feature Impact Analysis

These metrics provided insight into how effectively the model distinguished between prospects likely and unlikely to convert.

---

## ✅ Key Results & Insights

* Successfully integrated behavioral and lead data for predictive modeling
* The model demonstrated practical classification capability for campaign conversion prediction
* Certain behavioral features showed higher influence on conversion probability
* No-code ML significantly reduced setup time while maintaining analytical depth

---

## 💡 Learnings & Reflections

* Data quality and structure have significant impact on model reliability
* OUTER join preserved full customer behavior context, reducing potential bias
* SageMaker Canvas enables rapid experimentation for business-focused ML use cases
* Even no-code platforms require strong understanding of data logic and modeling concepts

---

## 🌍 Real-World Applications

This workflow can be adapted for:

* Targeted digital advertising
* Lead scoring and prioritization
* Customer acquisition optimization
* CRM-driven campaign strategy

---

## ⚠️ Limitations

* Limited control over model tuning parameters
* Dependence on platform-level service permissions
* Reduced transparency of model internals
* Performance tied to dataset representativeness

---

## 🚀 Future Improvements

* Compare Quick Build vs Standard Build performance
* Introduce feature engineering for improved accuracy
* Evaluate model stability across different campaigns
* Integrate real-time prediction pipelines

---

## 📌 Conclusion

This project highlights the feasibility of using Amazon SageMaker Canvas as a no-code solution for marketing campaign prediction. By integrating lead and behavioral data, the platform enabled efficient model development and predictive insights, demonstrating its value for data-driven marketing strategy without heavy technical overhead.

---

## 👩🏻‍💻 Author

Fei Wang
Data & Business Analytics

---

📂 *This project serves as a practical example of leveraging no-code machine learning for business decision-making and campaign optimization.*
