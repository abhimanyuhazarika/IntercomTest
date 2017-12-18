# IntercomTest
A program to read the full list of customers and output the names and user ids of matching customers (within 100km), sorted by User ID (ascending).

Requirements: <br/>R version 3.4.3,
              <br/>jsonlite package in R (for reading JSON data)
              <br/>testthat package in R (for running test cases)
              <br/>Imap package in R (for running test cases)
              
<br/><br/>
The unit tests can be run by executing the /tests/run_tests.R file. 
<br/>Executing the run_tests.R test file also runs the complete userDistance.R file and creates the CSV output file.
<br/>The unit tests are defined in /tests/test_userDistance.R file
              
<br/><br/>
The CSV file 'usersWithin100kms.csv' contains the final result.

<br/><br/>
The step by step execution and output after each step can be viewed at /docs/userDistance.pdf file
<br/>The R markdown script is available at /docs/userDistance.Rmd

<br/><br/>
The JSON-encoded user data with the latitudes and logitudes in degrees is kept at gistfile1.txt
