## Week 9 Quiz Questions and Answers

In order to prepare your Week 9 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-9" in your fork of this repo. Then, after all edits have been made/committed, your Week 9 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-9 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 14, Problem 1]
- *Question* (jcanfield3-stat6250): Are there any types of statements that can be use both data and proc steps?



[Course Textbook Chapter 14, Problem 2]
- *Question* (jcanfield3-stat6250): Why does the do loop resolve at the top rather than at the end?



[Course Textbook Chapter 14, Problem 3]
- *Question* (jcanfield3-stat6250): Can you use a statement like "do count=1 to (x*n)", or would x*n need to be pre-defined first?



[Course Textbook Chapter 14, Problem 4]
- *Question* (jcanfield3-stat6250): Can SAS detect an infinite loop, or does it get stuck iterating it until manually stopped?



[Course Textbook Chapter 14, Problem 5]
- *Question* (jcanfield3-stat6250): Does the year variable get deleted at the end of the data step (Does it still = 2005 after)?



[Course Textbook Chapter 14, Problem 6]
- *Question* (jcanfield3-stat6250): What value is year at the end of the loop?
- *Answer* (jcanfield3-stat6250): Year is 21, since it has to resolve at the top of the loop.



[Course Textbook Chapter 14, Problem 7]
- *Question* (jcanfield3-stat6250): How many different "do" statements are there in SAS?



[Course Textbook Chapter 14, Problem 8]
- *Question* (jcanfield3-stat6250): What happens if the until value is reached before the loop begins?
- *Answer* (jcanfield3-stat6250): The loop iterates only once then, since the loop is always executed at least once.



[Course Textbook Chapter 14, Problem 9]
- *Question* (jcanfield3-stat6250): Because it should in "do until(Capital gt 500000)", why does the do while(Capital le 500000) iterate when capital=500000?



[Course Textbook Chapter 14, Problem 10]
- *Question* (jcanfield3-stat6250): Can you have multiple while conditions in a single do loop?



[Course Textbook Chapter 15, Problem 1]
- *Question* (jcanfield3-stat6250): Why cannot i not mix numeric and character elements?



[Course Textbook Chapter 15, Problem 2]
- *Question* (jcanfield3-stat6250): What error if any is produced if an incorrect number is placed in parantheses?



[Course Textbook Chapter 15, Problem 3]
- *Question* (jcanfield3-stat6250): What error if any is produced if i try to access a nonexistent array element?



[Course Textbook Chapter 15, Problem 4]
- *Question* (jcanfield3-stat6250): Can a variable be used instead of a number in the parantheses when defining an array?
- *Answer* (jcanfield3-stat6250): Yes it can, as long as its value is numeric.



[Course Textbook Chapter 15, Problem 5]
- *Question* (jcanfield3-stat6250): Can you add elements to a pre-defined array with already maxed elements?



[Course Textbook Chapter 15, Problem 6]
- *Question* (jcanfield3-stat6250): What is the default numeric variable length?



[Course Textbook Chapter 15, Problem 7]
- *Question* (jcanfield3-stat6250): Are the 2nd and 3rd rows of weight1,2,3 even in the array?



[Course Textbook Chapter 15, Problem 8]
- *Question* (jcanfield3-stat6250): Why do special words in SAS need the underscores on both sides like in "_temporary_"?



[Course Textbook Chapter 15, Problem 9]
- *Question* (jcanfield3-stat6250): Since I cannot find it in the chapter, does {3, 25} specify a 2-D array with 3 rows and 25 columns?



[recipe_to_create_unique_record_id Week 9 Recipe]
- *Question* (jcanfield3-stat6250): What would happen if i used input instead of put?



[recipe_to_disaggregate_counts_data Week 9 Recipe]
- *Question* (jcanfield3-stat6250): So the code just creates repeated lines of each record based on the value of Enrollment_K12 right?


