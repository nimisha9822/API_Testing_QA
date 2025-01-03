# API_Testing_QA

## Overview

The application under test is **QTrip**, a travel website.

During the course of this project:

- Designed and automated 4+ test cases following the Page Object Model (POM) design pattern using Page Factory, Selenium, and TestNG.
- Utilized Apache POI in each test to accept dynamic test data.
- Created a TestNG project for easily running automated test cases.
- Implemented the Singleton pattern for initializing WebDriver to make effective use of resources.
- Generated customized test reports for the TestNG project using Extent Reports.
- Executed manual End-to-End API testing for APIs of different web pages using Postman.
- Automated the API tests using Rest Assured Framework and Java.
- Integrated API tests along with UI Tests.
- Used XML configuration in TestNG to selectively run tests.

---

## Scope of Work

### Explore QTrip and Analyze APIs

1. Executed all the important user flows in QTrip manually to understand the application.
2. Analyzed the QTrip application and its API documentation.
3. Designed API tests for different functional modules of the application.
4. Executed manual API tests using Postman.

### Automate QTrip Test Cases with TestNG

1. Automated four different test cases to test the working of the QTrip Application.
2. Populated sheets for data-driven testing using Apache POI.
3. Grouped test cases into functional groups to execute the test cases in a custom sequence.

### Automate QTrip API Tests with Rest Assured and TestNG

1. Automated the API tests using the Rest Assured Framework.
2. Modified the structure of the project using TestNG.
3. Executed API tests along with UI tests.
4. Grouped test cases into functional groups to execute the API and UI tests seamlessly.

### Generate Customized Test Reports for TestNG Project

1. Enhanced built-in Selenium methods with added functionality.
2. Implemented wrapper methods for screenshots and retry mechanisms.
3. Generated customized test reports using Extent Reports.

---

## Skills Used

- **Page Object Model (POM)**: Designed maintainable and scalable test scripts.
- **Test Case Design**: Converted manual test cases into automation scripts.
- **API Testing**: Validated APIs manually using Postman and automated using Rest Assured.
- **Test Data Enumeration**: Used dynamic data for robust test coverage.
- **Java**: Primary language for test script implementation.
- **Selenium**: Automated the web-based testing of QTrip.
- **TestNG**: Framework used for grouping and running test cases.
- **XPath**: Used for locating elements dynamically.
- **Apache POI**: Handled data-driven testing.
- **Extent Reports**: Customized reporting for test case results.

---

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd QTrip_Automation
   ```

2. Install dependencies:
   - Ensure you have **Java JDK 11+** installed.
   - Install **Selenium WebDriver** and required browser drivers (e.g., ChromeDriver).
   
3. Configure `testng.xml`:
   - Define your test suite and include/exclude test cases as required.

4. Run the test cases:
   ```bash
   mvn test
   ```

---

## Features

- **Comprehensive Test Coverage**: Ensures all critical flows of QTrip are tested.
- **Dynamic Test Data**: Leverages Apache POI for flexible and dynamic testing.
- **Custom Reporting**: Uses Extent Reports for detailed and visually appealing test results.
- **Efficient Resource Management**: Implements Singleton pattern for WebDriver initialization.
- **API Integration**: Combines UI and API testing for comprehensive validation.
- **Error Handling**: Enhances Selenium methods with retry mechanisms and screenshot capabilities.

---


