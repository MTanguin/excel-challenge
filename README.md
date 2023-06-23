#### "Analyzing 1,000 sample projects to uncover hidden trends and insights for achieving funding goals."
Using Excel functions/Graphs/Tables/Statistical Tools &amp; Formulas

# Background
Crowdfunding platforms like Kickstarter and Indiegogo have been growing in success and popularity since the late 2000s. From independent content creators to famous celebrities, more and more people are using crowdfunding to launch new products and generate buzz, but not every project has found success.
To receive funding, the project must meet or exceed an initial goal, so many organizations dedicate considerable resources looking through old projects in an attempt to discover “the trick” to finding success. For this week's Challenge, you will organize and analyze a database of 1,000 sample projects to uncover any hidden trends.

# Methods
- Use conditional formatting to fill each cell in the outcome column with a different color, depending on whether the associated campaign was successful, failed, canceled, or is currently live.
  *Create a new column called Percent Funded that uses a formula to find how much money a campaign made relative to its initial funding goal.

- Use conditional formatting to fill each cell in the Percent Funded column according to a three-color scale. The scale should start at 0 with a dark shade of red, and it should transition to green at 100 and blue at 200.
  *Create a new column called Average Donation that uses a formula to find how much each project backer paid on average.

  *Create two new columns, one called Parent Category and another called Sub-Category, that use formulas to split the Category and Sub-Category column into the two new,     separate columns.

  *Create a new sheet with a pivot table that analyzes your initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per category.

- Create a stacked-column pivot chart that can be filtered by country based on the table that you created.
  
- Create a new sheet with a pivot table that analyzes your initial sheet to count how many campaigns were successful, failed, or canceled, or are currently live per sub-category.

- Create a stacked-column pivot chart that can be filtered by country and parent category based on the table that you created.

- The dates in the deadline and launched_at columns use Unix timestamps. Fortunately for us, this formulaLinks to an external site. that can be used to convert these timestamps to a normal date.

  *Create a new column named Date Created Conversion that will use this formulaLinks to an external site. to convert the data contained in launched_at into Excel's date format.

  *Create a new column named Date Ended Conversion that will use this formulaLinks to an external site. to convert the data contained in deadline into Excel's date format.

  *Create a new sheet with a pivot table that has a column of outcome, rows of Date Created Conversion, values based on the count of outcome, and filters based on parent category and Years.

  *Now, create a pivot-chart line graph that visualizes this new table.

- Create a report in Microsoft Word, and answer the following questions:

  *Given the provided data, what are three conclusions that we can draw about crowdfunding campaigns?

  *What are some limitations of this dataset?

  *What are some other possible tables and/or graphs that we could create, and what additional value would they provide?

#### Crowfunding Goal Analysis
- Create a new sheet with 8 columns:

Goal
Number Successful
Number Failed
Number Canceled
Total Projects
Percentage Successful
Percentage Failed
Percentage Canceled

- In the Goal column, create 12 rows with the following headers:

Less than 1000
1000 to 4999
5000 to 9999
10000 to 14999
15000 to 19999
20000 to 24999
25000 to 29999
30000 to 34999
35000 to 39999
40000 to 44999
45000 to 49999
Greater than or equal to 50000


- Using the COUNTIFS() formula, count how many successful, failed, and canceled projects were created with goals within the ranges listed above. Populate the Number Successful, Number Failed, and Number Canceled columns with these data points.

- Add up each of the values in the Number Successful, Number Failed, and Number Canceled columns to populate the Total Projects column. Then, using a mathematical formula, find the percentage of projects that were successful, failed, or canceled per goal range.

- Create a line chart that graphs the relationship between a goal amount and its chances of success, failure, or cancellation.

#### Statistical Analysis
Most people would use the number of campaign backers to assess the success of a crowdfunding campaign. Creating a summary statistics table is one of the most efficient ways that data scientists can characterize quantitative metrics, such as the number of campaign backers.

For gaining an in-depth understanding of campaign backers, evaluate the number of backers of successful and unsuccessful campaigns by creating your own summary statistics table.

- Create a new worksheet in your workbook, and create one column for the number of backers of successful campaigns and one column for unsuccessful campaigns.
- Use Excel to evaluate the following values for successful campaigns, and then do the same for unsuccessful campaigns:

The mean number of backers
The median number of backers
The minimum number of backers
The maximum number of backers
The variance of the number of backers
The standard deviation of the number of backers

- Use your data to determine whether the mean or the median better summarizes the data.

- Use your data to determine if there is more variability with successful or unsuccessful campaigns. Does this make sense? Why or why not?

# Conclusions

1.	Overall, the success rate of crowdfunding campaign based on the outcome by percentage is 56.5. 
2.	As shown on the data sets:
-	the outcome with respect to parent category shows that the highest number of donations are pledged to theater.
-	the outcome with respect to sub-category shows that the highest number of donations are pledged to plays
-	the outcome with respect to launched date (years) shows that in years 2017,2018 & 2019 the crowdfunding campaigns success rate was going up then declined around year 2020 when the pandemic began. The total number of crowdfunding campaigns has also declined drastically in year 2020.
3.	Crowdfunding campaigns was directly affected by the pandemic & recessions, as pandemic is the major contributor to the cause of recessions and global lockdown that affected the economic status of the world.

Limitations:
-	Sampling error possible – methods of collecting the samples are not clarified or presented
-	Limited sources of data

Other possible tables and/or graphs:

-	Scatter with smooth line and markers as shown in Years_SuccessRate spreadsheet, Fig. A
-	Where all the lines projects downward to the lowest point of the chart in year 2020.
-	Line graph as shown in Years_SuccessRate spread sheet, Fig. B
-	Where the success rate and the total number of crowdfunding campaigns showed a significant decline in year 2020.
-	Clustered Column shown in ParentCategory_Country spreadsheet
-	Where the chart shows what countries have contributed/pledged the donations with respect to Parent Category. It showed that US earned the highest spot in most categories.



















Source:
https://courses.bootcampspot.com/courses/2799/assignments/42864?module_item_id=802611
