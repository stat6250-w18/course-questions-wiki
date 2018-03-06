## Week 10 Quiz Questions and Answers

In order to prepare your Week 10 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-10" in your fork of this repo. Then, after all edits have been made/committed, your Week 10 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-10 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 16, Problem 1]
- Question (ttruong59-stat6250): Does the column input have the ability to read fields in any order? 
- Answer (ttruong59-stat6250): Yes, the column input the ability to read fields in any order. Column input needs to specify the variable’s name followed by the $ sign if the values are character values.



[Course Textbook Chapter 16, Problem 5]
- Question (ttruong59-stat6250): What does $w. informat do for reading data?
- Answer (ttruong59-stat6250): The $w. Informat enables users to read character data. The w represents the field width of the data value or the total number of columns that contain the raw data field.



[Course Textbook Chapter 16, Problem 7]
- Question (ttruong59-stat6250): What is a major difference between @n and +n pointer control in the INPUT statements?



[Course Textbook Chapter 16, Problem 8]
- Question (ttruong59-stat6250): What does the COMMAw.d informat do in the INPUT statements?
- Answer (ttruong59-stat6250): The COMMAw.d informat is used to read the raw data values. It also will remove any special characters such as commas from numeric data and store only numeric values in a dataset.



[Course Textbook Chapter 16, Problem 9]
- Question (ttruong59-stat6250): What is a default location of the column pointer control?
- Answer (ttruong59-stat6250): The default location of the column pointer control is column 1 and a column pointer control is optional for reading the first field.



[Course Textbook Chapter 17, Problem 1]
- Question (ttruong59-stat6250): What is a free-format data?
- Answer (ttruong59-stat6250): Raw data can be organized in several ways and free-format typically is not arranged in fixed fields. The fields are often separated by blanks or by some delimiters.



[Course Textbook Chapter 17, Problem 2]
- Question (ttruong59-stat6250): Do users need to specify the column locations of the data with list input?
- Answer (ttruong59-stat6250): No, it is not necessary.


[Course Textbook Chapter 17, Problem 4]
- Question (ttruong59-stat6250): Is it necessary to list the variable names in the same order when using a list input statement?
- Answer (ttruong59-stat6250): It is required to list the variable names in the same order corresponding to raw data fields and fields can’t be skipped or re-read.



[Course Textbook Chapter 17, Problem 5]
- Question (ttruong59-stat6250): What is a significant reason users need to use the DLM= option in the INFILE statement?
- Answer (ttruong59-stat6250): We need to use the DLM= option in the INFILE statement to specify a delimiter other than a blank.



[Course Textbook Chapter 17, Problem 7]
- Question (ttruong59-stat6250): What is the default length of character variables when using list input to read raw data?



[Course Textbook Chapter 17, Problem 8]
- Question (ttruong59-stat6250): What is a major difference between “&” modifier and “:” modifier when using modified list input?



[Course Textbook Chapter 17, Problem 10]
- Question (ttruong59-stat6250): What kind of data can contain embedded blanks or nonstandard values?
- Answer (ttruong59-stat6250): free-format data



[basic_recipe_to_load_remote_delimited_file Week 10 Recipe]
- Question (ttruong59-stat6250): Why is “dlm” assigned for DBMS= option in proc import?



[adv_recipe_to_load_remote_delimited_file Week 10 Recipe]
- Question (ttruong59-stat6250): What is an advantage of using a data step rather than using proc import in the basic version of the recipe to load remote delimited file?
- Answer (ttruong59-stat6250): Users can add do-loops and if-then statement with a data step as needed when loading remote delimited file.



