# Bike Sales Excel Cleaning 

## Project Overview
Cleaning the Bike Sales Dataset using Microsoft Excel

## Resources
1. Data Source:
- bike_buyers.xlsx

2. Software:
- Microsoft Excel

## Create sheets
create pivot table sheet, dashboard sheet, working sheet
copy and paste original sheet to working sheet

look around to see what to clean up and how we can use it

## Cleaned Data
1. Add filters
- select all cells
- data -> filter
- mainly using filters to search thorugh column values
  
2.  removed duplicates
data -> remove duplicates

3.  find and replace
ctrl + H
searched by columns

Marital Status:
changed M to Married changed S to Single

Gender:
changed F to female
changed M to Male

Income:
changed Income from Accounting to Currency

4. Create Age ranges
 - create new column Age Bracket
 - used nested IF statements to create age brackets

## Create Pivot Tables

1. Average Income of people who did or did not buy bikes
- Created a pivot table through income, splitting it by gender and whether they purchased bikes or not
- gender = rows, sum income = values (value field settings -> average)
- create chart with insert -> recommended charts
- click on chart -> added axis titles, can change color
- changed pivot table values to numeric so chart is cleaner
- Conclusion: Men and women who had higher salaries bought bikes, with more men making the most amount of money
- Question: is their income different compared to ones that did or did not buy bikes? if they said yes, is it because of money? should we cater to customers or not?

2. Customer Commute
- does commuting distance make a difference?
- do they live one mile or 20 miles? who are more likely to buy it?
- commute distance, purchased bike if they did
  
- challenge, commute distance is not in order
- did not work: going back into the working sheet and using find and replace ctrl + H 10+ miles
- went back and replaced with "More than 10 miles" worked!
- added axis titles and chart title

- Conclusion: we found that customers with a commute of 0-1 miles bought bikes

3. Customer Age Brackets buying bikes

- Which age groups are buying the most number of bikes?

- count of yes and no
- age brackets

insert -> recommeded charts, line chart
conclusion: people under the age of 30 are not buying bikes, age 30-54 age buying a lot of bikes more than anybody, 
adding legend, axis title, title

instead of age brackets, we can use the ages themselves
insert line graph

second graph is more complicated and hard to make sense of, kind of see a pattern but is hard to see
therefore, the age brackets is more helpful than individual ages


## Create Dashboard

Used three visualizations in order to create a dashboard

1. remove gridlines (view: uncheck gridlines)
2. choose color for header (home: merge and center, then center veritcally) so centers title, make it white and bigger)
3. line everything up (select multiple charts: shape format tab: align to right
4. change designs of charts of needed (design tab)
5. pivot chart analyze (insert slicer for martial status, region, education)

Conclusion: 
- marital status: marrried people make 5k-10k more than single
- education: it was found that the number of individuals who completed partial high school bought signficantly more bikes than those who completed their bachelor's degree

this dashboard allows us to filter through each section: marital status, region, and education
