# Citi_Bike_Viz

Identifying Unexpected Phenomena
Phenomenon 1: Variation in Bike Usage Across Different User Types (Member vs Casual)
Hypothesis: There might be significant differences between members and casual riders in terms of ride patterns, usage duration, and preferred stations.
Suggested Visualizations:

Bar Chart: Visualize the proportion of total trips taken by members versus casual riders across the chosen time period. This will help highlight any shifts or changes in the user base.
Line Chart: Show how the total ridership has changed over time for both user types. This can reveal seasonal patterns or trends.
Heat Map of Stations: Display a map showing the most popular starting and ending stations for both members and casual users. Use color intensity to represent trip counts.
Time Series of Peak Hours: Compare the peak hours for bike usage by members and casual users. This can uncover whether different user types have distinct commuting or leisure patterns.
Box Plot: Show the distribution of trip duration (from Started at to Ended at) by user type. This will help identify if casual users typically have longer or shorter trips compared to members.

### Phenomenon 2: Station Popularity and its Connection to Geographic or Socioeconomic Factors

Hypothesis: Some stations may be much more popular for starting or ending trips due to their proximity to key transit hubs, recreational areas, or specific demographic regions.

Suggested Visualizations:

Static Map of Bike Stations: Plot all bike stations with color-coding based on the frequency of trips starting or ending at each station. Overlap zip code data or population density to explore potential correlations.
Dynamic Time-Based Map: Create a dynamic map to visualize how the popularity of stations changes over time. Use filters for specific months or years to identify seasonality or trends.
Top 10 Starting and Ending Stations: Create bar charts showing the top 10 stations for starting and ending trips. Add annotations or tooltips to explain why these locations are popular (e.g., proximity to parks, business centers, or transit).
Bottom 10 Stations: Similarly, visualize the bottom 10 stations and try to explain their low usage rates. This could help city planners understand underutilized infrastructure.
Scatter Plot of Trip Distance: Show trip distances by start station location to uncover whether some stations are associated with longer trips, perhaps in areas with fewer nearby stations.
Analysis:

Use socioeconomic or geographic data to explain why some stations might be underutilized or overutilized. For example, stations near major transportation hubs may experience higher usage, while stations in residential areas may have more casual riders.
Examine whether certain stations are more prone to short trips (e.g., from one transit stop to another) or longer recreational rides (e.g., along a waterfront or park).
Dashboard Design
You can create two dashboards, one for each phenomenon.
