
# 💎 Diamond Price Prediction Model

A machine learning-powered web application for predicting the price of diamonds based on key physical attributes. Built with **scikit-learn**, **XGBoost**, and **Flask**, this model demonstrates accurate price predictions and is designed for deployment-ready performance.

![UI Screenshot](https://user-images.githubusercontent.com/your-image-link.jpg) <!-- Optional: Add a screenshot or remove this line -->

---

## 📌 Table of Contents

- [Overview](#overview)
- [Tech Stack](#tech-stack)
- [Features](#features)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Model Performance](#model-performance)
- [Contributing](#contributing)
- [License](#license)

---

## 📖 Overview

This project aims to predict the price of diamonds by analyzing attributes like **carat**, **cut**, **color**, **clarity**, and dimensional properties. Using **machine learning regressors**, the app provides high-accuracy estimations, making it useful for **jewelers, gemologists, data scientists, and enthusiasts** alike.

---

## 🧰 Tech Stack

- **Programming Language:** Python
- **Libraries:** scikit-learn, XGBoost, Pandas, NumPy, Matplotlib, Seaborn
- **Deployment:** Flask, Joblib
- **Environment:** Jupyter Notebooks, VS Code

---

## 🚀 Features

- 🔍 **Exploratory Data Analysis (EDA)** with detailed visualizations
- 🔧 **Feature Engineering** and data preprocessing
- 🧠 **Model Training** using XGBoost, Random Forest, and Linear Regression
- 📊 **Model Evaluation** with RMSE, MAE, and R² metrics
- 🌐 **Web Application** using Flask for real-time predictions

---

## 📊 Dataset

Dataset sourced from the [Kaggle Diamond Dataset](https://www.kaggle.com/datasets/shivam2503/diamonds) with over **50,000 diamond records**, featuring:

- `carat`, `cut`, `color`, `clarity`
- `depth`, `table`
- Dimensions: `x`, `y`, `z`
- Target: `price` in USD

---

## 🗂️ Project Structure

```

prediction-model/
│
├── artifacts/               # Serialized model files
├── static/                  # CSS or images for web app
├── templates/               # HTML templates
│   └── index.html
├── app.py                   # Flask application
├── model.py                 # ML model code
├── pipeline.py              # Data preprocessing and training pipeline
├── requirements.txt         # Dependencies
├── README.md                # Project README
└── notebooks/
└── diamond\_analysis.ipynb

````

---

## 🛠️ Installation

Your installation section looks solid! Just a few minor tweaks to correct formatting and enhance clarity across systems:

---

## 🛠️ Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/Muskaanng/prediction-model.git
   cd prediction-model
   ```

2. **Create a virtual environment**

   **For Linux/macOS:**

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

   **For Windows:**

   ```bash
   python -m venv venv
   venv\Scripts\activate
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```


## ▶️ Usage

1. **Run the Flask application**

   ```bash
   python app.py
   ```

2. **Visit the app**
   Navigate to: [http://localhost:5000](http://localhost:5000)

3. **Predict diamond prices**
   Enter the diamond's features and hit **Predict** to get estimated prices.

---

## 📈 Model Performance

The model demonstrates high performance:

* **R² Score:** 0.982
* **RMSE:** 1057.32
* **MAE:** 842.15

These metrics confirm the model’s ability to generate accurate price predictions across diverse data points.

## 📄 License

This project is licensed under the MIT License.
See the [LICENSE](LICENSE) file for more details.

---

## 📬 Contact

Created and maintained by [Muskaan Gupta](https://github.com/Muskaanng)
For issues or queries, feel free to open an [issue](https://github.com/Muskaanng/prediction-model/issues).


