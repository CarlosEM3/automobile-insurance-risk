# automobile-insurance-risk
### Project Overview:
Analyzing auto data for refined insurance risk evaluations. The dataset comprises auto specifications, insurance risk ratings, and normalized losses. Through the "symboling" process, risk ratings are adjusted based on the discrepancy between a vehicle's risk and its price. Additionally, normalized losses offer insights into average loss payments per insured vehicle year, categorized by size. This analysis aims to assist insurance companies in accurately assessing and pricing risks associated with diverse automobile profiles. By analyzing comprehensive auto data, including specifications, risk ratings, and losses, the goal is to provide insurance companies with a tool for enhanced risk evaluation and pricing strategies.

### Workflow:

To begin this project, first in the exploratory data analysis (EDA) phase, the dataset was imported and reformatted. Then, missing values were identified, and univariate analysis was conducted to understand car make, body style, cylinders, and pricing distribution. Moving to bivariate analysis, relationships between variables such as body style and price were investigated, with outliers and patterns flagged to be addressed. During data wrangling, less informative columns were removed, missing data was addressed, and focus was placed on factors needed for estimating symbolizing scores and prices. For modeling, a linear regression approach was selected to predict symbolizing scores. The data was split for training and testing and the model was fitted. However, the model's R-squared score indicated a need for refinement, suggesting further adjustments were necessary.

### Discussion:
There are currently still areas for the linear regression model to improve. By potentially addressing these steps, the project aims to refine the linear regression model, improving its accuracy and applicability in risk assessment strategies for insurance companies in the auto insurance sector. A list of approach recommendations: 

- Feature Selection: Reevaluate the relevance of features and exclude those not contributing significantly to predictive power.
- Revisit Outlier Detection: Further ensuring outliers in variables have been addressed in data to enhance model performance.
- Error Analysis: Analyze model errors to understand misalignments and improve accuracy.
- Revisit Data Exploration: Further investigate relationships between car factors and pricing to uncover hidden patterns.
- New Model Exploration: Further investigating other machine learning models for better predictive accuracy.

Impact of Work:
Despite challenges, the project highlights areas for improvement in risk assessment and pricing strategies in the insurance sector. This project uncovers insights into refining machine-learning models for better predictive accuracy that would support automobile risk assessment and pricing for insurance companies.
