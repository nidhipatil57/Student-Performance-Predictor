
# Student Performance Predictor

A beginner-friendly Machine Learning project that aims to predict student academic performance using student-related attributes and historical academic data.

This project is being developed as a hands-on learning journey to understand Machine Learning concepts practically, from dataset exploration to model development and deployment.

The goal of this project is to understand how Machine Learning works behind the scenes.

---

## Project Overview

The Student Performance Predictor uses the **UCI Student Performance Dataset** to explore and predict students' final grades (`G3`).
The project follows a step-by-step Machine Learning workflow:

1. Dataset Exploration
2. Data Preprocessing
3. Model Development
4. Model Training
5. Model Evaluation
6. Model Experimentation
7. Model Comparison
8. Web Application Development

We will initially focus on understanding the dataset before implementing any Machine Learning algorithms.

## 📊 Dataset

**Dataset:** UCI Student Performance Dataset

**Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/320/student+performance)

The dataset contains student performance records from two Portuguese schools.

| Dataset | Number of Records |
|---|---:|
| Mathematics (`student-mat.csv`) | 395 |
| Portuguese (`student-por.csv`) | 649 |

### Features Used

Some important attributes in the dataset include:

| Feature | Description |
|---|---|
| `age` | Student's age |
| `studytime` | Weekly study time |
| `failures` | Previous class failures |
| `absences` | Number of absences |
| `schoolsup` | Extra educational support |
| `famsup` | Family educational support |
| `G1` | First-period grade |
| `G2` | Second-period grade |
| `G3` | Final grade (Target Variable) |

**Prediction Target:** `G3`

Initially, the model will be explored without `G1` and `G2` to understand how other student-related features relate to final performance. Later, we will include previous grades and compare the results.

## 🛠️ Tech Stack

- **Python** – Main programming language
- **Pandas** – Data analysis and manipulation
- **NumPy** – Numerical computations
- **Matplotlib** – Data visualization
- **Scikit-learn** – Machine Learning implementation
- **Streamlit** – Web application development
- **Google Antigravity** – AI-assisted coding and development
- **Git & GitHub** – Version control

## Machine Learning Concepts

Throughout this project, I aim to understand:

- Exploratory Data Analysis (EDA)
- Features and Target Variables
- Data Cleaning and Preprocessing
- Missing Value Handling
- Categorical Encoding
- Feature Selection
- Linear Regression
- Train-Test Split
- Model Training
- Model Evaluation
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score
- Overfitting and Underfitting
- Decision Trees
- Random Forest


## Project Architecture

```text
Dataset (CSV)
     |
     v
Data Exploration (EDA)
     |
     v
Data Preprocessing
     |
     v
Machine Learning Model
     |
     v
Model Training
     |
     v
Model Evaluation
     |
     v
Model Comparison
     |
     v
Streamlit Web Application
     |
     v
Predicted Final Grade (G3)
```

## 📂 Project Structure

```text
student-performance-predictor/
│
├── dataset/
│   └── student-mat.csv
│
├── notebooks/
│
├── src/
│
├── app.py
│
├── LEARNING_NOTES.md
│
├── requirements.txt
│
├── .gitignore
│
└── README.md
```

*Project structure will be updated as development progresses.*


### 5. Download the Dataset

Download the dataset from:

[UCI Student Performance Dataset](https://archive.ics.uci.edu/dataset/320/student+performance)

Extract `student-mat.csv` and place it inside the `dataset/` directory.

## Learning Documentation

A separate `LEARNING_NOTES.md` file is maintained to document the learning process.

It includes:

- Machine Learning concepts and definitions
- Important formulas
- Python code explanations
- Experiments and observations
- Model evaluation results
- Lessons learned during development

## Project Goal

By completing this project, I aim to gain practical knowledge of how Machine Learning works, including how data is collected, explored, processed, used to train models, and evaluated.
The final objective is to develop an interactive web application that predicts student performance using a trained Machine Learning model.


---

**Project Status:** Currently in Development
