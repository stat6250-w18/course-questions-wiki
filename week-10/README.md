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
- Question(dfei-stat6250): In SAS statement, do I have to put $ between attibutes and values in the raw data?
- Answer(dfei-stat6250): It depends on what tpye of values.
- *Question* (shatcher4-stat6250): What order do the variables appear when using column input?
- *Answer* (shatcher4-stat6250): The variables are printed in a report in the order they were listed in. 
- *Question*(kamirneni-stat6250): How does one convert non-standard data in external data to standard one while importing? 
- Question(pcheng14-stat6250):What kind of input specifies the variable's name？
- Answer(pcheng14-stat6250):Column input
- Question (nshrivastava2-stat6250): What happen when input variable contain embedded blank values?
- Question(tchan49-stat6250):Why some variables' names specified by column input followed by a dollar($) sign?
- Answer(tchan49-stat6250):If the variables are character values, and the beginning and ending column locations of the raw data values



[Course Textbook Chapter 16, Problem 5]
- *Question* (cli19−stat6250): Is SAS capable of automatically detecting when observations of variables end and begin?
- *Answer* (cli19−stat6250): Delimiters can be specified to detect the start/end of variable values.
- Question(dfei-stat6250): Is Standard as well as nonstandard data values can be read considered as advantage of column input?
- Answer(dfei-stat6250): No, it is not.
- *Question* (shatcher4-stat6250): What are informats?
- *Question*(kamirneni-stat6250): What is considered to be non-standard data?
- *Answer*(kamirneni-stat6250): Data which includes values containing fractions, $ sign, % sign and commas.
- Question(pcheng14-stat6250): Is the part number of columns that contain the raw data field.
- Answer(pcheng14-stat6250):No, the correct is the total number of columns that contain the raw data field.
- Question (nshrivastava2-stat6250): How one can identify difference betwee Standard Numeric Data and Nonstandard Numeric Data ?
- Question(tchan49-stat6250):What does 'w' represent in $w. informat?
- Answer(tchan49-stat6250):The w represents the field width of the data value or the total number of columns that contain the data field.



[Course Textbook Chapter 16, Problem 7]
- *Question* (cli19−stat6250): How can the "+" and "@" symbols be used to move the input column pointer?
- Question(dfei-stat6250): In INPUT statement, What does the special signal "@" mean?
- *Question* (shatcher4-stat6250): What informat is used to read character data and what informat is used to read standard numeric data?
- *Question*(kamirneni-stat6250): What is @n column pointer control?
- *Answer*(kamirneni-stat6250): It is an absolute pointer control that moves the input pointer to a specific column number.
- Question(pcheng14-stat6250):When should we use INPUT statement correctly read the values for ModelNumber?
- Question (nshrivastava2-stat6250): What is the funtion of INPUT statement?
- Answer(nshrivastava2-stat6250): INPUT statement lists the variables with their corresponding column locations in order from left to right. However, one of the features of column input is the ability to read fields in any order. 
- Question(tchan49-stat6250):How do you reade the values the second field after the forth field? 



[Course Textbook Chapter 16, Problem 8]
- *Question* (cli19−stat6250): What will SAS output if the input value does not fit the specified informat?
- Question(dfei-stat6250): In INPUT statement,  What does the special signal to sperate the numeric values?
- Answer(dfei-stat6250): Do not need anything to sperate.
- *Question* (shatcher4-stat6250): How do you read nonstandard numeric data?
- *Question*(kamirneni-stat6250): How does SAS store numeric values?
- *Answer*(kamirneni-stat6250): By default,SAS stores numeric values as floating point numbers in 8 bytes of storage.
- Question(pcheng14-stat6250):Do we must use the COMMAw.d informat when the values for Cost contain dollar signs and commas?
- Answer(pcheng14-stat6250):Yes, we do.
- Question (nshrivastava2-stat6250): What is @n Column Pointer Control and how it is useful?
- Answer(nshrivastava2-stat6250): The @n is an absolute pointer control that moves the input pointer to a specific column number. The @ moves the pointer to column n, which is the first column of the field that is being read. 
- Question(tchan49-stat6250):When do you need to include 'd' in COMMAw.d informat?
- Answer(tchan49-stat6250):If the data value contains decimal places, a d value is not needed. 



[Course Textbook Chapter 16, Problem 9]
- *Question* (cli19−stat6250): What is the best practice for moving the column pointer when formatting input.
- Question(dfei-stat6250): In INPUT statement, what does "comma6." mean?
- *Question* (shatcher4-stat6250): Explain the three parts of the COMMAw.d informat.
- *Question*(kamirneni-stat6250): What does PAD function do?
- *Answer*(kamirneni-stat6250): It pads each record with blanks so that all data lines have same length.
- Question(pcheng14-stat6250):How to set up the default location of the column pointer control is column 2?
- Question (nshrivastava2-stat6250): What si the funtion of The +n Pointer Control ?
- Answer(nshrivastava2-stat6250): The +n pointer control moves the input pointer forward to a column number that is relative to the current position. The + moves the pointer forward n columns. 
- Question(tchan49-stat6250):What is the default location of the column pointer?



