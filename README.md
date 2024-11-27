# Exploratory-Data-Analysis-Project
# Exploratory Data Analysis (EDA) Project: Two Centuries of Ultra-Marathon Races

## Introduction
This project explores two centuries of ultra-marathon races using data analysis techniques. It delves into trends, performance metrics, and patterns among athletes in events across the United States, focusing particularly on races held in 2020. By cleaning, preprocessing, and visualizing the dataset, the project uncovers valuable insights into athlete performance, seasonal effects, and race characteristics.

The dataset includes over 7 million records with 13 attributes, covering various ultra-marathon events, athlete demographics, and race statistics. The analysis emphasizes 50km and 50mi races, providing a comprehensive view of ultra-marathon trends.

---

## Objectives
1. Data Cleaning:
   - Filter data to include only relevant events in the USA.
   - Focus on specific race types and events from 2020.
   - Handle missing, duplicate, and inconsistent data for accurate analysis.

2. Feature Engineering:
   - Create new features such as athlete age and race season to enhance analysis.
   - Standardize and rename columns for better readability.

3. Visualization and Insights:
   - Use advanced visualizations to reveal patterns and trends.
   - Analyze gender, age, and seasonal impacts on race performance.

4. Performance Analysis:
   - Compare speed and participation across age groups, genders, and seasons.
   - Identify factors influencing athlete performance.

---

## Data Cleaning Process
The dataset was meticulously cleaned to ensure accurate analysis:
1. Filtering: 
   - Focused on races held in the USA, specifically 50km and 50mi events from 2020.
   - Standardized race names for consistency.

2. Handling Missing Data:
   - Identified and removed rows with null values in key columns.
   - Addressed non-numeric values and inconsistencies in columns like performance time and athlete age.

3. Fixing Duplicates:
   - Checked for and removed duplicate entries to maintain data integrity.

4. Feature Adjustments:
   - Extracted the athlete’s age from their year of birth.
   - Parsed race dates to identify the month and season.

5. Dropping Irrelevant Columns:
   - Removed columns not relevant to the analysis, such as club affiliations and nationality, since only USA events were considered.

---

## Feature Engineering
To enhance the dataset, new columns were created:
1. Athlete Age:
   - Calculated based on the year of the event and the athlete's year of birth.

2. Race Season:
   - Mapped months to seasons (Winter, Spring, Summer, Fall) for seasonal trend analysis.

3. Performance Time Standardization:
   - Cleaned and converted performance times into a uniform format.

---

## Data Visualization
Using libraries like Seaborn and Matplotlib, visualizations were created to explore key patterns and relationships.

### Key Visualizations:
1. Race Length Distribution:
   - Histograms showing the frequency of 50km and 50mi races.

2. Gender-Based Analysis:
   - Comparison of male and female participation and performance.

3. Age vs. Speed:
   - Scatter plots revealing the relationship between age and average speed.

4. Seasonal Analysis:
   - Insights into how seasons impact athlete performance.

5. Speed Distribution by Gender:
   - Violin plots comparing male and female speeds in different race lengths.

---

## Key Insights
1. Performance Differences by Gender:
   - Male athletes tend to have a slightly higher average speed than female athletes in both 50km and 50mi races.

2. Age Groups with Best Performance:
   - Athletes in their mid-20s to early 30s consistently achieve higher speeds, especially in 50mi races.

3. Seasonal Trends:
   - Performance is slower in summer races, likely due to heat, while winter and spring events show faster speeds.

4. Race Participation:
   - A significant number of races are held in spring and fall, with balanced participation across genders.

5. Event Characteristics:
   - The popularity of 50km and 50mi races highlights their importance in ultra-marathon culture.

---

## Challenges and Solutions
1. Large Dataset:
   - Managing over 7 million rows required efficient data cleaning and filtering to focus on relevant subsets.
   
2. Inconsistent Formats:
   - Performance times and race names were standardized for better analysis.

3. Missing Values:
   - Identified and handled missing values to avoid biased insights.

4. Duplicate Data:
   - Removed duplicate entries to ensure the accuracy of findings.

---

## Conclusions
This project successfully explores trends and patterns in ultra-marathon races using detailed data cleaning, feature engineering, and visualization. The analysis highlights:
- The influence of age, gender, and season on performance.
- Seasonal preferences and trends in ultra-marathon events.
- Differences in performance metrics for 50km and 50mi races.

These findings provide valuable insights for race organizers, athletes, and researchers studying endurance sports.
---

## Future Work
1. Expand the analysis to other race distances beyond 50km and 50mi.
2. Explore trends across multiple years to identify long-term changes.
3. Incorporate weather data to study its impact on athlete performance.

---

This project demonstrates the power of data analytics in uncovering valuable insights from complex datasets, providing a foundation for future exploration in sports and endurance race analytics.
