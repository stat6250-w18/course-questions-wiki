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
- *Question* (asharda-stat6250): What are different Column Input Features?
- *Answer* (asharda-stat6250) Column input has several features that make it useful for reading raw data.It can be used to read character variable values that contain embedded blanks.No placeholder is required for missing data. A blank field is read as missing and does not cause other fields to be read incorrectly.  
- *Question* (aacharya4−stat6250): How can we use column input to read values from raw data file?
- *Answer* (aacharya4−stat6250): When we use column input to read values, we specify the variable name(followed by $ sign in case of character variable) and the start and end location of raw data values.
- Question (ttruong59-stat6250): Does the column input have the ability to read fields in any order? 
- Answer (ttruong59-stat6250): Yes, the column input the ability to read fields in any order. Column input needs to specify the variable’s name followed by the $ sign if the values are character values.
- *Question* (ldai4-stat6250): How does the column input read the values in raw data file?
- *Answer* (ldai4-stat6250): Column input specifies the variables'name, followed by a dollar($) sigh if the values are character values, and the beginning and ending column locations of the raw data values.
- *Question* (sbagdi-stat6250): Which input style in SAS can read data fields in any order? How is a blank field taken care of in a column input style?
- *Answer* (sbagdi-stat6250): The column input allows fields to be read in any order. And the blank fields are considered as missing data, and it doesn’t create any problem for any other fields.
- *Question* (who7-stat6250): Could we have read the data using column pointer?
- *Answer* (who7-stat6250): Yes, you can.  Either with @n or +n would work.
- *Question* (akrishnamurthy-stat6250): What is the use of INPUT statement?
- Question (ljiang11−stat6250): What is column input?
- *Answer* (sbagdi-stat6250): Column input is a statement used to read raw data that is stored in an external file. It has the ability to read fields in any order.
- Question (aguenane−stat6250): What variable values makes the data non standard?
- Answer (aguenane−stat6250): If the values include $ sign, the data becomes non standard
- *Question* (ldeng11−stat6250): Can you read the column in custom order other than the sequential order (start from column 1)?
- *Answer* (ldeng11−stat6250): Yes, you can. You just need to write the column you want to read in the first place in your input statement.



[Course Textbook Chapter 16, Problem 5]
- *Question* (cli19−stat6250): Is SAS capable of automatically detecting when observations of variables end and begin?
- *Answer* (cli19−stat6250): Delimiters can be specified to detect the start/end of variable values.
- Question(dfei-stat6250): Is Standard as well as nonstandard data values can be read considered as advantage of column input?
- Answer(dfei-stat6250): No, it is not.
- *Question* (shatcher4-stat6250): What are informats?
- *Answer* (sbagdi-stat6250): Informats are instructions that tell SAS how to read raw data.
- *Answer* (asharda-stat6250):An informat that is associated with an INFORMAT statement behaves like an informat that you specify with a colon (:) format modifier in an INPUT statement.
- *Question*(kamirneni-stat6250): What is considered to be non-standard data?
- *Answer*(kamirneni-stat6250): Data which includes values containing fractions, $ sign, % sign and commas.
- Question(pcheng14-stat6250): Is the part number of columns that contain the raw data field.
- Answer(pcheng14-stat6250):No, the correct is the total number of columns that contain the raw data field.
- Question (nshrivastava2-stat6250): How one can identify difference betwee Standard Numeric Data and Nonstandard Numeric Data ?
- Question(tchan49-stat6250):What does 'w' represent in $w. informat?
- Answer(tchan49-stat6250):The w represents the field width of the data value or the total number of columns that contain the data field.
- *Question* (asharda-stat6250): Which data can you read with  $w. informat?
- *Answer* (asharda-stat6250): The $w. informat enables you to read character data. 
- *Question* (aacharya4−stat6250): What does 'w' represent in $w informat in INPUT statement?
- *Answer* (aacharya4−stat6250): $w informat is used to read character data. 'w' represents the width of the data field, i.e. the number of columns in the raw data field.
- Question (ttruong59-stat6250): What does $w. informat do for reading data?
- Answer (ttruong59-stat6250): The $w. Informat enables users to read character data. The w represents the field width of the data value or the total number of columns that contain the raw data field.
- *Question* (ldai4-stat6250): What does the $w mean?
- *Answer* (ldai4-stat6250): The $w informat enables you to read character data. the w represents the field width of the data value or the total number of columns that contain the raw data field.
- *Question* (sbagdi-stat6250): What is the difference between standard numeric and non-standard numeric data?
- *Question* (who7-stat6250): Can we use normal column input to read character value?
- *Question* (akrishnamurthy-stat6250): What is an informat in INPUT statement ? What are the informats available in SAS ?
- Question (ljiang11−stat6250): What does the informat $w. stand for?
- Question (aguenane−stat6250): If the data is arranged in columns and although it is in sequence,is it required that values begin and end in same column for it to be classified as standard data?
- *Question* (ldeng11−stat6250): How do you read the column if the column contain both number and letter?



