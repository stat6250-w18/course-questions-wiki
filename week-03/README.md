
## Week 3 Quiz Questions and Answers

In order to prepare your Week 3 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-3" in your fork of this repo. Then, after all edits have been made/committed, your Week 3 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-3 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 3, Problem 1]
Question (asharda-stat6250): What is a good way to write SAS Statement that can make it easy to understand and will be helpful for the code reviewers? 
Answer(asharda-stat6250): Although you can write SAS statements in almost any format, a consistent layout will enhance readability and enable you to understand the program's purpose. It will be a great idea to (1)begin DATA and PROC steps in column one(2) to indent statements within a step(3) to begin RUN statements in column one and (4) include a RUN statement after every DATA step or PROC step.



[Course Textbook Chapter 3, Problem 2]
Question (asharda-stat6250): How do you modify programs that contain errors? 
Answer(asharda-stat6250): You can correct simple typo errors in the code by typing over the incorrect text,deleting or inserting text.using Program editor Window you will usually need to recall the submitted statement from the last recall buffer to the Program Editor window where you can correct the problems.



[Course Textbook Chapter 3, Problem 3]
Question (asharda-stat6250): What happens if you miss a semicolon at the end of a statement? 
Answer(asharda-stat6250):When you miss a semicolon ,SAS reads the statement that lacks the semicolon ,plus the following statement as one long statement.The SAS logs then lists errors that relate to the combined statement ,not the actual mistake.


 
[Course Textbook Chapter 3, Problem 4]
Question (asharda-stat6250): Does the program terminate in the event of syntax error? 



[Course Textbook Chapter 3, Problem 5]
Question (asharda-stat6250): What are some of the common type of errors you see in SAS? 



[Course Textbook Chapter 3, Problem 6]
Question (asharda-stat6250): How can you correct a SAS program with an invalid option?



[Course Textbook Chapter 3, Problem 7]
Question (asharda-stat6250): What is the difference between a warning and an error?



[Course Textbook Chapter 3, Problem 10]
Question (asharda-stat6250): What is your understanding of Unbalanced quotation marks  in SAS?



[Course Textbook Chapter 4, Problem 1]
Question (asharda-stat6250): What is the significance of VAR statement?
Answer(asharda-stat6250):The VAR statement specifies variables and controls the order in which they appear.



[Course Textbook Chapter 4, Problem 3]
Question (asharda-stat6250): How do you specify compound WHERE Expressions?



[Course Textbook Chapter 4, Problem 4]
Question (asharda-stat6250): How do you sort a report based on variable values?
Answer(asharda-stat6250):You must use PROC SORT to sort your data before using the PRINT procedure to create reports from the data.



[Course Textbook Chapter 4, Problem 7]
Question (asharda-stat6250): What happens if you miss BY statement in PROC SORT?



[Course Textbook Chapter 4, Problem 9]
Question (asharda-stat6250): How do you use AND and OR operator?.



[Course Textbook Chapter 4, Problem 10]
Question (asharda-stat6250): How do you submit a Basic PROC PRINT step?.



[recipe_to_check_for_duplicates Week 3 Recipe]
Question (asharda-stat6250): How can you eliminate Duplicates?.



[recipe_for_sorting_data Week 3 Recipe]
Question (asharda-stat6250): Is there any other better way of sorting data?.



[recipe_for_printing_values Week 3 Recipe]
Question (asharda-stat6250): Are there any other ways of printing the values?.



