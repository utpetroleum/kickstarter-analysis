# Kickstarting with Excel

## Overview of Project

### Purpose
Louise’s play “Fever” came close to its fundraising goal. We are helping Louise see how her fundraising campaign fared with different campaigns in relation to their launch dates and funding goals. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/92401000/138753789-f1797f92-b656-48c0-8f59-70899d399eb1.png)

The analysis of this section was performed by creating a pivot table and filtering data by “theater” in Parent Category and Years. The rows were setup by date and grouped by months and the columns was outcome filter by “successful, failed, canceled”. A line plot of the count of outcomes versus date was created shown above. 

The most amount of successful theater fundraisings occurred in the month of May and June and gradually decline towards at the end of the year, December being the lowest. 

The amount of failed theater fundraisings ranged between 30 through 50, with the most occurring between May through August, and October.

The amount of canceled theater fundraising was low throughout the year, with January being the highest. 

### Analysis of Outcomes Based on Goals

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/92401000/138753868-d9e3218b-6d0c-48bf-bd92-7f51f48b3f19.png)

The analysis of this section was performed by creating a table of the Goal range from “less than 1000” to “Greater than 50000” with 5000 increments and count of outcomes filter by subcategory “plays”. Then the count of outcomes was converted to percentage out of total projects. Last, a line plot was created of percentage of outcomes versus goal range shown above. 

As the goal amount increased, the chance of the fundraising being successful decreases until the goal amount reached $30,000 where it increased momentarily and falls off.

As the goal amount increased, the chance of the fundraising being a failure increased until the goal amount reached $30,000 where it decreased momentarily and then increased.

None of the fundraisings for plays were canceled.

From the plot, the percentage of “successful” and “fail” of plays are inversely related. 

### Challenges and Difficulties Encountered
In “Theater Outcomes by Launch Date” zero fundraising for theaters were canceled in the month of October, however the data was blank, so it gives the illusion no data was retrieved for that month. This will need to be stated when presenting the visualization. 

In “Outcomes Based on Goals” the plot trend for “Number Successful” and “Number Failed” of plays fundraising reversed after $20,000 because it’s compared as “Percentage”, so it gives an incorrect representation. Instead, we should have plot them as number of counts versus Goal Range to show the real story that as Goal Range increased, the number of successful fundraisings decreased and vice versa. Another option is to get a larger sample size where Total Projects are the same throughout all Goal Range.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
If Louise wants a higher chance of her play having a successful fundraising campaign, she should do it in May.

Louise should avoid fundraising her campaign towards the end of the year as that is when the least amount of fundraising are successful and highest failed fundraisings.

- What can you conclude about the Outcomes based on Goals?
The higher the fundraising goal, the lower the chances of it being successful so Louise should keep your fundraising low and keep it below $20,000 to have a 50% or higher of it succeeding. 

- What are some limitations of this dataset?
The data is old, 2016 being the latest. The data needs to be more recent since the fundraising will happen “today” and not in the past. 

The sample sizes are too small, this limitation was shown in “Outcomes Based on Goals” because we saw how representing “Percentage Successful” and “Percentage Fail” was shewed for the higher goal ranges.  

- What are some other possible tables and/or graphs that we could create?
In “Theater Outcomes by Launch Date” we could represent the outcomes by quarters because fundraising campaigns can occur over series of months rather than just one month.
In “Outcomes Based on Goals” we could create a line plot of Fundraising Outcome Counts versus Goal Range to overcome the small sample size when goal range got too large. We can also represent the trend using a bar chart because a line chart is better use to illustrate changes over time.
