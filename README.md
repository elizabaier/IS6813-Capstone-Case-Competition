# IS6813-Capstone-Case-Competition-Group-Portfolio
University of Utah MSBA Capstone Case Competition Fall 2025 - Swire Coca-Cola Cart Abandonment Project

## Business Problem and Project Objective
Swire Coca-Cola currently faces a significant problem with cart abandonment on their online ordering platform, MyCoke360. Our analysis showed that Swire Coca-Cola is facing an abandonment rate of 14.8% on the current MyCoke360 platform, causing the business to miss out on significant revenue. Our purpose will be to measure, describe, and understand the behaviors that drive cart abandonment to assist Swire Coca-Cola in focusing their efforts to prevent cart abandonment on their MyCoke360 platform.

## Business Problem Solution


## Business Solution Value


## Personal Contributions
I was privileged to be able to contribute several important things to the project. First, I did a large part of the data wrangling to merge datasets and ultimately was able to produce a combined google analytics, visit plan, cutoff times, operating hours, and customer data table containing just over 3.6 million rows. I took advantage of Databricks notebooks and some advanced SQL functions to complete the steps of the merge (as documented in my Exploratory Data Analysis (EDA) notebook). I was also able to contribute insights into business demographics during the EDA process and created a TOTAL_ITEMS variable during the feature engineering process. During the modeling phase, I attempted a Random Forest and Interrupted Time Series analysis, though both ultimately did not produce any useful results. Since there were no actionable insights resulting from those models as previously mentioned, I worked with another teammate, Ashley to produce a viable logistic regression from which we gained some valuable and statistically significant insights into factors driving cart abandonment. Finally, I was heavily involved in compiling our final notebooks and writing up our conclusions.

## Project Difficulties
We faced several difficulties throughout the project. First and foremost, the data we were given was messy and required many transformations to obtain our final dataset and our target variable. Second, there was no data given from before the treatment period when the MyCoke360 ordering platform was implemented so it was impossible for us to determine the impact of the new ordering platform on cart abandonment. Finally, we lost some data to missing information: 75 rows to missing anchor dates and about 23,000 rows to missing other critical information that we needed to calculate order windows and cart abandonment. Fortunately, we were still left with over 3.6 million rows of data which was plenty to analyze customer behavior surrounding cart abandonment. Overall, this project gave us valuable experience with handling real-world, non-ideal data conditions. 

## Conclusion


## Other Considerations
Please note that some of the feature engineering code at the beginning of the modeling notebook are not my efforts but were necessary to include for the usability of my code later in the notebook. My contribution to feature engineering was the TOTAL_ITEMS column and the other features were a result of the work of my teammates. 
