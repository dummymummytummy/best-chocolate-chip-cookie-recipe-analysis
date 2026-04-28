# Chocolate Chip Cookie Recipe Analysis

## Overview
This analysis finds out the best chocolate chip cookie recipe 
by identifying which recipes produce a crispy edge, chewy middle, 
and caramel flavor, and how those recipes compare in ratings 
to recipes that do not meet these criteria.

## Dataset
The dataset was custom built from 34 popular chocolate chip cookie 
recipes sourced from well known creators including Preppy Kitchen, 
Broma Bakery, Sally's Baking Addiction, Jacques Torres, Alton Brown, 
Serious Eats, America's Test Kitchen, and more. It contains 30 columns 
covering ingredient amounts, baking techniques, sugar ratios, 
criteria scores, and user ratings.

## Reports and How They Were Solved

**Report 1: Which recipes meet all 3 criteria and how do their ratings 
compare to those that don't?**
Recipes were grouped into two categories using the Meets_All_Criteria_Y_N 
column. The average rating was calculated for each group and displayed 
using a clustered bar chart. Recipes meeting all 3 criteria averaged 
4.8 out of 5 compared to 4.7 for those that did not.

**Report 2: Does using brown butter correlate with a higher rating?**
Recipes were split into two groups using the Brown_Butter_Y_N column 
and their average ratings were compared using a clustered bar chart. 
Brown butter recipes averaged 4.8 out of 5 while regular butter 
recipes averaged 4.6 out of 5.

**Report 3: How does the brown to white sugar ratio vary and which range 
do top rated recipes share?**
A scatter plot was used to plot Brown_Sugar_Pct on the X axis and 
Recipe_Rating_5 on the Y axis. A trend line was added to show the 
direction of the relationship. Top rated recipes clustered in the 
60 to 85 percent brown sugar range.

**Report 4: What is the distribution of baking temperatures and how does 
it relate to crispy edges?**
Recipes were grouped by baking temperature (325, 350, and 375 degrees F) 
and displayed in a clustered column chart. The Meets_Crispy_Edge_Y_N 
column was used as a color legend. All recipes baked at 375 degrees F 
met the crispy edge criteria while most recipes baked at 350 degrees F 
did not.

**Report 5: Is there a relationship between chill time and recipe rating?**
A scatter plot was used with Min_Chill_Time_hrs on the X axis and 
Recipe_Rating_5 on the Y axis. A chill category column was created 
in Power Query grouping recipes into No Chill, Short, Medium, and Long. 
A trend line showed a slight upward slope meaning longer chill times 
tend to produce slightly higher rated recipes.

**Report 6: How does the use of an extra egg yolk impact recipe ratings 
compared to recipes that use only whole eggs?**
Recipes were grouped using the Extra_Yolk_Y_N column and their average 
ratings were compared using a clustered bar chart. Recipes with an extra 
egg yolk averaged 4.8 out of 5 while recipes without averaged 4.6 out of 5.

**Report 7: Which creator or source produces the most recipes meeting 
all 3 criteria?**
Recipes were grouped by Creator_Source and their average criteria scores 
were displayed in a stacked bar chart using the Criteria_Score_0_3 column. 
Bon Appetit and Smitten Kitchen both scored a perfect 3 out of 3. 
Broma Bakery, Serious Eats, and America's Test Kitchen scored 2 out of 3. 
Preppy Kitchen averaged 1.5 out of 3.

## Key Findings
- Recipes meeting all 3 criteria averaged a 4.8 out of 5 rating
- Brown butter recipes rated higher than regular butter recipes
- Top rated recipes used 60 to 85 percent brown sugar
- All recipes baked at 375F met the crispy edge criteria
- Bon Appetit and Smitten Kitchen scored a perfect criteria score of 3 out of 3

## Tools Used
- Power BI (visualizations and analysis)
- Microsoft Excel (data review)

## Files
- Chocolate_Chip_Cookie_Dataset.csv — the full dataset
- cookie_analysis.pbix — Power BI visualizations

## Author
Prashna Dhakal
April 2026
