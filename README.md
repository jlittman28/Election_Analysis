# Election Audit Analysis


## Overview of Election Audit
  
 In any election, a review is conducted to ensure completeness and accuracy over the the results. We were tasked with verifying the underlying election data for the Colorado Board of Elections. Using Python, we will walk through the steps taken to achieve our objective.
  
 ## Election Audit Results
  
  
* How many votes were cast in this congressional election?


  ![TotalVotes](https://user-images.githubusercontent.com/85204128/124392883-cb280e00-dcc5-11eb-9c13-926121b0a6c2.PNG)

* Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
  
  To achieve the below vote count and percentage by county (County Votes Results), we leveraged for loops to iterate through all rows and conditional if statements.
  
  ###   ForLoops & Conditionals
  ![ForLoopsCounty](https://user-images.githubusercontent.com/85204128/124392800-797f8380-dcc5-11eb-97e7-24ce4ee4461e.PNG)


  ###   County Votes Results
  ![County_Votes](https://user-images.githubusercontent.com/85204128/124392649-de86a980-dcc4-11eb-9a7e-b29d546047c4.PNG)

* Which county had the largest number of votes?
  
  ![LargestCounty](https://user-images.githubusercontent.com/85204128/124392898-d7ac6680-dcc5-11eb-9549-a6f178e03247.PNG)


* Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
  
  ![CandidateResults](https://user-images.githubusercontent.com/85204128/124392903-e135ce80-dcc5-11eb-9d64-8c183b3ad7d1.PNG)

* Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
  
  ![WinningResults](https://user-images.githubusercontent.com/85204128/124392905-e85cdc80-dcc5-11eb-85e1-58b26064fbf8.PNG)

## Election-Audit Summary

The below refactoring of the current script can allow for more informed decisions to made about resource allocation and investigation into potential fraud. Creating dynamic aspects of the data allows a more insightful analysis of the information.
    
    1. Set variables to dynamically update the federal/state/local headers
    2. Add losing vote count/percentage by county
    
  
  
  
