# Project2
# Group 3 Project Report – Emily Cruz, Chad Milburn, Ocean Showers, and Brian Smith
## Extract
  We set out to locate hotel review information in Las Vegas and attempt to answer questions about when and why people came to Las Vegas, and how they rated their stay. Our search for data began by using Kaggle and Google Dataset Search. Our datasets are Datafiniti Hotel Reviews, originating from Kaggle. All data are in the form of CSV files.
## Transform:
  After downloading appropriate files, we began to clean our data by selecting the columns that were relevant to our questions and dropping those that were not. We then filtered through our data to find only the reviews of hotels that are in Las Vegas. After all data was relevant to Las Vegas only, we formatted our date columns so that dates were displayed as month names. Once all CSVs were formatted correctly, we merged them together. 
## Load:
  Once the data was merged into one CSV file, we used pandas to read the CSV, and converted it to a SQL database. SQL was chosen to convert so that the user can perform queries on the data regarding month traveled, review score, where the traveler visited from, and other variables that would shed light on reasons why people travel to Las Vegas. We performed some preliminary queries so the users could see a sample of insights, including; average review rating by hotel, average rating by travel month, average review rating of each hotel ordered by month, worst review rating by hotel, and one star reviews and their review text. 
  One drawback to our transformation of the data was once we transformed our numeric dates to the month names, when we attempted to order by month, the results were ordered alphabetically instead of in calendar order. If the user wanted queries to be in calendar order, we would need to reformat our dates so that year, month, and date were separate, numeric columns that the user could then query.
 
Sources
https://www.kaggle.com/datafiniti/hotel-reviews?select=Datafiniti_Hotel_Reviews.csv

