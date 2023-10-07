# Functional Testing Automater using Selenium

This repository consists of an automated test script for the SauceDemo website, utilizing Selenium and Python.
## Prerequisites

- Python 3.x installed
- Selenium WebDriver library installed
- Chrome WebDriver executable installed and in the system PATH
- Chrome compatible with Chrome WebDriver

## Setup

1. Clone the repository to your local machine.
2. Install the required dependencies by running the following command: (`pip install selenium`)



## Test Scenario

The test scenario performs the following steps:

1. Create a browser instance and set up the test environment.
2. Open the login page and verify the Swag Labs logo.
3. Login with valid credentials.
4. Open the menu to access the Logout button and verify its presence.
5. Verify that the inventory page is displayed.
6. Navigate to the product detail page and verify the product name.
7. Add the item to the cart and verify the "Remove" button.
8. Navigate to the shopping cart page and verify the item in the cart.
9. Continue with the checkout process and verify the checkout page.
10. Enter required shipping and payment information.
11. Proceed to the confirmation page and verify the item in the overview.
12. Logout from the website.
13. Tear down the test environment.

## Running the Test
 python saucedemo_test.py

- The test will be executed with the provided test data (username and password). If the test passes, the message "test passed" will be displayed.
