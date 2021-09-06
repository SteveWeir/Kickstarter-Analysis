# Kickstarting with Excel

## Overview of Project

### Purpose

This analysis was conducted in order to determine trends in outcomes of Kickstarter campaigns in relation to their launch dates and funding goals. The dataset included in the "Kickstarter" tab of the attached Excel spreadsheet
serves as the population upon which the analysis was conducted, with data from a wide range of categories including, but not limited to theater, journalism, games, music, and more. However, this analysis will focus primiarily 
on the parent category of theater for the examination of trends in fundraising outcomes based on launch date, and then turn attention to fundraising outcomes based on fundraising goals within the subcategory of plays, specifically.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

As previously stated, this phase of the analysis focuses primarily on the larger category of fundraising outcomes based on launch date for the category of theater. PivotTables were created in Excel to aggregate the number of successful,
failed, and canceled fundraisers by the month in which their campaigns were launched. The trends in this PivotTable were then visualized via a line chart, which can be found in the "Resources" folder.

### Analysis of Outcomes Based on Goals

Within the parent category of theater fundraisers, data was then orgranized into a spreadsheet- which can be found on the "Outcomes Based on Goal" tab of the spreadsheet. The focus lays exclusively within the subcategory of "plays",
where the number and percentage of successful, failed, and canceled campaigns were counted based on fundraising goal intervals of approximately $5,000.00, including those with goals less than $1,000 and in excess of $50,000. Similarly
to the first part of the analysis, a line chart is used as the visualization method for outcomes based on fundraising goals. 

### Challenges and Difficulties Encountered

While no major challenges were encountered, cell references for the counting formulas within the outcomes based on goals spread sheet may have prove a pain point. The analyst must ensure that the formula references the correct cell, 
and that the COUNTIFS function has the correct numerical parameters for the fundraising goal intervals, otherwise the data table and subsequent line chart will both be incorrect.

## Results

In looking at the Theater kickstarter outcomes based on launch date, one can infer that theater kickstarters tend to be successful when launched in May, with February being a distant second alternative. Conversely, kickstarters
launched in May also lead to the highest number of failures, which can be justified by the high number of launches during that month.   

When examining the results of play kickstarter outcomes based on goals, it stands to reason that percentages of successful vs failed campaigns are negatively correlated for the majority of goal intervals. Those with high success rates
tend to have low failure rates and vice versa. Campaigns with low fundraising goals are more likely to be succcessful than those with more ambitious goals, and failure rates are highest for campaigns seeking to raise $45,000 or more.

It should be noted that this analysis focuses only on one parent category of campaigns (theater), and one subcategory of campaigns (plays). This limits the scope of the analysis' utility, particularly for those seeking to understand 
trends for campaigns with other focuses. Additional graphs and tables could be created to examine outcomes based on launch date or fundraising goal across all categories for a more high-level approach. Additionally, one could examine 
live kickstarters in the dataset to find trends in percentage of goal reached based on launch date and goal amount, either within certain categories or aggregated.

