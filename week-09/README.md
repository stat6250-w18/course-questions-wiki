## Week 9 Quiz Questions and Answers

In order to prepare your Week 9 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-9" in your fork of this repo. Then, after all edits have been made/committed, your Week 9 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-9 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 14, Problem 1]
- Question(dfei-stat6250): Can DO loops be used to combine DATA and PROC steps?
- Answer(dfei-stat6250): No, it can not.
- *Question* (aacharya4−stat6250):  What is the default value by which index variable is incremented in iterative DO statement in SAS?
- *Answer* (aacharya4−stat6250): The default value by which index variable is incremented in iterative DO statement in SAS is 1.
- *Question* (asharda-stat6250): Why do you need a DO loop?
- *Answer* (asharda-stat6250): You can execute SAS statements repeatedly by placing them in a DO loop. 
- *Question* (shatcher4-stat6250): What can DO loops be used for?
- *Answer* (shatcher4-stat6250): DO loops can execute any number of times in a single iteration of the DATA step, it can also generate data, conditionally execute statements, and read data.
- *Question* (ldai4-stat6250): What is DO loops?
- *Answer* (ldai4-stat6250): The DO loops are DATA step statement and cannot be used in conjunction with PROC steps.
- Question (tbishaw-stat6250): How can we execute a SAS statement repeatedly?     
- Answer (tbishaw-stat6250): We can execute a SAS statement repeatedly by placing them in a DO loop. Do loops can execute any number of times in a single iteration of the DATA step.  
- *Question*(kamirneni-stat6250): Which statements can be used with DO loop?
- *Answer*(kamirneni-stat6250): DATA steps can be used but not PROC steps.
- *Question* (cli19−stat6250): What can be used instead to run DATA and PROC steps iteratively?
- *Answer* (cli19−stat6250): MACROS can be written to process and automate some repetitive DATA and PROC steps.
- Question (nshrivastava2-stat6250): What is the use of Do Loop?
- Answer(nshrivastava2-stat6250): DO loops process groups of SAS statements repeatedly, reducing the number of statements that are required in repetitive calculations. 
- Question (ttruong59-stat6250): Can DO loops be used to combine DATA and PROC steps?
- Answer (ttruong59-stat6250): No. DO loops are DATA step statements and can’t be used to combine with PROC steps. 
- Question(tchan49-stat6250):Can you use Proc Print statement for DO loops?
- Answer(tchan49-stat6250):No, DO loops cannot be used for Proc steps. 
- Question (who7−stat6250): Is there any special occasion where the Do loop can be used in the PROC step?
- *Question* (jcanfield3-stat6250): Are there any types of statements that can be use both data and proc steps?
- Question (ldeng11−stat6250): What is DO loop using for?
- Answer (ldeng11−stat6250): DO loops can process a group of statement for any number of times rather than only one time. This can greatly reduce the number of statements for the repetitive calculation.
- Question (ljiang11−stat6250): Can DO loops be used in PROC steps?
- *Question* (akrishnamurthy-stat6250): Can DO loops include DATA and PROC steps?
- Answer(asharda-stat6250): No, it can not
- *Question* (sbagdi-stat6250): What is DO statement used for?
- *Answer* (sbagdi-stat6250): Do statement process SAS statements repeatedly, thereby reducing the number of statements required for repeted calculations.
- Question(pcheng14-stat6250):What kind of step statements are DO loops and cannot be used in conjunction with PROC steps?
- Answer(pcheng14-stat6250):DATA step statements.
- Question (aguenane−stat6250): What can be changed within the DO loop?
- Answer (aguenane−stat6250): The value of index variable can be changed within the loop.



[Course Textbook Chapter 14, Problem 2]
- Question(dfei-stat6250): How to determind the times DO loop execute?
- Answer(dfei-stat6250): "do month=1 to some value" is the factor to determind the times DO loop execute.
- *Question* (aacharya4−stat6250):  How can we change the value of incrementing or decrementing the index variable by 1 in iterative DO statement?
- *Answer* (aacharya4−stat6250): To change the incrementing or decrementing the index variable by 1 in iterative DO statement, we use the BY clause. For eg: do i = 1 to 5 by 0.5;
- *Question* (asharda-stat6250): How are number of iterations determined in a DO step?.
- *Answer* (asharda-stat6250): The number of iterations is determined by the DO statement's stop value.
- *Question* (shatcher4-stat6250): What is the purpose of the index variable in a DO loop?
- *Question* (ldai4-stat6250): Is the number of iterations determined by the DO statement's stop value?
- Question (tbishaw-stat6250): Which variables must be specified when creating a DO loop?
- *Question*(kamirneni-stat6250): What should one do to change increment value?
- *Answer*(kamirneni-stat6250): Using BY clause,and specifying the value one can change the increment value.
- *Question* (cli19−stat6250): Within a DO loop, is it possible to skip values in the iteration range specified?
- *Answer* (cli19−stat6250): Yes, you can include the BY option after the statement's stop value to specify by what value to increment each step.
- Question (nshrivastava2-stat6250): How the Do Loop iteration executes?
- Answer(nshrivastava2-stat6250): During each iteration of a DO loop, new values are created in the SAS program data vector. When the loop's index value exceeds the stop value, the DO loop stops, and processing continues with the following DATA step statement
- Question (ttruong59-stat6250): Is it possible that the value of the index can be changed within the loop?
- Answer (ttruong59-stat6250): Yes. A DO loop enables users to achieve the same results with fewer statements and the value of the index can be changed within the loop.
- Question(tchan49-stat6250):What is the number of iterations determined by?
- Answer(tchan49-stat6250):It is determined by the DO statement's stop value. 
- Question (who7−stat6250): Can the DO loop be consider similar to a FOR loop in R?
- Answer (who7-stat6250): It is very similar.  The way it goes through their iteration are very similar.
- *Question* (jcanfield3-stat6250): Why does the do loop resolve at the top rather than at the end?
- Question (ldeng11−stat6250): How do you know how many times of excution of the statements in the DO loop? 
- Answer (asharda−stat6250): By looking at the stoping value after DO statement.
- Question (ljiang11−stat6250): How to determine how many times DO loop executed?
- Answer (ljiang11−stat6250): By looking at the stoping value after DO statement.
- *Question* (akrishnamurthy-stat6250): What is the significance of index variable in a DO loop?
- *Question* (sbagdi-stat6250): How can we terminate an iterative DO statement in SAS program?
- *Answer* (sbagdi-stat6250): The iterative DO statement in SAS can be terminated  by a END statement.
- Question(pcheng14-stat6250):What is the number of iterations determined by?
- Answer(pcheng14-stat6250):It is DO statement's stop value.
- Question (aguenane−stat6250): What is the optional BY clause used for?
- Answer (aguenane−stat6250): It is used to specify an increment value for index variable.



