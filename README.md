# COVID-19 Outcome Prediction

## Project Description
This project aims to predict whether a person will recover from COVID-19 symptoms or not based on a set of predefined symptoms and demographic information. The dataset used in this project includes daily level information on the number of affected cases, deaths, and recoveries from the 2019 novel coronavirus, starting from January 22, 2020. The data is structured as a time series, with each entry representing cumulative numbers.

The dataset contains 14 major variables that could impact a patient's recovery outcome, including age, gender, location, and whether the person has visited or is from Wuhan, China. The target variable is the patient's outcome: death (1) or recovered (0).

## Dataset
- **File:** `data.csv`
- **Variables:**
  1. **Country:** Country of residence
  2. **Location:** Specific location within the country
  3. **Age:** Age group classification (based on WHO standards)
  4. **Gender:** Male or Female
  5. **Visited_Wuhan:** Whether the person has visited Wuhan, China
  6. **From_Wuhan:** Whether the person is from Wuhan, China
  7. **Symptoms:** Six fields representing different families of symptoms
  8. **Time_before_symptoms_appear:** Time before symptoms appeared
  9. **Result:** Outcome of the case - death (1) or recovered (0)

## Project Tasks
The goal is to design and implement different machine learning classifiers to predict the outcome (death or recovery) of new patients. The classifiers to be implemented are:

1. **K-Nearest Neighbors (KNN)**
2. **Logistic Regression**
3. **Naïve Bayes**
4. **Decision Trees**
5. **Support Vector Machines (SVM)**

### Steps Involved:
1. **Data Partitioning:** The dataset will be divided into three parts:
   - **Training Set:** To train the model
   - **Validation Set:** To tune hyperparameters
   - **Test Set:** To evaluate the model

2. **Model Implementation:** Implement each classifier and tune the hyperparameters to find the optimal settings.

3. **Performance Evaluation:** Compare the performance of all classifiers using the following metrics:
   - Precision
   - Recall
   - F1-Score
   - ROC/AUC Curves

## Installation
To run this project on your local machine, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Mohanad-Bador/COVID-19-Outcome-Prediction.git
