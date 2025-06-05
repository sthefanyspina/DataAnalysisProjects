<H1>Zomato Data Analysis</H1>

<p>Zomato is an Indian online food delivery and restaurant discovery platform. It allows users to find restaurants, view menus, read reviews, place orders for delivery, and make reservations. </p></br>

<p>In this project I used the Zomato dataset</p>
<p>The dataset can me found in this link: https://www.geeksforgeeks.org/zomato-data-analysis-using-python/</p>
<p>Understanding customer preferences and restaurant trends is important for making informed business decisions in food industry.</p>

<h3>Steps:</h3>
<ol> 
  <li> Importing necessary Python libraries:
    <ul>
      <li>In this project I needed the pandas, numpy, matplotlib, seaborn libraries</li>
    </ul>
  </li></br>

  <li>Creating the data frame</li></br>

  <li>Data Cleaning and Preparation:
    <ul>
      <li>Used the handleRate function to clean and convert each rating value in the 'rate' column</li>
      <li>Used df.info() to get summary of the dataframe</li>
      <li>Checked for missing or null values to identify any data gaps.</li>
    </ul>
  </li></br>

  <li>Exploring Restaurant Types:
    <ul>
      <li>Used sns.countplot to identify popular restaurant categories.</li>
      <li>Used plt.plot to count of votes for each category</li>
    </ul>
  </li></br>

  <li>Identify the Most Voted Restaurant
    <ul>
      <li>Used max_votes to find the restaurant with the highest number of votes</li>
    </ul>
  </li></br>

  <li>Online Order Availability
    <ul>
      <li>Used sns.countplot to see how many restaurants accept online orders</li>
    </ul>
  </li></br>

  <li>Analyze Ratings
    <ul>
      <li>Used plt.hist to check the distribution of ratings from the rate column.</li>
    </ul>
  </li></br>

  <li>Approximate Cost for Couples
    <ul>
      <li>Used sns.countplot in the approx_cost(for two people) column to find the preferred price range</li>
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

<h3>📦 Requisitos</h3></br>
<ul>
  <li>Python</li>
  <li>pandas</li>
  <li>numpy</li>
  <li>matplotlib</li>
  <li>seaborn</li>
</ul>

