# Crime-Cast: Predictive Crime Category Forecasting

![GitHub last commit](https://img.shields.io/github/last-commit/yourusername/crime-cast)
![Award](https://img.shields.io/badge/Award-Best%20Capstone%20Project%20IIT%20Madras-gold)

![TSNE](https://github.com/arjunthilak05/CrimeCast/blob/main/download.png)


## 🏆 Best Capstone Project Award - Machine Learning Practice Course, IIT Madras

This project was awarded the **Best Capstone Project** in the Machine Learning Practice Course at IIT Madras for its innovative approach to crime category prediction and practical applications in public safety.

## 📊 Project Overview

Crime-Cast is a sophisticated machine learning system designed to predict crime categories based on various spatial, temporal, and demographic features. Using data from Los Angeles crime reports, the model can forecast the type of crime likely to occur given specific conditions, enabling law enforcement agencies to allocate resources more effectively.

### Problem Statement

Law enforcement agencies face challenges in resource allocation and crime prevention due to limited information about where and what type of crimes might occur. This project addresses this challenge by developing models that can predict crime categories with high accuracy, providing actionable intelligence for crime prevention strategies.

## 🔍 Features

- Multi-class crime category prediction
- Temporal pattern analysis (time of day, day of week, seasonal trends)
- Spatial pattern recognition using latitude and longitude
- Victim demographic analysis
- Weapon and modus operandi pattern identification

## 📈 Model Performance

| Model | Accuracy | Precision | Recall | F1-Score |
|-------|----------|-----------|--------|----------|
| XGBoost | 0.9992 | 0.9993 | 0.9992 | 0.9992 |
| Random Forest | 1.0000 | 1.0000 | 1.0000 | 1.0000 |
| Decision Tree | 1.0000 | 1.0000 | 1.0000 | 1.0000 |
| KNN | 0.7848 | 0.7760 | 0.7848 | 0.7754 |
| SVM | 0.7027 | 0.6881 | 0.7027 | 0.6464 |

## 🔧 Technologies Used

- **Python**: Primary programming language
- **Pandas & NumPy**: Data manipulation and numerical operations
- **Scikit-learn**: Feature engineering, preprocessing, and modeling
- **XGBoost**: Gradient boosting implementation
- **Matplotlib & Seaborn**: Data visualization
- **T-SNE**: Dimensionality reduction for visualization

## 📁 Dataset

The project uses the Crime-Cast dataset with the following features:
- Location details (coordinates, area name, cross street)
- Temporal information (date and time of occurrence)
- Victim demographics (age, sex, descent)
- Crime details (premise, weapon used, modus operandi)
- Status information

## 🔬 Methodology

1. **Data Preprocessing**:
   - Handling missing values using KNN imputer
   - Feature engineering (temporal features, MO parsing)
   - Categorical encoding

2. **Exploratory Data Analysis**:
   - Crime distribution analysis
   - Temporal patterns visualization
   - Victim demographics analysis
   - T-SNE visualization of crime categories

3. **Feature Selection**:
   - Recursive Feature Elimination (RFE)
   - Importance-based selection

4. **Model Development**:
   - Multiple classifier implementation
   - Hyperparameter tuning using RandomizedSearchCV
   - Cross-validation for robust evaluation

5. **Model Evaluation**:
   - Performance metrics comparison
   - Prediction analysis

## 📊 Key Findings

- Certain times of day show significantly higher crime rates
- Crime categories show distinct patterns by day of week
- Victim demographics correlate with specific crime types
- Geographic clusters reveal crime hotspots
- Specific combinations of features yield high predictive power

## 🚀 Future Work

- Incorporate additional datasets (weather, economic indicators, social media)
- Develop an interactive dashboard for law enforcement
- Implement real-time prediction capabilities
- Expand to other metropolitan areas
- Investigate causal relationships

## 💻 Installation & Usage

```bash
# Clone the repository
git clone https://github.com/arjunthilak05/CrimeCast.git

# Navigate to the project directory
cd crime-cast

# Install required packages
pip install -r requirements.txt

# Run the analysis notebook
jupyter notebook crime_cast_analysis.ipynb
```

## 📝 Citation

If you use this project in your research or application, please cite:

```
@misc{crime-cast-2023,
  author = {R Arjun Thilak},
  title = {Crime-Cast: Predictive Crime Category Forecasting},
  year = {2023},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/R Arjun Thilak/crime-cast}}
}
```

## 🙏 Acknowledgments

- Machine Learning Practice Course faculty at IIT Madras
- Kaggle for hosting the competition and dataset
- Los Angeles Police Department for the original data collection

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

