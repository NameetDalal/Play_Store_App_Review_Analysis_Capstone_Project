# Play_Store_App_Review_Analysis_Capstone_Project
The Play Store apps data has enormous potential to drive app-making businesses to success. Actionable insights can be drawn for developers to work on and capture the Android market.
Each app (row) has values for catergory, rating, size, and more. Another dataset contains customer reviews of the android apps.
Explore and analyze the data to discover key factors responsible for app engagement and success.
Introduction to data

Mobile apps are everywhere. They are easy to create and can be money making. Because of these two factors, more and more apps are being developed. In this notebook, we will do a comprehensive analysis of the Android app market by comparing over ten thousand apps in Google Play across different categories. We'll look for insights in the data to devise strategies to drive growth and retention.
Let's take a look at the data, which consists of two files:

1.Play_store_data.csv
This file contains all the details of the apps on Google Play. There are 13 features that describe a given app.
App: Name of the app
Category: Category of the app. Some examples are: ART_AND_DESIGN, FINANCE, COMICS, BEAUTY etc.
Rating: The current average rating (out of 5) of the app on Google Play
Reviews: Number of user reviews given on the app
Size: Size of the app in MB (megabytes)
Installs: Number of times the app was downloaded from Google Play
Type: Whether the app is paid or free
Price: Price of the app in US$
Content Rating: A content rating (also known as maturity rating) rates the suitability of TV broadcasts, movies, comic books, or video games to its audience.To show which age group is suitable to view media and entertainment.
Genres: A category of artistic, musical, or literary composition characterized by a particular style, form, or content
Last Updated: Date on which the app was last updated on Google Play
Current Ver: Current Version means a version of the software that is currently being supported by its publisher.
Android Ver: Android versions (codenames) are used to describe the various updates for the open source Android mobile operating system.

2.user_reviews.csv
This file contains a random sample of 100 most helpful first user reviews for each app. The distribution of positive and negative reviews in each category has been pre-processed and passed through a sentiment analyzer.
App: Name of the app on which the user review was provided. Matches the App column of the play_store_data.csv file
Translated Review: The pre-processed user review text.
Sentiment: Sentiment category of the user review - Positive, Negative or Neutral.
Sentiment Polarity: Sentiment score of the user review. It lies between [-1,1]. A higher score denotes a more positive sentiment.
