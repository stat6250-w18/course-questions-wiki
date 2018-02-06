## Week 6 Quiz Questions and Answers

In order to prepare your Week 6 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-6" in your fork of this repo. Then, after all edits have been made/committed, your Week 6 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-6 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 12, Problem 1]
Question (asharda-stat6250): What happens when you perform one-to-one merging?



[Course Textbook Chapter 12, Problem 2]
Question (asharda-stat6250): What is interleaving ?What statements are used in it?.
Answer(asharda-stat6250):Intersperses observations from two or more data sets, based on one or more common variables.
SET and BY are the statements used.



[Course Textbook Chapter 12, Problem 3]
Question (asharda-stat6250): What is Concatenating?.
Answer(asharda-stat6250):Another way to combine SAS data sets with the SET statement is concatenating, which appends the
observations from one data set to another data set. To concatenate SAS data sets, you specify a list of data
set names in the SET statement.



[Course Textbook Chapter 12, Problem 4]
Question (asharda-stat6250): How is concatenated data sets read?.
Answer(asharda-stat6250):The concatenated data sets are read sequentially, in the order in which they are listed in the 
SET statement.



[Course Textbook Chapter 12, Problem 5]
Question (asharda-stat6250): What happens if you have variables with the same name in more than one input data set?.
Answer(asharda-stat6250):If you have variables with the same name in more than one input data set, values of the 
same-named variable in the first data set in which it appears are overwritten by values of the same-named variable in 
subsequent data sets.



[Course Textbook Chapter 12, Problem 7]
Question (asharda-stat6250): What is Match-merging?.



[Course Textbook Chapter 12, Problem 9]
Question (asharda-stat6250): How to exclude unmatched observations?.



[basic_recipe_for_combining_data_horizontally Week 6 Recipe]
Question (asharda-stat6250): What is the use of merge and by statement?.
Answer(asharda-stat6250):The merge statement is used to name two input datasets and the by statement is used to name the unique id column(s),which specify how rows are to be matched up when combining the datasets.



[adv_recipe_for_combining_data_horizontally Week 6 Recipe]
Question (asharda-stat6250): Why do many SAS programmers rely on proc sql for the bulk of their data manipulation tasks?.
Answer(asharda-stat6250):Many SAS programmers rely on proc sql for the bulk of their data manipulation tasks, especially 
since it's a more flexible tool for combining datasets while requiring significantly less code.


