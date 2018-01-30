## Week 5 Quiz Questions and Answers

In order to prepare your Week 5 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-5" in your fork of this repo. Then, after all edits have been made/committed, your Week 5 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-5 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 5, Problem 1]
Question (asharda-stat6250): How do you use a FILENAME statement?.
Answer(asharda-stat6250):When reading raw data, you can use the FILENAME statement to point to the location of the external file
that contains the data. Just as you assign a libref by using a LIBNAME statement, you assign a fileref by
using a FILENAME statement.



[Course Textbook Chapter 5, Problem 2]
Question (asharda-stat6250): Are LIBNAME and FILENAME statements global?
Answer(asharda-stat6250):Yes,LIBNAME and FILENAME statements are global.



[Course Textbook Chapter 5, Problem 6]
Question (asharda-stat6250): What is the use of INPUT statement?
Answer(asharda-stat6250):The INPUT statement creates a variable using the name that you assign to each field.



[Course Textbook Chapter 5, Problem 7]
Question (asharda-stat6250): Is Column input  appropriate in all situations.?
Answer(asharda-stat6250):Column input is appropriate only in some situations. When you use column input, your data must be standard
character and numeric values, and these values must be in fixed fields.



[Course Textbook Chapter 5, Problem 8]
Question (asharda-stat6250):  How do you re-define the values of the variable in an assignment statement?
Answer(asharda-stat6250):To re-define values of the variable in an assignment statement, one must specify the variable name on the left side of the equal sign and an appropriate expression including the variable name on the right side of the equal sign.



[Course Textbook Chapter 6, Problem 1]
Question (asharda-stat6250):  What is created at the beginning of compilation phase?
Answer(asharda-stat6250):At the beginning of the compilation phase, the input buffer (an area of memory) is created to hold a record
from the external file.



[Course Textbook Chapter 6, Problem 2]
Question (asharda-stat6250):  What does SYNTAX errors include?



[Course Textbook Chapter 6, Problem 3]
Question (asharda-stat6250):  Are variables that are created with an assignment statement in the DATA step , also added to the
program data vector.?
Answer(asharda-stat6250):Yes,Any variables that are created with an assignment statement in the DATA step are also added to the
program data vector.



[Course Textbook Chapter 6, Problem 4]
Question (asharda-stat6250):  What is the value of _ERROR_ at the beginning of the execution phase?
Answer(asharda-stat6250):Because there are no data errors, the value of _ERROR_ is 0.



[Course Textbook Chapter 6, Problem 5]
Question (asharda-stat6250):  What is the value of _ERROR_ for multiple errors?
Answer(asharda-stat6250):Whether one error or multiple errors, the value of _ERROR_ is set to 1.



[Course Textbook Chapter 6, Problem 6]
Question (asharda-stat6250):  What happens at the end of DATA step?



[basic_recipe_for_creating_analytic_datasets Week 5 Recipe]
Question (asharda-stat6250):  In addition to variable names what does a PDV also keep track of?



[adv_recipe_for_creating_analytic_datasets Week 5 Recipe]
Question (asharda-stat6250):  What is one of the drawback of using proc sql?


