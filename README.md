# Covid Cases Dashboard



## Problem Statement

This dashboard helps us to understand how the deadly disease that shook the world effected countries across the world. And how the infection spread in various countries and how many people could not make it. This dashboard was made in tableau where I imported data by connecting my sql server through Microsoft SQL server Management studio


### Steps followed 

- Step 1 : Create views in Microsot SQL Server as per the   requirements for the dashboard.
- Step 2 : Load data into Tableau desktop through sql server. 
- Step 3 : Create 4 sheets for the 4 views to be made in the dashboard 
- Step 4 : Create first view with Total cases, Total deaths and Death percentage and make simple table with 1 row and 3 columns.Then customize the table features to your liking and change the decimal value  to make it more accurate.
![view1](https://github.com/rahulshivanshbagwar/Tableau_Covid-Project/assets/173008519/6b784599-fffe-4c2d-ad18-c6a13aef17cc)
- Step 5 : Create the second view with location renamed as continent in the columns and total death count in the rows and make a simple bar chart.Custom sort the continent values to make the data clearly visible
![view2](https://github.com/rahulshivanshbagwar/Tableau_Covid-Project/assets/173008519/6d2e258a-9a7a-4146-a09f-730c3d47cabf)
- Step 6 : In the Third view, in order to create the view first change the geographic role of the location to country/region. then it is observed that to additional data attributes are created namely 'longitude(generated)' amd latitude '(generated)'.Drag Longitude to the columns and Latitude to the rows and it is observed that a map is automatically generated. Darg the location and percentage population infected to the marks and customize the map to your liking.
![view3](https://github.com/rahulshivanshbagwar/Tableau_Covid-Project/assets/173008519/b9ac3143-5965-4762-bc80-4bd8483f51db)

- Step 7 : In view 4 drag the location to columns and Percentage population infected to the rows and location to the marks section and create a custom filter to select the countries to be shown, in this project United Kingdom, United States, Mexico, Africa, India, Australia and Canada were selected.Selectr the location tab in marks and chane the colours to a suitable colour gradient for the values Drag the location and total percentage infected to marks and convert both of them to labels.All the zero values are ignored in all the views and calculation. 
![view4](https://github.com/rahulshivanshbagwar/Tableau_Covid-Project/assets/173008519/d833a804-930f-441f-a86d-0fcd071eb686)

- Step 8 : Now since all the necessary views are created make a dashboard by inserting the views and properly sizing them such that the data is clearly visble and is undertood. 
![dashboard](https://github.com/rahulshivanshbagwar/Tableau_Covid-Project/assets/173008519/e56935e1-17fa-42c4-9b50-2dc614be0dcf)

# Insights

A Dashboard was created in tableau from the data imported from sql server.

Following inferences can be drawn from the dashboard;

### [1] Global Death Percentage till 2024= 0.91%

   Total Number of Cases = 775,619,628

   Total Number of Deaths = 7,054,044

  


           
           
### [2] Europe Continent has the Highest Death rate.

    Europe = 2100613 deaths
    North America = 1666760 deaths
    Asia = 1637164 deaths
    South America = 1357630 deaths
    Africa =	259105 deaths
    Oceania = 32767 deaths
   
  
  ### [3] Visual Overview of the concentration of cases worldwide 
  

 ### [4] Among the major countries selected Australia had the most cases and Africa had the least
 
