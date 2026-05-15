<div align="center">

  # 💤 Sleep Disorder Prediction

  **Machine Learning Model to Predict Sleep Disorders**  
  *Insomnia • Sleep Apnea • No Disorder*

  [![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org/)
  [![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
  [![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
  [![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)

  [![License](https://img.shields.io/github/license/MusaIslamFahad/Sleep_Disorder_Prediction?style=for-the-badge)](LICENSE)
  [![Stars](https://img.shields.io/github/stars/MusaIslamFahad/Sleep_Disorder_Prediction?style=for-the-badge)](https://github.com/MusaIslamFahad/Sleep_Disorder_Prediction/stargazers)

</div>

## 📋 Table of Contents
- [Overview](#-overview)
- [Features](#-features)
- [Dataset](#-dataset)
- [Project Workflow](#-project-workflow)
- [Installation](#-installation)
- [Usage](#-usage)
- [Results & Model Performance](#-results--model-performance)
- [Technologies Used](#-technologies-used)
- [Future Improvements](#-future-improvements)
- [Contributing](#-contributing)
- [License](#-license)

## ✨ Overview

This project develops a **machine learning classification model** that predicts sleep disorders (Insomnia, Sleep Apnea, or None) based on lifestyle, physical activity, stress levels, and demographic factors.

The goal is to help identify individuals at risk of sleep disorders using data-driven insights for early intervention and better healthcare outcomes.

## 🚀 Features

- ✅ Comprehensive **Exploratory Data Analysis (EDA)**
- ✅ Data cleaning and preprocessing
- ✅ Feature engineering and selection
- ✅ Multiple classification models (Random Forest, SVM, Logistic Regression, etc.)
- ✅ Model evaluation with confusion matrix, classification report & ROC curves
- ✅ Interactive visualizations using Seaborn & Matplotlib
- ✅ Jupyter Notebook with step-by-step explanations

## 📊 Dataset

- **Source**: [Kaggle Sleep Health and Lifestyle Dataset] (Add actual link if available)
- **Target Variable**: `Sleep Disorder` (Insomnia, Sleep Apnea, None)
- **Key Features**: Age, Gender, Occupation, Sleep Duration, Quality of Sleep, Physical Activity Level, Stress Level, BMI Category, Blood Pressure, Heart Rate, Daily Steps, etc.

## 🔄 Project Workflow

1. Data Loading & Understanding
2. Exploratory Data Analysis
3. Data Preprocessing & Feature Engineering
4. Model Training & Hyperparameter Tuning
5. Model Evaluation & Comparison
6. Conclusion & Insights

## 💻 Installation

```bash
# Clone the repository
git clone https://github.com/MusaIslamFahad/Sleep_Disorder_Prediction.git
cd Sleep_Disorder_Prediction

# Create virtual environment (optional)
python -m venv venv
source venv/bin/activate    # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt


```

## 📌 Usage

```bash
# Clone the repository
git clone https://github.com/MusaIslamFahad/Sleep_Disorder_Prediction.git
cd Sleep_Disorder_Prediction

# Install required dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook

```
Run the main analysis:
```
jupyter notebook Sleep_Disorder_Prediction.ipynb
```
Or export as HTML report:
```
jupyter nbconvert --execute --to html Sleep_Disorder_Prediction.ipynb

```

## 📊 Results & Model Performance

**Best Performing Model: Random Forest** 🎯

### Performance Metrics

| Metric          | Score    |
|-----------------|----------|
| **Accuracy**    | 89.00%   |
| **Precision**   | 87.00%   |
| **Recall**      | 85.00%   |
| **F1-Score**    | 86.00%   |

### Model Comparison

| Model                   | Accuracy | Precision | Recall | F1-Score |
|-------------------------|----------|-----------|--------|----------|
| **Random Forest**       | 89.00%   | XX.XX%    | XX.XX% | XX.XX%   |
| Decision Tree           | 87.00%   | XX.XX%    | XX.XX% | XX.XX%   |

### Visualizations

![Confusion Matrix](images/confusion_matrix.png)
![ROC Curve](images/roc_curve.png)
![Feature Importance](images/feature_importance.png)

> *Random Forest outperformed other models with balanced precision and recall, making it the most reliable for sleep disorder prediction.*


---

## 🛠 Technologies Used

- **Programming Language**: Python 3.9+
- **Data Manipulation**: Pandas, NumPy
- **Data Visualization**: Matplotlib, Seaborn
- **Machine Learning**: scikit-learn
- **Development Environment**: Jupyter Notebook

---


## 🚀 Future Improvements

- [ ] Implement **Deep Learning** models (LSTM / CNN) for better performance
- [ ] Add **Hyperparameter Tuning** using Optuna or GridSearchCV
- [ ] Deploy the model as a **Web Application** (Streamlit / Flask)
- [ ] Include **SHAP** or **LIME** for model explainability
- [ ] Add support for **real-time prediction** from user input
- [ ] Expand dataset with more diverse samples
- [ ] Implement **cross-validation** and **ensemble techniques**
- [ ] Create a **mobile app** version using Flutter or Android
- [ ] Add **sleep quality scoring** and personalized recommendations

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!  
Feel free to check the [issues page](https://github.com/MusaIslamFahad/Sleep_Disorder_Prediction/issues).

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

**Made with ❤️ by [Musa Islam Fahad](https://github.com/MusaIslamFahad)**




