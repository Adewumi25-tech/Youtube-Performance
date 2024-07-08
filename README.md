# Youtube-Performance

## OVERVIEW
YouTube performance analysis involves examining various metrics and data points to understand the effectiveness and reach of YouTube content. This analysis is crucial for content creators, marketers, and businesses aiming to optimize their video strategies, enhance viewer engagement, and maximize return on investment.

This analysis focuses on 10 countries which published videos from 2006 to 2018
The dataset includes information such as video ID, title, channel, category, views, likes, dislikes, comments, country, trending date, published date, comments disabled, and rating disabled.

## PROBLEM STATEMENT
* Top performance
* Trending Analysis
* Engagement metrics
* Channel insights
* Accessibility analysis - videos with disabled comments and rating

## TOOLS
* Power BI on Fabrics
* Python (Data cleaning)
* DAX Function
* Quick measure
* Modelling

## DATA PREPARATION
The dataset was processed to handle missing values, clean outliers, and ensure consistency, transforming, and organizing the data to ensure accuracy and usability for analysis using Python. 

[Updated2.md](https://github.com/user-attachments/files/16120988/Updated2.md)

After the data cleaning, the data was saved to my laptop download.

I created a workspace on my Microsoft Fabric and Lakehouse for my data. The dataset was uploaded to my lakehouse, new dataflow gen2 was created. 

<img width="956" alt="image" src="https://github.com/Adewumi25-tech/Youtube-Performance/assets/72547309/6f394ffa-dcb7-4b49-bb54-7831731a0996">

Data transformation and DAX function were applied to create relevant features for analysis.


## DASHBOARD
[Youtube Analysis.pdf](https://github.com/user-attachments/files/16121479/Youtube.Analysis.pdf)

## INSIGHTS
The analysis highlights the UK, USA, and Canada as the leading countries in terms of viewership. Additionally, India and Germany show significant potential for growth. 

### Overall Metrics:
👉 Total YouTube Videos: 363K

👉 Total Views: 488 billion

👉 Total Likes: 14 billion

👉 Total Comments: 2 billion

👉 Average Views per Video: 1.34 million

👉 Average Likes per Video: 38.41K

### Category-wise Distribution:
👉 Top Categories by Number of Videos:

👉 Entertainment: 105K

👉 People & Blogs: 52K

👉 Music: 41K

👉 News & Politics: 36K

👉 Comedy: 26K

### Top Channels by Views:
👉 ChildishGambinoVEVO: 10.9 billion

👉 Marvel Entertainment: 10.1 billion

👉 NickyJamTV: 9.5 billion

👉 Ozuna: 8.6 billion

👉 ibighit: 7.6 billion

### Top Channels by Likes:
👉 ibighit: 734 million

👉 Marvel Entertainment: 302 million

👉 ChildishGambinoVEVO: 287 million

👉 TaylorSwiftVEVO: 210 million

👉 PewDiePie: 207 million

### Top Channels by Comments:
👉 ibighit: 117 million

👉 Marvel Entertainment: 36 million

👉 ChildishGambinoVEVO: 30 million

👉 jypentertainment: 28 million

👉 PewDiePie: 26 million

👉 Country-wise Distribution:

### Top Countries by Views:
👉 UK: 229 billion

👉 USA: 96.5 billion

👉 Canada: 46.8 billion

👉 India: 32.9 billion

👉 Germany: 24.6 billion

### Disabled Features:
👉 Comment Disabled Videos: 7907

👉 Rating Disabled Videos: 6771

👉 Average Views on Comment Disabled Videos: 1 million

👉 Average Views on Rating Disabled Videos: 779.61K

### Noteworthy Insights:
👉 High Engagement: Channels like ibighit and Marvel Entertainment show a high engagement rate with top positions in views, likes, and comments.

👉 Category Trends: Entertainment, People & Blogs, and Music dominate in terms of the number of videos.

👉 Country Insights: The UK and USA are leading in terms of the total number of views and engagement metrics.


## RECOMMENDATION
👉 Entertainment, People & Blogs, and Music are the leading categories with the highest number of videos and engagement. We should increase our content production in these areas to attract a larger audience.

👉 I encourage more interaction through likes, comments, and shares. Consider live streams, community posts, and Q&A sessions to build a stronger connection with our audience.

👉 Disabling comments and ratings should be avoided as these features drive higher engagement. Videos with these features enabled have been shown to receive higher average views.




