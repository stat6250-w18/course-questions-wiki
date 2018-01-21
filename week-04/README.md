## Week 4 Quiz Questions and Answers

In order to prepare your Week 4 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-4" in your fork of this repo. Then, after all edits have been made/committed, your Week 4 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-4 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 7, Problem 3]
- Question (nshrivastava2-stat6250): SAS stores date values as the number of days between January 1, 1960, and a specific date. How one can report the date more meaningful and recognisable?


[Course Textbook Chapter 7, Problem 4]
- Question (nshrivastava2-stat6250): How can we use the format procedure to create the formats? 
- Answer(nshrivastava2-stat6250): The name of a character format must begin with a dollar sign, followed by a letter or underscore, followed by letters, numbers, and underscores. Names for numeric formats must begin with a letter or underscore, followed by letters, numbers, and underscores. A format name cannot end in a number and cannot be the name of a SAS format. 


[Course Textbook Chapter 7, Problem 5]
- Question (nshrivastava2-stat6250): There are many existing SAS formats that you can use. What is the Character formats begin with ? 

[Course Textbook Chapter 7, Problem 6]
- Question (nshrivastava2-stat6250): Why we use Value Statement in PROC FORMAT step?  
- Answer(nshrivastava2-stat6250): You use a VALUE statement in a PROC FORMAT step to specify the way that you want the data values to appear in your output. You define value-range sets to specify the values to be formatted and the formatted values to display instead of the stored value or values. The value portion of a value-range set can include an indiv idual value, a range of values, a list of values, or a keyword. The keyword OTHER is used to define a value to display if the stored data value does not match any of the defined value-ranges.


[Course Textbook Chapter 7, Problem 7]
- Question (nshrivastava2-stat6250): The LOW and HIGH keywords are used to define a continuous range when the lowest and highest values are not known. How does the LOW meant for character value and numeric values? 
- Answer(nshrivastava2-stat6250):  For character values, the LOW keyword treats missing values as the lowest possible values. However, for numeric values, LOW does not include missing values.


[Course Textbook Chapter 7, Problem 8]
- Question (nshrivastava2-stat6250): How SAS Converts Calendar Dates to SAS Date Values? 


[Course Textbook Chapter 8, Problem 1]
- Question (nshrivastava2-stat6250): A PROC FREQ analysis identified invalid and missing values in a data set. Which of these procedures can display the observations that contain invalid or missing values? 
 


[Course Textbook Chapter 8, Problem 2]
- Question (nshrivastava2-stat6250): Which procedures can display the observations that contain invalid or missing values?


[Course Textbook Chapter 8, Problem 4]
- Question (nshrivastava2-stat6250): List the PROC MEANS step creates the statistics?
- Answer(nshrivastava2-stat6250): You can use PROC MEANS to produce summary reports with descriptive statistics. By default, it reports the number of nonmissing values, the mean, the standard dev iation, the minimum, and the maximum value of every numeric variable in a data set.


[Course Textbook Chapter 8, Problem 7]
- Question (nshrivastava2-stat6250): How PROC FREQ Validate the dataset?  
- Answer(nshrivastava2-stat6250): The FREQ procedure can also be used to validate a data set. A one-way frequency table, which displays all discrete values for a variable and reports on missing values, easily identifies the existence of invalid or missing values. You can use the ORDER=FREQ and NLEVELS options to identify duplicate values. After you've identified invalid values, you can use PROC PRINT to display the corresponding observations. 


[Course Textbook Chapter 8, Problem 8]
- Question (nshrivastava2-stat6250): While using the SAS Output Delivery System, Can we open the file on the destination without closing the ODS with an appropriate file type?
- Answer(nshrivastava2-stat6250): No, <ods pdf file="Path/folder/xyz.pdf"> is accompanied by <ods pdf close>, in oder to open the file at the destination. 


[Course Textbook Chapter 8, Problem 10]
- Question (nshrivastava2-stat6250): Why and How  PROC UNIVARIATE is useful?
- Answer(nshrivastava2-stat6250): PROC UNIVARIATE can be more useful because it displays the extreme observations, or outliers. By default, it displays the five highest and five lowest values of the analysis variable, and the number of the observation with each extreme value. You can use the NEXTROBS= option to display a different number of extreme observations.


[recipe_for_summarizing_quantitative_values Week 4 Recipe]
- Question (nshrivastava2-stat6250):  How the CLASS and BY Statements works when included in a PROC MEANS?
- Answer(nshrivastava2-stat6250):  CLASS statement options are also available in the PROC MEANS statement. They affect all CLASS variables. It specifies one or more variables that the procedure uses to group the data. Variables in a CLASS statement are referred to as class variables. Class variables are numeric or character.


[recipe_for_summarizing_qualitative_values Week 4 Recipe]
- Question (nshrivastava2-stat6250): What is Cross-tabulation in SAS ?
- Answer(nshrivastava2-stat6250): Cross tabulation involves producing cross tables also called contingent tables using all possible combinations of two or more variables. In SAS it is created using PROC FREQ along with the TABLES option.


[recipe_for_temporarily_binning_values Week 4 Recipe]
- Question (nshrivastava2-stat6250):  How binning works?
- Answer(nshrivastava2-stat6250): Statistical data binning is a way to group a number of more or less continuous values into a smaller number of "bins". For example, if you have data about a group of people, you might want to arrange their ages into a smaller number of age intervals.PROC HPBIN does not allow empty bins. If an empty bin is detected because of an insufficient number of nonmissing observations, PROC HPBIN issues an error and exits.

