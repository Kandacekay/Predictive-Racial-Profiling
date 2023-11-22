# Predictive-Racial-Profiling

## Link to Dashboard: 
   - https://public.tableau.com/views/AustinProfiling/ArrestAnalyticsDashBoard?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link



## Racial Profiling Analysis
##### Overview
This repository contains the code and findings for a data analysis project on racial profiling using data from the City of Austin's Open Data Portal (https://data.austintexas.gov/browse?q=racial%20profiling&sortBy=relevance). The analysis focuses on arrest data, exploring patterns based on race and location. The project utilizes various technologies, including Python, scikit-learn, Tableau, Jupyter Lab, PySpark, MongoDB, SparkSQL, AWS S3 buckets, and JSON.

##### Contributors
- Kandace Johnson
- Dren LaPhane

##### Project Structure
- data_processing: Jupyter notebooks and Python scripts for data cleaning and preprocessing.
- machine_learning: Jupyter notebook containing the machine learning model implementation.
- data_visualization: Tableau workbook for visualizing the findings.
- database_integration: Code related to storing and retrieving data from MongoDB and AWS S3.
- requirements.txt: List of Python packages and their versions used in this project.

##### Data
The primary dataset used for this analysis is sourced from the City of Austin's Open Data Portal. The dataset includes information on arrests, with a focus on the race of individuals involved.

##### Analysis Findings
The analysis explores the relationship between race, location, and arrests. The main findings are summarized below:


+--------------------+------------+
|                Race|Arrest Count|
+--------------------+------------+
|               WHITE|       13584|
|               BLACK|        9905|
|AMERICAN INDIAN/A...|          20|
|  HISPANIC OR LATINO|       17212|
|             UNKNOWN|         112|
|MIDDLE EASTERN       |         138|
|HAWAIIAN/PACIFIC ...|          22|
|               ASIAN|         427|
|          not_listed|           3|
+--------------------+------------+

##### Machine Learning Model
The machine learning model focuses on predicting arrests based on location and the individual being Hispanic. Further details about the model and its implementation can be found in the machine_learning folder.

##### Data Visualization
The findings are visualized using Tableau. The Tableau workbook in the data_visualization folder provides interactive visualizations for a better understanding of the analysis results.

##### Database Integration
The project involves integration with MongoDB and AWS S3 for storing and retrieving data. The database_integration folder contains code related to these integrations.

##### Setup Instructions
1. Clone the repository: git clone https://github.com/your_username/racial-profiling-analysis.git

2. Install dependencies: pip install -r requirements.txt

3. Follow the instructions in each folder for specific setup steps.

Feel free to reach out to the contributors for any questions or clarifications.

Happy analyzing!
