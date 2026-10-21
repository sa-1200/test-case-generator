Experiments and Results
1. Project Goal
Evaluate whether AI-assisted software test case generation can reduce the time required to draft test cases while maintaining clear inputs, expected results, and requirement coverage.
The experiments used a fictional login page and synthetic requirements.
2. Manual Baseline
Reported duration: Approximately 5 minutes.
Initial scenarios written:
Successful login.
Incorrect password.
Empty fields.
Review observations:
Inputs and expected results were not recorded in the submitted baseline.
The empty-fields scenario was not separated into empty-username and empty-password cases.
These observations describe the recorded baseline; they do not establish that the original work was incorrect.
3. Experiment 1: AI-Assisted Generation
Reported duration, including review: Approximately 2 minutes.
Output: 5 proposed test cases.
The cases covered successful login, incorrect password, empty username, empty password, and both fields empty.
4. Experiment 2: Handling Ambiguity
Reported duration, including review: Approximately 1 minute.
Output: 6 proposed test cases.
An additional scenario considered a username containing only whitespace. Since the requirements did not define how this input should be handled, the expected result was left unresolved pending clarification.
5. Quality Review of Experiment 2
Criterion Result
Input clarity 6/6 (100%)
Expected-result clarity 4/6 (66.7%)
Cases linked to specific requirements 5/6 (83.3%)
These figures reflect the user’s initial checklist review. They are not independent validation results.
6. Time Comparison
Workflow Approximate Duration
Manual baseline 5 minutes
AI-assisted experiment 1 2 minutes
AI-assisted experiment 2 1 minute
Relative to the manual baseline:
Experiment 1 showed an estimated time reduction of 60%.
Experiment 2 showed an estimated time reduction of 80%.
These are preliminary estimates based on user-reported times. Experiment 2 included an additional ambiguous scenario, so the tasks were not identical.
7. Limitations
No functioning application was available for executing the test cases.
The recorded times are approximate.
Manual baseline inputs and expected results were not documented sufficiently for a numerical quality comparison.
Quality scores came from an initial review and were not independently verified.
The whitespace-only username behavior requires clarification.
8. Next Steps
Define a consistent acceptance checklist before further experiments.
Review test cases against the four original requirements.
Clarify whitespace handling with the hypothetical system owner.
If possible, repeat the experiments using comparable tasks and record exact start and end times.
9. Conclusion
The preliminary experiments suggest that AI assistance can speed up drafting and help identify ambiguous requirements. Additional validation is necessary before drawing firm conclusions about test case quality.
