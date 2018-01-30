## Week 4 Quiz Questions and Answers

In order to prepare your Week 4 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-4" in your fork of this repo. Then, after all edits have been made/committed, your Week 4 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-4 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************
[Course Textbook Chapter 7, Problem 3]
- *Question* (shatcher4-stat6250): What is the VALUE statement used for?
- *Answer* (shatcher4-stat6250): The VALUE statement is used to define a format for displaying one or more values.
- Question(pcheng14-stat6250): When should we create a format with the VALUE statement?
- Answer(pcheng14-stat6250): Depends on the user, such as solving the mathematic problem.
- *Question* (cli19−stat6250): If a numeric variable ("JobTitle") is formatted to take on character values (i.e. 105='text processor'), does "JobTitle" remain a numeric variable after reformatting it (format JobTitle jobfmt.)?
- *Question* (aacharya4−stat6250): While specifying numeric values in VALUE statement, what are the rules that should be followed?
- *Answer* (aacharya4−stat6250): The numeric values should not end with '$' and they should be enclosed within quotation marks.
- *Question* (jbettonville-stat6250): If a dollar sign is placed in front of a format name, can a combination of character and number labels be used?
- *Answer* (jbettonville-stat6250): The values for a label can either be unique numerical values that are not surrounded by quotation marks, or unique combinations of characters surrounded by quotation marks, but not a combination of the two.
- Question (who7−stat6250): Could you write basic arithmetic function into the categorisation during FORMAT?
- Question (tchan49-stat6250): When is a dollar sign needed when creating a format with the VALUE statement?
- Answer (tchan49-stat6250): The new format’s name must begin with a dollar sign if used with character variable.
- Question (ttruong59-stat6250): What is a naming convention to name a character variable that is created with a VALUE statement?
- Answer (ttruong59-stat6250): The name of a format with a VALUE statement must begin with a dollar sign ($) if it applies to a character variable.
- Question (ldeng11−stat6250): When you use VALUR statement, does the format saved permanently to the dataset?
- *Question* (jcanfield3-stat6250): Who do character variables require a '$' to be assigned formats?

- *Question* (ldai4-stat6250): What is the name of a format with a VALUE statement?
- *Answer* (ldai4-stat6250): The name of a format with a VALUE statement must begin with a dollar sign ($) if it applies to a character variable.

[Course Textbook Chapter 7, Problem 4]
- *Question* (shatcher4-stat6250): How do you define several formats?
- Question(pcheng14-stat6250): How many FORMAT procedures we always used it?
- *Question* (cli19−stat6250): In regards to processing speed and programming efficiency, is specifying the variable format better than  using IF-THEN logic to recode a variable?
- *Question* (aacharya4−stat6250): What are the rules to follow while defining one's own unique format with PROC FORMAT statement?
- *Answer* (aacharya4−stat6250): To define one own's unique format, it must begin with keyword value followed by the format name and ends with semicolon after all labels are defined.
- *Question* (jbettonville-stat6250): In a VALUE statement, could all of the labels be included on the same line, even though this would be a poor stylistic choice? Would the declaration function the same way?
- Question (who7−stat6250): Is there a limit on how many conditions we can set during FORMAT?
- Question (tchan49-stat6250): Is semicolon needed every time after you finish formatting a name to a variable? 
- Answer (tchan49-stat6250): No, semicolon is needed after you finish formatting the last variable. 
- Question (ttruong59-stat6250): Is there any difference in formatting a numeric and character value of a VALUE statement?
- Question (ldeng11−stat6250): What are the naming rules when you use VALUE statement?
- Answer (ldeng11−stat6250): must begin with the $ if apply to the character data; must be a valid SAS name (the same rules as you define the variable); can’t be the same name as an existing SAS format; can’t end in a number; can’t end in a period.
- *Question* (jcanfield3-stat6250): How do you define a permanent format?
- *Answer* (jcanfield3-stat6250): You assign a permanent library using the lib= command.

- *Question* (ldai4-stat6250): How do we use VALUE statement to display one or more values?
- *Answer* (ldai4-stat6250): The statement begins with the keyword VALUE and ends with a semicolon after all the labels have been defined.

