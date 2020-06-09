Illinois is famous for being one of the very few states in the country with negative population growth.  The objective of this project was to Identify the key reasons for the declining population by extracting meaningful insights from unstructured text and provide actionable recommendations on what can be done to reverse this trend.
The data is a collection of a couple of months’ worth of news articles related to Chicago and/or Illinois.
The following steps were taken:
•	Clean-up the noise (eliminate articles irrelevant to the analysis)
•	Detect major topics (LDA)
•	Perform sentiment analysis to find out the top reasons for population decline 
•	Ran NLU Watson on the dataset to find out the entities (person, organization, company) in the dataset and run targeted sentiment analysis on those entities. Filtered out the entities with the positive sentiment to assist with recommendations on how city/state can attract new residents and businesses.

*the code is split into two jupyter notebooks
