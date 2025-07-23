#  SauceDemo Login Test Automation using Testim AI

##  Project Overview:
This project tests the **Login functionality** of [SauceDemo](https://www.saucedemo.com) using the **Testim AI tool**. It is a codeless test automation created by recording user actions and verifying UI elements with assertions.

---

##  Tool Used:
-  [Testim AI](https://app.testim.io)
-  Browser: Google Chrome with Testim Extension
-  Platform: Web-based UI testing
-  Test Exported As: JavaScript (Optional)

---

##  Application Under Test (AUT):
- **Website URL:** https://www.saucedemo.com

###  Test Credentials:
- Username: `standard_user`
- Password: `secret_sauce`

---

## Test Scenario: Valid Login Functionality

###  Test Steps:
1. Launch `https://www.saucedemo.com`
2. Enter valid username and password
3. Click on the **Login** button
4. Verify that user is redirected to the **Products** page

---

##  Test Details (Testim Steps):
- Step 1: Open browser and navigate to the website
- Step 2: Locate and fill in login fields
- Step 3: Click on login
- Step 4: Add assertion to verify element like `.inventory_list` is visible
- Step 5: Save test and run

---

##  Screenshot:
![Testim Test Screenshot](testim_result_screenshot.png)