[Course Textbook Chapter 14, Problem 3]
- Question(dfei-stat6250): Does "do count = 1 to some value * percentage" correct?
- Answer(dfei-stat6250): No, it does not.
- *Question* (aacharya4−stat6250):  How can we terminate an iterative DO statement in SAS?
- *Answer* (aacharya4−stat6250): We can terminate an iterative DO statement in SAS by using the END statement.
- *Question* (asharda-stat6250): Using a DO loop how will you perform repetitive calculations starting at 1 and looping 25 times. 
- *Answer* (asharda-stat6250): do count=1 to 25;
- *Question* (shatcher4-stat6250): What are the different conditions that execute the DO loop?
- *Question* (ldai4-stat6250): Can the DO loop statement be used to calculate a balance with a constant interest?
- Question (tbishaw-stat6250): What happens when you place an explicit OUTPUT statement in a DATA step?
- Answer (tbishaw-stat6250): It overrides automatic output, causing SAS to add an observation to the data set only when the explicit OUTPUT statement is executed.
- *Question*(kamirneni-stat6250): What is a purpose of INDEX statement?
- *Answer* (sbagdi-stat6250): The INDEX variable stores the value of the current iteration of the DO loop.
- *Question* (cli19−stat6250): How else can the start and stop values in a DO statement be incremented, if not with the BY option?
- Question (nshrivastava2-stat6250): To construct an iterative DO loop, What are the conditions an index variable execute the loop?
- Question (ttruong59-stat6250): What happens if users do not include END statement in DO loop along with other SAS statements?
- Question(tchan49-stat6250):Are there any rules to define the index-variable? 
- Question (who7−stat6250): Does the increment in the DO loop have a minimum?
- Answer (who7-stat6250): The default increment is 1 unless otherise specified.
- *Question* (jcanfield3-stat6250): Can you use a statement like "do count=1 to (x*n)", or would x*n need to be pre-defined first?
- Question (ldeng11−stat6250): What is the syntax of DO loop?
- *Answer* (asharda-stat6250): The basic iterative DO statement in SAS has the syntax DO value = start TO stop. An END statement marks the end of the loop.
- Question (ljiang11−stat6250): Can DO loops followed by a variable that has assigned value?
- *Question* (akrishnamurthy-stat6250): How should the index variables be defined for nested DO loops?
- *Question* (sbagdi-stat6250): How can we increase or decrease the value of index variable by 1 in an interactive DO statement?
- *Answer* (sbagdi-stat6250): The BY clause is used to change the value of index variable in a Do statement. For instance- i= 1-10 by 2.
- Question(pcheng14-stat6250):When should we Use a DO loop to perform repetitive calculations?
- Answer(pcheng14-stat6250):Depneds on the question, for example, we can use a DO loop to perform repetitive calculations starting at 1 and looping 15 times.
- Question (aguenane−stat6250): During compilation, why is the program data vector created for a dataset?



[Course Textbook Chapter 14, Problem 4]
- Question(dfei-stat6250): How many stored values happen if one DO loop execute?
- *Question* (aacharya4−stat6250):  How can we stop iterating a DO statement in SAS based on a condition?
- *Answer* (aacharya4−stat6250): To stop iterating a DO statement in SAS based on a condition; we need to use the WHILE or UNTIL clause.
- *Question* (asharda-stat6250): What is the use of TO clause in DO statement
- *Answer* (asharda-stat6250): The TO clause specifies the stop value. The stop value is the last index value that executes the DO loop. 
- *Question* (shatcher4-stat6250): When a DO loop is executed, what does the DATA step do?
- *Question* (ldai4-stat6250): Why do we need to specify an index variable when creating a DO loop with the iterative DO statement?
- *Answer* (ldai4-stat6250): The index variable stores the value of the current iteration of the DO loop.
- Question (tbishaw-stat6250): What is the difference between the DO UNTIL and DO WHILE statements? 
- *Answer* (asharda-stat6250): The only difference between do while and do until is that the first one loops is execute as long as the condition is true, while the second one loops execute as long as the condition is false. 
- *Question*(kamirneni-stat6250): What is the difference between using DO loop with WHILE and UNTIL clause?
- *Answer*(kamirneni-stat6250): In case of DO loop with WHILE clause, first the condition is evaluated before executing the statements within the loop. In case of DO loop with UNTIL clause, it executes at least one time because the condition is evaluated at the end of loop.
- *Question* (cli19−stat6250): How does SAS know it has reached the end of a DO loop?
- *Answer* (cli19−stat6250): When the value that is next incremented falls outside the stop value, the DO loop ends.
- Question (nshrivastava2-stat6250): Can we create labels for numaric series using Do loops.
- Answer(nshrivastava2-stat6250): SAS programmers often need to create labels for a numbered series of variables with a common prefix. Array and DO loops can not be used here since the LABEL statement is a declarative statement.
- Question (ttruong59-stat6250): How to specify increments the index variable by even numbers?
- Question(tchan49-stat6250):If the iteration is 1-12, after the twelfth execution of DO loop, what is the value that is incremented to?
- Answer(tchan49-stat6250):13, however, the DO loop only executes 12 times. 
- Question (who7−stat6250): Can we set arbituary variable for the count in a DO loop?
- *Question* (jcanfield3-stat6250): Can SAS detect an infinite loop, or does it get stuck iterating it until manually stopped?
- Question (ldeng11−stat6250): What is the value of the index variable after the last step of the DO loop?
- *Answer* (sbagdi-stat6250): The STOP values of the loop is the last value of the index variable.
- Question (ljiang11−stat6250): How would DO loop execute after it reaches the maximum set value?
- Answer (ljiang11−stat6250): It will increment one more step and ends after it finds the condition doesn't suffice.
- *Question* (akrishnamurthy-stat6250): Should index variables always be incremented by 1? How to define list of values for index variables?
- *Question* (sbagdi-stat6250): What does a TO clause in a a DO statement used for?
- Question(pcheng14-stat6250):Why the current values are written to the data set when DATA step at the bottom?
- Question (aguenane−stat6250): What is the process of creating each observation of DO loop?
- Answer (aguenane−stat6250): Write the OUTPUT statement inside DO loop.



[Course Textbook Chapter 14, Problem 5]
- Question(dfei-stat6250): Do I need OUTPUT statement in DO loop execute?
- *Question* (aacharya4−stat6250):  What is the difference between using DO loop with UNTIL clause and DO loop with WHILE clause?
- *Answer* (aacharya4−stat6250): In case of DO loop with UNTIL clause, it executes at least one time because the condition is evaluated at the end of loop. In case of DO loop with WHILE clause, first the condition is evaluated before executing the statements within the loop.
- *Question* (asharda-stat6250): What is the use of OUTPUT statement ?
- *Answer* (asharda-stat6250): The OUTPUT statement overrides the automatic output at the end of the DATA step. 
- *Question* (shatcher4-stat6250): Why does an OUTPUT statement need to be placed inside a DO loop?
- *Answer* (sbagdi-stat6250): To create an obseravtion for each iteration.
- *Question* (ldai4-stat6250): Does the OUTPUT statement override the automatic output at the end of the dATA step?
- Question (tbishaw-stat6250): Is the WHILE expression evaluated before or after the execution of the DO loop?
- Answer (tbishaw-stat6250): The WHILE expression is evaluated before the execution of the DO loop. 
- *Question*(kamirneni-stat6250): Does the OUTPUT statement make any difference to end DO loop in a DATA statement?
- *Question* (cli19−stat6250): What are the differences in output data sets when the OUTPUT statement is included versus when it is not?
- Question (nshrivastava2-stat6250): What is the syntax for Do Loop in SAS?
- Question (ttruong59-stat6250): When does OUTPUT statement write observations?
- Answer (ttruong59-stat6250): The OUTPUT statement writes the current observations to a SAS dataset immediately, not a the end of the DATA step. But the observation will be written to the dataset listed if no dataset name is specified.
- Question(tchan49-stat6250):What is the function of OUTPUT in DO Loop?
- *Answer* (asharda-stat6250): It  tells SAS to write observations to the data set or data sets that are being created
- Question (who7−stat6250): What will happen if we did not include end after the DO loop?
- *Question* (jcanfield3-stat6250): Does the year variable get deleted at the end of the data step (Does it still = 2005 after)?
- Question (ldeng11−stat6250): What is the OUTPUT statement doing?
- Answer (ldeng11−stat6250): The OUTPUT statement is used to overwrite the automatic output, so the DATA step will write the obversation for each step.
- Question (ljiang11−stat6250): Is the 15th loop stored in the dataset?
- *Question* (akrishnamurthy-stat6250): Will the DO loop stop iteration once the stop value is reached for index variable or after the stop value?
- *Question* (sbagdi-stat6250): What makes the iterative DO statement's execution stop in a SAS programming?
- *Answer* (sbagdi-stat6250): When the index variable's value exceeds that of a stop variable, the execution of iterative DO statement stops going further.
- Question(pcheng14-stat6250):When the OUTPUT statement will overrides the automatic output at the end of the DATA step?
- Question (aguenane−stat6250): What is the function of drop counter?



