## Week 9 Quiz Questions and Answers

In order to prepare your Week 9 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-9" in your fork of this repo. Then, after all edits have been made/committed, your Week 9 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-9 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 14, Problem 1]
- Question (nshrivastava2-stat6250): What is the use of Do Loop?
- Answer(nshrivastava2-stat6250): DO loops process groups of SAS statements repeatedly, reducing the number of statements that are required in repetitive calculations. 



[Course Textbook Chapter 14, Problem 2]
- Question (nshrivastava2-stat6250): How the Do Loop iteration executes?
- Answer(nshrivastava2-stat6250): During each iteration of a DO loop, new values are created in the SAS program data vector. When the loop's index value exceeds the stop value, the DO loop stops, and processing continues with the following DATA step statement



[Course Textbook Chapter 14, Problem 3]
- Question (nshrivastava2-stat6250): To construct an iterative DO loop, What are the conditions an index variable execute the loop?



[Course Textbook Chapter 14, Problem 4]
- Question (nshrivastava2-stat6250): Can we create labels for numaric series using Do loops.
- Answer(nshrivastava2-stat6250): SAS programmers often need to create labels for a numbered series of variables with a common prefix. Array and DO loops can not be used here since the LABEL statement is a declarative statement.



[Course Textbook Chapter 14, Problem 5]
- Question (nshrivastava2-stat6250): What is the syntax for Do Loop in SAS?



[Course Textbook Chapter 14, Problem 6]
- Question (nshrivastava2-stat6250): What is the role of BY clause in Do Loops statement?
- Answer(nshrivastava2-stat6250): The optional BY clause specifies an increment value for the index variable. Typically, you want the DO loop to increment by 1 for each iteration. If you do not specify a BY clause, the default increment value is 1.



[Course Textbook Chapter 14, Problem 7]
- Question (nshrivastava2-stat6250): To create an observation for each iteration of the DO loop, what statement be use?
- Answer(nshrivastava2-stat6250): To create an observation for each iteration of the DO loop, place an OUTPUT statement inside the loop. By default, every DATA step contains an implicit OUTPUT statement at the end of the step. But placing an explicit OUTPUT statement in a DATA step overrides automatic output, causing SAS to add an observation to the data set only when the explicit OUTPUT statement is executed. 



[Course Textbook Chapter 14, Problem 8]
- Question (nshrivastava2-stat6250): What is Nesting DO Loops ? Will the nested DO Loops, be a performance issues?



[Course Textbook Chapter 14, Problem 9]
- Question (nshrivastava2-stat6250): What is the overview of conditionally executing DO Loops? Name them? 



[Course Textbook Chapter 14, Problem 10]
- Question (nshrivastava2-stat6250): When we use the Do WHILE statement?
- Answer(nshrivastava2-stat6250):  You can use the DO WHILE statement to execute a DO loop while the expression is true. 



[Course Textbook Chapter 15, Problem 1]
- Question (nshrivastava2-stat6250): What is the difference between one-Dimensional and multi-Dimentional Arrays?



[Course Textbook Chapter 15, Problem 2]
- Question (nshrivastava2-stat6250): How to use arrays to recode set of variables?



[Course Textbook Chapter 15, Problem 3]
- Question (nshrivastava2-stat6250): How to use arrays to recode all the numeric variables?



[Course Textbook Chapter 15, Problem 4]
- Question (nshrivastava2-stat6250): Describe 5 Ways To Do A "table Lookup" In Sas?
- Answer(nshrivastava2-stat6250): Match Merging,Direct Access,Format Tables,Arrays,PROC SQL.



[Course Textbook Chapter 15, Problem 5]
- Question (nshrivastava2-stat6250): What is the better way of substituting one value for another in a group of variables
- Answer(nshrivastava2-stat6250): There are many ways but one better way by using an array to represent a list of variables, or elements where SAS system allows to perform an operation, or a set of operations, on the entire list by referring to the array.



[Course Textbook Chapter 15, Problem 6]
- Question (nshrivastava2-stat6250): How we specify an array element in SAS?



[Course Textbook Chapter 15, Problem 7]
- Question (nshrivastava2-stat6250): How DIM functions works using array?
- Answer(nshrivastava2-stat6250): One of the most common tasks involving arrays is to iterate (or, to loop) through each element of an array by using a DO group and then performing an operation on each element.The DIM function presents a more dynamic way to determine the STOP argument.



[Course Textbook Chapter 15, Problem 8]
- Question (nshrivastava2-stat6250): What are the commonly used functions in Array?
- Answer(nshrivastava2-stat6250): SAS has many functions and operators that you can use with arrays to perform common tasks. 



[Course Textbook Chapter 15, Problem 9]
- Question (nshrivastava2-stat6250): Defining a numbered range of variables using array?
- Answer(nshrivastava2-stat6250): The variables must have the same name except for the last character or characters. The last character of each variable must be numeric. The variables must be numbered consecutively.



[recipe_to_create_unique_record_id Week 9 Recipe]
- Question (nshrivastava2-stat6250): How to pad character variable with leading zeroes?
- Answer(nshrivastava2-stat6250): We can do so by uising Z4. format to add leading zeroes.



[recipe_to_disaggregate_counts_data Week 9 Recipe]
- Question (nshrivastava2-stat6250): Why is the initianlzation process relevant when no retain statement is involved?


