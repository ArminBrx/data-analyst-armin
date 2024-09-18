# data-analyst-armin

# Descriptive Analysis For Office of The President
Project Description: Descriptive Analysis of Student Complaint Patterns  
Project Title: Understanding Complaint Patterns of Students at University Canada West (UCW)  
Objective: The primary goal of this project is to conduct a descriptive analysis of student complaint data at University Canada West (UCW). Through this analysis, we aim to summarize key characteristics of complaints submitted by students, understand trends in complaint submission based on enrollment status, and generate insights that can help inform decision-making in the Office of the President regarding complaint resolution.
Dataset:  
The dataset includes information about students at UCW, particularly focusing on their enrollment status in relation to the complaints they have submitted. 

Key features of the dataset include:
•	Enrollment ID: Unique identifier for each student's enrollment.
•	Student ID: Identification number for each student.
•	First Name: The student's first name.
•	Last Name: The student's last name.
•	Gender: Gender of the student.
•	Date of Birth: The student's date of birth.
•	Program: The academic program in which the student is enrolled.
•	Years of Study: The number of years the student has been studying at UCW.
•	Enrollment Status: Indicates whether the student is currently enrolled or not.

([https://github.com/arminbrx/data-analyst-armin/main/images/OfficeofThePresident.png](https://github.com/ArminBrx/data-analyst-armin/blob/main/Images/OfficeofThePresident.png))

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


# Data Quality Control For Office of The President

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


# Descriptive Analysis City of Vancouver
Project Description: Descriptive Analysis of 3-1-1 Contact Center Call Data  
Project Title: Understanding Call Handling and Average Call Answer Time at the City of Vancouver’s 3-1-1 Contact Center  
Objective: The primary objective of this project is to conduct a descriptive analysis of call data from the City of Vancouver’s 3-1-1 Contact Center. This analysis aims to summarize key call center performance metrics such as the average speed of answer (ASA), service level, and call handling trends for 2023 and 2024. The insights from this analysis will help inform strategies to improve customer service efficiency and response times.

Dataset:  
The dataset includes call center data from the City of Vancouver’s 3-1-1 Contact Center, focusing on call volume and performance metrics over 2023 and 2024. Key features of the dataset include:
•	Date: The date when the data was recorded.
•	Calls Offered: Total number of calls received by the call center.
•	Calls Handled: Number of calls successfully answered by the call center staff.
•	Calls Abandoned: Number of calls abandoned by callers before being answered.
•	Average Speed of Answer (ASA): The average time it takes to answer a call.
•	Service Level: The percentage of calls answered within a pre-defined time target.
•	BI_ID: A unique identifier for the business intelligence system.

Methodology:  
1.	Data Collection and Preparation:
•	Load the dataset using data analysis tools (e.g., Python, Excel).
•	Perform data cleaning to address any missing values, correct data types, and remove duplicates.
•	Filter the dataset to focus on key periods for comparison between 2023 and 2024.

2.	Descriptive Statistics:
•	Calculate summary statistics for key variables, including:
o	Average speed of answer (ASA) for 2023 and 2024.
o	Total number of calls offered, handled, and abandoned.
o	Service level percentage for each year.

3.	Data Visualization:
•	Create visual representations to illustrate findings:
o	Line charts showing the average speed of answer (ASA) trends for 2023 and 2024.
o	Bar charts showing the number of calls offered, handled, and abandoned for each month.
o	Pie charts representing the proportion of calls handled versus abandoned.

4.	Segmentation by Year:
•	Analyze call performance trends for 2023 and 2024 to identify significant changes in call handling and average speed of answer.
•	Further break down the analysis by months to identify peak periods or changes in service levels.

5.	Insights and Findings:
•	Summarize the insights derived from the analysis, highlighting:
o	Trends in average speed of answer for 2023 vs. 2024.
o	The relationship between call volume and service level performance.
o	Patterns in call abandonment and their potential impact on customer satisfaction.

6.	Recommendations:
•	Provide actionable recommendations based on the findings to support the City of Vancouver in:
o	Reducing call abandonment rates and improving average speed of answer.
o	Enhancing service level performance during peak periods.
o	Optimizing call center staffing to handle fluctuating call volumes efficiently.

Tools and Technologies:
•	Python (Pandas, Matplotlib, Seaborn) or Excel for data analysis.
•	Data visualization tools (Tableau or Power BI) for creating charts and dashboards.

Deliverables:
•	A detailed report summarizing the methods, findings, and recommendations.
•	Visualizations and dashboards to present key insights clearly.
•	A presentation for stakeholders to communicate important findings and suggestions for future action.

This descriptive analysis project focuses on understanding call handling trends and the average speed of answer at the City of Vancouver’s 3-1-1 Contact Center, helping improve service delivery and customer satisfaction.

# Data Quality Control for City of Vancouver
Project Description: Data Quality Control Initiative at the City of Vancouver’s 3-1-1 Contact Center  
Project Title: Implementation of Data Quality Control Measures Using AWS Glue and Glue DataBrew at the City of Vancouver’s 3-1-1 Contact Center  
Objective: The primary objective of this project is to establish a comprehensive Data Quality Control (DQC) framework for the City of Vancouver’s 3-1-1 Contact Center. This initiative aims to ensure the accuracy, completeness, and consistency of call data, particularly focusing on metrics like the average speed of answer, service level, and call handling. The goal is to enhance the quality of data being used for performance analysis and decision-making.

Background:  
The City of Vancouver’s 3-1-1 Contact Center handles thousands of calls daily, making it critical to maintain high-quality data for analyzing performance and ensuring customer satisfaction. Issues such as data inaccuracies, incomplete records, and inconsistencies in call metrics can affect the reliability of the insights derived from the data. This project utilizes AWS Glue and Glue DataBrew to implement a robust data quality control system that will mitigate these issues and ensure reliable data.

Scope:  
The project focuses on the following key areas using AWS Glue and Glue DataBrew:
•	Data Profiling: Assessing the quality of call center data.
•	Data Cleansing: Developing automated processes to eliminate inaccuracies, handle missing data, and standardize formats.
•	Data Validation: Implementing validation rules to ensure data integrity across key metrics.
•	Monitoring and Reporting: Establishing ongoing monitoring processes to track data quality in real time.
•	Training and Awareness: Educating staff on maintaining data quality best practices.

Methodology:  
1.	Current State Assessment:
•	Conduct an analysis of the existing 3-1-1 call center data, identifying issues like missing call data, inconsistent formats, and duplicates.
•	Use AWS Glue’s data cataloging and profiling tools to review key datasets (calls offered, handled, abandoned, and ASA).

2.	Data Profiling:
•	Leverage AWS Glue DataBrew to assess data quality, focusing on key aspects such as completeness, validity, consistency, and accuracy.
•	Document the findings, highlighting datasets requiring immediate data quality improvement.

3.	Establish Data Quality Metrics:
•	Define clear data quality metrics and KPIs for the project:
o	Error rates for missing or incorrect call data.
o	Duplicate records within the call logs.
o	Consistency of average speed of answer (ASA) and service level data.

4.	Data Cleansing Processes:
•	Use AWS Glue DataBrew to create automated workflows for data cleansing:
o	Remove duplicates, correct incorrect values, and standardize formats (e.g., date formats, call metrics).
o	Impute missing values for critical fields like ASA and service level to ensure data completeness.

5.	Validation Rules and Procedures:
•	Set up validation rules within AWS Glue to verify the integrity of new call data entries.
•	Establish data entry guidelines for call center staff to promote consistency in logging key call metrics.

6.	Monitoring and Reporting:
•	Implement real-time data quality monitoring using AWS Glue DataBrew dashboards to track deviations in key metrics.
•	Schedule regular reports on data quality performance, highlighting trends and issues in call data accuracy.

7.	Training and Best Practices:
•	Develop training materials to educate call center and data management staff on data quality principles and the use of AWS Glue DataBrew.
•	Promote best practices in data entry, processing, and monitoring, fostering a culture of accountability for data quality.

8.	Feedback Mechanism:
•	Establish a feedback loop with call center managers and staff to continually improve data quality processes based on user input and data analysis outcomes.

Tools and Technologies:
•	AWS Glue: For cataloging, profiling, and processing call data.
•	AWS Glue DataBrew: For visual data preparation, profiling, and automated data cleansing workflows.
•	Python/SQL: For custom validation scripts and data cleansing tasks.
•	Data visualization tools (Tableau or Power BI): For monitoring and reporting data quality metrics.

Deliverables:
•	A comprehensive Data Quality Control Plan outlining processes, metrics, and responsibilities.
•	Documentation of Data Quality Metrics and KPIs being tracked.
•	Cleaned and validated call center datasets ready for analysis.
•	Training resources, including materials and workshops for staff education on data quality practices.
•	A Monitoring Dashboard visualizing data quality metrics in real-time.

Timeline:  
•	Expected completion of the project: 6-8 weeks, including assessment, implementation, training, and monitoring setup.

This Data Quality Control initiative using AWS Glue and Glue DataBrew ensures that the City of Vancouver’s 3-1-1 Contact Center maintains high-quality data for performance analysis, leading to improved decision-making and better customer service outcomes.