[Course Textbook Chapter 14, Problem 6]
- Question(dfei-stat6250): How to count observations in the data set contain?
- *Question* (aacharya4−stat6250):  When does the execution of an iterative DO statement stop?
- *Answer* (aacharya4−stat6250): The execution of an iterative DO statement stops when the index variable's value exceeds the value of the stop variable, hence the execution of the DO loop stops.
- *Question* (asharda-stat6250): What is the numbe rof observations based on ?
- *Answer* (asharda-stat6250): The number of observations is based on the number of times the OUTPUT statement executes.
- *Question* (shatcher4-stat6250): How do you specify how many times a DO loop executes with a variable list?
- *Question* (ldai4-stat6250): What determines the number of observations in DO loop statement?
- *Answer* (ldai4-stat6250): The number of observation is based on the number of times the OUTPUT statement executes.
- Question (tbishaw-stat6250): If the condition for the WHILE expression is initally false, does the DO loop execute?
- *Question*(kamirneni-stat6250): What is the value of index at the end of DO loop?
- *Answer*(kamirneni-stat6250): It is always one value greater than specified, but since the value exceeds the stop value, the DO loop ends.
- *Question* (cli19−stat6250): Why isn't the "value" variable defined in DATA step reassigned to 2000 for every row in the output data set?
- Question (nshrivastava2-stat6250): What is the role of BY clause in Do Loops statement?
- Answer(nshrivastava2-stat6250): The optional BY clause specifies an increment value for the index variable. Typically, you want the DO loop to increment by 1 for each iteration. If you do not specify a BY clause, the default increment value is 1.
- Question (ttruong59-stat6250): Is the number of observations based on the number of times the OUTPUT statement executes?
- Answer (ttruong59-stat6250): Yes. The number of observations is based on the number of times the OUTPUT statement executes
- Question(tchan49-stat6250):What is the number of observations determined by? 
- Question (who7−stat6250): Can we set output equal to new dataset name like when we create new dataset from before?
- *Question* (jcanfield3-stat6250): What value is year at the end of the loop?
- *Answer* (jcanfield3-stat6250): Year is 21, since it has to resolve at the top of the loop.
- Question (ldeng11−stat6250): How do you know the number of steps in the DO loop?
- Question (ljiang11−stat6250): Where is value+interest stored?
- *Question* (akrishnamurthy-stat6250): How to generate observation for each iteration of a DO loop? Is Output a default option for DO loop?
- *Answer* (sbagdi-stat6250): An explicit output statement must be put inside a DO loop to generate observation for each iteration. By default, an implicit OUTPUT statement is the option for DO loop.
- *Question* (sbagdi-stat6250): What is the Do loop syntax in a SAS programming?
- *Answer* (asharda-stat6250): DO; ...more SAS statements...END;
- Question(pcheng14-stat6250):What is the number of observations based on?
- Question (aguenane−stat6250): What precaution one must take while listing items in a series?



[Course Textbook Chapter 14, Problem 7]
- Question(dfei-stat6250): What does nested DO loops mean?
- *Answer* (sbagdi-stat6250): Putting a DO loop within a DO loop is called nesting.
- *Answer* (asharda-stat6250):A nested DO loop is a loop within a loop, an inner loop within the body of an outer one. 
- *Question* (aacharya4−stat6250):  What is the case in case we use decrementing DO loops?
- *Answer* (aacharya4−stat6250): In case of decrementing DO loops, the BY clause has a negative value. Thus, the start value of the index variable should be greater than the stop value of the index variable.
- *Question* (asharda-stat6250): Which statements do you use to loop  when number of iterations is fixed?.
- *Answer* (asharda-stat6250):  DO WHILE and DO UNTIL statement.
- *Question* (shatcher4-stat6250): What is the purpose of the DO WHILE and DO UNTIL statements?
- *Question* (ldai4-stat6250): What is the difference between DO WHILE statement and DO UNTIL statement?
- Question (tbishaw-stat6250): What does decrementing a DO loop accomplish? 
- *Question*(kamirneni-stat6250): When is DO UNTIL loop used?
- *Question* (cli19−stat6250): When would a non-iterative DO group be useful?
- Question (nshrivastava2-stat6250): To create an observation for each iteration of the DO loop, what statement be use?
- Answer(nshrivastava2-stat6250): To create an observation for each iteration of the DO loop, place an OUTPUT statement inside the loop. By default, every DATA step contains an implicit OUTPUT statement at the end of the step. But placing an explicit OUTPUT statement in a DATA step overrides automatic output, causing SAS to add an observation to the data set only when the explicit OUTPUT statement is executed. 
- Question (ttruong59-stat6250): Is it possible to run DO loops within another DO loops?
- Answer (ttruong59-stat6250): Yes. DO loops can run within DO loops as long as users assign a unique variable to each loop and terminate each DO loop with its own END statement.
- Question(tchan49-stat6250):Can you have DO loops within another DO loops? 
- Question (who7−stat6250): What are the main difference between DO WHILE and a DO UNTIL loop?
- Answer (who7-stat6250): DO WHILE loop can skil over some observation while DO UNTIL will go through each observation.
- *Question* (jcanfield3-stat6250): How many different "do" statements are there in SAS?
- Question (ldeng11−stat6250): Can you nested DO loop? Or use other statement in the DO loop?
- Question (ljiang11−stat6250): How many DO loops do we need?
- Answer (ljiang11−stat6250): 2. One for month, the other for year.
- *Question* (akrishnamurthy-stat6250): What is the difference between DO While and DO Until statements?
- *Answer* (akrishnamurthy-stat6250): The DO Until condition is evaluated at the bottom of the loop and hence the statements are always executed atleast once.When the expresssion is true, the DO loop stops. The DO WHILE loop is evaluated at the top of the loop and hence if the expression is false for the first time itself, the loop never executes.
- *Question* (sbagdi-stat6250): What is output statement used for?
- *Answer* (sbagdi-stat6250): The output statement overrides the automatic output at the end of DATA step in a SAS programming.
- Question(pcheng14-stat6250):When should we use the DO WHILE and DO UNTIL statements?
- Question (aguenane−stat6250): How do determine to choose which DO loops for a specific dataset?



