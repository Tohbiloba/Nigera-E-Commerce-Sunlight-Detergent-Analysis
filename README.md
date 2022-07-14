# Project Objective
1. To find out the sales trend of the product across 4 months
2. To find out which branch is bringing in more revenue
3. To find out states where the product has coverage and how to improve on the coverage
4. To find out the rate of anomalies in the order for the product 

Data Source
The data was sourced from Kaggle. 

![image](https://user-images.githubusercontent.com/101842162/179009577-37b23ee5-0385-4e50-b53d-717ca9dcf824.png)

Data Preparation
The data comprises of 3498 rows and 16 column. The column names includes Order ID, Branch Location, Branch Name, Business Name, Is Deleted, Item ID, Item Name, Item Price, Order Item Number, Item Status, Packed Quantity, Quantity, Total Price, Order Date, Order Region and Order Local Area.

![image](https://user-images.githubusercontent.com/101842162/179009824-98cc3848-6205-4b74-b90c-735091fd115a.png)

The empty cells in the Order region column were filled with the corresponding Order Local Area.

![image](https://user-images.githubusercontent.com/101842162/179010374-296acec8-7de3-4f88-aa10-9308a2ad696b.png)

Some of the cleaning process carried out include using the Replace Function to replace Sunlight Destiny Powder Yellow-900g with Sunlight Destiny Powder Yellow 900g so as to have a unique data.

Data Analysis 
The Analysis and Visualisation were carried out in Power BI.The use of DAX measures such as the Calculate and a calculated column was also created. 

Data Visualisation
In the dashboard created Cards were used to visualize some of the values gotten via the measures created; KPIs.

![image](https://user-images.githubusercontent.com/101842162/179012392-452971c2-c330-4b8e-8e09-7f2500060f8f.png)

Funnel Chart was used to visualize the Order by Region by this identifying the region where more orders come in from. The Month and Location slicers can be used to find out the amount of order coming in from the different regions per month and the Location.

![image](https://user-images.githubusercontent.com/101842162/179012639-e38948f0-b1d7-4715-b704-bcc2bb3037b9.png)

Area Chart was used to visualize the trend of sales across the 4 months recorded. From the visual, there is an increase in the sales from the month of February but the drop in sales in May is also worthy of note.

![image](https://user-images.githubusercontent.com/101842162/179012843-df977f61-48c8-45ca-94d6-2812aaf5dce3.png)

Donut Chart was used to visualise the Status of the sales i.e. Delivered, Cancelled or Invalid. This shows that the Delivered order has a larger percentage. This can be further simplified using the Month and Branch location Slicer to find out the status of order across a particular time and location.

![image](https://user-images.githubusercontent.com/101842162/179013078-74eed384-24c9-4842-b40b-0a54b6373a29.png)

Stacked Bar Chart was used to visualize the sales recorded by the Branches. This is to find out what Branch is bringing in more sales than the other. The Month and Location Slicer will further clarify what Month and Region each Branch makes more sales.

Dashboard

![image](https://user-images.githubusercontent.com/101842162/179013521-3e81755a-e538-45fa-bc7c-8b86f9d23582.png)
