# Employee-salary-Prediction
A powerful web application that predicts employee salaries using machine learning.

*Live Demo*: 🚀 [Click here to try it](https://employee-salary-estimator-using-ml-i92lk8ujysmo6nkgh36tnf.streamlit.app/)

---

![App Screenshot](app_ui.png)

---

## ✨ Key Features

- 🎨 *Modern Glassmorphism UI*: Beautiful Streamlit-based interface with sleek design.
- 📈 *Realistic Salary Prediction*: Predicts employee salaries based on multiple input features.
- ⚙ *End-to-End ML Pipeline*: From preprocessing to model inference.
- 💡 *Explainable Features*: Shows how different inputs affect salary.
- ✅ *Deployable Anywhere*: Easily deploy on Streamlit Community Cloud or other platforms.

---

## 🧠 Machine Learning Pipeline

- *Model Used*: XGBoost Regressor
- *Training Dataset*: Based on UCI Adult Income dataset
- *Features*:
  - Age
  - Gender
  - Education Level
  - Occupation
  - Hours-per-week
  - Native Country
- *Preprocessing*:
  - Label Encoding for categorical variables
  - Scaling numerical features using MinMaxScaler
- *Persistence*:
  - Trained model and pipeline saved with joblib

---

## 🛠 Tech Stack & Libraries

| Layer              | Tech Used                          |
|--------------------|------------------------------------|
| Language           | Python 3.12                        |
| ML Libraries       | scikit-learn, XGBoost              |
| Web Framework      | Streamlit                          |
| Data Handling      | Pandas                             |
| Model Saving       | Joblib                             |
| Animations (opt)   | Lottie                             |

---

## 🚀 How to Run Locally

### Prerequisites

- Python 3.9+ installed
- pip (Python package manager)

### 1️⃣ Clone the repository

```bash
git clone https://github.com/YourUsername/Employee-Salary-Prediction-ML.git
cd Employee-Salary-Prediction-ML
# For Windows
python -m venv venv
venv\Scripts\activate

# For macOS/Linux
python3 -m venv venv
source venv/bin/activate
# For Windows
python -m venv venv
venv\Scripts\activate

# For macOS/Linux
python3 -m venv venv
source venv/bin/activate
# For Windows
python -m venv venv
venv\Scripts\activate

# For macOS/Linux
python3 -m venv venv
source venv/bin/activate
