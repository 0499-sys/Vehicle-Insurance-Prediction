# Vehicle Insurance Prediction

## Project Overview
This project focuses on conducting comprehensive exploratory data analysis (EDA) and deploying advanced boosting models to predict outcomes in vehicle insurance. We leverage diverse datasets to ensure accuracy and representativeness across various attributes, including demographics, vehicle details, and policy history. Our approach includes meticulous data cleaning and visualization techniques to uncover trends and prepare the data for modeling.

We aim to develop decision models that facilitate informed decision-making and risk mitigation, optimizing pricing strategies and enhancing customer satisfaction. The insights gained from the analysis will inform risk segmentation, pricing strategies, and claims processing, ultimately improving operational efficiency in the vehicle insurance domain.

## Current Solutions
There are practical studies exploring cross-selling vehicle insurance to existing medical insurance clients through CRM and marketing analytics, enhancing customer retention and profitability.

## Business Problem
By leveraging our predictive model, we aim to optimize communication strategies for potential customers, thereby maximizing revenue. Our detailed information on customer demographics, vehicle attributes, and policy specifics will enhance our ability to predict customer interest in auto insurance.

## Data Description
- **Total Observations**: 381,109
- **Columns**: 12
  - **Binary Variables**: 2
  - **Categorical Variables**: 3
  - **Numerical Variables**: 5
- **Target Variable**: `Response` (binary)

### Target Variable Distribution
- **No (0)**: 87.7% (Count: 334,399)
- **Yes (1)**: 12.2% (Count: 46,710)

## Tech Stack
- **Data Analysis & Modeling**: SAS, Python (with libraries like Pandas, NumPy, Matplotlib)
- **Visualization**: Tableau

## Pre-Processing and Data Visualization
Prior to analysis, we purified the dataset by addressing missing values, eliminating duplicates, and rectifying inconsistencies. We employed undersampling techniques to handle class imbalance in the dataset, ultimately reducing it to 190,000 observations.

### Key Visualizations
1. **Scatter Plots**: Display relationships between age and premium amounts.
2. **Histograms**: Show age distribution and vehicle age groups.
3. **Chi-Square Analysis**: Reveal associations among variables related to the target variable.

## Data Modeling
We employed various modeling techniques, including:
1. **Stepwise Logistic Regression**
   - **Final model equation and significant predictors were identified.**
   - **High predictive accuracy with significant p-values for key variables.**
2. **Decision Trees**
    - **Visual representation of decision-making rules.**
   - **Strong performance in capturing non-linear relationships.**
3. **Gradient Boosting (XGB)**
    - **Sequentially builds trees to correct errors from prior models.**
   - **High gain and lift values indicate strong predictive capabilities.**

### Model Performance Metrics
![image](https://github.com/user-attachments/assets/b10e4e54-c7d8-46c2-8865-ccb38bb0e909)

## Results and Recommendations
The Decision Tree model outperformed others, offering robust Gain and Lift scores for targeted marketing. We recommend its use for customer classification, risk assessment, and optimizing operational efficiency.
