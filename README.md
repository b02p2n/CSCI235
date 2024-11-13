java c
CSCI235 – Database Systems
2024 S4
Implementation Task 3
Due on 21 November 2024
Scope
This laboratory includes two tasks related to the implementation of queries and data manipulations on a collection of documents stored in MongoDB database. I have decided to combine Implementation Task 3 and Implementation Task 4 into one implementation task.
This Implementation is due by Thursday, 21 November 2024, 9:00 pm Singapore time. This task is worth 10% of the total assessment for the subject.
Only electronic submission through Moodle at: https://moodle.uowplatform.edu.au/   is accepted. All email submission will be deleted and mark 0 (“zero”) will be awarded.
For all the implemented tasks, your report or output must include a listing of all JSON scripts and its output.
The submission procedure is explained at the end of this specification.
Specification
Preliminary Task
For this task, you  may  choose  to  use  either  a  virtual  machine  running  MongoDB Enterprise Edition 3.6.5 or your own local installation of MongoDB.
1.  Download the file studentSeminar2.js from the SAMPLE DATABASE section on Moodle.
2. Open the MongoDB command line interface (CLI).
3. To    create    the    sample    database,    run    the    following    command: load('studentSeminar.js').  This  will  generate  a  collection  containing  student seminar enrollment data.
4. Verify the data by running the command: db.studentSeminar.find().pretty().
No report submission is required for this task.
Tasks
Task 1 (2.0 marks)   Reverse Engineering
1.  Select a document from the studentSeminar sample collection.
2.  Using UML notation, create an equivalent object diagram to represent the document.
3.  Identify the implementation technique used for the document (e.g., one-to-one association,  one-to-many  association)   based  on  the   BSON   Design  techniques discussed in Topic 17.
4. You may use UMLet or any other UML drawing tool you have installed to create your conceptual model.
(2.0 marks)
Deliverables
Submit a file solution1.pdf containing the object diagram of the document in UML notation. Please put your UOW student number and name in all your solution.
Task 2 (8.0 marks)
MongoDB Data Manipulation
Use the data  manipulation  language  of  MongoDB  database  system  to  process  the following requirements:
a) Find all seminars whose description is "In-memory Database.".             (1.0 mark)
b) Find total number of seminars the student std009 have enrolled in.       (1.0 mark)
c)  Find the details of all seminars that have students received marks higher than 80.
(1.0 mark)
d) Find the det代 写CSCI235 – Database Systems 2024 S4 Implementation Task 3
代做程序编程语言ails of all 3 credit points seminars that the student Sharon Smith has attended. You MUST use conjunction operator to implement this query. (1.0 mark)
e) Insert a new seminar to the studentSeminar collection. The detail of the seminar is as followed:
SeminarID : sem006,
Seminar Description : Attending Online Course, Seminar Date : 12-November-2024,
Credit Point : 2
(1.0 mark)
f)  Change the seminar date of seminar sem006 to 18 November 2024.     (1.0 mark)
g) Add a student's enrolment to the studentSeminar collection. The student is enrolled to attend the seminar sem006 on 12 November 2024. The detail of the student is as follow:
studentID: std006
student name: Ofelia Ashley address: 123, Bukit Timah
telephone: [ handphone: 93858134, residentphone: 64352893 ] enrol to: sem002
mark received: 0
enrolment Date: 12-November-2024
Note: You can leave the mark received as 0 because the mark is not available yet.
(2.0 marks)
DeliverablesSubmit a file named solution2.pdfcontaining a report on the MongoDB data manipulation performed for the operations described above. Copy the contents of the terminal window showing  the  manipulation  process,  paste  it  into  the  output  file,  and  save  it  as solution2.pdf. Your  report  MUST  include  the  MongoDB  statements  used  and their respective outputs. Ensure your UOW student number and name appear on all parts of your submission. Reports missing the required listing of processed queries as specified will not receive any marks.
Submissions
This implementation task is due by 9:00 pm (2100 hours) Thursday, 21 November 2024, Singapore time.
Submit the files solution1.pdf and solution2.pdf through Moodle in the following way:
1)   Zip all the files (Solution1.pdf and solution2.pdf into one zipped folder. Name your zipped file as YourName-IT3)
2)  Access Moodle at http://moodle.uowplatform.edu.au/
3)   To login use a Login link located in the right upper corner the Web page or in the middle of the bottom of the Web page
4)   When successfully logged in, select a site CSCI235 (SP424) Database Systems
5)   Scroll down to a section Submissions of Implementation Tasks
6)   Click at Submit your Implementation Task 3 here link.
7)   Click at a button Add Submission
8)   Move the zipped file created in Step 1 above into an area provided in Moodle. You can drag and drop files here to add them. You can also use a link Add…
9)   Click at a button Save changes,
10) Click at check box to confirm authorship of a submission,
11) When you are satisfied, remember to click at a button Submit assignment.




         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
