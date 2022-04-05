# jobposting_dataset_analysis
The dataset contains more than 3900 jobs listing for data scientist positions, with features such as Salary Estimate, Location, Company Rating, Job Description, and other information about the position. 3909 job listing for data scientist roles scraped from glassdoor.


# Dataset is avalibe from:
- https://www.kaggle.com/rohitsahoo/data-scientist-jobs-analysis/data
- https://www.kaggle.com/samruddhim/analysis-of-data-scientist-jobs/data


# Purpose of the task
Analysis is helpful for both the candidate and the company. 

# Preparation of a data set
The dataset has been cleared, operations such as:
- deleting missing lines, 
- deleting items that contain drainage lines but are not works in the it area, e.g. science labs, which are intended for employees of chemical departments, have been performed.
- word replacement in numerical form, e.g. company size small: 1, medium: 2, large: 3
- grouping titles into groups, e.g. jr., jr., jr, jr. from junior to one junior gurper
- other...


# Analysis dataset:
- Top programming languages requrired by the companies
- Top Big Data Technologies requrired by the companies
- Experience/Education requrired by the companies
- other top skills required by companies
- Top 10 najpopularniejszych tytułów zawodowych
- the most common words in the job offer
- junior earnings
- other ...


#Prediction:
Based on information about:
• information about the position
• the company - information about the company's size and stability (functioning
on the market in years),
• candidate profile - information on experience in years, degrees
scientific.

#Dataset. for perdiction:
Size:
- 1: a small company with 1 to 50 employees and 51 to 200 employees,
- 2: medium company with 201 to 500 employees and from 501 to 1,000 employees,
- 3: a large company with 1001 to 5000 employees, from 5001 to 10,000 employees and 10,000+ employees.


Level of education:
- 1: bachelor degree
- 2: Master degree 
- 3: PhD - doktor.


Experience:
- Junior: 1 years of experience
- Middle: 3 years of experience
- Senior: 5 years of experience
- Lead i Head: 3 years of experience
- Researcher: 5 years of experience


Cat: 
(This cat is converted into numerous ads name. Based on the available announcements, five levels of IT skills have been selected)
- 1: Junior, Intern, Internship - novice programmer
- 2: Middle - medium level of knowledge.
- 3: Senior - advanced level of knowledge.
- 4: Lead i Head - the main person in charge of the team, advanced level of knowledge in programming
- 5: Researcher - researcher, advanced level of knowledge.

# Prediction - used models:
- Linear Regression 
- Logic Regression 
- Support Vector Regression 
- Random Forest Regressor
