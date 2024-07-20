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
![bike_buyers](https://github.com/user-attachments/assets/45d8156b-6146-438a-84a5-ecf89fed2f9b)
![Screenshot 2024-07-19 192628](https://github.com/user-attachments/assets/cc779a62-1fd0-46c4-935c-f052ba4b890f)
![cleaned_bike_buyers](https://github.com/user-attachments/assets/be1555f9-d23e-4279-b348-c65cd01bf1ad)


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
![Screenshot 2024-07-19 195948](https://github.com/user-attachments/assets/8b9bee4b-cc49-40e6-9e23-1b9f7fe04ffa)
![Screenshot 2024-07-19 195937](https://github.com/user-attachments/assets/082657fd-877f-4f4f-812a-55b8a7eb6730)
![Screenshot 2024-07-19 195832](https://github.com/user-attachments/assets/63e3a02e-7a7c-462d-b53f-a8d7a65acfc0)
![Screenshot 2024-07-19 195802](https://github.com/user-attachments/assets/20555c3c-3c49-4ac5-8020-203732d15d61)
![Screenshot 2024-07-19 195736](https://github.com/user-attachments/assets/4f93d33c-406b-48fc-a1c6-4f2f6b0a24f2)
![Screenshot 2024-07-19 195658](https://github.com/user-attachments/assets/db0ad9dc-4171-49e9-a5fe-b9e955339678)
![Screenshot 2024-07-19 195638](https://github.com/user-attachments/assets/5cdc77f6-b10b-4ec5-bfd9-563d8efc28ec)
![Screenshot 2024-07-19 195619](https://github.com/user-attachments/assets/1d72b524-f436-4e80-b4fc-86c2561e250f)
![Screenshot 2024-07-19 195552](https://github.com/user-attachments/assets/adc22746-ef92-42ca-bd0a-945a53997543)



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
![Screenshot 2024-07-20 130644](https://github.com/user-attachments/assets/c0861948-d37c-4014-a8db-89fc83264096)
![Screenshot 2024-07-20 130559](https://github.com/user-attachments/assets/177763a5-e72f-4f90-8160-3db48622b878)
![Screenshot 2024-07-20 130523](https://github.com/user-attachments/assets/dc762027-4bdb-434b-987d-afa518489a43)
![Screenshot 2024-07-20 130414](https://github.com/user-attachments/assets/7abde3b6-f7c3-4765-8296-fc006fd45367)
![Screenshot 2024-07-19 200105](https://github.com/user-attachments/assets/9d74e9d2-f7fb-4154-a6a3-cbbe006ebc0f)


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