[Course Textbook Chapter 16, Problem 7]
- *Question* (cli19−stat6250): How can the "+" and "@" symbols be used to move the input column pointer?
- Question(dfei-stat6250): In INPUT statement, What does the special signal "@" mean?
- *Answer* (asharda-stat6250):It holds an input record for the execution of the next INPUT statement within the same iteration of the DATA step. This line-hold specifier is called trailing @.
- *Question* (shatcher4-stat6250): What informat is used to read character data and what informat is used to read standard numeric data?
- *Question*(kamirneni-stat6250): What is @n column pointer control?
- *Answer*(kamirneni-stat6250): It is an absolute pointer control that moves the input pointer to a specific column number.
- Question(pcheng14-stat6250):When should we use INPUT statement correctly read the values for ModelNumber?
- Question (nshrivastava2-stat6250): What is the funtion of INPUT statement?
- Answer(nshrivastava2-stat6250): INPUT statement lists the variables with their corresponding column locations in order from left to right. However, one of the features of column input is the ability to read fields in any order. 
- Question(tchan49-stat6250):How do you reade the values the second field after the forth field? 
- *Question* (asharda-stat6250): Can Column Input  read character variable values that contain embedded blanks?
- *Answer* (asharda-stat6250): Yes.
- *Question* (aacharya4−stat6250): what is the use of pointer control in column input to read data from raw data file?
- *Answer* (aacharya4−stat6250): The pointer control is used to move the input pointer from the beginning column to the column whose data field is read from raw data file.
- Question (ttruong59-stat6250): What is a major difference between @n and +n pointer control in the INPUT statements?
- *Answer* (sbagdi-stat6250): @n moves the input pointer to a specific column number, while the +n moves the input pointer forward to a column number that is relative to the current position.
- *Question* (ldai4-stat6250): Which INPUT statement can read character values?
- *Question* (sbagdi-stat6250): What are the two types of column control pointers? What do they do?
- *Answer* (sbagdi-stat6250): The to column control pointers are- @n and +n the @n moves the input pointer to a specific column number and +n moves the input pointer to the column number relative to the current position.
- *Question* (who7-stat6250):Is +n equilavent to @n when we go backward?
- *Question* (akrishnamurthy-stat6250): How to read character and standard numeric data with INPUT statement?
- *Answer* (akrishnamurthy-stat6250): The "$w." informat is used to read character data. $ indicates that the variable is a character followed by width of the variable and period indicates end of informat. "w.d" is the informat for reading numeric data. "w" specifies width of the field, period is the delimiter and "d" optionally specifies the number of implied decimal places. 
- Question (ljiang11−stat6250): What does + mean here?
- Question (aguenane−stat6250): What are features of column input?
- *Question* (ldeng11−stat6250): How do you read the first field after you read the follow fields first?
- *Answer* (ldeng11−stat6250): You can use "@1" to move the pointer back to the first field.



