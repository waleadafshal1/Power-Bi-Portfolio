# EuroState Property Dashboard

## Overview
This interactive Power BI dashboard provides a comprehensive analysis of the European real estate market. It enables data-driven insights for real estate investors, analysts, and agencies by visualizing key property metrics across countries, property types, energy ratings, amenities, and pricing trends.

## Dashboard Link
[[View Interactive Dashboard Here](https://app.powerbi.com/links/YOUR_LINK_HERE)] <!-- Replace with your actual Power BI publish link -->

## Tools and Technologies
* **Power BI Desktop**: For data modeling, visualization, and dashboard development.
* **DAX (Data Analysis Expressions)**: For calculating advanced KPIs such as Median Rental Yield, Avg. Days on Market, Price Differences, and Growth Trends.
* **Microsoft Excel / CSV**: Primary data source containing 5,000+ property records.
* **Power BI Visuals**: Advanced charts including stacked bars, line charts, donut charts, and treemaps.

## Dataset
The dataset includes detailed property listings across Europe with:
* **Countries**: France, Germany, Netherlands, Spain, Italy, Austria, Portugal, Poland, Czech Republic, Belgium.
* **Property Attributes**: Listing Type (Rental / Sale), Property Type (Apartment, Villa, Office, Retail, etc.), Energy Rating (A–G), Floor Category, Amenities Status.
* **Key Metrics**: Sale Price, Rental Yield, Days on Market (DOM), Year Built, Total Amenities.
* **Temporal Data**: Market growth trends from 2020 to 2024.
* **Total Records**: 5,000 properties (2,045 Rental | 2,955 Sale).

## Dashboard Structure

### Page 1: Market Overview & Analysis
**Purpose:** High-level overview of the European property market including total properties, rental vs sale distribution, country-wise performance, and energy efficiency insights.

* **Key KPIs**: Total Properties (5,000), Rental Properties (2,045), Sale Properties (2,955), Avg. Days on Marketing (163), Median Rental Yield (5.60%).
* **Properties by Country and Listing Type**: Stacked bar chart showing rental and sale distribution per country.
* **Properties by Property Type and Listing Type**: Breakdown by Apartment, Villa, Office, Retail, etc.
* **Properties by Energy Rating and Listing Type**: Analysis of energy-efficient vs non-efficient properties.
* **Market Growth Year by Year**: Combo chart showing rental and sale trends (2020–2024).
* **Price Difference Between Properties With And Without Amenity**: Donut chart highlighting impact of amenities (Parking, Elevator, Gym, Swimming Pool).
* **Filters**: Listing Year, Listing Type, Amenities Status, Country.

### Page 2: Property Details Table
**Purpose:** Granular view of individual property listings with full filtering capabilities.

* **Detailed Property Table**: Includes PropertyID, Listing Type, Total Amenities, Country, City, Days on Marketing, DOM Status, Year Built, Sale Price, Energy Rating, and Amenities Status.
* **Advanced Filters**: Property ID search, Country, Furnishing Status, Amenity, Energy Rating.
* **DOM Status**: Visual indicators (Hot, Active, Slow, Stagnant).

### Page 3: Pricing & Performance Insights
**Purpose:** Deep dive into pricing trends, energy efficiency impact, and premium features.

* **Do Energy-Efficient Homes Command Higher Prices?**: Line chart showing average prices by energy rating (A–G).
* **Sale Price For Properties With vs Without Amenities**: Clustered bar chart comparing prices with/without key amenities.
* **Market Composition by Furnishing & Listing Type**: Treemap showing distribution of Furnished, Semi-Furnished, and Unfurnished properties.
* **Which Countries Offer the Most Expensive Space?**: Horizontal bar chart (sqm price or similar metric).
* **Sale Price VS Bedrooms**: Bar chart showing average sale price by number of bedrooms.
* **Do Rentals or Sales Move Faster Across Europe With Energy Rating**: Stacked bar analysis by energy rating.
* **Filters**: Listing Year, Listing Type, Amenities Status, Country.

## How to Use
1. **Navigation**: Use the buttons on the left sidebar (**Properties**, **Prices**, **Details**) to switch between report pages.
2. **Filters**: Apply filters using Listing Year, Listing Type, Amenities Status, and Country from the Filters pane.
3. **Interactive Visuals**: Click on any bar, segment, or country to cross-filter the entire dashboard.
4. **Reset**: Use the **Reset** button to clear all filters and return to the default view.
5. **Table Interaction**: Sort, filter, and search directly within the property details table.

## Dashboard Images

### Page 1: Market Overview
![Market Overview](screenshots/EuroState%20Property%20Dashboard_page-0001.jpg)

### Page 2: Property Details
![Property Details](screenshots/EuroState%20Property%20Dashboard_page-0003.jpg)

### Page 3: Pricing & Performance Insights
![Pricing & Performance Insights](screenshots/EuroState%20Property%20Dashboard_page-0002.jpg)

---
Developed by Waleed Javed
