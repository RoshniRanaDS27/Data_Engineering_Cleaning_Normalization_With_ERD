![image](https://github.com/RoshniRanaDS/Data_Engineering_Cleaning_Normalization_With_ERD/assets/161755928/79583743-ac2a-4162-96fa-811b19f300f3)
![image](https://github.com/RoshniRanaDS/Data_Engineering_Cleaning_Normalization_With_ERD/assets/161755928/f7392ce8-e0a1-4bcc-9e41-bfd63148c791)
# Women’s maternal and reproductive health 
## Married or in-union women of reproductive age who have their need for family planning satisfied with modern methods (%)
![image](https://github.com/RoshniRanaDS/Data_Engineering_Cleaning_Normalization_With_ERD/assets/161755928/14b3fb70-99ea-45e4-800f-4a9dd19b4252)
#
# BackGround 
This Repo throws light on fascinating journey of Project in crafting data engineering pipelines for meticulous data analysis.

# Specific focus areas:
How does access to modern family planning methods vary across different regions and socioeconomic groups?

# Step 1: Data collection
- Sources: WHO datasets WHO Indicators.
- Source link:  https://www.who.int/data/gho/data/indicators/indicator-details/GHO/married-or-in-union-women-of-reproductive-age-who-have-their-need-for-family-planning-satisfied-with-modern-methods-(-)
  
* This Project journey involves data collection from The World Health Organization Relational Data Hub.   
* Had collected data set Related to Women’s maternal and reproductive health which is related to family planning satisfied with modern methods (%),   
* Here Ensuring the reliability and relevance of  data was paramount for me as it formed the foundation for the depth and accuracy of our analysis.

# Step 02: Data cleaning ![image](https://github.com/RoshniRanaDS/Data_Engineering_Cleaning_Normalization_With_ERD/assets/161755928/79ef9430-0100-4aac-ae03-91e58391ffcb)

* In this stage data cleaning was on focus. 
* Here, I prioritized data cleaning and quality by addressing issues like missing values, nulls, duplicates, outliers, changing data's physical type
* Ensuring standardization with Python. Hence, This meticulous preparation ensures that the data aligns seamlessly with analysis goals.
* [Modern Family Planning Data Cleaning and Transformation Notebook](Modern%20Family%20Planning_Data%20Cleaning%20and%20Data%20Transformation_Roshni.ipynb)
* [Cleaned Data CSV](Extracted%20Cleaned%20Data%20File/Cleaned_Data.csv)

# Step 03: Data Transformation ![image](https://github.com/RoshniRanaDS/Data_Engineering_Cleaning_Normalization_With_ERD/assets/161755928/cee5f36f-6618-4774-a7dd-993456b3f4a3)

* Step three involves data transformation, where I have shaped the data to fit the needs of analysis.   
* This includes normalization to ensure consistency and clarity in data representation, setting the stage for effective modeling.
* [Data Normalization Notebook](Data_Normalization.ipynb)
* [Normalized Tables](Normalized_Tables)

## 1NF 
![image](https://github.com/RoshniRanaDS/Data_Engineering_Cleaning_Normalization_With_ERD/assets/161755928/dfcc1e3e-77a7-4c13-8598-c7912394a235)
## 2NF 
![image](https://github.com/RoshniRanaDS/Data_Engineering_Cleaning_Normalization_With_ERD/assets/161755928/5a88f056-4973-4ab9-bc86-50989e156912)
#
![image](https://github.com/RoshniRanaDS/Data_Engineering_Cleaning_Normalization_With_ERD/assets/161755928/271e40f1-f0c7-4c33-9ac6-ac61dbd7dd56)
#
# 3NF
![image](https://github.com/RoshniRanaDS/Data_Engineering_Cleaning_Normalization_With_ERD/assets/161755928/2ddbab7e-0048-452e-9515-f006547a66ec)
#
- Normalizing Period Ranges
  
![image](https://github.com/RoshniRanaDS/Data_Engineering_Cleaning_Normalization_With_ERD/assets/161755928/31b3cc56-1b3b-4f87-aae3-2499d21b8dad)
#
Fact Table   

![image](https://github.com/RoshniRanaDS/Data_Engineering_Cleaning_Normalization_With_ERD/assets/161755928/81ca9070-04c5-4564-8e00-dc2cfb2f751c)


# Step 04: Data modeling ![image](https://github.com/RoshniRanaDS/Data_Engineering_Cleaning_Normalization_With_ERD/assets/161755928/f948ff00-beb3-4d00-85f3-a27326bb884b)

crafting entity-relationship diagrams (ERDs) and establishing connections between datasets by Postgre-SQL and assigning primary and foreign keys within each tables. 

  ![image](https://github.com/RoshniRanaDS/Data_Engineering_Cleaning_Normalization_With_ERD/assets/161755928/c3291103-1c4b-49ab-91d2-1e8643f07c17)

* [ERD Data Modeling SQL Script](ERD_Data_Modeling/ERD-Data%20modeling_Modern_Family_Planning(SQL)_Roshni.sql)
* [ERD Data Modeling PK_FK_PDF](ERD_Data_Modeling/ERD-Data%20modeling_Modern_Family_Planning(PDF-FK,PK)_Roshni.pdf)


# Step 05: Exploratory data analysis ![image](https://github.com/RoshniRanaDS/Data_Engineering_Cleaning_Normalization_With_ERD/assets/161755928/c3f9eba7-c9eb-444a-a09b-339a4fc27456)

Delved into exploratory data analysis using Python libraries, and explored patterns with cleaned data sets.   
This phase unveils insights and prepares the data for meaningful visualizations.
# Continent Level Analysis
![image](https://github.com/RoshniRanaDS/Data_Engineering_Cleaning_Normalization_With_ERD/assets/161755928/1398d8df-dcfe-44fb-9950-079e9e789aea)
# Country Level Analysis
![image](https://github.com/RoshniRanaDS/Data_Engineering_Cleaning_Normalization_With_ERD/assets/161755928/208bac75-c4a6-4e41-945c-628a02c19141)
# Top Three Countries within each Continent - Family Planning Data set
![image](https://github.com/RoshniRanaDS/Data_Engineering_Cleaning_Normalization_With_ERD/assets/161755928/716a11c2-c1dc-4978-87c5-ab9d9ab3a2f9)

# Step 06: Data visualization ![image](https://github.com/RoshniRanaDS/Data_Engineering_Cleaning_Normalization_With_ERD/assets/161755928/606cc427-afc7-4cf3-a2e8-1c5ffb4d58ee)

involves data visualization for further analysis with Interactive Geoographical Heat Map  
where I transformed complex findings into clear, insightful visual representations.   
This step ensures that the results are not only understood but also actionable for stakeholders. 
    
* [Data Visualization Notebook](Data_Visualization_Roshni.ipynb)
* [Interactive Map HTML Files](Extracted_Interactive_Map/index.html)
    
## Interactive Geographical Heat Map with tooltips Screenshot (HTML file is Saved)
# Geographical Analysis - Family Planning Data set (Continent Level)
![image](https://github.com/RoshniRanaDS/Data_Engineering_Cleaning_Normalization_With_ERD/assets/161755928/fecdb12f-c29a-411d-a0a1-d1dd327361b1)
# Top Three Countries within each Continent - Family Planning Data set
![image](https://github.com/RoshniRanaDS/Data_Engineering_Cleaning_Normalization_With_ERD/assets/161755928/66ee770c-1307-47ca-a4cf-d3172c1fdb37)
# Time-Period Analysis
![image](https://github.com/RoshniRanaDS/Data_Engineering_Cleaning_Normalization_With_ERD/assets/161755928/ae34b079-c308-4eee-970d-a7174113f0a3)
#
#
> [!IMPORTANT]
> Key information users need to know to achieve their goal.
#
> Ultimately, Data journey concludes with interpreting the results, weaving them into meaningful conclusions 
> Through this approach, I ensure that my analysis not only addresses initial problems but also adds unexpected value to business requirements through my technical expertise.

# Dependency 
- CSV
- OS
- matlotlib
- Pandas
- pyplot
- numpy
- seaborn
- geopandas
- folium
- time
- Selenium, webdriver
- Ipython.display, image 
#
- Ultimately, Data journey concludes with interpreting the results, weaving them into meaningful conclusions 
- Through this approach, I ensure that my analysis not only addresses initial problems but also adds unexpected value to business requirements through my technical expertise.
#
#
> [!NOTE]
> Useful information that users should know, even when skimming content.
#
Data Flow:  
* Data sourced from WHO -> Processed in Jupyter Notebook -> Stored and retrieved from a SQL database.
* Schema Diagram: Detailed in the Engineering_ERD folder.

Tools Used:  
  
* Storage: SQL database for organized data storage and retrieval.
* Processing: Jupyter Notebook (odern Family Planning Data Cleaning and Transformation.ipynb) for data manipulation and analysis.

Analytical Use Cases  
  
* Access Disparities: Analyzing regional and socioeconomic variations in access to family planning.
  
Demonstration
* Jupyter Notebook: Demonstrates data retrieval and visualization.
* Visuals: Include Geo Heat Maps and line graph 

Assumptions:
* When the period of study was done between 2 years (i.e. 2022-2023), it is assumed that the results of that particular study corresponds to 12 months and it is a reflection of the latest year (2023).__
* The datasets were broken down in intervals of 3 years each starting in 2003 to 2023 to allow consistent analysis of data over time.
* The study was done in married and in-union women of reproductive age, which is assumed to be between 15-49 years.
* Assumed the same collecting data method accross countries.

Limitations:
* There are more indicators that could have been analyzed to contribute to the overall hypothesis. We focused on 4 key indicators due to time constrainsts.
* Period data was not standardized accross datasets. Some assumptions needed to be made to standardize it and make them fully comparable.

Ethical Considerations:
* Ensuring the confidentiality and ethical use of data.
* Addressing biases inherent in data collection methods.

Future Work Scope:
* Extended Analysis: Incorporate more indicators for a comprehensive view.
* Data Integration: Enhance the database with additional sources and real-time data.
* Interactive Dashboards: Develop more interactive visualization tools for dynamic data exploration.
* Please, refer to the word file to get the summary of the findings

Folder Structure:
* Extracted Folders: Contains all exported datasets and analysis results.
* Engineering_ERD: ERD for schema and SQL database export.
* Project_Analysis: Findings and summary documents.

How to Run:
* Environment Setup: Ensure you have Python and Jupyter Notebook installed.
* Dependencies: Install required libraries numpy, pandas, matplotlib, seaborn.
* Run Notebook: Open .ipynb in Jupyter Notebook and run the cells sequentially.






![image](https://github.com/RoshniRanaDS/Data_Engineering_Cleaning_Normalization_With_ERD/assets/161755928/8ab7839c-cff5-4d0d-af95-bb1bb994a4cd)
