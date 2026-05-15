## Business Scenario
Contoso HR onboards 30+ employees monthly. IT setup, equipment issue and access provisioning are all tracked in spreadsheets. Tasks fall through the cracks and new starters arrive without access.

## Business Problem
- Manual onboarding leading to delays, inaccurate access and general poor onboarding processing. 









## Roles in the Solution
HR Officers

HR Heads

Admin Manager

IT Professional

Managers

## Business Requirement
Onboarding Process to be automated from end to end.

Dashboard that allows HR Monitor and Manage onboarding process from stage to stage and also managers (to know when new employee is due for his first task)

Ability for HR to set and adjust Grade Levels and corresponding remuneration as part of data to sent to the finance department. 

Task to be monitored for all staff and completion rate

Approval system for HR Head 

On Approval, notification to sent to Admin Manager, Manager, Finance Department.

On acceptance by Admin Manager, notification and data of new staff is sent to IT Administrators and as well required access (and in the required level)

## Tables
Onboarding Table

Staff Table (Azure Active Directory)

Equipment Table

Equipment Assignment Table

Managers Table

## Columns

### Onboarding Request

OnboardingDate

EnroleeID

First Name

Middle Name

Last Name

Gender

Employment Type

Department ID

Grade Level

Proposed Salary

### Staff 

StaffID

First Name

Middle Name

LastName

DepartmentID

DateofEmployment

EmploymentType

### Assignment

AssignmentDate

AssignmentID

EquipmentID

StaffID

Expected Return/Change Date

### Managers

ManagersID

First Name

LastName

DepartmentID

### Equipment

Equipment id

equipment name

Brand name

Model 

Date Purchased

Serial No

### Department 

Department_id

Department



## ERD DIAGRAM

![image alt](https://github.com/gitemy/Platform-Explorers/blob/master/%20Employee%20Onboarding/Employee%20Enrollment.png)