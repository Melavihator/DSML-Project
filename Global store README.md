# DSML-Project
 Gloabal Super Store Sales Analysis


### Dashboard Link : https://drive.google.com/file/d/1CZkLBRxIsmmFHflcSUALv-vq74qN-jCE/view?usp=drive_link

## Problem Statement

This dashboard helps to understand their customers,market trends,better sales region and which country have the good market for, better. It helps the sales know if their customers are satisfied with their services and products. Through different sales count, they get to know their improvement area, & thus they can improve their services by identifying these area. 

Since,with these numbers,makes easy to identify satisfied customers with the increase in the sales and profit rating.

Also from this, using the dashboard we can formulate the effective practices can adopt to increase the sales in the region were sales are in less in count


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "Order table", "people tables" & "market tables" and their respective columns unanimously.
- Step 3 : As part of cleaning the data set columns having null values and exceptional values are encountered have been removed from the data set ".
- Step 4 :Clearly checked if many more cleaning process should be taken care of.
- Step 5 : Create relations with the 3 tables, in which tables with similar names or similar datas are formulated in such to establish effectively 
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 7 : formulated baisic data visualisation strategy  in the visualizations pane in report view. 
- Step 8 : Segment the visuals using country, region, market in first page with maps. 3 maps are created with count of sales in values aganist Market,Region,Country.

- Map-1:
- ![Screenshot (430)](https://github.com/user-attachments/assets/8f6a4ae2-a952-44d7-a810-d5e199d0f22d)
- Map-2:
- ![Screenshot (434)](https://github.com/user-attachments/assets/2fe8286e-4568-413a-8706-5bbafd6f7d10)
- Map-3:
-  ![Screenshot (435)](https://github.com/user-attachments/assets/55aa592c-ec78-41d2-b0e5-0c62a435c2ec)


- Step 9 : Analyze the data by visualizing the percentage of shipping based on ship mode.Pie Chart is used to plot the Ship Mode Percentage From the shipping modes.
        Using visual we can come across the share of each shipping modes in the salesd calculation.
        Although, by default, while calculating Percentage, blank values are ignored.

- Chart-1:
-  ![Screenshot (431)](https://github.com/user-attachments/assets/b87c37e0-fe76-4d66-8697-8e7cebb1e747)

- Step 10 : Give the report to see sales over the city, states, region and market
        It prefer to show sepreately the sales in state(city and sales) wise regions and the perticular sales in the regions and to which market does the regions belongs to and a common donut chart to show the total sales in regards of the cities

- Chart-Map showing cities in sales:
- ![Screenshot (436)](https://github.com/user-attachments/assets/7e3b397c-edcc-4198-8ea8-386afede2beb)

- Donut chart of sum of sales by cities in regard of slicers in which region and states are mentioned:
- ![Screenshot (437)](https://github.com/user-attachments/assets/6ecb6dad-bcab-4b16-96a8-eac84ea4a87d)
- Bar cahrt and slicers based on region and state:
- ![Screenshot (438)](https://github.com/user-attachments/assets/d79d2b1a-fc9e-421c-897d-06990985bff7)
 
- Step 11 : Create tables for all the visualizations.
- Table 1:
- ![Screenshot (439)](https://github.com/user-attachments/assets/06554b5f-2cee-4bd3-9835-850905ea8487)
- Table 2:
- ![Screenshot (440)](https://github.com/user-attachments/assets/f3da2285-b7f0-4b1e-a32e-4b7f7ff3f045)
- Table 3:
- ![Screenshot (441)](https://github.com/user-attachments/assets/3155129e-b60e-4866-b4c2-887833f8d30a)
- Table 4:
- ![Screenshot (442)](https://github.com/user-attachments/assets/1280a425-46f3-46c6-b9d0-2ab1f6baec20)
  
In our dataset, Some parameters were assigned value 0, representing those parameters are not applicable for some customers.

All these values have been ignored while calculatingpercentage and other calculations for each of the parameters mentioned above.


