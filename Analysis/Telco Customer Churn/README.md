<H1>Telco Customer Churn</H1>

<p>The company is a fictional telecommunications provider based in California, offering home phone and Internet services. In Q3, the company served 7,043 customers, delivering various service plans including phone, high-speed DSL, and fiber optic internet. The company aims to provide reliable connectivity and quality customer experience while maintaining a competitive edge in the telecom market. </p>

<p>In this project I used the Telco Customer Churn dataset that can me found in this link: https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data</p>
<p>Each row represents a customer, each column contains customer’s attributes described on the column Metadata.</p> </br>

<h3>Problem Background</h3>
  <ol>
    <ul>Customer churn is a critical challenge in the telecommunications industry.</ul>
    <ul>Customer churn is a critical challenge in the telecommunications industry.</ul>
    <ul>High churn rates impact revenue, operational efficiency, and market share.</ul>
    <ul>Despite having a broad service portfolio, the company has observed fluctuations in customer retention.</ul>
    <ul>Multiple factors such as service quality, contract terms, billing methods, and demographics influence churn.</ul>
    <ul>The company seeks to identify reasons for churn and predict customers at risk.</ul>
  </ol>


<h3>Goals:</h3>
<p>Leverage customer demographic, service usage, and account information to:
  <ul>
    <li> Understand churn drivers.</li>
    <li>Predict churn likelihood.</li>
    <li>Design targeted retention strategies.</li>
    <li>Reduce churn rates and improve customer satisfaction.</li>
  </ul>
</p>

<p>Steps:</p>
<ol> 
  <li> Load the csv file:
    <ul>
      <li>Used the read_csv() to load my dataset into a Pandas DataFrame.</li>
    </ul>
  </li></br>

  <li>Explore the data:
    <ul>
      <li>Used the function head to call the first 5 rows of the dataset. </li>
      <li>Used the info function, that gives the number of columns, column labels, column data types, memory usage, range index, and the number of cells in each column (non-null values).</li>
      <li>Used the describe function, that gives some statistical data like percentile, mean and standard deviation of the numerical values of the Series or DataFrame.</li>
    </ul>
  </li></br>

  <li>Identify and Handle Missing Values:
    <ul>
      <li>Used isnull function to identify missing values in the dataset.</li>
      <li>Used the dropna function to drop the missing/null values from our dataset.</li>
    </ul>
  </li></br>

  <li>Data Type Conversion:
    <ul>
      <li>Used the astype to convert the column types.</li>
    </ul>
  </li></br>

  <li>Save the data
    <ul>
      <li>I saved the data using the df.to_csv(new_name.csv, index=False)</li>
    </ul>
  </li>
</ol></br>


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