[Course Textbook Chapter 16, Problem 8]
- *Question* (cli19−stat6250): What will SAS output if the input value does not fit the specified informat?
- Question(dfei-stat6250): In INPUT statement,  What does the special signal to sperate the numeric values?
- Answer(dfei-stat6250): Do not need anything to sperate.
- *Question* (shatcher4-stat6250): How do you read nonstandard numeric data?
- *Answer* (asharda-stat6250):When they are read into a SAS data set, numeric values are stored in the floating-point format native to the operating environment.
- *Question*(kamirneni-stat6250): How does SAS store numeric values?
- *Answer*(kamirneni-stat6250): By default,SAS stores numeric values as floating point numbers in 8 bytes of storage.
- Question(pcheng14-stat6250):Do we must use the COMMAw.d informat when the values for Cost contain dollar signs and commas?
- Answer(pcheng14-stat6250):Yes, we do.
- Question (nshrivastava2-stat6250): What is @n Column Pointer Control and how it is useful?
- Answer(nshrivastava2-stat6250): The @n is an absolute pointer control that moves the input pointer to a specific column number. The @ moves the pointer to column n, which is the first column of the field that is being read. 
- Question(tchan49-stat6250):When do you need to include 'd' in COMMAw.d informat?
- Answer(tchan49-stat6250):If the data value contains decimal places, a d value is not needed. 
- *Question* (asharda-stat6250): What is a  Formatted Input
- *Answer* (asharda-stat6250): Formatted input is a very powerful method for reading both standard and nonstandard data in fixed fields.
- *Question* (aacharya4−stat6250): When does COMMAw.d informat is to be used in INPUT statement?
- *Answer* (aacharya4−stat6250): COMMAw.d informat is to be used in INPUT statement when the data field read from raw data file contains commas and dollar signs.
- Question (ttruong59-stat6250): What does the COMMAw.d informat do in the INPUT statements?
- Answer (ttruong59-stat6250): The COMMAw.d informat is used to read the raw data values. It also will remove any special characters such as commas from numeric data and store only numeric values in a dataset.
- *Question* (ldai4-stat6250): How does the COMMAw.d informat read the variables with dollar signs and commas? 
- *Question* (sbagdi-stat6250): What is an informat? What is the informat to read standard numeric data and what does that informat stands for?
- *Answer* (sbagdi-stat6250): An informat is an instruction that tells SAS how to read raw data, which could be both, standard and non-standard data values. “w.d” informat reads the standard numeric data, where w stands for field width of raw data values, the period as the delimeter, and the d, the number of implied decimals for the data value.
- *Question* (who7-stat6250): Is there an informat we can use to exclude the dollar sign when reading the data?
- *Question* (akrishnamurthy-stat6250): What is the difference between +n and @n pointer controls?
- *Answer* (akrishnamurthy-stat6250): The @n pointer control moves the input pointer to specific column number. The +n pointer control moves the pointer forward to a column number that is relative to the current position.
- Question (ljiang11−stat6250): What does @ mean here?
- Answer (ljiang11−stat6250): It stands for start from the specified column.
- Question (aguenane−stat6250): What are the 2 input styles which can be used on nonstandard data values?
- Answer (aguenane−stat6250): Column input which can be used to read standard data and formatted input to read both standard and non-standard data.
- *Question* (ldeng11−stat6250): How do you read the field if it contains special signs like dollar sign, or the comma?
- *Answer* (sbagdi-stat6250): The COMMAw.d informat is used to read the fields contating special signs or commas.



[Course Textbook Chapter 16, Problem 9]
- *Question* (cli19−stat6250): What is the best practice for moving the column pointer when formatting input.
- Question(dfei-stat6250): In INPUT statement, what does "comma6." mean?
- *Question* (shatcher4-stat6250): Explain the three parts of the COMMAw.d informat.
- *Answer* (sbagdi-stat6250): Three parts of the COMMAw.d informat are- the informat name; value that specifies the width of the field to be read; an optional value that specifies the number of implied decimal places for a value.
- *Question*(kamirneni-stat6250): What does PAD function do?
- *Answer*(kamirneni-stat6250): It pads each record with blanks so that all data lines have same length.
- Question(pcheng14-stat6250):How to set up the default location of the column pointer control is column 2?
- Question (nshrivastava2-stat6250): What si the funtion of The +n Pointer Control ?
- Answer(nshrivastava2-stat6250): The +n pointer control moves the input pointer forward to a column number that is relative to the current position. The + moves the pointer forward n columns. 
- Question(tchan49-stat6250):What is the default location of the column pointer?
- *Question* (asharda-stat6250): When is PAD option useful ?
- *Answer* (asharda-stat6250): The PAD option is useful only when missing data occurs at the end of a record or when SAS encounters an end-of-record marker before all fields are completely read
- *Question* (aacharya4−stat6250): What is the default location of the column pointer control while reading data from raw data file?
- *Answer* (aacharya4−stat6250): The default location of the column pointer control is column 1, while it reads data from the raw data file.
- Question (ttruong59-stat6250): What is a default location of the column pointer control?
- Answer (ttruong59-stat6250): The default location of the column pointer control is column 1 and a column pointer control is optional for reading the first field.
- *Question* (ldai4-stat6250): What is the column pointer control?
- *Answer* (asharda-stat6250):Column pointer controls indicate the column in which an input value starts.
- *Question* (sbagdi-stat6250): Why is it important to specify the actual field width of raw data in an input statement?
- *Answer* (sbagdi-stat6250): If the exact field width is missing, and we specify a default field width of 8 for all numeric values, SAS will read inappropriate variable values when program executes.
- *Question* (who7-stat6250): It seems there are multiple ways to ready data, which is the most common?
- *Question* (akrishnamurthy-stat6250): How to read variable length records in SAS ?
- Question (ljiang11−stat6250): Where to put the new variable's name?
- Answer (ljiang11−stat6250): Right after INPUT.
- Question (aguenane−stat6250): Like +n, is there any pointer which moves the pointer control in reverse direction?
- *Question* (ldeng11−stat6250): How many ways you can use to move the pointer back and forward when you read the fileds?



