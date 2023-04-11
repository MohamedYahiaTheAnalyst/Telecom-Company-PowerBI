# Telecom Company PowerBI Dashboard
The goal of the project is to create powerBI dashboard for the Budget Manager. This dashboard will help him overview and prepare 2023 budget. To achieve this goal, this dashboard will enable the manager to:  
- Compare 2022 Budget, 2022 Actual, and 2023 Budget.
- Slice charts based on business units(home and business costomers)
- Slice charts based on quarters.
- Slice charts based on revenues and costs type.
To achieve this goal I went throug the following steps.

## 1st. Step: Transforming the data
Data was unprepared. It was in one tall table.I used power query editor to transfomr the data by appling the following steps:
- Split the tall table into fact and dim tables.
- Change data types.
- Create calcuated colmons.

## 2sd. Step: Building the data model.
After transforming the data, we have three fact tabels:
- Revenues
- Costs
- Customer base

and for dimintional tables:
- Quarters
- Business Units
- Types
- Budgets

I created the required relationships in the model view. The data model is as the following pic.



![alt text](https://github.com/MohamedYahiaTheAnalyst/Telecom-Company-PowerBI/blob/main/Data%20Model.jpg?raw=true)

## 3rd. Step: Creating measures
I used DAX to calculate important values as cost variance, revenue variance and customer base variance.
I groubed all measres in seprite table.

## 4th. Stpe: Creating the dashboard
The final design is in the following image

![alt text](https://github.com/MohamedYahiaTheAnalyst/Telecom-Company-PowerBI/blob/main/Final%20dashboard.jpg?raw=true)




