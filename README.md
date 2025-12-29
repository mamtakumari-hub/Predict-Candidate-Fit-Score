
# Predict Candidate Fit Score

## 📌 Overview
This project predicts how well a candidate matches a job description
using NLP and supervised machine learning.

## 🎯 Objective To build a Python-based machine learning solution that 
compares candidate profiles with job descriptions and generates a 
fit score with explanations.

## Tech Stack
- Python
- Pandas
- NumPy
- scikit-learn
- NLTK

## Datasets
candidates.csv:
- candidate_id
- skills
- qualification
- experience_level
- job_role

jobs.csv:
- Job_Role
- Company
- Location
- Job Experience
- Skills/Description

## Approach
1. Clean and preprocess text data
2. Combine candidate and job features
3. Create candidate–job pairs with labels
4. Balance classes
5. Extract features using TF-IDF
6. Train Logistic Regression classifier
7. Evaluate using accuracy and classification report
8. Predict fit score (0–100%) with keyword explanation

## Model
TF-IDF + Logistic Regression (scikit-learn Pipeline)

## How to Run 
1. Open the notebook in Google Colab
2. Upload candidates.csv and jobs.csv
3. Run all cells from top to bottom
4. The trained model is saved as:
   job_candidate_matcher.pkl
5. Download model_metrics.csv

## Output
- Accuracy and performance metrics
- Fit score for candidate–job pair
- Key matching skills
- Saved trained model

## Example
Fit Score:73.43%
Key Matching Factors: ['python', 'machine', 'learning']

## 👩‍💻 Author 
Mamta Kumari
