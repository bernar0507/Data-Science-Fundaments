# Clustering Analysis of Thai Fashion Retailers on Facebook

## Overview

This project provides insights into the engagement metrics of 10 Thai fashion and cosmetics retail sellers on Facebook. Through clustering, sellers are grouped based on their post engagement patterns. The K-Means algorithm was chosen for its efficacy in segmenting the data.

## Steps Covered:

1. **Data Preparation:** The dataset was imported, and preliminary cleaning was performed.
2. **Exploratory Analysis:** Assessed data distributions such as post type, hour, and day of the month.
3. **Feature Engineering:** Correlated features were identified and removed to enhance model performance.
4. **Modeling:** Multiple clustering algorithms were tested, including K-Means, Agglomerative Clustering, and others.
5. **Evaluation:** The K-Means algorithm was chosen for deeper analysis. Cluster distributions were evaluated, especially post-undersampling, and profiles were formed based on engagement attributes.
6. **Conclusion:** Insights were derived from the analysis, leading to actionable recommendations.

## Major Conclusions:

- **Popularity Distinction:** Sellers were largely grouped into 'Less Popular' (Cluster 0) and 'Super Popular' (Cluster 1) categories.
- **Post Engagement:** Cluster 1 sellers, irrespective of the nature of the post, always have more likes than Cluster 0.
- **Posting Time Insights:** The window between 5:00 - 10:00 is ideal for maximum engagement. Conversely, the 15:00 - 20:00 window sees diminished interaction.
- **Monthly Engagement Trends:** No single month saw a marked spike in likes. However, Cluster 1 sellers maintained a consistent lead over Cluster 0.
- **Post Interactions:** Specific post interactions, like wows and hahas, don't necessarily correlate with overall post likes.

**Recommendations:** To optimize engagement, sellers are advised to post during early morning hours and take cues from the strategies employed by the more popular Cluster 1 sellers.

## Targeted Marketing Strategies for Each Cluster

| Strategy No. | Cluster 0 (Less Popular Sellers)                                                  | Cluster 1 (Super Popular Sellers)                                           |
|--------------|----------------------------------------------------------------------------------|------------------------------------------------------------------------------|
| 1            | **Engage More:** Initiate **User-Generated Content (UGC)** campaigns. Encourage followers to share their experiences. | **Loyalty Programs:** Introduce programs to reward frequent shoppers or active followers.           |
| 2            | **Collaborate with Influencers:** Partner with micro-influencers who resonate with your brand. | **Exclusive Launches:** Introduce new or limited-edition items with 'first access' for followers. |
| 3            | **Post Optimization:** Post during peak hours (5:00 - 10:00) for maximum visibility. | **Behind the Scenes:** Showcase the making of products or fun moments to humanize the brand.       |
| 4            | **Interactive Content:** Use polls, quizzes, or Q&A sessions for engagement and insights. | **Engage Consistently:** Engage with followers through comments, likes, or reposts.               |
| 5            | **Enhance Post Quality:** Use quality images, engaging captions, and trending hashtags. Consider videos for higher engagement. | **Collaborate with Brands:** Partner with complementary brands for wider exposure.                |
| 6            | **Promotions & Giveaways:** Organize contests and giveaways to increase reach rapidly. | **Advanced Analytics:** Use tools to understand what content type and posting times are most engaging. |
| 7            | **Feedback Loop:** Seek active feedback to gain insights and make audiences feel valued. | **Host Live Events:** Use Facebook Live for product launches or Q&A to boost real-time engagement. |
7. **Host Live Events:** 
   - Use Facebook Live for product launches, Q&A sessions, or simple interactive sessions. It boosts real-time engagement.


