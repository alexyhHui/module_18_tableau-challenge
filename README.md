# module_18_tableau-challenge
## Instructions
1. Your task in this assignment is to aggregate the data found in the Citi Bike Trip History Logs and find two unexpected phenomena.
2. Use your visualizations (not necessarily all of them) to design a dashboard for each phenomenon. The dashboards should be accompanied by an analysis explaining why the phenomenon may be occurring.
3. Create one of the following visualizations for city officials:

    * Basic: A static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey, with zip code data overlaid on top.

    * Advanced: A dynamic map that shows how each station's popularity changes over time (by month and year). Again, with zip code data overlaid on the map.

    * The map you choose should also be accompanied by a write-up describing any trends that were noticed during your analysis.
4. Create your final presentation:

    * Create a Tableau story that brings together the visualizations, requested maps, and dashboards.

    * Ensure your presentation is professional, logical, and visually appealing.

## Deployment
Please find the visualization of citibike anaylsis with the following link: https://public.tableau.com/app/profile/alex.hui/viz/citibike_2023_17088222319140/Story1

## Data Source
All the data sources are from the [Citi Bike Data](https://citibikenyc.com/system-data) webpage.

The initial step of this project is acquiring the all the monthly CSV files in 2023.

The jupyter notebook `merge_data.ipynb` merged 12 monthly CSV files in one combined CSV file for importing the data to tableau.

Please note that the large size of the CSV files precludes their storage in this repository and in GitHub's Large File Storage.

## Dashboard
### Citibike 2023 Dashboard
This dashboard is the summury of the performance of Citi Bike in 2023. It presents the total trips in 2023, the total number and percentage of user types and the monthly trend of trips and user types.
![image](https://github.com/alexyhHui/module_18_tableau-challenge/assets/147750285/673ca7e3-c459-4141-9850-b6f702897064)
### Top Station Dashboard
This dashboard presents the most popular station to start at or end at. It reveals the total number of stations to start at or end at, top ten popular stations and a treemap to show the total numbers of stations.
![image](https://github.com/alexyhHui/module_18_tableau-challenge/assets/147750285/0f39ce6a-4c45-4ea5-a8a5-fad28e02c38b)
### Weekly Station Dashboard
This dashboard presents the popular weekday and time that people are using Citi Bike.
![image](https://github.com/alexyhHui/module_18_tableau-challenge/assets/147750285/bbd2370c-5f4c-453c-ad32-206fc96c837f)
### Map Station Dashboard
This dashboard presents the distribution of the station to start at or end at across 12 months in 2023.
![image](https://github.com/alexyhHui/module_18_tableau-challenge/assets/147750285/6c76be32-0be9-4ab1-987d-214d7d58937a)
## Written Analysis
### Citibike 2023 Dashboard
The monthly trend in 2023 reveals that most people use Citi Bike between May and August. It may shows that season is one of the factors that affect the number of the users. People prefer riding bicycle in the summer rather than winter.

74% of the users are member which shows that most of the users are loyal customers and willing to utilize the service more than one time.
### Top Station Dashboard
Both the bar charts and the treemaps indicates that Grove St Path, Hoboken Terminal and South Waterfront Walkway are the top three most frequently used stations to start at or end at. It indicates that people living or working nearby are willing to travel by bicycle.
### Weekly Station Dashboard
The bar charts and the heatmaps have reveals the pattern of people using Citi Bike. The peak time of utilizing Citi Bike is weekday during 8 a.m. and 5p.m.. It shows that people are using Citi Bike as their daily commute to travel between work and home.
### Map Station Dashboard
Most of the frequently used stations is near the New Jersey and Jersey City. This shows that people living in New Jersey and Jersey City are willing to use Citi Bike to travel between these two places.
