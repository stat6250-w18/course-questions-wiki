
## Week 2 Quiz Questions and Answers

In order to prepare your Week 2 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-2" in your fork of this repo. Then, after all edits have been made/committed, your Week 2 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-2 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 1, Problem 1]
- Question (mresendiz3-stat6250): What must be done to ensure that SAS reads the 
correct amount of observations and variables? 
What do you do when you want more than one heading category?


[Course Textbook Chapter 1, Problem 2]
- Question (mresendiz3-stat6250): What other steps outside of DATA and PROC can 
execute discrete program sections/steps?


[Course Textbook Chapter 1, Problem 3]
- Question (mresendiz3-stat6250): Does SAS read the first couple of numbers at 
the beginning of a character variable expecting a number?
If so would it take longer to process if the number had for example 30,000 digits
and then some letters at the end making it a character variable?


[Course Textbook Chapter 1, Problem 4]
- Question (mresendiz3-stat6250): Does the period hold a numeric value in itself 
to indicate a null numeric value? What does it hold if it doesn't hold a 0/1.


[Course Textbook Chapter 1, Problem 5]
- Question (mresendiz3-stat6250): If SAS is internationally used are different
alphabets used to make variable names or is English standard across all programs?


[Course Textbook Chapter 1, Problem 8]
- Question (mresendiz3-stat6250): What if numeric variables exceed 8 bytes? Are 
the numbers omitted in the printout and stored as the real number? How would we 
be able to extend the length?


[Course Textbook Chapter 2, Problem 3]
- Question (mresendiz3-stat6250): How does SAS recognize that a four digit year 
value to be read correctly when the default is two? 
What if a study is done where a statistician needs to use 300 B.C.E? What 
should be done in order to override the default? Will a different function
need to be used?


[Course Textbook Chapter 2, Problem 7]
- Question (mresendiz3-stat6250): If PROC CONTENTS and PROC DATASETS overlap in 
function why do the two functions exist? Wouldn't it save space for SAS to only 
use one or does one potentially have a different method of functioning?


[Course Textbook Chapter 2, Problem 8]
- Question (mresendiz3-stat6250): Why does SAS only correctly represent dates 
1582 to 20,000 A.D.? 1582 seems like an arbitrary
date in my opinion and I'm curious about the reason it was chosen. 


[Course Textbook Chapter 2, Problem 9]
- Question (mresendiz3-stat6250): Is it possible to extract the files in a 
library after deleting librefs from the
operating system? How? Is there a list of what can and cannot be recovered?


[basic_recipe_for_loading_data_from_remote_Excel_file Week 2 Recipe]
- Question (mresendiz3-stat6250): If changes are made to the files belonging to 
the URL is the file within SAS updated when the URL is called? Would it be 
easier to make changes within SAS?


[bonus_advanced_recipe_for_loading_data_from_remote_Excel_file Week 2 Recipe]
- Question (mresendiz3-stat6250): Is there a limit to the amount of characters 
between the ampersand and period
(ending delimeter.) Are there array-type functions that can reduce the amount
of space when creating a macro command? If more than one macro is made how 
can SAS distinguish between different macros? Should we just use different names after %macro?

