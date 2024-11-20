Netflix Dataset Analysis
Overview
This project performs an analysis of the Netflix dataset, focusing on understanding the distribution of titles across different rating categories and conducting sentiment analysis on the movie and TV show descriptions. Additionally, we generate various data visualizations to highlight key insights from the data.

Table of Contents
1.Data Cleaning
2.Sentiment Analysis
3.Rating Category Distribution
4.Visualizations
5.Insights and Observations

Data Cleaning
Before conducting the analysis, the dataset underwent a data cleaning process to address the following issues:

Inconsistent Rating Entries: Some entries in the "rating" column contained values such as movie durations (e.g., "66 min"). 
These were removed to ensure the "rating" column only contains valid rating categories like "PG", "R", "TV-MA", etc.
Missing Values: Rows with missing descriptions were excluded from the sentiment analysis step.

Sentiment Analysis
Description:
We performed sentiment analysis on the description of each movie or TV show using the TextBlob library. The analysis includes two key metrics for each description:

Polarity: A score from -1 (negative) to +1 (positive) indicating the sentiment of the description.
Subjectivity: A score from 0 (objective) to 1 (subjective) indicating how subjective the description is.
3
Results:
Positive, neutral, and negative sentiment distributions are visualized to understand the general tone of Netflix titles.
Rating Category Distribution
We grouped the titles based on their rating categories and counted the number of titles for each category. The categories include:

G, PG, PG-13, R, TV-MA, etc.
Visualizations
We use various visualizations to summarize and better understand the dataset:

Pie Chart: Displays the distribution of Netflix titles across different rating categories.
Bar Graphs: Shows the sentiment distribution across the movie and TV show descriptions.
These visualizations help to identify the most common ratings and give insights into the sentiment of Netflix content.

Insights and Observations
Dominance of TV-MA: The TV-MA rating category has the highest number of titles (3,207), indicating a significant focus on adult content.
Teen and Family Content: There is a considerable amount of content for teenagers and families, with ratings like TV-14 (2,160), TV-PG (863), and TV-Y7 (334).
Rare Categories: Categories such as NC-17 (3) and UR (3) have very few titles, reflecting niche content.
Sentiment Distribution: Sentiment analysis shows the general tone of Netflix content, with most descriptions leaning toward a positive or neutral sentiment.


Requirements:
1.Python 3.x
2.pandas
3.numpy
4.matplotlib
5.textblob

