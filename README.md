# data-analyst-gautam
Project on Exploratory Data Analysis, Descriptive Analysis, Diagnostic Analysis, Data Wrangling, and Data Quality Control using AWS services.
Project Title: Data Analysis of City of Vancouver 

Dataset: The Open Source Vancouver dataset portal is the source of the data.

![image](https://github.com/gautam2709/data-analyst-gautam/blob/main/Screenshot%202024-12-10%20005210.png)

Descriptive Analysis:

Objective: To use statistical metrics and AWS services to identify and describe the dataset's main features.

Methodology:

1.Data Collection: The Vancouver dataset portal, known to be open source, provided the data.
   
2.Data Summary: AWS Athena was used to compute descriptive statistics for the dataset's important variables.

3.Data Visualization: To illustrate the distribution and core patterns, graphs and charts were made using Excel.

![image](https://github.com/gautam2709/data-analyst-gautam/blob/main/Screenshot%202024-12-11%20012435.png)


![image](https://github.com/gautam2709/data-analyst-gautam/blob/main/Screenshot%202024-12-11%20012619.png)


![image](https://github.com/gautam2709/data-analyst-gautam/blob/main/Screenshot%202024-12-11%20012733.png)


Technologies and Tools:

AWS S3: For storing datasets.

AWS Glue: For transforming and cleaning data.

AWS Athena: For data summarization and SQL query execution.

Excel: For creating visual summaries.


Important Data Findings:

In the downtown area, there were a total of 200 cooling towers of the mechanical system type erected. Additionally, there were 380 N volunteers who participated in the data collection.

Data Wrangling of data at the City of Vancouver

Data Collection: Information was gathered from the City of Vancouver's internal systems and a number of public data sites.

Data Cleaning: To deal with missing data and normalize inconsistent entries across datasets, AWS Glue and DataBrew were utilized.

Data Transformation: New columns were added, including permit type and date. 

Storage: AWS S3 was used to store the processed datasets so they could be examined further.

Technologies and Tools:


Large datasets can be stored and arranged using AWS S3.

For cleaning and transforming data, used AWS Glue.

Data is cleaned and managed using AWS DataBrew to facilitate analysis.

