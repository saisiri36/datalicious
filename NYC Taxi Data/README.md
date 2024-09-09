
#  NYC Taxi Data Analysis

This coding challenge is designed to test your skill and intuition about real world data. For the challenge, we will use data collected by the New York City Taxi and Limousine commission about “Green” Taxis. Green Taxis (as opposed to yellow ones) are taxis that are not allowed to pick up passengers inside of the densely populated areas of Manhattan. We will use the data from September 2015.

# DASHBOARD

![Screenshot 2024-09-09 145223](https://github.com/user-attachments/assets/4bc57285-78b3-4095-961b-f6599dc6065b)


![Screenshot 2024-09-09 145223](https://github.com/user-attachments/assets/4f62c395-9c02-4526-9a64-5b23123c10c5)

# Overall Insights

1. Trip Distribution & Distance (Top-Left Dashboard):
   
   Observation 1: Most taxi trips are short, with the highest frequency occurring for trips between 0-2 miles.
   
   Observation 2: As distance increases, there is a gradual decrease in the number of trips.
   
   Observation 3: The majority of trips are intra-borough, indicating that passengers often use taxis for short distances within the same borough.
   
   Hypothesis 1: Shorter trips may be more frequent due to a dense urban environment or for tasks such as airport travel.
   
   Hypothesis 2: Longer trips may be less frequent due to higher fares associated with greater distances.
   
   Hypothesis 3: The long tail of trip distances likely represents special cases like airport rides or inter-borough travel.

3. Trip Time Distribution by Hour (Top-Left Dashboard):

   Both average and median trip distances increase during the evening, peaking around 7 PM, possibly reflecting longer commuting times or other special travel cases.
The median trip distance remains shorter than the average throughout the day, indicating some very long trips skewing the average upwards.

4. Speed Analysis (Bottom-Left Dashboard):
   
   Average Speed by Week Number: Speed varies across weeks, showing some dips around week 36 and week 40.
   
   Average Speed by Hour of Day: Speeds peak between 3 PM and 6 PM, likely due to lighter traffic or faster roads, while lower speeds are observed during night hours (3 AM to 6 AM) and 
   early morning rush (7 AM to 9 AM).

6. Trip Distribution by Borough (Bottom-Right Dashboard):
   
   Manhattan Dominates: Manhattan sees the largest number of pickups and drop-offs, reflecting the high demand for taxis within the borough.
   
   Inter-borough Travel: Intra-borough trips dominate, with fewer inter-borough trips, which makes sense given Manhattan's density and the convenience of intra-city taxi services.

8. Trips by Hour of Day:
   
    Taxi usage increases throughout the day, with peaks in the evening between 6 PM and 9 PM, which is likely due to after-work travel.
   
    Morning Rush: There is a significant rise in trips between 7 AM and 9 AM, coinciding with the morning commute.

10. Airport Trips (Top-Left Dashboard):

    The dashboard highlights an average airport fare of $56.53 and an average airport trip distance of 10.24 miles.
    
    The data suggests that airport-related trips might be a small portion (4435 trips), but they represent higher-than-average fares and distances.

# Analysis & Trends:

Short-distance trips dominate: The high number of short trips points to typical inner-city taxi usage, with only a few long-distance trips.

Peak travel times: Taxi usage increases in the early morning (for commuting) and in the evening, which corresponds with commuting hours.

Speed Variations: Speed data shows higher speeds during off-peak hours, likely when there is less traffic.

These insights reflect urban travel patterns, with a focus on short, intra-borough trips, a significant number of Manhattan trips, and noticeable airport-related rides.
