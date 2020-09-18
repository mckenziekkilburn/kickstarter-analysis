
# Kickstarting with Excel

## Overview of Project:
#### Inspecting the following: 
1. Outcomes based on our launch date.
2. Outcomes based on our funding goal.

### Our purpose for the analysis is to show Louise, how different campaigns fared in relation to their launch dates and their funding goals. 

## Analysis 

### To perform this ananlysis I used a Pivot Chart to show Louise which months were the least and most successful. I first took all of the data from the original sheet and converted it into a Pivot Table. Then, I filtered it down to Parent Category and years. Additionally choosing the values as Outcomes, and columns as outcomes. Lastly choosing the Date Created Conversion for the rows, so that it will only show months. I was confused at first because Excel automatically put years and quarters into the rows section so I had to delete those values from the Excel Pivot Table to showcase just the months.  


![Theater_Outcomes_vs_Launch](https://github.com/mckenziekkilburn/kickstarter-analysis/blob/master/resources/Theater_Outcomes_vs_Launch.png)


### As shown in the image below, I had to create a line chart to provide insight to Louise how our outcomes were based on the funding goal that we were striving to reach. To get the chart, I had to create a table with all of the ranges that are shown below. To get the calculations, I had to use the COUNTIFS() function to pull data from the orginal Kickstarter worksheet. After completing the calculations and totaling the Projects. I was to perform each category with percentages. 

![Outcomes_VS_Goals](https://github.com/mckenziekkilburn/kickstarter-analysis/blob/master/resources/Outcomes_VS_Goals.png)


### Challenges or Difficulties encountered
- When I was working with the COUNTIFS formula in Excel, I did have trouble with it at first. I was not getting the right amounts, they were too high in value.  However I resolved the issue because I was not putting in the last critia range which was for subcategory plays in all of the cells. This solved my issue, because I went back in and observed each cell.  

## Results

- We can conclude that in the months of May and June, Theater is the most successful. However in the months of November and December, we are the least successful in the Theater category. 

- For the plays subcategory, when we compare the ranges that are given, we can conclude that we were more successful with the range of less than $1,000. The reason for this is because we have a successful rate of 76% and only a 24% rate or failure.   

- Something that I noticed when looking at the data is that some of it is misleading. For instance, for the Outcomes Based on Goals chart for the ranges 45000 to 49999 it shows that 100% was failed. However if you were not looking at the data table you wouldnt see that there was on 1 play that took place for that range. 

- On the Outcomes Based on Goals worksheet, I would consider using a stacked column chart to better showecase how the failed and successful amounts added up. It is a good way to compare parts of a whole and how segments of a whole change over time. 
