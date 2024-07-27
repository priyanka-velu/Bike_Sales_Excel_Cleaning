# Bike Sales Excel Cleaning 

## Project Overview
The Bike Sales Dataset project aims to clean, analyze, and visualize sales data to uncover key business insights using Microsoft Excel. By meticulously processing raw data, creating pivot tables, and developing dynamic charts and a comprehensive dashboard, we are able to reveal important trends and patterns in customer behavior, income distribution, and demographic preferences. This project provided actionable insights that can guide marketing strategies, customer segmentation, and sales optimization for the bike retail business.

## Resources
1. **Data Source**:
   - [bike_buyers.xlsx](bike_buyers.xlsx)

2. **Software**:
   - Microsoft Excel

## Cleaned Data

### Raw Data
![bike_buyers](https://github.com/user-attachments/assets/45d8156b-6146-438a-84a5-ecf89fed2f9b)

### Cleaning Steps
1. Add filters to search through each column values for discrepancies
2. Remove Duplicate Information
3. Find and Replace values
   - Marital Status: M to Married, S to Single
   - Gender: F to Female, M to Male
4. Change formatting
   - Income: Accounting to Currency
5. Created ranges
   - Age Brackets: Used nested IF statements to create age brackets

![Screenshot 2024-07-19 192628](https://github.com/user-attachments/assets/cc779a62-1fd0-46c4-935c-f052ba4b890f)

### Cleaned Data

![cleaned_bike_buyers](https://github.com/user-attachments/assets/be1555f9-d23e-4279-b348-c65cd01bf1ad)

## Created Pivot Tables and Charts

1. **Average of Income**
- Pivot Table:
![Screenshot 2024-07-19 195736](https://github.com/user-attachments/assets/4f93d33c-406b-48fc-a1c6-4f2f6b0a24f2)
- Chart:
![Screenshot 2024-07-19 195552](https://github.com/user-attachments/assets/adc22746-ef92-42ca-bd0a-945a53997543)

- **Pivot Table**: Created a pivot table through income, splitting it by gender and whether they purchased bikes or not.
  - Gender = Rows, Sum Income = Values (Value Field Settings -> Average).
- **Chart**: Created a chart with Insert -> Recommended Charts.
  - Added axis titles and changed colors.
- **Conclusion**: Men and women with higher salaries bought bikes, with men making the most money.
- **Business Question**: Is there an income difference between those who bought bikes and those who didn't? Should we cater to higher-income customers?


2. **Customer Commute Distance**
- Pivot Table:
![Screenshot 2024-07-19 195802](https://github.com/user-attachments/assets/20555c3c-3c49-4ac5-8020-203732d15d61)
- Chart:
![Screenshot 2024-07-19 195619](https://github.com/user-attachments/assets/1d72b524-f436-4e80-b4fc-86c2561e250f)

- **Pivot Table**: Does commuting distance make a difference in bike purchases?
  - Analyzed commute distance and bike purchase status.
  - Sorted and cleaned commute distance values for accuracy.
- **Conclusion**: Customers with a commute of 0-1 miles bought bikes.
- **Business Question**: Are short-distance commuters more likely to buy bikes?

3. **Customer Age**
- Pivot Table:
![Screenshot 2024-07-19 195832](https://github.com/user-attachments/assets/63e3a02e-7a7c-462d-b53f-a8d7a65acfc0)
- Chart:
![Screenshot 2024-07-19 195638](https://github.com/user-attachments/assets/5cdc77f6-b10b-4ec5-bfd9-563d8efc28ec)

4. **Customer Age Ranges**
- Pivot Table:
![Screenshot 2024-07-19 195937](https://github.com/user-attachments/assets/082657fd-877f-4f4f-812a-55b8a7eb6730)
![Screenshot 2024-07-19 195948](https://github.com/user-attachments/assets/8b9bee4b-cc49-40e6-9e23-1b9f7fe04ffa)
- Chart:
![Screenshot 2024-07-19 195658](https://github.com/user-attachments/assets/db0ad9dc-4171-49e9-a5fe-b9e955339678)
- **Pivot Table**: Which age groups are buying the most number of bikes?
  - Count of "Yes" and "No" for bike purchases by age brackets.
- **Chart**: Used a line chart to visualize age brackets vs. bike purchases.
- **Conclusion**: People under 30 are not buying bikes; ages 30-54 buy the most.
- **Business Question**: Which age demographics should be targeted for bike sales?


## Created Dashboard

### Dashboard Overview
This dashboard allows us to filter through sections: marital status, region, and education.

![Screenshot 2024-07-19 200105](https://github.com/user-attachments/assets/9d74e9d2-f7fb-4154-a6a3-cbbe006ebc0f)

### Filters and Insights

1. **Bachelor's Degree**
   ![Screenshot 2024-07-20 130644](https://github.com/user-attachments/assets/c0861948-d37c-4014-a8db-89fc83264096)

2. **Partial High School**
   ![Screenshot 2024-07-20 130559](https://github.com/user-attachments/assets/177763a5-e72f-4f90-8160-3db48622b878)

3. **Married**
   ![Screenshot 2024-07-20 130523](https://github.com/user-attachments/assets/dc762027-4bdb-434b-987d-afa518489a43)

4. **Single**
   ![single](https://github.com/user-attachments/assets/88955ccd-4d64-4f12-88b2-c793ff3fc3f3)

### Key Findings
- **Marital Status**: Married people make $5k-$10k more than singles.
- **Education**: Individuals who completed partial high school bought significantly more bikes than those with a bachelor's degree.

---

This structured documentation provides a clear and organized overview of the Bike Sales Excel Cleaning project, detailing each step, analysis, and key business insights.
