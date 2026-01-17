# PRODIGY_ST_05
Automatic Checkout Process on a e-commerce platform including adding items to cart, fill form for checkout , etc..
**Project Overview**

This project automates the complete checkout process of an e-commerce website using Selenium WebDriver with Python.
The automation covers user login, adding items to the cart, navigating through checkout pages, form validation, payment selection, and verification of the order success message.

**Demo Website Used:**
http://www.automationpractice.pl/index.php

**Objectives**

1.Automate the end-to-end checkout workflow

2.Verify page transitions during checkout

3.Validate mandatory checkout form fields

4.Confirm successful order placement

5.Capture screenshots as execution evidence

**Application Under Test (AUT)**
Parameter	                  Details
Application Name	          Automation Practice
URL	                        http://www.automationpractice.pl/index.php
Type	                      Web-based E-Commerce Application
**Test Scenarios Covered**
**Positive Scenarios**

1.User login with valid credentials

2.Product added to shopping cart

3.Successful navigation through checkout pages

4.Payment completed successfully

5.Order confirmation message verified

**Validation Scenarios**

1.Mandatory Terms & Conditions validation

2.Page transition verification at each checkout step

**Tools & Technologies**

Language: Python

Automation Tool: Selenium WebDriver

Browser: Google Chrome

IDE: Visual Studio Code

Version Control: Git & GitHub

**Prerequisites**
Ensure the following are installed:
Python 3.x
Google Chrome Browser
ChromeDriver (compatible with your Chrome version)
Selenium package
Install Selenium:
pip install selenium

**Project Structure**
PRODIGY_ST_05
│
├── Automatic_Checkout.py
├── Automatic_Checkout_Screenshots
│   ├── login_ss.png
│   ├── Address_ss.png
│   ├── checkout_ss.png
│   ├── item_ss.png
│   ├── moredetails_ss.png
│
│
└── Task5_Documentation
└── README.md

**How to Run the Automation Script**

1.Clone the repository:

2.git clone <repository-url>

3.Navigate to the project folder:

4.cd automationpractice-checkout-automation

Execute the script:

1.python checkout_test.py

Screenshots & Evidence

Screenshots are automatically captured at critical stages:

1.Login success

2.Product added to cart

3.Address confirmation

4.Shipping validation

5.Payment selection

6.Order success confirmation

These screenshots provide visual proof of execution.

**Test Execution Result**
1.Step	Result
2.Login	Pass
3.Add to Cart	Pass
4.Checkout Navigation	Pass
5.Form Validation	Pass
6.Order Confirmation	Pass
**Issues Encountered**

*Dynamic elements required hover actions

*Page load delays handled using waits

*Mandatory checkbox validation added for shipping step

*All issues were resolved during automation.

**Conclusion**

The automation script successfully validated the entire checkout flow of the e-commerce application.
All checkout steps, validations, and the final order confirmation were executed and verified with screenshot evidence.

This project demonstrates real-world UI automation testing skills using Selenium.

👤 Author

Name: Lalitha B
