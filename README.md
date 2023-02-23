# Bikesharing Proposal
## Overview
Citi Bike is a Bike-sharing service in New York which allows people to commute around The Big Apple. This repository was created to create a proposal for a Bike-sharing service in Iowa.

The purpose of this analysis is to understand how Citi Bike works and how this can be implemented in a similar service. Using Tableau, relevant information on the operation of Citi Bike will be displayed.

## Results
The analysis used data from Citi bike from August 2019, this process was divided in two main sections. This with the objective of transforming the data and preparing it for the visualizations.

### Data Transformation
The first part of the analysis allowed the transformation of the 'tripduration' column to date_time format using Jupyter Notebook. This with the purpose of facilitating the use of the data for the visualization.

### Data Visualization 
The second part of the analysis helped to create visualization of data that answered questions to structure the proposal.

#### Number of Rides and Average Duration of the Rides
In the month of August 2019 Citi Bike Bike-sharing service had 2,344,244 users as shown in Figure 1. In Figure 2 we can se that almost all the rides lasted less than an hour having the highest peak of rides on the mark of 5 minutes for 146,752 rides.

<img width="233" alt="Captura de pantalla 2023-02-22 a la(s) 17 14 58" src="https://user-images.githubusercontent.com/93279134/220785011-f58c4c80-e10c-422c-84b4-4311f8dde63c.png">
Figure 1. Number of Rides.

<img width="972" alt="Captura de pantalla 2023-02-22 a la(s) 17 17 25" src="https://user-images.githubusercontent.com/93279134/220785313-fc9fe0d1-521f-4c17-9116-b34ea42eb931.png">
Figure 2. Checkout Times for User.

It's also important to say that mostly all the users are males with 1,530,272 users, female users are 588,431, and the unknown users are 225,521. This information it's displayed in Figure 3. The duration of rides also depend on the user gender, this data is displayed in Figure 4. 

<img width="199" alt="Captura de pantalla 2023-02-22 a la(s) 17 27 50" src="https://user-images.githubusercontent.com/93279134/220786679-87dbc247-36cb-4a81-a8ad-31a7f76fb5c8.png">
Figure 3. Gender Breakdown.

<img width="979" alt="Captura de pantalla 2023-02-22 a la(s) 17 30 02" src="https://user-images.githubusercontent.com/93279134/220787022-cbfa6de3-c1b3-4605-a70e-3314b2611530.png">
Figure 4. Checkout by Genders.

#### Usage Trend by Day and Time
The most use of the Bike-sharing service is carried out on weekdays specifically in two ranges of hours, between 7 am and 9 am, as well as between 5 pm and 7 pm. On weekends, the use of the service is higher between 10 am and 7 pm. This data is shown in Figure 5.

<img width="1001" alt="Captura de pantalla 2023-02-22 a la(s) 17 42 20" src="https://user-images.githubusercontent.com/93279134/220788700-f7db12ac-666b-4930-a6db-3f5e24d2f78f.png">
Figure 5. Trips by Weekday per Hour.

The busiest days and hours for the service also depends on the gender of the users. In the Figures 6 and 7, we can see that the previous trend it's kept, but it's distributed between the genders.

<img width="997" alt="Captura de pantalla 2023-02-22 a la(s) 17 56 03" src="https://user-images.githubusercontent.com/93279134/220790884-6d52260f-eb94-4f04-8736-29ecb273b9a3.png">Figure 6. User Trips by Gender by Weekday.


![Captura de pantalla 2023-02-22 a la(s) 17 56 50](https://user-images.githubusercontent.com/93279134/220790984-a0ba6ce1-079b-4146-b3f5-6e50b8e21aa1.png)
Figure 7. Trips By Gender.

#### Location of the Bikes
Using Figures 8 and 9, the location of the bikes can be seen, this is important because we know where the majority of the trips starts and ends. This is helpful because knowing the concentration of bikes per zone could help us to set mainteinence calendars and also to know where more bikes are needed. 

![Captura de pantalla 2023-02-22 a la(s) 18 03 46](https://user-images.githubusercontent.com/93279134/220791826-bf9ad1fb-463d-457f-95df-26ead15654c2.png)
Figure 8. Top Starting Location.

![Captura de pantalla 2023-02-22 a la(s) 18 04 14](https://user-images.githubusercontent.com/93279134/220791879-e04422d4-ad1e-4430-be55-6b86fc01e47a.png)
Figure 9. Top Ending Location.

## Summary
Once the analysis was finished, we get to know the top locations od the service and the busiest hours. A population density analysis should be perform in Iowa, so we could get to know the more crowded places, where the service could be tapped the most. Also, it's important to realize that most of the users are males, so it would be important to create campigns to attract female users.

### Suggested Visualizations
 - Location of the users by age: This could be helpful to create programs or offers to attract users of different segments. This could lead to increasing the amount of suscribed users.
 - Suscription based on aged: Create a visualization that differentiates age ranges and if the users are suscribed. This could lead to the creation of campaings to make those unsuscribed segments to suscribe to the service.

## Tableau Link
Tableau story can be find in the following link:
[link to dashboard](https://public.tableau.com/app/profile/alberto.quiroz/viz/Challenge_15_16771046352740/Historia1)
