# Panda Challenge - PyCitySchools

## Read Me - Code Method

#### Initial work

- Import Pandas
- Load the Datasets 
- Read School and Student Data File and store into Pandas Dataframes
- Combine the data into a single dataset. 




#### District Summary

- Print the list of columns within newly combine Dataframe

- Print the list of columns from the school Dataframe

- Print the list of columns from the student Dataframe

- Print the top 5 observations to get an idea of the columns within newly combine Dataframe

- Identify my datatypes on the columns to prepare for any datatype changes that may be needed for calculations

- Check my counts to see if there is any null values

- Copy to another Dataframe for shorter name

- Count the unique number of schools and add it to array of total schools

- Count the number of students and add it to array of total students

- Sum the budget of the schools to get total budget and add it to array of total budget

- Average the number of students math scores and add it to array of average math score

- Average the number of students reading scores and add it to array of average reading score

- For a math passing score of 70 or above get the number students and get the total count

- Calculate the total % of students passing math

- For a reading passing score of 70 or above get the number students and get the total count

- Calculate the total % of students passing reading

- For a reading and math passing score of 70 or above get the number students and get the total count

- Calculate the total % of students passing overall

- Create a District Summary Dataframe to house my district summary

- Format the District Summary Dataframe


#### School Summary

- Create groupby Dataframe from the merge Dataframe to use for the school summary based on grouping of school name

- Capture school types from original school input Dataframe

- Set the index to school name

- Use groupby Dataframe to get the total students per school

- Capture the original budgets outlined in the school input Dataframe

- Set the index to school name

- Capture the budgets per student using the school budgets over the students counts

- Use groupby Dataframe to get the average math score per school

- Use groupby Dataframe to get the average math score per school

- For a math passing score of 70 or above get the number students

- Then create groupby Dataframe to get the count per school 

- Calculate the total % of students passing reading per school

- For a reading passing score of 70 or above get the number students

- Then create groupby Dataframe to get the count per school

- Calculate the total % of students passing reading per school

- For a reading and math passing score of 70 or above get the number students

- Then create groupby Dataframe to get the count per school

- Calculate the total % of students passing overall per school

- Create a School Summary Dataframe to house my school summary

- Format the School Summary Dataframe


#### Top Performing Schools (By % Overall Passing)

- Sort top performing schools by % overall passing.

- Display the top five performing schools


#### Bottom Performing Schools (By % Overall Passing)

- Sort bottom performing schools by % overall passing.

- Display the bottom five performing schools


#### Math Scores by Grade

- Capture all the 9th grade students

- Then create groupby dateframe to get the average (mean) math grade per school 

- Capture all the 10th grade students

- Then create groupby dateframe to get the average (mean) math grade per school

- Capture all the 11th grade students

- Then create groupby dateframe to get the average (mean) math grade per school 

- Capture all the 12th grade students

- Then create groupby dateframe to get the average (mean) math grade per school 

- Create Average Math Score by students grade Dataframe

- Format the Average Math Score by Grade Summary Dataframe


#### Reading Scores by Grade

- Capture all the 9th grade students

- Then create groupby dateframe to get the average (mean) reading grade per school 

- Capture all the 10th grade students

- Then create groupby dateframe to get the average (mean) reading grade per school

- Capture all the 11th grade students

- Then create groupby dateframe to get the average (mean) reading grade per school 

- Capture all the 12th grade students

- Then create groupby dateframe to get the average (mean) reading grade per school 

- Create Average Reading Score by students grade Dataframe

- Format the Average Reading Score by Grade Summary Dataframe


#### Scores by School Spending

- Use a copy of school summary

- Min and Max for Bin Ranges

- Convert my columns back to numbers to use for calculations

- Create my Bin Ranges

- Create my Bin Labels

- Create Spending Ranges (Per Student) column 

- Create a Spending Ranges groupby Dataframe

- Capture values to put in summary of spending ranges per student Dataframe

- Create Spending Range per students Summary Dataframe

- Format Spending Range per students Summary Dataframe


#### Scores by School Size

- Use a copy of school summary

- Add school size column to Dataframe

- Min and Max for Bin Ranges

- Convert my columns back to numbers to use for calculations

- Create my Bin Ranges

- Create my Bin Labels

- Create School Size column

- Create a School Size groupby Dataframe

- Capture values to put in summary of school size Dataframe

- Create School Size Summary Dataframe

- Format School Size Summary Dataframe


#### Scores by School Type

- Use copy of school summary

- Convert my columns back to numbers to use for calculations

- Create a School Type groupby Dataframe

- Capture values to put in summary of School Type Dataframe

- Create district Type School Summary Dataframe

- Format district Type School Summary Dataframe