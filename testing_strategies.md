# Software Testing Strategies
**What to consider when choosing a software testing strategy?"**
- risks (is there a possibility that tests will disrupt function?)
- objectives (does the test satisfy all requirements and needs?)
- regulations (does the software meet all regulations based on region)

### Static Testing Strategy
- static test evaluates the quality of a system without running the system
- looks at elements related to the ssytem in order to detect problems as early as possible
    * developers review code after writing and before pushing (desk-checking)
- Static tests offer a decided advantage: If a problem is detected in the requirements before it develops into a bug in the system, it will save time and money. If a preliminary code review leads to bug detection, it saves the trouble of building, installing, and running a system to find and fix the bug

### Structural Testing Strategy
- designed on the basis of the software structure (white-box tests)
- run by testers with knowledge of the software and systems
- run on individual components and interfaces to identify localized errors in data flows
- using well crafted test harness to run the tests every time new code is added
- executed by developers


### Behavioral Testing Strategy
- focuses on how a system acts rather than the mechanism behind its functions
- focuses on workflows, configurations, performance, and all elements from a user experience (black-box tests)
- cover multiple scenarios
- focus on integrated systems rather than individual components
- most frequently run manually
- skilled manual testers are known for being able to follow a trail of bugs and ascertain their effect on user experience
- automation testing helps with repetitve actions such as regression tests to check new code has ot disrupted existing features
- does require some undrestanding of the system's technicality

## Cultivating Test Culture
- don't treat QA as the final development phase (testing should be integrated regularly and ongoing)
- encourage clarity in bug reporting to reduce unnecessary time asking for more information and miscommunication
- testing is a team effort
- define what is good enough to achieve quality
- user documentation or user manual should also be tested
- automation is good but doesn't fix poor test design

## Test Prep Tips
- start with a product map to model features and requirements of the product to provide a clear representation of the product
- involve testers in the beginning to help team understand customer goals
- create sample test data if needed
- understand the data flow
- define entry and exit points
- test the instructions

## Test Considerations
- consider the complete user journey
- embrace exploratory testing
- don't skip load testing (check how site handles traffic)
- some bugs are triggered by the perfect storm so they might be discovered in the wild (bug will slip to production)
- write logical acceptance tests


# Resources
https://www.browserstack.com/guide/software-testing-strategies-and-approaches
