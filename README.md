# Sentiment Analysis of Thai Text Regarding Broker Services on Pantip

## 📌 Overview
This repository contains the code and report for my Senior Project in Statistics at King Mongkut's University of Technology Thonburi (KMUTT). The project focuses on applying Natural Language Processing (NLP) and Machine Learning techniques to extract actionable business insights from unstructured Thai text.

## 🎯 Objective
To analyze user comments on Pantip.com regarding stock broker services, categorize them into specific topics (e.g., Trading, Service, System Issues), and classify the sentiment (Positive, Neutral, Negative) to help businesses improve their operations.

## 📊 Dataset
* **Source:** Scraped from Pantip.com (Thailand's largest webboard).
* **Size:** 1,327 unstructured Thai comments.
* **Data Balancing:** Addressed class imbalance using the **Undersampling** technique, resulting in a balanced dataset of 909 comments for model training and testing.

## 🛠️ Methodology & Tech Stack
* **Language:** Python
* **NLP Processing:** Utilized `PyThaiNLP` for Thai word tokenization and `TF-IDF` for text vectorization.
* **Modeling:** Built a **Lasso Logistic Regression** model.
* **Optimization:** Applied **Stratified 10-Fold Cross-Validation** to ensure robust model evaluation and tune hyperparameters.

## 📈 Key Results & Business Insights
The model achieved an **overall classification accuracy of 73.08%** (with an F1-Score of 0.84 for positive sentiment). 

Beyond technical metrics, the project successfully translated raw textual data into actionable management insights:
* **Topic Distribution:** Found that **62.02%** of users focused their discussions on "Trading", followed by "Service" (28.41%).
* **Sentiment Insights:** * Highlighted a critical operational bottleneck: **50.79%** of comments regarding **"System Issues"** were negative.
  * Identified a core strength: **49.81%** of comments regarding **"Service"** were positive.

## 📁 Repository Structure
* `/code`: Contains the Jupyter Notebook/Python scripts for data scraping, preprocessing, and modeling.
* `/report`: Contains the full academic Senior Project report (PDF).
