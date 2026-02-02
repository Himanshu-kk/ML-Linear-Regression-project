# Insurance Cost Prediction using Linear Regression

This project predicts **medical insurance charges** using a **Linear Regression model**.  
The dataset includes features such as **age, BMI, sex, children, smoker status, and region**.

---

## 📌 Project Objective
To build a machine learning model that can predict **insurance charges** based on customer details.

---

## 📂 Dataset Information
Dataset contains the following columns:

| Column Name | Description |
|------------|-------------|
| age | Age of the person |
| sex | Gender (male/female) |
| bmi | Body Mass Index |
| children | Number of children/dependents |
| smoker | Smoking status (yes/no) |
| region | Residential region |
| charges | Medical insurance cost |

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- Jupyter Notebook

---

## ⚙️ Workflow / Steps
1. Import dataset
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Encoding (Label Encoding / One Hot Encoding)
5. Train-Test Split
6. Model Training (Linear Regression)
7. Predictions
8. Model Evaluation using:
   - R² Score
   - Adjusted R² Score

---

## 🧠 Machine Learning Model
- **Algorithm Used:** Linear Regression  
- **Train-Test Split:** 80% Train, 20% Test  

---

## 📊 Model Evaluation
Evaluation metrics used:
- **R² Score**
- **Adjusted R² Score**

**R² Score Formula:**
\[
R^2 = 1 - \frac{SS_{res}}{SS_{tot}}
\]

**Adjusted R² Formula:**
\[
Adjusted\ R^2 = 1 - \left(\frac{(1-R^2)(n-1)}{n-p-1}\right)
\]

Where:
- n = number of samples
- p = number of predictors/features

---

## 🚀 How to Run the Project
1. Clone the repository
```bash
git clone https://github.com/your-username/your-repo-name.git

