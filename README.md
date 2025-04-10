
# Summary
---
Complete the following three QA Tasks about creating test cases, test plans, executing test plans and bug reporting. 
Tasks 1 and 2 focus on a fictional Timeclock application, designed for restaurant employees to clock in and out of their work shifts.

#### Submission Instructions:
Submit your completed work to the recruiter you are working with. You may do so by:
- Sharing links to a public GitHub or GitLab repository, or
- Sending your files as attachments in a standard format (e.g., PDF, Excel, or Word).

## 1. User Story Test Plan Task
---
- Write a Test Plan that for the below user story, detailing the objectives, scope, and testing methods.
- Additionally, write test cases based on the provided acceptance criteria. Your test cases should cover a variety of test scenarios.
#### Evaluation Criteria:
- **Test Plan Quality**: Clarity, structure, and completeness of the test plan.
- **Test Case Quality**: Thoroughness, coverage of different scenarios, and clarity in the test steps and expected results.
- **Problem-Solving Skills**: The ability to identify edge cases and effectively test complex scenarios.
- **Documentation**: How clearly and comprehensively you communicate your testing approach.

#### User Story:
**As a** restaurant employee,   
**I want to** select my name or enter it if it's not already in the system,   
**so that** I can identify myself in the timeclock system and track my working hours.

**As a** restaurant employee,   
**I want to** choose my job from a list of roles,   
**so that** the system knows which role I am working in and can associate the correct data.

**As a** restaurant employee,   
**I want to** be able to clock in when I start working and clock out when I finish,   
**so that** my working hours are accurately tracked.

**As a** restaurant employee,   
**I want to** see a graph below with my clock-in and clock-out times,   
**so that** I can easily track the time I've worked.

#### Acceptance Criteria:
1. **Given** the user opens the timeclock app  
    **When** they are prompted to select their name,  
    **Then** they should see a list of existing names.  
    **When** the user does not see their name in the list,  
    **Then** they should be able to manually input their name.

2. **Given** the user has selected or entered their name  
    **Then** they should see a list of available roles and be able to select one.

3. **Given** the user has selected their job role  
    **When** they need to log their time,  
    **Then** they should be able to choose the time for their action.

4. **Given** the user is not currently clocked in  
    **When** they view the action button,  
    **Then** the text should display "Clock In".

5. **Given** the user is already clocked in  
    **When** they view the action button,  
    **Then** the text should display "Clock Out".

6. **Given** the user has clocked in or out  
    **When** they look at the graph below,  
    **Then** their name should appear along with a visual representation of their clock-in and clock-out times.


![](file:///C:/Users/BOBSTA~1/AppData/Local/Temp/msohtmlclip1/01/clip_image002.jpg)


## 2. Task Plan Execution and Bug Report Task
---
The user stories in the previous task have been implemented at: https://restaurant365.github.io/challenge-timeclock

Using the test plan created in Task 1, execute the tests against the application. Validate the functionality as per the user story’s acceptance criteria.

During your testing, if you encounter any issues or bugs, document them as bug reports.

Please ensure the following are included as a part of your results:
- A list of test cases you executed, including the results (pass/fail).
- Bug reports for any issues found, as outlined above.
- A summary of your testing experience, including challenges faced and any insights or recommendations.

#### Evaluation Criteria:
- **Test Coverage**: How thoroughly you’ve tested the application according to the user story and acceptance criteria.
- **Bug Reporting**: The clarity, detail, and quality of your bug reports.
- **Test Execution**: Your ability to follow the test plan and track test results.
- **Problem-Solving and Critical Thinking**: How you handled edge cases, negative testing, and any unusual situations.
- **Documentation**: The organization and clarity of your test cases, bug reports, and summary.



## 3. API Testing Task
---
- Choose any API listed on https://www.freepublicapis.com/
- Identify and write test cases for the selected API. The test cases should cover a variety of scenarios.

Optional Stretch Goal
- Automation: Implement basic test automation for at least one of your test cases using a programming language, testing framework or tool you are comfortable with. 

#### Evaluation Criteria:
- **Test Case Quality**: How well the test cases cover a wide range of scenarios and their clarity.
- **Attention to Detail**: Thoroughness in defining test conditions, data, and expected outcomes.
- **Problem-Solving Skills**: Your ability to identify and address potential issues with the API.
- **Documentation**: How well you communicate your process, assumptions, and challenges.
- **Automation** (optional): The quality and maintainability of the automated tests.