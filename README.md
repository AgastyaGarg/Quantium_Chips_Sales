This project focuses on chips sales analysis, leveraging data analytics for insights into different sales attributes. It helps businesses tailor their approaches and improve sales effectively   

The project was done in partnership with an Australia based Data Analytics company Quantium. The data has been provided by them. It consists of potato chips sales across various stores in Australia from July 2018 - July 2019. Our task is to analyze sales of chips in this time period and recommend where improvements can be made. Python and it's data analysis libraries were applied to complete this task.

There are two datasets which have been provided to us, transactions and customer

Task 1 : Analyze the sales data of last 1 year and make recommendations where the company can make improvements. They need suggestions on demographic, time period to target to boost their sales. This is in Quantium Project 1 notebook

Task 2 : The company decided to conduct impact specific strategy for three trial stores(77, 86, 88) and wants us to study their impact by comparing sales data and customers volume during the trial and pre trial period. This is in Quantium Project 2 notebook

Task 1
Our main methodology for this task is to build visualizations for 'TOT_SALES'  by membership ('PREMIUM_CUSTOMER') and by 'LIFESTAGE'. We will also plot total transactions made over the 1 year.

Based on these visualizations, we will make recommendations and suggestions to the company to increase their sales.

Task 2
We would like to compare sales and customer traffic data for our three trial stores (77, 86, 88) during the pre trials and trial period. Our data is from July 2018 to July 2019. Pre trial period has been defined from July 2018 to Jan 2019 and trial period has been defined from Feb 2019 - April 2019. Our methodology to achieve this will be

We start by calculating correlations to compare trends like sales or customer counts between the trial store and potential control stores during the pre-trial period. This helps us identify stores with similar patterns.

Next, we calculate standardized magnitudes to measure scale differences in metrics, ensuring that we account for absolute variances between the trial and control stores.

We combine the correlation and standardized magnitude scores into a weighted total. Using this combined score, we select the control store that best matches the trial store during the pre-trial period.

During the trial period, we compare the metrics of the trial store and the scaled control store to evaluate the effect of the intervention, adjusting for scaling as needed.

We run hypothesis tests to determine if the differences in metrics during the trial period are statistically significant. This allows us to assess whether the intervention in the trial store was effective.

After analyzing the results, we interpret the findings, focusing on whether the intervention achieved its desired impact and what actions might be needed.

Finally, we create clear visualizations to present trends across the pre-trial and trial periods, making the insights easier to understand and communicate.
