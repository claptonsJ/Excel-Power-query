# Car-Inventory-Analysis

## Table of Contents
- [INTRODUCTION](#INTRODUCTION)
- [PROJECT DESCRIPTION](#PROJECT-DESCRIPTION)
- [PROBLEM DEFINITION](#DEFINING-THE-PROBLEM)
- [METHODOLOGY](#METHODOLOGY)
- [INSIGHTS](#INSIGHTS)
- [RECOMMENDATIONS](#RECOMMENDATIONS)

# INTRODUCTION
In this project, You will gain hand-on experience with extracting, transforming, and loading text (.txt) file in excel using the modern data analysis feature like the power query (Get & Transform Data). The raw and uncleaned data file is attached in this repository as a .txt file and also the cleaned dataset as .xlsx file.

# PROJECT DESCRIPTION
Project Title: Data cleaning and analysis.
Company name: Jo autos Ltd.
Objejctive: To clean and transform data for analysis and recommendations.

# PROBLEM DEFINITION
Jo autos Ltd. has a limited information about the cars in their inventory dataset. They needed to see clearly the Make, Model, Manufature year, Age, Miles/year, cars that are still covered by their warranty, and also assign new car IDs to each car contained in their inventory database. They also further want to prove or disprove the hypothesis that the higher the age of cars, the higher the miles driven and lastly, to figure out the top drivers in the company.

# METHODOLOGY
The raw dataset gotten from client contains colums like "Car ID", "Miles", "Warranty miles", "Color", and "Driver". This dataset was cleaned and transformed using Microsoft Excel's power query.
- The make of the cars were extracted from the "Car ID" column and also converted to their full names.
- The model was extracted from the "Car ID" column and also converted to their full names.
- The manufacture year was extracted from the "Car ID" column and was subtracted from the current year to derive the "Age" column.
- The "Miles/year" was derived by dividing the "Miles" column by the "Age" column.
- The "Warranty covered?" was derived by applying conditional statements for cars that were below or equal to the warranty miles.
- The new car IDs were derived by including the color of vehicle to the already existing car IDs.
- The hypothesis was proven using a scatter chart to visualize the relationship between the age of cars and miles driven.
- The association of the drivers and miles was visualized using a bar chart.

# INSIGHTS
- The hypothesis was proven that as the car ages, the miles increases.
- Smith emerged as the driver with the most miles driven due to the fact that he has driven a total of 6 cars compared to the rest of the drivers who drove 3 cars each except for one who drove just 1 car from YTD.

# RECOMMENDATIONS
- Cars that are aging with relatively higher miles can be auctioned to prevent incurring huge maintenance costs in future.
