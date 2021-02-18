# Software Testing
**Software Testing:** activity whcih involves controlling the quality of the softwar and matches with the software requirements to make customers happy

#### Scandals as a Result of Not Testing
- Knights ($440 million error)
    * lost money in 30 minutes due to a software bug that flooded the market with unintented trades

## Software Development Life Cycle
**SDLC:** how software is delivered toa  customer in a series of steps
1. Plan: what do we want?
2. Define: how will we get what we want? (gather buisness requirements, create diagram, perform analysis, design IT infrastructure)
3. Build: let's create what we want (developers write code)
4. Test: did we get what we want (write test cases, execution of test cases)
5. Deploy: let's start using what we got (shared with customers and users and get feedback)
6. Maintain: let's get this closer to what we want (fix any errors that might arise)

## Testing Activities
- **Test plan** is a document describing testing scope and activities
    * identifies the task
    * who will do each task
    * testing environments
    * which design testing practice will be use
- **Test specification** contains two components
    * design test cases (determine how identified test conditions are going to be exercised)
    * build test cases (implement of test cases such as test scripts)
- **Test Execution** where QA runs the test and makes sure the application matches with the expected results with the most important test cases prioritized and executed first
    * for example with Amazon, the most important feature would be user can add item to basket
    * for banking, the most important feature would be money transfer
    * issue converted to bug report
- **Test completion** QA testing activities completed and high level bugs are solved and product ready to deliver

## Bug Reporting
- *Visual Bugs:* truncated images, alignment issues
- *Functional Bugs:* user's can't proceed
- *Performancer Issues:* takes 10 seconds to open the page
- bug report should be self explanatory and as simple as possible

      Summary: what the bug is
      Steps to Reproduce: how
      Expected Results:
      Actual Results:
      Screenshots:
      
 ### Bug Life Cycle
<img width="422" alt="Screen Shot 2021-02-18 at 9 20 02 AM" src="https://user-images.githubusercontent.com/59414750/108387109-86924f00-71ca-11eb-9cf8-c4a3c2d667e5.png">

## Software Requirement Specifications
- give basic knowledge about how the software should work
- typical test case parameters (may not need to use all)
   * test scenario
   * test description
   * test steps
   * preconditions (assumptions)
   * test data
   * expected result
   * priority
   * environment information
- test checklists have less information and beneficial to use when testing team is more experienced and everyone knows the product very well (smaller teams)
- test cases are used in larger teams and work with inexperience colleagues

## Black Box Testing
<img width="806" alt="Screen Shot 2021-02-18 at 11 18 22 AM" src="https://user-images.githubusercontent.com/59414750/108402649-0aecce00-71db-11eb-9007-ac187e9ae3c6.png">

- method in which the internal implementation of the function is not known by the tester
- test website by browser and verify output with the expected result
- attempt to find errors in incorrect function, interface issues, behavior, and initialization/termination errors
- *Functional Testing*: done by software testers
- *Non-Functionationl*: checks non functional aspect such as performance, usability, reliability (how many people can use the website at one time)
- *Regression*: testing existing software to check new change didn't break the functionality
- *White Box Testing*: the internatal design is known to the tester

# Best Practices
A well-written test case should:

1. Easy to understand and execute
2. Create Test Cases with End User’s perspective
3. Use unique test case id
4. Have a clear description
5. Add proper pre & postconditions
6. Specify the exact expected result
7. Test cases should be reusable & maintainable
8. Utilize testing techniques
9. Get peer review

If you follow the best practices to write test cases then anyone in the team can understand and execute the well-written test case easily. It should be easy to read and understand, not only for whoever wrote it but also for other testers as well.

# Resources
https://blog.testlodge.com/how-to-write-test-cases-for-software-with-sample/
https://medium.com/@appsierra/a-complete-guide-for-writing-manual-test-case-with-hacks-c0faa92669e5
https://www.guru99.com/test-case.html
