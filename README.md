# Analysis-of-Youtube-trending-data:

In this notebook, we will provide a detailed report on our analysis of YouTube Trending Video data, including codes we have used in cleaning, preparing, and visualizing the data.

# Introduction:
In the modern age, most people have access to a variety of electronic devices. This means more and more people are consuming content using online video services, among which YouTube is the most popular. According to Google, the owner of YouTube, over 400 hours of video are uploaded every minute, 100s of millions of hours are watched each day, and billions of users visit YouTube each month. Thus, YouTube provides something of interest for creators, viewers, and advertisers. YouTube videos are monetized through ad revenues, so the more views a video receives, the more ad revenue that can be generated. From the advertiser's point of view, they want to market their product to as wide an audience as possible, so they will want their ads on the most popular videos.

In our project, we obtained the individual country datasets on videos that were trending on YouTube over the same time period. The data includes several months of data from 2017 to 2018 on daily trending YouTube videos, with up to 200 listed trending videos per day. There is a separate dataset for each country. Data includes the following variables/columns: category, video title, channel title, publish time, tags, views, likes and dislikes, description, and comment count. The category variable varies between regions, and we will find categories for a specific video in its associated JSON. One such file is included for each region in the dataset. There is a column metadata for this dataset which provides more specific information about its contents.

Given YouTube’s large library of videos, it is important to filter videos to different users. YouTube uses a combination of different factors including measuring users interactions (number of views, shares, comments and likes) to determine if a video is trending. These trending videos are then made visible to users so they can see which videos are popular at a given moment. We looked at what factors make a video become trending and whether these factors are different across various countries and categories. We also explored why certain videos may generate more views, likes and comments.Given the current shift away from traditional TV to online platforms like YouTube, there is increased interest in the content of the videos on the online platforms, especially about which kinds of videos generate more engagement in the form of views, likes and comments, which in turn translate into more ads and revenues. Moreover, currently, COVID-19 has caused large numbers of people to stay at home, which will undoubtedly cause a spike in the number of daily YouTube visitors and create opportunities for video creators and advertisers.

The main research questions we tried to answer in our project include:

What similarities and differences are there between trending videos in different regions (between the United States, Great Britain and India)?

Which categories of trending videos have high likeability?

What insights can we gain from text mining and natural language processing analyses on video titles, tags and descriptions?

Can we make any inferences about viewer preferences based on the analysis of the video data?

What are the implications for content creation, monetization and advertising?

# Conclusions:

Our findings reveal quite a bit of information about trending videos on YouTube in the United States, Great Britain and India, and they can serve as useful insights for video content creators, advertisers and viewers in these countries. Below is a summary of our findings:

Although there were some slight differences across countries, videos in the "Music" and "Pets & Animals" categories had greater likeability ratios. Not surprisingly, “News and Politics” had the lowest likeability ratio across all three countries.

Among the trending videos in the dataset, a large majority of them fell into the "Entertainment" (33,763 videos) and "Music" (23,459 videos) categories.

The most frequently used words in titles of trending videos across all three countries included "official", "video", "trailer", "episode" and "full". In terms of word combinations, "official video", "official trailer", "music video", and "official music" appeared the most, indicating most of the trending videos are related to music, film, and entertainment programs discussing music and film. The film, music and TV industry are major players on the YouTube platform. We also found that the sentiments of about 88.2% of trending video titles can be categorized as neutral or positive.

Across all three countries, the most popular tags used in the trending videos included "news", "video", "new", "comedy" and "movie". Interestingly, for the United States, "makeup" was the second most popular tag. Sentiment analysis on tags of the trending videos in our datset revealed that the sentiment of 84.2% of tags used in trending videos were positive or neutral.

In each country, the most popular words included in the descriptions included "http", "https", "twitter", "youtube", "facebook", "instagram" and "channel", which means that most video creators include links to their websites, to the video or to their other social media accounts with the goal of increasing the reach of the video across all social media platforms, gaining more subscribers, and thus, maximizing monetization. Across all three countries, sentiment analysis revealed that 91.4% of the descriptions provided in trending videos were positive or neutral.

Over the period of analysis, videos that are trending in Great Britain tend to be watched by more people around the world (with a maximum of 2 billion people per day), whereas the videos trending in the US tend to be watched by relatively less people (with a maximum of over 1 billion people), and the videos trending in India tend to have lower view counts around the world.

In conclusion, our project findings offer something of value for various interested parties, including creators, advertisers and viewers on the YouTube platform. Given that YouTube now has 2 billion monthly users who watch 250 million hours on TV screens daily (Variety, 2019) and the continuing trend of viewers moving away from tradition TV to online platforms like YouTube, it is an important time for advertisers and agencies to think about diversifying their advertising spending away from traditional TV to online platforms like YouTube.
