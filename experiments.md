# Experiments and Results

## Project Goal

Evaluate whether AI-assisted software test case generation can reduce the time required to draft test cases while maintaining clear inputs, expected results, and requirement coverage. The experiments used a fictional login page and synthetic requirements.

## Manual Baseline

* **Reported duration:** Approximately 5 minutes.
* **Initial scenarios written:**

  * Successful login.
  * Incorrect password.
  * Empty fields.

**Review observations:**

* Inputs and expected results were not recorded in the submitted baseline.
* The empty-fields scenario was not separated into empty-username and empty-password cases.

These observations describe the recorded baseline; they do not establish that the original work was incorrect.

## Experiment 1: AI-Assisted Generation

* **Reported duration, including review:** Approximately 2 minutes.
* **Output:** 5 proposed test cases.

The cases covered successful login, incorrect password, empty username, empty password, and both fields empty.

## Experiment 2: Handling Ambiguity

* **Reported duration, including review:** Approximately 1 minute.
* **Output:** 6 proposed test cases.

An additional scenario considered a username containing only whitespace. Since the requirements did not define how this input should be handled, the expected result was left unresolved pending clarification.

## Quality Review of Experiment 2

| Criterion                             |      Result |
| ------------------------------------- | ----------: |
| Input clarity                         |  6/6 (100%) |
| Expected-result clarity               | 4/6 (66.7%) |
| Cases linked to specific requirements | 5/6 (83.3%) |

These figures reflect the user's initial checklist review. They are not independent validation results.

## Time Comparison

| Workflow                 | Approximate duration |
| ------------------------ | -------------------: |
| Manual baseline          |            5 minutes |
| AI-assisted experiment 1 |            2 minutes |
| AI-assisted experiment 2 |             1 minute |

Relative to the manual baseline:

* Experiment 1 showed an estimated time reduction of 60%.
* Experiment 2 showed an estimated time reduction of 80%.

These are preliminary estimates based on user-reported times. Experiment 2 included an additional ambiguous scenario, so the tasks were not identical. The reported AI-assisted times included review, but exact start and end times were not recorded.

## Required Scenario Coverage

The project brief asks for comparison using normal, messy, and difficult cases, both with and without AI assistance.

* **Normal case:** Successful login with valid credentials.
* **Messy case:** A username containing only whitespace. The expected behavior requires clarification.
* **Difficult case:** An edge case must be selected and evaluated. The existing experiments do not yet document a completed difficult-case comparison.

The scenario descriptions above do not establish that all three cases have been tested in both workflows. Their results must be recorded only after the comparisons are performed.

## Limitations

* No functioning application was available for executing the test cases.
* The recorded times are approximate.
* Manual baseline inputs and expected results were not documented sufficiently for a numerical quality comparison.
* Quality scores came from an initial review and were not independently verified.
* The whitespace-only username behavior requires clarification.
* The number of revisions made during each workflow was not recorded.
* A consistent comparison across normal, messy, and difficult cases remains to be completed.

## Next Steps

1. Define a consistent acceptance checklist before further experiments.
2. Review test cases against the four original requirements.
3. Clarify whitespace handling with the hypothetical system owner.
4. Select a difficult scenario based on the available requirements and clearly document any unresolved assumptions.
5. If possible, repeat the manual and AI-assisted workflows using comparable tasks.
6. Record actual start and end times, review time, number of revisions, and whether the output meets the acceptance checklist.
7. Document the fixed instructions or assistant setup actually used for AI-assisted generation.

## Conclusion

The preliminary experiments suggest that AI assistance can speed up drafting and help identify ambiguous requirements. Additional validation is necessary before drawing firm conclusions about test case quality or overall productivity improvement.
