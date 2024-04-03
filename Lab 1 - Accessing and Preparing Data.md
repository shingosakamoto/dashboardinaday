# Lab 1 - Accessing and Preparing Data

## 1.Intro
We’ll start at the beginning, by using the Power BI Desktop Query Editor to ingest data from various data sources. We won’t use them all, but we’ll start the day by showing how we can ingest data from multiple disparate sources and combine them into a single data model.
1. If you don’t already have the Power BI Desktop open, launch it now.

## 2.Accessing Data
In this section, you will import VanArsdel’s and its competitors’ USA sales data. You will then import and 
merge sales data from other countries.

### 2.1.Get Data
With Power BI Desktop installed, you're ready to connect to the ever-expanding world of data. To see the many types of data sources available, select Get Data > More in the Power BI Desktop Home tab, and in the Get Data window, scroll through the list of All data sources.

We are using CSV and Excel data files in this lab for simplicity. If you would like a full list of data sources, 
please visit this link: https://docs.microsoft.com/en-us/power-bi/connect-data/desktop-data-sources
Start by loading USA Sales data, which is in a CSV file.

USA sales data is in a CSV file located in the Usages subfolder within the Data folder (/Data/USSales).

Sales of all other countries is in the InternationalSales subfolder within the Data folder
(/Data/InternationalSales). Each country’s sales data is in a CSV file in this folder.

Product, Geography, and Manufacturer information is in a Microsoft Excel file called bi_dimensions.xlsx in 
the USSales subfolder within the Data folder (/Data/USSales/).

1. From the ribbon at the top of the screen, select the Home tab. Then, choose the Get Data drop-down
