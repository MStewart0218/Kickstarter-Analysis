# An Analysis of Kickstarter Campaigns

> ## Overview of Project:
> The purpose of this analysis is to show the outcomes of Kickstarter campaigns in relation to their launch dates and funding goals.

## Analysis:

The analysis was performed by creating pivot tables and charts: "Theater Outcomes by Launch Date" and "Outcomes Based on Goal". The Theater Outcomes vs launch Date chart highlights month-to-month outcomes for parent category “Theater” compared to the launch date. The data set in the Outcomes Based on Goal(s) table and chart drills down the data to subcategory “Plays” and shows the count and percentage of successful, failed, and canceled campaigns based on goal ranges.

## Questions to Consider:

####  - What are two conclusions you can draw about the Theater Outcomes by Launch Date?
####  - What can you conclude about the Outcomes based on Goals?
####  - What are some limitations of this dataset?
####  - What are some other possible tables and/or graphs that we could create?

## Results:

The “Theater Outcomes by Launch Date” pivot line chart visualizes successful, failed, and canceled outcome, consequently showing the majority of successful and failed outcomes in May and June. The ideal period to launch a successful Kickstarted campaign is between April and August. Goal 1000 to 4999 account for the majority of ‘Number Successful’ and ‘Number Failed’. The highest percentage of ‘Percentage Successful’ campaigns have a goal less than 1000, while the highest percentage of ‘Percentage Failed’ campaigns have a goal greater than 50000. Campaign goals less than 1000 are more successful thaan goals greater than 50000. Data limitations are reflected in the Canceled Plays- Outcomes Based on Goal data since there are no canceled campaigns that met any of the goal ranges. Data is also not drilled down to “US” only campaigns and could limit the overall assessment by not providing a clear analysis of the US theater and play campaign demographic. The Mode = 3 for the Canceled Theater Outcomes by Launch Date and show 5 out of 12 months (Feb, Mar, May, Nov, Dec) campaigns were canceled in Parent Category “Theater”. Other contributing factors may have played a role in why plays were cancelled (i.e. region, weather, etc). This is not visible within the dataset.

We could create a statistical table to show the Goal outcomes for “successful”, “failed”, and canceled” for parent category “Theater” or subcategory “Plays”. The table would show the Mean, Median, Standard Deviation, Upper Quartile, Lower Quartile, IQR, Q1 Boundary, and Q3 Boundary. The statistical table data could now be used to create a Box and Whisker Plot graph to call out outliers and skewedness.

## Documents & Charts:

1. `Kickstarter Challenge Workbook` 
    [Kickstarter_Challenge.xslx](https://github.com/MStewart0218/Kickstarter-Analysis/files/7786949/Kickstarter_Challenge.xlsx)
 
2. `Theater Outcomes vs Launch Date Line Chart`
    [Theater_Outcomes_vs_Launch.png](https://user-images.githubusercontent.com/95396477/147617173-832dbcfe-127a-4fed-a63c-d9a4f0a3a4c8.png)
    
    **Pivot Table Criteria**
    
    | Pivot Field | Criteria|
    | ------:| -----------:|
    | Filters | Parent Category & Years
    | Columns | Outcomes |
    | Rows| Date Created Conversion|
    | Values| Count of Outcomes|

3. `Play Outcomes vs Goal Line Chart` 
    [Play_Outcomes_vs_Goal.png](https://user-images.githubusercontent.com/95396477/147617018-8f99a447-4b82-49ef-8ed4-74864431ec5b.png)
    
    **Outcomes Based on Goals Data Set**
    
    ![image](https://user-images.githubusercontent.com/95396477/147625927-4172ba27-63b5-4811-ad37-cbe8de524099.png)
