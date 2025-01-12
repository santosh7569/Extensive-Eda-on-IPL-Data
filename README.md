# Extensive-Eda-on-IPL-Data
Integrated match data from external CSV files and cleaned it with Pandas and NumPy, handling missing values and outliers. Developed visualizations like bar plots, pie charts, and heatmaps to examine team wins, player performance, and seasonal trends using seaborn and matplotlib. Provided actionable insights on target runs, margins, and performance to aid data-driven decisions.

## Project objective
Goal is to extract meaningful insights, uncover patterns, and use visualizations to effectively present the
findings. This task involves understanding trends, comparisons, and relationships in the data, leading to
actionable insights.

## Project Workflow
1. Data Preparation:
Loaded the dataset and inspected its structure using .head(), .info(), and .describe() to understand its characteristics.
Handled missing values, duplicates, and ensured appropriate data types for consistency.
For time-series data, parsed the date column into a datetime object for accurate temporal analysis.
2. Data Visualization:
Utilized various visualization techniques to explore the dataset in-depth:
Trends:
Analyzed match-winning trends by team, season, and venue.
Comparisons-
 Compared team performances and player contributions to uncover top performers.
Distributions-
Explored numerical variables using histograms, box plots, and density plots to uncover patterns.
Relationships-
Used scatter plots and pair plots to explore correlations between variables.
Analyzed relationships such as runs scored and match outcomes 
Advanced Visualizations-
Created heatmaps to visualize correlations effectively.
Used pie charts and bar graphs for categorical data distributions.
3. Strategy Analysis:
Focused on specific strategic analyses to derive actionable insights:
Evaluated team win rates across different venues.
Identified key players contributing to consistent team success.
4. Key Insights:
Summarized significant findings from the visualizations, including trends, patterns, and relationships.
Highlighted unusual patterns and actionable insights, such as:
Key players and venue-specific team strategies.

## Visualisations
<a href="
<a href="https://github.com/santosh7569/Extensive-Eda-on-IPL-Data/blob/main/visualisations.pdf"<a/>



## Key Insights 
1. Team Performance:
Mumbai Indians, Chennai Super Kings, and Kolkata Knight Riders have won the most games, with Mumbai Indians leading the charts, achieving over 30,000 victories.
2. Player Performance:
The best player across all seasons is Virat Kohli, followed by Shikhar Dhawan and Rohit Sharma.
Brendon McCullum consistently delivered with the best average, frequently hitting boundaries and scoring runs.
Badoni emerged as a standout performer in 2023 and 2024, recovering form from 2022.
Ashish Reddy excelled in 2012 and 2013, faced a dip in 2014, and made a strong comeback in 2015 and 2016.
Chopra started strong in 2007 but experienced a performance drop in subsequent seasons.
Flintoff was the best performer in 2009.
Kumble showed early promise during the first three seasons but was underwhelming later.
Manohar had a slow start but delivered significant performances between 2022 and 2023.
3. Match Outcomes:
On average, teams win by margins of 0 to 20 runs, but there are frequent instances of larger margins exceeding 40 runs, with some as high as 140 runs.
The average target score is between 150 to 200 runs, though scores below 100 and above 250 have been observed.
Matches are typically played over 20 overs, but certain conditions have led to reductions, with matches played in as few as 5 overs or, in rare cases, canceled entirely.
4. Batting and Bowling Trends:
Batsmen predominantly scored 1s and 2s, with occasional boundaries.
Dot balls and singles were common, alongside occasional 3s, 4s, and even 5s.
Some rare instances recorded total runs scored in a single ball fluctuating between 3 to 76 runs.
Bowlers occasionally gave extras, including 1s, 2s, 3s, 4s, 5s, and 7s.
Overs had an average of 4 valid deliveries, with anomalies where more than 8 balls were bowled.
5. Strategy Analysis:
Matches with targets between 150-200 runs often resulted in close contests, with result margins typically below 40 runs.
Higher targets (above 200 runs) led to more frequent large-margin victories, whereas modest targets (below 150 runs) resulted in competitive matches with smaller margins.
6. Actionable Insights:
Setting a target of 150-200 runs provides a competitive edge, leading to close and engaging matches.
Teams defending high targets (above 200 runs) have a greater chance of securing significant victories, indicating the importance of setting high scores.