[Course Textbook Chapter 17, Problem 1]
- *Question* (cli19−stat6250): How is the informat modified to read free-format data?
- *Answer* (cli19−stat6250): In some cases, the INPUT statement can be modified to read values until two consecutive blanks are encountered. In other cases, a delimiter can be specified if available using the DLM= option.
- Question(dfei-stat6250): What does "arranged in fixed fields" mean?
- *Question* (shatcher4-stat6250): What is free-format data?
- *Answer* (sbagdi-stat6250): A free formatted data is the one which is not arranged in fixed fields or columns.
- *Question*(kamirneni-stat6250): What is the rule of field delimiter?
- *Answer*(kamirneni-stat6250): It must not be a character that occurs in a data value.
- Question(pcheng14-stat6250):When the raw data file contains data that is free-format?
- Question (nshrivastava2-stat6250): list input causes SAS to scan the input lines for values rather than reading from specific columns. When the INPUT statement is submitted for processing, the input pointer is positioned at column 1 of the raw data file.
- Answer(nshrivastava2-stat6250): SAS reads the first field until it encounters a blank space. The blank space indicates the end of the field, and the data value is assigned to the program data vector for the first variable in the INPUT statement.Next, SAS scans the record until the next nonblank space is found, and the second value is read until another blank is encountered. Then the value is assigned to its corresponding variable in the program data vector.
- Question(tchan49-stat6250):How do you describe the data that is not arranged in columns or fixed fields?
- *Answer* (asharda-stat6250):Data in a fixed-width text file is arranged in rows and columns, with one entry per row.No delimiters are used to separate the fields in the file.
- *Question* (asharda-stat6250): What different input styles does SAS provide? 
- *Answer* (asharda-stat6250):  SAS providesthree primary input styles: column, formatted, and list input. 
- *Question* (aacharya4−stat6250): What is the meaning of free format data in a raw data file?
- *Answer* (aacharya4−stat6250): The data contained in a raw data file is called free format data when the data is not arranged in columns of fixed width.
- Question (ttruong59-stat6250): What is a free-format data?
- Answer (ttruong59-stat6250): Raw data can be organized in several ways and free-format typically is not arranged in fixed fields. The fields are often separated by blanks or by some delimiters.
- *Question* (ldai4-stat6250): If the rae file contains free-format data, does the data need to arrange in columns or fixed fields?
- *Question* (sbagdi-stat6250): How can a free formatted data be read from a raw data file?
- *Answer* (sbagdi-stat6250): The LIST INPUT option is used to read free formatted data from the raw data file, where we do not need to specify the column location of the data field.
- *Question* (who7-stat6250): How to use dlm when i was the seperator is be two spaces?
- *Question* (akrishnamurthy-stat6250): How to read free format data in SAS ? Can variables from free format file be read in different orders?
- Question (ljiang11−stat6250): What is free-format data?
- Answer (ljiang11−stat6250): Data is not arranged in columns or fixed fields.
- Question (aguenane−stat6250): What is the $ sign in list input used for?
- Answer (aguenane−stat6250): It used to specify that the character is a variable.
- *Question* (ldeng11−stat6250): What does free format data mean?



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
- *Question* (asharda-stat6250): What different input styles does SAS provide? 
- *Answer* (asharda-stat6250):  SAS providesthree primary input styles: column, formatted, and list input. 
- *Question* (aacharya4−stat6250): How can we read free format data from a raw data file?
- *Answer* (aacharya4−stat6250): List input is used to read free format data from a raw data file where we do not need to give column location of data fields.
- Question (ttruong59-stat6250): Do users need to specify the column locations of the data with list input?
- Answer (ttruong59-stat6250): No, it is not necessary.
- *Question* (ldai4-stat6250): What should be used to read the free-format data?
- *Answer* (ldai4-stat6250): List input should be used to read data that is free-format because you do not need to specify the column locations of the data.
- *Question* (sbagdi-stat6250): What are some of the limitations of LIST input?
- *Answer* (sbagdi-stat6250): LIST input places several restrictions on the type of data that can be read:
Character values greater than 8 characters gets truncated. Data has to be standard numeric or character format. Character values cannot contain embedded delimiters. Missing values must be repreented by a period or some other character. 
- *Question* (who7-stat6250):How can i include the space without it being counted as a seperator?
- *Answer* (who7-stat6250): You can use the modifier &.
- *Question* (akrishnamurthy-stat6250): Can range of variables be specified using formatted input?
- Question (ljiang11−stat6250): How many kind of input style are there in SAS?
- *Answer* (asharda-stat6250):You can use the following different input styles, depending on the layout of data values in the records: list input. column input. formatted input. named input. 
- Question (aguenane−stat6250): What should be specified in list input?
- Answer (aguenane−stat6250): All fields must be separated by blank/delimiter, traverse from left to right and can't skip or re-read fields.
- *Question* (ldeng11−stat6250): How do you choose the correct way to read different format input data?



