# Statistical-Data-Analysis
This project is a part of the [Data Analyst Course](https://practicum.yandex.com/profile/data-analyst/).

#### -- Project Status: [Completed]

## Project Intro/Objective
The purpose of this project is education project. 

### Description of the plans
Note: Megaline rounds seconds up to minutes, and megabytes to gigabytes. For calls, each individual call is rounded up: even if the call lasted just one second, it will be counted as one minute. For web traffic, individual web sessions are not rounded up. Instead, the total for the month is rounded up. If someone uses 1025 megabytes this month, they will be charged for 2 gigabytes.

### Instructions on completing the project
Step 1. Open the data file and study the general information
File path:
* /datasets/megaline_calls.csv Download dataset
* /datasets/megaline_internet.csv Download dataset
* /datasets/megaline_messages.csv Download dataset
* /datasets/megaline_plans.csv Download dataset
* /datasets/megaline_users.csv Download dataset
Step 2. Prepare the data
* Convert the data to the necessary types
* Find and eliminate errors in the data
* Explain what errors you found and how you removed them. Note: many calls have a duration of 0.0 minutes. These might be missed calls. Whether or not to preprocess these values is up to you; assess how much their absence would affect the results of your analysis.
For each user, find:
* The number of calls made and minutes used per month
* The number of text messages sent per month
* The volume of data per month
* The monthly revenue from each user (subtract the free package limit from the total number of calls, text messages, and data; multiply the result by the calling plan value; add the monthly charge depending on the calling plan)
Step 3. Analyze the data
* Describe the customers' behavior. Find the minutes, texts, and volume of data the users of each plan require per month. Calculate the mean, dispersion, and standard deviation. Plot histograms. Describe the distributions.
Step 4. Test the hypotheses
* The average revenue from users of Ultimate and Surf calling plans differs.
* The average revenue from users in NY-NJ area is different from that of the users from other regions.
You decide what alpha value to use.
Explain:
* How you formulated the null and alternative hypotheses.
* What criterion you used to test the hypotheses and why.
Step 5. Write an overall conclusion
Format: Complete the task in Jupyter Notebook. Put the programming code in code cells and text explanations in markdown cells, then apply formatting and headings.

### Methods Used
* Data Visualization
* Predicting and Forecast Modeling

### Technologies
* Python
* Pandas, matplotlib, sklearn
* Jupyter Notebook

## Project Description
You work as an analyst for the telecom operator Megaline. The company offers its clients two prepaid plans, Surf and Ultimate. The commercial department wants to know which of the plans brings in more revenue in order to adjust the advertising budget.
You are going to carry out a preliminary analysis of the plans based on a relatively small client selection. You'll have the data on 500 Megaline clients: who the clients are, where they're from, which plan they use, and the number of calls they made and text messages they sent in 2018. Your job is to analyze clients' behavior and determine which prepaid plan brings in more revenue.
