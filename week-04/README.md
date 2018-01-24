## Week 4 Quiz Questions and Answers

In order to prepare your Week 4 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-4" in your fork of this repo. Then, after all edits have been made/committed, your Week 4 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-4 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 7, Problem 3]
- Question (ljiang11−stat6250): Will there be any conflicts by naming format's name a dataset variable's name?


[Course Textbook Chapter 7, Problem 4]
- Question (ljiang11−stat6250): Why semicolon is not needed after each defined level?
- Answer (ljiang11−stat6250): Because they belong to the same value statement. Semicolon would end the statement.


[Course Textbook Chapter 7, Problem 5]
- Question (ljiang11−stat6250): How to specify a single value by ranged in VALUE statement?


[Course Textbook Chapter 7, Problem 6]
- Question (ljiang11−stat6250): How many characters can be used in a label?
- Answer (ljiang11−stat6250): 256.

[Course Textbook Chapter 7, Problem 7]
- Question (ljiang11−stat6250): Which keyword can be used to label missing numeric values as well as any values that are not specified in a range?
- Answer (ljiang11−stat6250): OTHER.
- Question (ljiang11−stat6250): For LOW keyword, what is the difference between numeric values and character values in terms of range?
- Answer (ljiang11−stat6250): For character values, LOW can be missing value, but not for numeric values.


[Course Textbook Chapter 7, Problem 8]
- Question (ljiang11−stat6250): You can place the FORMAT statement in either a DATA step or a PROC step. What happens when you place it in a DATA step?
- Answer (ljiang11−stat6250): You permanently associate the formats with variables.


[Course Textbook Chapter 8, Problem 1]
- Question (ljiang11−stat6250): What does PROC MEANS provide as opposed to PROC FREQ or PROC UNIVARIATE?
- Answer (ljiang11−stat6250): It provides summary statistics, while PROC FREQ is looking at distinct values, checking for duplicates; PROC UNIVARIATE is looking at extreme values, missing values.


[Course Textbook Chapter 8, Problem 2]
- Question (ljiang11−stat6250): Which statement can be used in PROC MEANS statement to group the data?
- Answer (ljiang11−stat6250): class statement.


[Course Textbook Chapter 8, Problem 4]
- Question (ljiang11−stat6250): In order to get variable A's frequency by variable B, what should we do first?
- Answer (ljiang11−stat6250): We should first sort the data by variable B


[Course Textbook Chapter 8, Problem 7]
- Question (ljiang11−stat6250): What does PROC FREQ do?


[Course Textbook Chapter 8, Problem 8]
- Question (ljiang11−stat6250): What type of data works best with frequency distributions?


[Course Textbook Chapter 8, Problem 10]
- Question (ljiang11−stat6250): What is the use of an asterisk in tables variable_A * variable_B?


[recipe_for_summarizing_quantitative_values Week 4 Recipe]
- Question (ljiang11−stat6250): What is a better PROC statement for quantitative variables?
- Answer (ljiang11−stat6250): PROC MEANS


[recipe_for_summarizing_qualitative_values Week 4 Recipe]
- Question (ljiang11−stat6250): What is a better PROC statement for qualitative variables?
- Answer (ljiang11−stat6250): PROC FREQ


[recipe_for_temporarily_binning_values Week 4 Recipe]
- Question (ljiang11−stat6250): In SAS, is "<" the only sign we use to specify an edge value is not included? Can we use ">"?
- Answer (ljiang11−stat6250): Yes, only use "<". ">" is not applicable for SAS.

