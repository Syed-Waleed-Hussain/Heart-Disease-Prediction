# Heart Disease Prediction ❤️🩺

A simple and effective Machine Learning project that predicts the likelihood of heart disease in a patient based on their medical attributes using **Logistic Regression**.

## 📌 Overview
This project is a beginner-friendly implementation of a binary classification problem in Machine Learning. By analyzing various medical indicators such as age, blood pressure, cholesterol levels, and heart rate, the model predicts whether a person is prone to heart disease (1) or not (0).

## 🛠️ Tech Stack Used
* **Language:** Python
* **Libraries:** 
  * `pandas` & `numpy` (for Data Manipulation)
  * `matplotlib` & `seaborn` (for Data Visualization)
  * `scikit-learn` (for Machine Learning model and evaluation)

## 📊 Dataset
The dataset used for this project contains various medical records. 
*https://www.kaggle.com/datasets/mfarhaannazirkhan/heart-dataset*

Key features in the dataset include:
* Age
* Sex
* Chest Pain Type (cp)
* Resting Blood Pressure (trestbps)
* Serum Cholestoral (chol)
* Maximum Heart Rate Achieved (thalach)

## ⚙️ Model Training & Evaluation
The core of this project relies on **Logistic Regression**, which is excellent for binary classification tasks. 
* The data was cleaned, preprocessed, and split into training and testing sets.
* The model's performance was evaluated using **Accuracy Score**, **Confusion Matrix**, and **Classification Report**.

## 🚀 How to Run the Project locally

1. **Clone the repository:**
   ```
   git clone [https://github.com/](https://github.com/)Syed-Waleed-Hussain/Heart-Disease-Prediction.git
   ```
Navigate to the project directory:

```
cd Heart-Disease-Prediction
```
Install the required dependencies:

```
pip install pandas numpy scikit-learn matplotlib seaborn
```
Run the Jupyter Notebook or Python Script:

```
jupyter notebook heart_disease_prediction.ipynb
```
# OR
```
python main.py
```
🔮 Future Improvements
Since this is a baseline model, future updates could include:

Testing out other algorithms like Random Forest or Decision Trees.

Building a simple web interface using Streamlit or Gradio so anyone can input their data and get a prediction.

Author: Syed Waleed

GitHub: @Syed-Waleed-Hussain
