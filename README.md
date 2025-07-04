# DSA-EXCEL-PROJECT

This work is on the DSA excel project using Amazon Case Study Data

## Project Topic-Amazon Product Review 

### Project Overview

This data aims to analyse product and customer review data to generate insights that can
guide product improvement, marketing strategies, and customer engagement.

### Tool used
- Ms Excel [Download here](www.microsoft.com)
  - For Data Collection
  - For analysis
  - For creating a report
 
### Data cleaning and preparation

In the initial phase of the data cleaning and preparations, we perform the following;
  
- The product category field was split into five subcategories using Excel's Text to Columns feature.
- The first four extracted categories were merged back into the main dataset and renamed for clarity.
- Analysis was primarily conducted on the main category to allow for concise and meaningful pivot table summaries.

  ### Analytical Techniques
- Excel’s IF function was used to identify products with 50% or more discount.
- COUNTIF function calculated the total count of such discounted products.
- Pivot tables and summary statistics were created to explore patterns in rating counts and discount levels.

  ### Analysis

  I was able to get answers to the following questions using Excel for analysis
  
  - What is the average discount percentage by product category?
  - How many products are listed under each category?
  - What is the total number of reviews per category?
  - Which products have the highest average ratings?
  - What is the average actual price vs the discounted price by category?
  - Which products have the highest number of reviews?
  - How many products have a discount of 50% or more?
  - What is the distribution of product ratings (e.g., how many products are rated 3.0,
    4.0, etc.)?
  - What is the total potential revenue (actual_price × rating_count) by category?
  - What is the number of unique products per price range bucket (e.g., <₹200,
   ₹200–₹500, >₹500)?
  - How does the rating relate to the level of discount?
  - How many products have fewer than 1,000 reviews?
  - Which categories have products with the highest discounts?
  - Identify the top 5 products in terms of rating and number of reviews combined.
 

![PIVOT TABLE 1](https://github.com/user-attachments/assets/3f26f2f8-81f1-4650-a032-460791226641)

![PIVOT TABLE 2](https://github.com/user-attachments/assets/95611df5-1efe-4bde-97aa-006556da1eaa)

![PIVOT TABLE 3](https://github.com/user-attachments/assets/42d469aa-acea-4992-b7da-2f2ddf69d65d)

![PIVOT TABLE 4](https://github.com/user-attachments/assets/2b485f41-b749-454d-9000-e57f724ccae0)

![PIVOT TABLE 5](https://github.com/user-attachments/assets/a8d5443e-741f-4547-91ae-e1964d86dc4f)

![PIVOT TABLE 6](https://github.com/user-attachments/assets/dee50efd-3b36-4f21-bf2b-19f1d74f4d7f)

![PIVOT TABLE 8](https://github.com/user-attachments/assets/25624ea4-73d8-4aa9-a2cd-02fe1fbe83d7)

![PIVOT TABLE 9](https://github.com/user-attachments/assets/9506d94a-217f-40b3-bcb9-1d6a4ac55e08)

![PIVOT TABLE 10](https://github.com/user-attachments/assets/190295bc-787c-467c-a27b-251536b74521)

![PIVOT TABLE 11](https://github.com/user-attachments/assets/8bdf6d7b-4c45-483a-8e5e-2deab4bb5789)


### Interpretation

- Higher discounts are generally associated with reduced customer rating activity.- Encourage Detailed Reviews

- This may indicate that deeply discounted products are either overlooked or not perceived as strongly, reducing the likelihood of reviews.

- In contrast, full-price or minimally discounted items may trigger greater engagement, possibly due to higher customer expectations.

### Recommendation

 - Encourage Detailed Reviews
  -Prompt buyers to leave comprehensive reviews, especially for discounted items, to balance the perceived value and boost engagement.

- Target High-Engagement Users
 -Identify and engage customers who leave longer or more detailed reviews, as they tend to be more invested in the brand and products.

- Leverage Sentiment Trends
 -Use review content (length, tone, sentiment) to guide improvements in product descriptions, features, and customer support touchpoints.






# DSA-POWER BI-PROJECT

This work is on the DSA Power BI project using Palmora group employee and bonus rules Data

## Project Topic-Palmora group review using Power Bi 

### Project Overview

This data aims to analyse the company data and generate insights that the Palmoria management team would need to address, should be visualised using appropriate charts. The focus should be on gender-related issues within the organization and its regions.

### Tool used

- Power Bi[Download here](www.microsoft.com)
 - For Data Cleaning
 - For analysis and visualization
 - For creating a report
    
### Data cleaning and preparation
	
In the initial phase of the data cleaning and preparations, we perform the following;

- A generic gender status was assigned to employees who chose not to disclose their gender, ensuring completeness in the gender column
- Employees without salary entries—primarily those who are no longer with the company—were excluded from the dataset to maintain accuracy.
- Departments labeled as “NULL” were also removed to achieve 100% column quality and avoid distortion in departmental analysis.
- In alignment with the case study requirements, which reference regions rather than locations, the column header Location was renamed to Region.
- To maintain data integrity throughout the transformation process, the ‘Keep Rows’ function was applied to permanently exclude rows with null values, preventing them from reappearing in the cleaned dataset.
- Employee records were grouped by attributes such as Gender, Department, Rating, Region, and Salary Band.
- Visualizations such as bar charts, pie charts, and clustered column charts were used to identify patterns in distribution and diversity.
- Filters and slicers were likely used to refine cross-segment insights.
  
### Summary of Findings

#### Gender Distribution
- Females account for the largest gender group (55.32%).
- Males make up 40.43%, while Others represent a small minority (2.26%).
- This reflects good gender diversity, with room to further promote inclusion for underrepresented groups.
  
### Analysis

### Departmental Gender Representation
- The Service and Training departments have the highest gender diversity.
- Legal, Product Management, and Engineering departments also show a strong mix, though some departments (e.g., Support) have lower representation overall.
- Female presence appears strong across departments, with minimal inclusion of "Others".

### Rating and Gender
- A significant portion of the dataset is "Not Rated":
- Females dominate the unrated group, indicating a potential gap in performance review completion or transparency.
- This may affect career progression, morale, and development tracking.

### Recommendations
- Improve Rating Completion
  - Ensure that all employees receive regular and documented performance ratings.
  - Use this data for feedback, training plans, and promotion considerations.
- Promote Departmental Balance
  - Encourage cross-departmental inclusion programs where gender representation is low (e.g., Support, Accounting).
  - Introduce mentorship or diversity hiring initiatives in underrepresented departments.
- Address Salary Band Disparities
  - Conduct a pay equity audit across salary bands and regions.
  - Ensure fair compensation practices that reflect qualifications, contributions, and roles regardless of gender.
- Increase Representation of Minority Groups
  - Explore and expand efforts to support "Others" gender identity category through inclusive policies and safe reporting environments.













