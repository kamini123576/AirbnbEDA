# Airbnb Listings EDA Project: New York 2024

Project Overview : This project performs Exploratory Data Analysis (EDA) on New York Airbnb data to uncover trends and patterns in rental listings. We use libraries like Pandas, Numpy, Matplotlib, Seabornfor cleaning, visualization, and analysis.

Objective: 
The goal of this project is to:

1. Analyze room types, prices, and availability across different neighborhoods.
2. Understand host behavior and listing patterns.
3. Detect potential outliers in prices.
4. Provide recommendations for guests and hosts based on insights.

Dataset: The dataset contains 20,765 entries and 22 features, including:

1. id: Unique identifier for each listing
2. name: Title of the Airbnb listing
3. host_name: Name of the host
4. neighborhood_group: Group (borough) where the listing is located
5. latitude/longitude: Geolocation of listings
6. price: Nightly rental price
7. room_type: Type of accommodation (e.g., entire home, private room)
8. reviews_per_month: Average monthly reviews for the listing
9. availability_365: Number of available days in the year.

Key Findings and Insights:

1. Price Trends:

Manhattan has the most expensive listings, followed by Brooklyn.
Entire homes/apartments cost significantly more than private or shared rooms.
2. Room Type Distribution:

Entire homes/apartments are the most common, but private rooms offer budget-friendly options.
3. Outliers in Price:

Few listings priced at $10,000+ were detected, indicating the need to filter such extreme values.
4. Availability Patterns:

Listings with high availability tend to have lower prices and more reviews, likely due to better guest experience.
5. Host Behavior:

Some hosts manage multiple listings, indicating a trend toward professional hosting.

Conclusion:
 This project offers valuable insights into the New York Airbnb market, helping both guests and hosts make informed decisions. By using EDA techniques, we identified key trends and developed actionable recommendations. Future improvements can involve advanced analytics and predictive modeling to further enhance the findings.
