## Week 9 Quiz Questions and Answers

In order to prepare your Week 9 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-9" in your fork of this repo. Then, after all edits have been made/committed, your Week 9 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-9 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 14, Problem 1]
- *Question* (cli19−stat6250): What can be used instead to run DATA and PROC steps iteratively?
- *Answer* (cli19−stat6250): MACROS can be written to process and automate some repetitive DATA and PROC steps.



[Course Textbook Chapter 14, Problem 2]
- *Question* (cli19−stat6250): Within a DO loop, is it possible to skip values in the iteration range specified?
- *Answer* (cli19−stat6250): Yes, you can include the BY option after the statement's stop value to specify by what value to increment each step.



[Course Textbook Chapter 14, Problem 3]
- *Question* (cli19−stat6250): How else can the start and stop values in a DO statement be incremented, if not with the BY option?



[Course Textbook Chapter 14, Problem 4]
- *Question* (cli19−stat6250): How does SAS know it has reached the end of a DO loop?
- *Answer* (cli19−stat6250): When the value that is next incremented falls outside the stop value, the DO loop ends.



[Course Textbook Chapter 14, Problem 5]
- *Question* (cli19−stat6250): What are the differences in output data sets when the OUTPUT statement is included versus when it is not?



[Course Textbook Chapter 14, Problem 6]
- *Question* (cli19−stat6250): Why isn't the "value" variable defined in DATA step reassigned to 2000 for every row in the output data set?



[Course Textbook Chapter 14, Problem 7]
- *Question* (cli19−stat6250): When would a non-iterative DO group be useful?



[Course Textbook Chapter 14, Problem 8]
- *Question* (cli19−stat6250): What is the minimum number of times enclosed statements within a DO UNTIL condition executed?
- *Answer* (cli19−stat6250): Since the condition is evaluated at the bottom of the loop, the enclosed statement within a DO UNTIL condition is executed at least one time.



[Course Textbook Chapter 14, Problem 9]
- *Question* (cli19−stat6250): What are the tradeoffs to using DO UNTIL versus DO WHILE?



[Course Textbook Chapter 14, Problem 10]
- *Question* (cli19−stat6250): When is it best to specify the start and stop values if a WHILE or UNTIL condition is specified in the DO loop?



[Course Textbook Chapter 15, Problem 1]
- *Question* (cli19−stat6250): What is the purpose in first defining an array?



[Course Textbook Chapter 15, Problem 2]
- *Question* (cli19−stat6250): Is there a way for an array to automatically detect the number of elements?



[Course Textbook Chapter 15, Problem 3]
- *Question* (cli19−stat6250): What does the number in curly brackets of an array represent?
- *Answer* (cli19−stat6250): It represents the position of the array elements.



[Course Textbook Chapter 15, Problem 4]
- *Question* (cli19−stat6250): At what value does SAS begin its index count?
- *Answer* (cli19−stat6250): SAS starts its count at 1.



[Course Textbook Chapter 15, Problem 5]
- *Question* (cli19−stat6250): What does the DIM function do? Can this function be used outside of an array?



[Course Textbook Chapter 15, Problem 6]
- *Question* (cli19−stat6250): Do varaibles need to be identified as either numeric or character before they are created in an array?



[Course Textbook Chapter 15, Problem 7]
- *Question* (cli19−stat6250): Is the output from an array written out to the final data set immediately?



[Course Textbook Chapter 15, Problem 8]
- *Question* (cli19−stat6250): How are values in a temporary array delimited?
- *Answer* (cli19−stat6250): Values are delimited by commas or spaces.



[Course Textbook Chapter 15, Problem 9]
- *Question* (cli19−stat6250): When utilizing arrays to transpose data, when does it have an upperhand over PROC TRANSPOSE?



[recipe_to_create_unique_record_id Week 9 Recipe]
- *Question* (cli19−stat6250): How are values concatenated?
- *Answer* (cli19−stat6250): Values can be contatenated using two pipe symbols (||). 



[recipe_to_disaggregate_counts_data Week 9 Recipe]
- *Question* (cli19−stat6250): Can a single RETAIN statements be used to specify order of variables and to preserve variable values between DATA step iterations?


