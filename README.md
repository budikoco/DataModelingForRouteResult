# DATA SCIENCE MODELING IN EVALUATING AIRLINE ROUTE PROFITABILITY

Indonesian airlines were into turbulance situation due to the spread of COVID-19 since March 2020. The positive route result dropped significantly. Government’s policy to implement PSBB and PPKM urged the airline to be agile with the current situation immediately to maintain business continuity. 

Data science will drive the airline in finding the significant factors which could lead in maintaining profitability route

# Objective:
This project is to find the essential features or aspect which had a high relationship to route result, so the airline could focus in managing that features to avoid route result.

# Feature Data-Column:
1. Period : the month of flight scheduled
2. Service Type : Domestic / International Flight
3. Departure Airport 
4. Arrival Airport
5. Number of Transit : the number of transit location for this flight
6. Passenger Revenue Nett : the revenue from passenger stream business 
7. Freight Revenue Nett : the revenue from freight stream business
8. Mail Revenue : the revenue from mail stream business
9. Other Revenue : the ancillary revenue
10. Total Direct Costs : the cost from direct flight operation
11. Total Indirect Costs : the cost from indirect flight operation
12. Total Fleet Cost : the cost of aircraft rental
13. Total Branch Office Cost : the cost occoured on branch office
14. Administration Head Office : the cost occored on head office
15. Flight Routes : the flight route (destination to arrival airport)
16. Number of Landing : the number of landing happened 
17. Block Hours : how long the aircraft arrive in parking area until the aircraft take off
18. Flight Hours : how long the aircraft airborne 
19. Flight Kilometers : measurement of flight distance 
20. Fuel Burn : the number of fuel use 
21. Seat Offered : the number of offered seat 
22. Passenger Carried : the number of passenger carried
23. SLF : the seat load factor, the percentage of booked seat to offered seat.
24. Freight Carried : the number of freight carried
25. Mail Carried : the number of mail carried 
26. Aircraft Type : the aircraft type us

# Supported Application:
Because this file is .ipynb you need to install Google Colaboration/Jupyter Notebook. You should Mount Drive to connect the Google Colaboration into your Google Drive and place the csv file into a folder

# Step
1. Data Preprocessing : handle missing value, data duplicate, label encoding, scalling, multicollinear features
2. Conducted Ridge Regression
3. Conducted Lasso Regression
4. Conducted Random Forest Regression
5. Conducted XG Boost Regression

# Summary
1. There were 7633 clean data that can lead the airline to find the significant factor where the airline could focus on building quick-win initiatives to reduce negative route results. 
2. Data modeling will use Ridge Regression, Lasso Regression, Random Forest Regression, and XG Boost Regression to find the best model.
3. Finding the essential features which had a high relationship to route result using Random Forest Regression gave the optimum result because this model could provide the strength relationship at 98.14%, with the absolute difference between the predicted and the actual values of only 0.09 points.

![image](https://user-images.githubusercontent.com/99941081/179911466-f3a3563e-f3a6-4b0b-b299-453f90f40130.png)

4. The top 5 features that have a high coefficient to route result (based on Random Forest Regression modeling) are total branch office cost, total indirect cost, seat load factor, flight route, and other revenue. 

![image](https://user-images.githubusercontent.com/99941081/179911536-27d2e06a-86b2-47cd-9770-37f7d6329f63.png)

5. The airline could focus on that features (20%) to have an 80% impact on route results. 





