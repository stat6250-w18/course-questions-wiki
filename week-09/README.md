## Week 9 Quiz Questions and Answers

In order to prepare your Week 9 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-9" in your fork of this repo. Then, after all edits have been made/committed, your Week 9 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-9 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 14, Problem 1]
- *Question*(kamirneni-stat6250): Which statements can be used with DO loop?
- *Answer*(kamirneni-stat6250): DATA steps can be used but not PROC steps.



[Course Textbook Chapter 14, Problem 2]
- *Question*(kamirneni-stat6250): What should one do to change increment value?
- *Answer*(kamirneni-stat6250): Using BY clause,and specifying the value one can change the increment value.



[Course Textbook Chapter 14, Problem 3]
- *Question*(kamirneni-stat6250): What is a purpose of INDEX statement?



[Course Textbook Chapter 14, Problem 4]
- *Question*(kamirneni-stat6250): What is the difference between using DO loop with WHILE and UNTIL clause?
- *Answer*(kamirneni-stat6250): In case of DO loop with WHILE clause, first the condition is evaluated before executing the statements within the loop. In case of DO loop with UNTIL clause, it executes at least one time because the condition is evaluated at the end of loop.



[Course Textbook Chapter 14, Problem 5]
- *Question*(kamirneni-stat6250): Does the OUTPUT statement make any difference to end DO loop in a DATA statement?



[Course Textbook Chapter 14, Problem 6]
- *Question*(kamirneni-stat6250): What is the value of index at the end of DO loop?
- *Answer*(kamirneni-stat6250): It is always one value greater than specified, but since the value exceeds the stop value, the DO loop ends.



[Course Textbook Chapter 14, Problem 7]
- *Question*(kamirneni-stat6250): When is DO UNTIL loop used?



[Course Textbook Chapter 14, Problem 8]
- *Question*(kamirneni-stat6250): Can string condition be evaluated in DO loop?



[Course Textbook Chapter 14, Problem 9]
- *Question*(kamirneni-stat6250): How does one use values at intervals of 10?
- *Answer*(kamirneni-stat6250): It can be done using POINT statement.



[Course Textbook Chapter 14, Problem 10]
- *Question*(kamirneni-stat6250): What is the function of OUTPUT statement?



[Course Textbook Chapter 15, Problem 1]
- *Question*(kamirneni-stat6250): What kind of statement is an ARRAY statement?
- *Answer*(kamirneni-stat6250): It is not, it only defines an array.



[Course Textbook Chapter 15, Problem 2]
- *Question*(kamirneni-stat6250): Where can ARRAY be used?
- *Answer*(kamirneni-stat6250): Only in DATA step, not in any other labels.



[Course Textbook Chapter 15, Problem 3]
- *Question*(kamirneni-stat6250): How does one define a string array?



[Course Textbook Chapter 15, Problem 4]
- *Question*(kamirneni-stat6250): How can one define a range of values for the index in an array?



[Course Textbook Chapter 15, Problem 5]
- *Question*(kamirneni-stat6250): What is the index value in an array?



[Course Textbook Chapter 15, Problem 6]
- *Question*(kamirneni-stat6250): What is the specific use of DIM function?



[Course Textbook Chapter 15, Problem 7]
- *Question*(kamirneni-stat6250): How to create a temporary element in an array?



[Course Textbook Chapter 15, Problem 8]
- *Question*(kamirneni-stat6250): How does one reference a specific element in an array?



[Course Textbook Chapter 15, Problem 9]
- *Question*(kamirneni-stat6250): How does one remove a temporary element?



[recipe_to_create_unique_record_id Week 9 Recipe]
- *Question*(kamirneni-stat6250): Can one array be assigned as a primary key in a multidimensional array?



[recipe_to_disaggregate_counts_data Week 9 Recipe]
- *Question*(kamirneni-stat6250): What does disaggregation accomplish and what function is used to define it?