[Course Textbook Chapter 17, Problem 4]
- *Question* (cli19−stat6250): For list input, why isn't it necessary to specify the column?
- *Answer* (cli19−stat6250): Because the data is free-format, you simply name each variable and identify its type. Data will be read in until a blank is encountered.
- Question(dfei-stat6250): Do I have to put some special signal when reading the raw data values in order?
- *Question* (shatcher4-stat6250): How do you specify a range of variables in the INPUT statement?
- *Question*(kamirneni-stat6250): What is the function of MISSOVER?
- *Answer* (sbagdi-stat6250): The MISSOVER option in INFILE statement is used to prevent SAS from reading the next record when missing values are encountered at the end of the record.
- *Answer* (asharda-stat6250): This option prevents SAS from going to a new input line if it does not find values for all of the variables in the current line of data.
- Question(pcheng14-stat6250):When should list input be used to read data that is free-format?
- Question (nshrivastava2-stat6250): When PROC IMPORT is used to read a CSV, tab, or other character-delimited file, what procedure SAS uses / follows?
- Question(tchan49-stat6250):Can you use list input to read data that is not free-format?
- *Question* (asharda-stat6250): When should list input be used to read free-format data?.
- *Question* (aacharya4−stat6250): What are some of the points to consider in regards to data fields while using list input to read free format data from a raw data file?
- *Answer* (aacharya4−stat6250): While using list input, the data fields should be seperated by at least a blank space or delimiter and also data fields are read from left to right where we cannot skip or re-read data fields.
- Question (ttruong59-stat6250): Is it necessary to list the variable names in the same order when using a list input statement?
- Answer (ttruong59-stat6250): It is required to list the variable names in the same order corresponding to raw data fields and fields can’t be skipped or re-read.
- *Question* (ldai4-stat6250): How does the list input read the values with free-format?
- *Question* (sbagdi-stat6250): When should we specify the range of variables in SAS? Does it make a difference if we specify the range in VAR statement with PROC PRINT step rather than in the INPUT statement?
- *Answer* (sbagdi-stat6250): When the variable values in the raw data file are sequential (specially, if the variables are similar) and are separated by a blank or any other delimiter, we can specify a range of variables in the INPUT statement. When the range is specified with PROC PRINT sep, it is done to list a range of specific variables. 
- *Question* (who7-stat6250): Is there a limit how long a variable can be?
- *Question* (akrishnamurthy-stat6250): what is the DSD option used for in FILE statement?
- Question (ljiang11−stat6250): What is list input?
- Question (aguenane−stat6250): How does SAS input process the dataset?
- *Question* (ldeng11−stat6250): How do you read the fields contain character value?
- *Answer* (ldeng11−stat6250): You use "$" to indicate that this field contain character value.



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
- *Answer* (sbagdi-stat6250): The DLM= option in the INFILE statement is used to specify a delimiter other than a blank.
- *Answer* (asharda-stat6250): The dlm= option can be used to specify the delimiter that separates the variables in your raw data file. 
- *Question* (asharda-stat6250): When do you use DSD option in file statement?.
- *Question* (aacharya4−stat6250): What is the use of DLM option in INFILE statement?
- *Answer* (aacharya4−stat6250): The DLM option in the INFILE statement is used to specify the delimiter that seperates the data fields.
- Question (ttruong59-stat6250): What is a significant reason users need to use the DLM= option in the INFILE statement?
- Answer (ttruong59-stat6250): We need to use the DLM= option in the INFILE statement to specify a delimiter other than a blank.
- *Question* (ldai4-stat6250): How does the INFILE statement work?
- *Answer* (ldai4-stat6250): The INFILE statement identifies the location of the external data file. The DLM=option specifies the colon(:) as the delimiter that separates each field.
- *Question* (sbagdi-stat6250): Why is a DLM= option used in SAS?
- *Answer* (sbagdi-stat6250): Sometimes, in free format data, characters other than blanks are used to separate data values in SAS. In such cases, the DLM= option is used in th INFILE statements.
- *Question* (who7-stat6250): What are the common delimiter?
- *Question* (akrishnamurthy-stat6250): Can free format data be seperated by a delimiter other than blanks?
- Question (ljiang11−stat6250): Can INFILE also import excel file?
- Question (aguenane−stat6250): Will there be any error if field limiter is a character that occurs in data value?
- *Question* (ldeng11−stat6250): How do you read the data file use other format like comma, -, other than the blank to seperate each fields?



