# CITI BIKE ANALYTICS

## Introduction:
The Citi Bike program, launched in 2013, is the largest bike-sharing initiative in the United States, based in New York City. This program enables New Yorkers and visitors to easily rent and return bikes across numerous stations in the city. Over the years, a substantial amount of data has been collected to track ridership patterns, station usage, and bike availability, making it a valuable source of information for understanding urban mobility.

The goal of this project is to analyze Citi Bike’s publicly available trip history logs, uncover two unexpected phenomena, and provide key insights to help city officials enhance the bike-sharing service.

## Purpose:
This project seeks to achieve the following objectives:

- Analyze Ridership Trends: 
Identify trends and patterns in bike usage across different time periods and locations in New York City.

- Discover Unexpected Phenomena: Using data aggregation and visualization, discover at least two surprising or unusual findings that might reveal important insights for city planners and program administrators.

- Create Dashboards and Visualizations: Build interactive dashboards using Tableau to present the findings in a clear and visually appealing format. These visualizations will allow city officials to better understand the program’s performance and make data-driven decisions for its future development.

- Provide Recommendations: Offer suggestions for improving the bike-sharing system based on the analysis, including potential opportunities for increasing ridership or addressing program inefficiencies.

## Data Sources:
The primary dataset for this analysis comes from Citi Bike’s Trip History Logs, which are publicly available and updated monthly. The dataset includes key attributes such as:

- Ride ID
- Start and End Time
- Start and End Station Names
- Latitude and Longitude Coordinates of Stations
- Rideable Type (Classic or Electric Bike)
- User Type (Member or Casual)
- Trip Duration
-Timespan: Data from multiple periods (months and/or years) can be combined to assess trends over time. The timespan used in this analysis depends on the phenomena identified.

## Project Usage and Methodology:
- Data Cleaning and Preparation:

  - Aggregation: Multiple CSV files containing trip history logs were downloaded from Citi Bike's data page. These datasets were merged to analyze usage across different months and years.
  - Cleaning: Any missing or irrelevant data points were removed or filtered to ensure data accuracy. This included handling missing station names and ride IDs.

- Data Visualization & Analysis:

  - Unexpected Phenomena Discovery: Using exploratory data analysis (EDA), two unexpected phenomena were identified within the dataset. Visualizations were created to illustrate these phenomena.
  
      Two phenomena identified are:
    1. Variation in Bike Usage Based on Membership Type:

        The analysis reveals distinct patterns in bike usage between electric bikes and classic bikes across different membership types. This includes variations in peak usage hours, ride duration, and seasonal trends for each membership category (annual members vs. casual riders). For instance, classic bike users consistently outnumber electric bike users, and there are clear distinctions in how different user groups prefer certain types of bikes.

    2. Geographic and Socioeconomic Influence on Bike Usage:
        Another phenomenon relates to the geographic distribution of rides and how socioeconomic factors, such as household income, influence bike usage. The dashboards suggest that stations located in higher-income areas tend to see more Citi Bike activity, while lower-income areas exhibit moderate usage. There is also a notable correlation between bike usage and proximity to public transit hubs, which suggests that Citi Bikes are often used as a last-mile commuting option.

  - Station Popularity Fluctuations: Dynamic maps were created to show how bike station popularity changed over time, with zip code data overlaid to contextualize usage based on geographic and socioeconomic factors.

  - Unusual User Behavior: Visualizations explored differences in ride duration, ride frequency, and bike type preference across different user groups (members vs. casual riders).

  - Advanced Visualization Creation: Tableau dashboards were designed to include various charts and maps, such as:

  - Heatmaps showing peak hours by user type.

  - Donut charts displaying the number of rides across seasons and bike types.

  - Dynamic maps that track how each station’s popularity changes over time and location.
  - Link to the URL : <code style ="color:blue">[Citi_Bike_Vis](https://public.tableau.com/app/profile/ernawaty.ernawaty/viz/Citi_Bike_Viz_17257435405910/Story1?publish=yes)</code>


## Tableau Story Creation:

A Tableau Story was created to bring together all the visualizations and dashboards. This story format allows city officials to interactively explore different aspects of the data, including ridership trends, user behavior, and geographic patterns.

### Visualization Types Used:
- Dynamic Map with Zip Code Overlay: Highlights how station popularity changes across different neighborhoods and income levels.
- Heatmaps: Shows peak bike usage hours segmented by user type (weekday vs. weekend).
- Donut Charts: Compares the proportion of rides across seasons and membership types.
Line Charts: Track monthly ride counts and station popularity trends.
- Bar Graphs: Represent bike usage based on trip duration and user type (classic vs. electric bikes).

## Results and Trends:
- Key Insight 1: Shifts in Station Popularity Over Time
The dynamic maps revealed significant changes in station usage across the seasons. Certain stations, especially those near high-income neighborhoods and major transit hubs, showed consistently high usage, while others fluctuated depending on external factors like weather, events, and commuting trends.

- Key Insight 2: Differences in Ride Behavior Based on User Type
The analysis showed distinct differences between members and casual riders. Casual riders tended to use bikes for shorter, recreational trips on weekends, while members were more likely to use bikes for commuting during weekdays, especially during peak hours. This distinction helps city planners better understand the different user demographics and their needs.

## Conclusion:
This project demonstrates the value of Citi Bike’s trip history data in uncovering hidden trends and patterns in urban mobility. By identifying unexpected phenomena, city officials can make data-driven decisions to improve bike accessibility, optimize station placement, and cater to both casual and commuter ridership. The dashboards and visualizations provided will serve as an ongoing resource for the Citi Bike program as it continues to expand and adapt to New York City’s evolving transportation needs.

## Usage Notes:
Tableau Dashboards: The interactive Tableau dashboards allow users to filter the data by season, bike type, user type, and more. City officials can explore these dashboards to understand how various factors influence bike-sharing usage.
File Formats: The raw data is stored in CSV format, and the visualizations are shared through Tableau Public, making the analysis easily accessible and shareable.