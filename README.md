# bikesharing

## Project Overview
The purpose of this analysis was to demonstrate that there's a market for bike sharing by analying CitiBike bike data from NY. Through analyzing the data and presenting it in Tableau, a visual story can be shown to help provide visual context for the data.

## Resources
- Data Source: 201908-citibike-tripdata-dt.csv 
- Software: Visual Studio, Jupyter Notebook, Tableau
- Files: pngs/

## Challenge Overview
Three deliverables:
- Deliverable 1: Change Trip Duration to a Datetime Format
- Deliverable 2: Create Visualizations for the Trip Analysis
- Deliverable 3: Create a Story and Report for the Final Presentation


## Results

### Deliverable 1: Change Trip Duration to a Datetime Format
The trip duration needed to be changed from an integar to a datetime format. The following python code provided the needed conversion:

[## Convert the 'tripduration' column to datetime datatype.
citibike_data_df['tripduration'] = pd.to_datetime(citibike_data_df['tripduration'], unit='s')]



### Deliverable 2: Create Visualizations for the Trip Analysis

To view my story on Tableau Public
[link to dashboard](https://public.tableau.com/app/profile/sharon.dieckert/viz/CitibikeChallenge_16584540182340/Story1?publish=yes)

<tv1>
Shows the number of Citibike users broken out by Usertype. The chart is moved to a box chart so it fit at the top of the dashboard and can used to filter on the page.

<tv2>
Shows the Top 3 Stations by the Start Hour. Identifies the stations with the most customers and at the time of day.

<tv3>
Shows the Top 3 Stations by the End Hour. Identifies the stations with the most customers and during the time of day.

<tv4>
Provides a map showing the areas of Manhatten that receive the most bike usage as the starting locations. 

<tv5>
Provides a map showing the areas of Manhatten that receive the most bike usage as the ending locations. 

<tv6>
Breaks down the duration of the bike rides into hours. Most rides are under an hour.

<tv7>
Breaks down the duration of the bike rides into hours and by gender. Men and women average about the same amount of time but there are more male bikers.

<tv8>
Breaks down the trips by the start hour and day of the week. Most rides are occurring during the work week in the morning and after work. On the weekends, bike usage starts later in the day which would align with tourist and siteseeing. 

<tv9>
Breaks down the trips by the start hour and day of the week and by gender. Time of usage follows the same pattern but with more male bikers. 

<tv10>
Breaks down weekday but gender and user type. Customers are more balanced between genders and subscribers show more males.



### Deliverable 3: Create a Story and Report for the Final Presentation

[link to dashboard](https://public.tableau.com/app/profile/sharon.dieckert/viz/CitibikeChallenge_16584540182340/Story1?publish=yes)


Through analyzing the data, it appears that not only is there a market for providing bikes to tourists, but that city commuters also provide a viable market and only use the bikes for short distances and during peak rush hours. These bikers tend to be subscribers and male.

<summary1>

The heat map shows bike usage by usertype and stoptime. With the majority of points showing in the morning rush hour and evening commute home, it shows that the majority of subscribers are utilizing the service for work commuting. 

<summary2>
The graph show that the majority of subscribers are taking short trips with the majority under twenty minutes.