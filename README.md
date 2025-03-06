# BlinkIT Dashboard
Dashboard Link : https://app.powerbi.com/groups/me/reports/f9de5397-0aeb-4bde-82db-cb365d5b330b/840af57e6be72951c5c2?experience=power-bi

## Problem Statement

This dashboard helps the customers to understand their Sales performance better. It helps the customers know theirs item details and outlet details are satisfied with their services. Through different ratings, they get to know their improvement area, & thus they can improve their services by identifying these area. It also lets them know the average rating,average sales and total sales thus since by using this dashboard they have identified this problem, they can further work on factors responsible.

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present in Item weight
- Step 5 : For calculating average sales, null values were not taken into account as only less than 1% values are null in this column(i.e column named "Item Weight") 
- Step 6 : In the report view, under the insert tab, using shapes option from elements group a rectangle was inserted & similarly using some formatting Company Name was added to the report design area. 
- Step 7 : Since the data contains various ratings and sales details, thus in order to represent, a multi-row card visual was added in the visualizations pane in report view. 
- Step 8 : Visual filters (Slicers) were added for three fields named "Outlet Location Type", "Outlet Size", "Item Type".
- Step 9 : Multi Row card visuals were added to the canvas, one representing "Total Sales","Average Sales","No of Items" & "Average Rating"
          -----Using Field Parameters----- which consists of "Total Sales","Average Sales","No of Items" & "Average Rating" is created. Named "Metrics" is added to the report.That "Metrics"(i.e;Field parameter) has been added as a slicer in the report. Which helps in filtering three charts."Fat Content","Fat by Outlet","Item Type".
- Step 10 : A donut chart was also added to the report design area representing  "Fat Content" also added to the report design area representing the "Fat Content". While creating this visual, field named "Item Fat Content" was added to the visual, thus Fat Content are also seggregated according the "Metrics". 

- Step 11 :  A clustered bar chart was also added to the report design area representing the Outlet location type and Item fat content based on Metrics.

- Step 12 :  A stacked bar chart was also added to the report design area representing the Item type based on Metrics.

- Step 13 : A line chart was also added to the report design area representing the "Outlet establishment year" and its total sales was added to the report design area. While creating this visual, field named "Total sales" was added to the visual, thus sales are seggregated accordingly.

- Step 14 : A donut chart was also added to the report design area representing the "Outlet size" and its total sales was added to the report design area. While creating this visual, field named "Total sales" was added to the visual, thus sales are seggregated accordingly.

- Step 15 : A Funnel chart was also added to the report design area representing the "Outlet location type" and its sales was added to the report design area. While creating this visual, field named "Sales" was added to the visual, thus sales are seggregated accordingly.

- Step 16 : A Matrix visualization was also added to the report design area representing the "Total Sales","Average Sales","No of Items","Average Rating","Outlet Type" & "Item Visibility"

- Step 17 : A image is added under the slicers "Reset Filters" option to reset all the filters applied to the report.

 
- Step 18 : The report was then published to Power BI Service.
 

# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.


![image](https://github.com/user-attachments/assets/c5f9a23e-9285-423b-bd18-cd50a06dd651)

