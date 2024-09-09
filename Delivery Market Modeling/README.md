
# Delivery Market Modeling

This data project has been used as a take-home assignment in the recruitment process for the data science positions at Delhivery.

Delhivery is the largest and fastest-growing fully integrated player in India by revenue in Fiscal 2021. They aim to build the operating system for commerce, through a combination of world-class infrastructure, logistics operations of the highest quality, and cutting-edge engineering and technology capabilities.

# PROBLEM OF STATEMENT
The Data team builds intelligence and capabilities using this data that helps them to widen the gap between the quality, efficiency, and profitability of their business versus their competitors.

The company wants to understand and process the data coming out of data engineering pipelines:

Clean, sanitize and manipulate data to get useful features out of raw fields;
Make sense of the raw data and help the data science team to build forecasting models on it.

# Analysis

![image](https://github.com/user-attachments/assets/dedc3ade-5858-4853-a42e-4339f73407b2)

The dashboard provides insights into delivery market trends based on key metrics like trips, duration, distance, and route types. Here’s a simple breakdown of the insights:

Key Metrics:

1. Total Trips: There have been 145,000 trips recorded.

2. Average Duration: The average time taken for a trip is around 962 minutes.

3. Average Distance: The average distance covered per trip is 234 kilometers.

4. Route Type Distribution:
   
   The pie chart shows that FTL (Full Truck Load) is the dominant route type, making up 68.79% of trips, while Carting accounts for 31.21%.

5. Time Series Analysis of Trips:

   The line graph shows the number of trips over different time points, with a general downward trend in trip count, suggesting fewer trips as time progresses.

6. Average Trip Duration by Route Type:

   The bar chart shows that trips to different destinations have varying durations, with Carting trips generally being longer compared to FTL trips.

7. Trip Duration vs. Distance:

   The scatter plot shows a relationship between trip duration and distance. It highlights that Carting trips, on average, cover shorter distances but take longer than FTL trips, which may cover longer distances in less time.


![image](https://github.com/user-attachments/assets/1433d503-b768-41f0-8bf6-8ec0010fc90d)

The dashboard provides comparative and efficiency-related insights for delivery trips, focusing on actual vs. expected performance metrics and route types. Here's a simple breakdown of the insights:

1. Actual vs. OSRM Time:

   The bar chart compares the actual time taken for trips vs. the OSRM (Open Source Routing Machine) predicted time. In some trips, the actual time exceeds the OSRM time predictions, indicating potential delays or inefficiencies, while other trips closely match the predictions.

3. Actual vs. OSRM Distance:

   The line chart compares the actual distance covered in trips against the OSRM predicted distance. It appears that most trips closely follow the OSRM's estimated distance, though some discrepancies exist, possibly due to route changes or detours.

4. Trip Duration Efficiency Analysis by Destination:

   The horizontal bar chart highlights trip duration (from start scan to end scan) for different destination centers. Some destinations (like IND56212AAC and IND781018AAB) have longer average durations, suggesting possible inefficiencies or bottlenecks at these locations.

5. Route Type Analysis:
   
   The bar chart shows the count of trips by route type (Carting vs. FTL) for various destination centers. Carting dominates in most destination centers, while FTL appears less frequent, especially in certain destinations (like IND74112AAB), indicating the preference for carting in these areas.



