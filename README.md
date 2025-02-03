# OLA RIDE ANALYSIS DASHBOARD USING POWER BI AND MYSQL

## TABLE OF CONTENT

- [INTRODUCTION](#INTRODUCTION)
- [PROJECT OVERVIEW](#PROJECT-OVERVIEW)
- [RESULTS AND INSIGHTS](#RESULTS-AND-INSIGHTS)
- [CONCLUSION](#CONCLUSION)
  

## INTRODUCTION 

The Ola Ride Analysis Dashboard is a comprehensive business intelligence and SQL-based data analysis project aimed at extracting meaningful insights from ride data. This project leverages Power BI for visualization and MySQL for querying the dataset, providing a detailed understanding of ride trends, cancellations, revenue, and customer-driver interactions.

This analysis helps in identifying key performance indicators (KPIs), evaluating service efficiency, and improving business decisions for ride-hailing services.

## PROJECT OVERVIEW

### 2.1 Tools & Skills Used

- Power BI – Interactive dashboard creation and data visualization.

- Power Query Editor – Data transformation and cleaning.

- DAX (Data Analysis Expressions) – Custom calculations and measures.

- MySQL – Querying and extracting insights from ride data.

### 2.2 Datasets Used

  The dataset consists of ride bookings from July 2024, including:
  
  Ride ID, Date, Booking Status, Vehicle Type ,Total Booking Value, Distance Traveled, Customer & Driver Ratings ,
  Payment Method & Customer Information ,Ride Cancellations by Driver & Customer

### 2.3 Key Objectives

- Analyze booking success rate & cancellations.

- Evaluate vehicle type performance based on bookings and distance traveled.

- Assess customer payment preferences.

- Measure customer and driver ratings across vehicle types.

- Perform SQL-based analysis to answer specific business questions.

## RESULTS AND INSIGHTS

### 3.1 Overall Ride Booking Trends

Total Bookings: 1,03,024  | Total Booking Value: 35M |  Booking Success Rate: 62.09%

Cancellations->   By Driver: 17.89% | By Customer: 10.19% | Driver Not Found: 9.83%

#### Insight:
A significant portion of bookings (36%) gets canceled. Driver cancellations (18%) are higher than customer cancellations (10%), indicating potential driver availability issues.

![OLA 1](https://github.com/user-attachments/assets/72a76700-1108-47db-a9d6-9a4e495d6af8)

### 3.2 Vehicle Type Performance

#### Insight:

- Prime Sedan and Prime Plus generate the highest revenue.

- Auto has the lowest avg. distance (10.04 km), indicating shorter trips.

- E-Bikes have a high average distance (25.15 km), suggesting growing demand for electric rides.

![OLA 2](https://github.com/user-attachments/assets/d24aec4f-996d-469b-9c05-16c63c121b64)


### 3.3 Revenue by Payment Method

Cash: 54.9% | UPI: 40.39% | Credit Card: 3.74% | Debit Card: 2.41%

#### Insight:

- Cash remains the dominant payment mode (55%), but digital payments (UPI + Credit/Debit Cards) are increasing.

- Encouraging digital payments could reduce cash handling issues for drivers.

![OLA 3](https://github.com/user-attachments/assets/2fc9f315-cbe3-443b-8e16-4fd4ea1bb867)

### 3.4 CANCELLATION

#### Cancellation Breakdown

**Customer Cancellations** :

- The most common reason is "Driver is not moving towards the location" (30.24%).

- Other reasons include "Driver asked to cancel," "Change of plans," "AC is not working," and "Wrong address."

**Driver Cancellations** :

- The highest percentage of cancellations by drivers is due to "Personal/Car-related issues" (35.49%).

- Other significant reasons include "Customer-related issues," "Customer was coughing/sick," and "More than the permitted number of people."

![OLA 4](https://github.com/user-attachments/assets/7b7c4756-67af-4d4b-9269-5b2400e2d8ad)


### 3.5 Customer & Driver Ratings

#### Insights:

- Prime Plus vehicles have the high customer & driver ratings (4.01 & 4.00).

- Mini, Bike, and E-Bike have lower ratings, indicating a need for service improvements.

![OLA 5](https://github.com/user-attachments/assets/f2458449-befb-4e2a-92ec-5da09c4aff8f)


## 4. CONCLUSION

  The Ola Ride Analysis Dashboard successfully provides insights into ride trends, cancellations, vehicle performance, payment preferences, and customer-driver ratings.

 Key takeaways include:

- High driver cancellations (18%) highlight a need for better driver engagement.

- Sedans and SUVs generate the highest revenue, but E-Bikes show potential for long-distance travel.

- Cash is still the most used payment method, but digital payments are growing.

- Customer satisfaction is highest for Prime Plus rides, while Auto/Bike rides have scope for improvement.






















