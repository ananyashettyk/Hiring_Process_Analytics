# Hiring_Process_Analytics
This data analysis project is aimed to analyze the company’s hiring process data. The hiring process is a crucial function of any company, and understanding trends such as the number of rejections, interviews, job types, and vacancies can provide valuable insights for the hiring department. Here, we are analyzing the data using Excel to improve the company’s hiring process

The approach involved handling missing data, detecting and handling outliers, summarizing data, and creating visualizations using Excel. After cleaning and preparing the data, I summarized my findings using statistical measures and created visualizations using Excel charts and graphs

Used Microsoft Excel for analysis and visualisation. Excel was chosen due to its easy-to-use, powerful data manipulation capabilities, and built-in charting and graphing features.

Initial steps
Handling Missing Data : There were 15 missing values in “event_name” column. Replaced it with “Don’t want to say”.
There were 1 missing values in “Post Name” and “Offered Salary” each. Replaced it with “c5” and “49990” respectively. These changes were made by taking “department”, “Post Name” “Offered Salary”  and “event_name” into consideration, by taking average for the “Offered Salary” and mode for the “Post Name”
Post Name -> replaced c-10 to c10 for 232 records
Handline Outliers : 
By using the formula =QUARTILE(), Q1, Q3, IQR, Low and High were calculated and then using these values outliers were detected.
3 outliers found were found, and removed those 3 records.
