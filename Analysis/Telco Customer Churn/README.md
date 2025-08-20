


Business Understanding
🏢 1.1 About Company
The company is a fictional telecommunications provider based in California, offering home phone and Internet services. In Q3, the company served 7,043 customers, delivering various service plans including phone, high-speed DSL, and fiber optic internet. The company aims to provide reliable connectivity and quality customer experience while maintaining a competitive edge in the telecom market.

⚠️ 1.2 Problem Background
Customer churn is a critical challenge in the telecommunications industry.
High churn rates impact revenue, operational efficiency, and market share.
Despite having a broad service portfolio, the company has observed fluctuations in customer retention.
Multiple factors such as service quality, contract terms, billing methods, and demographics influence churn.
The company seeks to identify reasons for churn and predict customers at risk.
🎯 1.3 Goals
Leverage customer demographic, service usage, and account information to:

Understand churn drivers.
Predict churn likelihood.
Design targeted retention strategies.
Reduce churn rates and improve customer satisfaction.
🛠️ 1.4 Objective
To address churn effectively, the analysis will focus on:

📈 Predictive Modeling
Build a machine learning model to classify customers into churn or non-churn segments.
Identify the most influential features contributing to churn.
💡 Actionable Insights
Provide recommendations for personalized retention offers.
Support marketing and customer service teams in implementing targeted strategies.
📊 Business Impact
Reduce churn rate and increase Customer Lifetime Value (CLTV).
Enhance customer loyalty and satisfaction.

Data Understanding
-Checking duplicated data
-Checking missing values
-Check the count and what unique values exist for each feature
- Conversion Data Type TotalCharges

Data Preprocessing
-Conversion Data Type TotalCharges
-Handling Missing Values
-Fill NaN values only in the 'TotalCharges' column with 0

Univariate Analysis
-Grouping Categorical and Numerical Columns
-Histogram and boxplot Numerical Columns
-Churn Distribuition plot
-Distribuiton Categorical Columns plots

Bivariate Analysis
- Barplot Categoricak Columns by Churn
- Displot of Bivariate Analysis by Churn

Multivariate Analysis
-correlation heatmap

Features Encoding
- # Drop 'customerID' because it's not a feature but a unique ID
- Encode target 'Churn' into 0/1
- Binary categorical columns — use LabelEncoder
- Multi-category categorical columns — use One-Hot Encoding

Features Scalling
- Convert TotalCharges to numeric (sometimes stored as string)
- Fill missing TotalCharges with median value
- Scale numerical features using StandardScaler (mean=0, std=1)

Modeling & Evaluation
- Spliting Data
- Modeling : Random Forest

Performance Evaluation
- Evaluate performance
- heatmap(confusion_matrix(y_test, y_pred
- Plot top 15 important features
- Calculate ROC-AUC

Conclusion
The current model performs reasonably well in distinguishing between churn and non-churn customers, as indicated by its high AUC score.
However, the relatively low churn recall (48%) shows that a significant number of churn cases remain undetected, which could lead to potential business losses from customer attrition.
This project will be continued, as there is still room to improve the model’s performance. The author is also exploring various techniques to achieve better predictive results.
In the future, once the model’s performance improves, data-driven business strategy recommendations based on the model’s output will be added for actionable insights.
