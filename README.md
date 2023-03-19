# Citi Bike Usage (August 2019)

## Overview of Project

### Purpose

The purpose of this project was to use Tableau Public to visualize data from Citi Bike's bikesharing statistics from August 2019 and to provide summary statistics.

### Data

The data used comes from Citi Bike's public datasets, specifically `201908-citibike-tripdata.csv.zip`. That file can be found **[HERE](https://s3.amazonaws.com/tripdata/index.html)**.

## Results

### Tableau Visualization

All of the proceeding screenshots are taken from my Tableau Public visualization. All of that data, and more, can be viewed and interacted with in my [August 2019 Citi Bike Story](https://public.tableau.com/app/profile/michael.marchand2858/viz/CitibikeAugust2019_16790902829250/August2019CitiBikeStory) story.

### Customer Types

![overview](img/overview.png)
Grouping the users into 2 different categories of `Customer Type` and `Gender` shows:
- **Subscribers** are the largest group of users by `Customer Type`
- **Males** are the largest group of users by `Gender`<br><br>


### Popular Citi Bike Station Locations

![starting_location](img/starting_loc_bubble.png)

This map shows all the starting locations of bike trips, with the bubble size representing the amount.<br><br>

![ending_location](img/ending_loc_bubble.png)

This map shows all the ending locations of bike trips, with the bubble size representing the amount.<br><br>


### Length of Trips

![tripduration](img/tripduration.png)

This chart shows that 5 minutes was the single most common length of bike trip duration.<br><br>

![tripduration_by_gender](img/tripduration_by_gender.png)

This chart breaks down the trip duration into each gender.<br><br>
### Popular Times of Usage

![heatmap_usage_times](img/heatmap_usage_times.png)

This heatmap shows at what hour in each day of the week sees the most usage.<br><br>

![heatmap_usage_times_female](img/heatmap_usage_times_female.png)

This heatmap shows at what hour in each day of the week sees the most usage by females.<br><br>

![heatmap_usage_times_male](img/heatmap_usage_times_male.png)

This heatmap shows at what hour in each day of the week sees the most usage by males.<br><br>

![heatmap_usage_days](img/heatmap_usage_days.png)

- The first heatmap shows what days in a week see the most usage, and is grouped by `Customer Type`.
- The second heatmap shows what days in a week see the most usage, and is grouped by `Customer Type` and `Gender`<br><br>

## Summary

### Brief Analysis

- August 2019 saw 2,344,224 trips completed
- Subscribers are the majority customer type
- Males are the majority Gender Type
- The majority of customers are using the bikes for under 30 minute trips
- All days from 2:00am to 5:00am see the least amount of trips being taken with Citi Bikes
- Thursday between 5:00pm and 7:00pm see the most usage for the bikes
- Thursdays and Fridays are the days with the most usage in general

### Additional Visualizations

![gender_usage_by_birth_year](img/gender_usage_by_birth_year.png)
This visualization breaks down the usage of each gender by birth year. The default birth year for a customer is `1969`. For this reason, the year `1969` cannot be considered an accurate data point.<br><br>

![starting_ending_loc_pair_count](img/starting_ending_loc_pair_count.png)
This one was fun. I wanted to see if there were any repeat combinations of `Starting Station` to `Ending Station` pairings. I was surprised to find there were actually quite a few. This visualization is also very beautiful. If you haven't checked out the Tableau Public story yet, this slide is fun and interactive.<br><br>
