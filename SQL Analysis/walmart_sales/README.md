<H1>Walmart Sales</H1>

<p>This project is an end-to-end data analysis solution designed to extract critical business insights from Walmart sales data. We utilize Python for data processing and analysis, SQL for advanced querying, and structured problem-solving techniques to solve key business questions. </p>

<h2>Steps:</h2>


<ol> 
  <li> <h3>Set Up the Environment</h3></li>
    <ul>
      <li> Used Tools: Visual Studio Code (VS Code), Python, SQL (MySQL and PostgreSQL)</li>
      <li>Goal: Create a structured workspace within VS Code and organize project folders for smooth development and data handling.</li>
    </ul>
  </li>

  <li> <h3>Download Walmart Sales Data</h3></li>
    <ul>
      <li> Data Source: download the Walmart sales datasets from Kaggle using this link: https://www.kaggle.com/datasets/najir0123/walmart-10k-sales-datasets.</li>
    </ul>
  </li>

  <li> <h3>Explore the Data</h3></li>
    <ul>
      <li> Goal: Conduct an initial data exploration to understand data distribution, check column names, types, and identify potential issues.</li>
      <li> Analysis: Use functions like .info(), .describe(), and .head() to get a quick overview of the data structure and statistics.</li>
    </ul>
  </li>

  <li> <h3>Data Cleaning</h3></li>
    <ul>
      <li> Remove Duplicates: Identify and remove duplicate entries.</li>
      <li> Handle Missing Values: Drop rows or columns with missing values if they are insignificant; fill values where essential.</li>
      <li> Fix Data Types: Ensure all columns have consistent data types (e.g., dates as datetime, prices as float).</li>
      <li> urrency Formatting: Use .replace() to handle and format currency values for analysis.</li>
      <li> Validation: Check for any remaining inconsistencies and verify the cleaned data.</li>
    </ul>
  </li>

  <li> <h3>Feature Engineering</h3></li>
    <ul>
      <li> Create New Columns: Calculate the Total Amount for each transaction by multiplying unit_price by quantity and adding this as a new column.</li>
      <li> Enhance Dataset: Adding this calculated field will streamline further SQL analysis and aggregation tasks.</li>
    </ul>
  </li>

  <li> <h3>Load Data into MySQL and PostgreSQL</h3></li>
    <ul>
      <li> Set Up Connections: Connect to MySQL and PostgreSQL using sqlalchemy and load the cleaned data into each database.</li>
      <li> Table Creation: Set up tables in both MySQL and PostgreSQL using Python SQLAlchemy to automate table creation and data insertion.</li>
      <li>Verification: Run initial SQL queries to confirm that the data has been loaded accurately.</li>
    </ul>
  </li>

  <li> <h3>SQL Analysis: Complex Queries and Business Problem Solving</h3></li>
    <ul>
      <li> Business Problem-Solving: Write and execute complex SQL queries to answer critical business questions, such as:</li>
        <ul>
          <li>Revenue trends across branches and categories.</li>
          <li>Identifying best-selling product categories.</li>
          <li>Sales performance by time, city, and payment method.</li>
          <li>Analyzing peak sales periods and customer buying patterns.</li>
          <li>Profit margin analysis by branch and category</li>
        </ul>
    </ul>
  </li>>/br>

  ![image](https://github.com/user-attachments/assets/9c4f8b7b-a187-481d-aab8-55fc5e4625cf)
