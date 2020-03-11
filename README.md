# ETL-Project
Group project

We pulled data from YouTube via their public APIs.  We then saved that data to csv files (2) and json (1).
  * ytapi.ipynb
  * Data saved to the "data" directory

We then loaded the csv files and the json file into dataframes and inserted that data into mongodb.
  * ETL_DB_Work.ipynb

Once loaded, we were able to pull the data back out of mongodb and put it all back into dataframes.
  * ETL_DB_Work.ipynb
