## Week 10 Quiz Questions and Answers

In order to prepare your Week 10 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-10" in your fork of this repo. Then, after all edits have been made/committed, your Week 10 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-10 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 16, Problem 1]
- *Question* (asharda-stat6250): What are different Column Input Features?



[Course Textbook Chapter 16, Problem 5]
- *Question* (asharda-stat6250): Which data can you read with  $w. informat?
- *Answer* (asharda-stat6250): The $w. informat enables you to read character data. 



[Course Textbook Chapter 16, Problem 7]
- *Question* (asharda-stat6250): Can Column Input  read character variable values that contain embedded blanks?
- *Answer* (asharda-stat6250): Yes.



[Course Textbook Chapter 16, Problem 8]
- *Question* (asharda-stat6250): What is a  Formatted Input
- *Answer* (asharda-stat6250): Formatted input is a very powerful method for reading both standard and nonstandard data in fixed fields.



[Course Textbook Chapter 16, Problem 9]
- *Question* (asharda-stat6250): When is PAD option useful ?
- *Answer* (asharda-stat6250): The PAD option is useful only when missing data occurs at the end of a record or when SAS
encounters an end-of-record marker before all fields are completely read



[Course Textbook Chapter 17, Problem 1]
- *Question* (asharda-stat6250): What different input styles does SAS provide? 
- *Answer* (asharda-stat6250):  SAS providesthree primary input styles: column, formatted, and list input. 



[Course Textbook Chapter 17, Problem 2]
- *Question* (asharda-stat6250): What different input styles does SAS provide? 
- *Answer* (asharda-stat6250):  SAS providesthree primary input styles: column, formatted, and list input. 



[Course Textbook Chapter 17, Problem 4]
- *Question* (asharda-stat6250): When should list input be used to read free-format data?.



[Course Textbook Chapter 17, Problem 5]
- *Question* (asharda-stat6250): When do you use DSD option in file statement?.



[Course Textbook Chapter 17, Problem 7]
- *Question* (asharda-stat6250): How do you prevent SAS from reading the next record to find the missing values
- *Answer* (asharda-stat6250):You can use the INFILE statement with the MISSOVER option to prevent SAS from reading the next record to find the missing values



[Course Textbook Chapter 17, Problem 8]
- *Question* (asharda-stat6250): What are some things to remember when you use list input?.



[Course Textbook Chapter 17, Problem 10]
- *Question* (asharda-stat6250): How do you specify the length of character variables ?.
- *Answer* (asharda-stat6250):  You can specify the length of character variables by using the LENGTH statement.



[basic_recipe_to_load_remote_delimited_file Week 10 Recipe]
- *Question* (asharda-stat6250): Why is the "replace" option excluded?.



[adv_recipe_to_load_remote_delimited_file Week 10 Recipe]
- *Question* (asharda-stat6250): Why are the options dlm and truncover used?.
- *Answer* (asharda-stat6250):  The option dlm to set the delimiter used in the file, the truncover option to allow incomplete data to be read.