[Course Textbook Chapter 7, Problem 5]
- *Question* (shatcher4-stat6250): How do you specify a range of character values with the VALUE statement?
- Question(pcheng14-stat6250): A range of numeric values, such as 50000-99999 is the ranges in the VALUE statement can be specify?
- *Question* (cli19−stat6250): What type of messages should we expect to see in the SAS log if the VALUE range includes a mistake?
- *Question* (aacharya4−stat6250): How to define a list of values (either numeric or character) in the VALUE statement?
- *Answer* (aacharya4−stat6250): A list containing either all numeric or character values can be used in the VALUE statement by seperating each value with commas.
- *Question* (jbettonville-stat6250): Can a combination of character and number labels within quotes be used in a VALUE statement? I.e. could 'A1' and 'A2' be used in a VALUE statement?
- Question (who7−stat6250): What can we do if we need to exceed the range in the VALUE statement?
- Question (tchan49-stat6250): Can the VALUE range specify a combination o character and numeric values? 
- Answer (tchan49-stat6250): No, it cannot. 
- Question (ttruong59-stat6250): Can ranges in VALUE statement specify a list of numeric and character values?
- Answer (ttruong59-stat6250): No. Either all numeric or all character values can specify.
- Question (ldeng11−stat6250): What is the VALUE range used for?
- *Question* (jcanfield3-stat6250): If i'm using number and letters both as characters, would I just add quotes to the numbers as well?

- *Question* (ldai4-stat6250): In the VALUE statement, can a combined list of numeric and character be used?   

[Course Textbook Chapter 7, Problem 6]
- *Question* (shatcher4-stat6250): What do you have to remember when specifying a label for displaying each range?
- Question(pcheng14-stat6250): What the lowest number of characters can be used in a label?
- Answer(pcheng14-stat6250): One
- *Question* (cli19−stat6250): Is it necessary to specify the maximum length of labels?
- *Question* (aacharya4−stat6250): What happens if the format name ends in a period when used in a VALUE statement?
- *Question* (jbettonville-stat6250): Does the 256 character limit for labels include the quotation marks that surround the content of the label?
- Question (who7−stat6250): Would it be wise to use FORMAT on a primary key?
- Question (tchan49-stat6250): Can you use more than 256 characters in a label?
- Question (ttruong59-stat6250): How many characters can be used in label? What if the label exceeds character limits?
- Answer (ttruong59-stat6250): There are 256 characters can be used in label. In case the label exceeds 256 character limit, the system normally returns an error and notifies the user to rename. 
- Question (ldeng11−stat6250): When you add label to your dataset, how many character can you use?
- *Question* (jcanfield3-stat6250): Why is 256 the character limit of a label?

- *Question* (ldai4-stat6250): How can a label be specified in VALUE statement?
- *Answer* (ldai4-stat6250): Enclose the label in quotation marks; limit the label to 256 characters; and use two single quotation marks if you want an apostrophe to appear in the label.

[Course Textbook Chapter 7, Problem 7]
- *Question* (shatcher4-stat6250): What does the keyword LOW do when applied to a character format?
- Question(pcheng14-stat6250): What is the meaning of “OTHER” in keyword?
- *Question* (cli19−stat6250): The book provides an example for a numeric variable, but can "OTHER" also be applied to missing character values?
- *Question* (aacharya4−stat6250): What keywords can be used as a label to depict the lower and upper limits of a variable's value range in VALUE statement?
- *Answer* (aacharya4−stat6250): 'LOW' and 'HIGH' keywords can be used as a label to depict the lower and upper limits of a variable's value range in VALUE statement.
- *Question* (jbettonville-stat6250): In which other contexts might we use keywords LOW, HIGH, and OTHER?
- Question (who7−stat6250): Is there other keywords that can be used when we define our range?
- Question (tchan49-stat6250): Is UNKOWN the keyword you should use to format the missing values? 
- Answer (tchan49-stat6250): NO, it should be OTHER 
- Question (ttruong59-stat6250): OTHER is a keyword to label any missing value that is not specified in a range. Is there any other keyword perform this function? 
- Question (ldeng11−stat6250): How do you label the missing values?
- *Question* (jcanfield3-stat6250): Wouldn't having Miss/Missing as a key word be useful when separating missing and other values?
- *Answer* (jcanfield3-stat6250): This is because a . or ' ' can be used instead.

