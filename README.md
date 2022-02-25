# Kickstarter-analysis
Performing analysis on Kickstarter to uncover trends

## Overview of Project
The project consists in sort information using filtering tools, conditional formatting and data charts from a dataset in Excel.

### Purpose
The purpose of the Project is to provide information to Louise, by analyzing historical data and have a better insight on campaign funding, in order to set the campaign funding for the play called Fever.

## Analysis and Challenges
The data is found raw and some columns have combined information that could be split in different columns, for example the Category and Subcategory column. In order to have a better understanding of "Plays", it would be required to separate the information. If data is not separated the data will show as follow.

![image](https://user-images.githubusercontent.com/98929742/154858664-ec4cc45e-edd3-4355-bed8-31217ab65f5b.png)

The chart shows an overall information about Theaters, but it will not show how many "Plays" have been successful or have failed.

By separating the information of Category and Subcategory, the data will display the insight of "Plays" and the chart will show the information as follow.

![image](https://user-images.githubusercontent.com/98929742/154859030-a0b9e7c7-8a3f-494d-97e7-6a8e217bfa44.png)

Allowing to understand the outcomes of the "Plays"

### Analysis of Outcomes Based on Launch Date
![image](https://user-images.githubusercontent.com/98929742/154860213-cc82490d-0637-44c8-af44-2b6917b5adce.png)
The dates are given in Unix Timestamps, in order to display MM/DD/YY a conversion formula had to be implemented to provide an easier data to read and understand.

By filtering Theater from the data in three possible outcomes (Successful, Failed, Canceled), shows that the highest number of successful outcomes are from months May through July , and the highest being the month of May. These months take place in the beginning of the Summer and the start of vacation, were people have more leisure time.

### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/98929742/154859612-51b586bb-015b-42aa-8378-da6c4672f14b.png)
![image](https://user-images.githubusercontent.com/98929742/154859736-897f52b6-735b-4771-b718-a002e752953b.png)

The data displays the follows:

- Goals that go from less than 1,000 to 14,999 have a % Success of 64% (36% Fail).
- Goals from 15,000 to 19,000 have 50% chances to Fail or Succeed.
- The Overall Average % Success is 45%, and a Overall Average % Fail 55%.
- There are no canceled campaigns.


### Challenges and Difficulties Encountered
-Organizing and filtering big data set
-Convert Unix Timestamp, the formula is not build-in in Excel
-Countifs can be difficult to write and read

## Results

In order to have a successful campaign, Loise must have the capaign during the Months of May-July (Constitutes =~ 22% of succesful outcome vs grand total) and set a goal that is below 1,000 to have a Success Rate of 76%, or goal that ranges from 1,000 to 4,999 to have a Success Rate of 73%.

### What are two conclusions you can draw about the Outcomes based on Launch Date?
- The highest number of successful outcomes are from months May - July , and May has the highest numer of successful.
- There number of canceled outcomes is very low (Almost 3% from the total outcome)

### What can you conclude about the Outcomes based on Goals?
-High value goals (45,000 and over) are most likely to fail
-Highest successful rate is goal below 1,000

### What are some limitations of this dataset?
The data set contains a total of 4414 datapoints, where the subcategory "Play" has 1066 datapoints. This contitutes almost 26% of the entire set. Since the purpose of the analysis is to focus on "Play" the collected data should focused more on that subcategory. In addition the collected data was taken in different countries, meaning that the outcomes might be different for each country and alter the data. The data should be collected in the same place where Louise is setting the campaign. 

### What are some other possible tables and/or graphs that we could create?

This graph will help us undertand the outcomes just for the Play subcategory based on the Launch date
![TheaterPlays_Outcomes_vs_Launch](https://user-images.githubusercontent.com/98929742/154864195-e42d5eb9-5620-48a3-bd3f-d41798731843.png)

The graph will help us undertand the outcomes just for the Play subcategory
![Subcategory Chart Statistics](https://user-images.githubusercontent.com/98929742/154864199-d47c45d3-acd0-47c1-a196-46ac732606a9.png)

