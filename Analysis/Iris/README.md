<H1>Iris Data Analysis</H1>

<p>Iris Dataset is considered as the Hello World for data science. It contains five columns namely - Petal Length, Petal Width, Sepal Length, Sepal Width, and Species Type. Iris is a flowering plant, the researchers have measured various features of the different iris flowers and recorded them digitally.</p></br>

<p>In this project I used the Iris dataset</p>
<p>The dataset can me found in this link: https://www.geeksforgeeks.org/exploratory-data-analysis-on-iris-dataset//</p>

<h3>Steps:</h3>
<ol> 
  <li> Importing necessary Python libraries:
    <ul>
      <li>In this project I needed the pandas, numpy, matplotlib, seaborn libraries</li>
    </ul>
  </li></br>

  <li>Getting Information about the Dataset:
    <ul>
      <li>Used the shape function to get the shape of dataset</li>
      <li>Used info() to get summary of the dataframe</li>
      <li>Used the describe function to get a quick statistical summary of the dataset .</li>
    </ul>
  </li></br>

  <li>Checking Missing Values:
    <ul>
      <li>Used the isnull() function to check if our data contains any missing values or not</li>
    </ul>
  </li></br>

  <li>Checking Duplicates:
    <ul>
      <li>Used drop_duplicates to see if our dataset contains any duplicates or not </li>
    </ul>
  </li></br>

  <li>Data Visualization:
    <ul>
      <li>Used sns.countplot to see the Species column whis is our target column.</li>
      <li>Used sns.scatterplot to see the relation between Sepal Length and Sepal Width</li>
      <li>Used sns.scatterplot to see the relation between Petal Length and Petal Width</li>
      <li>Used sns.pairplot to plot all the column's relationships</li>
      <li>Used .hist to see the distribution of data for various columns</li>
    </ul>
  </li></br>

  <li>Handling Correlation:
    <ul>
      <li>Used dataframe.corr() to find the pairwise correlation of all columns in the dataframe</li>
      <li>Used sns.heatmap to show a correlation between all numerical variables in the dataset</li>
      <li>Used sns.boxplot to see how the categorical value os distributed with other numerical values</li>
    </ul>
  </li></br>

  <li>Removing Outliers:
    <ul>
      <li>Used plt.hist to check the distribution of ratings from the rate column.</li>
    </ul>
  </li></br>
  
</ol>

<h3>📦 Requisitos</h3>
<ul>
  <li>Python</li>
  <li>pandas</li>
  <li>numpy</li>
  <li>matplotlib</li>
  <li>seaborn</li>
</ul>


