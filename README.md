<h1>Introduction</h1>
Exploring the Data Analytics Employment Landscape! This comprehensive analysis delves into data analyst positions, examining lucrative career opportunities, essential competencies, and the intersection of market demand with compensation in the data analytics field.
SQL code repository? Find all queries in the project_sql directory.

<h1>Background</h1>
Driven by a quest to navigate the data analyst job market more effectively, this project was born from a desire to pinpoint top-paid and in-demand skills, streamlining others work to find optimal jobs.

<h2>The questions i want to answer</h2>
1. What are the top-paying data analyst jobs?
2. What skills are required for these top-paying jobs?
3. What skills are most in demand for data analysts?
4. Which skills are associated with higher salaries?
5. What are the most optimal skills to learn?

<h1>Tools i used</h1>
1. SQL:Served as the foundation for my investigation, enabling sophisticated database queries to extract valuable market intelligence.
2. PostgreSQL: Selected as the primary database platform, perfectly suited for managing extensive job posting datasets.
3. VScode: My preferred environment for database administration and SQL query execution.
4. Git & Github: Critical components for maintaining code versioning and distributing SQL scripts and findings, facilitating teamwork and progress monitoring.

<h1>The Analysis</h1>
<h2>1. Top Paying Data Analyst Jobs</h2>
To identify the highest-paying roles, I filtered data analyst positions by average yearly salary and location, focusing on remote jobs. This query highlights the high paying opportunities in the field.
query location in project_sql folder 1st folder.
Here's the breakdown of the top data analyst jobs in 2023:

1. Wide Salary Range: Top 10 paying data analyst roles span from $184,000 to $650,000, indicating significant salary potential in the field.
2. Diverse Employers: Companies like SmartAsset, Meta, and AT&T are among those offering high salaries, showing a broad interest across different industries.
3.Job Title Variety: There's a high diversity in job titles, from Data Analyst to Director of Analytics, reflecting varied roles and specializations within data analytics.


![Screenshot 2025-05-27 151727](https://github.com/user-attachments/assets/e24d2a28-3041-4df4-be14-18319f4b8160)
Bar graph visualizing the salary for the top 10 salaries for data analysts; ChatGPT generated this graph from my SQL query results

<h2>2. Skills for Top Paying Jobs</h2>
To understand what skills are required for the top-paying jobs, I joined the job postings with the skills data, providing insights into what employers value for high-compensation roles.
Here's the breakdown of the most demanded skills for the top 10 highest paying data analyst jobs in 2023:

1. SQL is leading with a bold count of 8.
2. Python follows closely with a bold count of 7.
3. Tableau is also highly sought after, with a bold count of 6. Other skills like R, Snowflake, Pandas, and Excel show varying degrees of demand.



![Screenshot 2025-05-27 152508](https://github.com/user-attachments/assets/c7c6c07d-b911-4861-8581-83f27553f526)
Bar graph visualizing the count of skills for the top 10 paying jobs for data analysts; ChatGPT generated this graph from my SQL query results.

<h2>In-Demand Skills for Data Analysts</h2>
This query helped identify the skills most frequently requested in job postings, directing focus to areas with high demand.
Here's the breakdown of the most demanded skills for data analysts in 2023

1. SQL and Excel remain fundamental, emphasizing the need for strong foundational skills in data processing and spreadsheet manipulation.
2. Programming and Visualization Tools like Python, Tableau, and Power BI are essential, pointing towards the increasing importance of technical skills in data storytelling and decision support.
   



![Screenshot 2025-05-27 152713](https://github.com/user-attachments/assets/970fb0d6-0531-4780-aeea-be2f3b2f4590)
Table of the demand for the top 5 skills in data analyst job postings.

<h2>4. Skills Based on Salary</h2>
Exploring the average salaries associated with different skills revealed which skills are the highest paying.
Here's a breakdown of the results for top paying skills for Data Analysts:

1. High Demand for Big Data & ML Skills: Top salaries are commanded by analysts skilled in big data technologies (PySpark, Couchbase), machine learning tools (DataRobot, Jupyter), and Python libraries (Pandas, 
   NumPy), reflecting the industry's high valuation of data processing and predictive modeling capabilities.
2. Software Development & Deployment Proficiency: Knowledge in development and deployment tools (GitLab, Kubernetes, Airflow) indicates a lucrative crossover between data analysis and engineering, with a premium 
   on skills that facilitate automation and efficient data pipeline management.
3. Cloud Computing Expertise: Familiarity with cloud and data engineering tools (Elasticsearch, Databricks, GCP) underscores the growing importance of cloud-based analytics environments, suggesting that cloud 
   proficiency significantly boosts earning potential in data analytics.





![Screenshot 2025-05-27 152948](https://github.com/user-attachments/assets/5907d52b-af4f-4537-893d-90ebd7bbcc65)

<h2>5. Most Optimal Skills to Learn</h2>
Combining insights from demand and salary data, this query aimed to pinpoint skills that are both in high demand and have high salaries, offering a strategic focus for skill development.
Table of the most optimal skills for data analyst sorted by salary

Here's a breakdown of the most optimal skills for Data Analysts in 2023:

1. High-Demand Programming Languages: Python and R stand out for their high demand, with demand counts of 236 and 148 respectively. Despite their high demand, their average salaries are around $101,397 for 
   Python and $100,499 for R, indicating that proficiency in these languages is highly valued but also widely available.
2. Cloud Tools and Technologies: Skills in specialized technologies such as Snowflake, Azure, AWS, and BigQuery show significant demand with relatively high average salaries, pointing towards the growing 
   importance of cloud platforms and big data technologies in data analysis.
3. Business Intelligence and Visualization Tools: Tableau and Looker, with demand counts of 230 and 49 respectively, and average salaries around $99,288 and $103,795, highlight the critical role of data 
   visualization and business intelligence in deriving actionable insights from data.
4. Database Technologies: The demand for skills in traditional and NoSQL databases (Oracle, SQL Server, NoSQL) with average salaries ranging from $97,786 to $104,534, reflects the enduring need for data storage, 
   retrieval, and management expertise.
![Screenshot 2025-05-27 153830](https://github.com/user-attachments/assets/55b732c5-1194-494f-9ae1-e353dae2f1eb)

<h1>What i learned</h1>
Throughout this adventure, I've turbocharged my SQL toolkit with some serious firepower:

🧩 Complex Query Crafting: Mastered the art of advanced SQL, merging tables like a pro and wielding WITH clauses for ninja-level temp table maneuvers.
📊 Data Aggregation: Got cozy with GROUP BY and turned aggregate functions like COUNT() and AVG() into my data-summarizing sidekicks.
💡 Analytical Wizardry: Leveled up my real-world puzzle-solving skills, turning questions into actionable, insightful SQL queries.

<h1>CONCLUSION</h1>
From the analysis, several general insights emerged:

1. Top-Paying Data Analyst Jobs: The highest-paying jobs for data analysts that allow remote work offer a wide range of salaries, the highest at $650,000!
2. Skills for Top-Paying Jobs: High-paying data analyst jobs require advanced proficiency in SQL, suggesting it’s a critical skill for earning a top salary.
3. Most In-Demand Skills: SQL is also the most demanded skill in the data analyst job market, thus making it essential for job seekers.
4. Skills with Higher Salaries: Specialized skills, such as SVN and Solidity, are associated with the highest average salaries, indicating a premium on niche expertise.
5. Optimal Skills for Job Market Value: SQL leads in demand and offers for a high average salary, positioning it as one of the most optimal skills for data analysts to learn to maximize their market value.




