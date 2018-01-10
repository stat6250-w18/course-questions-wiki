[Course Textbook Chapter 1, Problem 1]
  
 Question(rlopez31-stat6250): What does it mean to have SAS statements as free-format?
  
 Answer(rlopez31-stat6250): Free-format means that they can bein and end anywhere on a line, that one statement can continue over several lines, and several statements can be on the same line.
  
  [Course Textbook Chapter 1, Problem 2]
  
 Question(rlopez31-stat6250): In most situations, text that are enclosed in quotation marks ar case sensitive. Can one only specify SAS statements in uppercase, lowercase, or both?
  
 Answer(rlopez31-stat6250): SAS statements can be specified with both.
  
  [Course Textbook Chapter 1, Problem 3]
  
 Question(rlopez31-stat6250): The RUN statement is not always required between steps, but why is it highly suggested?
  
 Answer(rlopez31-stat6250): The RUN statement makes the SAS program easier to read and debug while also making the SAS log easier to read.
  
  [Course Textbook Chapter 1, Problem 4]
  
 Question(rlopez31-stat6250): What does the SAS programs usually invoke that create ouput in the form of a report?
  
  [Course Textbook Chapter 1, Problem 5]
  
 Question(rlopez31-stat6250): In the DATA step Output Example, What does the DATA step produce and message is produced in the SAS log?
  
 data sasuser.admit2;
 set sasuser.admit;
 where age>39;
 run;
  
  [Course Textbook Chapter 1, Problem 8]
  
 Question(rlopez31-stat6250): How can one refereance a permanent SAS data set in the SAS programs?
  
  [Course Textbook Chapter 2, Problem 3]
  
 Question(rlopez31-stat6250): What statement is used to define libraries in SAS?
  
 Answer(rlopez31-stat6250): You can store the LIBNAME statement, which can be done with any SAS program.
  
  [Course Textbook Chapter 2, Problem 7]
  
 Question(rlopez31-stat6250): Interface library engines support read-only access to what three types of files?
  
  [Course Textbook Chapter 2, Problem 8]
  
 Question(rlopez31-stat6250): Using the Programming Workspace explained that after you have assigned a libref, what can you view?
  
 Answer(rlopez31-stat6250): One can view details about the library that the libref references, the library's contents, and contents and properties of files in the library.
  
  [Course Textbook Chapter 2, Problem 9]
  
 Question(rlopez31-stat6250):Alternatively, how can you use the CONTENTS procedure to create SAS output that describes either of the following?
  
 Answer(rlopez31-stat6250):Can use the contents of a library and the descriptor information for an individual SAS data set.
  
  [basic_recipe_for_loading_data_from_remote_Excel_file Week 2 Recipe]
  
 Question(rlopez31-stat6250): How can one import data from excel files and what various methods can be used?
  
  [bonus_advanced_recipe_for_loading_data_from_remote_Excel_file Week 2 Recipe]
  
 Question(rlopez31-stat6250): Macro variables are used for what following reason?
