# [StackOverflow Developer Survey Analysis](https://github.com/aaysul/stackoverflow-developer-survey-analysis/tree/main)
### A Job Market Demand and Supply Analysis
This project involves analysis of the demand and supply between the current jobs and the available developer pool all over the world. The analysis is based on the 2019 Stack Overflow Developer Survey. The purpose of the analysis is to identify the current and future technology trends in the developer pool accross the world with regards to programming languages, databases, platforms and Web Frameworks. 

Following is the detail of the steps involved in the process that led to successful completion of this analysis. The insights achieved in the process were share in the final report.

## 1. Data Collection

Prior to the analysis relevant data needs to be collected which requires different techniques for data gathering. Initially two different techniques have been deployed to practice data collection.

* APIs
* Web Scraping

The data related to available jobs was collected from the API running on the IBM Skills Network. The python lab for the data collection using API is available [here](https://github.com/aaysul/stackoverflow-developer-survey-analysis/blob/main/Collecting_Jobs_data_Using_API-Questions.ipynb).
The data is provided in JSON format with fields including 'Job Title', 'Job Experience Required', 'Key Skills', 'Role Category', 'Role', 'Location', 'Functional Area' and 'Industry'. The data was segregated and transfered into Excel Workbook.

The second mode of data collection used was web scraping. This data was also provided by the IBM Skills Network and provided the information on popular programming lanaguages and associated annual average salary. The lab for this step is available [here](https://github.com/aaysul/stackoverflow-developer-survey-analysis/blob/main/Web-Scraping-Lab.ipynb). The data was collected using python BeautifulSoup library and converted for storage to Excel CSV file.

## 2. Exploring Dataset

In this step the Stack Overflow Developer Survey 2019 dataset was used. The link for survey dataset is available [here](https://insights.stackoverflow.com/survey/). The python lab for this step can be accessed [here](https://github.com/aaysul/stackoverflow-developer-survey-analysis/blob/main/M1ExploreDataSet-lab.ipynb).
In this lab the dataset was explored for its shape and contents, the countries from which the respondents to the survey belonged and the age groups of the respondents.

## 3. Data Wrangling

The next step was data wrangling involving finding and removing duplicates, finding and imputing missing values and normalizing data. The lab can be accessed [here](https://github.com/aaysul/stackoverflow-developer-survey-analysis/blob/main/M2DataWrangling-lab.ipynb).

## 4. Exploratory Data Analysis (EDA)

After the data wrangling process, it was time for exploratory data analysis or EDA was performed to understand distribution of data, identifying and removing outliers, and finding correlations among different variables. The python lab for this step is accessible [here](https://github.com/aaysul/stackoverflow-developer-survey-analysis/blob/main/M3ExploratoryDataAnalysis-lab.ipynb).

## 5. SQL Queries and Visualizations 

An important aspect of data engineering is to be able to run SQL queries on databases. This step utilized the python Sqlite library to run SQL queries and then create visualizations for data distribution, correlations, composition and comparisons. The python lab for this step is available [here](https://github.com/aaysul/stackoverflow-developer-survey-analysis/blob/main/M4DataVisualization-lab.ipynb).

## 6. Dashboards

Once the data has been analyzed it was time to create dashboards. The dashboards were created using IBM Cognos Analyitcs platform. These dashboards provide the current and future technology trends related to programming languages, databases, platforms and web frameworks along with the demographic information of the respondents. The created dashboards were exported to pdf file accessible [here](https://github.com/aaysul/stackoverflow-developer-survey-analysis/blob/main/Developer%20Survey%20Dashboard.pdf). 

## 7. Presentation

The final presentation has been created to explain the entire process including the employed methodology for the analysis, the steps involved in the process and share the insights achieved through the analysis with the viewer. The comparisons have been drawn to inform the viewer about the current demand in the job market and the available developer pool accross the world. To access the presentation click [here](https://github.com/aaysul/stackoverflow-developer-survey-analysis/blob/main/Developer%20Survey%20Analysis.pdf).


