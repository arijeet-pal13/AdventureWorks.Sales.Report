# AdventureWorks Sales Report
### Microsoft Power BI
* Power BI is a business analytics service by Microsoft.
* It aims to provide interactive visualizations and business intelligence capabilities with an interface simple enough for end users to create their own reports and dashboards.

### Extract, Tranform & Load Data
To add a data source, go to the Get data option. Then, select the data source you want to connect and click the Connect button.
Connect to following data from the Dataset file.
* AdventureWorks_Calendar.csv
* AdventureWorks_Customers.csv
* AdventureWorks_Product_Categories.csv
* AdventureWorks_Product_Subcategories.csv
* AdventureWorks_Products.csv
* AdventureWorks_Returns.csv
* AdventureWorks_Territories.csv
* AdventureWorks_Sales_2015.csv
* AdventureWorks_Sales_2016.csv
* AdventureWorks_Sales_2015.csv

In Power Query Editor Transform and Clean all the data as needed then Load the data in Power BI.

### Data Model

In the Relationship tab, you can see the relationship between data sources. When you add multiple data sources to Power BI visualization, the tool automatically tries to detect the relationship between the columns. When you navigate to the Relationship tab, you can view the relationship. You can also create a Relationship between the columns using Create Relationships option.

Here the relationship between tables is called 'Star Schema'. Star schema is a mature modeling approach widely adopted by relational data warehouses. It is classified into fact table & dimension tables. In this model Sales and Return table are fact tables. Others table are dimension table.
![image](https://github.com/arijeet-pal13/AdventureWorks.Sales.Report/assets/84266230/0c0a4ea7-8330-4c3f-a80b-125fdcf9bc12)



### Creating Reports

* This page represent Total orders , Return orders , Revenue by Products, Category,Subcategory and Location.

![image](https://github.com/arijeet-pal13/AdventureWorks.Sales.Report/assets/84266230/c3364905-4c82-407d-b872-37e591483073)

![image](https://github.com/arijeet-pal13/AdventureWorks.Sales.Report/assets/84266230/402588bb-c125-4790-b84c-cf2c2e62e617)


* This page represent Customers Information.

![image](https://github.com/arijeet-pal13/AdventureWorks.Sales.Report/assets/84266230/c0725c5f-1386-4b85-b988-0f00d7861631)

