# Sonar Rock vs Mine Classification

This project is about classifying sonar signals as either a **Rock (R)** or a **Mine (M)** using a Logistic Regression model.  
It is based on the Sonar dataset from the UCI Machine Learning Repository.

---

## Project Overview
The dataset contains 60 features, each representing a sonar signal. The task is to predict whether the signal bounced off a rock or a mine.  
Logistic Regression is used here as a baseline model to perform the classification.

---

## Dataset
- Name: Sonar, Mines vs. Rocks  
- Features: 60 continuous values (sonar signals)  
- Target: Rock (`R`) or Mine (`M`)  
- Source: [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/connectionist+bench+(sonar,+mines+vs.+rocks))

---

## Tools and Libraries
- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- Google Colab  

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sonar-rock-mine-classification.git
Install the required libraries:

pip install -r requirements.txt


Open the notebook and run it in Jupyter or Google Colab:

jupyter notebook sonar_model.ipynb

Results

Training Accuracy: ~80–85%

Test Accuracy: ~76%

This shows that Logistic Regression can handle the classification reasonably well, but the dataset is not perfectly separable with a linear model.

Future Work

Try more powerful models like Support Vector Machines (SVM) or Random Forests

Apply dimensionality reduction (PCA) to reduce noise

Use cross-validation for more reliable evaluation
