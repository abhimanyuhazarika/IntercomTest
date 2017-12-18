# IntercomTest
A program to read the full list of customers and output the names and user ids of matching customers (within 100km), sorted by User ID (ascending).

**Requirements:** 
- R version 3.4.3,
- jsonlite package in R (for reading JSON data)
- testthat package in R (for running test cases)
- Imap package in R (for running test cases)
              
<br/><br/>
**Testing**
- The unit tests can be run by executing the /tests/run_tests.R file. 
- Executing the run_tests.R test file also runs the complete userDistance.R file and creates the CSV output file.
- The unit tests are defined in /tests/test_userDistance.R file
              
<br/><br/>
**Output**
- The CSV file 'usersWithin100kms.csv' contains the final result. The users who are within 100 kms of Intercom's Dublin office are listed in ascending order of user_id.

<br/><br/>
**Documents**
- The step by step execution with descriptions and output after each step can be viewed at /docs/userDistance.pdf file
- The R markdown script is available at /docs/userDistance.Rmd

<br/><br/>
**Dataset**
- The JSON-encoded user data with the latitudes and logitudes in degrees is available at gistfile1.txt