[Course Textbook Chapter 17, Problem 1]
- *Question* (cli19−stat6250): How is the informat modified to read free-format data?
- *Answer* (cli19−stat6250): In some cases, the INPUT statement can be modified to read values until two consecutive blanks are encountered. In other cases, a delimiter can be specified if available using the DLM= option.
- Question(dfei-stat6250): What does "arranged in fixed fields" mean?
- *Question* (shatcher4-stat6250): What is free-format data?
- *Question*(kamirneni-stat6250): What is the rule of field delimiter?
- *Answer*(kamirneni-stat6250): It must not be a character that occurs in a data value.
- Question(pcheng14-stat6250):When the raw data file contains data that is free-format?
- Question (nshrivastava2-stat6250): list input causes SAS to scan the input lines for values rather than reading from specific columns. When the INPUT statement is submitted for processing, the input pointer is positioned at column 1 of the raw data file.
- Answer(nshrivastava2-stat6250): SAS reads the first field until it encounters a blank space. The blank space indicates the end of the field, and the data value is assigned to the program data vector for the first variable in the INPUT statement.Next, SAS scans the record until the next nonblank space is found, and the second value is read until another blank is encountered. Then the value is assigned to its corresponding variable in the program data vector.
- Question(tchan49-stat6250):How do you describe the data that is not arranged in columns or fixed fields?



[Course Textbook Chapter 17, Problem 2]
- *Question* (cli19−stat6250): When modifying list input, what modifiers can be used to read values that contain embedded blanks and nonstandard values?
- *Answer* (cli19−stat6250): The ampersand enables you to read character values that contain single embedded blanks. The colon enables youto read nonstandard data values and character values that are longer than eight characters, but which contain no embedded blanks.
- Question(dfei-stat6250): How many input styles should be used to read the values?
- *Question* (shatcher4-stat6250): What must you remember when using list input?
- *Answer* (shatcher4-stat6250): List input, by default, does not specify column locations; therefore, all fields must be separated by at least one blank or other delimiter, fields must be read in order from left to right, and you cannot skip or re-read fields.
- *Question*(kamirneni-stat6250): Can range of variables be specified using formatted input?
- Question(pcheng14-stat6250):When the raw data file contains data that is free-format?
- Question (nshrivastava2-stat6250): How SAS can read the data value which is saperated by other than blank character.
- Answer(nshrivastava2-stat6250): When characters other than blanks are used to separate the data values, one can use the DLM= option in the INFILE statement to specify a delimiter other than a blank. DLIMITER is an alias for the DLM option.
- Question(tchan49-stat6250):Do you use mixed input to read data that is free-format?



[Course Textbook Chapter 17, Problem 4]
- *Question* (cli19−stat6250): For list input, why isn't it necessary to specify the column?
- *Answer* (cli19−stat6250): Because the data is free-format, you simply name each variable and identify its type. Data will be read in until a blank is encountered.
- Question(dfei-stat6250): Do I have to put some special signal when reading the raw data values in order?
- *Question* (shatcher4-stat6250): How do you specify a range of variables in the INPUT statement?
- *Question*(kamirneni-stat6250): What is the function of MISSOVER?
- Question(pcheng14-stat6250):When should list input be used to read data that is free-format?
- Question (nshrivastava2-stat6250): When PROC IMPORT is used to read a CSV, tab, or other character-delimited file, what procedure SAS uses / follows?
- Question(tchan49-stat6250):Can you use list input to read data that is not free-format?



[Course Textbook Chapter 17, Problem 5]
- *Question* (cli19−stat6250): When data is being read in from DATALINES, how can you specify the delimiters?
- *Answer* (cli19−stat6250): In the INFILE statement, specify datalines as the location of the data, and utilize the DLM= option to declare your delimiters.
- Question(dfei-stat6250): Which SAS statement is the most convenient way to read the raw data file?
- *Question* (shatcher4-stat6250): What does the MISSOVER option do?
- *Answer* (shatcher4-stat6250): The MISSOVER option prevents SAS from reading the next record if, when using list input, it does not find values in the current line for all the INPUT statement variables.
- *Question*(kamirneni-stat6250): Where is DSD used and why?
- Question(pcheng14-stat6250):When should the INFILE statement identifies the location of the external data file?
- Question (nshrivastava2-stat6250): How to read range of variables in the INPUT statement?
- Answer(nshrivastava2-stat6250): When the variable values in the raw data file are sequential and are separated by a blank (or by another delimiter), can specify a range of variables in the INPUT statement. This is especially useful if your data contains similar variables.
- Question(tchan49-stat6250):What is the function of DLM= option? 



