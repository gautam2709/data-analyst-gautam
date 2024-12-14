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

Methodology:

Data Collection: Information was gathered from the City of Vancouver's internal systems and a number of public data sites.

Data Cleaning: To deal with missing data and normalize inconsistent entries across datasets, AWS Glue and DataBrew were utilized.

Data Transformation: New columns were added, including permit type and date. 

Storage: AWS S3 was used to store the processed datasets so they could be examined further.

Technologies and Tools:


Large datasets can be stored and arranged using AWS S3.

For cleaning and transforming data, used AWS Glue.

Data is cleaned and managed using AWS DataBrew to facilitate analysis.

Key Findings:

Data Preparation:

The water permits and ucw research ethics dataset was considered to be a very messy dataset in which there were problems mentioned as missing values and mismatched formatting of values. Before subjecting the dataset to analysis, the AWS Glue DataBrew was used to format the dataset properly.

Data Transformation: Based on raw datasets like water permits, AWS Glue was chosen to normalize these sets and apply predefined categories to municipal data.

Data Wrangling Outcome: Through data preprocessing, the processed datasets we generated from self-developed scripts were prepared for diagnostic and predictive analysis and trends of multiple types of permits and customer service query.


![image](https://github.com/gautam2709/data-analyst-gautam/blob/main/Screenshot%202024-12-11%20023048.png)

![image](https://github.com/gautam2709/data-analyst-gautam/blob/main/Screenshot%202024-12-11%20023104.png)

![image](https://github.com/gautam2709/data-analyst-gautam/blob/main/Screenshot%202024-12-11%20023120.png)

![image](https://github.com/gautam2709/data-analyst-gautam/blob/main/Screenshot%202024-12-11%20023134.png)

The Data Quality Control with Reference to the City of Vancouver

Methodology:

Data Collection: .primary data was gathered from the City of Vancouver’s open data repository alongside internal municipal datasets for a variety of domains that can include water permits in downtown region was active status

Data Quality Checks: AWS Glue automatically checked for same records, missing values and incorrect record format in multiple datasets.

Data Governance: Because of AWS IAM (Identity and Access Management) and AWS KMS (Key Management Service) were performed to maintain adequate Identity and access and controls encryption on sensitive data.

![image](https://github.com/gautam2709/data-analyst-gautam/blob/main/Screenshot%202024-12-11%20023145.png)

![image](https://github.com/gautam2709/data-analyst-gautam/blob/main/Screenshot%202024-12-11%20023215.png)

Tools and Technologies:

AWS S3: It is used for storing unrefined and refined data sets with municipal information.

AWS Glue: Automated the ETL process and was handling data quality check.

AWS IAM & KMS: Applied to regulate access and security data and files through encryption.

Key Findings:

Data Integrity: Their analysis revealed concerns about duality and wrong types of data within permits data , such as business permits and  dates. These problems were solved by using AWS Glue, and now all the data is of high quality for different departments.

Automation of Data Quality Processes: AWS Glue was used in order to have less human intervention in the eventual fixing of data quality problems that range from double indexing to null values. This made it possible to maintain data integrity across the various dataset collected during the project.

Data Governance Implementation: AWS IAM and KMS were used for the protection of key data; it meant that only the authorized personnel was allowed to interact with the data. This ensured the city’s data governance policies that were strictly adhered to were met to the letter.