- *Question* (ldai4-stat6250): Can the keyword OTHER be used in the label missing character values?

[Course Textbook Chapter 7, Problem 8]
- *Question* (shatcher4-stat6250): What do you have to do when associating a format with a variable?
- *Answer* (shatcher4-stat6250): Use the same format name in the FORMAT statement that was specified in the VALUE statemet and place a period at the end of the format name when it is used in the FORMAT statement.
- Question(pcheng14-stat6250): Why should we used FORMAT statement in either a DATA step or a PROC step?
- *Question* (cli19−stat6250): What are the pros and cons to a temporary association versus a permanent association between formats and variables?
- *Question* (aacharya4−stat6250): What can we make a apostrophe to appear in a label?
- *Answer* (aacharya4−stat6250): In order to make a make a apostrophe to appear in a label, we have to use two single quotation marks.
- *Question* (jbettonville-stat6250): If a format is permanently associated with a variable by using FORMAT in a DATA step, can another format be temporarily applied by using FORMAT to choose another format in a PROC step in reference to the same variable?
- Question (who7−stat6250): Can we save the temp FORMAT statement afterward?
- Question (tchan49-stat6250): What should you do if you want to associate a format with a variable permanently? 
- Question (ttruong59-stat6250): Does FORMAT statement replace original data when we place it in a DATA step?
- Question (ldeng11−stat6250): When you use FORMAT statement in the DATA step. What happened?
- Answer (ldeng11−stat6250): You permanently add the formats to the variables.
- *Question* (jcanfield3-stat6250): Does formatting replace original data?
- *Answer* (jcanfield3-stat6250): No it does not, it merely transforms the look of the data, but the original data remains intact.

- *Question* (ldai4-stat6250): What happens when placing the FORMAT statement in a DATA step?

[Course Textbook Chapter 8, Problem 1]
- *Question* (shatcher4-stat6250): What does PROC means do in its simplest form?
- Question(pcheng14-stat6250): When should we use the MEANS procedure in SAS?
- Answer(pcheng14-stat6250): When we solve the mathematic problems, we can use it.
- *Question* (cli19−stat6250): How does PROC MEANS deal with missing values?
- *Answer* (cli19−stat6250): Missing values are not included in the calculation (unless specified with "missing"), and sample size is (N) will show the total number of non-missing rows.
- *Question* (aacharya4−stat6250): Why is the purpose of using MAXDEC option in PROC MEANS statement?
- *Answer* (aacharya4−stat6250): By default, PROC MEANS statement displays the entire width of numeric variable. MAXDEC option in PROC MEANS statement is used to limit it to specified number of decimal places. 
- *Question* (jbettonville-stat6250): How could we create a procedure that invokes specific keywords used in the MEANS statement? I.e. Could a user create a single function that outputs only Median, Mode, and Standard Error when called, without needing to specify this collection of keywords more than once?
- *Answer* (jbettonville-stat6250): This could be accomplished with a macro declaration and call, such as:
```%LET mmse = median mode stderr;
proc means data=mydata &mmse.;
run;
```
- Question (who7−stat6250): What is the main difference between PROC MEAN and PROC SUMMARY?
- Question (tchan49-stat6250): Can you get the median of the data set by the default setting of the MEAN procedure?
- Question (ttruong59-stat6250): What are the default statistics produced by the MEANS procedure?
- Answer (ttruong59-stat6250): By default, MEANS procedure returns the n, mean, min, max, and standard deviation.
- Question (ldeng11−stat6250): What are the default output when you use the MEANS procedure.
- Answer (ldeng11−stat6250): mean, minimum, maximum, n-count, standard deviation.
- *Question* (jcanfield3-stat6250): Why is standard deviation a default statistic instead of variance?

