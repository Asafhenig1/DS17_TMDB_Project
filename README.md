# DS17_TMDB_Project
project to analyze TMDB tv dataset


** ML_TMDB_PROJECT_EDA_1.pynb
**
The ML_TMDB_PROJECT_EDA_1.pynb file is a notebook that performs data preperation on the pickle file 'tmdb_flat_file.pkl'
These are the operations conducted as part of the data preperations:
1) BLOCK 1: Uploading pickle file
2) BLOCK 2: Presenting Dataframe shape
3) BLOCK 3: Presenting Dataframe Info
4) BLOCK 4: Data Protocol - Generating files that provide basic values for dataframe columns.
5) BLOCK 5: Descriptive Statistics - AutoViz auto reports.
6) BLOCK 6: Descriptive Statistics - Database describe()
7) BLOCK 7: Target Value Analysis - Provide a diagram to correlate the Target Column 'Popularity' with other columns + table that presents the relevant data
8) BLOCK 8: Categorial Data Diagrams
9) BLOCK 9: Modifying 'Network' feature - leaving top 10 networks and all others are in the 'Other' category
10) BLOCK 10: Modifying 'Original_language' feature - leaving top 10 languages and all others are in the 'Other' category
11) BLOCK 11: Modifying 'Origin_Country' feature - replace this column with 'Origin Continent' column where each country in the original column is associated with its geographical continent
12) BLOCK 12: Remove 'last_air_date' and 'in_production' columns due to large precentage of mistaks and per Orit instruction
13) BLOCK 13: Histograms for continues numbers
14) BLOCK 14: SKEWNESS
15) BLOCK 15: Correlation and heatmap
16) BLOCK 16: Write the tmdb_EDA_data_protocol_file.pkl file based on the last status of 'df' dataframe

** ML_TMDB_PROJECT_EDA_2.pynb
**

The ML_TMDB_PROJECT_EDA_2.pynb file is a notebook that performs data cleansing on the previously 
1) BLOCK 1: Load the last created pickle file (tmdb_EDA_data_protocol_file.pkl0
2) BLOCK 2: showing df.shape and df.info()
3) BLOCK 3: transforming 'Number_of_seasons' feature from Numerical continious to Numerical Categorical
4) BLOCK 4: Virtualize all 'numerical continious' parameters via Boxplot
5) BLOCK 5: Create a modified version of the data in which numerical values are transformed to their log (in base 10) version in order to 
create a more normalized-like data to improve boxplot virtualization
6) BLOCK 6: Present new boxplot based on log files
7) BLOCK 7: Finding outliers based on IQR
8) BLOCK 8: Create an outliers table (feature	| outliers_cnt | distribution_changed | correlation_changed)
9) BLOCK 9: 
