# AI Test Case Generator

## Project Overview

AI Test Case Generator is a no-code project that explores how generative AI can assist in creating structured software test cases from written system requirements.

The project uses a fictional login page and synthetic requirements to examine test case generation, clarity, requirement coverage, and the importance of human review.

No real user data, credentials, or confidential information are used.

## Problem Statement

Writing software test cases manually can be time-consuming. Important scenarios, inputs, or expected results may also be overlooked.

## Project Objective

To evaluate how AI-assisted test case generation can support the software testing process by examining task completion time, test case clarity, requirement coverage, and the need for human review.

## Project Scope

The project includes:

* Generating structured test cases from written requirements.
* Defining test inputs and expected results.
* Reviewing test cases against the specified requirements.
* Identifying unclear or incomplete requirements.
* Exploring different input scenarios.
* Comparing manual and AI-assisted workflows.
* Recording experimental observations and limitations.

## Synthetic Login Requirements

The fictional login system is based on the following requirements:

1. A username and password are required.
2. Correct credentials allow successful login.
3. An incorrect password displays an error and prevents login.
4. Empty fields display a message identifying the required field.

These requirements are used as the reference for reviewing the generated test cases.

## Methodology

The project follows these steps:

1. Define the fictional login system and its requirements.
2. Create an initial manual set of test cases.
3. Generate test cases using AI assistance.
4. Review the test cases for input clarity, expected-result clarity, and requirement coverage.
5. Explore normal, messy, and difficult input scenarios.
6. Record observations and identify requirements that need clarification.

## Experimental Results

The project records observations from the manual baseline and AI-assisted experiments, including task completion time, generated test cases, and quality review findings.

Detailed experimental records and results are documented in [`experiments.md`](experiments.md).

The results are preliminary and should not be interpreted as proof of AI accuracy or as validation of a functioning software application.

## Test Case Documentation

The generated and reviewed test cases are documented in [`test-cases.md`](test-cases.md).

They describe test inputs, execution steps, expected results, and the associated requirements where applicable.

## Limitations

* No functioning login application was tested.
* Test cases were generated and reviewed but not executed against a real application.
* The manual baseline does not provide sufficient detail for a fair numerical comparison of test case quality.
* The expected behavior for whitespace-only usernames remains unresolved.
* The experiments are preliminary and require more consistent validation.

## Data Safety

All requirements and examples are fictional and synthetic.

No real credentials, personal data, or confidential information were used.

## Conclusion

AI assistance may help reduce the effort required to draft software test cases. However, generated test cases require human review to identify unclear requirements, improve expected results, and assess requirement coverage.

Further validation is needed to compare manual and AI-assisted workflows fairly and to verify test cases against a functioning application.

## Project Status

This project is a preliminary, no-code evaluation of AI-assisted software test case generation. It does not represent a deployed AI model or an automated testing system.
