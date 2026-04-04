
# Social Media Performance Analysis Dashboard

## Overview
This interactive Power BI dashboard provides a comprehensive analysis of social media performance across 6 major platforms. Designed for marketing teams and social media managers, it enables data-driven decisions regarding content strategy, platform investment, and audience engagement by visualizing key metrics across post types, hashtags, geographies, and time periods.

## Dashboard Link
[[View Interactive Dashboard Here](https://app.powerbi.com/links/WDSDSQozQj?ctid=733ebfdf-2ed0-4b53-b651-bece4730a970&pbi_source=linkShare)] <!-- Replace with your Power BI publish link -->

## Tools and Technologies
* **Power BI Desktop**: For data modeling and visualization.
* **DAX (Data Analysis Expressions)**: For calculating complex KPIs like Engagement Rate, MOM%, CTR, and ER%.
* **Microsoft Excel / CSV**: Used as the primary data source for social media post records.
* **Microsoft Azure Maps**: Used for geographic engagement visualization across global regions.

## Dataset
The dataset includes social media post records covering:
* **Platforms**: Facebook, TikTok, Instagram, YouTube, LinkedIn, and X.com.
* **Post Attributes**: Post type (Video, Image, Live Stream, Text, Article, Carousel, PDF), Content type (Organic / Sponsored), and Hashtags.
* **Engagement Metrics**: Total Likes, Shares, Comments, Views, Clicks, CTR, and ER%.
* **Geographic Data**: Regional engagement breakdown across USA, Japan, Brazil, UK, Canada, Australia, India, and Germany.
* **Temporal Data**: Monthly engagement data from January 2024 to May 2025.

## Dashboard Structure

### Page 1: Executive Summary (All Media)
**Purpose:** To provide a high-level snapshot of overall social media performance and identify top-performing regions, post types, and engagement trends.

* **Key KPIs**: Total Posts (5,600), Total Engagements (646.5M), Avg Engagement Rate (15.28%), Total Views (4.8bn), Total Likes (844M), Total Comments (193.3M), and Total Shares (267M).
* **Geographic Insights**: Horizontal bar chart showing audience engagement by country — USA leads with 90.6M engagements.
* **Post Type Analysis**: Bar chart revealing that Video content dominates with 75.5% of total shares.
* **Month-over-Month Trend**: A combo chart tracking Total Engagements and MOM% growth from Jan 2024 to May 2025.
* **Regional Engagement Map**: Azure Maps visual showing High, Medium, and Low engagement levels across global regions with pie chart breakdowns per country.
* **Filters**: Engagement Level (High / Low / Medium) and Content Type (Organic / Sponsored).

### Page 2: Temporal & Geo Performance
**Purpose:** To deep-dive into platform-level performance, hashtag effectiveness, content category contribution, and top-performing individual posts.

* **Performance KPIs**: Avg Engagement (15.28%), Avg Engagement Per Post (115.4K), Avg Clicks Per View (0.74%), Avg CTR — Tracked Posts (1.8%), ER% (13.45%), and Top Hashtag (#CustomerStory).
* **Platform Comparison**: Clustered bar chart comparing Total Likes, Total Shares, and Total Comments — YouTube (197M) and TikTok (195M) lead in total likes.
* **Hashtag Click Analysis**: Bar chart showing #ProductDemo drives the highest clicks, followed by #CustomerStory (5.5M).
* **Hashtag Engagement Analysis**: #CustomerStory (201M) and #ProductDemo (190M) generate the most overall engagement.
* **Content Category Table**: Matrix showing engagement % by content category (Customer Story, Educational, Entertainment, Event/Webinar, Product Promotion) across all 6 platforms.
* **Top-Performing Posts Table**: Detailed post-level table showing Post_ID, Platform, Region, Total Likes, Total Shares, Total Comments, ER%, and CTR%.
* **Filters**: Engagement Level, Post Type (Article, Carousel, Image, Live Stream, PDF, Text, Video), and Content Type (Organic / Sponsored).

## How to Use
1. **Navigation**: Use the buttons in the top right (**Executive Summary** and **Temporal & Geo Performance**) to switch between the two report pages.
2. **Platform Filter**: Use the social media icons on the left sidebar (Facebook, TikTok, Instagram, YouTube, LinkedIn, X.com) to filter data by platform.
3. **Slicers**: Use the Engagement Level, Post Type, and Content Type filters to drill down into specific segments.
4. **Interactive Visuals**: Click on any bar, region, or hashtag to cross-filter the entire page and surface deeper insights.
5. **Reset**: Use the refresh icon on the sidebar to clear all filters and return to the full view.

## Dashboard Images

### Page 1: Executive Summary
(![Executive Summary](screenshots/Social%20Media%20Dashbaord%20(3)_page-0001.jpg))

### Page 2: Temporal & Geo Performance
(![Temporal & Geo Performance](screenshots/Social%20Media%20Dashbaord%20(3)_page-0002.jpg)g)

---
Developed by Waleed Javed
