>   **SENG 637 - Software Testing, Reliability, and Quality**

# **Lab. Report #1 – Introduction to Testing and Defect Tracking** 

| Group: 27               |
| ----------------------- |
| Student 1 Walid Farhat  |
| Student 2 Raakin Bhatti |

# **Table of Contents**

- 1. [**Introduction**](#introduction) <br>
- 2. [**Testing**](#testing) <br>
- 3. [**High-level description of the exploratory testing plan**](#high-level-description-of-the-exploratory-testing-plan)<br>
- 4. [**Comparison of exploratory and manual functional testing**](#comparison-of-exploratory-and-manual-functional-testing)<br>
- 5. [**Notes and discussion of the peer reviews of defect reports**](#notes-and-discussion-of-the-peer-reviews-of-defect-reports)<br>
- 6. [**How the pair testing was managed and team work/effort was divided**](#how-the-pair-testing-was-managed-and-team-workeffort-was-divided)<br>
- 7. [**Difficulties encountered, challenges overcome, and lessons learned**](#difficulties-encountered-challenges-overcome-and-lessons-learned)<br>
- 8. [**Comments/feedback on the lab and lab document itself**](#commentsfeedback-on-the-lab-and-lab-document-itself)<br>


# **Introduction**

In this report, we document our comprehensive testing efforts for two versions (1.0 and 1.1) of an ATM System. 
Prior to this lab, our understanding of exploratory testing was centered around its flexibility and adaptability, 
allowing testers to uncover hidden defects by simulating real-world user behaviors without relying on pre-defined 
test cases. Manual functional testing, on the other hand, was perceived as a structured approach where predetermined 
test cases are executed to validate that the system behaves as expected based on specified requirements. This lab 
provided us with an opportunity to apply both methodologies practically, deepening our understanding of their 
strengths and limitations.

# **Testing**
## **Test Types**
In this lab, we applied several testing approaches to ensure comprehensive coverage of the ATM system functionalities:

Exploratory Testing:
This unscripted testing method allowed team members to freely interact with the system, uncovering unexpected issues through intuitive exploration. We focused on identifying edge cases, system vulnerabilities, and unusual user behaviors that could lead to errors.

Manual Functional Testing (MFT):
This structured approach involved executing predefined test cases based on specific system requirements. It helped verify that the ATM's core functions, such as cash withdrawal and PIN validation, performed as expected under various conditions.

Regression Testing:
After identifying and reporting defects, we conducted regression testing to confirm that the fixes implemented did not negatively affect other parts of the system. This ensured that the software remained stable even after changes were made.

## Scope of Testing
The testing scope focused on validating the core functionalities of the ATM system that are critical to both users and operators. 
We aimed to ensure that the system operated reliably under both typical and exceptional conditions.

**Features to Be Tested:**
Card and PIN Validation: Handling valid/invalid card-PIN combinations and card retention after multiple failed attempts.
Cash Withdrawals: Transactions with sufficient and insufficient funds, including boundary tests for withdrawal limits.
Deposits: Testing envelope deposits, timeout conditions, and error handling.
Fund Transfers: Ensuring accurate transfers between linked accounts.
Balance Inquiries: Displaying real-time balance information.
Error Handling: System responses to invalid inputs, failed transactions, and unexpected shutdowns.
Operator Controls: ATM start/stop operations and transaction log verification.

## Test Logitistics/Environment
The ATM system was tested by a group of 2 (Walid and Raakin) in a simulated environment designed to replicate 
real-world usage scenarios. All testing was conducted on personal laptops using a stable version of 
the ATM software (Version 1 and 1.1). We used Jira for defect tracking and maintained logs for all identified issues.


# **High-level description of the exploratory testing plan**

Our exploratory testing plan aims to identify defects that may not be uncovered through scripted tests. 
This approach enables testers to adapt dynamically, focusing on areas where potential issues are more likely 
to occur.

## Objectives

- Identify hidden defects that formal test cases might overlook.

- Simulate real-world usage scenarios.

- Adapt quickly to unexpected system behaviors.
 
## Approach 

- Familiarize with system requirements and functionalities.

- Develop a high-level test plan targeting critical functions.

- Focus on both common user paths and exceptional cases.

## Defect Reporting 

All identified defects are documented in Jira, including detailed summary, descriptions, 
expected vs. actual results, severity ratings, and associated tags for easy tracking.


# **Comparison of exploratory and manual functional testing**

## Manual Functional Testing 

Manual functional testing involves executing pre-defined test cases designed to verify specific system functionalities.

### Advantages:  

- Ensures comprehensive coverage of known scenarios.

- Provides a reliable benchmark for system performance.

- Offers detailed documentation for future reference.

### Limitations: 

- Time-consuming and labor-intensive.

- Limited in identifying unexpected issues outside predefined scenarios.

## Exploratory Testing 

Exploratory testing is a more flexible approach where testers actively learn and adapt during the testing process.

### Advantages: 

- Effective at discovering unexpected bugs and edge cases.

- Encourages creative problem-solving and in-depth analysis.

- Suitable for complex systems and early development phases.

### Limitations: 

- Potential gaps in coverage due to lack of structured test cases.

- Challenges in reproducing and documenting certain issues.


# **Notes and discussion of the peer reviews of defect reports**

During peer review sessions, we focused on:

Ensuring completeness of defect reports, with clear documentation of issues, reproduction steps.

Achieving consensus on severity ratings to maintain consistency in prioritization.

Standardizing tags to improve report readability and organization.

Reflecting on lessons learned to enhance future defect documentation practices.


# **How the pair testing was managed and team work/effort was divided** 

We adopted a pair testing approach to promote collaboration and ensure thorough coverage.
One member executed the tests while the other documented findings and analyzed results. 
The tasks were divided as follows:

System Startup:         Walid
System Shutdown:        Raakin
Session:                Walid
Transaction:            Raakin
Withdrawal:             Raakin
Deposit:                Walid
Transfer:               Raakin
Inquiry:                Raakin
Invalid PIN Extension:  Walid 


# **Difficulties encountered, challenges overcome, and lessons learned**

## Difficulties Encountered 

- Learning Curve with Jira: Initial struggles with navigating Jira 
impacted our efficiency.

- Task Allocation Challenges: Distributing tasks effectively among team members was 
challenging, affecting productivity.

## Challenges Overcome 

- Improved familiarity with Jira through hands-on practice.

- Enhanced team coordination by establishing clear roles and responsibilities.

## Lessons Learned 

- Early familiarization with tools improves efficiency.

- Effective communication and collaboration are key to successful testing.

- Regular peer reviews help maintain consistency and quality in defect reporting.


# **Comments/feedback on the lab and lab document itself**

This lab was an excellent learning experience, offering practical insights into software testing 
methodologies. The hands-on approach with exploratory and manual functional testing helped solidify 
our understanding. However, incorporating more practice sessions with tools like Jira
during lectures would be beneficial. The lab guidelines were clear, though some confusion existed
regarding the report format and the Test_Plan_Sample.pdf being restricted. Overall, the lab encouraged 
collaboration, critical thinking, and a comprehensive approach to defect management.