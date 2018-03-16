## Week 6 Quiz Questions and Answers

In order to prepare your Week 6 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-6" in your fork of this repo. Then, after all edits have been made/committed, your Week 6 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-6 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 12, Problem 1]
- *Question* (aacharya4−stat6250): While combining two data sets in one-on-one reading using multiple SET statements, what happens when variable of same names occur?
- *Answer* (aacharya4−stat6250): In this case involving same variable names, the values that are read from the second data set replaces the values from the first data set.
- Question (dfei-stat6250): What is the code that can combine two datasets together?
- Answer (dfei-stat6250): "data new dataset name; old dataset name1; old dataset name2; run;"
- *Question* (sbagdi-stat6250): Which method of combining datasets diversifies or scatters the observations from two or more data sets, based on common variables? Which SAS statement is used to do so?
- Question(pcheng14-stat6250):Is the number of observations in the new data set is the number of observations in the highest original data set?
- Answer(pcheng14-stat6250):No, the correct is the number of observation in the smallest original data set.
- Question (tbishaw-stat6250): What are the two functions one-to-one mergin (or combining) allows you to do in SAS?     
- Answer (tbishaw-stat6250): In one-to-one merging you can read different data sets, or you can read the same data set more than once, as if you were reading from separate data sets.  
- Question (nshrivastava2-stat6250): How one-to-one reading data set works ?
- Answer(nshrivastava2-stat6250): The first SET statement reads the first observation from the first data set into the program data vector. Then The second SET statement reads the first observation from the second data set into the program data vector and SAS writes the contents of the program data vector to the new data set. The value from second data set overwrites the value from first data set.  
- Question (ttruong59-stat6250): What happen if the data sets contain variables that have the same names in term of One-to-One Reading?
- Answer (ttruong59-stat6250): The value that are read from the last data set overwrite the values that were read from earlier data sets.
- *Question*(kamirneni-stat6250): In one-to-one reading, what happens when data sets have the same variable names?
- *Answer*(kamirneni-stat6250): The values which are read from the last dataset overwrite the values from the earlier datasets.
- *Question* (aamiri2-stat6250): Is it possible to combine two datasets with the goal of merging variables to match ID or observation numbers?
- *Answer* (aamiri2-stat6250):This is possible, there are many situations where there are multiple variables associated with one ID. Foremost, it is important that any dataset you want to combine should both have matching ID's. You can then combine the first dataset with the second dataset where you will have one ID column and various variables that were in both datasets.
- *Question* (shatcher4-stat6250): What are the different methods of merging?
- *Answer* (shatcher4-stat6250): The methods of merging are one-to-one reading, concatenating, appending, interleaving, and match-merging
- Question (aguenane−stat6250): How does one-to-one merging work in SAS?
- Answer (aguenane−stat6250): You can combine your data sets with one-to-one merging by including multiple SET statements in the DATA step. 



[Course Textbook Chapter 12, Problem 2]
- *Question* (aacharya4−stat6250): What is meant by interleaving of two data sets and how is it accomplished in SAS?
- *Answer* (aacharya4−stat6250): Interleavinng of two or more data sets means taking observations from both datasets which have common observations. It is accomplished using BY statement.
- Question (dfei-stat6250): What is the most important points when programmer will combine two datasets together?
- *Question* (sbagdi-stat6250): What does match-making method of combining does? Which SAS statements are used for match-making?
- Question(pcheng14-stat6250):Waht will the new data set contain in the case of interleaving?
- Answer(pcheng14-stat6250):The new data set contains all the variables from all the input data sets, as well as the total number of records from all input data sets.
- Question (tbishaw-stat6250): What is the difference between appending and concatenating?   
- Question (nshrivastava2-stat6250):To append the observations from one data set to another data set,what are the two ways to do that?
- Answer(nshrivastava2-stat6250): Concatenating and appending are the two ways, by specifying the data set names in the SET statement and PROC APPEND procedure respectively.
- Question (ttruong59-stat6250): According to the textbook, the result is interleaving if you use a BY statement when users concatenate data sets. What if users do not include a BY statement? Is it still considered as interleaving?
- *Question*(kamirneni-stat6250): In concatenation, what does SAS do when length of attributes is different in datasets?
- *Answer*(kamirneni-stat6250): In this case, SAS takes length from first data set that contains the variable.
- *Question* (aamiri2-stat6250): What are the differences between one-to-one merging, concatenating, and appending when combining datasets?
- *Answer* (aamiri2-stat6250): The method of one-to-one merging creates observations that contain all of the variable from each dataset and combines the observations based on their position in each data set. The method of concatenating appends the observations from one dataset to another. The method of appending adds the observations in the second dataset to the end of the original dataset.
- *Question* (shatcher4-stat6250): What happens when a program concatenates data sets?
- Question (aguenane−stat6250): How can you concatenate data sets to append the observations?
- Answer (aguenane−stat6250): You can use the SET statement to specify the data set names to concatenate the data set. 



