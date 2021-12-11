# CallAnalysisProject

In this project, we analyze the dataset consisting of calls to the 311 phone number for non-emergency services, provided by New York City for public consumption or use.
Our dataset contains roughly 2,587,316 number of cases recorded by 311 non-emergency services within New York City during one year.
It includes 41 features such as the zip code, area, types of request, status and due date, etc. in order to better study the cases for study and public use.


## Files:

### Top10.ipynb

For the first part of the project, we chose the zip code 10019 to analyze the top 10 causes of calls in this specific area. 
We first extract the data that corresponds to our target zip code and get the total number of calls of each complaint type.
Then we get and displayed the top 10 number of complaint types in descending order the year 2020.

### Parking.ipynb

For the second part of the project, we evaluate the portion of illegal parking incidents within our zip code compared to the incidents of illegal parking across the whole city and assign this value to a boolean variable called higher_parking_proportion. If the portion of illegal parking within our selected zip code with respect to all the cases within our zip code is higher than the portion of illegal parking of all areas in New York City, then thsi value is set to True. Otherwise, it returns false.



#### Group name: Project Group 51 
#### section 02
#### Group members：
##### Muchen Liang ml4688
##### Yu-Hua Chen yc4030
