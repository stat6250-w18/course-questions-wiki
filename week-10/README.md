## Week 10 Quiz Questions and Answers

In order to prepare your Week 10 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-10" in your fork of this repo. Then, after all edits have been made/committed, your Week 10 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-10 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 16, Problem 1]
- *Question* (sbagdi-stat6250): Which input style in SAS can read data fields in any order? How is a blank field taken care of in a column input style?
- *Answer* (sbagdi-stat6250): The column input allows fields to be read in any order. And the blank fields are considered as missing data, and it doesn’t create any problem for any other fields.



[Course Textbook Chapter 16, Problem 5]
- *Question* (sbagdi-stat6250): What is the difference between standard numeric and non-standard numeric data?



[Course Textbook Chapter 16, Problem 7]
- *Question* (sbagdi-stat6250): What are the two types of column control pointers? What do they do?
- *Answer* (sbagdi-stat6250): The to column control pointers are- @n and +n the @n moves the input pointer to a specific column number and +n moves the input pointer to the column number relative to the current position.



[Course Textbook Chapter 16, Problem 8]
- *Question* (sbagdi-stat6250): What is an informat? What is the informat to read standard numeric data and what does that informat stands for?
- *Answer* (sbagdi-stat6250): An informat is an instruction that tells SAS how to read raw data, which could be both, standard and non-standard data values. “w.d” informat reads the standard numeric data, where w stands for field width of raw data values, the period as the delimeter, and the d, the number of implied decimals for the data value.



[Course Textbook Chapter 16, Problem 9]
- *Question* (sbagdi-stat6250): Why is it important to specify the actual field width of raw data in an input statement?
- *Answer* (sbagdi-stat6250): If the exact field width is missing, and we specify a default field width of 8 for all numeric values, SAS will read inappropriate variable values when program executes.



[Course Textbook Chapter 17, Problem 1]
- *Question* (sbagdi-stat6250): How can a free formatted data be read from a raw data file?
- *Answer* (sbagdi-stat6250): The LIST INPUT option is used to read free formatted data from the raw data file, where we do not need to specify the column location of the data field.



[Course Textbook Chapter 17, Problem 2]
- *Question* (sbagdi-stat6250): What are some of the limitations of LIST input?



[Course Textbook Chapter 17, Problem 4]
- *Question* (sbagdi-stat6250): When should we specify the range of variables in SAS? Does it make a difference if we specify the range in VAR statement with PROC PRINT step rather than in the INPUT statement?
- *Answer* (sbagdi-stat6250): When the variable values in the raw data file are sequential (specially, if the variables are similar) and are separated by a blank or any other delimiter, we can specify a range of variables in the INPUT statement. When the range is specified with PROC PRINT sep, it is done to list a range of specific variables. 



[Course Textbook Chapter 17, Problem 5]
- *Question* (sbagdi-stat6250): Why is a DLM= option used in SAS?
- *Answer* (sbagdi-stat6250): Sometimes, in free format data, characters other than blanks are used to separate data values in SAS. In such cases, the DLM= option is used in th INFILE statements.



[Course Textbook Chapter 17, Problem 7]
- *Question* (sbagdi-stat6250): What does DSD= option stand for? Why does SAS need this option? Is there a difference between MISSOVER option and DSD option?



[Course Textbook Chapter 17, Problem 8]
- *Question* (sbagdi-stat6250): What are the two types of modifiers used with list INPUT?
- *Answer* (sbagdi-stat6250): To make the list input more versatile, the modifiers are used. The two types are: The ampersand (&)- To read character values that contain embedded blanks, and the colon (:) modifier- To red non-standard data values and character values, which are longer than 8 characters and do not contain embedded blanks.



[Course Textbook Chapter 17, Problem 10]
- *Question* (sbagdi-stat6250): What does a LENGTH statement in SAS used for?
- *Answer* (sbagdi-stat6250): LENGTH statement in SAS is used to increase the character length of the variables, whose character lengths are greater than 8, so that they do not get truncated.



[basic_recipe_to_load_remote_delimited_file Week 10 Recipe]
- *Question* (sbagdi-stat6250): What is the delimiter if instead of a .csv file, the file is .tsv or for a pipe separated value file? What does .tsv stand for?
- *Answer* (sbagdi-stat6250): The .tsv stands for tab separated value file with “09”x, which is the ASCII hexadecimal representation for a tab character as its delimiter. For a pipe separated value file, a ‘|’ is used as its delimiter.



[adv_recipe_to_load_remote_delimited_file Week 10 Recipe]
- *Question* (sbagdi-stat6250): What does a ‘lrecl’ option do in SAS?
- *Answer* (sbagdi-stat6250): The ‘lrecl’ option is used to specify the maximum possible line length (logical record length), which is 256 by default, but is too short for most real-world file. 


