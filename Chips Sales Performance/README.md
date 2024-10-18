## Use Case: Analyzing QVI Chips Sales Performance with Python


**Objective:** To analyze QVI Chips sales data using Python to identify key performance indicators, understand customer behavior, and inform marketing and product strategies.

**Steps:**

1. **Data Acquisition and Preparation:**
   - **Gather data:** Collect sales data from QVI Chips' database, including product ID, product name, sales quantity, sales price, purchase date, and customer information.
   - **Clean and preprocess data:** Handle missing values, inconsistencies, and outliers.
   - **Load data into a DataFrame:** Use Pandas to load the data into a DataFrame for analysis.

   ```
   import pandas as pd

   df = pd.read_csv('qvi_chips_sales.csv')
   ```
![Transaction df head](<Images/Screenshot (167).png>)

![Behaviour df head](<Images/Screenshot (168).png>)


2. **Exploratory Data Analysis (EDA):**
   - **Summary statistics:** Calculate summary statistics for numerical variables.
   - **Data visualization:** Create visualizations to explore data distributions and relationships.
   - **Extract Packet Weight:** Create a new column containing the chips packet weight.
   ![Packet weight](<Images/Screenshot (178).png>)
   - **Extract Brand Weight:** Create a new column containing the chips brand.
   ![Brand Weight](<Images/Screenshot (179).png>)
   - **Extract Dates:** Create a new column containing the date names, month, month-year and the year when chips was bought.
   ![Dates columns](<Images/Screenshot (180).png>)
   - **Extract Size Categories:** Create a new column containing the chips size categories based on the packet weight.
   [Size Categories](<Images/Screenshot (181).png>)
   - **Brand Name Correction:** Correct the brand names.
   ![Brand Names](<Images/Screenshot (182).png>)
  

3. **Product Performance Analysis:**
   - **Top-selling products:** Identify the best-selling products based on sales quantity, revenue, or profit.
   - **Product trends:** Analyze sales trends over time to identify seasonal patterns, growth rates, and declining products.
   - **Product segmentation:** Segment products based on categories, flavors, or packaging types to understand their performance within different segments.

   ![Brands By Sales](<Images/Screenshot (185).png>)

   - **Relationships:** Analyze the relationship between store numbers to identify similarities.
   ![Relationship](<Images/Screenshot (186).png>)
    

4. **Customer Analysis:**
   - **Customer demographics:** Analyze customer demographics to understand the target market.
   - **Customer purchasing behavior:** Identify customer preferences, purchase frequency, and average order value.

   ![Lifestage distribution](<Images/Screenshot (183).png>)

   ![Top 10 Buyers](<Images/Screenshot (184).png>)

   
**Visualization and Reporting:**
- Create visualizations to present key findings in a clear and concise manner.
- Develop comprehensive reports summarizing the analysis and providing actionable insights.