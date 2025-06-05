<H1>Houses Price Prediction</H1>

<p>House price prediction is a problem in the real estate industry to make informed decisions. By using machine learning algorithms we can predict the price of a house based on various features such as location, size, number of bedrooms and other relevant factors.</p></br>

<p>In this project I used the House Price dataset</p>
<p>The dataset can me found in this link: https://www.geeksforgeeks.org/house-price-prediction-using-machine-learning-in-python/ </p>

<h3>Steps:</h3>
<ol> 
  <li> Importing necessary Python libraries:
    <ul>
      <li>In this project I needed the pandas, matplotlib, seaborn libraries</li>
    </ul>
  </li></br>

  <li>Creating the data frame</li></br>

  <li>Data Preprocessing:
    <ul>
      <li>I categorized the features depending on their datatype (int, float, object) and then calculate the number of them</li>
    </ul>
  </li></br>

  <li>Exploratory Data Analysis:
    <ul>
      <li>Used sns.heatmap to examine all your variables.</li>
      <li>Used sns.barplot to analyze the different categorical features</li>
      <li>Used sns.barplot to findout the actual count of each four features separately</li>
    </ul>
  </li></br>

  <li>Data Cleaning:
    <ul>
      <li>Used drop to remove the Id Column because will not be participating in any prediction</li>
      <li>Replaced SalePrice empty values with their mean values to make the data distribution symmetric.</li>
      <li>Used dropna to drop records with null values</li>
      <li>Used isnull() to check features which have null values</li>
    </ul>
  </li></br>

  <li>OneHotEncoder - For Label categorical features:
    <ul>
      <li>Used One hot Encoding to convert categorical data into binary vectors</li>
    </ul>
  </li></br>

  <li>Splitting Dataset into Training and Testing:
    <ul>
      <li>Used train_test_split to split the dataset into trainig and testing</li>
    </ul>
  </li></br>

  <li>Model Training and Accuracy:
    <ul>
      <li>Used Support vector Machine: used the SVR() function to create the Support vector Machine</li>
      <li>Random Forest Regression: used RandomForestRegressor to create the algorithm  </li>
      <li>Linear Regression: used the LinearRegression() function for modeling the relationship between a dependent variable and one or more independent variables.</li>
    </ul>
  </li></br>

   <li>Ratings Comparison - Online vs Offline Orders
    <ul>
      <li>Used plt.figure and sns.boxplot to compare ratings between restaurants that accept online orders and those that don't.</li>
    </ul>
  </li></br>

   <li>Order Mode Preferences by Restaurant Type
    <ul>
      <li>Used dataframe.pivot_table to create a pivot table counting restaurants by type and online order availability.</li>
      <li>Used sns.heatmap to show the relationship</li>
    </ul>
  </li></br>
  
</ol>

<h3>📦 Requisitos</h3>
<ul>
  <li>Python</li>
  <li>pandas</li>
  <li>matplotlib</li>
  <li>seaborn</li>
  <li>sklearn</li>
</ul>