[Course Textbook Chapter 12, Problem 3]
- *Question* (aacharya4−stat6250): What is the difference between using DATA CONCAT and PROC APPEND procedure to combine observations of two data sets?
- *Answer* (aacharya4−stat6250): In case of CONCAT procedure, a new dataset is created that contains observations from both data sets, while in APPEND procedure SAS does not create a new data set and appends the observations of one data set at the end of another(base) data set.
- Question (dfei-stat6250): What will happen after coding "set dataset name1 dataset name2"?
- Answer (dfei-stat6250): The two datasets will combine together and the dataset 2 will follow the dataset 1.
- *Question* (sbagdi-stat6250): In one-to-one merging method of combining, what is the number of observations in the new data set?
- *Answer* (sbagdi-stat6250): The new dataset in one-to-one merging method has the number of observations equivalent to the number of observations in the smallest original dataset. 
- Question(pcheng14-stat6250):Is it part of the variables from all the input data sets appear in the new data set is correct?
- Answer(pcheng14-stat6250):No, correct should be all of the variables from all the input data sets appear in the new data.
- Question (tbishaw-stat6250): How is interleaving peformed and what are the functions of interleaving?   
- Answer (tbishaw-stat6250): If you use a BY statement when you concatenate data sets, the result is interleaving. Interleaving intersperses observations from two or more data sets, based on one or more common variables.
- Question (nshrivastava2-stat6250): What is the requirement to append procedure?
- Answer(nshrivastava2-stat6250): Only two data sets can be used at a time in one step. The observations in the base data set are not read whereas the variable information in the descriptor portion of the base data set cannot change. The final data set is the original data set with appended observations and that no new data set was created.
- Question (ttruong59-stat6250): What does concatenating datasets mean?
- Answer (ttruong59-stat6250): Concatenating datasets means stacking one dataset on top of the other. For example, given two datasets, records from the second dataset will be added to the end of the first one.
- *Question*(kamirneni-stat6250): In what situations is the FORCE option used in APPEND procedure and other what conditions?
- *Question* (aamiri2-stat6250): When combining a dataset using DATA CONCAT and all variables and observations are combined, what happens if there is missing data?
- *Question* (shatcher4-stat6250): How do you concatenate data sets?
- *Answer* (shatcher4-stat6250): You must use the SET statement to append the observations from one data set to another data set by specifying a list of data set names in the statement.
- Question (aguenane−stat6250): What are some differences between appending and concatenating?



[Course Textbook Chapter 12, Problem 4]
- *Question* (aacharya4−stat6250): How is the new data set that is created with CONCAT by combining two data sets?
- *Answer* (aacharya4−stat6250): The new data set created with CONCAT will have all variables of both data sets and it contains all observations from both data sets. The sequence of observations in the new data set is determined by the sequence in which the data sets are mentioned in the SET statement.
- Question (dfei-stat6250): How to get the values when there are different rows between 2 datasets?
- *Question* (sbagdi-stat6250): What happens if the attributes of the datasets to be concatenated are different? 
- *Answer* (sbagdi-stat6250): If the attributes of the datasets to be concatenated are different, then SAS takes the attribute from the first dataset that contains the variable with that attribute. 
- Question(pcheng14-stat6250):Why the concatenated data sets are read sequentially?
- Question (tbishaw-stat6250): How does Match-Merging Select Data?   
- Question (nshrivastava2-stat6250): What is the functionality of FORCE option in APPEND procedure ?
- Question (ttruong59-stat6250): I see the correct answer from the textbook for problem 4 is “a” that means “missing" or the second observation in Sales.Rep does not contain a value for Sale, so a missing value appears for this variable. What about the first observation? Does a missing value appear for this variable as well?
- *Question*(kamirneni-stat6250): Does any case of duplicity arise when interleaving data, if yes, how is it resolved?
- *Question* (aamiri2-stat6250): What is the difference between PROC APPEND and DATA CONCAT when combining datasets?
- *Question* (shatcher4-stat6250): When concatenating data sets, what would cause an error message?
- Question (aguenane−stat6250): Which statement is used to execute interleaving in SAS? And how is Interleaving used in SAS?
- Answer (aguenane−stat6250): We use the BY statement when concatenating the data set and that results in interleaving. Interleaving intersperses observations form two or more data sets according to the values of the BY variable. 



