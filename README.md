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
* Here, I prioritized data cleaning and quality by addressing issues like missing values, nulls, duplicates, outliers, changing data physical type and 
* Ensuring standardization with Python. Hence, This meticulous preparation ensures that the data aligns seamlessly with analysis goals.

# Step 03: Data Transformation ![image](https://github.com/RoshniRanaDS/Data_Engineering_Cleaning_Normalization_With_ERD/assets/161755928/cee5f36f-6618-4774-a7dd-993456b3f4a3)

* Step three involves data transformation, where I have shaped the data to fit the needs of analysis.   
* This includes normalization to ensure consistency and clarity in data representation, setting the stage for effective modeling.

# Step 04: Data modeling ![image](https://github.com/RoshniRanaDS/Data_Engineering_Cleaning_Normalization_With_ERD/assets/161755928/f6e65725-0164-4626-864e-b02cf451fc8f)

crafting entity-relationship diagrams (ERDs) and establishing connections between datasets by Postgre-SQL and assigning primary and foreign keys within each tables. 

  ![image](https://github.com/RoshniRanaDS/Data_Engineering_Cleaning_Normalization_With_ERD/assets/161755928/c3291103-1c4b-49ab-91d2-1e8643f07c17)



# Step 05: Exploratory data analysis ![image](https://github.com/RoshniRanaDS/Data_Engineering_Cleaning_Normalization_With_ERD/assets/161755928/c3f9eba7-c9eb-444a-a09b-339a4fc27456)

Delved into exploratory data analysis using Python libraries, and explored patterns with cleaned data sets.   
This phase unveils insights and prepares the data for meaningful visualizations.

# Step 06: Data visualization ![image](https://github.com/RoshniRanaDS/Data_Engineering_Cleaning_Normalization_With_ERD/assets/161755928/606cc427-afc7-4cf3-a2e8-1c5ffb4d58ee)

involves data visualization for further analysis with Interactive Geoographical Heat Map  
where I transformed complex findings into clear, insightful visual representations.   
This step ensures that the results are not only understood but also actionable for stakeholders. 
  
Ultimately, Data journey concludes with interpreting the results, weaving them into meaningful conclusions 
Through this approach, I ensure that my analysis not only addresses initial problems but also adds unexpected value to business requirements through my technical expertise.


Data Flow: Data sourced from WHO -> Processed in Jupyter Notebook -> Stored and retrieved from a SQL database.
* Schema Diagram: Detailed in the Engineering_ERD folder.


Tools Used:
Storage: SQL database for organized data storage and retrieval.
Processing: Jupyter Notebook (main_file.ipynb) for data manipulation and analysis.
Visualization: Matplotlib, Seaborn for plotting graphs and charts.

Additional Tools:
* NumPy: For numerical operations.
* Pathlib: For file path manipulations.
* CSV and OS Libraries: For handling data files.

Analytical Use Cases
* Access Disparities: Analyzing regional and socioeconomic variations in access to family planning.
Demonstration
* Jupyter Notebook: Demonstrates data retrieval and visualization.
* Visuals: Include bar charts, line graphs, and heatmaps to depict key findings. Visuals are included in the project report and presentation.

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
* Output: Contains all exported datasets and analysis results.
* Engineering_ERD: ERD for schema and SQL database export.
* Project_Analysis: Findings and summary documents.

How to Run:
Environment Setup: Ensure you have Python and Jupyter Notebook installed.
Dependencies: Install required libraries via pip: numpy, pandas, matplotlib, seaborn.
Run Notebook: Open main.ipynb in Jupyter Notebook and run the cells sequentially.






![image](https://github.com/RoshniRanaDS/Data_Engineering_Cleaning_Normalization_With_ERD/assets/161755928/8ab7839c-cff5-4d0d-af95-bb1bb994a4cd)
