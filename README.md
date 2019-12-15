# cmsc11-srs
This is a CMSC11 Student Registration System (SRS) which serves as a database system of the records of CMSC11 students. The basic features of SRS are the following: Create, Update and Delete Student Records where in the user must be able to do all these features using a keyboard input. However, the user can also create student records by reading input data from an input file students.txt or students.csv wherein the data is in the format (StudentID, FirstName, LastName, CMSC11Section, Hands-On Exam 1, Hands-On Exam 2, Hands-On Exam 3, Subject 1, Subject 2, Subject 3). Display the records of all students in alphabetical order of the surname. Moreover, it display the following additional information: Summary statistics for each Hands-On Exams at the bottom: Lowest score, Highest score, Average score rounded to 3 decimal places and Standard deviation rounded to 3 decimal places.  Apart from the basic student information, the following data displayed as well: Total Hex Score, Grade – will be calculated based on the total hex score. Follow the grading system below: • HD (High Distinction) = total score of 135 or more • D (Distinction) = total score of 120 to 134 • P (Pass) = total score of 100 to 119 • C (Credit) = total score of 75 to 99 • F (Fail) = total score of 74 and below. Export masterlist and save as .csv file . Export the masterlist to a file and save it as masterlist.csv with one student record per line and each information separated by a comma. Enroll or Drop a subject (maximum of 3 subjects per student), By default, all students are automatically enrolled to CMSC11 and cannot unenroll CMSC11. Students must be enrolled to at least to one subject (i.e. CMSC11) and at most 3 subjects. When a student drops a subject, the dropped subject automatically removed from the student’s Subjects Enrolled list. Moreover, the student cannot drop CMSC11 as it must have at least 1 enrolled subject. Search Student Record, search a student record using student’s last name and display the matched record(s). Create, Update and Delete Subject. The user must be able to do all these functionalities using keyboard input. However, the user must also be able to create a new Subject record by reading input data from an input file students.txt wherein the data is in the format (SubjectID, SubjectCode, SubjectTitle). When Updating or Deleting a Subject, all changes reflected directly in the masterlist. Search Subject, this feature must be able to search a subject using the subject’s code (e.g., CMSC11, cmsc11, Cmsc11, etc) and display the matched record(s). If the subject does not exist, prompt the user if he/she wants to create subjects by reading input data from an input file subjects.txt.