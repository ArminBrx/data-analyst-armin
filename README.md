# data-analyst-armin

Descriptive Analysis  
Project Description: Descriptive Analysis of Student Complaint Patterns  
Project Title: Understanding Complaint Patterns of Students at University Canada West (UCW)  
Objective: The primary goal of this project is to conduct a descriptive analysis of student complaint data at University Canada West (UCW). Through this analysis, we aim to summarize key characteristics of complaints submitted by students, understand trends in complaint submission based on enrollment status, and generate insights that can help inform decision-making in the Office of the President regarding complaint resolution.
Dataset:  
The dataset includes information about students at UCW, particularly focusing on their enrollment status in relation to the complaints they have submitted. Key features of the dataset include:
•	Enrollment ID: Unique identifier for each student's enrollment.
•	Student ID: Identification number for each student.
•	First Name: The student's first name.
•	Last Name: The student's last name.
•	Gender: Gender of the student.
•	Date of Birth: The student's date of birth.
•	Program: The academic program in which the student is enrolled.
•	Years of Study: The number of years the student has been studying at UCW.
•	Enrollment Status: Indicates whether the student is currently enrolled or not.
Methodology:  
1.	Data Collection and Preparation:
o	Load the dataset using data analysis tools (e.g., Python, Excel).
o	Perform data cleaning to address any missing values, correct data types, and remove duplicates.
o	Filter the dataset to separate complaints from enrolled and non-enrolled students.
2.	Descriptive Statistics:
•	Calculate summary statistics for key variables, including:
o	The number of complaints submitted by enrolled students versus non-enrolled students.
o	Gender distribution among those who submitted complaints.
o	Distribution of complaints based on the academic program and years of study.
3.	Data Visualization:
•	Create visual representations to illustrate findings:
o	Bar charts showing the proportion of complaints from enrolled vs. non-enrolled students.
o	Pie charts representing the gender distribution among complainants.
o	Line charts depicting trends in complaints over the study period, broken down by enrollment status.
4.	Segmentation by Enrollment Status:
•	Analyze the patterns of complaints based on the enrollment status of students (currently enrolled vs. not enrolled).
•	Further break down the complaints by other demographic factors such as gender and academic program to identify trends.
5.	Insights and Findings:
•	Summarize the insights derived from the analysis, highlighting:
o	Which group (enrolled or non-enrolled) tends to submit more complaints.
o	Any significant patterns in complaints based on gender or academic program.
o	The relation between years of study and the likelihood of submitting complaints.

