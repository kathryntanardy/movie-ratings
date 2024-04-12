# Movie Sentiment Analysis Rating 🎥🎬
#### CMPT353 Spring 2024 Project (kta98 and vaa13)

### 1. How to run the code
By order of execution:
Filename | Command | Description | Expected output |
--- | --- | --- |  --- | 
01-reddit_scrape.py | python3 01-reddit_scrape.py | Run the command in the terminal. The link to be scraped is already listed inside the program, automatically loop through all of the link to produce the desired output. | A CSV file containing the raw data scraped by PRAW, which contains time and the comments | 
02-data_cleaning.py | python3 02-data_cleaning.py | The raw data scraped is already located in the data_scraped file, filepath and output name is already listed in the program and just need to be run. If you want to do it manually, remove the loop inside the program and specify the filepaths yourself in the command arguments using the CSV files from the previous step. | A CSV file containing the cleaned data | 
03-sentiment_analysis.py | python3 03-sentiment_analysis.py | The cleaned data from the previous step is all located in the 'cleaned_data' file, filepath and output name is already listed in the program and just need to be run. If you want to do it manually, remove the loop inside the program and specify the filepaths yourself in the command arguments using the CSV files that is created in the previous step. | A CSV file containing the sentiment_data that contains negative, neutral, positive, and rating scores from the analysis. |
04-imdb_to_csv.py | python3 04-imdb_to_csv.py | Run the command in the terminal. The filepath to the imdb_data that is collected manually by the developers are already inside the program. User just need to run the python command in the terminal. Output name is already inside the program as well and will be produced by the for-loop created by the programmers.  | A CSV file containing all fo the ratings count of each movies separately. | 
05-imdb_to_csv.py | python3 05-imdb_to_csv.py| Run the command in the terminal. The filepath of both the Reddit and IMDb data is already specified in the programme and will be run by the for loop. If user wants to do it manually, remove the for loop and specify the path created from step 3 and 4, and also assign the path to the variable correctly inside the program.| A print output that shows whether the test succeeded (where a conclusion can be made) or if it fails the statistical test. Each movie also produces a graph with two subplots (IMDb and Reddit Sentiment Analysis score ratings) | 
06-analyze_time_ratings.py | python3 06-analyze_time_ratings.py| To be filled. | To be filled. | 


