## Week 10 Quiz Questions and Answers

In order to prepare your Week 10 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-10" in your fork of this repo. Then, after all edits have been made/committed, your Week 10 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-10 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 16, Problem 1]
- *Question* (ldai4-stat6250): How does the column input read the values in raw data file?
- *Answer* (ldai4-stat6250): Column input specifies the variables'name, followed by a dollar($) sigh if the values are character values, and the beginning and ending column locations of the raw data values.



[Course Textbook Chapter 16, Problem 5]
- *Question* (ldai4-stat6250): What does the $w mean?
- *Answer* (ldai4-stat6250): The $w informat enables you to read character data. the w represents the field width of the data value or the total number of columns that contain the raw data field.



[Course Textbook Chapter 16, Problem 7]
- *Question* (ldai4-stat6250): Which INPUT statement can read character values?



[Course Textbook Chapter 16, Problem 8]
- *Question* (ldai4-stat6250): How does the COMMAw.d informat read the variables with dollar signs and commas? 



[Course Textbook Chapter 16, Problem 9]
- *Question* (ldai4-stat6250): What is the column pointer control?



[Course Textbook Chapter 17, Problem 1]
- *Question* (ldai4-stat6250): If the rae file contains free-format data, does the data need to arrange in columns or fixed fields?



[Course Textbook Chapter 17, Problem 2]
- *Question* (ldai4-stat6250): What should be used to read the free-format data?
- *Answer* (ldai4-stat6250): List input should be used to read data that is free-format because you do not need to specify the column locations of the data.



[Course Textbook Chapter 17, Problem 4]
- *Question* (ldai4-stat6250): How does the list input read the values with free-format?



[Course Textbook Chapter 17, Problem 5]
- *Question* (ldai4-stat6250): How does the INFILE statement work?
- *Answer* (ldai4-stat6250): The INFILE statement identifies the location of the external data file. The DLM=option specifies the colon(:) as the delimiter that separates each field.



[Course Textbook Chapter 17, Problem 7]
- *Question* (ldai4-stat6250): Should the LENGTH statement precede the INPUT statement?



[Course Textbook Chapter 17, Problem 8]
- *Question* (ldai4-stat6250): Can modified list input be used to read the values that contain embedded blanks and nonstandard values?



[Course Textbook Chapter 17, Problem 10]
- *Question* (ldai4-stat6250): Which input can be used to read the values for year?



[basic_recipe_to_load_remote_delimited_file Week 10 Recipe]
- *Question* (ldai4-stat6250): How do we use INFILE to load a exteral file? 



[adv_recipe_to_load_remote_delimited_file Week 10 Recipe]
- *Question* (ldai4-stat6250): Can the PROC IMPORT read a Specific Delimited File?




