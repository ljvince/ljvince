# Module 1 Challenge -- Kickstarter's Analysis of the Results
## Overview
**the purpose of this analysis is Using the "Kickstarter dataset" to visualize the campaign outcomes，in order to present how different campaigns fared in relation to their launch dates and their funding goals，to get a better idea for the launch and fundraising**
## Analysis and Challenges
**------How to performed the analysis using images and links to code------**
###### **analysis 1-Theater_Outcomes_vs_Launch**
###### using the "excel-data-Text to Columns" in order to break down the data into more categories, therefore to grab the "Parent Category" category;
<img width="1137" alt="Screen Shot 2022-05-30 at 11 23 50 PM" src="https://user-images.githubusercontent.com/106010498/171108719-29c6d52f-109d-49c5-88a9-7583233318ba.png">
<img width="592" alt="Screen Shot 2022-05-30 at 11 23 52 PM" src="https://user-images.githubusercontent.com/106010498/171108726-64c8dea6-1db3-4693-b5c7-42fb5b563c4c.png">
<img width="587" alt="Screen Shot 2022-05-30 at 11 23 56 PM" src="https://user-images.githubusercontent.com/106010498/171108737-8ab40eaa-b0bf-4df1-b28d-77204f2fa758.png">

###### using "year()" function in order to grab "year" category;
<img width="228" alt="Screen Shot 2022-05-30 at 11 42 20 PM" src="https://user-images.githubusercontent.com/106010498/171109096-bdb3277f-1786-4cef-bab2-839d34662788.png">

###### "pivot table" is used for clear up dataset in an new sheet，making dataset ready for virtual analysis;
<img width="250" alt="Screen Shot 2022-05-30 at 11 43 42 PM" src="https://user-images.githubusercontent.com/106010498/171109273-bbdee5dc-4560-4498-9181-1ace6b710085.png">

###### "line graph" is made by month of the year in x-axis and outcomes in y-axis, in order to virtualize the value of outcome in every month;
<img width="1680" alt="Screen Shot 2022-05-30 at 11 44 50 PM" src="https://user-images.githubusercontent.com/106010498/171109422-c0623634-39b9-40a9-93a5-53b587ac9ab4.png">

###### according above, it is able to visualize "Outcomes Based on Launch Date".
<img width="890" alt="Screen Shot 2022-05-30 at 11 46 12 PM" src="https://user-images.githubusercontent.com/106010498/171109805-80c186b0-907a-43d5-a54b-28bec681dbeb.png">

###### **analysis 2-Outcomes_vs_Goals**
###### typing a column with different dollar amount ranges that the projects could be grouped based on the goal amount;
<img width="1589" alt="Screen Shot 2022-05-30 at 11 49 32 PM" src="https://user-images.githubusercontent.com/106010498/171110330-de9aba69-e942-4d71-9bb1-36d1d8b08b9a.png">

###### "COUNTIFS()"function is really good way pop up the outcomes's Number of Successful, Failed, and Canceled;
<img width="723" alt="Screen Shot 2022-05-30 at 11 51 28 PM" src="https://user-images.githubusercontent.com/106010498/171110735-04d5be2c-4e1e-4b0b-8c87-0727225195a4.png">
<img width="759" alt="Screen Shot 2022-05-30 at 11 52 28 PM" src="https://user-images.githubusercontent.com/106010498/171110748-ede07a97-4f0b-4ba1-8e38-74b2d9ea12b4.png">

###### in this case, using basic math to present total project and the value of percentage  of successful, failed, and canceled on each goal amount group;
<img width="893" alt="Screen Shot 2022-05-30 at 11 53 53 PM" src="https://user-images.githubusercontent.com/106010498/171111095-8275ec3d-8850-4796-91db-317ddff6ece7.png">
<img width="1527" alt="Screen Shot 2022-05-30 at 11 53 56 PM" src="https://user-images.githubusercontent.com/106010498/171111114-a2fa119f-9628-49c4-9d44-82dd44bbd829.png">

###### check the value infallible is very important, several kinds of examine being used to make sure the value precision;
###### "line graph" again to visualize the "Outcomes Based on Goals".

**------Challenges encountered and how to overcame them------
###### in this program, my biggest challenge is using the function "countifs", at first i did not know how to apply multiple criterial, after looking at the hint and the vedio, i succsufuly applied it and get a better idea on how to use "countifs" function.


## Results
**analysis 1-Theater_Outcomes_vs_Launch**
###### There is a higher possibility of successful when launch is during May and June.
###### The number of "canceled" is evenly distributed in each month with an exception of October which is no canceled. 
<img width="554" alt="Screen Shot 2022-05-31 at 12 05 31 AM" src="https://user-images.githubusercontent.com/106010498/171112966-ce0bb3be-a37e-4dba-958f-fa911bada56e.png">

**analysis 2-Outcomes_vs_Goals**
###### the less the goal is, the higher possibility of success. if the gaol is set too high, there is larger possibility of failed.
<img width="580" alt="Screen Shot 2022-05-31 at 12 07 01 AM" src="https://user-images.githubusercontent.com/106010498/171114175-2290e4a2-c4a9-4daa-8943-2f2b1b73817c.png">

**Limitations of this dataset**
###### The limitation is the size of the dataset is not large enough for all categories.

**Recommendation of additional tables or graphs**
###### The recommendation of graph is the histogram graph, because there is some extreme value showed in this dataset, and in this graph we can filter the extreme value in order to get more accurate result.
