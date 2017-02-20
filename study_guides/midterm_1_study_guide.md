# CS 1632 Midterm 1 Exam Study Guide - Spring 2017

The midterm is on 27 FEB 2017.

The midterm will cover everything we have covered up to the lecture of 20 FEB 2017 (i.e., nothing from the web testing lecture on 22 FEB will be included).  I recommend you review the slides and the textbook (see syllabus.md for reminders of which chapters were required reading).

However, here are the key topics to study in preparation for the test.

## TESTING THEORY AND TERMINOLOGY
* Equivalence class partitioning
* Boundary and interior values
* Base, Edge, and Corner cases
* Static vs Dynamic testing
  * Know the differences and examples of each
* Black/White/Grey box testing
  * Know the differences and examples of each

## REQUIREMENTS ANALYSIS
* What makes a good or bad requirement?
* Testability - requirements must be:
  * Complete, consistent, unambiguous, quantitative, feasible
* Functional Requirements vs Non-Functional (Quality Attributes)
  * Be able to define and write your own
* Traceability Matrices
  * Be able to define and write your own

## TEST PLANS
* Given a list of requirements, be able to write a test plan
* Terminology: test cases, test plans, test suites, test runs
* Verification vs validation

## DEFECT REPORTING
* Be prepared to report a defect based on a test case
* Remember the defect template:
  * SUMMARY, DESCRIPTION, REPRODUCTION STEPS, EXPECTED BEHAVIOR, OBSERVED BEHAVIOR
  * Optionally: SEVERITY/IMPACT, NOTES
  * Levels of severity: BLOCKER, CRITICAL, MAJOR, NORMAL, MINOR, TRIVIAL
* Enhancements vs defects
  * Be prepared to argue if something is a defect or enhancement
* Coding mistakes vs defects

## AUTOMATED TESTING
* Pros and cons of automated testing
* Unit tests vs system/acceptance/integration tests
* Writing automated tests:
  * PRECONDITIONS, POSTCONDITIONS, EXECUTION STEPS, INPUT/OUTPUT VALUES

## UNIT TESTING
* Be prepared to write some unit tests in JUnit
* Pay special attention to assertions
* Stubs, test doubles, mocks, and verification
* Be able to explain code coverage and what it's good for/not good for
* Testing private methods
  * You will NOT need to use/know about reflection
  * Why/why not one might not test them?

## TDD
* The red-green-refactor loop
* Principles of TDD:
  * YAGNI
  * KISS
  * "Fake it 'til you make it"
  * Avoid interdependency
  * Avoid slow tests
* Benefits and drawbacks of TDD
  * When to use it?
  * When not to use it?

## WRITING TESTABLE CODE
* Basic strategies for testable code
* The DRY Principle
* The SOLID Principles
* The Law of Demeter
* TUFs and TUCs

## COMBINATORIAL TESTING
* Benefits / Drawbacks
* Given a problem, be able to make a truth table
* Understand what a covering array is
* Be able to make a simple covering array
