# PROBLEM STATEMENT
You are given a reference monitor and 10 test cases. The reference monitor currently fails to handle 9 of
the test cases correctly (1-9). It is your job to fix the reference monitor so it handles each of the 10 test
cases without crashing.

To get started copy each of the 10 test cases, the securitylayer.r2py file, and the run_tests.py file into
your repy RUNNABLE directory. Execute run_tests.py using Python 2, which will run each of the test
cases and produce the following output:

## Results:
----------------------------
Test 1 Failed
Test 2 Failed
Test 3 Failed
Test 4 Failed
Test 5 Failed
Test 6 Failed
Test 7 Failed
Test 8 Failed
Test 9 Failed
Test 10 Passed

## Below is a description of each of the test cases.

Test Number Test Description
1           Close file without writing anything to it
2           Write past end of file
3           Write before beginning of file
4           Read past end of file
5           Read before beginning of file
6           Write empty string
7           Read negative size limit
8           Close file twice
9           Thread safe
10          Handles multiple files at once

## Submission
Turn in an updated version of securitylayer.r2py that passes each of the test cases. Name the file
securitylayer_[netid].r2py
