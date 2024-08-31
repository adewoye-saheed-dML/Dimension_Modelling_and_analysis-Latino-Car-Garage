<h1>Latino Car Garage Project</h1>
<p>Welcome to the Latino Car Garage project! This repository contains a detailed dimension modelling and analysis of a car garage's operational data. The project focuses on creating a star schema for efficient data analysis and reporting.</p>
<h2>Project Overview</h2>
<p>The Latino Car Garage project involves designing a dimension model based on garage invoice receipts and analyzing the dataset to gain actionable insights. The star schema includes several dimensions that are crucial for understanding garage operations.</p>
<h2>Dimension Modeling</h2>
<p>The dimension model is designed using a star schema and includes the following dimensions:</p>
<ul>
<li><strong>Invoice:</strong> Details of each invoice issued by the garage.</li>
<li><strong>Dates:</strong> Date-related information for each transaction.</li>
<li><strong>Job:</strong> Details about the jobs performed in the garage.</li>
<li><strong>Vehicle:</strong> Information about the vehicles serviced.</li>
<li><strong>Parts:</strong> Data on the parts used in servicing vehicles.</li>
<li><strong>Customer:</strong> Information about the customers who visited the garage.</li>
</ul>
<h2>Key Features</h2>
<ul>
<li><strong>Star Schema Design:</strong> The schema organizes data into fact and dimension tables for optimal performance in querying and reporting.</li>
<li><strong>Invoice Data:</strong> Includes transactional details for each invoice.</li>
<li><strong>Date Dimension:</strong> Facilitates time-based analysis and reporting.</li>
<li><strong>Job and Vehicle Dimensions:</strong> Provides insights into the types of jobs and vehicles serviced.</li>
<li><strong>Parts Dimension:</strong> Tracks the parts used in services, allowing for inventory and cost analysis.</li>
<li><strong>Customer Dimension:</strong> Helps in understanding customer demographics and service patterns.</li>
</ul>
<h2>Data Analysis</h2>
<p>The dataset was analyzed to extract meaningful insights, including:</p>
<ul>
<li><strong>Sales Trends:</strong> Analysis of sales over time.</li>
<li><strong>Job Performance:</strong> Evaluation of job types and their frequency.</li>
<li><strong>Parts Usage:</strong> Insights into the most frequently used parts and their impact on overall costs.</li>
<li><strong>Customer Behavior:</strong> Understanding customer preferences and service patterns.</li>
</ul>
<h2>How to Use</h2>
<ol>
<li><strong>Clone the Repository:</strong> Use <code>git clone</code> to get a copy of this project.</li>
<li><strong>Explore the Schema:</strong> Review the <code>schema_design</code> folder for the star schema diagrams and descriptions.</li>
<li><strong>Analyze the Data:</strong> Check out the <code>analysis</code> folder for scripts and results of the data analysis.</li>
<li><strong>Run Analysis Scripts:</strong> Use Python or MySQL to execute the analysis scripts provided.</li>
</ol>
<h2>Requirements</h2>
<ul>
<li>Python 3.11</li>
<li>SQL Database (MySQL)</li>
<li>Pandas and other relevant libraries for data analysis</li>
</ul>
<h2>Contributing</h2>
<p>Feel free to contribute to this project by submitting pull requests or opening issues. Your feedback and improvements are welcome!</p>
