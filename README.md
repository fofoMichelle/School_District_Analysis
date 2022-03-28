# School_District_Analysis
# Overview of the school district analysis

In this project we were working with Maria from the school to provide an analysis on the schools and districts performances based on data collected from those schools and districts.To do so we had to go through all the key performmance metrics provided in those collected data and complete a detailed analysis.
The school board was overall pleased with our performance but has identified some anomalies with the data collected for a particular school:*Thomas High School* and turned to us and Maria (our contact) to perform a new analysis that would remove those compromised data

# Results
## Impact on district summary
Adding Nan to all grade 9 at Thomas High School had the following impact on our district summary result

***District Analysis Updated***
![image](https://user-images.githubusercontent.com/99924850/160303956-7e48607b-8d18-43e9-8a8e-2385a4fd5924.png)

***District Analysis Original***
![image](https://user-images.githubusercontent.com/99924850/160304212-e334aada-e5f7-45d1-8b17-1b2155104205.png)

- As shown on the above screenshots the above mentioned change did not have a huge impact on the results of our result (with the difference between the original data being less than 0.5%) this mainly due on the fact that the grade 9 students from Thomas High School represent a very small percentage of the total student count (they only make up approximately 1.2% of the total student count)

## Impact on the school summary and Thomas High School Performance

***High and low performance original***
![image](https://user-images.githubusercontent.com/99924850/160304584-b248eade-5295-47de-8c89-cb8fbe17a040.png)

![image](https://user-images.githubusercontent.com/99924850/160304622-5920190a-37a9-454f-acdd-bcaff1de9c32.png)

***High and low performance updated***
![image](https://user-images.githubusercontent.com/99924850/160304644-ac15c099-9035-4796-aff3-6afddfacab02.png)
![image](https://user-images.githubusercontent.com/99924850/160304668-6138d391-ee6b-47d1-b81f-e307331be709.png)

- Only the top school performance were updated as we only made changes on Thomas High School grades.
- The changes although they impacted the reading and math scores did not affect the school ranking as the changes made were close to insignificant as this reduced its score to less than 1% point on each metric

## Impact on math and reading scores by grade
***Math and reading score original***

![image](https://user-images.githubusercontent.com/99924850/160305113-be59b8de-76df-4b54-b131-147034a58a6b.png)

![image](https://user-images.githubusercontent.com/99924850/160305198-97b881e5-14d9-4ca6-94a0-157da7197af9.png)

***Math and reading score updated***

![image](https://user-images.githubusercontent.com/99924850/160305245-257a74a6-e976-456e-a8f6-dabcfe06e73a.png)

![image](https://user-images.githubusercontent.com/99924850/160305268-c3401ed7-91da-4c35-814c-4e5f428f1100.png)

- There was an impact on the grade nine score which was updated to nan. The impact will be properly shown if we were to run a sum or mean of the the DataFrame.

## Impact on scores by School Spending
***Spending summary original***

![image](https://user-images.githubusercontent.com/99924850/160305975-e16109c4-2319-45f4-bced-170ed39f52c7.png)

***Spending summary updated***

![image](https://user-images.githubusercontent.com/99924850/160306021-20ffaae1-0dd0-47c9-bb23-00165d3fe9c3.png)

- There was a slight change on the spending range of 630-644 (631-645) which was the ranking of Thomas High School but then again the changes were less than 1% mostly and if we were to include the format in our code to only include only one decimal places the changes would not be visible

## Impact on scores by school size

***Scores by School Size original***

![image](https://user-images.githubusercontent.com/99924850/160306426-0a43740b-650f-43b6-9603-eb22582c15b6.png)

***Scores by School Size updated***

![image](https://user-images.githubusercontent.com/99924850/160306458-2104f37d-e408-4361-a794-c415f033e99f.png)

- There was slight change in the medium range which included the Thomas High School but again the changes were less than 1%. These changes were made because of Thomas High School students whose scores were erroneous.

## Impact on scores by school type

***School type original***

![image](https://user-images.githubusercontent.com/99924850/160306735-c77a93ad-c68d-4e58-a429-bf0cf2042be0.png)

***School type updated***

![image](https://user-images.githubusercontent.com/99924850/160306761-e05620f9-997a-4a64-9281-b2d8eb5c10f3.png)

- Thomas High School being a Charter type school,we can see some few changes on the charter school and no changes to the District type as the Thomas High School is not part of the group.

# Summary

- District Analysis: changes to all scores by less than 0.5% points or even less and no impact on school or student count
- Top school Ranking: no changes to ranking as the changes made were not great enough to change Thomas High School range although the scores were impacted slightly by 1% even less for each metric
- Scores by School Type: Changes were made to the medium grouping for all scores 
- Scores by School types : Changes were only on the Charter type as included Thomas High School to which we made changes







