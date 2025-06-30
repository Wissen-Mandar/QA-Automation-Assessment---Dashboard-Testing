# QA Automation Assessment - Dashboard Testing

## Overview
This repository contains the QA automation assessment for Wissen. Candidates are required to fork this repository and implement automated test cases for an interactive dashboard application.

## Assessment Details

### Application Under Test
- **URL:** https://grand-bienenstitch-47218a.netlify.app/
- **Type:** Interactive Dashboard with Configurable Columns and Filtering
- **Duration:** 30-35 minutes

### Task Objective
Set up a test automation framework from scratch and write automated test cases for the dashboard's column configuration and filtering functionality.

## Requirements

### Part 1: Framework Setup (10-12 minutes)
- Set up a basic automation framework using your preferred technology stack
- Create a simple page object structure for the dashboard
- Configure browser/driver setup and basic utilities

### Part 2: Test Implementation (18-20 minutes)

#### Test Case 1: Column Configuration
**Scenario:** Verify column show/hide functionality
- Hide a column and verify it disappears from the table
- Show the column again and verify it reappears
- Validate table structure remains intact

#### Test Case 2: Data Filtering  
**Scenario:** Verify filtering functionality
- Apply a filter and verify only matching data is displayed
- Clear the filter and verify all data is restored
- Validate row count updates correctly

#### Test Case 3: Combined Operations
**Scenario:** Test column configuration with active filters
- Apply a filter, then hide/show columns
- Verify both functionalities work together correctly

### Part 3: Execution & Validation (5 minutes)
- Ensure tests run independently and clean up properly
- Add basic reporting/logging
- Verify all assertions are meaningful

## Expected Deliverables
1. Working automation framework with proper structure
2. Page object(s) for dashboard interactions
3. Three automated test cases covering core functionality
4. Ability to execute tests and view results

## Evaluation Criteria
- **Technical Implementation** (60%): Framework setup, code organization, element handling
- **Test Coverage** (30%): Test logic, assertions, scenario coverage  
- **Code Quality** (10%): Readability, maintainability, best practices

## Getting Started

### Prerequisites
- Ensure you have the necessary tools installed for your chosen automation framework
- Browser drivers (if using Selenium-based frameworks)
- Development environment setup

### Instructions
1. **Fork this repository** to your GitHub account
2. **Clone** your forked repository locally
3. **Explore** the application at the provided URL to understand its functionality
4. **Implement** your automation framework and test cases
5. **Commit** your changes with meaningful commit messages
6. **Push** your implementation to your forked repository
7. **Share** the repository link for evaluation

### Project Structure Suggestion
```
your-automation-project/
├── src/
│   ├── pages/
│   ├── tests/
│   └── utils/
├── config/
├── reports/
├── README.md (your implementation notes)
└── package.json / requirements.txt / pom.xml (as applicable)
```

## Submission Guidelines

### Required Files
- All source code files
- Configuration files
- Documentation/README explaining how to run your tests
- Any additional setup instructions

### Documentation Requirements
Please include in your implementation:
- Brief explanation of your chosen tech stack
- Instructions to run the tests
- Any assumptions made about the application
- Known limitations or areas for improvement

## Technical Notes
- Use any automation framework/language you're comfortable with
- Focus on creating a solid foundation rather than comprehensive coverage
- Inspect the application first to understand its behavior before writing tests
- Ensure your tests are reliable and can run consistently

## Questions?
If you have any questions about the assessment, please reach out to the Wissen team.

---

**Good luck with your assessment!**

*This assessment is designed to evaluate your practical automation skills and approach to testing web applications.*