[Course Textbook Chapter 14, Problem 8]
- Question(dfei-stat6250): How to evaluate DO UNTIL statements?
- Answer(asharda-stat6250):The bottom of the loop so that a DO UNTIL loop executes at least once. 
- *Question* (aacharya4−stat6250):  How can we generate observations with the DO loops for each iteration of the loop?
- *Answer* (aacharya4−stat6250): To generate observations for each iteration of the DO loop, we can use the OUTPUT statement.
- *Question* (asharda-stat6250): When is DO UNTIL condition evaluated?.
- *Answer* (asharda-stat6250):  The DO UNTIL condition is evaluated at the bottom of the loop, so the enclosed statements are always excecuted at least once.
- *Question* (shatcher4-stat6250): During what part of the loop is the DO UNTIL statemnet evaluated, and what happens if the expression is evaluated as false?
- *Question* (ldai4-stat6250): In executing DO until statement, are the enclosed statement always executed at least once?
- Question (tbishaw-stat6250): What conditions must be met for a DO loop to run within a DO loop?
- Answer (tbishaw-stat6250): DO loops can run within DO loops, as long as you assign a unique index variable to each loop and terminate each DO loop with its own END statement.
- *Question*(kamirneni-stat6250): Can string condition be evaluated in DO loop?
- *Question* (cli19−stat6250): What is the minimum number of times enclosed statements within a DO UNTIL condition executed?
- *Answer* (cli19−stat6250): Since the condition is evaluated at the bottom of the loop, the enclosed statement within a DO UNTIL condition is executed at least one time.
- Question (nshrivastava2-stat6250): What is Nesting DO Loops ? Will the nested DO Loops, be a performance issues?
- Question (ttruong59-stat6250): How does the DO UNTIL statement execute a DO loop?
- Answer (ttruong59-stat6250): The DO UNTIL statement executes the DO loop until the specified condition is true. 
- Question(tchan49-stat6250):Where would the DO UNTIL start being evaluated?
- Answer(tchan49-stat6250):The bottom of the loop so that a DO UNTIL loop executes at least once. 
- Question (who7−stat6250): In what scenerio would the DO UNTIL loop does not execute the enclosed statement at all.
- *Question* (jcanfield3-stat6250): What happens if the until value is reached before the loop begins?
- *Answer* (jcanfield3-stat6250): The loop iterates only once then, since the loop is always executed at least once.
- Question (ldeng11−stat6250): What is DO UNTIL statement using for?
- *Answer* (sbagdi-stat6250): Do until statement executes a DO statement until an expression becomes true.
- Question (ljiang11−stat6250): When is the condition stop being evaluated?
- *Question* (akrishnamurthy-stat6250): How to execute a DO loop when the iterations are not fixed and depends on a condition?
- *Question* (sbagdi-stat6250): What are DO WHILE and DO UNTIl statements?
- Question(pcheng14-stat6250):What is the meaning of the DO UNTIL condition?
- Question (aguenane−stat6250): What clauses are used to create samples?



[Course Textbook Chapter 14, Problem 9]
- Question(dfei-stat6250): What is the difference between do until and DO WHILE statement?
- *Answer* (sbagdi-stat6250): The DO WHILE expression is evaluated at the top of the LOOP. SO, if the expression is false the first time, DO loop will never execute.
- *Answer* (asharda-stat6250)The only difference between do while and do until is that the first one loops is execute as long as the condition is true, while the second one loops execute as long as the condition is false. 
- *Question* (aacharya4−stat6250):  What are the possible types of start, stop and increment/decrement values for index variable in iterative DO statements?
- *Answer* (aacharya4−stat6250): The start, stop and increment/decrement values for index variable can be any number, numeric variable or SAS expression which evaluates to give a numeric value.
- *Question* (asharda-stat6250): When is DO WHILE loop evaluated?.
- *Answer* (asharda-stat6250): DO WHILE loop is evaluated at the top of the loop.
- *Question* (shatcher4-stat6250): During what part of the loop is the DO WHILE statemnet evaluated, and what happens if the expression is evaluated as true?
- *Question* (ldai4-stat6250): Why do we need to specify the condition in DO WHILE statement?
- Question (tbishaw-stat6250): What does the SET statement in a DO loop execute? 
- *Question*(kamirneni-stat6250): How does one use values at intervals of 10?
- *Answer*(kamirneni-stat6250): It can be done using POINT statement.
- *Question* (cli19−stat6250): What are the tradeoffs to using DO UNTIL versus DO WHILE?
- Question (nshrivastava2-stat6250): What is the overview of conditionally executing DO Loops? Name them? 
- Question (ttruong59-stat6250): What is a major difference between DO UNTIL and DO WHILE statement?
- Answer (ttruong59-stat6250): DO WHILE is evaluated at the top of the DO loops and if the expression is initially false, DO loop never executes. On the other hand, DO UNTIL is not evaluated until the end of the loop so DO UNTIL executes at least once. 
- Question(tchan49-stat6250):Where would the DO WHILE start being evaluated?
- Question (who7−stat6250): Would the variable need to be sorted before we can use DO UNTIL loop?
- *Question* (jcanfield3-stat6250): Because it should in "do until(Capital gt 500000)", why does the do while(Capital le 500000) iterate when capital=500000?
- Question (ldeng11−stat6250): Whst is DO WHILE statement using for?
- Question (ljiang11−stat6250): What is the difference between DO WHILE and DO UNTIL?
- *Question* (akrishnamurthy-stat6250): How should the index variable be defined for a DO WHILE loop?
- *Question* (sbagdi-stat6250): WHat is nesting DO loops?
- Question(pcheng14-stat6250):Why should we specify the condition that must exist in order to execute the enclosed statements?
- Question (aguenane−stat6250): Is there a limit to number of nested DO loops?



[Course Textbook Chapter 14, Problem 10]
- Question(dfei-stat6250): What time does program stop generating observations?
- *Question* (aacharya4−stat6250):  How can we do nested DO loops in SAS?
- *Answer* (aacharya4−stat6250): Nested DO loops can be used in SAS where each DO loop has an unique index variable for each DO loop and each of the DO loops has its own terminating END statement.
- *Question* (asharda-stat6250): What is difference between DO UNTIL and DO WHILE statements?
- *Question* (shatcher4-stat6250): What occurs when you enclose a SET statement in a DO loop and what occurs when you add a POINT= option to that SET statement?
- *Question* (ldai4-stat6250): If we want to the DO LOOP to stop executing some condition, should we use the WHILE statement?
- Question (tbishaw-stat6250): How many values is the index variable always incremented by?
- *Answer* (sbagdi-stat6250): The INDEX value is always incremented by 1 value.
- *Question*(kamirneni-stat6250): What is the function of OUTPUT statement?
- *Answer* (asharda-stat6250) :An OUTPUT statement overrides the default process by telling SAS to output the current observation when the OUTPUT statement is processed — not at the end of the DATA step.
- *Question* (cli19−stat6250): When is it best to specify the start and stop values if a WHILE or UNTIL condition is specified in the DO loop?
- Question (nshrivastava2-stat6250): When we use the Do WHILE statement?
- Answer(nshrivastava2-stat6250):  You can use the DO WHILE statement to execute a DO loop while the expression is true. 
- Question (ttruong59-stat6250): Can DO WHILE statements be used within iterative DO loops to combine conditional and unconditional execution?
- Answer (ttruong59-stat6250): Yes. DO WHILE statements can be used within iterative DO loops to combine conditional and unconditional execution
- Question(tchan49-stat6250):If you want to know how many years it takes to earn $10,000 if you deposit $10,000 each year with 10% interest, would you use DO WHILE or DO UNTIL?
- Question (who7−stat6250): Are there other DO statement besides UNTIL and WHILE?
- *Question* (jcanfield3-stat6250): Can you have multiple while conditions in a single do loop?
- Question (ldeng11−stat6250): What are the differences between DO UNTIL and DO WHILE statements?
- Question (ljiang11−stat6250): Can DO loop contain conditional clause?
- *Question* (akrishnamurthy-stat6250): How to use conditional clauses with the iterative DO statement?
- *Question* (sbagdi-stat6250): When do we use the decrementing DO loops?
- Question(pcheng14-stat6250):Which expression would cause the DO loop to stop executing?
- Question (aguenane−stat6250): What is the exact process when the loop reaches the limit value?



