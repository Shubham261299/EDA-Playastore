# EDA on Play Store App Reviews
This project explores two datasets: one with basic information and another with user reviews for apps available on the Google Play Store. The goal is to identify the important characteristics that influence app engagement and success. An app is considered successful if it has a high average user rating, a good number of positive reviews, a good number of monthly average users, and high revenue per customer, among other factors.

## Datasets
The two datasets used in this project are:

Play_Store_Data.csv: This dataset contains basic information about the apps, including the app name, category, size, rating, number of reviews, number of installs, type (free or paid), and content rating.

User_reviews.csv: This dataset contains user reviews for the apps, including the app name, translated review, sentiment (positive, negative, or neutral), sentiment polarity, sentiment subjectivity, price, genre, last updated date, current version, Android version, rating group, and revenue.

## Agenda
The analysis of the datasets covers the following topics:

Correlation heatmap
Type and content rating analysis
Categorical analysis
App rating analysis
Top free and paid apps
Average price of paid apps in each category
Most popular apps
App size analysis
App reviews analysis
## Results
Some of the key findings from the analysis are:

There is a strong positive correlation between the number of reviews and installs.
The price is slightly negatively correlated with the rating, reviews, and installs.
The rating is slightly positively correlated with the installs and reviews.
The majority of the apps in the Play Store (~80%) are top-rated.
There are a total of 20 free apps with over one billion installs. The top categories in which these apps fall are Communication, Social, Video Players, and Travel and Local.
Minecraft, I am rich, and I am rich premium are the top paid apps based on revenue generated. Minecraft is the only app that has over 10M installs.
The paid apps in the Finance, Lifestyle, and Events category are, on average, significantly more expensive than the paid apps in other categories.
The most popular apps are those with more reviews, whether positive, negative, or neutral.
The apps in the Family category are the most competitive.
The most popular app sizes are between 10 MB and 20 MB.
The most common words used in user reviews are "good," "great," "app," "useful," and "love."
## Challenges
The main challenges faced during the project were:

Reading and understanding the datasets and the problem statement.
Devising a solution to the problem based on the business KPIs for app development.
Handling errors, duplicates, and NaN values in the datasets.
Designing multiple visualizations to summarize the information in the datasets and communicate the results and trends effectively.
## Conclusion
The analysis provides insights into the characteristics that influence the success of apps in the Google Play Store. Developers can use this information to make data-driven decisions when creating and marketing their apps. The findings can also be used to benchmark app performance and track progress over time.
