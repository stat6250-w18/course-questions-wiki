## Week 5 Quiz Questions and Answers

In order to prepare your Week 5 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-5" in your fork of this repo. Then, after all edits have been made/committed, your Week 5 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-5 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 5, Problem 1]
- *Question*(kamirneni-stat6250): If one does not want to specify a file extension for referencing a file in an aggregate storage location, what is the alternative?

- *Answer*(kamirneni-stat6250): The alternative is to put the filename in quotation marks.



[Course Textbook Chapter 5, Problem 2]
- *Question*(kamirneni-stat6250): What is the naming convention when declaring a new variable?

- *Answer*(kamirneni-stat6250): One must specify the variable in the exact case to be stored. After that, one can specify it any case.



[Course Textbook Chapter 5, Problem 6]
- *Question*(kamirneni-stat6250): What should be included in the INFILE statement to process records 1 through n?



[Course Textbook Chapter 5, Problem 7]
- *Question*(kamirneni-stat6250): Can date be assigned to variables, if yes, how?



[Course Textbook Chapter 5, Problem 8]
- *Question*(kamirneni-stat6250): Does subsetting DATA create a new file with the conditional data or make changes to the original file? 



[Course Textbook Chapter 6, Problem 1]
- *Question*(kamirneni-stat6250): Why is raw data considered for creating a input buffer, and not SAS data at all?



[Course Textbook Chapter 6, Problem 2]
- *Question*(kamirneni-stat6250): What is a program data vector?

- *Answer*(kamirneni-stat6250): It is the area of memory where SAS holds one observation at a time.



[Course Textbook Chapter 6, Problem 3]
- *Question*(kamirneni-stat6250): After the end of DATA step, why variable values in the program data vector are re-set to missing?



[Course Textbook Chapter 6, Problem 4]
- *Question*(kamirneni-stat6250): Why are there exceptions for SAS to set value of variable missing in DATA statement at beginning of each cycle of execution? What happens if the exceptions are ignored?



[Course Textbook Chapter 6, Problem 5]
- *Question*(kamirneni-stat6250): How do PROC FREQ and PROC MEANS filter invalid data?



[Course Textbook Chapter 6, Problem 6]
- *Question*(kamirneni-stat6250): Is it efficient to delete observations which have invalid data instead of correcting them?



[basic_recipe_for_creating_analytic_datasets Week 5 Recipe]
- *Question*(kamirneni-stat6250): Which is more efficient in loading data from disk, PDV in SAS or R/SQL, considering time and size of data?



[adv_recipe_for_creating_analytic_datasets Week 5 Recipe]
- *Question*(kamirneni-stat6250): What is the advantage of using PROC SQL over the conventional retain and keep method?

- *Answer*(kamirneni-stat6250): it can also be used as a substitute for proc means, proc freq, and many other proc statements with the right syntax to make the code and dataset result more efficient.