- *Question* (ldai4-stat6250): Which descriptive statistics can be displayed by using PROC MEANS? How to limit statistics?

[Course Textbook Chapter 8, Problem 2]
- *Question* (shatcher4-stat6250): What happens when a statistic is specified in the PROC MEANS statement?
- Question(pcheng14-stat6250): What is the meaning of “Deplane” in SAS?
- *Question* (cli19−stat6250): If variables do not have the same prefixes, what are other ways to select a range of variables?
- *Answer* (cli19−stat6250): Another way to select a range of variables is by using the colon (:). For example, specifying "var m:" will include all variables that start with the letter "m".
- *Question* (aacharya4−stat6250): What is the purpose of using "var" statement in PROC MEANS? 
- *Answer* (aacharya4−stat6250): The purpose of using "var" in PROC MEANS statement is to specify the variables in the dataset for which PROC MEANS is applied.
- *Question* (jbettonville-stat6250): Would the statement "by boarded transfer deplane" create separate analyses breakdowns for each combination of unique values of variables Boarded, Transfer, and Deplane? Does SAS limit the number of breakdowns that can be created in a single PROC step?
- Question (who7−stat6250): What happens when you accidentally put a var that does not exist?
- Question (tchan49-stat6250): Do you use VAR to specify which variables you want to generate the MEAN from?
- Question (ttruong59-stat6250): To limit a PROC MEANS analysis to variables, what can user do? 
- Answer (ttruong59-stat6250): User can add a VAR statement and list only the variable names they want to analyze.
- Question (ldeng11−stat6250): What you should do if you only want to do the analysis on some specific variables?
- *Question* (jcanfield3-stat6250): What is the difference between using var and keep?

- *Question* (ldai4-stat6250): What happens if using VAR statement in the PROC MEANS statement?

[Course Textbook Chapter 8, Problem 4]
- *Question* (shatcher4-stat6250): What is the difference between the BY and CLASS statements?
- Question(pcheng14-stat6250): What is meaning of BY-group processing?
- *Question* (cli19−stat6250): By which variables should the data set be sorted prior to using the BY statement in PROC MEANS?
- *Question* (aacharya4−stat6250): What should be done before using the "BY" group processing?
- *Answer* (aacharya4−stat6250): "BY" group processing needs already indexed or sorted data, hence we need to run PROC SORT before using BY group processing.
- *Question* (jbettonville-stat6250): What happens if you attempt to use BY with data that has not already been sorted or indexed in the order of the BY variables?
- Question (who7−stat6250): When is the best scenario to use BY and when to use VAR?
- Question (tchan49-stat6250): Can you use BY and CLASS interchangeably? What are the differences? 
- Answer (tchan49-stat6250): No, the difference is that BY requires a sorted or indexed dataset. 
- Question (ttruong59-stat6250): Why does user need to run BY group processing statement?
- Question (ldeng11−stat6250): What would happen when you add BY group.
- *Question* (jcanfield3-stat6250): Why do by variables have to be pre-sorted?

- *Question* (ldai4-stat6250): What is CLASS statement and BY statement? What is the BY statement different from the CLASS statement?

[Course Textbook Chapter 8, Problem 7]
- *Question* (shatcher4-stat6250): What can the FREQ procedure be used for?
- Question(pcheng14-stat6250):Besides PROC FREQ, do we have other ways to create a table of frequencies and percentages?
- *Question* (cli19−stat6250): Does PROC FREQ also count the number and percent of missing values?
- *Answer* (cli19−stat6250): Under the "tables" statement, "missing" needs to be specified in order to include rows with missing values to the summary table. Otherwise, SAS excludes these by default and shows the total number missing at the bottom of the table.
- *Question* (aacharya4−stat6250): How is the purpose of using TABLES statement in PROC FREQ ?
- *Answer* (aacharya4−stat6250): The purpose of using TABLES statement in PROC FREQ is to determine the order in which the variables appear in the PROC FREQ report.
- *Question* (jbettonville-stat6250): Does PROC FREQ have any options that would cause character strings that are equal except for capitalization to be considered identical for purposes of counting? I.e. "Place" counted in the same group as "PLACE"?
- Question (who7−stat6250): Is there other keywords taht you can ues like in PROC MEAN?
- Question (tchan49-stat6250): Do you need to use different statements to summarize numeric and character variables?
- Question (ttruong59-stat6250): What is a required statement to create a table of frequencies and percentages for all variables in a dataset?
- Answer (ttruong59-stat6250): The PROC FREQ is the required statement for the FREQ procedure.
- Question (ldeng11−stat6250): Can you use PROC FREQ on character variables?
- *Question* (jcanfield3-stat6250): Is having a frequency table for numeric variables useful?

