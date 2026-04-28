# Data Visualization Report: Airbnb Case Study

**Author:** Arda Tutmaz (212134)  
**Date:** April 2026  
**Subject:** Descriptive Statistics

## 1. Executive Summary
This report analyzes the Airbnb dataset to understand the underlying statistical structure of home-sharing listings. Through descriptive statistics and visualization, we examine how price correlates with room types and geographic locations.

## 2. Methodology
The data was processed using Google Colab. Descriptive measures such as mean, median, and standard deviation were calculated, followed by the generation of plots to identify patterns and anomalies.

## 3. Data Visualizations & Analysis

### A. Distribution of Prices
The histogram below shows that the majority of listings are concentrated in the lower price range, with a long tail indicating luxury outliers.
> ![Price Distribution](price_dist.png)  
> *Figure 1: Histogram showing the skewness of Airbnb prices.*

### B. Room Type Frequency
This count plot illustrates the dominance of "Entire home/apt" and "Private room" within the market, reflecting the most common supply types.
> ![Room Type Count](room_type_count.png)  
> *Figure 2: Distribution of accommodation types.*

### C. Geographical Price Heatmap
By plotting latitude and longitude against price, we can observe that specific high-traffic areas command significantly higher premiums.
> ![Geo Map](geo_analysis.png)  
> *Figure 3: Scatter plot representing the spatial distribution of prices.*

### D. Correlation Heatmap
The heatmap identifies which numerical variables (e.g., number of reviews, availability) have the strongest relationships with listing prices.
> ![Correlation Heatmap](heatmap.png)  
> *Figure 4: Correlation matrix of dataset variables.*

## 4. Statistical Conclusion
1. **Right-Skewed Data:** The pricing data is heavily right-skewed, meaning average prices are influenced by high-end listings.
2. **Location Premium:** Geographical coordinates are a primary driver for pricing, as seen in the cluster analysis.
3. **Supply Trends:** Private rooms and entire apartments make up over 90% of the total listings in this dataset.
