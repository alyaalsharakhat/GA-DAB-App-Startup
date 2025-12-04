# App Development Startup


## Overview
As app developers preparing to launch a new mobile application, our goal is to determine which platform (Apple’s App Store or Google Play) offers the strongest opportunity for success.
This project analyzes both markets using pricing, ratings, engagement, genre, and age-category data to identify which platform aligns best with our target audience and strategy.


## Scenario
A startup must choose whether to launch a new app on Apple or Google first.

The challenge is identifying which platform provides the best environment for growth based on:
- Platform performance
- Pricing strategy
- User age segmentation
- Genre distribution
- Engagement and popularity

Our analysis answers these questions using real app-store market data.

## Objectives
We aim to answer the following:
- Which platform should we target first?
- What is the best price strategy (Free vs Paid)?
- Which genres perform best per platform?
- Which age category provides the highest engagement?

## Dataset
The dataset includes apps from Apple’s App Store and Google Play with 7 variables:
- App (App name)
- Genre
- Price (in $)
- Rating
- Reviews
- Content Rating ( We catogrize them as Age category)
- Platform (Apple vs Google)


## Data Cleaning
Performed primarily in Excel:
- Removed $ symbols from the Price column
- Checked duplicates
- Corrected missing values ( missing ratings classified as “No Rating”)

## Analysis
The analysis was performed entirely in Tableau, focusing on platform performance, user behavior, pricing strategy, genres, and engagement. Five dashboards were developed to explore the data from different angles. 
- [Here You can view the full interactive Story](https://public.tableau.com/shared/RSQTWWMJ5?:display_count=n&:origin=viz_share_link)
  
### 1. Platform Overview
The initial analysis showed that Google Play hosts more apps than the Apple App Store. Google also has a higher share of free apps, while Apple has a more balanced free–paid distribution.

Ratings revealed a consistent pattern:
- Google apps have higher average ratings (free and paid).
- Apple apps score lower overall, reflecting differences in user expectations or review behavior.

Genre distribution also differs significantly:
- Apple’s market is heavily dominated by Games, making up over half of all apps.
- Google’s ecosystem is more diverse, with strong representation in Utilities, Productivity, Social, and Medical categories.

### 2. User Ratings & App Quality
Ratings were analyzed by genre, age group, and platform:
- Across almost all genres, Google apps receive higher average ratings.
- A higher percentage of Apple apps sit in the “Very Good” category, but Google leads in Excellent and Good ratings.
- By age group, Google rates higher in every segment, especially in apps targeting younger users.
  
This suggests that Google Play may offer a more positively engaged user base, or that developers optimize more aggressively for Android users.

### 3. Pricing Insights
Price comparison highlighted several patterns:
- Apple apps are more expensive on average than Google apps.
- For apps available on both platforms, price gaps exist in both directions, but Apple is more likely to be higher-priced.
- Certain genres (like: Finance, Medical, Education) show significant price differences between platforms.

This implies that the App Store is more friendly to premium pricing, while Google Play aligns better with free or low-cost strategies.

### 4. Genre Trends
Genre analysis showed clear strategic differences:
- Apple is dominated by Games, making it a highly competitive category.
- Google is more balanced, which may provide more opportunities for niche or utility-based apps.
- Some genres (like: Medical, Productivity, Social Networking) have a much stronger presence on Google.

This indicates that platform choice should depend heavily on the intended genre of the new app.

### 5. Engagement & User Activity
Engagement was measured through review volume:
- Google Play dramatically outperforms Apple, with over 2 billion reviews compared to Apple’s 92 million.
- For every major genre (Games, Productivity, Photo & Video, Shopping), Google apps receive far more reviews per app, suggesting much higher user interaction levels.
- Higher ratings on Google also correlate with higher engagement, reinforcing the platform's more active user base.

In summary, Google Play demonstrates significantly stronger engagement, which is especially important for app visibility and growth.

## Key Insights
### Platform
Google Play leads in:
- Ratings
- Reviews
- Engagement
- Genre diversity
- Younger user activity

### Price Strategy
- Free apps perform best on both platforms
- Google has lower average price
- Paid apps still perform slightly better in Google

### Genre
- Games dominate engagement on both platforms
- Google has more diversity (Productivity, Medical, Finance)

### Age Category
- Engagement increases significantly for ages 10+
- Google dominates youth engagement

## Recommendations
- ✔ Platform: Google Play
- ✔ Genre: Gaming 
- ✔ Age Target: 10+
- ✔ Price Strategy: Free with potential in-app monetization

## Tools Used
- Excel (cleaning, transformation)
- Tableau (analysis, dashboards, story presentation)

## Project Structure:
GA-DAB-App-Strategy
│

├── Data/

├── Tableau/

└── README.md

## Future Improvements
- Further Research
- Developers Facility

## Acknowledgements  
This project was completed as part of a group collaboration with:
- [Alya Alsharakhat](https://github.com/alyaalsharakhat)
- [Ali Salman](https://github.com/3lawisd)
- [Nora Faqeeh](https://github.com/noorafaqih172-source)


