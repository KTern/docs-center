---
title: "How to create and govern Test Scripts?"
date: 2021-01-15T11:02:05+06:00
lastmod: 2021-01-15T11:02:05+06:00
weight: 10
draft: false
# search related keywords
keywords: ["induct", "instate"]
---

Test scripts play a crucial role in the quality assurance process by defining a set of instructions for testing software applications. 

## Accessing the Test Cockpit 

To get started with creating and governing test scripts, follow these steps:
1.	Navigate to Digital Labs.

![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Labs/1_Click_DigitalLabs.png)

2.	Access the Test Cockpit.

![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Labs/2_Click_Testcockpit.png)

Upon entering the Test Cockpit, you will find a catalog of test suits and their components, including test plans, test scenarios, and test cases.

![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Labs/3_Testsuit.png)

## Creating a Test Script 

Follow these steps to create a new test script:

1.	In the Test Cockpit, expand the relevant test plan, test scenario, and test case that you want to associate the test script with.

2.	Launch the desired test case.

![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Labs/4_ExpandTestsuit.png)

You will be redirected to the Test Case Wizard page.

3.	Click on the “Test Labs” tab, where you will see a list of test scripts along with their corresponding test steps.

![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Labs/5_TestLabs.png)

4.	To create a new test script, click on “Add new Test Lab Item” and select “Test Script.”

5.	A side panel will open with fields to create the test script. Fill in the following details:
<ul>
  <li>Test Script Title</li>
  <li>Planned Test Environment</li>
  <li>Test steps (including Step Title, Step Action, Step Value, Instruction, Executed result)</li>
  <li>Use the “Add new step” button to add multiple steps.</li>
</ul>

6.	Once you’ve filled in the necessary information, click “Submit” to create your test script.

![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Labs/7_TestscriptSubmit.png)

## Editing an Existing Test Script 
To make changes to an existing test script, follow these steps:
1.	Access the Test Cockpit and navigate to the test script you want to edit.

2.	Select the test script.

3.	Use the “Edit” option to modify the test script details as needed.

![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Labs/8_EditTestScript.png)

## Governing Test Scripts 
Governing test scripts includes tracking their execution and outcomes. To do this, create corresponding test logs.
### Creating Test Logs 
To create test logs for a test script, follow these steps:

1.	Click on “Add new Test Lab Item” and choose “Test Execution Logs.”

![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Labs/9_SelectTestLog.png)

2.	A side panel will open with fields to create test logs for the script. Fill in the following details:

<ul>
  <li>Actual Environment</li>
  <li>Execution Title</li>
  <li>Test Script (the one you are creating the log for)
</li>
</ul>

3.	Once you’ve added the test script, fields for test step outcomes will be visible (e.g., Passed, Failed, Untested). You can also add Actual Results and Expected Results.

4.	If there are any defects encountered during testing, use the “Add Defects” option to document them.

5.	Click “Add Execution” to create a test log for the test script. This action will also update the status of the test script based on the outcomes recorded.


![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Labs/10_CreateTestLog.png)

![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Labs/11_TestScriptStatusUpdate.png)

### Governing Test Logs 

Governing test logs involves reviewing and tracking the execution of test scripts. You can access and update test logs to monitor the progress of your testing efforts.

![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Labs/12_GovernTestLogs.png)