[Course Textbook Chapter 15, Problem 1]
- Question(dfei-stat6250): Can an ARRAY statement be used to create variables?
- *Question* (aacharya4−stat6250):  Is it possible to store both numeric and character variables in a single array in SAS?
- *Answer* (aacharya4−stat6250): No, a single array in SAS can store either numeric or character variables and not both.
- *Question* (asharda-stat6250): What does an ARRAY statement do?.
- *Answer* (asharda-stat6250) :The ARRAY statement can be used to create variables, must contain either all numeric or all character elements, and must be used to define an array before the array name can be referenced.
- *Answer* (asharda-stat6250):  It merely defines an array.
- *Question* (shatcher4-stat6250): What is a SAS array?
- *Answer* (sbagdi-stat6250): A SAS array is temporarliy grouping of SAS variables under single name.
- *Question* (ldai4-stat6250): What is ARRAY statement?
- *Answer* (ldai4-stat6250): The ARRAY statement can be used to create variables, must contain either all numeric or all character elements, and must be used to define an array before the array name can be referenced.
- Question (tbishaw-stat6250): How can you process variables as a group?
- Answer (tbishaw-stat6250): You can process varaibles as a group by using array processing.
- *Question*(kamirneni-stat6250): What kind of statement is an ARRAY statement?
- *Answer*(kamirneni-stat6250): It is not, it only defines an array.
- *Question* (cli19−stat6250): What is the purpose in first defining an array?
- Question (nshrivastava2-stat6250): What is the difference between one-Dimensional and multi-Dimentional Arrays?
- Question (ttruong59-stat6250): What is an ARRAY statement?
- Answer (ttruong59-stat6250): An ARRAY is a temp grouping of SAS variables under a single name and is not an executable statement.
- Question(tchan49-stat6250):Can you execute an ARRAY statement? 
- Question (who7−stat6250): Can ARRAY be considered a list of matrix in R term?
- *Question* (jcanfield3-stat6250): Why cannot i not mix numeric and character elements?
- Question (ldeng11−stat6250): What is SAS array?
- Question (ljiang11−stat6250): Is ARRAY statement executable?
- *Question* (akrishnamurthy-stat6250): What is the use of ARRAY statement?
- *Answer* (akrishnamurthy-stat6250): Arrays are used to simplify the code needed to perform repetitive calculations,create many variables with same attributes,read data,rotate SAS datasets by changing variables to observations or observation to variables,compare variables,table lookups.
- *Question* (sbagdi-stat6250): Is there a difference between one-dimensional and multi-dimensional arrays? If so, what is it?
- Question(pcheng14-stat6250):Why an ARRAY statement is not an executable statement?
- Question (aguenane−stat6250): Is array similar to list/tuple in python?



[Course Textbook Chapter 15, Problem 2]
- Question(dfei-stat6250): What does the braces of this ARRAY statement mean?
- *Question* (aacharya4−stat6250):  In the following syntax: (ARRAY array-name{dimension} {elements};), what does dimension mean?
- *Answer* (aacharya4−stat6250): The dimension in the given syntax indicates the length of the array or the number of elements in the array.
- *Question* (asharda-stat6250): What does the value in parentheses indicate?.
- *Answer* (asharda-stat6250):  The value in parentheses indicates the number of elements in the array.
- *Question* (shatcher4-stat6250): What is the purpose of the specification of the dimension of the array?
- *Question* (ldai4-stat6250): Does the value in parentheses indicate the number of elements in the array?
- Question (tbishaw-stat6250): What is an array? What are its functions?
- *Question*(kamirneni-stat6250): Where can ARRAY be used?
- *Answer*(kamirneni-stat6250): Only in DATA step, not in any other labels.
- *Question* (cli19−stat6250): Is there a way for an array to automatically detect the number of elements?
- Question (nshrivastava2-stat6250): How to use arrays to recode set of variables?
- Question (ttruong59-stat6250): How to specify a dimension in an ARRAY statement?
- Answer (ttruong59-stat6250): There are a few ways to do this. One way is to simply specify the number of array elements in term of a one-dimensional array. Typically array elements are the variables users want to reference and process elsewhere in the DATA step.
- Question(tchan49-stat6250):How do you define the value in the parenthese of an ARRAY statement? 
- Question (who7−stat6250): Waht would happen if the number within the bracket is different from the number f variables listed in the ARRAY statement?
- *Question* (jcanfield3-stat6250): What error if any is produced if an incorrect number is placed in parantheses?
- Question (ldeng11−stat6250): What is the array statement?
- *Answer* (asharda-stat6250) :The ARRAY statement defines a set of elements that you plan to process as a group.
- Question (ljiang11−stat6250): Can a variable be inside the parenthesis?
- *Question* (akrishnamurthy-stat6250): Is it mandatory to specify the array length while defining the array ?
- *Question* (sbagdi-stat6250): WHy should we specify the array dimensions?
- *Answer* (sbagdi-stat6250): Dimensions should be specified as they describes the number and arrangements in an array. 
- uestion(pcheng14-stat6250):What kinds of the value indicates the number of elements in the array?
- Question (aguenane−stat6250): What is the maximum number of variables that can be used in an array?



