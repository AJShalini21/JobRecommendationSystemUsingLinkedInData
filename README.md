# Job Recommendation System Using LinkedIn Data

A machine learning–powered system that recommends jobs based on user-input skills using a cleaned LinkedIn dataset.

## Dataset

- **Source**: [Kaggle – LinkedIn Jobs & Skills 2024](https://www.kaggle.com/datasets/asaniczka/1-3m-linkedin-jobs-and-skills-2024)
- Used: 
  - `linkedin_job_postings.csv`
  - `job_skills.csv`

## Project Overview

The system tackles the problem of information overload in job search by recommending roles based on skill matching.

### Key Phases
- **Phase 1**: Data cleaning & EDA (handled missing data, merged datasets, visual insights)
- **Phase 2**: Clustering (KMeans) & model training (SVM, Logistic Regression, etc.)
- **Phase 3**: Deployed via **Flask Web App**

## Models Used

- Logistic Regression
- Decision Tree
- K-Nearest Neighbors
- Naive Bayes
- Random Forest
- XGBoost
- ** Best Accuracy: Support Vector Machine (76%)**

## Web App (Flask)

### Features
- Input: User enters skills (e.g., `nursing`, `coding`)
- Output: Top 5 job matches with title, location, and LinkedIn URL
- Built with Flask + HTML/CSS

### How to Run

```bash
# Setup
python -m venv venv
source venv/bin/activate  # or .\venv\Scripts\activate on Windows
pip install -r requirements.txt

# Run the app
python app.py
