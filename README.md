# CivicEye-Intelligent-Citizen-Complaint-Classification-and-Priority-System

**CivicEye** is an AI-powered complaint classification and priority prediction system designed to improve urban grievance redressal.

The system automatically:

* Classifies civic complaints into categories
* Predicts complaint priority (High / Medium / Low)
* Provides a simple Streamlit-based interface for interaction

CivicEye aims to support smart city initiatives by enabling faster, data-driven decision making in municipal governance.


## Problem Statement

Manual handling of civic complaints leads to:

* Delayed response times
* Misclassification of issues
* Lack of prioritization
* Inefficient grievance management

CivicEye solves this by using **Natural Language Processing (NLP)** and **Machine Learning** to automate complaint understanding and prioritization.


## Key Features

✅ Automatic Complaint Category Classification

✅ Priority Prediction (High / Medium / Low)

✅ SBERT-based Semantic Text Embeddings

✅ Pre-trained ML Model Integration

✅ Streamlit Web Interface

✅ Model Persistence using Pickle

✅ Modular and Scalable Architecture

## Technologies Used

### Backend & ML

* Python 3.11
* Scikit-learn
* Sentence-Transformers (SBERT)
* NumPy
* Pandas
* Pickle

### Frontend

* Streamlit

### Machine Learning Models

* Logistic Regression
* Random Forest
* Support Vector Machine
* Naive Bayes

## NLP & Embedding Approach

Instead of traditional TF-IDF, CivicEye uses:

### SBERT (Sentence-BERT)

* Generates semantic sentence embeddings
* Captures contextual meaning of complaints
* Improves classification accuracy
* Efficient for sentence comparison

This allows the system to understand complaints even if wording differs but meaning is similar.


## Project Workflow

1. Data Collection (NYC 311 Civic Dataset)
2. Data Cleaning & Preprocessing
3. Text Embedding using SBERT
4. Model Training & Evaluation
5. Best Model Selection
6. Priority Prediction Logic
7. Model Saving (.pkl files)
8. Web App Integration using Streamlit

## How It Works

1. User sends a complaint in the email.
2. The complaint is converted into SBERT embedding.
3. The trained ML model predicts:

   * Complaint Category
   * Priority Level
4. Results are displayed instantly.


## Model Evaluation Metrics

Models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score

Best-performing model is saved using pickle for deployment.

## Architecture Diagram
<img width="960" height="720" alt="212222240101-Projectwork2-R2-W1-pres-Review2 pptx" src="https://github.com/user-attachments/assets/cc44ae9b-be88-483a-ac95-a448c52a581f" />



## SDG Alignment

CivicEye supports the following UN Sustainable Development Goals:

* **SDG 11:** Sustainable Cities & Communities
* **SDG 16:** Peace, Justice & Strong Institutions
* **SDG 9:** Industry, Innovation & Infrastructure


## Future Enhancements

* Real-time dashboard analytics
* Integration with government APIs
* Multilingual complaint support
* Mobile application version
* Email/SMS auto-notification system
* Cloud deployment (AWS / Azure)

## Output Screenshots

### Homepage

<img width="1916" height="767" alt="image" src="https://github.com/user-attachments/assets/e64e39a5-34c6-4650-9c43-1a41d24457ec" />

### Complaint emails without filter (all)

<img width="1918" height="706" alt="image" src="https://github.com/user-attachments/assets/7470015d-b115-4888-b078-4c6ae1d95aad" />

### Complaint emails with priority and category keyword filter

<img width="1919" height="690" alt="image" src="https://github.com/user-attachments/assets/5e855fba-a27a-4c1e-aaf7-5478f5261682" />

### Complaint summary by priority

<img width="1916" height="828" alt="image" src="https://github.com/user-attachments/assets/2d923b5b-83b8-4356-9fb6-d68d1e6320c1" />

### Complaint summary by category

<img width="1900" height="661" alt="image" src="https://github.com/user-attachments/assets/94ddbd73-d4c4-4209-91f1-39c333613897" />


## Conclusion

CivicEye demonstrates how AI and NLP can be applied to improve civic governance. By automating complaint classification and prioritization, the system enhances response efficiency and supports smarter urban management.


