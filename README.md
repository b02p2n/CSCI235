java c
CSCI235 – Database Systems, SP424, Assignment 3 
[Assignment 3 (15% of total marks)
Due date: Thursday, 21 November 2024, 9:00 pm Singapore time.
Scope: The objectives of this assignment are to implement a hierarchical data structure using BSON documents, utilize the query language of the MongoDB database system, perform. data operations on BSON documents, and work with aggregations and cursors.
Assessment criteria: 
Marks will be awarded for:
•    Correct,
•    Comprehensive, and
•    Appropriate
application of the materials covered in this subject.
Only electronic submission through Moodle at: https://moodle.uowplatform.edu.au/ is accepted. All email submission will be deleted and mark 0 (“zero”) will be awarded.
For all the implemented tasks, your report or output must include a listing of all JSON scripts and its output.
The submission procedure is explained at the end of this specification.
Assignment Specification: 
Preliminary actions In this implementation task, you may use the virtual machine that runs MongoDB Enterprise Edition database server 3.6.5. or the actual installation of MongoDB in your computer system.
Download and unzip a file Assignment3-all-files.zip. You should get the specification of the Assignment 3 and a Java script. file, customerOrder.js.
Task 1 (5.0 marks) 
Task 1 Implementation of BSON documents 
Consider the following conceptual schema of a sample MongoDB database.

1.  Start the MongoDB client and connect to the database server.
2.  Perform. the following steps:
(a)  Create a new MongoDB database named with your UOW student number.
(b)  Create a collection named after the prefix of your UOW email address (e.g., "sjapit").
(c)  Insert  documents  into  the  collection  according  to  the  conceptual  schema provided above.  Ensure the documents  represent the  hierarchical structure effectively. You do not need to enforce all identification constraints from the schema. Insert at least one document for each class of objects defined in the schema, with meaningful values for each property.
(d)  Display the contents of the collection in a "pretty" format to verify the document structure.
3.  Save a report of these actions in a file named solution1.lst. To do this, copy the output from your terminal and paste it into the solution1.lst file, ensuring the actions appear in the same order as listed above.
Deliverables:
Submit a PDF of the solution1.lst file. The report should contain no errors and must include all processed methods and inserted documents displayed in a pretty format.
Task 2 (5.0 marks) 
Retrieving information from BSON documents Start mongo client and connect to the MongoDB database server. Next, process a script. file customerOrder.js to insert BSON documents into a collection customerOrder. Make yourself familiar with the contents of the collection.
a) Find all customer orders' detail by customer from Singapore who have ever made order after 1 October 2024.
b) 代 写CSCI235 – Database Systems, SP424, Assignment 3Java
代做程序编程语言Find the first name, last name, emails, and address of customers from Singapore who have ever bought a personal computer.
c)  Find the first name, last name and email of customer who have no telephone.
d) Find the first name, last name, date of birth (DOB), and the language of customers who speak both English and Mandarin.
e) Find the first name, last name, address, and balance of customer whose balance is in a range between 1000 and 2500.
f)  Find the first name, last name, and email of customer who bought MicroSD. Do not list the object id of the customer.Save the listings of processed queries and the results of processing in a file solution2.lst. To create a report, you can process the queries one by one and later ‘Copy’ the contents of Terminal window and ‘ Paste’ it into a file solution2.lst. The results of query processing must be included into a file solution2.lst in the same order as the respective queries listed above.
Deliverables Generate a file solution2.lst with a report from processing the queries listed above. The report MUST have no errors. The report must list all methods processed by mongo command line shell. Please save your solution2.lst in pdf format before submission.
Task 3 (5.0 marks) 
Aggregation and Data manipulations on BSON documents If you have not done it yet, start mongo client and connect to the MongoDB database server. Next, process a script. file customerOrders.js to insert BSON documents into a collection person. Make yourself familiar with the contents of the collection.
Use a query language of MongoDB database system to retrieve the following information from a collection customerOrder.
a) List the first name and last name of customer who made the order ord001.
b) Find the order number (orderNumber) of the order that was attended by a staff whose staff number = stf890.
c)  Find the first and last name of customer who have made orders on 15-NOVEMBER- 2024.
d) Find the total number of orders made by each customer. For each customer, list his/her email address and the total number of orders performed.
e) Change the staff number of order number ord005 to stf789.
f)  Delete from a collection the documents that contain information about the customers whose first name is Andrew, and the last name is Smith or customers who live in Singapore.Save the listings of processed queries and the results of processing in a file solution3.lst. To create a report, you can process the queries one by one and later ‘Copy’ the contents of Terminal window and ‘ Paste’ it into a file solution3.lst. The results of query processing must be included into a file solution3.lst in the same order the as respective queries listed above.
Deliverables Generate a file solution3.lst with a report from processing the queries listed above. The report MUST have no errors. The report must list all methods processed by mongo command line shell. Please save your solution3.lst in pdf format before submission.




         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
