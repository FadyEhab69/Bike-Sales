# Bike Sales Analysis Documentation

# Overview

This report details the analysis of a Bike Sales dataset, showcasing proficiency in data cleaning, transformation, and visualization using Power Query, Power Pivot, and Excel. The dataset, initially containing raw customer and sales information, was processed to derive actionable insights into customer demographics, purchasing behavior, and regional trends.

# Data Cleaning and Transformation

The raw dataset was imported into Power Query to address inconsistencies and enhance data quality:


Handled missing values by discarding rows with empty or invalid entries.


Standardized column headers by trimming extra spaces and quotes, and cleaned cell values by removing leading/trailing quotes and spaces.

Converted categorical variables (e.g., Marital Status, Gender) and numerical data (e.g., Income) to consistent formats, parsing date-related fields to handle abnormalities.

Flagged extreme values (e.g., an age of 89) for review to maintain dataset representativeness.

Post-cleaning, Power Pivot was used to create calculated measures and relationships, enabling deeper analysis of purchase patterns against demographic and geographic factors.

# Analytical Approach

The analysis focused on key dimensions to uncover trends in bike purchases:


Commute Distance: Assessed the impact of commute distance (0-1 Miles, 1-2 Miles, 2-5 Miles, 5-10 Miles, Above 10 Miles) on purchase decisions.


Age Bracket: Segmented customers into Adolescent, Middle Age, and Old categories to evaluate age-related purchasing behavior.


Gender and Income: Analyzed average income per purchase across genders to identify spending disparities.


Regional Insights: Explored regional variations (Europe, North America, Pacific) in sales data.

# Key Findings


Commute Distance Impact: Customers with shorter commutes (0-1 Miles) had the highest purchase count (200 Yes vs. 166 No), indicating proximity influences buying decisions. Longer commutes (Above 10 Miles) showed fewer purchases (33 Yes vs. 78 No).


Age Bracket Trends: Middle-aged customers (30-59) led purchases (30 Yes vs. 23 No), marking them as a key market segment. Adolescents and older customers showed lower engagement.


Gender and Income: Males had a higher average income per purchase ($49,444) compared to females ($36,000), with an overall average of $42,368 for buyers versus $38,444 for non-buyers.


Interesting Fact: A customer aged 89 purchased a bike, suggesting a niche market of active seniors for further exploration.

# Visualization

A dashboard was created in Excel to present the analysis visually:

Customer Commute: Line charts depicted a decline in purchases with increasing commute distance, with a notable drop beyond 5-10 Miles.

Customer Age Bracket: Line charts highlighted a peak in purchases among middle-aged customers, with a decline in older age groups.

Avg Income Per Purchase: Bar charts compared income distributions by gender, showing males with higher spending capacity.

Filters: Interactive dropdowns for Education, Region, and Marital Status enabled dynamic data exploration.

# Conclusion

This analysis demonstrates a robust approach to transforming raw data into meaningful insights using Power Query for cleaning, Power Pivot for modeling, and Excel for visualization. Findings suggest targeting middle-aged customers with shorter commutes and exploring the senior market as a growth opportunity. Future analysis could incorporate predictive modeling to forecast sales trends.
