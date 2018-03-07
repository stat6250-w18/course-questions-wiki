## Week 10 Quiz Questions and Answers

In order to prepare your Week 10 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-10" in your fork of this repo. Then, after all edits have been made/committed, your Week 10 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-10 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 16, Problem 1]
Question (ldeng11−stat6250): Can you read the column in custom order other than the sequential order (start from column 1)?
Answer (ldeng11−stat6250): Yes, you can. You just need to write the column you want to read in the first place in your input statement.



[Course Textbook Chapter 16, Problem 5]
Question (ldeng11−stat6250): How do you read the column if the column contain both number and letter?



[Course Textbook Chapter 16, Problem 7]
Question (ldeng11−stat6250): How do you read the first field after you read the follow fields first?
Answer (ldeng11−stat6250): You can use @1 to move the pointer back to the first field.



[Course Textbook Chapter 16, Problem 8]
Question (ldeng11−stat6250): How do you read the field if it contains special signs like dollar sign, or the comma?



[Course Textbook Chapter 16, Problem 9]
Question (ldeng11−stat6250): How many ways you can use to move the pointer back and forward when you read the fileds?



[Course Textbook Chapter 17, Problem 1]
Question (ldeng11−stat6250): What does free format data mean?



[Course Textbook Chapter 17, Problem 2]
Question (ldeng11−stat6250): How do you choose the correct way to read different format input data?



[Course Textbook Chapter 17, Problem 4]
Question (ldeng11−stat6250): How do you read the fields contain character value?
Answer (ldeng11−stat6250): You use $ to indicate that this field contain character value.



[Course Textbook Chapter 17, Problem 5]
Question (ldeng11−stat6250): How do you read the data file use other format like comma, -, other than the blank to seperate each fields?



[Course Textbook Chapter 17, Problem 7]
Question (ldeng11−stat6250): How do you read the data if all fields have different length, and start in different location?



[Course Textbook Chapter 17, Problem 8]
Question (ldeng11−stat6250): How do you read the data if the data in one single field have different format, like some have blanks, some don't?



[Course Textbook Chapter 17, Problem 10]
Question (ldeng11−stat6250): How do you handle if the length of the data in the single field are different?



[basic_recipe_to_load_remote_delimited_file Week 10 Recipe]
Question (ldeng11−stat6250): What is "%sysfunc(getoption(work))/tempfile.txt" doing here?



[adv_recipe_to_load_remote_delimited_file Week 10 Recipe]
Question (ldeng11−stat6250): Can we use the column headers in the orginal file as the file column header in the output file, instead of just simply skipping it over when reading?


