# Project 1: SAT & ACT Analysis
## Problem Statement
This data science problem involves identifying likely factors influencing SAT and ACT participation rates and scores in various states of America. We will be taking a look at aggregate SAT and ACT scores and participation rates from each state in the United States. The aim of this data science project is to make recommendations about how the SAT College Board might work to increase the participation rate in a state with low participation rate.
## Executive Summary
### Contents:
- [2017 Data Import & Cleaning](./code/starter-code.ipynb#Data-Import-and-Cleaning)
- [2018 Data Import and Cleaning](./code/starter-code.ipynb#2018-Data-Import-and-Cleaning)
- [Exploratory Data Analysis](./code/starter-code.ipynb#Exploratory-Data-Analysis)
- [Data Visualization](./code/starter-code.ipynb#Visualize-the-data)
- [Descriptive and Inferential Statistics](./code/starter-code.ipynb#Descriptive-and-Inferential-Statistics)
- [Outside Research](./code/starter-code.ipynb#Outside-Research)
- [Conclusions and Recommendations](./code/starter-code.ipynb#Conclusions-and-Recommendations)
## Data Dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
|**state**|_object_|2017 SAT Scores<br>2017 ACT Scores<br>2018 SAT Scores<br>2018 ACT Scores|50 states and the federal district (Washington, D.C.) of the United States.|
|**sat_2017_participation**|_float_|2017 SAT Scores|The participation rate of the 2017 SAT in each state.|
|**sat_2017_evidence-based_reading_and_writing**|_integer_|2017 SAT Scores|The average score for the 2017 SAT Evidence-Based Reading and Writing section in each state.|
|**sat_2017_math**|_integer_|2017 SAT Scores|The average score for the 2017 SAT Math section in each state.|
|**sat_2017_total**|_integer_|2017 SAT Scores|The average total score for the 2017 SAT in each state.|
|**act_2017_participation**|_float_|2017 ACT Scores|The participation rate of the 2017 ACT in each state.|
|**act_2017_english**|_float_|2017 ACT Scores|The average score for the 2017 ACT English test in each state.|
|**act_2017_math**|_float_|2017 ACT Scores|The average score for the 2017 ACT Math test in each state.|
|**act_2017_reading**|_float_|2017 ACT Scores|The average score for the 2017 ACT Reading test in each state.|
|**act_2017_science**|_float_|2017 ACT Scores|The average score for the 2017 ACT Science test in each state.|
|**act_2017_composite**|_float_|2017 ACT Scores|The average composite score for the 2017 ACT in each state.|
|**sat_2018_participation**|_float_|2018 SAT Scores|The participation rate of the 2018 SAT in each state.|
|**sat_2018_evidence-based_reading_and_writing**|_integer_|2018 SAT Scores|The average score for the 2018 SAT Evidence-Based Reading and Writing section in each state.|
|**sat_2018_math**|_integer_|2018 SAT Scores|The average score for the 2018 SAT Math section in each state.|
|**sat_2018_total**|_integer_|2018 SAT Scores|The average total score for the 2018 SAT in each state.|
|**act_2018_participation**|_float_|2018 ACT Scores|The participation rate of the 2018 ACT in each state.|
|**act_2018_english**|_float_|2018 ACT Scores|The average score for the 2018 ACT English test in each state.|
|**act_2018_math**|_float_|2018 ACT Scores|The average score for the 2018 ACT Math test in each state.|
|**act_2018_reading**|_float_|2018 ACT Scores|The average score for the 2018 ACT Reading test in each state.|
|**act_2018_science**|_float_|2018 ACT Scores|The average score for the 2018 ACT Science test in each state.|
|**act_2018_composite**|_float_|2018 ACT Scores|The average composite score for the 2018 ACT in each state.|
## Conclusions and Recommendations
- SAT and ACT are substitutes for one another.
- A greater number of states have high participation rates in ACT than SAT.
- Participation rates are highly influenced by state and local education policies.
- For states such as Oregon with a lower participation rate, SAT and ACT are usually optional and not part of the standard school curriculum. Therefore, students have to prepare for the test using their own resources. One suggestion for the SAT College Board would be to provide high quality, easily accessible test prep materials that are free or at reduced-cost. This will attract students who cannot afford tutors or classes to prepare for SAT instead of ACT given the lower cost barrier to entry. Students from states with mandatory ACT testing may also be encouraged to attempt SAT when test prep materials are readily available.
- Additional data that would be helpful include students who have taken both SAT and ACT, and whether the state subsidizes the cost of the test.
