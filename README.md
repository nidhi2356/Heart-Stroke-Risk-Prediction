# ❤️ Heart Stroke Risk Prediction

A Machine Learning web application built using **Python** and **Streamlit** to predict the risk of heart disease based on user health parameters. The application uses a **K-Nearest Neighbors (KNN)** classification model trained on a preprocessed heart disease dataset.

---

## 📌 Project Workflow

1. Performed data preprocessing, including:
   - Handling categorical features using one-hot encoding.
   - Scaling numerical features using StandardScaler.
   - Preparing the dataset for machine learning.

2. Trained and evaluated multiple classification algorithms, including:
   - Logistic Regression
   - Decision Tree Classifier
   - Random Forest Classifier
   - Support Vector Machine (SVM)
   - K-Nearest Neighbors (KNN)

3. Compared the accuracy scores of all the models.

4. Selected the **K-Nearest Neighbors (KNN)** classifier because it achieved the highest accuracy on the dataset.

5. Saved the trained model, scaler, and feature columns using Joblib.

6. Developed an interactive web application using **Streamlit** to allow users to enter health-related information and receive heart disease risk predictions.

---

## 🚀 Features

- Interactive user interface built with Streamlit.
- Real-time heart disease prediction.
- Automatic preprocessing of user inputs.
- Uses the trained KNN model for prediction.
- Simple and user-friendly interface.

---

## 🛠️ Tech Stack

- Python
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- Joblib

---

## 📂 Project Structure

```
Heart-Stroke-Risk-Prediction/
│
├── app.py
├── heart.ipynb
├── heart_model.pkl
├── heart_scaler.pkl
├── heart_columns.pkl
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ▶️ How to Run

Clone the repository:

```bash
git clone https://github.com/your-username/Heart-Stroke-Risk-Prediction.git
```

Move into the project directory:

```bash
cd Heart-Stroke-Risk-Prediction
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Run the Streamlit application:

```bash
streamlit run app.py
```

---

## 📚 Libraries Used

- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Joblib

---

## 📈 Model Used

**K-Nearest Neighbors (KNN)**

The KNN classifier was selected after comparing the performance of multiple classification algorithms. It achieved the highest accuracy on the preprocessed dataset and was therefore used for deployment in the Streamlit application.
