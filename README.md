# star-wars-survey

For this project, we'll be cleaning and exploring the data set in Jupyter notebook. 

The data has several columns, including:

RespondentID - An anonymized ID for the respondent (person taking the survey)
Gender - The respondent's gender
Age - The respondent's age
Household Income - The respondent's income
Education - The respondent's education level
Location (Census Region) - The respondent's location
Have you seen any of the 6 films in the Star Wars franchise? - Has a Yes or No response
Do you consider yourself to be a fan of the Star Wars film franchise? - Has a Yes or No response
There are several other columns containing answers to questions about the Star Wars movies. For some questions, the respondent had to check one or more boxes. This type of data is difficult to represent in columnar format. As a result, this data set needs a lot of cleaning.

First, we'll need to remove the invalid rows. For example, RespondentID is supposed to be a unique ID for each respondent, but it's blank in some rows. we'll need to remove any rows with an invalid RespondentID.
