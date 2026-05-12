# 🚢 Titanic Survival Analysis - Data Science Project

## 📊 Project Overview

This comprehensive data science project analyzes the famous Titanic dataset to understand survival patterns and build a predictive model. The analysis explores demographic factors, passenger class, and other variables that influenced survival during the 1912 disaster.

## 🎯 Project Objectives

- **Data Exploration**: Understand the dataset structure and identify key patterns
- **Data Cleaning**: Handle missing values and prepare data for analysis
- **Exploratory Data Analysis**: Create visualizations to uncover insights
- **Machine Learning**: Build and evaluate a Logistic Regression model for survival prediction
- **Feature Analysis**: Identify the most important factors affecting survival

## 📈 Key Findings

### Survival Statistics
- **Overall Survival Rate**: 38.4% (327 survived out of 891 passengers)
- **Gender Impact**: Females had 73% survival rate vs. 19% for males
- **Class Impact**: 1st class passengers had the highest survival rates
- **Age Impact**: Younger passengers had slightly better survival chances

### Machine Learning Results
- **Model Accuracy**: ~80% on test data
- **Most Important Features**:
  1. Gender (sex_encoded) - Strongest predictor
  2. Passenger Class (pclass) - Second most important
  3. Family size (sibsp) - Moderate influence
  4. Embarkation port - Minor influence

## 🛠 Technical Stack

- **Programming Language**: Python 3.9
- **Data Manipulation**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Machine Learning**: Scikit-learn
- **Environment**: Jupyter Notebook, Virtual Environment

## 📁 Project Structure

```
├── week2_project.ipynb          # Main analysis notebook
├── Titanic-Dataset.csv          # Dataset file
├── Requirements.txt             # Python dependencies
├── README.md                    # Project documentation
└── .venv/                       # Virtual environment
```

## 🚀 Getting Started

### Prerequisites
- Python 3.8 or higher
- Git (for version control)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/abdulraheemtariq12-hash/DecodeLabs-DataScience-Internship-P2.git
   cd DecodeLabs-DataScience-Internship-P2
   ```

2. **Create virtual environment**
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r Requirements.txt
   ```

4. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

5. **Open the analysis notebook**
   - Navigate to `week2_project.ipynb`
   - Run all cells to reproduce the analysis

## 📊 Analysis Sections

### 1. Data Loading & Exploration
- Dataset overview and structure
- Column descriptions and data types
- Initial data inspection

### 2. Data Cleaning
- Missing value identification and handling
- Duplicate removal
- Data type conversions

### 3. Exploratory Data Analysis
- **Survival Count**: Overall survival distribution
- **Gender Analysis**: Survival rates by gender
- **Class Analysis**: Survival by passenger class
- **Age Distribution**: Passenger age patterns
- **Age vs Survival**: Age impact on survival
- **Correlation Heatmap**: Feature relationships

### 4. Machine Learning Model
- **Data Preparation**: Feature encoding and selection
- **Model Training**: Logistic Regression implementation
- **Model Evaluation**: Accuracy, precision, recall metrics
- **Confusion Matrix**: Prediction performance visualization
- **Feature Importance**: Key predictors identification

## 🔍 Key Insights

### Demographic Factors
- **Gender** was the strongest survival predictor, reflecting the "women and children first" protocol
- **Passenger Class** showed clear socioeconomic disparities in survival rates
- **Age** had a moderate impact, with children being prioritized

### Model Performance
- The Logistic Regression model achieved ~80% accuracy
- The model correctly identified survival patterns based on available features
- Feature importance analysis confirmed EDA findings

## 📈 Visualizations

The project includes 6 professional visualizations:
1. Overall Survival Count (Bar Chart)
2. Survival by Gender (Grouped Bar Chart)
3. Survival by Passenger Class (Grouped Bar Chart)
4. Age Distribution (Histogram with KDE)
5. Age vs Survival (Box Plot)
6. Feature Correlation Heatmap
7. Confusion Matrix
8. Feature Importance Chart

## 🤖 Machine Learning Details

### Model: Logistic Regression
- **Algorithm**: Logistic Regression with L2 regularization
- **Features Used**: pclass, sex_encoded, age, sibsp, parch, fare, embarked_encoded
- **Train/Test Split**: 80/20 split with random_state=42
- **Performance Metrics**:
  - Accuracy: ~80%
  - Precision: ~78%
  - Recall: ~72%

### Feature Engineering
- Categorical encoding for gender and embarkation port
- Mean imputation for missing age values
- Mode imputation for missing embarked values

## 📋 Requirements

```
pandas==2.3.3
numpy==2.0.2
matplotlib==3.9.4
seaborn==0.13.2
scikit-learn==1.6.1
jupyter==1.1.1
```

## 🎯 Learning Outcomes

This project demonstrates:
- Complete data science workflow
- Data cleaning and preprocessing
- Exploratory data analysis techniques
- Statistical analysis and visualization
- Machine learning model development
- Model evaluation and interpretation
- Professional documentation and presentation

## 📞 Contact

**Author**: Abdul Raheem Tariq
**GitHub**: [abdulraheemtariq12-hash](https://github.com/abdulraheemtariq12-hash)
**Project Repository**: [DecodeLabs-DataScience-Internship-P2](https://github.com/abdulraheemtariq12-hash/DecodeLabs-DataScience-Internship-P2)

## 📄 License

This project is for educational purposes as part of a data science internship program.

---

**⭐ If you found this analysis helpful, please give it a star on GitHub!**