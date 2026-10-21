# Experiment Results — AI Test Case Generator

## 1. Project Goal

The goal of this project is to evaluate whether ChatGPT can help generate software test cases faster than writing them manually.

The experiment uses a fictional login page and predefined requirements. No real or confidential data was used.

## 2. Experimental Method

Three test-case tasks were completed manually and then repeated using ChatGPT.

Time was recorded in minutes. Manual times are approximate where indicated. AI times include reviewing the generated result.

## 3. Results

| Test Case               |        Manual Time | ChatGPT Time |        Time Saved | Accepted Without Changes?      |
| ----------------------- | -----------------: | -----------: | ----------------: | ------------------------------ |
| Valid login credentials |              3 min |        2 min |             1 min | Yes                            |
| Incorrect password      |              3 min |        1 min |             2 min | Yes                            |
| Empty password field    |      Approx. 4 min |        1 min |     Approx. 3 min | Yes                            |
| **Total**               | **Approx. 10 min** |    **4 min** | **Approx. 6 min** | **3 of 3 AI results accepted** |

## 4. Time Comparison

The manual process took approximately 10 minutes in total. Using ChatGPT took 4 minutes, including reviewing each result.

The approximate time reduction was 60%.

Calculation:

Time reduction = (Manual time - ChatGPT time) / Manual time × 100

Time reduction = (10 - 4) / 10 × 100 = 60%

Because the third manual measurement was approximate, the total and percentage are also approximate.

## 5. Quality Review

* Valid login case: accepted without changes.
* Incorrect password case: accepted without changes.
* Empty password case: accepted without changes.

All three AI-generated results were accepted during the user's review. This is a preliminary review, not an independent verification that every result is defect-free.

## 6. Limitations

* The experiment used only three test-case tasks.
* Manual time for the empty-password case was approximate.
* The results reflect one person's review and a small sample.
* The experiment does not establish that ChatGPT will always be faster or more accurate.
* Further testing is needed with normal, messy, and difficult inputs as required by the project guide.

## 7. Conclusion

In these three trials, ChatGPT reduced the recorded test-case writing time from approximately 10 minutes to 4 minutes, a reduction of about 60%. All three generated cases were accepted without changes during the review.

More experiments are needed before drawing broader conclusions.
