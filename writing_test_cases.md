# All About Writing Test Cases
- a set of actions executed to verify a particular feature or functionality of your software application
- contains test steps, test data, precondition, postcondition developed for specific test scenario to verify any requirement
- includes specific variables or conditions
- a testing engineer can compare expected and actual results to determine whether a software product is functioning as per the requirements of the customer
- documentation is important (simple but detailed)
- manual testing is usually done in a word document or spreadsheet (this is different than testing using jest or Rspec)

# Writing a Test Case
**Pre-conditions:** any assumptions that are being made or something has to happen before the event such as user can see account meaning user has be registered already

**Post-conditions:** anything that applies after the test case completes such as time and date of login stored in the database

## Scenario 1: Check login functionality

![test-cases_01](https://user-images.githubusercontent.com/59414750/108417232-f0bbeb80-71ec-11eb-8f36-c2cdbbbd11b0.png)

**Test Case:** #1

**Test Case Description**: Check response when valid email and password entered

**Test Data**: email: email@gmail.com password: 1235

**Test Steps**: 1) enter email 2) enter password 3) click sign in

**Expected Result**: Login should be successful

**Actual Result**: Login was successful

**Pass/Fail**: Pass

**Precondition**: Browser installed to have access to site

**Postcondition**: Date and time of last login is stored in database

## Things to Keep In Mind
- The description of what requirement is being tested
- The explanation of how the system will be tested
- The test setup like a version of an application under test, software, data files, operating system, hardware, security access, physical or logical date, time of day, prerequisites such as other tests and any other setup information pertinent to the requirements being tested
- Inputs and outputs or actions and expected results
- Any proofs or attachments
- Use active case language
- Test Case should not be more than 15 steps
- An automated test script is commented with inputs, purpose and expected results
- The setup offers an alternative to pre-requisite tests
- With other tests, it should be an incorrect business scenario order

# Best Practice
- test cases need to be simple and transparent
- create test cases with the end user in mind
- avoid test case repetition (if a test case is needed for executing some other test case, refer it by its test casse number in the precondition column)
- do not assume functionality and features of application while preparing test case (stick to specific douments)
- ensure 100% coverage
- test cases must be identifiable
- implement testing techniques
    * **Boundary Value Analysis (BVA):** As the name suggests it's the technique that defines the testing of boundaries for a specified range of values.
    * **Equivalence Partition (EP):** This technique partitions the range into equal parts/groups that tend to have the same behavior.
    * **State Transition Technique:** This method is used when software behavior changes from one state to another following particular action.
    * **Error Guessing Technique:** This is guessing/anticipating the error that may arise while doing manual testing. This is not a formal method and takes advantages of a tester's experience with the application