[Course Textbook Chapter 15, Problem 3]
- Question(dfei-stat6250): How to select an iterative DO statement to process all elements?
- *Question* (aacharya4−stat6250):  What happens if we do not specify array elements in an ARRAY statement?
- *Answer* (aacharya4−stat6250):  If we do not specify array elements in an ARRAY statement, SAS automatically creates variable names by concatenating numbers 1,2,3,..upto the array dimension with the array name.
- *Question* (asharda-stat6250): Which variable represents the values of the array elements in the DO statement.
- *Answer* (asharda-stat6250):  Index variable represents the values of the array elements in the DO statement.
- *Question* (shatcher4-stat6250): When are arrays used with a DO loop?
- *Answer* (shatcher4-stat6250): Arrays are generally used with DO loops to process multiple variables and to perform repetitive calculations.
- *Question* (ldai4-stat6250): How can we specify the index variable that represents the values of the array elements in the DO statement?
- *Answer* (ldai4-stat6250): We need to specify the start and stop position of the array elements. 
- Question (tbishaw-stat6250): What are the functions of a a DIM function? 
- Answer (tbishaw-stat6250): You can use the DIM function to specify the TO clause of the iterative DO statement.
- *Question*(kamirneni-stat6250): How does one define a string array?
- *Question* (cli19−stat6250): What does the number in curly brackets of an array represent?
- *Answer* (cli19−stat6250): It represents the position of the array elements.
- Question (nshrivastava2-stat6250): How to use arrays to recode all the numeric variables?
- Question (ttruong59-stat6250): Can we add a DO statement to process all elements in the array?
- Answer (ttruong59-stat6250): Yes. In the DO statement, we need to specify the index variable to represents the values of the array elements, then specify the start and stop positions of the array elements.
- Question(tchan49-stat6250):Do you need to specify the start and stop positions of the array elements in DO statement?
- Question (who7−stat6250): Can we use DO WHILE or DO UNTIL for the array?
- *Question* (jcanfield3-stat6250): What error if any is produced if i try to access a nonexistent array element?
- Question (ldeng11−stat6250): How do you specify the dimension in the array?
- *Answer* (sbagdi-stat6250): DImension in an array can be specified by using an '*' sign. 
- *Answer* (asharda-stat6250) :{subscript} describes the number and arrangement of elements in the array by using an asterisk, a number, or a range of numbers. Subscript has one of these forms:
- Question (ljiang11−stat6250): Can a DO loop conjugate with an ARRAY statement?
- *Question* (akrishnamurthy-stat6250): While referencing an array element using DO loop index variable, should the stop value of index variable be equal to array length?"
- *Question* (sbagdi-stat6250): What happen if we specify array elements outside of array statements?
- Question(pcheng14-stat6250):Do we need to specify the start and stop positions of the array elements in DO ststement?
- Question (aguenane−stat6250): What character is used to specify the dimension of 1-D array?



[Course Textbook Chapter 15, Problem 4]
- Question(dfei-stat6250): How to know the value of the index variable?
- *Question* (aacharya4−stat6250):  When we use DO iterative statement with array in SAS, what does the index variable of the DO iterative statement indicate in regard to the array that it references?
- *Answer* (aacharya4−stat6250): The index variable of the DO iterative statement indicates the position of the array element of the array that it references.
- *Question* (asharda-stat6250): What does an index value represents .
- *Answer* (asharda-stat6250):  The index value represents the position of the array element.
- *Question* (shatcher4-stat6250): How do you specify the elements of an array?
- *Question* (ldai4-stat6250): What does the index value represent?
- Question (tbishaw-stat6250): What length are all character variables that are created with an ARRAY statement assigned by default?  
- *Question*(kamirneni-stat6250): How can one define a range of values for the index in an array?
- *Answer* (asharda-stat6250) :By specifying a constant value within the brackets, you can specify the number of variables or elements that are to be associated with the array.
- *Question* (cli19−stat6250): At what value does SAS begin its index count?
- *Answer* (cli19−stat6250): SAS starts its count at 1.
- Question (nshrivastava2-stat6250): Describe 5 Ways To Do A "table Lookup" In Sas?
- Answer(nshrivastava2-stat6250): Match Merging,Direct Access,Format Tables,Arrays,PROC SQL.
- Question (ttruong59-stat6250): How to specify the range of variables in the array?
- Question(tchan49-stat6250):Is the index vaule for the first array element 0 or 1? 
- Question (who7−stat6250): Is there a way to write a shorter code if we want to include all months besides listing all of them in the array?
- *Question* (jcanfield3-stat6250): Can a variable be used instead of a number in the parantheses when defining an array?
- *Answer* (jcanfield3-stat6250): Yes it can, as long as its value is numeric.
- Question (ldeng11−stat6250): How do you reference the elements of the array?
- Question (ljiang11−stat6250): How is an array element's position expressed in the ARRAY statement?
- *Question* (akrishnamurthy-stat6250): Can the dimension of array and array elements be defined as range of values?
- *Answer* (akrishnamurthy-stat6250): Yes, the array dimension can be specified as a range like array{4-7}. The array elements can also be defined as variable list. The variable list can be a numbered range of variables, all numeric, all character, all character or numeric types.
- *Question* (sbagdi-stat6250): What is DIM function used for in SAS?
- *Answer* (sbagdi-stat6250): When using DO loops to process arrays, one can use the DIM function to specify the TO clause of the iterative DO statement.
- Question(pcheng14-stat6250):Wht the index value represents the position of the array element?
- Question (aguenane−stat6250): What are the rules for defining a numbered range of variables?



[Course Textbook Chapter 15, Problem 5]
- Question(dfei-stat6250): What does the "*" mean in "do i=1 to dim(*)" statement?
- *Question* (aacharya4−stat6250): What is the purpose of using the DIM function in SAS? 
- *Answer* (aacharya4−stat6250): We use the DIM function to process all the elements in an array in SAS.
- *Question* (asharda-stat6250): How do you process all the elements in an array?
- *Answer* (asharda-stat6250):  To process all the elements in an array, you can either specify the array dimension or use the DIM function with the array name as the argument.
- *Question* (shatcher4-stat6250): What is the purpose of the i in the DO loop of an array?
- *Question* (ldai4-stat6250): How can we use the DIM function?
- *Answer* (asharda-stat6250) :Use DIM in array processing to avoid changing the upper bound of an iterative DO group
- Question (tbishaw-stat6250): How can we assign initial values to character varaibles?  
- *Question*(kamirneni-stat6250): What is the index value in an array?
- *Question* (cli19−stat6250): What does the DIM function do? Can this function be used outside of an array?
- Question (nshrivastava2-stat6250): What is the better way of substituting one value for another in a group of variables
- Answer(nshrivastava2-stat6250): There are many ways but one better way by using an array to represent a list of variables, or elements where SAS system allows to perform an operation, or a set of operations, on the entire list by referring to the array.
- Question (ttruong59-stat6250): Is it true that the variables must be numbered consecutively?
- Question(tchan49-stat6250):When you use DIM function, do you put the name of the array in the parenthese? 
- Question (who7−stat6250): Can we create a two-dimensional array?
- *Question* (jcanfield3-stat6250): Can you add elements to a pre-defined array with already maxed elements?
- Question (ldeng11−stat6250): How DIM function work?
- Answer (ldeng11−stat6250): The DIM fuction return the number of elements in the array.
- Question (ljiang11−stat6250): What is the function dim{}?
- *Question* (akrishnamurthy-stat6250): How to process all the array elements without explicitly specifying the array length?
- *Question* (sbagdi-stat6250): WHat type of variables can be created in an array statement?
- Question(pcheng14-stat6250):When should we use the DIM function with the array name as the argument?
- Question (aguenane−stat6250): What variable is used in DO loop to reference element of an array?
- *Answer* (sbagdi-stat6250): The INDEX varaible is used to reference element of an array. 



