<H1>Eletric Vehicles Data Analysis and Dashboard</H1>

<p>In this project I used the Eletric Vehicles dataset</p>
<p>The dataset can be found in this link: https://www.kaggle.com/datasets/sahirmaharajj/electric-vehicle-population</p>
</br>

<p>This dataset shows the Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs) that are currently registered through Washington State Department of Licensing (DOL).

A Battery Electric Vehicle (BEV) is an all-electric vehicle using one or more batteries to store the electrical energy that powers the motor and is charged by plugging the vehicle in to an electric power source. A Plug-in Hybrid Electric Vehicle (PHEV) is a vehicle that uses one or more batteries to power an electric motor; uses another fuel, such as gasoline or diesel, to power an internal combustion engine or other propulsion source; and is charged by plugging the vehicle in to an electric power source. </p></br>

<p>Steps:</p>
<ol> 
  <li> Load the csv file:
    <ul>
      <li>Used the read_csv() to load my dataset into a Pandas DataFrame.</li>
    </ul>
  </li>

  <li>Explore the data:
    <ul>
      <li>Used the function head to call the first 5 rows of the dataset. </li>
      <li>Used the info function, that gives the number of columns, column labels, column data types, memory usage, range index, and the number of cells in each column (non-null values).</li>
      <li>Used the describe function, that gives some statistical data like percentile, mean and standard deviation of the numerical values of the Series or DataFrame.</li>
    </ul>
  </li>

  <li>Identify and Handle Missing Values:
    <ul>Used isnull function to identify missing values in the dataset.</ul>
    <ul>Used the replace function to replace all the empty rows with NAN.</ul>
    <ul>Used the dropna function to drop the missing/null values from our dataset.</ul>
  </li>

  <li>Data Type Conversion:
    <ul>In this dataset I didn't need to made any conversion, all the columns were with the correct types.</ul>
  </li>

  <li>Save the data
    <ul>I saved the data using the df.to_csv(new_name.csv, index=False)</ul>
  </li>
</ol>

<img src="https://github.com/sthefanyspina/sthefanys.tech/blob/main/src/Assets/Projects/EletricVehicles.png"/>
