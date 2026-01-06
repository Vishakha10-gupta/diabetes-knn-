# 🩺 Diabetes Linear Regression Model

[![Streamlit App](https://img.shields.io/badge/Live%20App-Open%20Now-brightgreen?logo=streamlit)](https://o9mjetrgytnde9nh8nsr94.streamlit.app/)
[![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![scikit-learn](https://img.shields.io/badge/Scikit--Learn-Model-orange?logo=scikit-learn)](https://scikit-learn.org/)
[![Streamlit](https://img.shields.io/badge/Built%20With-Streamlit-red?logo=streamlit)](https://streamlit.io/)

## 📊 Overview

This interactive web app uses a **Linear Regression** model trained on the **Diabetes dataset** from `scikit-learn` to predict disease progression based on key patient features. Users can input patient data and visualize predictions in real time.

🔗 **Live App**: [https://o9mjetrgytnde9nh8nsr94.streamlit.app/](https://o9mjetrgytnde9nh8nsr94.streamlit.app/)

---

## 🧠 Features

- Trains a linear regression model on selected important features:
  - `age`, `sex`, `bmi`, `bp`, `s5`
- Displays model performance metrics:
  - **Mean Squared Error (MSE)**
  - **R-squared (R²)**
- Interactive sidebar for user input
- Real-time prediction of diabetes progression
- Dual visualizations:
  - True vs Predicted values
  - BMI vs Predicted progression (with user input highlighted)

---

## 🚀 How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/diabetes-regression-app.git
   cd diabetes-regression-app


2. **Install dependencies**

pip install -r requirements.txt

3. **Run the app**

streamlit run app.py

## Requirements

Install them

pip install streamlit numpy matplotlib scikit-learn

## 📁 File Structure

```
├── app.py               # Main Streamlit app
├── README.md            # Project documentation
├── requirements.txt     # Python dependencies
```

## License

MIT License
Copyright (c) 2026
