# Manual-testing-project

![Agenda Diagram](https://github.com/Iulia-Calota/manual-testing-project/blob/main/Agenda%20project.png)


#####
# Test project Fenty Beauty 

For this project, I am using Fenty Beauty (FEИTY BEAUTY), a cosmetics brand by Rihanna. The mission statement for the brand is: 

**"So that people everywhere would be included and is created for everyone."**

## Sprint 2 Weeks:

|  Start Date  |  Test process                      |   Tester           | 
| ----------   | -----------------------------      | ------------------ |
| 05/10/2024   | STLC (Software Testing Life Cycle) | Calota Iulia       |      

## 1.Introduction

- Static and Dynamic testing
- Software Testing Life Cycle (STLC)


### Static testing
- Early Phase: Begins early in the SDLC.

- Quality Evaluation: 
    - Evaluates the quality and builds confidence in work products like requirements, code analysis, test plans, test cases, and product backlogs.
Benefits: 
    - Early testing saves time and money, fulfilling the principle of “Early testing saves time & money.”
Stakeholder Involvement: 
    - Involves various stakeholders to review and improve the product.

###  Dynamic Testing

- Triggering Failures:
    -  Identifies defects and triggering failures.
- Functionality Validation: 
    - Verifying and Validates the functionality of the website **[https://fentybeauty.com]**
- Test types:
    - Functional Testing, Non- Functional Testing, Black box testing

###  Objectives of testing

-  Ensures the software is reliable, efficient, and meets user requirements.
-  Triggers failures and identifies defects.
-  Reduces the risk of inadequate software quality.
-  Builds confidence in the test object, contributing to decisions to move to the next SDLC stage, such as the release decision.

### Testing principles used:

- Early Testing: 
    - Saves time and money; early review of test design, requirements, test plan, test cases, and code analysis is cost-effective for finding and fixing defects.
- Defect Clustering: 
    - Follows the Pareto principle where a small number of modules contain most defects. This insight is crucial for risk-based testing.
- Context Dependency: 
    - Testing varies based on context; different software systems have different risk levels, requiring different approaches, tools, and technologies.

## Software Testing Life Cycle (STLC)

 ~~After planning the objectives, principles, and test approaches, we defined the entry and exit criteria, executed the test suites, generated reports, and completed the test process, making the project ready for a new version release.
~~

## Entry Criteria
- Review the **Fenty** website's specifications for **"Favorites"** and **"Sign in"** functionalities to be tested.
- User stories (test suites, test cases) are complete and reviewed.
- Test data is prepared, validated, and available.
## Exit Criteria

- User Experience: Usability testing shows that the website is **user-friendly** and accesible.
- Cross-Check Compatibility: The website is **tested across various browsers**, ensuring responsive design.
- Analytics tools are correctly implemented and **reporting**.

### 1. Test Planning

**Objective**: Plan the testing process.
**Activities:**
- Define the scope and objectives of testing.
- Identify resources (team members, tools, etc.).
- Estimate time and effort for testing.
**Tools**: 
- Jira (for project management), **TestRail** (for test case management)
**Deliverables:**
- Test Summary Report

## 2. Test Design

**Objective:** 
- Create detailed test cases.
**Activities:**
- Write test cases for **"Favorites"** and **"Sign in"** functionalities.
- Review and get approval for the test cases.
- Tools: **TestRail**
**Deliverables:**
- Test cases for "Favorites" and "Sign in"

## 3. Test Implementation

 **Environment Setup**
- Testing environment:**Prod**
- Test data:**Creating new account**
- Devices + Browsers: **PC** ( Windows 11 Pro), **Browsers** (Googke Chrome, Microsoft Edge, Mozilla Firefox)

## 4. Test Execution

**Objective:** 
- Execute the test cases.
**Activities:**
- Execute the test cases as per the test plan.
- Log defects in Jira for any issues found.
- Conformation testing and regression testing after bug fixes.
**Tools:** 
- TestRail (for test execution), Jira (for bug tracking)
**Deliverables:**
- Test execution logs
- Defect reports

## 5. Test Cycle Closure

**Objective:** 
- Conclude the testing process.
**Activities:**
- Ensure all planned test cases are executed.
- Confirm all critical bugs are fixed and closed.
- Document the test results and prepare a test summary report.
**Deliverables:**
- Test summary report

### Implementation in the Project

# Sprint Planning (05/10/2024 - 05/24/2024)

# Requirement Analysis and Test Planning (05/10/2024 - 05/11/2024):
- Review requirements for "Favorites" and "Sign in".
- Create test plan and RTM.
# Test Case Development (05/12/2024 - 05/13/2024):
- Develop and review test cases in TestRail.
# Environment Setup (05/14/2024):
- Prepare the test environment.
# Test Execution (05/15/2024 - 05/20/2024):
- Execute test cases.
- Log and track bugs in Jira.
- Perform confirmation and regression testing after bug fixes.
# Test Cycle Closure (05/21/2024 - 05/24/2024):
- Ensure all tests are executed and critical bugs are resolved.
- Generate and review the test summary report.
# Test deliverables
**- Test Summary Report: **
- Document covering:
- Number of test cases executed.
- Pass/fail status of test cases.
- Number and severity of bugs found.
- Confirmation and regression test results.


## 2.7 Test Monitoring and Control

- Various periodic reports will be generated to reflect the current status of the testing process.
- Offering feedback to the QA team and other stakeholders regarding the progress.
- Conveying test results achieved so far to all relevant parties.
- Identifying and tracking relevant test metrics.
- All test cases are written and reviewd.
- Planning and Estimation to determine the future course of action based on the metrics being tracked.
- Prioritize testing efforts in a different way.
- Reorganize test schedules and deadlines.
- Restructure the test environment.
- Reprioritize the test case and conditions.

## 3. Test Deliverables

### 3.1 Test Condition

In total, there are 30 test conditions that detail what will be tested on the  application.
  [Test condition]
- Verify if each field in the 'New Customer' section is found in the documentation
- Verify if new customer can be added using New customer section with valid data
- We are checking the system does not allow the selection of a future birth date in "Date of Birth" field
- Verify if the system should display an error message when attempting to enter a PIN code with fewer than 6 digits.
- Verify if when mandatory fields are left empty a new customer  cannot be created 
- Verify that  Customer Name field doesn't accept numbers 
- Verify that an error message is displayed when special characters are entered in the Customer Name field
- Verify that an error message is displayed when special characters are entered in the  Address field
- Verify that an error message is displayed when numbers are entered in the  city field
- Verify that an error message is displayed when numbers are entered in the state  field
- Verify that an error message is displayed when special characters are entered in the  Pin field
- Verify that when an invalid email address is entered in the E-Mail field, an error message is received
- Verify that an error message is displayed when special characters are entered in the Telephone number   field
- Verify that when entering an existing email during the creation of a new customer, the system will not allow the account to be created
- Verify First Character of Customer Name Cannot Have a Space
- Verify First Character of City  field Cannot Have a Space
- Verify that an error message is displayed when special characters are entered in the Customer ID field
- Check if an error message appears when trying to enter an already deleted user in the 'Customer ID' field
- Verify that clicking the "Reset" button should reset the values in the "Edit Customer" form to their initial state.
- Verify that  the same Email Id exists in the system, the system shows an error
- Verify that the Customer ID field does not allow a space as the first character.
- Verify that the Customer ID field does not allow a space as the first character.
- Verify that clicking the "Reset" button should reset the values in the "Delete  Customer" form to their initial state.
- Verify that "No Changes Made" Pop-Up Message in the "Edit Customer" Section Upon Submit.
- Verify that an error message is displayed when special characters are entered in the  Customer ID field
- Verify that a manager can delete an existing customer 
- Verify if the system displays an error message when the Customer ID field is left empty
- Verify if the password field  hide/show functionality is working in chrome browser
- Verify that manager can edit customer data from Edit customer section 
- Verify if the system displays an error message when the Customer ID field is left empty
  
### 3.2 Test Cases

- Test cases are designed to cover various scenarios and functionalities of the Guru99 application.
- Each test case includes detailed steps, expected results, and preconditions.
- There are 30

### 3.3 Daily Test Summary Report

- The report generated on , shows the execution of 30 test cases, out of which 10 failed.
  ![Daily report]
  ![Daily report]
- On the second day,We retested the tests on , and the result showed that out of 30 tests, 22 passed, and 8 failed.
  ![Daily report]
- On the third day,We retested the tests on 23. 05, 2024, and the result showed that out of 30 tests, 26 passed, and 4 failed.
  ![Daily report]
  

### 3.4 Traceability Matrix
  
  ! Traceability Matrix
- Regular updates to the [Traceability matrix]help maintain transparency and alignment between testing and project objectives throughout the test life cycle.
- The matrix indicates the current status of each test case, helping to monitor the testing process and identify any gaps or missing coverage
- The matrix can be used for compliance purposes and to demonstrate that all requirements have been adequately tested and verified

### 3.5 Test Cases Result

- Test Cases and Results for the G,
   you will find a list of all the test cases result created, along with their results, for the Guru99 application. These test cases cover various aspects of the project and are used to assess its correctness and performance for the functionalities: "delete customer," "New customer," and "edit customer.".

### 3.6 Bugs Report

- A total of 10 bugs were discovered, out of which 7 were resolved, and through retesting, it was confirmed that they have been fixed, leaving only 3 open bugs.
  Bugs 

### 3.7 Test Completion Report

- This is the for the Guru99 application. It provides a comprehensive overview of the testing process, including test cases, their execution status, and any associated observations or issues encountered during testing.

-**Test execution final report**:
 !


### 3.8 Schedule

- We have 10 days of testing.
- We have 30 test cases.
- We would need to run an ~ of 30 tests/day.

## Key Aspects of the Project

- Non-functional testing, such as stress or performance testing, was not included in this project.
- Test automation was not considered.
- No support was provided for mobile applications, focusing exclusively on testing web applications.
- Out of the 10 identified bugs:
 7 have been resolved and retested.
 3 bugs remain open.
 These open bugs do not seem to critically impact the production release and can be addressed later.

1. **Detailed Attention to Test Definition:**
   Paying detailed attention to the definition of tests is crucial for project success.

2. **Monitoring Testing Progress:**
   Periodic reporting is essential for monitoring testing progress.

3. **Adjusting the Test Plan:**
   Adjust the test plan based on collected metrics for better efficiency.

4. **Exploring Broader Coverage:**
   In future projects, explore broader coverage of non-functional tests.

5. **Adopting Agile Approach:**
   Consider adopting an agile approach for better adaptability to changes.

Testing was conducted comprehensively, with the majority of tests passing successfully. Ongoing monitoring, reporting, and improvement of testing processes are essential for ensuring a quality final product.






