AI Test Case Generator
Project Overview
AI Test Case Generator is a no-code project that explores how artificial intelligence can help generate structured software test cases from system requirements.
The project uses a fictional login page and synthetic requirements. No real user data, credentials, or confidential information are used.
Problem Statement
Writing software test cases manually can take time, and important scenarios or expected results may be missed.
Project Objective
Evaluate whether AI-assisted test case generation can reduce task completion time while producing clear and relevant test cases.
Scope
The project covers:
Generating test cases from written requirements.
Specifying test inputs and expected results.
Identifying unclear requirements.
Reviewing the generated test cases against a predefined checklist.
Comparing manual and AI-assisted workflows.
Synthetic Login Requirements
Username and password are required.
Correct credentials allow successful login.
An incorrect password displays an error and prevents login.
Empty fields display a message identifying the required field.
Preliminary Experiment Results
Workflow Approximate Time Initial Output
Manual baseline 5 minutes 3 initial scenarios
AI-assisted experiment 1 2 minutes 5 test cases
AI-assisted experiment 2 1 minute 6 test cases
The times are user-reported estimates and include review. The experiments are preliminary and were not conducted on a functioning login application.
Experiment 2: Quality Review
Input clarity: 6/6 (100%)
Expected-result clarity: 4/6 (66.7%)
Cases linked to specific requirements: 5/6 (83.3%)
These scores reflect an initial review of the generated test cases, not the accuracy of a deployed AI model or the correctness of a real application.
Limitations
No functioning login application was tested
Test cases were generated and reviewed, not executed
The manual baseline details were not recorded sufficiently for a fair numerical quality comparison
The handling of whitespace-only usernames remains an unresolved requirement
Data Safety
All requirements and examples are fictional. No real credentials or sensitive data are included
Conclusion
The preliminary results suggest that AI assistance may reduce the time needed to draft software test cases. Further validation is needed to assess quality consistently and verify the cases against an actual application
Conclusion
The preliminary results suggest that AI assistance may reduce the time needed to draft software test cases. Further validation is needed to assess quality consistently and verify the cases against an actual application.
