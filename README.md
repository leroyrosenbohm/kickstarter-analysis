# Kickstarting with Excel

## Overview of Project
This project is performing data analysis on Kickstarter projects to uncover trends and help launch a certain type of project.
### Purpose
The purpose of this anaylyse was to give Louise’s play "Fever" the best chance of succeeding based on analysis of past Kickstarter projects.
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
In order to analyse the outcomes of projects based on launch date, I had to organize the data based on numerous factors. The date launched data had to be converted from an epoch unix timestamp to human-readable data. I also had to find the total amount of projects based on outcome. The launch dates and outcomes had to be categorized by theater so we could show data relative to Louise's project.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/95730129/146666523-1de4fcdb-7254-4082-a31a-c05010b44978.png)

### Analysis of Outcomes Based on Goals
To analyse the outcomes based on goals, a select amount of data had to be moved to a new sheet that was to be sorted by the range of the goal. Data was then brought over to this new sheet using a formula to coincide with varying categories such as outcome, goal amount, and plays as a subcategory. We used plays to relate to Louise's project as close as we could. 
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/95730129/146666539-e127c00e-33ab-4f85-b460-b6bb0d98f469.png)

### Challenges and Difficulties Encountered
A potential challenge of the analysis would be the iniitial formatting of the data. There is a lot of information there and if you mess any of it up, the resulting information will not be correct. 
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

We can conlude that theater projects have a lot of success between April and June. We can also conclude that the time period of September to March is not a great time to launch a theater project as the success rate is not much higher than the failed rate.
- What can you conclude about the Outcomes based on Goals?

We can conclude that the subcategory of plays has a higher failure rate when the goal is at least $45000. We can also conclude that the sucess rate is highest when the goal is less than $5000.
- What are some limitations of this dataset?

A limitation of the dataset would be that it does not currently account for the backers themselves. There could be more data on the age of the backers in relation to how much money they pledge and compare that to the countries they reside.
- What are some other possible tables and/or graphs that we could create?

We could create a table to show the amount of backers and their average pledge compared to outcome and filtered by the country.
