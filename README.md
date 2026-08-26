# OrangeHRM Manual Testing Project

A structured manual testing project performed on the OrangeHRM web application to validate key user workflows, functional behavior, input validation, boundary conditions, and access control within the defined testing scope.

The project follows a practical QA workflow:

**Requirement Analysis → Test Scenario Design → Test Case Design → Test Execution → Test Evidence → Test Closure**

---

## 📌 Project Overview

The objective of this project was to verify the functional behavior of the OrangeHRM web application across selected user workflows.

Testing focused on:

- Login and Logout
- Admin – User Management
- PIM – Employee Management
- Leave Management
- Input Validation
- Boundary Value Analysis
- Role-Based Access Control
- Basic Security-Oriented Checks
- Functional Workflow Validation

---

## 🧪 Application Under Test

| Item | Details |
|---|---|
| Application | OrangeHRM |
| Application Type | Web Application |
| Testing Type | Manual Testing |
| Testing Approach | Functional Testing |
| Browser | Google Chrome |
| Operating System | Windows |
| Test Environment | Public OrangeHRM Demo Environment |

---

## 🎯 Testing Scope

The following modules and functionalities were covered:

### 🔐 Login & Logout

- Login with valid credentials
- Login validation with invalid credentials
- Required field validation
- Logout functionality

### 👤 Admin – User Management

- User management functionality
- User creation and validation
- User search/filter functionality
- User status and role-related checks

### 👨‍💼 PIM – Employee Management

- Employee management functionality
- Employee creation
- Employee information validation
- Employee search/filter functionality

### 🏖️ Leave Management

- Apply Leave
- My Leave
- Leave List
- Leave-related validations
- Required field validation

### 🔍 Validation & Boundary Testing

- Required field validation
- Invalid input validation
- Boundary value checks
- Input length validation
- Field-level validation behavior

### 🔐 Access Control

- Role-based access checks
- Admin and ESS user access validation
- Verification of access to authorized functionality
- Verification of restricted functionality

### 🛡️ Basic Security-Oriented Checks

- Basic input validation checks
- Access control checks
- Authentication-related validation

> Full security penetration testing was not performed as part of this project.

---

## 🧭 Test Approach

Testing was performed using a requirement-driven approach within the available public demo environment.

The test design included:

- Positive Testing
- Negative Testing
- Functional Testing
- Input Validation
- Boundary Value Analysis
- Role-Based Access Control Testing
- Basic Security-Oriented Checks
- End-to-End Workflow Validation

---

## 🔍 Testing Activities

The following testing activities were performed:

1. Requirement Analysis
2. Test Scenario Design
3. Test Case Preparation
4. Positive Testing
5. Negative Testing
6. Input Validation Testing
7. Boundary Value Testing
8. Access Control Testing
9. Basic Security-Oriented Checks
10. Test Execution
11. Test Evidence Collection
12. Test Result Documentation
13. Test Closure

---

## 📊 Test Execution Summary

| Metric | Result |
|---|---:|
| Total Test Cases | 28 |
| Passed | 28 |
| Failed | 0 |
| Blocked | 0 |
| Confirmed Defects | 0 |
| Pass Percentage | 100% |
| Overall Result | PASS |

All 28 planned test cases were executed successfully within the defined testing scope.

No confirmed defects were identified during the final test execution cycle.

> **Note:** The 100% pass result applies only to the defined testing scope, test data, and available demo environment. It does not mean that the application is completely defect-free.

---

## 📝 Test Execution

Test cases were executed against the OrangeHRM application by following the documented test steps and comparing the actual application behavior with the expected results.

The execution results were recorded in the test execution summary.

Supporting screenshots were captured for selected test cases and stored in the `Test_Evidence` folder.

---

## 📸 Test Evidence

Test execution evidence is available in the `Test_Evidence/` folder.

The screenshots provide supporting evidence for selected test cases and demonstrate the observed application behavior during test execution.

> **Note:** OrangeHRM was tested using a shared public demo environment. Test data created during execution may be modified or removed later by other users.

---

## 📁 Project Artifacts

| File / Folder | Description |
|---|---|
| `01.OrangeHRM__Requirements.xlsx` | Documented requirements and requirement analysis |
| `02.OrangeHRM__Test_Scenarios.xlsx` | Test scenarios derived from the requirements |
| `03.OrangeHRM_Test_Case.xlsx` | Detailed manual test cases with steps and expected results |
| `04.OrangeHRM__Test_Execution_Summary.xlsx` | Test execution results and summary |
| `05.OrangeHRM_Test_Closure_Report.xlsx` | Test closure summary and conclusion |
| `Test_Evidence/` | Screenshots captured during test execution |

---

## ⚠️ Testing Limitations

Testing was limited to the defined functional scope, selected modules, available test data, and the public OrangeHRM demo environment.

The following areas were not covered in this testing cycle:

- Performance Testing
- Load Testing
- Stress Testing
- Full Cross-Browser Testing
- Full Security Penetration Testing
- API Testing
- Database Testing
- Mobile Application Testing
- Comprehensive Accessibility Testing

Therefore, the test results represent the behavior observed within the defined scope and test environment.

---

## 🏁 Test Closure

All planned test cases were executed successfully for the defined testing scope.

### Final Result

**28 Test Cases → 28 Passed → 0 Failed → 0 Blocked → 0 Confirmed Defects**

Testing was considered complete for this test cycle.

No confirmed defects were identified within the defined testing scope.

---

## 🛠️ Skills Demonstrated

- Manual Testing
- Functional Testing
- Requirement Analysis
- Test Scenario Design
- Test Case Design
- Positive Testing
- Negative Testing
- Input Validation
- Boundary Value Analysis
- Role-Based Access Control Testing
- Basic Security-Oriented Checks
- Test Execution
- Test Evidence Documentation
- Defect Analysis
- Test Documentation
- Microsoft Excel
- GitHub

---

## 📂 Project Structure

```text
orangehrm-manual-testing/
│
├── 01.OrangeHRM__Requirements.xlsx
├── 02.OrangeHRM__Test_Scenarios.xlsx
├── 03.OrangeHRM_Test_Case.xlsx
├── 04.OrangeHRM__Test_Execution_Summary.xlsx
├── 05.OrangeHRM_Test_Closure_Report.xlsx
│
├── Test_Evidence/
│   ├── screenshot files
│   └── ...
│
└── README.md
