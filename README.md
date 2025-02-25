# EDA-Analyisis-New-York-AirBnb-2024

## Project Overview

This project conducts Exploratory Data Analysis (EDA) on New York Airbnb listings to identify key trends and patterns. Using Pandas, NumPy, Matplotlib, and Seaborn, we clean, visualize, and analyze the data to gain meaningful insights.


## Objective

The main goals of this analysis are:

* Examining room types, pricing, and availability across neighborhoods.
* Understanding host behavior and listing trends.
* Identifying price outliers and anomalies.
* Providing data-driven recommendations for guests and hosts.

## Dataset Overview

The dataset consists of 20,757 entries and 22 features, including:

* **id**: Unique listing identifier
* **name**: Airbnb listing title
* **host_name**: Name of the host
* **neighborhood_group**: Borough where the listing is located
* **latitude/longitude**: Geographical coordinates
* **price**: Nightly rental cost
* **room_type**: Accommodation type (e.g., entire home, private room)
* **reviews_per_month**: Average monthly reviews per listing
* **availability_365**: Number of available rental days in a year

## Workflow and Methodology

### 1. Data Cleaning
  * Handling missing values: Addressing null values in columns but couldn't find any.
  * Data type corrections: Converted last_review into a datetime format.
  * Outlier removal: Capped listings priced above $1,000 to prevent skewed analysis.

### 2. Exploratory Data Analysis (EDA)

1. **Room Type Analysis**

    * Visualized room type distribution using bar charts.
    * Found Entire home/apt to be the most common listing.

2. **Neighborhood Pricing Insights**
  
    * Analyzed price variations by borough.
    * Manhattan had the highest average rental prices.

3. **Availability Trends**

    * Used heatmaps to explore correlations between price, availability_365, number_of_reviews, and beds.

4. **Price Distribution**

    * Created histograms to display price distribution.
    * Most listings fell within the $50 - $300 range.

5. **Host Analysis**

    * Used box plots to identify hosts managing multiple listings.

6. **Review Patterns**

    * Applied pair plots to study relationships between reviews, price, and availability.

### 3. Data Visualization

* **Pairplots**: Highlighted relationships among price, availability, and number_of_reviews.
* **Heatmaps**: Showed correlations between numerical variables.
* **Histograms & Boxplots**: Detected price outliers.
* **Bar Charts**: Illustrated room type and neighborhood distribution.

## Key Findings

1. **Price Trends**

    * Manhattan is the most expensive listing, followed by Brooklyn.
    * Entire homes/apartments cost significantly more than private or shared rooms.

2. **Room Type Distribution**

    * Entire homes/apartments dominate the market, but private rooms offer more budget-friendly options.

3. **Outliers in Pricing**

    * Some extreme outliers ($10,000+ listings) suggest potential data errors or luxury properties.

4. **Availability & Demand Patterns**

    * Listings with higher availability tend to have lower prices and more reviews, indicating better guest experiences.

5. **Host Behavior**

    * Some hosts manage multiple listings, suggesting a trend toward professional hosting.

## Recommendations

**For Guests**:
  * Choose listings with high availability and good reviews for a better experience.
  * Private rooms in Brooklyn offer affordable alternatives to Manhattan.

**For Hosts**:
  * Improve availability and review response rates to attract more bookings.
  * Set competitive pricing based on borough trends to maximize occupancy.

## Future Enhancements

* Implement machine learning models to predict listing prices based on location and features.
* Perform sentiment analysis on guest reviews to assess satisfaction levels.
* Develop an interactive dashboard using Plotly or Tableau for real-time monitoring.

## Conclusion

This project provides valuable insights into New York Airbnb listings, helping both guests and hosts make informed decisions. Through EDA techniques, we identified pricing trends, availability patterns, and host behaviors. Future improvements could include advanced analytics and predictive modeling for deeper market understanding.
