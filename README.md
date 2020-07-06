# berkeley-etl
Module 8 from Berkeley Data Analytics Program

# Challenge
  For our challenge, I created a function that reads in 3 files, cleans the data, merges the dataframes, and reads into a database. Below are important assumptions that must be followed in order for the function to execute successfully:
1. The `wiki_file` must be a filepath to a JSON file
2. The `kaggle_file` and `ratings_file` must be csv files
3. You must have a `config.py` file in the same directory that holds the password to your database in a variable called `db_password`
4. You must have a database named `movie_data` on your Postgres server
5. Existing data in table will be truncated with each run
