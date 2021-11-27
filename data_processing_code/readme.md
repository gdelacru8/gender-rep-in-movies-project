# Data Processing

The **project_data_processing.ipynb** notebook documents the mapping of movie titles in the Cornell dialogue dataset to imdb ids from The Pudding dataset based on matching titles. Some titles had no match because of different formatting of titles or because they were not present in The Pudding data. The imdb ids for these titles are manually searched for. Then each title is matched with the writer names using the IMDB datasets. The resulting data is exported to **dialogue_writers.csv**.

IMDB does not provide gender information with names, so the gender information for each writer had to be manually added based on the names. Gender information for each writer was determined by looking at each person's bio on IMDB. **dialogue_writers_with_gender.csv** contains the final writers data with gender information. 

The **writers_gender_counting.ipynb** notebook simply adds numerical data to tally the number of female and male writers for each movie title. The results are exported to **dialogue_writers_gender_with_counts.csv**. 
