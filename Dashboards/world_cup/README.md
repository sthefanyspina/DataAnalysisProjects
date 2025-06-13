<H1>NBA Data Analysis and Dashboard</H1>

<p>The National Basketball Association (NBA) is one of the most popular watched sports leagues in the world, with millions of fans tuning in to watch their favorite teams and players compete on the court. </p></br>

<p>In this project I used three diferents datasets</p>
<p>The first can me found in this link: https://www.kaggle.com/datasets/ulrikthygepedersen/nba-player-salaries</p>
<p>This dataset provides a detailed breakdown of the salaries earned by NBA players based on their individual attributes and career trajectory.</p>
<p>The dataset includes information on a variety of player attributes, including age, height, weight, position, and years of experience. It also includes data on each player's career statistics, such as points per game, rebounds per game, and assists per game, among others.</p>
<p>By analyzing this data, fans and analysts can gain insights into how different attributes and career milestones impact NBA player salaries. They can also identify trends and patterns that might inform player evaluations and team-building strategies.</p>
<p>The dataset is updated daily with the latest results. </p> </br>

<p>The second and third datasets can be found in this link: https://www.kaggle.com/datasets/eoinamoore/historical-nba-data-and-player-box-scores</p>
<p>I used the PlayerStatistics.csv - The centerpiece of the dataset, this file contains detailed box scores for every individual player in NBA history, game by game.</p>
<p>And the Players.csv - Biographical information for every player, including height, weight, and position, enabling detailed player analysis across eras.</p></br>

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
    <ul>Used the dropna function to drop the missing/null values from our dataset.</ul>
  </li>

  <li>Data Type Conversion:
    <ul>Used the astype to convert the column types.</ul>
  </li>

  <li>Save the data
    <ul>I saved the data using the df.to_csv(new_name.csv, index=False)</ul>
  </li>
</ol>

![image](https://github.com/user-attachments/assets/d57ebb0d-975c-4fd9-a7eb-34ddf26e41c5)
