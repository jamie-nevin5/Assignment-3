# Assignment-3


Instructor: Melissa Laurino
Spring 2024

Name: Jamie Nevin

Date: 02/08/24

We introduced in Assignment #2 the imporatance of data cleaning and why accurrate data is needed when making informed decisions in our field. In our assignment, we were faced with making the decision whether or not to omit data we may not know too much about yet.
Metadata is data about the data. Metadata can be structural, administrative, statistical and much more.
When building your data warehouses it is important to have data cleaning protocols established for your organization BEFORE you start to clean the data.

Your task for Assignment #3 is to:
--Create a Github repository for this class. It can be public or private. If you choose to make it private, add the instructor as a collaborator. @MelissaLaurino
--Staying Connected -> Visit the Discussion Board and share your username with classmates if you are interested.
--Upload Assignment #1, #2, and your clean data (If you created a physical clean copy of it, otherwise the link is fine) to your new/established Github repository. For every repository you create, you'll automatically have the option to include a README.md (Meta data) file.
--Create a descriptive and very detailed README.md file for your dataset you have chosen to continue with. Insert a link to your Github README.md repository file in the comments section on Blackboard, or attach this assignment for submission.

Include all of the following information on your README.md file for full credit. Be specific!:
More research may be needed on your dataset, besides general exploration, to answer the different types of metadata questions. If you are exploring your data at a greater depth to answer these questions, you can explore on this new document or continue working in Assignment #2.
(Refer to the Powerpoint notes on Blackboard for examples and guidance.)

Data Science Salaries Data:

Where is the data from? ​
This dataset is from Keggle.com. A free website that has a bunch of free datasets to access. 

How was it collected?​
This data was collected by looking at the salaries of data scientists over the last 5 years (2020-2024). 

How was it extracted?​
The data set was extracted from ai-jobs.net. 

What program was used to clean the data?​
R was used to clean the data set. 

How was the data cleaned or transformed? Be specific.​
The data was cleaned by removing duplicates, making sure all the data columns are the right class, made sure all the column were lowercase, checked for outlers, removed any duplicates, made sure data that should be consistent was consistent, and arranged the salary category by descending order. 
What are the units of the numeric data?​
salary- money
salary_in_usd- U.S. money
work_year- year

What were the formulas used in column creation?​
The data provider does not give details on the formulas used to create the column however according to the columns provided, it looks like he used data/time operation, 

How is the data validated to ensure consistency?​
The data was cleaned throughly, as visalize by creating a couple graphs to visualize the data. 

What are the definitions for the column names? Include all columns in your dataset.​
job_title- the name of the job that is in data science
experience_level- how experienced the job is 
employment_type- how many hours the job is (full-time/part-time)
work_models- where the person works remote, on-site, or hybrid
work_year- what year the salary was collected
employee_residence- what country the worker lives
salary- how much money was earned that year
salary_currency- what country the money is in.
salary_in_usd- what the salsry would be if comverted into US dollars.
company_location- what country the company is located
Company_size- how big the company is in terms of size 

If there are set variable options in your dataset, what are thier definitions? ​
Experience level
    Entry-level- just starting out in the job and practically no experience
    Mid-level- some experience, but not much
    Senior-level- very experienced
    Executive-level- well experienced and most likely oversee or is a boss
Employment Type
    Full-time- working 35-40 hours a week
    Part-time- working 34 or less hours
Work Models
    Remote- works from home
    On-site- has an office at the comapny and works there
    Hybrid- works from home about 50% and at the office about 50%
Company Size- the creator does not specify nor does ai-jobs.net about how many people classify in a small, medium and large company size, therefore this column should probably be omitted. However, these are ranges I found on a different job site, Indeed. 
    Small- having no more than 1,500 employees and an annual revenue of $38.5 million at most
    Medium- employ between 1,500 and 2,000 people and have annual revenue between $38.5 million and $1 billion.
    Large- their size and ability to dominate a particular market means that they produce the majority of total revenue when taking
    into account all business sizes in the U.S.
    
What are the regulations to using the data? 
This is public information found from job listings on a public website, therefore this is all public data. 
If you are referencing sources, be sure to include citations/references as needed.
Works Cited:
    Jobs and talents in AI, ML, data science and Big Data. ai-jobs. (n.d.). https://ai-jobs.net/?key=&exp=EN 
    
    Islam, S. (2024, January 20). Data Science salaries 2024. Kaggle. https://www.kaggle.com/datasets/sazidthe1/data-science-salaries/data 
    
    Indeed Editorial Team. (n.d.). Business sizes: Classifications and characteristics | indeed.com. Indeed. https://www.indeed.com/career-advice/career-development/business-sizes 
