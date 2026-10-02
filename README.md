# INSIGHTFY: Vienna Airbnb Market Analysis

## Project Overview
Imagine a traveler opening Airbnb in Vienna for the first time, with over 14,000 listings staring back at them. This project walks alongside the traveler, starting from simple questions about price and quality, and going deeper layer by layer to uncover the hidden structure of the market. The findings demonstrate that these insights are valuable not just for travelers, but for anyone looking to enter this market.

**Team Members:** Shadi Nayyeri, Zahrasadat Rezaei, Mohammad Rahmani Rezaiyeh, Sajjad Vazifehdoost 
**Academic Context:** Visualization Lab SS26, Johannes Kepler University Linz, June 2026.

## The Dataset
This project utilizes a dataset obtained from Inside Airbnb, an independent open-data project. 
*   **Size:** Contains detailed information about 14,124 Airbnb listings in Vienna, Austria.
*   **Timeframe:** The data was scraped in September 2025.
*   **Attributes:** The dataset comprises 79 attributes grouped into host profiles, property details, pricing and availability, location, guest reviews (overall rating and six sub-scores), and performance estimates (estimated occupancy and revenue over the last 365 days).

## Key Findings & Visual Analysis

### A.1 - The Price Landscape
*   Prices in Vienna follow a clear radial pattern; the closer a listing is to the historic center, the more expensive it is.
*   Innere Stadt, the historic core, commands a median price of approximately €196.
*   Peripheral districts like Liesing and Simmering sit below €80, representing a price gap of roughly 195% compared to the center.
*   Certain central neighborhoods, such as Neubau, exhibit high variance, containing both affordable and expensive listings side by side.

### A.2 - Does Price Guarantee Quality?
*   The vast majority of listings are concentrated in the low-to-mid price range and already achieve high cleanliness scores between 4.6 and 5.0.
*   There is virtually no correlation between price and cleanliness (r = 0.03).
*   Paying more does not guarantee a better cleanliness experience, and a €50 apartment can be just as clean as a €200 one.

### B.1 - Hunting for Hidden Gems
*   "Hidden Gems" were defined as listings priced below the city-wide median, rated 4.8 or higher by guests, and having at least 10 reviews.
*   These high-value, low-cost hidden gems do not cluster in tourist-heavy central neighborhoods.
*   The highest concentrations appear in districts that most travelers do not consider first, such as Favoriten, Leopoldstadt, and Landstraße.
*   The vast majority of these gems are Entire Homes, with Private Rooms making up a smaller share.

### B.2 - Market Structure & Service Gap
*   The Vienna Airbnb market has a highly unequal structure, indicated by a Gini coefficient of approximately 0.77.
*   Just 8.3% of hosts operating multiple listings control 51.6% of total estimated revenue, and the top 20% capture 73.8% of the revenue.
*   Despite this revenue dominance, multi-listing hosts score lower than single-listing hosts across all three human-centric service metrics: cleanliness (+0.18 gap), communication (+0.19 gap), and check-in (+0.15 gap).

## Implications & Conclusions
*   **For Travelers:** Travelers cannot rely on price as a quality signal.Furthermore, multi-listing operators do not necessarily provide better service; smaller, personal hosts often deliver a more human and higher-quality experience.Travelers seeking the best value should look beyond the city center.
*   **For Individual Newcomers:** There is no need to fear competing with large-scale operators. Single-listing hosts hold a natural competitive advantage in service quality.
*   **For Investors:** The current service gap represents a genuine investment opportunity. New entrants with multiple listings can differentiate themselves by focusing on human-centric service quality, which is precisely where current multi-listing operators are weakest.
