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
### Funnel & Campaign Performance
Visualizes the complete marketing funnel from impressions to enrollments
Displays key campaign metrics and conversion rates
Highlights drop-offs between funnel stages
Provides an overview of campaign performance and efficiency
Audience, Region & Platform Analysis
Breaks down campaign performance by target audience, region, and advertising platform
Compares engagement and conversion across different segments
Allows platform performance to be evaluated using both funnel and financial metrics
###Interactive Filtering
Allows users to filter results by campaign characteristics
Supports filtering by platform, audience, region, campaign type, and date
Updates dashboard visuals based on selected filters for more focused analysis

## Key Insights
High impression and click volume does not necessarily translate into strong enrollment performance.
Conversion rates provide additional context when comparing campaigns with different levels of traffic.
Campaign performance varies across target audiences, regions, and advertising platforms.
Strong engagement at the beginning of the funnel does not always result in strong performance at later stages.
Examining cost, revenue, and ROI alongside funnel metrics provides a more complete view of campaign efficiency.
Analyzing the full funnel helps identify where potential customers are lost rather than focusing only on top-level engagement.
Project Takeaways

This project provided hands-on experience using SQL, Excel, and Power BI to analyze campaign data and present the results through an interactive dashboard.

The analysis focused on moving beyond raw campaign totals by using conversion and financial metrics to compare performance across different campaigns and segments. This provided a more complete view of how marketing activity translated into applications and enrollments.
