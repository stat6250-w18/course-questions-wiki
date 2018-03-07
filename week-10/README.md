## Week 10 Quiz Questions and Answers

In order to prepare your Week 10 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-10" in your fork of this repo. Then, after all edits have been made/committed, your Week 10 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-10 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 16, Problem 1]
- *Question* (akrishnamurthy-stat6250): What is the use of INPUT statement?



[Course Textbook Chapter 16, Problem 5]
- *Question* (akrishnamurthy-stat6250): What is an informat in INPUT statement ? What are the informats available in SAS ?



[Course Textbook Chapter 16, Problem 7]
- *Question* (akrishnamurthy-stat6250): How to read character and standard numeric data with INPUT statement?
- *Answer* (akrishnamurthy-stat6250): The "$w." informat is used to read character data. $ indicates that the variable is a character followed by width of the variable and period indicates end of informat. "w.d" is the informat for reading numeric data. "w" specifies width of the field, period is the delimiter and "d" optionally specifies the number of implied decimal places. 



[Course Textbook Chapter 16, Problem 8]
- *Question* (akrishnamurthy-stat6250): What is the difference between +n and @n pointer controls?
- *Answer* (akrishnamurthy-stat6250): The @n pointer control moves the input pointer to specific column number. The +n pointer control moves the pointer forward to a column number that is relative to the current position.



[Course Textbook Chapter 16, Problem 9]
- *Question* (akrishnamurthy-stat6250): How to read variable length records in SAS ?



[Course Textbook Chapter 17, Problem 1]
- *Question* (akrishnamurthy-stat6250): How to read free format data in SAS ? Can variables from free format file be read in different orders?



[Course Textbook Chapter 17, Problem 2]
- *Question* (akrishnamurthy-stat6250): Can range of variables be specified using formatted input?



[Course Textbook Chapter 17, Problem 4]
- *Question* (akrishnamurthy-stat6250): what is the DSD option used for in FILE statement?



[Course Textbook Chapter 17, Problem 5]
- *Question* (akrishnamurthy-stat6250): Can free format data be seperated by a delimiter other than blanks?



[Course Textbook Chapter 17, Problem 7]
- *Question* (akrishnamurthy-stat6250): Can the order of variables be defined along with LENGTH overrides?



[Course Textbook Chapter 17, Problem 8]
- *Question* (akrishnamurthy-stat6250): what is the use of '&' and ':' modifiers in list input?
- *Answer* (akrishnamurthy-stat6250): The ampersand (&) modifier is used to read character values with embedded blanks. The colon(:) modifier is used to read variables greater than 8 characters without any embedded blanks.



[Course Textbook Chapter 17, Problem 10]
- *Question* (akrishnamurthy-stat6250): Can mixed input styles be used in same INPUT statement ?



[basic_recipe_to_load_remote_delimited_file Week 10 Recipe]
- *Question* (akrishnamurthy-stat6250): How does PROC import behave for delimited text files ?



[adv_recipe_to_load_remote_delimited_file Week 10 Recipe]
- *Question* (akrishnamurthy-stat6250): Will a data step to transform text file into SAS dataset be better than a PROC sql 


