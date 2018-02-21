## Week 8 Quiz Questions and Answers

In order to prepare your Week 8 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-8" in your fork of this repo. Then, after all edits have been made/committed, your Week 8 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-8 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 13, Problem 1]
- *Question*(kamirneni-stat6250): Can the arguments of mean function be imported by some other way apart from a variable list?
- *Answer*(kamirneni-stat6250): Yes, the variables can be referenced by an array.



[Course Textbook Chapter 13, Problem 2]
- *Question*(kamirneni-stat6250): Under what circumstances, does SAS convert character into numeric value?



[Course Textbook Chapter 13, Problem 3]
- *Question*(kamirneni-stat6250): When converting data, what is the result if one forgets to skip the INPUT function?
- *Answer*(kamirneni-stat6250): SAS detects the mismatched variables and tries an automatic character to numeric conversion or vice versa. This process is not always successful. It is recommended to include INPUT and PUT function.



[Course Textbook Chapter 13, Problem 4]
- *Question*(kamirneni-stat6250): What happens if one creates a variable in the PUT function?
- *Answer*(kamirneni-stat6250): It creates a character variable whose length is equal to the format width.



[Course Textbook Chapter 13, Problem 5]
- *Question*(kamirneni-stat6250): How is the MDY function efficient?



[Course Textbook Chapter 13, Problem 6]
- *Question*(kamirneni-stat6250): What are the specifications of INTNX function?
 

 
[Course Textbook Chapter 13, Problem 7]
- *Question*(kamirneni-stat6250): What is the maximum number of delimiters that can be used in a SCAN function?



[Course Textbook Chapter 13, Problem 10]
- *Question*(kamirneni-stat6250): What is the criteria of using the pre-defined functions in nested functions?



[recipe_for_isolating_all_duplicates Week 8 Recipe]
- *Question*(kamirneni-stat6250): How is isolating the duplicates more efficient from PROC SORT function?



[recipe_for_drop_and_swap Week 8 Recipe]
- *Question*(kamirneni-stat6250): What are the implications of removing all characters from values of a variable?


