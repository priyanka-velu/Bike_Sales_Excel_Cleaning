# Bike Sales Analysis

## Project Overview
The Bike Sales Dataset project aims to clean, analyze, and visualize sales data to uncover key business insights using Microsoft Excel. By meticulously processing raw data, creating pivot tables, and developing dynamic charts and a comprehensive dashboard, we are able to reveal important trends and patterns in customer behavior, income distribution, and demographic preferences. This project provided actionable insights that can guide marketing strategies, customer segmentation, and sales optimization for the bike retail business.

## Resources
1. **Data Source**:
   - [bike_buyers.xlsx](bike_buyers.xlsx)

2. **Software**:
   - Microsoft Excel

## Excel Cleaning

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

## Excel Analysis: Pivot Tables and Charts

1. **Average of Income**
- **Methods**:
   - Created a pivot table of the customers' incomes, splitting it by gender and whether they purchased bikes or not.
- **Pivot Table**:

![Screenshot 2024-07-19 195736](https://github.com/user-attachments/assets/4f93d33c-406b-48fc-a1c6-4f2f6b0a24f2)

- **Chart**:

![Screenshot 2024-07-19 195552](https://github.com/user-attachments/assets/adc22746-ef92-42ca-bd0a-945a53997543)

**Questions Answered:**

1. **Question:** Is there an income difference between those who bought bikes and those who didn't?
   - **Answer:** Yes, the data indicates that individuals with higher incomes are more likely to purchase bikes. This suggests that higher-income customers are a key market segment for bike sales.

2. **Question:** Should we cater to higher-income customers?
   - **Answer:** Given the higher average income of bike buyers, marketing and product offerings should be tailored to appeal to higher-income customers. This could include offering premium bike models, personalized services, and targeted advertising.

- **Conclusion**: Men and women with higher salaries are more likely to purchase bikes, with men making the most money.

2. **Customer Commute Distance**
- **Methods**:
   - Analyzed commute distance and bike purchase status.
   - Sorted and cleaned commute distance values for accuracy.
- **Pivot Table**:

![Screenshot 2024-07-19 195802](https://github.com/user-attachments/assets/20555c3c-3c49-4ac5-8020-203732d15d61)

- **Chart**:

![Screenshot 2024-07-19 195619](https://github.com/user-attachments/assets/1d72b524-f436-4e80-b4fc-86c2561e250f)

**Questions Answered:**

1. **Question:** Are short-distance commuters more likely to buy bikes?
   - **Answer:** Yes, the data shows that customers with a commute of 0-1 miles are more likely to purchase bikes. This indicates a strong preference for bikes among those who have short commutes.

2. **Question:** How can we leverage this information to increase bike sales?
   - **Answer:** Marketing efforts should focus on promoting the convenience and benefits of biking for short commutes. Highlighting features such as ease of parking, cost savings, and health benefits could attract more short-distance commuters.

- **Conclusion**: As the commute distance increases, the less likely customers purchased bikes. Customers with a commute of 0-1 miles were most likely to buy bikes.

3. **Customer Age**
- **Methods**:
   - Count of "Yes" and "No" for bike purchases by individual ages.
   - Used a line chart to visualize age vs. bike purchases.
   - Observed that it was difficult to interpret due to the variability of each age, indicating no clear pattern or insight. 
- **Pivot Table**:

![Screenshot 2024-07-19 195832](https://github.com/user-attachments/assets/63e3a02e-7a7c-462d-b53f-a8d7a65acfc0)

- **Chart**:

![Screenshot 2024-07-19 195638](https://github.com/user-attachments/assets/5cdc77f6-b10b-4ec5-bfd9-563d8efc28ec)

- **Conclusion**: Decided to create an age bracket pivot table and graph in order to visually depict patterns in age and bike purchases. 

4. **Customer Age Ranges**
- **Methods**:
   - Count of "Yes" and "No" for bike purchases by age brackets.
   - Used a line chart to visualize age brackets vs. bike purchases.
- **Pivot Table**:

![Screenshot 2024-07-19 195937](https://github.com/user-attachments/assets/082657fd-877f-4f4f-812a-55b8a7eb6730)

![Screenshot 2024-07-19 195948](https://github.com/user-attachments/assets/8b9bee4b-cc49-40e6-9e23-1b9f7fe04ffa)

- **Chart**:

![Screenshot 2024-07-19 195658](https://github.com/user-attachments/assets/db0ad9dc-4171-49e9-a5fe-b9e955339678)

**Questions Answered:**

1. **Question:** Which age demographics should be targeted for bike sales?
   - **Answer:** The data shows that people middle aged people from ages 30-54 are buying the most bikes. This demographic should be the primary target for bike sales campaigns. Younger individuals under 30 are less likely to purchase bikes.

2. **Question:** Why are people under 30 not buying bikes, and how can this be addressed?
   - **Answer:** People under 30 might not be buying bikes due to factors such as financial constraints, lifestyle preferences, or lack of interest in biking. To address this, bike companies could consider creating affordable bike models, promoting biking as a trendy and eco-friendly option, and offering flexible payment plans to attract younger customers.

- **Conclusion**: Customers of ages 30-54 are buy the most number of bikes with customers under 30 buying the least amount.

## Dashboard Analysis

### Dashboard Overview
This dashboard allows us to filter through the following sections: marital status, region, and education.

![Screenshot 2024-07-19 200105](https://github.com/user-attachments/assets/9d74e9d2-f7fb-4154-a6a3-cbbe006ebc0f)

### Filters and Insights

#### Education
- **Bachelor's Degree**

![Screenshot 2024-07-20 130644](https://github.com/user-attachments/assets/c0861948-d37c-4014-a8db-89fc83264096)

- **Partial High School**

![Screenshot 2024-07-20 130559](https://github.com/user-attachments/assets/177763a5-e72f-4f90-8160-3db48622b878)

**Key Finding:** Individuals who completed partial high school bought significantly more bikes than those with a bachelor's degree.

**Analysis:**
- The data suggests that individuals with lower formal education levels (partial high school) are more likely to purchase bikes compared to those with higher education (bachelor's degree).
- This could be due to various factors such as lower income levels leading to a preference for bikes as a cost-effective mode of transportation or a greater interest in biking as a recreational activity within this demographic.

**Questions Answered:**

1. **Question:** Why are individuals with partial high school education buying more bikes than those with a bachelor's degree?
   - **Answer:** This could be because bikes are a more affordable means of transportation, which might appeal more to individuals with lower income levels typically associated with lower educational attainment. Marketing efforts could emphasize the affordability and cost savings of biking.

2. **Question:** How can we target marketing efforts to individuals with partial high school education?
   - **Answer:** Marketing campaigns can focus on the cost-effectiveness, health benefits, and convenience of biking. Promotional strategies could include discounts, financing options, and community events that engage this demographic.


#### Marital Status
- **Married**

![Screenshot 2024-07-20 130523](https://github.com/user-attachments/assets/dc762027-4bdb-434b-987d-afa518489a43)

- **Single**

![single](https://github.com/user-attachments/assets/88955ccd-4d64-4f12-88b2-c793ff3fc3f3)

**Key Finding:** Married individuals were more likely to buy more bikes than single individuals.

**Analysis:**
- Married individuals might have different transportation and recreational needs compared to single individuals. They may be more inclined to buy bikes for family activities or as a cost-saving measure for commuting.
- This demographic might also have a higher disposable income or value health and family time, making them more likely to invest in bikes.

**Questions Answered:**

1. **Question:** What motivates married individuals to buy more bikes than single individuals?
   - **Answer:** Married individuals may prioritize family activities and health, leading to higher bike purchases. They might also view biking as a family-friendly recreational activity and an economical commuting option.

2. **Question:** How can we better cater to the needs of married individuals in our product offerings and marketing strategies?
   - **Answer:** Offering family packages, tandem bikes, or accessories for children can attract married customers. Marketing campaigns can highlight family-friendly biking activities, health benefits, and cost savings. Additionally, promoting group discounts or family-oriented biking events can further engage this demographic.


## Conclusion

### Education:
- **Key Insight:** Those with partial high school education are significant bike buyers.
- **Strategic Focus:** Highlight affordability and utility in marketing efforts.

### Marital Status:
- **Key Insight:** Married individuals show a higher propensity to purchase bikes.
- **Strategic Focus:** Develop family-oriented products and marketing strategies to cater to their needs.
