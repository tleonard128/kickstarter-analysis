# Analysis of Kickstarter Campaigns categorized as theater and plays

## Overview of Project
### Purpose
Using the functionality of Excel, I analyzed a set of Kickstarter data in order to analyze campaigns in relation to their launch dates and funding goals for Louise to compare to her Kickstarter for the play _Fever_.
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Using the Kickstarter data that was compiled to filter by Parent Category and start year, I was able to analyze the success of campaigns based on the month they were launched. Below you can see a graph that plots the number of successful, failed, and canceled campaigns based on the month in which the campaign was launched:

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/49666078/164600844-281469ac-9f9a-44c6-ab9c-3514f5646b55.png)


### Analysis of Outcomes Based on Goals
Using Kickstarter data compiled based on the successfullness of campaigns based on **funding goals**, I was able to calculate the percentage of campaigns that succeeded failed and were canceled (evidently none were canceled) based on the funding goals that were set in the **plays** category for campaigns.. Below you can see a graph with the funding goal in dollars on the x-axis relative to the success or failure percentage on the y-axis:

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/49666078/164592729-ce2d4d50-7d7f-4ec3-9050-bd985701a322.png)

### Challenges and Difficulties Encountered
During this analysis, the main challenges were faced when inserting unfamiliar functions and formation of the line graph used to plot the chart displayed in Analysis of **Outcomes Based on Goals**

#### Unfamiliar Functions
In order to utilize the `COUNTIFS` and `YEAR` functions properly in excel, I simply went through Microsofts documentation for each of the functions. Once I familiarized myself with the inner workings of the functions, I double checked the syntax to make sure there were not any errors and proceeded with the rest of the project. Documentation linked below:

[COUNTIFS](https://support.microsoft.com/en-us/office/countifs-function-dda3dc6e-f74e-4aee-88bc-aa8c2a866842?ui=en-us&rs=en-us&ad=us)

[YEAR](https://support.microsoft.com/en-us/office/year-function-c64f017a-1354-490d-981f-578e8ec8d3b9?ui=en-us&rs=en-us&ad=us)

#### Outcomes Based on Goals Line Graph

When plotting the percentages of successful, failured and canceled campaigns in the line graph, I came accross an issue where the failed campaigns were not plotting and the canceled campaigns were showing in a line accross the 100% mark in the top of the graph. I started to troubleshoot this by attempting to change the dataset being used, but that did not work. I attempted to replicate the data in a new sheet and run through the process again of creating a graph, but I ran into the same issue. Finally, I changed the graph type from a 100% stacked line graph to a simple line graph. I believe this is due to the fact that the 100% stacked line graph plots specific values and calculates them to be 100% and we were using data that had already been calculated into percentages, so there were extra calculations going into the graph that was misinterpretting the data.

## Results

### Conclusions from Theater Outcomes based on Launch Date

Theater campaigns start most frequently in May and June and are also have the most amount of successful outcomes. Conversly, theater campaigns start least frequently in November and December and have a lowest amount of successful outcomes. Regardless of the month in which a theater campaign starts, it seems to have the same chance at getting canceled with a small spike in January.

### Conclusion from Outcomes based on Goals

Kickstarter campaigns for plays in the theater category with the smallest funding goals had the highest percentage of success. Looking at the data, although the majority of the campaigns were trying to raise less than $5000 in fundings, those campaigns were successful in achieving their funding goal at a rate of more than 70%. Although there is a spike in percentage of successful campaigns looking for funding between $35,000 and $45,000 (66% succces), the total campaigns with goals in that range is only 9 which is less than 1% of the total campaigns run in this data set.

### Dataset Limitations

### Other possible tables/ graphs that could be created
- What are some other possible tables and/or graphs that we could create?