6.	Recommendations:
•	Provide actionable recommendations based on the findings to support the Office of the President in:
o	Improving complaint resolution processes for both enrolled and non-enrolled students.
o	Addressing any patterns in complaint behaviour (e.g., gender or program-specific issues).
o	Developing targeted interventions for the most frequent categories of complaints.
Tools and Technologies:
•	Excel for data analysis.
•	Data visualization tools (Tableau or Power BI) for creating charts and dashboards.
Deliverables:
•	A detailed report summarizing the methods, findings, and recommendations.
•	Visualizations and dashboards to present key insights clearly.
•	A presentation for stakeholders to communicate important findings and suggestions for future action.
This descriptive analysis project aims to provide a comprehensive understanding of complaint patterns among students at UCW, enabling the Office of the President to enhance the complaint resolution process and improve overall student satisfaction. 
Data Quality Control  
Project Description: Data Quality Control Initiative at University Canada West (UCW)  
Project Title: Implementation of Data Quality Control Measures Using AWS Glue and Glue DataBrew at UCW  
Objective: The primary objective of this project is to establish a comprehensive Data Quality Control (DQC) framework at University Canada West (UCW) using AWS Glue and Glue DataBrew. This framework ensures the accuracy, completeness, consistency, and reliability of student data, particularly in the context of complaint submissions. The aim is to enhance the quality of data being analyzed and improve decision-making in the university’s administrative processes.
Background:  
As UCW processes growing volumes of student data related to complaints, enrollment, and academic performance, issues with data quality—such as inaccuracies, duplicates, and inconsistent formats—have surfaced. These issues could lead to incorrect reporting and suboptimal administrative actions. This project aims to implement robust data quality control measures using AWS Glue and Glue DataBrew to mitigate these risks and ensure high-quality data for analysis and decision-making.
Scope:  
The project focuses on the following key areas using AWS Glue and Glue DataBrew:
•	Data Profiling: Analyzing existing datasets to assess data quality.
•	Data Cleansing: Developing automated processes to correct inaccuracies, eliminate duplicates, and standardize formats.
•	Data Validation: Implementing validation rules to ensure data integrity before analysis.
•	Monitoring and Reporting: Setting up ongoing monitoring processes and dashboards to track data quality metrics over time.
•	Training and Awareness: Developing resources to educate staff on maintaining data quality best practices.
Methodology:  
1.	Current State Assessment:
o	Conduct an in-depth analysis of existing student complaint data, identifying quality issues such as missing values, duplicates, and incorrect formats.
o	Use AWS Glue's built-in data cataloging and profiling features to identify key datasets impacting complaint resolution workflows.
2.	Data Profiling:
o	Leverage AWS Glue DataBrew to analyze datasets, focusing on key data quality aspects: completeness, uniqueness, validity, consistency, and accuracy.
o	Document the findings, including datasets requiring immediate attention and the specific types of quality issues encountered.
3.	Establish Data Quality Metrics:
•	Define clear data quality metrics and key performance indicators (KPIs) such as:
o	Error rates (e.g., missing enrollment IDs, incorrect dates of birth).
o	Duplicate records within student enrollment or complaint data.
o	Compliance with data standards (e.g., format consistency for names, dates).
4.	Data Cleansing Processes:
•	Use AWS Glue DataBrew to build automated data cleansing workflows:
o	Remove duplicates, correct invalid data entries, and standardize formats (e.g., consistent date formats).
o	Implement imputation techniques to fill missing values, ensuring data completeness.
5.	Validation Rules and Procedures:
o	Set up validation rules within AWS Glue to check for errors in incoming data (e.g., checking enrollment status consistency).
o	Create data entry guidelines and validation scripts to prevent poor-quality data from entering the system.
6.	Monitoring and Reporting:
o	Implement real-time data quality monitoring using AWS Glue DataBrew dashboards, providing alerts for deviations in key metrics.
o	Schedule regular reports summarizing data quality performance, including trends and outliers based on established KPIs.
7.	Training and Best Practices:
o	Develop training materials and conduct workshops to educate university staff on data quality principles and the use of AWS Glue DataBrew.
o	Promote best practices in data entry, maintenance, and governance, fostering a culture of accountability for maintaining data quality.
8.	Feedback Mechanism:
o	Establish a feedback loop with data users (administrative and academic staff) to continually improve data quality processes based on practical experience and observed results.
Tools and Technologies:
•	AWS Glue: For cataloging, profiling, and processing data.
•	AWS Glue DataBrew: For visual data preparation, profiling, and automated data cleansing workflows.
•	Python/SQL: For custom validation scripts and data cleansing tasks.
•	Data visualization tools (Tableau or Power BI): For monitoring and reporting data quality metrics.
Deliverables:
•	A comprehensive Data Quality Control Plan detailing processes, metrics, and responsibilities.
•	Documentation of Data Quality Metrics and KPIs being tracked.
•	Cleaned and validated datasets ready for analysis and reporting.
•	Training resources, including materials and workshops to educate staff on data quality best practices.
•	A Monitoring Dashboard visualizing data quality metrics in real-time using AWS Glue DataBrew.
Timeline:  
•	Expected completion of the project: 6-8 weeks, including assessment, implementation, training, and monitoring setup.
This Data Quality Control initiative using AWS Glue and Glue DataBrew empowers UCW to enhance the integrity and reliability of its student complaint and enrollment data. By improving data quality, UCW can make more informed decisions, improve operational efficiency, and ensure regulatory compliance where necessary.
