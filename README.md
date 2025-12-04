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
Analysis was conducted entirely in Tableau, using 5 dashboards:

### 


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



