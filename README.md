# Bike Sales Excel Cleaning 

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
- **Pivot Table**:

![Screenshot 2024-07-19 195736](https://github.com/user-attachments/assets/4f93d33c-406b-48fc-a1c6-4f2f6b0a24f2)

- **Chart**:

![Screenshot 2024-07-19 195552](https://github.com/user-attachments/assets/adc22746-ef92-42ca-bd0a-945a53997543)

- **Methods**:
   - Created a pivot table of the customers' incomes, splitting it by gender and whether they purchased bikes or not.

**Questions Answered:**

1. **Question:** Is there an income difference between those who bought bikes and those who didn't?
   - **Answer:** Yes, the data indicates that individuals with higher incomes are more likely to purchase bikes. This suggests that higher-income customers are a key market segment for bike sales.

2. **Question:** Should we cater to higher-income customers?
   - **Answer:** Given the higher average income of bike buyers, marketing and product offerings should be tailored to appeal to higher-income customers. This could include offering premium bike models, personalized services, and targeted advertising.

**Conclusion**: Men and women with higher salaries bought bikes, with men making the most money.

2. **Customer Commute Distance**
- **Pivot Table**:

![Screenshot 2024-07-19 195802](https://github.com/user-attachments/assets/20555c3c-3c49-4ac5-8020-203732d15d61)

- **Chart**:

![Screenshot 2024-07-19 195619](https://github.com/user-attachments/assets/1d72b524-f436-4e80-b4fc-86c2561e250f)

- **Methods**:
   - Analyzed commute distance and bike purchase status.
   - Sorted and cleaned commute distance values for accuracy.
- **Conclusion**: Customers with a commute of 0-1 miles bought bikes.

**Questions Answered:**

1. **Question:** Are short-distance commuters more likely to buy bikes?
   - **Answer:** Yes, the data shows that customers with a commute of 0-1 miles are more likely to purchase bikes. This indicates a strong preference for bikes among those who have short commutes.

2. **Question:** How can we leverage this information to increase bike sales?
   - **Answer:** Marketing efforts should focus on promoting the convenience and benefits of biking for short commutes. Highlighting features such as ease of parking, cost savings, and health benefits could attract more short-distance commuters.


3. **Customer Age**
- **Pivot Table**:

![Screenshot 2024-07-19 195832](https://github.com/user-attachments/assets/63e3a02e-7a7c-462d-b53f-a8d7a65acfc0)

- **Chart**:

![Screenshot 2024-07-19 195638](https://github.com/user-attachments/assets/5cdc77f6-b10b-4ec5-bfd9-563d8efc28ec)

**Questions Answered:**

1. **Question:** What is the age distribution of bike buyers?
   - **Answer:** The age distribution data indicates that customers aged 30-54 are the primary buyers of bikes. Younger individuals under 30 are less likely to purchase bikes.

2. **Question:** How should marketing strategies be adjusted based on age?
   - **Answer:** Marketing strategies should be tailored to target individuals aged 30-54, emphasizing factors that appeal to this age group, such as family-friendly bikes, fitness benefits, and durable, high-quality products.

4. **Customer Age Ranges**
- **Pivot Table**:

![Screenshot 2024-07-19 195937](https://github.com/user-attachments/assets/082657fd-877f-4f4f-812a-55b8a7eb6730)

![Screenshot 2024-07-19 195948](https://github.com/user-attachments/assets/8b9bee4b-cc49-40e6-9e23-1b9f7fe04ffa)

- **Chart**:

![Screenshot 2024-07-19 195658](https://github.com/user-attachments/assets/db0ad9dc-4171-49e9-a5fe-b9e955339678)

- **Methods**:
   - Count of "Yes" and "No" for bike purchases by age brackets.
   - Used a line chart to visualize age brackets vs. bike purchases.
- **Conclusion**: People under 30 are not buying bikes; ages 30-54 buy the most.

**Questions Answered:**

1. **Question:** Which age demographics should be targeted for bike sales?
   - **Answer:** The data shows that people aged 30-54 are buying the most bikes. This demographic should be the primary target for bike sales campaigns.

2. **Question:** Why are people under 30 not buying bikes, and how can this be addressed?
   - **Answer:** People under 30 might not be buying bikes due to factors such as financial constraints, lifestyle preferences, or lack of interest in biking. To address this, bike companies could consider creating affordable bike models, promoting biking as a trendy and eco-friendly option, and offering flexible payment plans to attract younger customers.


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