[Course Textbook Chapter 15, Problem 6]
- Question(dfei-stat6250): By default, are all character variables assigned a length of eight?
- *Question* (aacharya4−stat6250): How can we assign initial values in an ARRAY statement?
- *Answer* (aacharya4−stat6250): We can assign initial values in an ARRAY statement by placing the values within parenthesis, where each value is separated by a comma or blank. In case, of values for character variable in array, the values should be enclosed in quotation marks. 
- *Question* (asharda-stat6250): How do you process all the elements in an array?
- *Answer* (asharda-stat6250):  To process all the elements in an array, you can either specify the array dimension or use the DIM function with the array name as the argument.
- *Question* (shatcher4-stat6250):  If exisiting variables within an array are not referenced, why does SAS automatically create new variables and assigns them default names?
- *Question* (ldai4-stat6250): Do we need to specify the array elements in the ARRAY statement?
- Question (tbishaw-stat6250): How can we define a multidimensional arrays? 
- *Answer* (asharda-stat6250) :To create a multidimensional array, place the number of elements in each dimension after the array name in the form {n, … } where n is required for each dimension of a multidimensional array.
- *Question*(kamirneni-stat6250): What is the specific use of DIM function?
- *Question* (cli19−stat6250): Do varaibles need to be identified as either numeric or character before they are created in an array?
- Question (nshrivastava2-stat6250): How we specify an array element in SAS?
- Question (ttruong59-stat6250): Are variables added to the program data vector during the compilation of the DATA step?
- Question(tchan49-stat6250):Can you create numeric variable using arrrays?
- Answer(tchan49-stat6250): Yes and characters as well. 
- Question (who7−stat6250): Why was the length of character variable set at 8?
- *Question* (jcanfield3-stat6250): What is the default numeric variable length?
- Question (ldeng11−stat6250): How do you use array to create variables?
- Question (ljiang11−stat6250): Can numeric variable be created in ARRAY statement?
- Answer (ljiang11−stat6250): Yes, both numeric and character variables can be created in ARRAY statement.
- *Question* (akrishnamurthy-stat6250): What are the rules for creating a numbered range of array variables?
- *Question* (sbagdi-stat6250): How to create temporary array elements?
- *Answer* (sbagdi-stat6250): By specifying _TEMPORARY_ after array name and dimension.
- Question(pcheng14-stat6250):Can either numeric or character variables be created by an ARRAY statement?
- Question (aguenane−stat6250): What is the DIM function used as an alternative for?



[Course Textbook Chapter 15, Problem 7]
- Question(dfei-stat6250): Why does array "wt{*} weight1-weight10" mean?
- *Question* (aacharya4−stat6250): How can we define multidimensional arrays in SAS?
- *Answer* (aacharya4−stat6250): In SAS, we can define a multidimensional array by specifying the number of elements in each dimension separated by comma. For example: array twoDim{2,4} a1-a8; means it is a 2D array with 2 rows and 4 columns.
- *Question* (asharda-stat6250): Which  variables can be created by an ARRAY statement.
- *Answer* (asharda-stat6250):  Either numeric or character variables can be created by an ARRAY statement. 
- *Question* (shatcher4-stat6250): How do you create an array of character variables?
- *Answer* (asharda-stat6250) :Using $ - Indicates the elements within the array are character type variables
- *Question* (ldai4-stat6250): Can we give an array the same name as a variqable in the same DATA step?
- Question (tbishaw-stat6250): What does rotating a data set accomplish?
- Answer (tbishaw-stat6250): Rotating a data set changes variables to observations or observations to variables. 
- *Question*(kamirneni-stat6250): How to create a temporary element in an array?
- *Question* (cli19−stat6250): Is the output from an array written out to the final data set immediately?
- Question (nshrivastava2-stat6250): How DIM functions works using array?
- Answer(nshrivastava2-stat6250): One of the most common tasks involving arrays is to iterate (or, to loop) through each element of an array by using a DO group and then performing an operation on each element.The DIM function presents a more dynamic way to determine the STOP argument.
- Question (ttruong59-stat6250): Based on the solution in the textbook, the correct answer is 15 which is the value of diff{i} at the end second iteration of the DO loop as diff{2}=215-200. What happens if the second iteration of the DO loop is a missing blank? 
- Question(tchan49-stat6250):How do you count the value for the i in diff{i}? 
- Question (who7−stat6250): How do we rotate the dataset if we have a 3D dataset like an olap cube?
- *Question* (jcanfield3-stat6250): Are the 2nd and 3rd rows of weight1,2,3 even in the array?
- Question (ldeng11−stat6250): How many ways you can use to create the array?
- Question (ljiang11−stat6250): How to create an array?
- *Question* (akrishnamurthy-stat6250): What is the use of temporary arrays and how to define a temporary array?
- *Question* (sbagdi-stat6250): WHat are the ways to 'table lookup' in SAS?
- *Answer* (sbagdi-stat6250): There are 5 ways to do so- match merging, direct access, array, format tables, and PROC SQL. 
- Question(pcheng14-stat6250):When should we use define multidimensional arrays in SAS?
- *Answer* (sbagdi-stat6250): When we want to combine variables into table like structure, we use multi-dimensional arrays.
- Question (aguenane−stat6250): While creating variables in ARRAY statement,does one need to specify elements?



[Course Textbook Chapter 15, Problem 8]
- Question(dfei-stat6250): What is the format to create temporary array elements?
- *Question* (aacharya4−stat6250): How can we reference a multidimensional array in SAS?
- *Answer* (aacharya4−stat6250): We can reference a multidimensional array in SAS by suing nested DO loops.
- *Question* (asharda-stat6250): How do you reference the elements of an array.
- *Question* (shatcher4-stat6250): What is the purpose of temporary array elements?
- *Answer* (shatcher4-stat6250): Temporary array elements are useful when the array is needed for calculations, since these temporary arrays can improve performance time.
- *Question* (ldai4-stat6250): How temporary array element can be created?
- *Answer* (ldai4-stat6250): To create temporary array element, specify _TEMPORARY_ after the array name and dimension, specify an inital value for each element, separated by either blanks or commas, and enclose the values in parentheses.
- Question (tbishaw-stat6250): Can we give an array the same name as a variable in the same DATA step? 
- *Question*(kamirneni-stat6250): How does one reference a specific element in an array?
- *Question* (cli19−stat6250): How are values in a temporary array delimited?
- *Answer* (cli19−stat6250): Values are delimited by commas or spaces.
- Question (nshrivastava2-stat6250): What are the commonly used functions in Array?
- Answer(nshrivastava2-stat6250): SAS has many functions and operators that you can use with arrays to perform common tasks. 
- Question (ttruong59-stat6250): Is it possible to assign initial values to an array without specifying each array elements?
- Question(tchan49-stat6250):Is parenthese necessary to enclose all the temporary vaule using _temporary_ function?
- Question (who7−stat6250): Can we achieve the same effect to creating temporary values by creating an new varaible in the dataset?
- *Question* (jcanfield3-stat6250): Why do special words in SAS need the underscores on both sides like in "_temporary_"?
- Question (ldeng11−stat6250): What is temporary array?
- Question (ljiang11−stat6250): What is the format to create temporary array elements?
- *Question* (akrishnamurthy-stat6250): How to reference the elements of multi dimensional array?
- *Question* (sbagdi-stat6250): What are temporary array statements used for?
- *Answer* (sbagdi-stat6250): When arrays are only meant for calculations, and when the performance time is to be improved, the temporary array elements are used. 
- *Answer* (asharda-stat6250) :To define bounds array
- Question(pcheng14-stat6250):When should we create temporary array elements?
- Question (aguenane−stat6250): What is the use of rotating a dataset in SAS?



