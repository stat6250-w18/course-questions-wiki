## Week 9 Quiz Questions and Answers

In order to prepare your Week 9 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-9" in your fork of this repo. Then, after all edits have been made/committed, your Week 9 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-9 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 14, Problem 1]
- *Question* (akrishnamurthy-stat6250): Can DO loops include DATA and PROC steps?



[Course Textbook Chapter 14, Problem 2]
- *Question* (akrishnamurthy-stat6250): What is the significance of index variable in a DO loop?



[Course Textbook Chapter 14, Problem 3]
- *Question* (akrishnamurthy-stat6250): How should the index variables be defined for nested DO loops?



[Course Textbook Chapter 14, Problem 4]
- *Question* (akrishnamurthy-stat6250): Should index variables always be incremented by 1? How to define list of values for index variables?



[Course Textbook Chapter 14, Problem 5]
- *Question* (akrishnamurthy-stat6250): Will the DO loop stop iteration once the stop value is reached for index variable or after the stop value?



[Course Textbook Chapter 14, Problem 6]
- *Question* (akrishnamurthy-stat6250): How to generate observation for each iteration of a DO loop? Is Output a default option for DO loop?



[Course Textbook Chapter 14, Problem 7]
- *Question* (akrishnamurthy-stat6250): What is the difference between DO While and DO Until statements?
- *Answer* (akrishnamurthy-stat6250): The DO Until condition is evaluated at the bottom of the loop and hence the statements are always executed atleast once.When the expresssion is true, the DO loop stops. The DO WHILE loop is evaluated at the top of the loop and hence if the expression is false for the first time itself, the loop never executes.



[Course Textbook Chapter 14, Problem 8]
- *Question* (akrishnamurthy-stat6250): How to execute a DO loop when the iterations are not fixed and depends on a condition?



[Course Textbook Chapter 14, Problem 9]
- *Question* (akrishnamurthy-stat6250): How should the index variable be defined for a DO WHILE loop?



[Course Textbook Chapter 14, Problem 10]
- *Question* (akrishnamurthy-stat6250): How to use conditional clauses with the iterative DO statement?



[Course Textbook Chapter 15, Problem 1]
- *Question* (akrishnamurthy-stat6250): What is the use of ARRAY statement?
- *Answer* (akrishnamurthy-stat6250): Arrays are used to simplify the code needed to perform repetitive calculations,create many variables with same attributes,read data,rotate SAS datasets by changing variables to observations or observation to variables,compare variables,table lookups.



[Course Textbook Chapter 15, Problem 2]
- *Question* (akrishnamurthy-stat6250): Is it mandatory to specify the array length while defining the array ?



[Course Textbook Chapter 15, Problem 3]
- *Question* (akrishnamurthy-stat6250): While referencing an array element using DO loop index variable, should the stop value of index variable be equal to array length?"



[Course Textbook Chapter 15, Problem 4]
- *Question* (akrishnamurthy-stat6250): Can the dimension of array and array elements be defined as range of values?
- *Answer* (akrishnamurthy-stat6250): Yes, the array dimension can be specified as a range like array{4-7}. The array elements can also be defined as variable list. The variable list can be a numbered range of variables, all numeric, all character, all character or numeric types.



[Course Textbook Chapter 15, Problem 5]
- *Question* (akrishnamurthy-stat6250): How to process all the array elements without explicitly specifying the array length?



[Course Textbook Chapter 15, Problem 6]
- *Question* (akrishnamurthy-stat6250): What are the rules for creating a numbered range of array variables?



[Course Textbook Chapter 15, Problem 7]
- *Question* (akrishnamurthy-stat6250): What is the use of temporary arrays and how to define a temporary array?



[Course Textbook Chapter 15, Problem 8]
- *Question* (akrishnamurthy-stat6250): How to reference the elements of multi dimensional array?



[Course Textbook Chapter 15, Problem 9]
- *Question* (akrishnamurthy-stat6250): Instead of initializing entire array, is it possible to initialize specific array elements?



[recipe_to_create_unique_record_id Week 9 Recipe]
- *Question* (akrishnamurthy-stat6250): What does the format z6 signify?



[recipe_to_disaggregate_counts_data Week 9 Recipe]
- *Question* (akrishnamurthy-stat6250): What is the use of RETAIN statement?


