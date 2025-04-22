# Group 1 MIST4610 Group Project 2

## Team Name:
21482 Group 1

## Team Members:
1. Sophie Naustdal https://github.com/sophienaustdal/MIST4610GroupProject2.git
2. Rachel Chuan 
3. Riley Cook 
4. Chidera Nwosu
5. Coleman Vaughn

## Description of Dataset:

## Question 1:
Question: What are the top 15 components that have the highest potential impact across the top 5 manufacturers with the most frequent recalls? How many vehicles are possibly affected by each component for each manufacturer?

Importance:


<img width="1236" alt="Screenshot 2025-04-22 at 4 05 55 PM" src="https://github.com/user-attachments/assets/98be873e-91f1-4ba4-bc7a-0636d1001be7" />

Through filtering the manufacturers by top 5 by COUNT(Nhtsa Id) and the components by top 15 by SUM([Potentially Affected]), this graph identifies the top 5 manufacturers with the most amount of recalls and the top 15 components that affect the most vehicles. The SUM([Potentially Affected]) was placed in the color mark to illustrate the total number of possibly affected vehicles for each component recall for each of the manufacturers. The lighter colors indicate components that affect fewer vehicles, while the darker colors highlight the highest-risk components. A grand total row was added to show how many total vehicles could be affected by each manufacturer for these components. The results were sorted in ascending order by the grand total of SUM([Potentially Affected]) within each manufacturer, and also in descending order by the grand total of SUM([Potentially Affected]) of each component. This allows us to quickly identify which components are the most critical and affect the most amount of vehicles, and also which manufacturers are the leading contributors to the most amount of recalls. Our results indicate that air bags, electrical system, and power train components have the highest potential impact across all components. Particularly, for General Motors, air bags are the riskiest component, prompting further investigation and likely higher standards and regulations needing to be put in place. The recalled components of General Motors, Ford, and Chrysler affect the largest number of vehicles as compared to Daimler Trucks and Forest River, which have fewer, likely due to their specialization in commercial vehicles. The results from this visualization are useful in order to pinpoint which vehicle components regulators should focus on, as they likely need better industry standards. These findings would be especially important for manufacturers to identify which specific components need more quality control. It could also be important for consumers when making buying decisions, as they could identify which manufacturers to possibly steer clear of.

## Question 2:
Question: Since vehicles and equipment are the most frequently recalled items, which of our “major brands” have the highest number of recalls in these categories? For the top three brands, what specific components are most commonly found to be faulty?

Importance:

## Manipulations Applied:

## Tableau Packaged Workbook:
