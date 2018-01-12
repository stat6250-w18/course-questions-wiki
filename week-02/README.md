
## Week 2 Quiz Questions and Answers

In order to prepare your Week 2 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-2" in your fork of this repo. Then, after all edits have been made/committed, your Week 2 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-2 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 1, Problem 1]
*Question* (sbagdi-stat6250): What are the descriptor portion of SAS data sets? 
*Answer* (sbagdi-stat6250): The descriptor portions are- 
1. the name of the data set
2. the date and time that the data set was created
3. the number of observations
4. the number of variables.

[Course Textbook Chapter 1, Problem 2]
*Question* (sbagdi-stat6250): How are SAS programs processed?
*Answer* (sbagdi-stat6250): While running a SAS program, the program looks for statements- DATA, PROC, and RUN. When it encounters a DATA, PROC, or RUN statement, SAS stops reading statements and executes the previous step in program. 

[Course Textbook Chapter 1, Problem 3]
*Question* (sbagdi-stat6250): What constitutes a numeric variable?
*Answer* (sbagdi-stat6250):The numerals from 0-9, operators(‘+’, ‘-‘), ‘.’ ,and e (scientific notation).


[Course Textbook Chapter 1, Problem 4]
*Question* (sbagdi-stat6250): How to represent a missing value for a character type variable?
*Answer* (sbagdi-stat6250): Missing value of character variable is represented by a “blank”.

[Course Textbook Chapter 1, Problem 5]
*Question* (sbagdi-stat6250): What are the naming conventions to followed by a programmer for declaring a variable?
*Answer* (sbagdi-stat6250):The following are the name conventions-
1.	can be 1 to 32 characters long
2.	must begin with a letter (A-Z, either uppercase or lowercase) or an underscore (_)
3.	can continue with any combination of numbers, letters, or underscores.


[Course Textbook Chapter 1, Problem 8] 
*Question* (sbagdi-stat6250): What is the maximum memory allocation for a character variable?
*Answer* (sbagdi-stat6250):The character variables can take up to 32,767 bytes, which is equivalent to 4000 characters. 

[Course Textbook Chapter 2, Problem 3]
*Question* (sbagdi-stat6250): How the date expression 04/15/91 would be interpreted by SAS, if the default YEARCUTOFF = Date(1995)?
*Answer* (sbagdi-stat6250): Since, SAS interprets a two-digit date value on a 100 year span (in this case from 1995-2014), which starts at the YEARCUTOFF = value. The date expression 04/15/91(not included in the 100 year-span specified) would be interpreted as 04/15/2091.

[Course Textbook Chapter 2, Problem 7]
*Question* (sbagdi-stat6250): What happens if we do not specify a libref when creating a file in SAS? Does the file remain there or gets deleted?
*Answer* (sbagdi-stat6250): If we do not specify a libref while creating a file in SAS, the file is stored in the temporary library. And gets deleted at the end of the session.

[Course Textbook Chapter 2, Problem 8]
*Question* (sbagdi-stat6250): For date 04/15/1991, is the YEARCUTOFF = 1992 correct?
*Answer* (sbagdi-stat6250): For a four-digit year, It doesn’t matter if the specified date fits in the range of 100 year time span because, the YEARCUTOFF= value option works only on the two-digit year dates.

[Course Textbook Chapter 2, Problem 9]
*Question* (sbagdi-stat6250): How do I create my own SAS library?
*Answer* (sbagdi-stat6250): libname statement is used to create the library. For example- 
libname test ‘C:\Users\prara\Desktop\CAl STATE’
The above statement creates a library called test on a windows machine with the mentioned path.

[basic_recipe_for_loading_data_from_remote_Excel_file Week 2 Recipe]
*Question* (sbagdi-stat6250): What does the ‘RUN’ statement does apart from terminating proc http step?
*Answer* (sbagdi-stat6250): The RUN statement causes the file to be loaded from the specified website. 

[bonus_advanced_recipe_for_loading_data_from_remote_Excel_file Week 2 Recipe] 
*Question* (sbagdi-stat6250): What is the character ‘&’ used for in SAS? Also, what does ‘%mend’ does?
*Answer* (sbagdi-stat6250): The & character is used to reference a macro variable. And %mend is used to end the creation of the macro.
