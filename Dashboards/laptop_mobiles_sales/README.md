<H1>Laptop and Mobile Analysis and Dashboard</H1>

<p>In this project I used the Mobiles and Laptop Sales dataset</p>
<p>The dataset can me found in this link: https://www.kaggle.com/datasets/vinothkannaece/mobiles-and-laptop-sales-data</p>
<p>This dataset simulates sales transactions for mobile phones and laptops, including product specifications, customer details, and sales information. It contains 50,000 rows of randomly generated data to help analyze product sales trends, customer purchasing behavior, and regional distribution of sales. </p> </br>

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
      <li>Used the replace function to replace all the empty rows with NAN.</li>
      <li>Used the dropna function to drop the missing/null values from our dataset.</li>
    </ul>
  </li></br>

  <li>Data Type Conversion:
    <ul>
      <li>In this dataset I didn't need to made any conversion, all the columns were with the correct types.</li>
    </ul>
  </li></br>

  <li>Save the data
    <ul>
      <li>I saved the data using the df.to_csv(new_name.csv, index=False)</li>
    </ul>
  </li>
</ol></br>

![image](https://github.com/user-attachments/assets/1d1aaed3-47ea-45b5-a283-d60a6362c0f1)
