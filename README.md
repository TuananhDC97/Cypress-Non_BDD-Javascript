# Project Name #

Study Project: Automation Testing with Cypress and JavaScript

# Author #

Le Tuan Anh

# Completion Period # 

June 2022 - September 2022

 # Description # 

This project is an automation testing suite built using Cypress and JavaScript to test the functionalities of DemoQA.com. It leverages the Page Object Model (POM) for efficient test organization and maintainability.

 # Technologies Used # 

Cypress: Modern JavaScript-based testing framework
JavaScript: Programming language for building test scripts
Page Object Model (POM): Design pattern for structuring test code

 # Scope # 

The project focuses on automated testing of both UI (User Interface) elements and API endpoints of DemoQA.com. This allows for comprehensive validation of the application's behavior.

 # Getting Started # 

**1. Prerequisites:**  Ensure you have Node.js and npm (Node Package Manager) installed on your system. You can download them from the official Node.js website (https://nodejs.org/en).

**2. Clone the Repository:** Use Git to clone this repository locally:

`git clone https://github.com/TuananhDC97/Cypress-Non_BDD-Javascript.git`

**3. Install Dependencies:** Navigate to the project directory and run the following command to install the required dependencies:

`npm install`

# Running the Tests #

**1. Start Cypress Test Runner:** Execute the command:

`npx cypress open`

This will launch the Cypress test runner in your web browser, allowing you to visualize and interact with the tests.

**2. Run Specific Tests:** 
You can also run individual test files or groups of tests using the appropriate Cypress commands (https://docs.cypress.io/guides/guides/command-line).

**3. Folder Structure**

cypress/: Contains Cypress test files and related configuration (modify as needed).

integration/: Houses the integration test scripts.

Your test files following the POM structure (e.g., login.spec.js, api.spec.js).

fixtures/: Stores any test data or fixtures required by your tests.

plugins/: Holds custom Cypress plugins (optional).

support/: Includes utility functions or other support code for tests.

package.json: Lists project dependencies, scripts, and other configurations.

**Page Object Model (POM)**

This project adheres to the POM for improved organization and maintainability. Test code interacts with page objects representing specific UI components for better separation of concerns. Refer to the cypress/integration directory for examples of POM implementation.

**Testing APIs**

The project demonstrates testing DemoQA.com's API endpoints using Cypress capabilities (refer to relevant test files).

**Further Enhancements**

This README.md file provides a basic guide to get you started with the project. Feel free to customize and adapt it further based on your specific project structure and testing needs.
