<H1>Telco Customer Churn</H1>

<p>The company is a fictional telecommunications provider based in California, offering home phone and Internet services. In Q3, the company served 7,043 customers, delivering various service plans including phone, high-speed DSL, and fiber optic internet. The company aims to provide reliable connectivity and quality customer experience while maintaining a competitive edge in the telecom market. </p>

<p>In this project I used the Telco Customer Churn dataset that can me found in this link: https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data</p>
<p>Each row represents a customer, each column contains customer’s attributes described on the column Metadata.</p>

<h3>Problem Background</h3>
<ul>
    <li>Customer churn is a critical challenge in the telecommunications industry.</li>
    <li>Customer churn is a critical challenge in the telecommunications industry.</li>
    <li>High churn rates impact revenue, operational efficiency, and market share.</li>
    <li>Despite having a broad service portfolio, the company has observed fluctuations in customer retention.</li>
    <li>Multiple factors such as service quality, contract terms, billing methods, and demographics influence churn.</li>
    <li>The company seeks to identify reasons for churn and predict customers at risk.</li>
</ul>


<h3>Goals:</h3>
<p>Leverage customer demographic, service usage, and account information to:
  <ul>
    <li> Understand churn drivers.</li>
    <li>Predict churn likelihood.</li>
    <li>Design targeted retention strategies.</li>
    <li>Reduce churn rates and improve customer satisfaction.</li>
  </ul>
</p>

<h3>Objective</h3>
<p>Predictive Modeling:
    <ul>
        <li> Build a machine learning model to classify customers into churn or non-churn segments. </li>
        <li>Identify the most influential features contributing to churn.</li> 
    </ul>
</p>

<ul>Actionable Insights:
    <li>Provide recommendations for personalized retention offers. </li>
    <li>Support marketing and customer service teams in implementing targeted strategies. </li> 
</ul>

<ul>Business Impact
    <li>Reduce churn rate and increase Customer Lifetime Value (CLTV).</li>
    <li>Enhance customer loyalty and satisfaction. </li> 
</ul>

<h3>Steps:</h3>
<ol> 
    <li> Load the csv file:
        <ul>
            <li>Used the read_csv() to load my dataset into a Pandas DataFrame.</li>
        </ul>
    </li></br>

    <li>Data Understanding:
        <ul>
          <li>Checking duplicated data. </li>
          <li>Checking missing values</li>
          <li>Check the count and what unique values exist for each feature</li>
        </ul>
    </li></br>

    <li>Data Preprocessing:
        <ul>
          <li>Conversion Data Type TotalCharges</li>
          <li>Handling Missing Values</li>
          <li>Fill NaN values only in the 'TotalCharges' column with 0</li>
        </ul>
    </li></br>

    <li>Univariate Analysis:
        <ul>
            <li>Grouping Categorical and Numerical Columns</li>
            <li>Histogram and boxplot Numerical Columns</li>
            <li>Churn Distribuition plot</li>
            <li>Distribuiton Categorical Columns plots</li>
        </ul>
    </li></br>

    <li>Bivariate Analysis:
        <ul>
            <li>Barplot Categoricak Columns by Churn</li>
            <li>Displot of Bivariate Analysis by Churn</li>
        </ul>
    </li></br>

    <li>Multivariate Analysis:
        <ul>
            <li>Correlation heatmap</li>
        </ul>
    </li></br>

    <li>Features Encoding:
        <ul>
            <li>Drop 'customerID' because it's not a feature but a unique ID</li>
            <li>Encode target 'Churn' into 0/1</li>
            <li>Binary categorical columns — use LabelEncoder</li>
            <li>Multi-category categorical columns — use One-Hot Encoding</li>
        </ul>
    </li></br>

    <li>Features Scalling:
        <ul>
            <li>Convert TotalCharges to numeric (sometimes stored as string)</li>
            <li>Fill missing TotalCharges with median value</li>
            <li>Scale numerical features using StandardScaler (mean=0, std=1)</li>
        </ul>
    </li></br>

    <li>Modeling & Evaluation:
        <ul>
            <li>Spliting Data</li>
            <li>Modeling : Random Forest</li>
        </ul>
    </li></br>
  
    <li>Performance Evaluation:
        <ul>
            <li>Evaluate performance</li>
            <li>heatmap(confusion_matrix(y_test, y_pred</li>
            <li>Plot top 15 important features</li>
            <li>Calculate ROC-AUC</li>
        </ul>
    </li>
</ol>

<h3>Conclusion</h3>
<ul>
    <li>The current model performs reasonably well in distinguishing between churn and non-churn customers, as indicated by its high AUC score.</li>
    <li>However, the relatively low churn recall (48%) shows that a significant number of churn cases remain undetected, which could lead to potential business losses from customer attrition.</li>
    <li>This project will be continued, as there is still room to improve the model’s performance. The author is also exploring various techniques to achieve better predictive results.</li>
    <li>In the future, once the model’s performance improves, data-driven business strategy recommendations based on the model’s output will be added for actionable insights.</li>
</ul>