[Course Textbook Chapter 17, Problem 7]
- *Question* (cli19−stat6250): Are there any repercussions to defining a variable length that is longer than necessary?
- Question(dfei-stat6250): How to read the data in the raw data file when meeting some speical types of values?
- *Question* (shatcher4-stat6250): What happens when list input is used to read character variables whose values are longer than the default length?
- *Question*(kamirneni-stat6250): What is the order of the variable in the INPUT statement?
- Question(pcheng14-stat6250):Why the LENGTH statement should precede the INPUT statement?
- *Answer* (sbagdi-stat6250): In order to appear first in the data set, the LENGTH statement would precede an INPUT statement.
- Question (nshrivastava2-stat6250): How to list a range of specific variables?
- Answer(nshrivastava2-stat6250): By specifying a range in the VAR statement with the PROC PRINT step to list a range of specific variables.
- Question(tchan49-stat6250):Do you have to define the correct length of each character variable? 
- *Question* (asharda-stat6250): How do you prevent SAS from reading the next record to find the missing values
- *Answer* (asharda-stat6250):You can use the INFILE statement with the MISSOVER option to prevent SAS from reading the next record to find the missing values
- *Question* (aacharya4−stat6250): What is the use of LENGTH statement in SAS?
- *Answer* (aacharya4−stat6250): The LENGTH statement is used to increase the length of a character variable so that character values having length greater than 8 charcaters are not truncated.
- Question (ttruong59-stat6250): What is the default length of character variables when using list input to read raw data?
- *Question* (ldai4-stat6250): Should the LENGTH statement precede the INPUT statement?
- *Question* (sbagdi-stat6250): What does DSD= option stand for? Why does SAS need this option? Is there a difference between MISSOVER option and DSD option?
- *Question* (who7-stat6250): What would happen if the length of varialbe part is after the input part?
- *Question* (akrishnamurthy-stat6250): Can the order of variables be defined along with LENGTH overrides?
- Question (ljiang11−stat6250): Where do we specify the length of a variable? 
- *Answer* (asharda-stat6250):  LENGTH Statement specifies the number of bytes for storing character and numeric variables, or the number of characters for storing VARCHAR variables.
- Question (aguenane−stat6250): What is the condition for specifying a range of character variables?
- *Question* (ldeng11−stat6250): How do you read the data if all fields have different length, and start in different location?



