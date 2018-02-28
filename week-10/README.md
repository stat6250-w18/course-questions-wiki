## Week 10 Quiz Questions and Answers

In order to prepare your Week 10 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-10" in your fork of this repo. Then, after all edits have been made/committed, your Week 10 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-10 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 16, Problem 1]
- *Question* (cli19−stat6250): How does SAS know the variable type of each column input?
- *Answer* (cli19−stat6250): The informat of each variable is specified after the variable name in the INPUT statement. The dollar sign ($) distinguishes character from numeric.



[Course Textbook Chapter 16, Problem 5]
- *Question* (cli19−stat6250): Is SAS capable of automatically detecting when observations of variables end and begin?
- *Answer* (cli19−stat6250): Delimiters can be specified to detect the start/end of variable values.


[Course Textbook Chapter 16, Problem 7]
- *Question* (cli19−stat6250): How can the "+" and "@" symbols be used to move the input column pointer?



[Course Textbook Chapter 16, Problem 8]
- *Question* (cli19−stat6250): What will SAS output if the input value does not fit the specified informat?



[Course Textbook Chapter 16, Problem 9]
- *Question* (cli19−stat6250): What is the best practice for moving the column pointer when formatting input.



[Course Textbook Chapter 17, Problem 1]
- *Question* (cli19−stat6250): How is the informat modified to read free-format data?
- *Answer* (cli19−stat6250): In some cases, the INPUT statement can be modified to read values until two consecutive blanks are encountered. In other cases, a delimiter can be specified if available using the DLM= option.



[Course Textbook Chapter 17, Problem 2]
- *Question* (cli19−stat6250): When modifying list input, what modifiers can be used to read values that contain embedded blanks and nonstandard values?
- *Answer* (cli19−stat6250): The ampersand enables you to read character values that contain single embedded blanks. The colon enables youto read nonstandard data values and character values that are longer than eight characters, but which contain no embedded blanks.



[Course Textbook Chapter 17, Problem 4]
- *Question* (cli19−stat6250): For list input, why isn't it necessary to specify the column?
- *Answer* (cli19−stat6250): Because the data is free-format, you simply name each variable and identify its type. Data will be read in until a blank is encountered.



[Course Textbook Chapter 17, Problem 5]
- *Question* (cli19−stat6250): When data is being read in from DATALINES, how can you specify the delimiters?
- *Answer* (cli19−stat6250): In the INFILE statement, specify datalines as the location of the data, and utilize the DLM= option to declare your delimiters.



[Course Textbook Chapter 17, Problem 7]
- *Question* (cli19−stat6250): Are there any repercussions to defining a variable length that is longer than necessary?



[Course Textbook Chapter 17, Problem 8]
- *Question* (cli19−stat6250): What happens when modified list input is not used to read valaues that contain embedded blanks and nonstandard values?



[Course Textbook Chapter 17, Problem 10]
- *Question* (cli19−stat6250): Unlike column input, how must list input fields be read in?



[basic_recipe_to_load_remote_delimited_file Week 10 Recipe]
- *Question* (cli19−stat6250): 



[adv_recipe_to_load_remote_delimited_file Week 10 Recipe]
- *Question* (cli19−stat6250): 


