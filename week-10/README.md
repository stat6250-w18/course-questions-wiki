## Week 10 Quiz Questions and Answers

In order to prepare your Week 10 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-10" in your fork of this repo. Then, after all edits have been made/committed, your Week 10 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-10 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 16, Problem 1]
- Question (nshrivastava2-stat6250): What happen when input variable contain embedded blank values?



[Course Textbook Chapter 16, Problem 5]
- Question (nshrivastava2-stat6250): How one can identify difference betwee Standard Numeric Data and Nonstandard Numeric Data ?



[Course Textbook Chapter 16, Problem 7]
- Question (nshrivastava2-stat6250): What is the funtion of INPUT statement?
- Answer(nshrivastava2-stat6250): INPUT statement lists the variables with their corresponding column locations in order from left to right. However, one of the features of column input is the ability to read fields in any order. 



[Course Textbook Chapter 16, Problem 8]
- Question (nshrivastava2-stat6250): What is @n Column Pointer Control and how it is useful?
- Answer(nshrivastava2-stat6250): The @n is an absolute pointer control that moves the input pointer to a specific column number. The @ moves the pointer to column n, which is the first column of the field that is being read. 



[Course Textbook Chapter 16, Problem 9]
- Question (nshrivastava2-stat6250): What si the funtion of The +n Pointer Control ?
- Answer(nshrivastava2-stat6250): The +n pointer control moves the input pointer forward to a column number that is relative to the current position. The + moves the pointer forward n columns. 



[Course Textbook Chapter 17, Problem 1]
- Question (nshrivastava2-stat6250): list input causes SAS to scan the input lines for values rather than reading from specific columns. When the INPUT statement is submitted for processing, the input pointer is positioned at column 1 of the raw data file.
- Answer(nshrivastava2-stat6250): SAS reads the first field until it encounters a blank space. The blank space indicates the end of the field, and the data value is assigned to the program data vector for the first variable in the INPUT statement.Next, SAS scans the record until the next nonblank space is found, and the second value is read until another blank is encountered. Then the value is assigned to its corresponding variable in the program data vector.



[Course Textbook Chapter 17, Problem 2]
- Question (nshrivastava2-stat6250): How SAS can read the data value which is saperated by other than blank character.
- Answer(nshrivastava2-stat6250): When characters other than blanks are used to separate the data values, one can use the DLM= option in the INFILE statement to specify a delimiter other than a blank. DLIMITER is an alias for the DLM option.



[Course Textbook Chapter 17, Problem 4]
- Question (nshrivastava2-stat6250): When PROC IMPORT is used to read a CSV, tab, or other character-delimited file, what procedure SAS uses / follows?



[Course Textbook Chapter 17, Problem 5]
- Question (nshrivastava2-stat6250): How to read range of variables in the INPUT statement?
- Answer(nshrivastava2-stat6250): When the variable values in the raw data file are sequential and are separated by a blank (or by another delimiter), can specify a range of variables in the INPUT statement. This is especially useful if your data contains similar variables.



[Course Textbook Chapter 17, Problem 7]
- Question (nshrivastava2-stat6250): How to list a range of specific variables?
- Answer(nshrivastava2-stat6250): By specifying a range in the VAR statement with the PROC PRINT step to list a range of specific variables.



[Course Textbook Chapter 17, Problem 8]
- Question (nshrivastava2-stat6250):  MISSOVER option works only for missing values that occur at the end of the record. What different method is required to read raw data that contains missing values at the beginning or middle of a record?



[Course Textbook Chapter 17, Problem 10]
- Question (nshrivastava2-stat6250): How program reads the raw data file with two consecutive delimeter / comma? 
- Answer(nshrivastava2-stat6250): The DSD ( Delimeter Sensitive Data ) option sets the default delimiter to a comma and treats the two consecutive delimiters as a missing value. Hence, the data is read correctly.



[basic_recipe_to_load_remote_delimited_file Week 10 Recipe]
- Question (nshrivastava2-stat6250): Infile statement has DELIMITER= option which specifies characters (other than the blank default character) to use as the delimiter that are being read. Common delimiters include comma (,), vertical pipe (|), semi-colon (;) , and the tab. What has been use for a tab in option to define tab delimeter?
- Answer(nshrivastava2-stat6250): In order to specify a tab delimiter, one can use hexadecimal value i.e DLM=’09’x.



[adv_recipe_to_load_remote_delimited_file Week 10 Recipe]
- Question (nshrivastava2-stat6250): What is the function of TERMSTR= option in INFILE statement to read delimited text files?
- Answer(nshrivastava2-stat6250): TERMSTR= option specifies what end-of-line character to use for a file. This option is useful, to share data files that are created on one operating system with another operating system. For example, while working in a UNIX environment, need to read a file that was created under Windows, use TERMSTR=CRLF. Similarly, while working in the Windows environment, need to read a file that was created under UNIX, use TERMSTR=LF. 


