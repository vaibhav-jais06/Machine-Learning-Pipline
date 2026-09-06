# End-to-End Machine Learning Pipeline: Titanic Survival Prediction 🚢

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Scikit-Learn](https://img.shields.io/badge/scikit--learn-1.0+-F7931E.svg)](https://scikit-learn.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data_Manipulation-150458.svg)](https://pandas.pydata.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626.svg)](https://jupyter.org/)

Welcome to the **Machine Learning Pipeline** repository! This project demonstrates a complete, structured, and easy-to-understand machine learning workflow using the classic Titanic dataset. Our goal is to predict passenger survival based on their historical data.

---

## 🎯 Problem Statement
**Task (T):** Classify whether a passenger survived (1) or did not survive (0).  
**Experience (E):** Historical passenger records with known outcomes.  
**Performance (P):** Accuracy (the percentage of passengers correctly classified).  

---

## 🛠️ Pipeline Architecture

This repository encapsulates the standard lifecycle of an ML project:

1. **Setup & Import Libraries:** Bringing in `pandas`, `numpy`, `matplotlib`, `seaborn`, and `scikit-learn`.
2. **Problem Definition:** Setting a clear objective for the model.
3. **Data Collection:** Loading the raw data.
4. **Exploratory Data Analysis (EDA):** Understanding data distributions, missing values, and feature correlations.
5. **Data Preprocessing:** Handling missing data, encoding categorical variables, and scaling.
6. **Model Training:** Building a robust `DecisionTreeClassifier` (and exploring others).
7. **Model Evaluation:** Analyzing performance using Accuracy, Confusion Matrices, and Classification Reports.

---

## 📂 Repository Contents

- 📓 **`ML_Pipeline.ipynb`**: The core Jupyter Notebook containing the entire end-to-end pipeline. It is heavily commented and structured step-by-step for educational purposes.
- 📄 **`README.md`**: Project documentation.

---

## 🚀 Getting Started

### Prerequisites
Make sure you have Python installed along with the following libraries:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Running the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/vaibhav-jais06/Machine-Learning-Pipline.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Machine-Learning-Pipline
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook ML_Pipeline.ipynb
   ```
4. Run the cells sequentially to observe the data transformation and model training process!

---

## 📊 Results & Evaluation
The model evaluates passenger survival using standard classification metrics:
- **Accuracy Score:** Overall correctness of the model.
- **Confusion Matrix:** True Positives, True Negatives, False Positives, False Negatives.
- **Classification Report:** Precision, Recall, and F1-score for comprehensive analysis.

---

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/vaibhav-jais06/Machine-Learning-Pipline/issues) if you want to contribute.

## 📝 License
This project is open-source and available under the [MIT License](LICENSE).

---
*Created with ❤️ by Vaibhav Jaiswal*
