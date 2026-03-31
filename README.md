Power BI Project – Anime Dataset Analysis

Project Overview

This Power BI project focuses on analyzing an Anime dataset to extract meaningful insights such as ratings, popularity, release trends, and audience engagement.

The dashboard helps users understand trends in anime based on attributes like score, episodes, release year, and members.

Objectives

* Analyze anime ratings and popularity
* Identify top-performing anime based on score
* Study trends by year and month of release
* Compare number of episodes vs ratings
* Visualize audience engagement using member count

Dataset Information

The dataset includes the following fields:

* Title – Name of the anime
* Episodes – Total number of episodes
* Members – Number of users who watched/liked
* Score – Rating of the anime
* Release Date – Date of release
* Year / Month – Extracted for trend analysis

Tools & Technologies

* Power BI Desktop
* DAX (Data Analysis Expressions)
* Power Query (Data Transformation)

Data Transformation Steps

1. Imported dataset into Power BI
2. Cleaned and formatted data using Power Query
3. Created new columns:

   * Year
   * Month
4. Handled missing and inconsistent values

Dashboard Features

* Top Anime by Score
* Year-wise Release Trends
* Episodes vs Ratings Analysis
* Members Distribution
* Interactive filters and slicers

Sample DAX Measures

```DAX
Average Score = AVERAGE(Anime[Score])

Total Members = SUM(Anime[Members])

Anime Count = COUNT(Anime[Title])
```

Dashboard Preview

Add screenshots here after uploading images to GitHub.

How to Use

1. Download the .pbix file
2. Open it in Power BI Desktop
3. Explore the dashboard using filters and visuals

Future Improvements

* Add genre-based analysis
* Include recommendation system
* Connect live API data

Author

Swarna Ajay Pathak

Repository Structure

PowerBI-Anime-Project
 Anime 2.pbix
  README
