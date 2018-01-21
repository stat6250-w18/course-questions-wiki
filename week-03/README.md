
## Week 3 Quiz Questions and Answers

In order to prepare your Week 3 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-3" in your fork of this repo. Then, after all edits have been made/committed, your Week 3 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-3 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 3, Problem 1]
- *Question*(kamirneni-stat6250): Is it necessary to use PROC before PRINT? If no, will it display an error?
 


[Course Textbook Chapter 3, Problem 2]
- *Question*(kamirneni-stat6250): What is the advantage of using SAS enhanced editor?
- *Answer*(kamirneni-stat6250): One can use text formatting, indentation,  macros, keyboard shortcuts, bookmark codes, collapse and expand sections of SAS procedures.



[Course Textbook Chapter 3, Problem 3]
- *Question*(kamirneni-stat6250): Does SAS differentiate between error and warning?
 
 
 
[Course Textbook Chapter 3, Problem 4]
- *Question*(kamirneni-stat6250): How are the errors displayed if the they are syntax, data and logic?  Are they categorized and displayed separately?
 


[Course Textbook Chapter 3, Problem 5]
- *Question*(kamirneni-stat6250): ): Are different kinds of invalid options are defined separately and shown as such? 



[Course Textbook Chapter 3, Problem 6]
- *Question*(kamirneni-stat6250): How does one determine which procedures should undergo error handling and which ones should log window messages?
 
 

[Course Textbook Chapter 3, Problem 7]
- *Question*(kamirneni-stat6250): Can DAT be used instead of DATA without any error?
- *Answer*(kamirneni-stat6250): Yes, it is very common to do so. SAS does produce a warning though.



[Course Textbook Chapter 3, Problem 10]
- *Question*(kamirneni-stat6250): What happens when you do not submit a RUN statement after a DATA statement?
- *Answer*(kamirneni-stat6250): The DATA submit runs but does no execute, causing the window to display an error “DATA step running”.



[Course Textbook Chapter 4, Problem 1]
- *Question*(kamirneni-stat6250): Is it possible to change the value of an observation specifically?



[Course Textbook Chapter 4, Problem 3]
- *Question*(kamirneni-stat6250): Is a nested where statement (like SQL) possible in SAS?



[Course Textbook Chapter 4, Problem 4]
- *Question*(kamirneni-stat6250): Similar to having alternate statements for OR function, does AND also have alternate statements?



[Course Textbook Chapter 4, Problem 7]
- *Question*(kamirneni-stat6250): ): Does the SORT statement by default replace the original dataset? Is there any other way to duplicate the original dataset and then perform the SORT function?
 


[Course Textbook Chapter 4, Problem 9]
- *Question*(kamirneni-stat6250): By default, the PRINT PROC displays all observations in the dataset in the original format. Is there a way to make changes on how to print observations in a different format?  
- *Answer*(kamirneni-stat6250): Using the WHERE, AND, OR statements one can modify the way observations are printed.


[Course Textbook Chapter 4, Problem 10]
- *Question*(kamirneni-stat6250): Is there any specific rule for PAGEBY on requesting subtotals?
- *Answer*(kamirneni-stat6250): The variable specified in PAGEBY statement must also be specified in BY statement in the PROC PRINT statement.


[recipe_to_check_for_duplicates Week 3 Recipe]
- *Question*(kamirneni-stat6250): What steps lead to duplication of datasets and how can we avoid them?
 
 

[recipe_for_sorting_data Week 3 Recipe]
- *Question*(kamirneni-stat6250): What happens if one does not use the OUT=option?
- *Answer*(kamirneni-stat6250): PROC SORT overwrites the data specified in DATA=option. 



[recipe_for_printing_values Week 3 Recipe]
- *Question*(kamirneni-stat6250): What is the optimal position to place titles and footnotes?
- *Answer*(kamirneni-stat6250): It does not matter much as long as they are place before the PRINT statement.


