# Data-Analysis-using-R
R is a powerful language used widely for data analysis and statistical computing. Learn how to investigate and summarize data sets using R and eventually create your own analysis.

# Table of Content
1. About Data Analysis
2. ETL (Extract, Transform, and Load)
3. Data Manipulation in R
4. EDA (Exploratory Data Analysis)
5. Statistics Essentials for Analytics
6. Discriptive Statistics
7. Probabilty and It's Uses
8. Statistical Inference
9. Statistical Testing of Data
10. Data Visualization
11. Data Mining
12. Anova and Sentiment Analysis


# 1. About Data Analystics
**Data Analytics** is the science of examining raw data with the purpose of drawing conclusions about that information. It is all about discovering useful information from the data to support decision-making. This process involves inspecting, cleansing, transforming & modeling data.

Data analystics refers to the techniques to analyes data to enchance productivity and business gain.

**Definition**: Data Analysis is a process of inspecting, cleaning, transforming, and modeling data with the goal of discovering useful information, suggesting conclusions, and supporting decision-making.

#### What does a Data Analyst do?
**Data analysts translate numbers into plain English.** Every business collects data, like sales figures, market research, logistics, or transportation costs. A data analyst’s job is to take that data and use it to help companies to make better business decisions.


# 2. ETL (Extract, Transform and Load)
ETL is defined as a process that extracts the data from different RDBMS source systems or other data sources, then transforms the data (like applying calculations, concatenations, etc.) and finally loads the data into the Data Warehouse system. ETL full-form is Extract, Transform and Load.

It's tempting to think a creating a Data warehouse is simply extracting data from multiple sources and loading into database of a Data warehouse. This is far from the truth and requires a complex ETL process. The ETL process requires active inputs from various stakeholders including developers, analysts, testers, top executives and is technically challenging.

### Why do you need ETL?
There are many reasons for adopting ETL in the organization:

* It helps companies to analyze their business data for taking critical business decisions.
* Transactional databases cannot answer complex business questions that can be answered by ETL.
* A Data Warehouse provides a common data repository
* ETL provides a method of moving the data from various sources into a data warehouse.
* As data sources change, the Data Warehouse will automatically update.
* Well-designed and documented ETL system is almost essential to the success of a Data Warehouse project.
* Allow verification of data transformation, aggregation and calculations rules.
* ETL process allows sample data comparison between the source and the target system.
* ETL process can perform complex transformations and requires the extra area to store the data.
* ETL helps to Migrate data into a Data Warehouse. Convert to the various formats and types to adhere to one consistent system.
* ETL is a predefined process for accessing and manipulating source data into the target database.
* ETL offers deep historical context for the business.
* It helps to improve productivity because it codifies and reuses without a need for technical skills.

### Extract – 
Data extraction involves extracting data from homogeneous or heterogeneous sources;

#### Three Data Extraction methods:

* Full Extraction
* Partial Extraction- without update notification.
* Partial Extraction- with update notification

#### Some validations are done during Extraction:

* Reconcile records with the source data
* Make sure that no spam/unwanted data loaded
* Data type check
* Remove all types of duplicate/fragmented data
* Check whether all the keys are in place or not

### Transform – 
Data transformation processes data by data cleansing and transforming them into a proper storage format/structure

#### Validations are done during this stage

* Filtering – Select only certain columns to load
* Using rules and lookup tables for Data standardization
* Character Set Conversion and encoding handling
* Conversion of Units of Measurements like Date Time Conversion, currency conversions, numerical conversions, etc.
* Data threshold validation check. For example, age cannot be more than two digits.
* Data flow validation from the staging area to the intermediate tables.
* Required fields should not be left blank.
* Cleaning ( for example, mapping NULL to 0 or Gender Male to "M" and Female to "F" etc.)
* Split a column into multiples and merging multiple columns into a single column.
* Transposing rows and columns,
* Use lookups to merge data
* Using any complex data validation (e.g., if the first two columns in a row are empty then it automatically reject the row from processing)

### Load – 
Data loading describes the insertion of data into the final target database

#### Types of Loading:

* Initial Load — populating all the Data Warehouse tables
* Incremental Load — applying ongoing changes as when needed periodically.
* Full Refresh —erasing the contents of one or more tables and reloading with fresh data.

#### Load verification
* Ensure that the key field data is neither missing nor null.
* Test modeling views based on the target tables.
* Check that combined values and calculated measures.
* Data checks in dimension table as well as history table.
* Check the BI reports on the loaded fact and dimension table.

#### Key Points of ETL:
* ETL is an abbreviation of Extract, Transform and Load.
* ETL provides a method of moving the data from various sources into a data warehouse.
* In the first step extraction, data is extracted from the source system into the staging area.
* In the transformation step, the data extracted from source is cleansed and transformed .
* Loading data into the target datawarehouse is the last step of the ETL process.

# 3. Data Manipulation in R

#### Data Wrangling:
Data Wrangling is the process of converting and mapping data from its raw form to another format with the purpose of making it more valuable and appropriate for advance tasks such as Data Analytics and Machine Learning.

Data wrangling, like most data analytics processes, is an iterative one – the practitioner will need to carry out these steps repeatedly in order to produce the results he desires. There are six broad steps to data wrangling, which are:

##### 1. Discovering
In this step, the data is to be understood more deeply. Before implementing methods to clean it, you will definitely need to have a better idea about what the data is about. Wrangling needs to be done in specific manners, based on some criteria which could demarcate and divide the data accordingly – these are identified in this step.

##### 2. Structuring
Raw data is given to you in a haphazard manner, in most cases – there will not be any structure to it. This needs to be rectified, and the data needs to be restructured in a manner that better suits the analytical method used. Based on the criteria identified in the first step, the data will need to be separated for ease of use. One column may become two, or rows may be split – whatever needs to be done for better analysis.

##### 3. Cleaning
The process of detecting and correcting corrupt or inaccurate records from database or dataset is said to be data cleaning.

All datasets are sure to have some outliers, which can skew the results of the analysis. These will have to be cleaned, for the best results. In this step, the data is cleaned thoroughly for high-quality analysis. Null values will have to be changed, and the formatting will be standardized in order to make the data of higher quality.

Inconsistent and noisy data cannot be used to gain meaningful insights in an organisation. The noisy data needs to be cleaned before it is used for analytical approaches.

##### 4. Enriching
After cleaning, it will have to be enriched – this is done in the fourth step. This means that you will have to take stock of what is in the data and strategise whether you will have to augment it using some additional data in order to make it better. You should also brainstorm about whether you can derive any new data from the existing clean data set that you have.

##### 5. Validating
Validation rules refer to some repetitive programming steps which are used to verify the consistency, quality and the security of the data you have. For example, you will have to ascertain whether the fields in the data set are accurate via a check across the data, or see whether the attributes are normally distributed.

##### 6. Publishing
The prepared wrangled data is published so that it can be used further down the line – that is its purpose after all. If needed, you will also have to document the steps which were taken or logic used to wrangle the said data.


### Data Manipulation:
The process of changing data to make it more orgazined and easy to read is known as Data Manipulation.


### Descriptive Statistics:
Descriptive Statistics uses the data to provide descriptions of the population, either through numerical calculation or graph or tables.


