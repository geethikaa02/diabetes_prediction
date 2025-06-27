
# 🩺 Diabetes Prediction Web App

This project is a **machine learning-powered web application** built using **Streamlit** that predicts whether a person is diabetic based on key medical attributes. It uses a pre-trained model and provides an easy-to-use web interface for quick diagnosis.

---

## 📂 Project Structure

```
.
├── app.py                  # Backend model testing script
├── app1.py                 # Streamlit web application
├── trained_model.sav       # Pre-trained machine learning model
├── requirements.txt        # Required dependencies
└── diabetes.csv            # Dataset used to train the model
```

---

## 🚀 How to Run the Project

1. **Clone this repository** or download the project files.

2. **Install the required packages**:

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Streamlit app**:

   ```bash
   streamlit run app1.py
   ```

4. **Enter health metrics** such as Glucose Level, Blood Pressure, BMI, Age, etc., in the input fields and click **"Diabetes Test Result"** to view the prediction.

---

## 🧠 Model Information

- The model is trained on the [PIMA Diabetes dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database) (`diabetes.csv`).
- It predicts whether a person is **diabetic (1)** or **not diabetic (0)** using 8 input features:
  - Pregnancies
  - Glucose
  - BloodPressure
  - SkinThickness
  - Insulin
  - BMI
  - DiabetesPedigreeFunction
  - Age

---

## 💻 Tech Stack

- **Python 3**
- **NumPy**
- **Pickle**
- **Streamlit**

---

## 📌 Sample Input (for Testing in `app.py`)

```python
input_data = (5,166,72,19,175,25.8,0.587,51)
```

---

## 📷 Web App UI Preview

Upon launching the app, you'll see an interactive form asking for 8 medical inputs. When submitted, the app instantly shows whether the person is diabetic or not based on the trained model.

---

