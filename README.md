# Potential Customers Prediction Project

This project leverages machine learning techniques to predict potential customers for ExtraaLearn, a startup focused on cutting-edge technology education. The goal is to identify leads who are more likely to convert to paid customers, allowing for better resource allocation and targeted marketing strategies.

## Project Files
- `AmirFullCode-Potential+Customers+Prediction.html`: An HTML file containing the complete code and results in a static, shareable format.
- `AmirFullCode-Potential+Customers+Prediction.ipynb`: The Jupyter Notebook file with the full code, data analysis, and model training steps.

## Project Overview
### Objective
The primary objective is to build a predictive model that identifies potential customers who are more likely to convert to paid customers, helping ExtraaLearn optimize its marketing efforts and resource allocation.

### Data
The dataset includes features related to customer interactions such as:
- **Demographics**: Age, Gender, Location
- **Engagement**: Number of visits, Duration of sessions
- **Behavior**: Click patterns, Course interests
- **Previous Purchases**: Any prior transactions or subscriptions

### Methodology
1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Scaling numerical features

2. **Exploratory Data Analysis (EDA)**
   - Visualizing data distributions and relationships
   - Identifying patterns and insights
   - Feature engineering to create new meaningful variables

3. **Model Training**
   - Splitting data into training and test sets
   - Training multiple machine learning models (e.g., Logistic Regression, Random Forest, Gradient Boosting)
   - Hyperparameter tuning to optimize model performance

4. **Model Evaluation**
   - Evaluating model performance using metrics such as accuracy, precision, recall, and F1-score
   - Selecting the best model based on evaluation metrics

5. **Feature Importance Analysis**
   - Identifying the most important features contributing to the predictions
   - Understanding how each feature influences the model

## Results
- The models achieved high accuracy and F1-scores in predicting potential customers.
- Key features such as session duration, engagement with specific course categories, and prior purchase history were identified as significant predictors.

### Key Findings
- **High Engagement**: Users with longer session durations and frequent visits are more likely to convert.
- **Specific Interests**: Interest in certain course categories correlates strongly with conversion rates.
- **Previous Purchases**: Customers who have made prior purchases are more likely to subscribe again.

## How to Use
1. **View the Results**: Open the HTML file (`.html`) to see the complete code and results without needing to run the code.
2. **Run the Code**: Open the Jupyter Notebook file (`.ipynb`) to view and execute the code interactively. Ensure you have the necessary dependencies installed (e.g., pandas, scikit-learn, matplotlib).

### Dependencies
To run the Jupyter Notebook, ensure you have the following Python packages installed:
```bash
pip install pandas scikit-learn matplotlib seaborn