[Course Textbook Chapter 15, Problem 9]
- Question(dfei-stat6250): What does array reference mean?
- *Question* (aacharya4−stat6250):  Can we use arrays to rotate datasets (changing variable to observation and vice versa) in SAS?
- *Answer* (aacharya4−stat6250): We can use arrays to rotate datasets (changing variable to observation and vice versa) in SAS.
- *Question* (asharda-stat6250): How do you create  create temporary array elements?
- *Answer* (asharda-stat6250) :The elements are defined by the key word _TEMPORARY_. 
- *Question* (shatcher4-stat6250): How do assign inital values in an ARRAY statement?What is the purpose of temporary array elements 
- *Question* (ldai4-stat6250): How do we specify the array reference in the nested DO loops?
- Question (tbishaw-stat6250): How can we indicate the dimension of a one-dimensional array?
- Answer (tbishaw-stat6250): You can indicate the dimension of a one-dimensional array with an asterik as long as you specify the elements of the array.
- *Question*(kamirneni-stat6250): How does one remove a temporary element?
- *Question* (cli19−stat6250): When utilizing arrays to transpose data, when does it have an upperhand over PROC TRANSPOSE?
- Question (nshrivastava2-stat6250): Defining a numbered range of variables using array?
- Answer(nshrivastava2-stat6250): The variables must have the same name except for the last character or characters. The last character of each variable must be numeric. The variables must be numbered consecutively.
- Question (ttruong59-stat6250): What is a major reason to create temp array elements?
- Question(tchan49-stat6250):How do you create a multidimensional array with two rows and 5 columns? 
- Question (who7−stat6250): What would happen if we select something out of the array?
- *Question* (jcanfield3-stat6250): Since I cannot find it in the chapter, does {3, 25} specify a 2-D array with 3 rows and 25 columns?
- Question (ldeng11−stat6250): How do you refrence the elements in the array?
- Question (ljiang11−stat6250): How many rows and columns does ARRAY ques{3, 25} q1-q75 have?
- *Question* (akrishnamurthy-stat6250): Instead of initializing entire array, is it possible to initialize specific array elements?
- *Question* (sbagdi-stat6250): Can arrays be used to rotate datasets in a SAS?
- *Answer* (sbagdi-stat6250): Yes, arrays can be used to rotate datasets in SAS. The observations become variables and vice-versa. 
- Question(pcheng14-stat6250):When should we use arrays to rotate datasets in SAS?
- Question (aguenane−stat6250): What is the syntax required for creating temporary elements in an array?



[recipe_to_create_unique_record_id Week 9 Recipe]
- Question(dfei-stat6250): "_N_ is converted to a character value, meaning it's left-padded with zeros." Why not with ones?
- *Question* (aacharya4−stat6250): Why is the "z6." format used for conversion of automatic variable to character variable in the SAS recipe?
- *Answer* (aacharya4−stat6250): The "z6." format is used to make the converted character value to be exactly of 6 digits, which is one magnitude larger than the number of records of the dataset being used.
- *Question* (asharda-stat6250): What happens during compilation phase of data step?.
- *Answer* (asharda-stat6250) :In particular, _N_ is created automatically during the compilation phase of the data step and is added automatically to the PDV, but it is given a drop attribute, preventing it from being included in the output dataset. However, it can be treated like any other numeric variable in a data step, including being included in computations.
- *Question* (shatcher4-stat6250): What is the purpose of the double-pipe operator?
- *Question* (ldai4-stat6250): How can I assign serial numbers to observations in a data set?
- Question (tbishaw-stat6250): How can we adda new ID column in SAS? 
- *Question*(kamirneni-stat6250): Can one array be assigned as a primary key in a multidimensional array?
- *Question* (cli19−stat6250): How are values concatenated?
- *Answer* (cli19−stat6250): Values can be contatenated using two pipe symbols (||). 
- Question (nshrivastava2-stat6250): How to pad character variable with leading zeroes?
- Answer(nshrivastava2-stat6250): We can do so by uising Z4. format to add leading zeroes.
- Question (ttruong59-stat6250): Assuming school_record_ID is defined as char e.g. school_record-AB0001, how do we set a unique school ID with the string “school_record-AB” if _N_=42?
- Question(tchan49-stat6250):Why do we need to create unique ID? 
- Question (who7−stat6250): What are other format beside z6?
- *Question* (jcanfield3-stat6250): What would happen if i used input instead of put?
- Question (ldeng11−stat6250): Where is the automatic variable _N_ from?
- Question (ljiang11−stat6250): How does _N_ work?
- *Question* (akrishnamurthy-stat6250): What does the format z6 signify?
- *Question* (sbagdi-stat6250): WHat is the double pipe operartor's purpose in SAS?
- *Answer* (sbagdi-stat6250): The double pipe operator (||) is used to concatenate strings, i.e. to form a single string, combining the two.
- Question(pcheng14-stat6250):What kind of the format used for conversion of automatic variable to character variable in the SAS recipe is best?
- Question (aguenane−stat6250): Are there any other formats apart from Z6 SAS to convert automatic variable to character variable?



[recipe_to_disaggregate_counts_data Week 9 Recipe]
- Question(dfei-stat6250): How many ways to add an unique ID to each row in dataset?
- *Question* (aacharya4−stat6250):  What is the purpose of using RETAIN statement in SAS?
- *Answer* (aacharya4−stat6250): In a DATA step, SAS sets the initial values of variables created by INPUT or assignment system as missing by default. The RETAIN statement overrides this default, so the value of the variable is retained when used with RETAIN statement.
- *Question* (asharda-stat6250): What is the use of where not statement?.
- *Question* (shatcher4-stat6250): Why would you use a retain attribute in a DO loop?
- *Question* (ldai4-stat6250): In using PROC mean statement, how can we calculate disaggregate statistics?
- Question (tbishaw-stat6250): Which SAS function do we use to execute disaggreagation? And what does Disaggreagation accomplish?  
- *Question*(kamirneni-stat6250): What does disaggregation accomplish and what function is used to define it?
- *Question* (cli19−stat6250): Can a single RETAIN statements be used to specify order of variables and to preserve variable values between DATA step iterations?
- Question (nshrivastava2-stat6250): Why is the initianlzation process relevant when no retain statement is involved?
- Question (ttruong59-stat6250): Why do we use RETAIN statements in the DO loop for this recipe? Is it mainly because we like to override the default values? 
- Question(tchan49-stat6250):What statement you might want to use when you don't want to count missing values? 
- *Answer* (asharda-stat6250) :In the example provided will use :where not(missing(Enrollment_K12));
- Question (who7−stat6250): How is the second example different from the first example besides removing all missing value?
- *Question* (jcanfield3-stat6250): So the code just creates repeated lines of each record based on the value of Enrollment_K12 right?
- Question (ldeng11−stat6250): Why we should retain the student_record_counter as 0?
- Question (ljiang11−stat6250): What is the purpose to disaggregate data?
- *Question* (akrishnamurthy-stat6250): What is the use of RETAIN statement?
- *Answer* (sbagdi-stat6250): SAS sets the initial values of variables created by INPUT or assignmnet system as missing by default. RETAIN statement overrides these default values. 
- *Question* (sbagdi-stat6250): How to pad character variable with the leading zeroes?
- *Answer* (sbagdi-stat6250): We can pad character variable with the leading zeroes by making use of Z4. format, which adds the leading zeroes.
- Question(pcheng14-stat6250):What is the meaning of RETAIN statement in SAS and when should we use it?
- Question (aguenane−stat6250): In what analysis is disaggregation statistics used for?


