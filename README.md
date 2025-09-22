**EdTech Platform Web Application - Guvi**

**Title**

Automated Testing of the Web Application https://www.guvi.in

**Test Objective**

The objective of this project is to automate the testing of web application https://www.guvi.in by simulating user actions and 
validating key UI functionalities. This includes verifying page behaviour, accessibility of critical elements, navigation flows, and login functionalities.

**Test Scenario**

Test Case 1 - Verify whether the URL https://www.guvi.in is valid or not.

Test Case 2 - Verify whether the title of the webpage is correct.

Test Case 3 - Verify visibility and clickability of the Login button.

Test Case 4 - Verify visibility and clickability of the Sign-Up button.

Test Case 5-  Verify navigation to the Sign-In page via the Sign-Up button.

Test Case 6-  Verify login functionality with valid credentials.

Test Case 7-  Verify login with invalid credentials. 

Test Case 8-  Verify that menu items like “Courses”, “LIVE Classes”, and “Practice” are displayed.

Test Case 9- Validate that the Dobby Guvi Assistant is present on the page.

Test Case 10 - Validate logout functionality.

**Project Overview**

This project is a test automation suite for an EdTech platform, developed using pytest and Selenium. 
The main objective is to automate functional testing for various critical flows in an Edtech platform, 
such as registering new user, login , accessibility of menu items like Courses, Practices & Live Classes 
and Logout. By using pytest and Selenium, the test suite validates that application operates as intended 
and provides seamless experience for users.

**Table of Contents**
•	Features
•	Tech Stack
•	Setup and Installation
•	Running Tests
•	Project Structure

**Features**

•	Automation POM Framework: Home Page, Sign in, Register and Dashboard Page are automated and reusable design

•	Cross Browser Validation: It supports Chrome , Firefox, Edge and Safari

•	Config driven Approach : Used 'config.ini' for browser settings and Credentials

•	Logging and Reporting Support: We can get test result in HTML format and test_logs file is also generated

**Tech Stack**

•	Programming Language : Python

•	Test Framework : pytest

•	Automation Tool : Selenium Web Driver

•	Reporting : pytest-html, test_log

•	Browser Compatibility: Chrome, Firefox, Edge and Safari

•	CI/CD Integration : GitHub Actions

**Setup and Installation**

To set up and run this project locally, follow these steps:

**Clone the Repository:**

**1.	Clone the Repository**

  	 git clone https://github.com/username/Project1_Guvi_Application.git cd Project1_Guvi_Application
  
**2. Create a Virtual Environment(optional but recommended)**

   python3 -m venv env source env/bin/activate # Linux/Mac env\Scripts\activate # Windows
   
**3. Install Dependencies:**
   
   pip install -r requirements.txt
   
**4.	Set Up Environment Variables:**
    
    Create a .env file in the root directory to store sensitive information such as login credentials and URLs. Example:
    BASE_URL=https://example.com
    USER_EMAIL=test@example.com
    USER_PASSWORD=yourpassword


**Running Tests**

To execute tests, use the following commands:

1.	Run All Tests:

pytest

2.	Generate HTML Report:

pytest --html=report.html

3.	Run Tests by Marker (e.g., only "login" tests):

pytest -m login

4.	Headless Browser Execution:

You can set up tests to run in headless mode by configuring the config.ini file or directly in your test script.

**Project Structure**  


<img width="940" height="566" alt="image" src="https://github.com/user-attachments/assets/ceff81b6-b368-411b-b87d-400ed7d835fa" />

 

