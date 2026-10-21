# Experiment Results — AI Test Case Generator

## 1. Project Goal

The goal of this project is to evaluate whether ChatGPT can help generate software test cases faster than writing them manually.

The experiment uses a fictional login page and predefined requirements. No real or confidential data was used.

## 2. Experiment A: Manual vs. ChatGPT

Three test-case tasks were completed manually and then repeated using ChatGPT. AI time includes reviewing the generated result.

| Test Case               |        Manual Time | ChatGPT Time |        Time Saved | Accepted Without Changes? |
| ----------------------- | -----------------: | -----------: | ----------------: | ------------------------- |
| Valid login credentials |              3 min |        2 min |             1 min | Yes                       |
| Incorrect password      |              3 min |        1 min |             2 min | Yes                       |
| Empty password field    |      Approx. 4 min |        1 min |     Approx. 3 min | Yes                       |
| **Total**               | **Approx. 10 min** |    **4 min** | **Approx. 6 min** | **3 of 3 accepted**       |

The approximate time reduction was 60%.

Calculation:

Time reduction = (Manual time - ChatGPT time) / Manual time × 100

Time reduction = (10 - 4) / 10 × 100 = 60%

The third manual time was approximate, so the total and percentage are also approximate.

## 3. Experiment B: Input-Type Tests

Three additional prompts were used to evaluate how ChatGPT handled normal, messy, and difficult inputs. Time includes reviewing the result.

| Input Type | Task                                                                                                                     |  Time | Review Outcome                                                                      |
| ---------- | ------------------------------------------------------------------------------------------------------------------------ | ----: | ----------------------------------------------------------------------------------- |
| Normal     | Generate one successful-login test case using correct credentials                                                        | 1 min | Accepted without changes                                                            |
| Messy      | Generate a successful-login test case from an informal, less structured prompt                                           | 2 min | One edit: removed the step "attempt to log in"                                      |
| Difficult  | Generate exactly two test cases: successful login and incorrect password, with requirement links and no invented details | 3 min | Kept as generated; reviewer noted that the exact error-message text was unspecified |

## 4. Quality Review

* The normal prompt produced a test case that was accepted without changes.
* The messy prompt required one edit to the generated steps.
* The difficult prompt produced exactly two distinct test cases linked to R2 and R3.
* The reviewer noticed that the exact error-message text was not specified in the requirements. The output was kept unchanged because the requirements do not define the exact message wording.

These are preliminary user reviews, not independent verification that every generated test case is defect-free.

## 5. Requirements Used

* **R1:** Username and password are required.
* **R2:** Correct credentials allow successful login.
* **R3:** An incorrect password displays an error and prevents login.
* **R4:** If either field is empty, a message identifies the required field.

## 6. Limitations

* The login page is fictional; the test cases were not executed against a functioning application.
* The experiments cover a small number of prompts and test cases.
* Manual time for the empty-password case was approximate.
* The results reflect one person's review.
* The two experiments measure different things: Experiment A compares manual and AI-assisted time, while Experiment B examines how ChatGPT handles different prompt types.
* More trials are needed before drawing broader conclusions.

## 7. Conclusion

In Experiment A, ChatGPT reduced the recorded test-case writing time from approximately 10 minutes to 4 minutes, a reduction of about 60%.

In Experiment B, ChatGPT generated test cases from normal, messy, and difficult prompts. The messy prompt required one edit, while the normal and difficult outputs were kept as generated.

The findings are preliminary and should not be generalized beyond these trials.