[Course Textbook Chapter 12, Problem 5]
- *Question* (aacharya4−stat6250): What is match-merging and how is it accomplished in SAS?
- *Answer* (aacharya4−stat6250): Match-merging happens when we need to combine observations from two or more data sets based on values of BY variable. We can use MERGE statement to accomplish this in SAS.
- Question (dfei-stat6250): Will sas send error message that calucate two different types of values when combining two datasets?
- *Question* (sbagdi-stat6250): Which statement differentiates between concatenation and interleaving?
- *Answer* (sbagdi-stat6250): BY statement differentiates between concatenation and interleaving. 
- Question(pcheng14-stat6250):When shoudl we merge the data sets?
- Question (tbishaw-stat6250): What is the code format to renaming a variable in SAS?   
- Answer (tbishaw-stat6250): RENAME=(old-variable-name=new-variable-name)
- Question (nshrivastava2-stat6250): What is the difference between Interleaving and Conacatenate dataset?
- Question (ttruong59-stat6250): What is a mechanism of SAS when users merge the datasets but have variables with the same name in more than one input dataset?
- Answer (ttruong59-stat6250): Values of the same name variable in the second dataset will overwrite the values of the first one.
- *Question*(kamirneni-stat6250): In match-merging processing, what's the advantage of creating PDV to hold one observation at a time by SAS?
- *Question* (aamiri2-stat6250): When combining a dataset, can you combine data based on a variable instead of an observation or ID number? 
- *Question* (shatcher4-stat6250): How are unmatched observations and missing values handled during the match-merge process?
- Question (aguenane−stat6250): What is the process of compiling the data set to prepare it for merging?


[Course Textbook Chapter 12, Problem 7]
- *Question* (aacharya4−stat6250): How are missing values proceessed in case of match-merging of two or more data sets?
- *Answer* (aacharya4−stat6250): When there are missing values for observations based on BY variable, then they appear at the top of the top of the output data set in match-merging.
- Question (dfei-stat6250): How do you prevent the same variables names of values when merge two datasets?
- Answer (dfei-stat6250): Coding rename=(name1=name2) at the end of one of the dataset name.
- *Question* (sbagdi-stat6250): Which option in the SAS prevents the variable values from being overwritten by values of another variable with the same name? In which programming step does over writing take place?
- *Answer* (sbagdi-stat6250): The RENAME option in SAS prevents overwriting of values of variable. This takes place in the DATA step of programming in SAS.
- Question(pcheng14-stat6250):Is there any others solutions way could prevent the values of the variable being overwritten when we merge the two data sets
- Question (tbishaw-stat6250): Why is it important that you reference a variable in the original data set (in a subsetting IF statement, for example) using the DROP= option in the DATA statement?
- Answer (tbishaw-stat6250): If you do not reference the variable then you may get unexpected results and your variable will be uninitialized. 
- Question (nshrivastava2-stat6250): How Interleaving Selects Data works?
- Answer(nshrivastava2-stat6250): When SAS interleaves data sets, observations in each BY group in each data set in the SET statement are read sequentially, in the order in which the data sets and BY variables are listed, until all observations have been processed. The new data set includes all the variables from all the input data sets, and it contains the total number of observations from all input data sets.
- Question (ttruong59-stat6250): What is a main reason users have to prevent the values of the variable from overwritten when merging two datasets that have a same-named variable?
- *Question*(kamirneni-stat6250): What is the process of referencing a variable in the original dataset? 
- *Question* (aamiri2-stat6250): What can be done to prevent a variable from being overwritten when merging two datasets?
- *Answer* (aamiri2-stat6250): To prevent overwriting, you can rename variables by using the RENAME= option in the MERGE statement. Then the old variable and new variable name must be stated to ensure your data does not get overwritten.
- *Question* (shatcher4-stat6250): What happens when you have same-named variables in more than one input data set?
- Question (aguenane−stat6250): How can we rename variables in a dataset in SAS?


[Course Textbook Chapter 12, Problem 9]
- *Question* (aacharya4−stat6250): How can we exclude unmatched observations in the output data set while match-merging two or more data sets?
- *Answer* (aacharya4−stat6250): To exclude unmatched observations in the output data set while match-merging, we need to use IN dataset option along with subsetting IF statement in DATA step.
- Question (dfei-stat6250): Why and How SAS merge some special numberical values?
- *Question* (sbagdi-stat6250): What does SAS does if the type of variable in the DATA= data set is different than in BASE= data set?
- *Answer* (sbagdi-stat6250): If the type of variable in the DATA= data set is different than in BASE= data set, SAS replaces all the values for the variable in the DATA= data set with missing values and keeps the variable type of the variable specified in the BASE= data set. 
- Question(pcheng14-stat6250):What is the smallest observations amount the new data set contain?
- Question (tbishaw-stat6250): Where do observations that have missing values for the BY variable appear?   
- Answer (tbishaw-stat6250): Observations that have missing values for the BY variable appear at the top of the output data set.
- Question (nshrivastava2-stat6250): Explian the match merging processing?
- Answer(nshrivastava2-stat6250): When we submit a DATA step, it is processed in two phases: the compilation phase, in which SAS checks the syntax of the SAS statements and compiles them (translates them into machine code). During this phase, SAS also sets up descriptor information for the output data set and creates the program data vector (PDV), an area of memory where SAS holds one observation at a time. 
- Question (ttruong59-stat6250): How does the DATA step perform or process match-merges? What happen if observations do not match?
- *Question*(kamirneni-stat6250): What is the function of FIRST and LAST in processing?
- *Question* (aamiri2-stat6250): How can you exclude unmatched observation data when combining  a dataset? Does this cause any discrepancies in the final combined dataset?
- *Question* (shatcher4-stat6250): What does the IN= data set option do in excluding unmatched observations?
- *Answer* (shatcher4-stat6250): It creates and names a variable that indicates whether the data set contributed data to the current observations.
- Question (aguenane−stat6250): What is the process of excluding unmatched observations in a data set in SAS?



