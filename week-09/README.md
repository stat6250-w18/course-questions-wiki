## Week 9 Quiz Questions and Answers

In order to prepare your Week 9 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-9" in your fork of this repo. Then, after all edits have been made/committed, your Week 9 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-9 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 14, Problem 1]
- Question (ttruong59-stat6250): Can DO loops be used to combine DATA and PROC steps?
- Answer (ttruong59-stat6250): No. DO loops are DATA step statements and can’t be used to combine with PROC steps. 



[Course Textbook Chapter 14, Problem 2]
- Question (ttruong59-stat6250): Is it possible that the value of the index can be changed within the loop?
- Answer (ttruong59-stat6250): Yes. A DO loop enables users to achieve the same results with fewer statements and the value of the index can be changed within the loop.



[Course Textbook Chapter 14, Problem 3]
- Question (ttruong59-stat6250): What happens if users do not include END statement in DO loop along with other SAS statements?



[Course Textbook Chapter 14, Problem 4]
- Question (ttruong59-stat6250): How to specify increments the index variable by even numbers?



[Course Textbook Chapter 14, Problem 5]
- Question (ttruong59-stat6250): When does OUTPUT statement write observations?
- Answer (ttruong59-stat6250): The OUTPUT statement writes the current observations to a SAS dataset immediately, not a the end of the DATA step. But the observation will be written to the dataset listed if no dataset name is specified.



[Course Textbook Chapter 14, Problem 6]
- Question (ttruong59-stat6250): Is the number of observations based on the number of times the OUTPUT statement executes?
- Answer (ttruong59-stat6250): Yes. The number of observations is based on the number of times the OUTPUT statement executes



[Course Textbook Chapter 14, Problem 7]
- Question (ttruong59-stat6250): Is it possible to run DO loops within another DO loops?
- Answer (ttruong59-stat6250): Yes. DO loops can run within DO loops as long as users assign a unique variable to each loop and terminate each DO loop with its own END statement.



[Course Textbook Chapter 14, Problem 8]
- Question (ttruong59-stat6250): How does the DO UNTIL statement execute a DO loop?
- Answer (ttruong59-stat6250): The DO UNTIL statement executes the DO loop until the specified condition is true. 



[Course Textbook Chapter 14, Problem 9]
- Question (ttruong59-stat6250): What is a major difference between DO UNTIL and DO WHILE statement?
- Answer (ttruong59-stat6250): DO WHILE is evaluated at the top of the DO loops and if the expression is initially false, DO loop never executes. On the other hand, DO UNTIL is not evaluated until the end of the loop so DO UNTIL executes at least once. 



[Course Textbook Chapter 14, Problem 10]
- Question (ttruong59-stat6250): Can DO WHILE statements be used within iterative DO loops to combine conditional and unconditional execution?
- Answer (ttruong59-stat6250): Yes. DO WHILE statements can be used within iterative DO loops to combine conditional and unconditional execution



[Course Textbook Chapter 15, Problem 1]
- Question (ttruong59-stat6250): What is an ARRAY statement?
- Answer (ttruong59-stat6250): An ARRAY is a temp grouping of SAS variables under a single name and is not an executable statement.



[Course Textbook Chapter 15, Problem 2]
- Question (ttruong59-stat6250): How to specify a dimension in an ARRAY statement?
- Answer (ttruong59-stat6250): There are a few ways to do this. One way is to simply specify the number of array elements in term of a one-dimensional array. Typically array elements are the variables users want to reference and process elsewhere in the DATA step.



[Course Textbook Chapter 15, Problem 3]
- Question (ttruong59-stat6250): Can we add a DO statement to process all elements in the array?
- Answer (ttruong59-stat6250): Yes. In the DO statement, we need to specify the index variable to represents the values of the array elements, then specify the start and stop positions of the array elements.



[Course Textbook Chapter 15, Problem 4]
- Question (ttruong59-stat6250): How to specify the range of variables in the array?



[Course Textbook Chapter 15, Problem 5]
- Question (ttruong59-stat6250): Is it true that the variables must be numbered consecutively?



[Course Textbook Chapter 15, Problem 6]
- Question (ttruong59-stat6250): Are variables added to the program data vector during the compilation of the DATA step?



[Course Textbook Chapter 15, Problem 7]
- Question (ttruong59-stat6250): Based on the solution in the textbook, the correct answer is 15 which is the value of diff{i} at the end second iteration of the DO loop as diff{2}=215-200. What happens if the second iteration of the DO loop is a missing blank? 



[Course Textbook Chapter 15, Problem 8]
- Question (ttruong59-stat6250): Is it possible to assign initial values to an array without specifying each array elements?



[Course Textbook Chapter 15, Problem 9]
- Question (ttruong59-stat6250): What is a major reason to create temp array elements?



[recipe_to_create_unique_record_id Week 9 Recipe]
- Question (ttruong59-stat6250): Assuming school_record_ID is defined as char e.g. school_record-AB0001, how do we set a unique school ID with the string “school_record-AB” if _N_=42?



[recipe_to_disaggregate_counts_data Week 9 Recipe]
- Question (ttruong59-stat6250): Why do we use RETAIN statements in the DO loop for this recipe? Is it mainly because we like to override the default values? 