[Course Textbook Chapter 17, Problem 7]
- *Question* (cli19−stat6250): Are there any repercussions to defining a variable length that is longer than necessary?
- Question(dfei-stat6250): How to read the data in the raw data file when meeting some speical types of values?
- *Question* (shatcher4-stat6250): What happens when list input is used to read character variables whose values are longer than the default length?
- *Question*(kamirneni-stat6250): What is the order of the variable in the INPUT statement?
- Question(pcheng14-stat6250):Why the LENGTH statement should precede the INPUT statement?
- Question (nshrivastava2-stat6250): How to list a range of specific variables?
- Answer(nshrivastava2-stat6250): By specifying a range in the VAR statement with the PROC PRINT step to list a range of specific variables.
- Question(tchan49-stat6250):Do you have to define the correct length of each character variable? 



[Course Textbook Chapter 17, Problem 8]
- *Question* (cli19−stat6250): What happens when modified list input is not used to read valaues that contain embedded blanks and nonstandard values?
- Question(dfei-stat6250): Can I change values when reading the values in the raw data file?
- *Question* (shatcher4-stat6250): What is free-format data?
- *Question*(kamirneni-stat6250): What must one follow while mentioning the and modifier?
- Question(pcheng14-stat6250):Why modified list input can be used to read the values that contain embedded blanks and nonstandard values?
- Question (nshrivastava2-stat6250):  MISSOVER option works only for missing values that occur at the end of the record. What different method is required to read raw data that contains missing values at the beginning or middle of a record?
- Question(tchan49-stat6250):How do you read the data that contains enbedded blanks and nonstandard values?



[Course Textbook Chapter 17, Problem 10]
- *Question* (cli19−stat6250): Unlike column input, how must list input fields be read in?
- Question(dfei-stat6250): When reading the raw data values in order, can I change the oders of attributes?  
- *Question* (shatcher4-stat6250): What are the differences between the different input styles?
- *Question*(kamirneni-stat6250): How does one determine to chose appropriate style for evaluating raw data?
- Question(pcheng14-stat6250):What kind of the data will contain embedded blanks or nonstandard values?
- Question (nshrivastava2-stat6250): How program reads the raw data file with two consecutive delimeter / comma? 
- Answer(nshrivastava2-stat6250): The DSD ( Delimeter Sensitive Data ) option sets the default delimiter to a comma and treats the two consecutive delimiters as a missing value. Hence, the data is read correctly.
- Question(tchan49-stat6250):When do you have to use modified list input?



[basic_recipe_to_load_remote_delimited_file Week 10 Recipe]
- *Question* (cli19−stat6250): How can you increase the number of values SAS uses to determine the variable type?
- *Answer* (cli19−stat6250): The GUESSINGROWS= option can be used to specify the number of values SAS uses to determine variable type.
- Question(dfei-stat6250): What's the best way to deal with hacker mindset?
- *Question* (shatcher4-stat6250): How does excluding the replace option prevent a pre-existing dataset from being overwritten?
- *Question*(kamirneni-stat6250): When do errors occur while reading a SAS file?
- Question(pcheng14-stat6250):What kind of situation will result the numerous erroes displayed in system log?
- Question (nshrivastava2-stat6250): Infile statement has DELIMITER= option which specifies characters (other than the blank default character) to use as the delimiter that are being read. Common delimiters include comma (,), vertical pipe (|), semi-colon (;) , and the tab. What has been use for a tab in option to define tab delimeter?
- Answer(nshrivastava2-stat6250): In order to specify a tab delimiter, one can use hexadecimal value i.e DLM=’09’x.
- Question(tchan49-stat6250):What are some common delimiters for DELIMITER= statement to define?
-



[adv_recipe_to_load_remote_delimited_file Week 10 Recipe]
- *Question* (cli19−stat6250): When are DATA steps preferred over PROC SQL?
- Question(dfei-stat6250): Is L rec L option commonly used in SAS programming?
- *Question* (shatcher4-stat6250): What does the truncover option do?
- *Question*(kamirneni-stat6250): What does the input statement specifies?
- Question(pcheng14-stat6250):What kind of the data steps can be thought of like a Swiss army knife?
- Question (nshrivastava2-stat6250): What is the function of TERMSTR= option in INFILE statement to read delimited text files?
- Answer(nshrivastava2-stat6250): TERMSTR= option specifies what end-of-line character to use for a file. This option is useful, to share data files that are created on one operating system with another operating system. For example, while working in a UNIX environment, need to read a file that was created under Windows, use TERMSTR=CRLF. Similarly, while working in the Windows environment, need to read a file that was created under UNIX, use TERMSTR=LF. 
- Question(tchan49-stat6250):Can you use proc sql to replace proc means and proc freq?