[basic_recipe_for_combining_data_horizontally Week 6 Recipe]
- *Question* (aacharya4−stat6250): In match merging, what happens when both input data sets with no identical variable names have the same value of unique id?
- *Answer* (aacharya4−stat6250): In match merging, a single row with the unique id is created in the output data set that contains all the variables from both the input data sets.
- Question (dfei-stat6250): What are the most common merge datasets statements when programmer coding?
- *Question* (sbagdi-stat6250): What is the difference between SET statement and MERGE statement used in the compile and execute steps of any SAS program? Can a SET statement be used to specify multiple input datasets? If so, then what difference does it create? 
- *Answer* (sbagdi-stat6250): The prime difference between SET and MERGE statements is that the former is used to specify single input data sets and the later is used to specify multiple input data sets. A SET statement can be used to specify multiple I/P datasets, but in which case the data sets will be merged vertically rather than horizontally. 
- Question(pcheng14-stat6250):Why retain statemnet is used to specify columen order in he output dataset?
- Question (tbishaw-stat6250): When building an analytic file, what statement can be use to specify column order in the output data set?      
- Answer (tbishaw-stat6250): You use a RETAIN statement to specify column order in the output data set. 
- Question (nshrivastava2-stat6250): In match merging, when we are trying to merge two files BY variables. In case of character variables, what happen when variables from one dataset has different case? 
- Answer(nshrivastava2-stat6250): The SAS match-merge is case sensitive. In such case an upper-case letter form one data set will not match with a lower-case of another dataset. However, when we receive data from different sources, the alphabet is not keyed uniformly in upper or lower case. 
- Question (ttruong59-stat6250): When combining data horizontally by using a recipe per provided, is it possible to merge two columns with the same names but they have different variable attributes? 
- *Question*(kamirneni-stat6250): What is the difference in working in DATA step of a RETAIN statement between single and multiple datasets?
- *Answer*(kamirneni-stat6250): The difference is that there are multiple origin points for values in mutliple datasets 
used to fill in the PDV for each row to be included in output.
- *Question* (aamiri2-stat6250): Does MERGE statements and BY statements need to be used conjointly? 
- *Question* (shatcher4-stat6250): In match-merging why is a merge and by statement required?
- Question (aguenane−stat6250): What are some ways of combining two datasets together in SAS?



[adv_recipe_for_combining_data_horizontally Week 6 Recipe]
- *Question* (aacharya4−stat6250): What are some of the advantages of using PROC SQL for combining data sets?
- *Answer* (aacharya4−stat6250): Some of the advantages of using PROC SQL is less lines of code is required. Also, we do not need to use RENAME data set option to avoid overwriting if there are variables of same names in input data sets.
- Question (dfei-stat6250): Can I name same names of columns when I want to merge datasets?
- *Question* (sbagdi-stat6250): What are the three JOIN conditions in PROC SQL? 
- Question(pcheng14-stat6250):Besides using proc sql with a from clause combining the datasteps with a join operation specifying the condition for matching up rows. Is there any other ways can get same result? 
- Question (tbishaw-stat6250): What is the Program Data Vecor (PDV)?  
- Question (nshrivastava2-stat6250): Comparing data step match-merges and proc sql joins, how they are different from each other?
- Question (ttruong59-stat6250): What is a disadvantage of using proc sql?
- Answer (ttruong59-stat6250):proc sql loads all the data into memory before joining so the process will take longer to create join datasets if the datasets are large but there is no issue as long as the data are small enough to fit in memory.
- *Question*(kamirneni-stat6250): What is the data limit beyond which PROC SQL is no longer useful and conventional SAS methods are to be used?
- *Question* (aamiri2-stat6250): What is the benefit of using PROC SQL when combining datasets? Where can we learn more about PROC SQL for self-study?
- *Question* (shatcher4-stat6250): What are the tradeoffs in combining datasets using proc sql?
- Question (aguenane−stat6250): What are the steps to executing a JOIN statement properly?



