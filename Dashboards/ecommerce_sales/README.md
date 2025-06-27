<H1>Eccomerce Sales Dashboard</H1>

<p>Amazon Prime is one of the most popular media and video streaming platforms. They have close to 10000 movies or tv shows available on their platform, as of mid-2021, they have over 200M Subscribers globally</p>

<p>In this project I used the Eccomerce Sales dataset</p>
<p>The dataset can me found in this link: https://docs.google.com/spreadsheets/d/1L6aBX0uNlzKiJb7JHdkNUile18s9CI4r/edit?gid=1589100670#gid=1589100670</p>
<p>This dataset contains the data of eccomerce sales. </p> </br>

<p>Steps:</p>
<ol> 
  <li> Load the csv file:
    <ul>
      <li>Used the read_csv() to load my dataset into a Pandas DataFrame.</li>
    </ul>
  </li> </br>

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

<img src="https://github.com/sthefanyspina/sthefanys.tech/blob/main/src/Assets/Projects/EcommerceSalesAnalysis.png"/>
