# Project2_Crowdfunding_ETL

Following steps were used for executing project 2

1. First Crowdfunding excel file was read into panda DataFrame
2. The DataFrame was further cleaned and re arranged to make category and subcategory data frames and exported to the resources folder as csv files
3. Next campaign dataFrame was created from the crowdfunding dataFrame and further cleaned and merged with earlier data frames and exported to resources folder
4. After that contacts dataframe was created and the text entries were cleaned and arranged as required and it was exported back to resources folder
5. Then the four csv files schema was created in PostgreSQL and data was imported into them from csv files
6. All the sql tables were printed using SELECT * to demonstrate successful data import and the screenshots are added to the repository
7. Also the ERD screenshot is added to the repository to demonstrate the relationships between multiple tables
