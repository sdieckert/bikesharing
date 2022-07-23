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
[Link to Citibike Dashboard](https://public.tableau.com/app/profile/sharon.dieckert/viz/CitibikeChallenge_16584540182340/Story1?publish=yes)


Overview of the widgets in the story:

![tv1](https://user-images.githubusercontent.com/87085239/180588943-c5046e93-918d-417e-bbdf-73bc1efd03b5.png)

Shows the number of Citibike users broken out by Usertype. The chart is moved to a box chart so it fit at the top of the dashboard and can used to filter on the page.

![tv2](https://user-images.githubusercontent.com/87085239/180588950-1e139d53-02e9-4554-a4ad-32afa2a21fff.png)

Shows the Top 3 Stations by the Start Hour. Identifies the stations with the most customers and at the time of day.

![tv3](https://user-images.githubusercontent.com/87085239/180588965-7807a177-2d39-4599-a5cc-5920dc43ce40.png)

Shows the Top 3 Stations by the End Hour. Identifies the stations with the most customers and during the time of day.

![tv4](https://user-images.githubusercontent.com/87085239/180588971-efdbad2e-a6c9-496e-bb5e-b8933686fd51.png)

Provides a map showing the areas of Manhatten that receive the most bike usage as the starting locations. 

![tv5](https://user-images.githubusercontent.com/87085239/180588981-864f878b-5642-4991-9cad-7954ef913cd1.png)

Provides a map showing the areas of Manhatten that receive the most bike usage as the ending locations. 

![tv6](https://user-images.githubusercontent.com/87085239/180588985-a53afd93-9a70-4b0f-b429-cd3953adc9ae.png)

Breaks down the duration of the bike rides into hours. Most rides are under an hour.

![tv7](https://user-images.githubusercontent.com/87085239/180588997-652bd8b0-bf3d-40bf-a058-49cbac4e486a.png)

Breaks down the duration of the bike rides into hours and by gender. Men and women average about the same amount of time but there are more male bikers.

![tv8](https://user-images.githubusercontent.com/87085239/180589002-846b3cef-3f04-4d65-9824-d7ca99c4044c.png)

Breaks down the trips by the start hour and day of the week. Most rides are occurring during the work week in the morning and after work. On the weekends, bike usage starts later in the day which would align with tourist and siteseeing. 

![tv9](https://user-images.githubusercontent.com/87085239/180589012-f8aced02-8b03-4812-a39b-1681dccbb2fd.png)

Breaks down the trips by the start hour and day of the week and by gender. Time of usage follows the same pattern but with more male bikers. 

![tv10](https://user-images.githubusercontent.com/87085239/180589018-ff1b46f5-71db-4160-8f1b-92f4b89f3d79.png)

Breaks down weekday but gender and user type. Customers are more balanced between genders and subscribers show more males.

### Deliverable 3: Create a Story and Report for the Final Presentation

[Link to Citibike Dashboard](https://public.tableau.com/app/profile/sharon.dieckert/viz/CitibikeChallenge_16584540182340/Story1?publish=yes)

## Summary

Through analyzing the data, it appears that not only is there a market for providing bikes to tourists, but that city commuters also provide a viable market and only use the bikes for short distances and during peak rush hours. These bikers tend to be subscribers and male.

![Summary1](https://user-images.githubusercontent.com/87085239/180589025-93ad8eb8-9cc1-438b-ab78-e5878c743582.png)

The heat map shows bike usage by usertype and stoptime. With the majority of points showing in the morning rush hour and evening commute home, it shows that the majority of subscribers are utilizing the service for work commuting. 

![Summary2](https://user-images.githubusercontent.com/87085239/180589036-47e1fa18-7de9-46ab-90ee-4d2e574a4573.png)

The graph show that the majority of subscribers are taking short trips with the majority under twenty minutes.
