# Python: This repository contains the code for below programming tasks:
PROGRAMMING TASKS
You have been provided with a “repository” folder containing approximately 180 files without extensions, as well as a file named “data.csv,” which contains two columns. For each row in “data.csv,” the data in column A, “repository path,” is a path to a file in the repository folder, and the data in column B, “copy path,” is a path to which the file should be copied by your source code. 
Your overall task will be to export the data from the “repository” folder into a set of files. You will also be asked to generate a report that contains metadata for the extracted files. 
The files that you will extract from the repository are a collection of image (“.jpg”) and text (“.txt”) files. Some of these files have been assigned the wrong extension in column B of the data.csv file; i.e., some images have been given the “.txt” extension, and some text files have been given the “.jpg” extension. 
Your answer to the PROGRAMMING TASKS should be returned in the form of: 
.	1)  A source code file or files you create to complete the PROGRAMMING TASKS below. Please include comments in your code that indicate what code is directed towards which task.  
.	2)  A folder of exported files that you will create as instructed in the PROGRAMMING TASKS below.  
.	3)  A spreadsheet in CSV format called “results.csv” which contains the information requested in  the PROGRAMMING TASKS below.  
If you do not submit all three of the above requested items, we will not be able to score your answers to the PROGRAMMING TASKS, and you will receive a 0/30 for the PROGRAMMING TASKS section of the test. 
The “results.csv” report you generate should include the following column headings: 
.	1)  “Repository Path”;  
.	2)  “Copy Path”;  
.	3)  “Corrected File Path”;   
.	5)  “File Size”;  
.	6)  “Date of File Creation”;  
.	7)  “Line / Pixel Count”; and  
PROGRAMMING TASK 1.1: Copy each file in “data.csv” from the “repository path” to the “copy path,” and correct the extension of each of the mislabeled files. Report the correct extracted paths (including corrected file extensions) in “results.csv” in the “Corrected File Path” column.  
PROGRAMMING TASK 1.2: For each file, calculate the file size in bytes. Record this information in the “File Size” column of “results.csv.” 
PROGRAMMING TASK 1.3: For each file, determine the date on which the file in the repository was created. Record this information in the “Date of File Creation” column of “results.csv.” 
PROGRAMMING TASK 1.4: For each of the text files, calculate the number of lines per file; for each image file, calculate the number of pixels (i.e., height x width). Record this information in the “Line / Pixel Count” column of “results.csv.” 
