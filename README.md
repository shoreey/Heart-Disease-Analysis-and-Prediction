# Heart Disease Prediction Model

## Project Overview
This project aims to predict the 10-year risk of coronary heart disease (CHD) using machine learning techniques. The analysis focuses on various health factors to identify patterns and risk indicators for heart disease, ultimately aiding in early detection and prevention strategies.

## Dataset
The dataset used for this analysis contains health information of 4,238 individuals, including features such as:
- **Demographic Data**: Age, sex, education level
- **Health Indicators**: BMI, blood pressure, cholesterol levels
- **Lifestyle Factors**: Smoking status, diabetes
- **Target Variable**: TenYearCHD (10-year risk of coronary heart disease)

## Methodology

### Data Preprocessing
- **Loading the Dataset**: The dataset is loaded using Pandas.
- **Handling Missing Values**: Identified and addressed missing values in various features.
- **Exploratory Data Analysis (EDA)**: Conducted to understand the dataset's structure and distribution.

### Exploratory Data Analysis (EDA)
- **Data Overview**: Displayed the first few rows and summary statistics of the dataset.
- **Count Plot**: Visualized the distribution of heart disease cases.
- **Age Distribution Histogram**: Analyzed age distribution in relation to heart disease outcomes.
- **Correlation Analysis**: Examined correlations between health factors and CHD risk.

### Feature Engineering
- Created age groups for more granular analysis of heart disease risk.

### Model Development
1. **Logistic Regression**: Implemented to predict the likelihood of heart disease based on health factors.
2. **Model Evaluation**: Assessed model performance using confusion matrix, classification report, and accuracy score.

## Results
- **Count of Heart Disease Cases**: Out of 4,238 individuals, 644 (15.2%) were identified as at risk for heart disease within 10 years.
- **Key Insights**:
  - Age and smoking status are significant predictors of heart disease risk.
  - The analysis revealed patterns indicating that older individuals and smokers face higher risks.

## Key Findings
1. The dataset indicates a strong correlation between smoking status and heart disease risk.
2. Age appears to be a significant factor, with risk increasing in older age groups.
3. Other factors like BMI and diabetes also contribute to the overall risk assessment.

## Conclusion
This study demonstrates the potential of machine learning in predicting heart disease risk. The findings emphasize the importance of health indicators such as age and smoking status in assessing risk, providing valuable insights for healthcare professionals.

## Future Work
- Explore additional machine learning algorithms (e.g., Random Forest, Support Vector Machines) for comparison.
- Investigate the impact of lifestyle factors on heart disease risk more deeply.
- Consider developing a user-friendly interface for healthcare professionals to utilize the model.

## Technologies Used
- Python
- Pandas for data manipulation
- Matplotlib and Seaborn for data visualization
- Scikit-learn for machine learning models
