# Module 8 -Movies-ETL
Terra Lasho

## Project Overview
In this module, I used the Extract, Transform, Load (ETL) process to create data pipelines which are not only a key step in mass data analysis, but also critical for accessibility to quality data.  This is accomplished by moving and merging data to a destination, while interrogating and transforming it in pieces. For this Module, I used Python script to perform the ETL on extracted Wikipedia and Kaggle data. 
## Deliverable 1: Write an ETL Function to Read Three Data Files
For this Deliverable, I wrote an ETL 'ETL_function_test.ipynb' to read in all three data files: ‘wiki’, ‘Kaggle’, and ‘ratings’.
### wiki_movies_df  
![](https://github.com/Beetleee/School_District_Analysis/blob/main/resources/percentages_on_new.png)

### Kaggle_metadata

![](https://github.com/Beetleee/School_District_Analysis/blob/main/resources/percentages_on_new.png)

### ratings

![](https://github.com/Beetleee/School_District_Analysis/blob/main/resources/percentages_on_new.png)

## Deliverable 2: Extract and Transform the Wikipedia Data
For this Deliverable, I extracted and transformed the Wikipedia-derived data 'ETL_clean_wiki_movies.ipynb' so it could be prepped to merge with the Kaggle metadata.  For this, I used expression strings (to mould the data type for easier merging) and dropped duplicates.
### wiki_movies_df  
![](https://github.com/Beetleee/School_District_Analysis/blob/main/resources/percentages_on_new.png)

### wiki_movies_df (columns)

![](https://github.com/Beetleee/School_District_Analysis/blob/main/resources/percentages_on_new.png)

## Deliverable 3: Extract and Transform the Kaggle data
For this Deliverable, I extracted and transformed the Kaggle data and ratings 'ETL_clean_kaggle_data.ipynb', and merged them similar to Deliverable #2.
### movies_with_ratings_df  
![](https://github.com/Beetleee/School_District_Analysis/blob/main/resources/percentages_on_new.png)

### movies_df

![](https://github.com/Beetleee/School_District_Analysis/blob/main/resources/percentages_on_new.png)

## Deliverable 4: Create the Movie Database

For this Deliverable, I uploaded the transformed movies_df and rating CSV data to a SQL database 'ETL_create_database.ipynb'.

### movies_query.png (query run from SQL database)
![](https://github.com/Beetleee/School_District_Analysis/blob/main/resources/percentages_on_new.png)

### ratings_query.png (query run from SQL database)
![](https://github.com/Beetleee/School_District_Analysis/blob/main/resources/percentages_on_new.png)

### elapsed time to add the data to the database display…
![](https://github.com/Beetleee/School_District_Analysis/blob/main/resources/percentages_on_new.png)

In conclusion, I have successfully cleaned and aligned the files into SQL so that the Client will be able to access straightforward and accurate information.