[Course Textbook Chapter 17, Problem 8]
- *Question* (cli19−stat6250): What happens when modified list input is not used to read valaues that contain embedded blanks and nonstandard values?
- Question(dfei-stat6250): Can I change values when reading the values in the raw data file?
- *Question* (shatcher4-stat6250): What is free-format data?
- *Question*(kamirneni-stat6250): What must one follow while mentioning the and modifier?
- Question(pcheng14-stat6250):Why modified list input can be used to read the values that contain embedded blanks and nonstandard values?
- Question (nshrivastava2-stat6250):  MISSOVER option works only for missing values that occur at the end of the record. What different method is required to read raw data that contains missing values at the beginning or middle of a record?
- Question(tchan49-stat6250):How do you read the data that contains enbedded blanks and nonstandard values?
- *Question* (asharda-stat6250): What are some things to remember when you use list input?.
- *Question* (aacharya4−stat6250): How can we read data that contain embedded blanks and nonstandard values from a raw data file?
- *Answer* (aacharya4−stat6250): Modified list input is used to read data that contain embedded blanks and nonstandard values from a raw data file.
- Question (ttruong59-stat6250): What is a major difference between “&” modifier and “:” modifier when using modified list input?
- *Answer* (sbagdi-stat6250): The major difference between the two is that the '&' modifier is used to read embedded balnks, while the ':' modifier can read only those values that have no embedded blanks. 
- *Question* (ldai4-stat6250): Can modified list input be used to read the values that contain embedded blanks and nonstandard values?
- *Question* (sbagdi-stat6250): What are the two types of modifiers used with list INPUT?
- *Answer* (sbagdi-stat6250): To make the list input more versatile, the modifiers are used. The two types are: The ampersand (&)- To read character values that contain embedded blanks, and the colon (:) modifier- To red non-standard data values and character values, which are longer than 8 characters and do not contain embedded blanks.
- *Question* (who7-stat6250): How can we avoid free format data?
- *Question* (akrishnamurthy-stat6250): what is the use of '&' and ':' modifiers in list input?
- *Answer* (akrishnamurthy-stat6250): The ampersand (&) modifier is used to read character values with embedded blanks. The colon(:) modifier is used to read variables greater than 8 characters without any embedded blanks.
- Question (ljiang11−stat6250): How is modified list input different from list input?
- Question (aguenane−stat6250): What are the limitations of list input?
- *Answer* (asharda-stat6250): Fields must be separated by at least one blank (or other delimiter),Fields must be read in order from left to right.,You cannot skip or re-read fields,Data must be in standard character or numeric format.
- *Question* (ldeng11−stat6250): How do you read the data if the data in one single field have different format, like some have blanks, some don't?



[Course Textbook Chapter 17, Problem 10]
- *Question* (cli19−stat6250): Unlike column input, how must list input fields be read in?
- Question(dfei-stat6250): When reading the raw data values in order, can I change the oders of attributes?  
- *Question* (shatcher4-stat6250): What are the differences between the different input styles?
- *Question*(kamirneni-stat6250): How does one determine to chose appropriate style for evaluating raw data?
- Question(pcheng14-stat6250):What kind of the data will contain embedded blanks or nonstandard values?
- Question (nshrivastava2-stat6250): How program reads the raw data file with two consecutive delimeter / comma? 
- Answer(nshrivastava2-stat6250): The DSD ( Delimeter Sensitive Data ) option sets the default delimiter to a comma and treats the two consecutive delimiters as a missing value. Hence, the data is read correctly.
- Question(tchan49-stat6250):When do you have to use modified list input?
- *Question* (asharda-stat6250): How do you specify the length of character variables ?.
- *Answer* (asharda-stat6250):  You can specify the length of character variables by using the LENGTH statement.
- *Question* (aacharya4−stat6250): When can we use formatted input while reading data from a raw data file?
- *Answer* (aacharya4−stat6250): We can use formatted input while reading data from a raw data file when the same number of coulmns have to read for each record in the raw data file.
- Question (ttruong59-stat6250): What kind of data can contain embedded blanks or nonstandard values?
- Answer (ttruong59-stat6250): free-format data
- *Question* (ldai4-stat6250): Which input can be used to read the values for year?
- *Answer* (asharda-stat6250): The INPUT statement reads raw data from instream data lines or external files into a SAS data set. You can use the following different input styles, depending on the layout of data values in the records: list input. column input. formatted input. named input. You can also combine styles of input in a single INPUT statement.
- *Question* (sbagdi-stat6250): What does a LENGTH statement in SAS used for?
- *Answer* (sbagdi-stat6250): LENGTH statement in SAS is used to increase the character length of the variables, whose character lengths are greater than 8, so that they do not get truncated.
- *Question* (who7-stat6250): Would it cause an error if i put & and dlm = " " in the same step?
- *Question* (akrishnamurthy-stat6250): Can mixed input styles be used in same INPUT statement ?
- Question (ljiang11−stat6250): Can modified list input read nonstandard values?
- Question (aguenane−stat6250): What is the condition for MISSOVER option to be working?
- *Answer* (sbagdi-stat6250): The MISSOVER function works only for missing values that occue at the end of the record.
- *Question* (ldeng11−stat6250): How do you handle if the length of the data in the single field are different?



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
- *Question* (asharda-stat6250): Why is the "replace" option excluded?
- *Answer* (sbagdi-stat6250): In order to prevent pre-existing data-set in the owrk library from over written. 
- *Answer* (asharda-stat6250):  "replace" option has been excluded in order to prevent a pre-existing dataset already named "frpm_raw" in the Work library from being overwritten.
- *Question* (aacharya4−stat6250): What would have been the value for the delimiter option in the proc import step in case a .tsv file i.e tab seperated file was used?
- *Answer* (aacharya4−stat6250): The delimiter option in proc import step should have been specified as "09"x, which is a hexadecimal representation of a tab character if a .tsv file was used.
- Question (ttruong59-stat6250): Why is “dlm” assigned for DBMS= option in proc import?
- *Question* (ldai4-stat6250): How do we use INFILE to load a exteral file? 
- *Question* (sbagdi-stat6250): What is the delimiter if instead of a .csv file, the file is .tsv or for a pipe separated value file? What does .tsv stand for?
- *Answer* (sbagdi-stat6250): The .tsv stands for tab separated value file with “09”x, which is the ASCII hexadecimal representation for a tab character as its delimiter. For a pipe separated value file, a ‘|’ is used as its delimiter.
- *Question* (who7-stat6250): How do we use tab as a limiter?
- *Answer* (who7-stat6250): we can use dlm = "09"x
- *Question* (akrishnamurthy-stat6250): How does PROC import behave for delimited text files ?
- Question (ljiang11−stat6250): Can PROC IMPORT import .R file or .py file?
- Question (aguenane−stat6250): In what parts of SAS, can delimiters be used?
- *Question* (ldeng11−stat6250): What is "%sysfunc(getoption(work))/tempfile.txt" doing here?



