# Project Overview

This project analyzes a marketing campaign dataset containing 764 campaign records to evaluate campaign effectiveness and understand how potential customers move through the marketing funnel. The analysis follows the customer journey from impressions → clicks → leads → applications → enrollments, using conversion metrics to identify where users drop off and how effectively campaigns move users from one stage to the next. Campaign performance is also examined across target audiences, geographic regions, and advertising platforms, with financial metrics used to evaluate campaign efficiency.

## Tools Used
SQL
Power BI
Excel

## Dataset

The dataset contains campaign performance information including:
Date
Campaign ID & Name
Platform
Target Audience
Impressions
Clicks
Leads
Applications
Enrollments
Campaign Cost
Revenue
Region

The dataset also includes additional campaign information such as campaign objectives, start and end dates, budget allocation, campaign type, creative type, marketing manager, channel, and conversion goal.
Campaigns are distributed across platforms including Google Ads, Facebook, Instagram, LinkedIn, and YouTube, with regional and audience information available for comparison.

Dataset: Marketing Campaign Dataset — Kaggle

## Project Goals
Analyze marketing funnel performance across campaigns
Calculate key performance indicators (KPIs) such as:
Click-through rate (CTR)
Lead conversion rate
Application conversion rate
Enrollment conversion rate
ROI
Identify major drop-off points between funnel stages
Compare campaign performance across target audiences and regions
Evaluate differences between advertising platforms
Examine campaign efficiency using cost and revenue
## Data Analysis
### Funnel Analysis

The customer journey was divided into individual funnel stages to measure how effectively campaigns move users toward enrollment.

Conversion rates were calculated between consecutive stages to identify where the largest drop-offs occur and to provide more context than raw impression, click, or enrollment totals.

### Campaign Analysis

Campaign performance was evaluated using engagement, conversion, and financial metrics.

SQL was used to aggregate campaign data and calculate performance measures, allowing campaigns with different levels of traffic and activity to be compared more consistently.

### Audience Analysis

Campaign performance was compared across target audience groups to identify differences in engagement and progression through the funnel.

Average clicks, leads, applications, and enrollments were examined alongside conversion rates to determine whether higher engagement translated into stronger results further down the funnel.

### Regional Analysis

Campaigns were grouped by region to examine geographic differences in performance.

Conversion rates, campaign cost, revenue, and ROI were compared to evaluate both marketing and financial performance across locations.

### Platform Analysis

The dataset includes campaigns from:

Google Ads
Facebook
Instagram
LinkedIn
YouTube

These platforms were compared using funnel activity, conversion rates, cost, revenue, and ROI to evaluate differences in advertising performance.

## Dashboard Features
### Marketing Funnel & Campaign Performance
Built a dashboard tracking the marketing funnel from impressions and clicks to leads, applications, and enrollments.
Used conversion rates to identify drop-offs between funnel stages and compare campaign performance.
Compared campaign costs, revenue, and ROI to evaluate marketing efficiency.
### Audience, Region & Platform Analysis
Analyzed campaign performance across different audiences, regions, and advertising platforms.
Compared engagement and conversion rates to identify differences in performance across segments.
Used both funnel metrics and financial data to evaluate campaign effectiveness.
### Interactive Filtering
Added filters for platform, target audience, region, campaign type, and date.
Enabled users to explore specific campaign segments and see how performance changed across different selections.'

## Key Insights
High impressions and clicks did not always lead to more enrollments.
Conversion rates helped show how effectively campaigns moved potential customers through the funnel.
Campaign performance varied across audiences, regions, and advertising platforms.
Looking at ROI, revenue, and costs alongside engagement metrics provided a clearer picture of campaign effectiveness.
Tracking the full funnel helped reveal where potential customers dropped off before enrollment.

## Project Takeaways
I used SQL, Excel, and Power BI to analyze marketing campaign data and build an interactive dashboard. The project helped me practice comparing campaign performance using conversion rates and financial metrics rather than relying on impressions and clicks alone. It also gave me experience turning raw data into visualizations that make campaign trends and performance differences easier to understand.
