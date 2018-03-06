## Week 10 Quiz Questions and Answers

In order to prepare your Week 10 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-10" in your fork of this repo. Then, after all edits have been made/committed, your Week 10 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-10 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 16, Problem 1]
- *Question* (aacharya4−stat6250): How can we use column input to read values from raw data file?
- *Answer* (aacharya4−stat6250): When we use column input to read values, we specify the variable name(followed by $ sign in case of character variable) and the start and end location of raw data values.



[Course Textbook Chapter 16, Problem 5]
- *Question* (aacharya4−stat6250): What does 'w' represent in $w informat in INPUT statement?
- *Answer* (aacharya4−stat6250): $w informat is used to read character data. 'w' represents the width of the data field, i.e. the number of columns in the raw data field.



[Course Textbook Chapter 16, Problem 7]
- *Question* (aacharya4−stat6250): what is the use of pointer control in column input to read data from raw data file?
- *Answer* (aacharya4−stat6250): The pointer control is used to move the input pointer from the beginning column to the column whose data field is read from raw data file.



[Course Textbook Chapter 16, Problem 8]
- *Question* (aacharya4−stat6250): When does COMMAw.d informat is to be used in INPUT statement?
- *Answer* (aacharya4−stat6250): COMMAw.d informat is to be used in INPUT statement when the data field read from raw data file contains commas and dollar signs.



[Course Textbook Chapter 16, Problem 9]
- *Question* (aacharya4−stat6250): What is the default location of the column pointer control while reading data from raw data file?
- *Answer* (aacharya4−stat6250): The default location of the column pointer control is column 1, while it reads data from the raw data file.



[Course Textbook Chapter 17, Problem 1]
- *Question* (aacharya4−stat6250): What is the meaning of free format data in a raw data file?
- *Answer* (aacharya4−stat6250): The data contained in a raw data file is called free format data when the data is not arranged in columns of fixed width.



[Course Textbook Chapter 17, Problem 2]
- *Question* (aacharya4−stat6250): How can we read free format data from a raw data file?
- *Answer* (aacharya4−stat6250): List input is used to read free format data from a raw data file where we do not need to give column location of data fields.



[Course Textbook Chapter 17, Problem 4]
- *Question* (aacharya4−stat6250): What are some of the points to consider in regards to data fields while using list input to read free format data from a raw data file?
- *Answer* (aacharya4−stat6250): While using list input, the data fields should be seperated by at least a blank space or delimiter and also data fields are read from left to right where we cannot skip or re-read data fields.



[Course Textbook Chapter 17, Problem 5]
- *Question* (aacharya4−stat6250): What is the use of DLM option in INFILE statement?
- *Answer* (aacharya4−stat6250): The DLM option in the INFILE statement is used to specify the delimiter that seperates the data fields.



[Course Textbook Chapter 17, Problem 7]
- *Question* (aacharya4−stat6250): What is the use of LENGTH statement in SAS?
- *Answer* (aacharya4−stat6250): The LENGTH statement is used to increase the length of a character variable so that character values having length greater than 8 charcaters are not truncated.



[Course Textbook Chapter 17, Problem 8]
- *Question* (aacharya4−stat6250): How can we read data that contain embedded blanks and nonstandard values from a raw data file?
- *Answer* (aacharya4−stat6250): Modified list input is used to read data that contain embedded blanks and nonstandard values from a raw data file.



[Course Textbook Chapter 17, Problem 10]
- *Question* (aacharya4−stat6250): When can we use formatted input while reading data from a raw data file?
- *Answer* (aacharya4−stat6250): We can use formatted input while reading data from a raw data file when the same number of coulmns have to read for each record in the raw data file.



[basic_recipe_to_load_remote_delimited_file Week 10 Recipe]
- *Question* (aacharya4−stat6250): What would have been the value for the delimiter option in the proc import step in case a .tsv file i.e tab seperated file was used?
- *Answer* (aacharya4−stat6250): The delimiter option in proc import step should have been specified as "09"x, which is a hexadecimal representation of a tab character if a .tsv file was used.



[adv_recipe_to_load_remote_delimited_file Week 10 Recipe]
- *Question* (aacharya4−stat6250): What is the purpose of using the "lrcel" option in the INFILE statement in the SAS recipe?
- *Answer* (aacharya4−stat6250): The "lrcel" option is used to set the maximum possible length of each record in the as 32767, otherwise for SAS, the default length of each record is 256 which is very less for real world data.


