# ValueOfCollege

## Project Proposal
It is traditionally thought that earning a 4 year degree is the best way to have a successful career.  While this may have been true historically, we believe that this may not be the best value within the IT career track.  We propose to analyze data to determine what the true value of a bachelor’s degree is versus getting specific certifications and/or technical school degrees.


## Team Members:
Alex Martinez  
Howard Mayorga  
Christina Gangi


## Project Description/Outline
Null Hypothesis:
Getting a 4 year degree in IT is the best value in Florida  
Alternate Hypothesis:
Getting a certificate/technical degree in IT is a better investment in Florida  



## What is the cost of tuition for each of the education levels?
The following graph shows the cost of each degree from a Florida school.  
Our data listed the cost per year and we assumed an Associate's degree requires 2 years and a Bachelor's degree requires 4.  
As expected the Bachelor's degree is more expensive overall.  

![fig1](/Images/Stat_Analysis.png)

## What is the average annual salary for all IT occupations?  
There is a wide variance across IT occupations with the median around $70k annualy.
![annual_salaries](/Images/Annual_salaries.png). 

This is the median of all median IT occupations.  

![annual_salaries](/Images/Median_salary_all.png)


## What is the average distribution for education requirments for all IT occupations?
Over 50% of the IT occupations have at least a bachelor's degree. However, there is a good amount of current position holders in the IT field with a Highschool diploma or less.  

![annual_salaries](/Images/Pie_distribution.png)

## What is the average return on each education level within the IT field?  

![fig2](/Images/Box_Plot.png)  

![fig3](/Images/ROI_line_plot.png)  

## Research questions to answer:
Scope: IT Field in Florida  
Is a 4 year degree a better investment vs a technical/certificate degree in Florida?  
What is the cost of a 4 year degree?  
What is the cost of a non-bachelor program?  
How are the jobs available distributed between bachelor degrees required vs not required?  
How are salary changes divergent or inline for certain periods of career?(first 10 years, next 10? etc)  
Is there any difference based on career type/level?  
How does long term salary growth vary between the two (Bachelor vs Certificate)?  


## Datasets to be used:
College Scorecard - University data and data by field of study:  
https://collegescorecard.ed.gov/data/documentation/

Career One Stop - List of occupations with salary information and education requirements:  
https://www.careeronestop.org/Developers/WebAPI/Certifications/list-certifications.aspx
* Returns Salary & education requirements for a given occupation: https://api.careeronestop.org/api-explorer/home/index/Occupations_GetOccupationDetails


## Datasets Not Use
### JSON APIs
CollegeAI: salary post graduation and tuition cost data  
https://collegeai.com/

### CSV Files
Cost of tuition for Florida State Universities  
https://www.flbog.edu/universities/parents-students/tuition-fees/

Career Levels:  
https://www.kaggle.com/wsj/college-salaries

### xls Files
Salary based on position:  
https://www.bls.gov/oes/2018/may/oes_fl.htm


## Analysis Questions
* What is the cost of tuition for each of the education levels?
* What is the average annual salary for all IT occupations?
* What is the average distribution for education requirments for all IT occupations?
* What is the average return on each education level within the IT field?


## Rough breakdown of tasks:
1. Gather data sets for analysis  
1. Clean  
1. Breakdown tuition costs for a 4 year degree program vs. certificate cost in Florida.  
1. Look into careers in the computer data science field.  
1. Compare success rates  


## Next Steps:
* Combine all data clean up logic into 1 jupyter notebook. -- **Christina**
* Distribute workload.
* Analyze data and create visualizations.
  * Cost of tuition -- **Howard**
  * Annual Salary -- **Alex**
  * Distribution for education requirments -- **Christina**
  * Average return -- **Do together**
* Combine all visualization logic into 1 jupyter notebook file.
* Save visualizations as .png files & add to the README file.
* Summarize findings in README file.
* Create power point presentation.
* Clean up the old notebooks from the repository.


