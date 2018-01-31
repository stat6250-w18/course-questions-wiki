## Week 4 Quiz Questions and Answers

In order to prepare your Week 4 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-4" in your fork of this repo. Then, after all edits have been made/committed, your Week 4 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-4 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 7, Problem 3]
- *Question* (kamirneni-stat6250): Is format that is stored Work.formats is temporary or permanent?
- *Answer* (kamirneni-stat6250): The format exists for the current SAS session. It is erased after the SAS session ends.

[Course Textbook Chapter 7, Problem 4]
- *Question* (kamirneni-stat6250): What is the most important rule when creating a format with VALUE statement?
- *Answer* (kamirneni-stat6250): It must begin with a $ sign if it is a character variable.

[Course Textbook Chapter 7, Problem 5]
- *Question* (kamirneni-stat6250): Can we enter special characters in ranges in VALUE statement?


[Course Textbook Chapter 7, Problem 6]
- *Question* (kamirneni-stat6250): How many characters can be used in a label? 256 or 32,767?


[Course Textbook Chapter 7, Problem 7]
- *Question* (kamirneni-stat6250): What is the result when you place a FORMAT statement in DATA step?
- *Answer* (kamirneni-stat6250): By doing so, you permanently associate the FORMAT with the variable.

[Course Textbook Chapter 7, Problem 8]
- *Question* (kamirneni-stat6250): What is the difference between temporary and permanent library?


[Course Textbook Chapter 8, Problem 1]
- *Question* (kamirneni-stat6250): Does the using the PROC statement for Statistics generate results in the same dataset by or as a separate output in another location?


[Course Textbook Chapter 8, Problem 2]
- *Question* (kamirneni-stat6250): What are the statements by which one can perform group processing?
+- *Answer* (kamirneni-stat6250): Using CLASS and BY statements, one can perform group processing.

[Course Textbook Chapter 8, Problem 4]
- *Question* (kamirneni-stat6250): What is the difference between CLASS and BY statements?
- *Answer* (kamirneni-stat6250): BY processing requires data to be already sorted or indexed in the order of BY variables unlike CLASS. Also, the layout of group results is also different between the two.

[Course Textbook Chapter 8, Problem 7]
- *Question* (kamirneni-stat6250): How can one supress the default report?
- *Answer* (kamirneni-stat6250): One can use NOPRINT option in PROC MEANS statement to supress the default report and only create the desired output data set.

[Course Textbook Chapter 8, Problem 8]
- *Question* (kamirneni-stat6250): How does one create n-way tables for frequency analysis for more than 2 variables?


[Course Textbook Chapter 8, Problem 10]
- *Question* (kamirneni-stat6250): What is the use of NOFREQ option?


[recipe_for_summarizing_quantitative_values Week 4 Recipe]
- *Question* (kamirneni-stat6250): How does one determine that class statements are needed or not?


[recipe_for_summarizing_qualitative_values Week 4 Recipe]
- *Question* (kamirneni-stat6250): Why in EDA (Exploratory Data Analysis), PROC functions are not utilized instead of PROC MEANS and PROC FREQ being used to replicate the result?


[recipe_for_temporarily_binning_values Week 4 Recipe]
- *Question* (kamirneni-stat6250): In discrete quantitative variables, does taking the high and low options affect the outcome of data, resulting in neglecting of edge cases? 

