# The AB Testing Case Study   

The case study on AB Testing covered the essentials for understanding and implementing A/B testing. 
Starting with A/B testing statistics and the the Central Limit Theorem and confidence intervals in statistical inference. 
Methods tested were 1-sample and 2-sample T-tests, as well as the Chi-squared test, which was also used for   
the case study. All tests were executed with Python Scipy.    

## Overview
In the case study the task is to help the Library of Montana State University with its website.   

Below the library picture, there is a search bar and three big items: “Find”, “Request” and “Interact”.     
All three of them contain access to important information and services that the library prides itself in offering.     
However, the Website Analytics show that the “Interact” button has, ironically, almost no interactions.    

The University therefore wants to improve the Headline of the category Interact.    
An A/B Test is conducted:   
- duration 21 days   
- 5 Versions for the headline: Interact / Connect / Learn / Help / Services   
- Measuresd primary KPI: CTR    
- second KPIs: drop off on category site /  Homepage return rate   
- Minimum detectable effect: 30% in CTR   

## Tools used
- Python with Scipy, Pandas, Seaborn

You can find the csvs for the AB testing [here](https://github.com/HannePruefer/AB_Testing/tree/main/data)  
The notebook with the testing script is [here](https://github.com/HannePruefer/AB_Testing/blob/main/montana.ipynb) 