- *Question* (ldai4-stat6250): What is PROC FREQ statement?
- *Answer* (ldai4-stat6250): The PROC FREQ produces one-way and n-way frequency tables, and it concisely describes your data by reporting the distribution of variable values.

[Course Textbook Chapter 8, Problem 8]
- *Question* (shatcher4-stat6250): How do you specify varirables to be processed by the FREQ procedure?
- Question(pcheng14-stat6250): When should we use the frequency distributions in SAS?
- *Question* (cli19−stat6250): Aside from PROC FREQ or PROC MEANS, what would be an alternative way for examining the distribution for numeric values?
- *Question* (aacharya4−stat6250): Why frequency distributions do not work well with continous and unique values?
- *Question* (jbettonville-stat6250): Under what, if any, circumstances might we want to use FREQ with continuous numerical data rather than categorical data?
- Question (who7−stat6250): Can we combine certain variables to count together in PROC FREQUENCY?
- Question (tchan49-stat6250): Is it better to use PROC FREQ on continuous variables or categorical variables?
- Question (ttruong59-stat6250): Why does frequency distribution work best with categorical values only?
- Question (ldeng11−stat6250): What kind of variables are the best to use frequency distributions?
- *Question* (jcanfield3-stat6250): Are discrete numerical variables more useful than continuous ones when it comes to frequency tables?

- *Question* (ldai4-stat6250): what variables are unsuitable for PROC FREQ processing? Why?

[Course Textbook Chapter 8, Problem 10]
- *Question* (shatcher4-stat6250): How do you create a two-way frequency table?
- *Answer* (shatcher4-stat6250): Join two variables with an asterisk in the TABLES statement of a PROC FREQ step.
- Question(pcheng14-stat6250): Is PROC FREQ the best step to create or produce the table in Figure 8.28 in textbook?
- *Question* (cli19−stat6250): Can the order of the levels in categorical values we see in the table be manipulated?
- *Question* (aacharya4−stat6250): What is the purpose of using NOFREQ option in PROC FREQ statement?
- *Answer* (aacharya4−stat6250): The purpose of using NOFREQ option in PROC FREQ statement is to suppress the cell frequencies.
- *Question* (jbettonville-stat6250): Beyond the options shown in this chapter, what other options can be applied after a slash in a TABLES statement to alter the appearance of a table when using the FREQ procedure?
- Question (who7−stat6250): Can we use SAS to create a table similar to OLAP cube?
- Question (tchan49-stat6250): How can you suppress the row and column percentages by default? 
- Question (ttruong59-stat6250): Is it possible to join 2 variables from 2 different datasets with PROC FREQ?
- Question (ldeng11−stat6250): How can you change the table format?
- *Question* (jcanfield3-stat6250): Can all options of a table be suppressed?

- *Question* (ldai4-stat6250): How does PROC FREQ produce two-way tables?

