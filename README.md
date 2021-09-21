# Kickstarting with Excel

## Overview of Project

### Purpose
Based on the theater plays' launch dates and their funding goals, determine when the foundrasing should start and which should be the goal to have a successful play.

### Backgorund
Louise’s play Fever came close to its fundraising goal in a short amount of time. She wants to know how different campaigns fared in relation to their launch dates and their funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
These are the conclusions based on historical data from 2009 to 2017: 
* The best month to launch the fundraisng is May, with a 67% success rate, followed by June, with a 65% success rate. 
* Contrary, the worst month to launch the fundraisign is December, with a 49% success rate.      

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/21972342/134095417-915d9261-01ac-4258-8a70-7861d80e59c4.png)

### Analysis of Outcomes Based on Goals
Based on the kickstarter goals trend, the following conclusions were drawn:
* Successful plays had a goal less than $5,000 (73% success rate).
* If the goal is too high, greater than $45,000; the goal will not be met (11% success rate).  

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/21972342/134098355-8f5c3125-a5ef-498d-ad8e-429bd3797e3c.png)

### Challenges and Difficulties Encountered
The most challenging encounter I had was to drawn conclusions from the charts. I think the less information we have the more general the conclusion will be.

The difficulty of working with pivot table is presented when the data is not correctly labeled. This can cause confusion when selecting the fields. Additionally, you have to know what you want to show with the charts, to select the fields accordingly.   

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  * The best months to launch the fundraisng are May and June. 
  * Contrary, the worst month to launch the fundraisign is December.
  
- What can you conclude about the Outcomes based on Goals?
  * The higher the goal the higher the difficulty to achieve successful fundraisng. Highest successful rate can be found below the $5000 goal.

- What are some limitations of this dataset?
  * The limitation I can see is that the data has not been updated since 2017. If the dataset is continuosly updated, we should be able to find newer trends. 
  * New columns we can add are goal in USD and pledged in USD, to standarize the currency in the dataset and have a better "outcomes based on goals" table.     

- What are some other possible tables and/or graphs that we could create?
  * Some information that can help to deepen the conclusion can be:
    - Create a chart with the trend by year/month to see if the number of kickstarted plays have been increasing or decreasing in popularity.  
    - Additionally, we can use the country information to determine where are the most succesful plays.
    - Also, changing the "outcome vs goals" line chart to "goal vs pledged" box and whisker chart can give us more information for the achievable fundraising goals.     
    - Finally, adding a table of the date created vs date ended can show us how quickly the successful projects were fundraised.      
