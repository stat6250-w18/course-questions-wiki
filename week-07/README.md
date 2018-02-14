## Week 7 Quiz Questions and Answers

In order to prepare your Week 7 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-7" in your fork of this repo. Then, after all edits have been made/committed, your Week 7 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-7 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 10, Problem 2]
- *Question*(kamirneni-stat6250): What is the advantage of RETAIN statement used in initializing SUM variables? 
- *Answer*(kamirneni-stat6250): The RETAIN statements assigns an initial value to the retained variable and prevents variables from being initialized each time the DATA step executes.



[Course Textbook Chapter 10, Problem 6]
- *Question*(kamirneni-stat6250): What functions do we use to read and process variables that we do not want in the dataset?



[Course Textbook Chapter 10, Problem 7]
- *Question*(kamirneni-stat6250): Do the temporary labels and formats assigned during PROC step override the ones in DATA step if assigned?



[Course Textbook Chapter 10, Problem 8]
- *Question*(kamirneni-stat6250): Does WHEN statement identify both TRUE and FALSE statements?



[Course Textbook Chapter 10, Problem 9]
- *Question*(kamirneni-stat6250): When does SAS issue an error in the SELECT-WHEN statement?



[Course Textbook Chapter 10, Problem 10]
- *Question*(kamirneni-stat6250): Are there any limitations in using SELECT groups? 



[Course Textbook Chapter 11, Problem 1]
- *Question*(kamirneni-stat6250): What is the difference in procedure of referencing a variable from original dataset? 
- *Answer*(kamirneni-stat6250): Use DROP/KEEP in SET statement to not reference variables and not let them appear in new dataset. If one needs to reference a variable in the original dataset, use DROP/KEEP statement in DATA statement.



[Course Textbook Chapter 11, Problem 2]
- *Question*(kamirneni-stat6250): What is a minor difference between STOP and DATA step in looping with POINT function?



[Course Textbook Chapter 11, Problem 3]
- *Question*(kamirneni-stat6250): What is the difference in DATA step processing for existing dataset and raw data?



[Course Textbook Chapter 11, Problem 8]
- *Question*(kamirneni-stat6250): What does SAS do differently for raw data compared to existing dataset in DATA step?



[Course Textbook Chapter 11, Problem 9]
- *Question*(kamirneni-stat6250):How does the DATA step execute the dataset?



[basic_recipe_for_combining_data_vertically Week 7 Recipe]
- *Question*(kamirneni-stat6250): How are defensive programming practices defined?



[adv_recipe_for_combining_data_vertically Week 7 Recipe]
- *Question*(kamirneni-stat6250): What are the trade-offs for combining datasets using SQL in SAS? 
- *Answer*(kamirneni-stat6250): It loads all data into memory before performing set theory operations, RAM has limitations and takes longer time to create datasets comparatively.