[recipe_for_summarizing_quantitative_values Week 4 Recipe]
- *Question* (shatcher4-stat6250): What is the purpose of the Output Delivery System (ODS) in SAS?
- Question(pcheng14-stat6250): When should we use “Output Delivery System” in SAS?
- *Question* (cli19−stat6250): Is it possible to subset data in PROC MEANS (i.e. summarizing for x number of observations)?
- *Question* (aacharya4−stat6250): What is the purpose of using "class" statement in PROC MEANS? 
- *Answer* (aacharya4−stat6250): The purpose of using "class" statement in PROC MEANS is to group the PROC MEANS output by the values of variables mentioned in the class statement.
- *Question* (jbettonville-stat6250): How might we use options with PROC MEANS to exclude variables with a number of observations beneath a certain threshold from the output?
- Question (who7−stat6250): Which are the most often uses PROC statement in statistical anlysis?
- Answer (who7−stat6250): PROC MEAN and PROC FREQUENCY are some of the most often use PROC statments.
- Question (tchan49-stat6250): How do you decide when to use PROC MEAN or PROC FREQ?
- Question (ttruong59-stat6250): Both PROC MEANS and PROC FREQ are used to tell SAS which variables to summarize, but what are the major differences between of these 2 statements?
- Question (ldeng11−stat6250): What is the “missing” statement doing here? What happen if you don’t include “missing” statement here?
- *Question* (jcanfield3-stat6250): Can I save a mean as a variable in a dataset?

- *Question* (ldai4-stat6250): What is the NOCUM and NOPERCENT options in the TABLES statement?

[recipe_for_summarizing_qualitative_values Week 4 Recipe]
- *Question* (shatcher4-stat6250): Why should you use the nlevels options?
- Question(pcheng14-stat6250): Have any better way can we summarize the qualitative data in SAS?
- *Question* (cli19−stat6250): Is there a limit on how many levels per variable can be cross-tabulated?
- *Question* (aacharya4−stat6250): How to create two way table using TABLES statement in PROC FREQ?
- *Answer* (aacharya4−stat6250): In PROC FREQ, the TABLES statement contains the keyword "tables" followed by the two variable names joined by asterisk(*). The first varible represents the rows while the second variable represents the columns in PROC FREQ output table.
- *Question* (jbettonville-stat6250): How would the LABEL function be used in a FREQ procedure to alter the headers in the resulting output table?
- Question (who7−stat6250): What are the ways to summarize your data set?
- Answer (who7−stat6250): You can create two-way tables or one-way tables or even present your data as a list.
- Question (tchan49-stat6250): Can you generate a PROC FREQ table for only one variable?
- Question (ttruong59-stat6250): Does PROC FREQ have an option to calculate or compute the content (values) between two rows in the table? or should a user need to add another procedure to do so?
- Question (ldeng11−stat6250): What is “nlevels” statement doing here?
- *Question* (jcanfield3-stat6250): How long has SAS been around for?

- *Question* (ldai4-stat6250): How do we use a LENGTH statement in our DATA step to explicitly define the length of a character variable?

[recipe_for_temporarily_binning_values Week 4 Recipe]
- *Question* (shatcher4-stat6250): What is the difference between the discrete quantitative variable and the continuous quantitative variable?
- Question(pcheng14-stat6250): When should we have to temporarily binning values in SAS?
- *Question* (cli19−stat6250): Does the order of the statements within PROC FREQ matter? That is, can the "format" statement precede the "table" statement?
- *Question* (aacharya4−stat6250): How can we permanently associate a format with a variable?
- *Answer* (aacharya4−stat6250): A varible can be permanently associated with a format if the format is defined in the data step.
- *Question* (jbettonville-stat6250): Can implicit ranges with half-closed intervals be written with the inclusive term on the right-hand side, as in (.36-.67] instead of [.36-.67)?
- *Answer* (jbettonville-stat6250): Changing the format of a label in a VALUE statement from .36-<.67 to .36<-.67 does not cause an error to occur when the statement runs, so this construction appears to be syntactically valid.
- Question (who7−stat6250): how can we avoid edge cases when binning values?
- Answer (who7−stat6250): We can use the keywords low or high to avoid edge cases when binning values.
- Question (tchan49-stat6250): How can you permanently associate a format to a variable? 
- Question (ttruong59-stat6250): Temporarily binning values with a format is a two-step process, can a user make it permanently?
- Question (ldeng11−stat6250): What is “missing list” statement doing here?
- *Question* (jcanfield3-stat6250): Can I format formats?


- *Question* (ldai4-stat6250): Can we use PROC FORMAT statement to bin numerical variables?
- *Answer* (ldai4-stat6250): Yes, we can use PROC FORMAT to bin a numerical variable into categories.

