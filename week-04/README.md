## Week 4 Quiz Questions and Answers

In order to prepare your Week 4 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-4" in your fork of this repo. Then, after all edits have been made/committed, your Week 4 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-4 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 7, Problem 3]
- *Question* (akrishnamurthy-stat6250): How should format name be defined for character and numeric data ?


[Course Textbook Chapter 7, Problem 4]
- *Question* (akrishnamurthy-stat6250): What is the syntax of VALUE statement while defining multiple labels in PROC FORMAT? 


[Course Textbook Chapter 7, Problem 5]
- *Question* (akrishnamurthy-stat6250): Can one FORMAT be defined to include both character and numeric data ?
- *Answer* (akrishnamurthy-stat6250): FORMAT can be defined for either character or numeric data and cannot hold mixed data types. When the specified values are character, the format name should begin with '$' and values should be enclosed within quotes. Format for numeric values should not be enclosed within quotes and format name should not begin with '$'.


[Course Textbook Chapter 7, Problem 6]
- *Question* (akrishnamurthy-stat6250): How is a label defined for a range of values in FORMAT ?


[Course Textbook Chapter 7, Problem 7]
- *Question* (akrishnamurthy-stat6250): While specifying range, how are the out of bound or missing values identified ? Is it necessary to specify a seperate label for such values?


[Course Textbook Chapter 7, Problem 8]
- *Question* (akrishnamurthy-stat6250): What is the difference of using the format statement in PROC or DATA step?


[Course Textbook Chapter 8, Problem 1]
- *Question* (akrishnamurthy-stat6250): What are the default statistical measures produced by MEANS procedure?


[Course Textbook Chapter 8, Problem 2]
- *Question* (akrishnamurthy-stat6250): If variables are not explicitly specified for MEANS procedure, what will be the output? If dataset includes only character data, how does MEANS procedure behave?


[Course Textbook Chapter 8, Problem 4]
- *Question* (akrishnamurthy-stat6250): What is the difference between 'BY' and 'CLASS' statements?


[Course Textbook Chapter 8, Problem 7]
- *Question* (akrishnamurthy-stat6250): Why is it advisable to use TABLES statment while creating crosstabulation table?
- *Answer* (akrishnamurthy-stat6250): FREQ procedure creates frequency table for all variables in a data set. However, it may not be meaningful for conitnuous numeric values like timestamp. Hence it is better to specify the variables that are categorical explicitly using TABLES statement.


[Course Textbook Chapter 8, Problem 8]
- *Question* (akrishnamurthy-stat6250): Why does frequency distribution work better for categorical values?


[Course Textbook Chapter 8, Problem 10]
- *Question* (akrishnamurthy-stat6250): How can the cell frequencies be suppressed in crosstabulation table?
- *Answer* (akrishnamurthy-stat6250): The cell frequencies can be suppressed by using NOFREQ option.


[recipe_for_summarizing_quantitative_values Week 4 Recipe]
- *Question* (akrishnamurthy-stat6250): Is 'Class' statement mandatory while summarizing data using MEANS procedure?


[recipe_for_summarizing_qualitative_values Week 4 Recipe]
- *Question* (akrishnamurthy-stat6250): While creating cross tabulated reports, how are rows with missing variables handled?


[recipe_for_temporarily_binning_values Week 4 Recipe]
- *Question* (akrishnamurthy-stat6250): How to specify non inclusive range of unique values while defining FORMAT?