[adv_recipe_to_load_remote_delimited_file Week 10 Recipe]
- *Question* (cli19−stat6250): When are DATA steps preferred over PROC SQL?
- *Answer* (asharda-stat6250):  Like proc sql, data steps can be thought of like a Swiss army knife since they can be used to accomplish many different types of tasks, including importing raw text files (including non-delimited, free-form or fixed-column width formats), data cleaning, copying datasets, combing datasets, and even simulate many of the featues of procs like proc means and proc freq.
- Question(dfei-stat6250): Is L rec L option commonly used in SAS programming?
- *Question* (shatcher4-stat6250): What does the truncover option do?
- *Answer* (sbagdi-stat6250): Truncate overrun allows incomplete data to be read.
- *Question*(kamirneni-stat6250): What does the input statement specifies?
- Question(pcheng14-stat6250):What kind of the data steps can be thought of like a Swiss army knife?
- Question (nshrivastava2-stat6250): What is the function of TERMSTR= option in INFILE statement to read delimited text files?
- Answer(nshrivastava2-stat6250): TERMSTR= option specifies what end-of-line character to use for a file. This option is useful, to share data files that are created on one operating system with another operating system. For example, while working in a UNIX environment, need to read a file that was created under Windows, use TERMSTR=CRLF. Similarly, while working in the Windows environment, need to read a file that was created under UNIX, use TERMSTR=LF. 
- Question(tchan49-stat6250):Can you use proc sql to replace proc means and proc freq?
- *Question* (asharda-stat6250): Why are the options dlm and truncover used?.
- *Answer* (asharda-stat6250):  The option dlm to set the delimiter used in the file, the truncover option to allow incomplete data to be read.
- *Question* (aacharya4−stat6250): What is the purpose of using the "lrcel" option in the INFILE statement in the SAS recipe?
- *Answer* (aacharya4−stat6250): The "lrcel" option is used to set the maximum possible length of each record in the as 32767, otherwise for SAS, the default length of each record is 256 which is very less for real world data.
- Question (ttruong59-stat6250): What is an advantage of using a data step rather than using proc import in the basic version of the recipe to load remote delimited file?
- Answer (ttruong59-stat6250): Users can add do-loops and if-then statement with a data step as needed when loading remote delimited file.
- *Question* (ldai4-stat6250): Can the PROC IMPORT read a Specific Delimited File?
- *Question* (sbagdi-stat6250): What does a ‘lrecl’ option do in SAS?
- *Answer* (sbagdi-stat6250): The ‘lrecl’ option is used to specify the maximum possible line length (logical record length), which is 256 by default, but is too short for most real-world file. 
- *Question* (who7-stat6250): How do we determine the value of lrecl?
- *Question* (akrishnamurthy-stat6250): Will a data step to transform text file into SAS dataset be better than a PROC sql 
- Question (ljiang11−stat6250): How can PROC SQL import files?
- Question (aguenane−stat6250):Where is truncover applicable?
- *Question* (ldeng11−stat6250): Can we use the column headers in the orginal file as the file column header in the output file, instead of just simply skipping it over when reading?


