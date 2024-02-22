---
title: "UiPath - KTern.AI Integration Guide"
date: 2021-01-15T11:02:05+06:00
lastmod: 2024-01-22T11:02:05+06:00
weight: 3
draft: false
# search related keywords
keywords: ["induct", "instate"]
---
<div style='text-align: justify;'>

## About UiPath Test Manager and KTern.AI

Have you ever wanted to test only the test cases that are essential for a release, instead of testing all of them, which could number in the thousands? Now, with the UiPath Integration Bot available in KTern, you can achieve just that. Using this integration, you will be able to:

</br>1. Create Test Sets from the identified testcases in KTern.AI.

</br>2. Create Test Requirements from the identified testcases in KTern.AI.

## Introduction

Before we move into the "How to", it's important to understand the terms in the current scenario. In a given environment, there can be thousands of test cases. With constant change requests from the business, the number of transport requests going into the production system demands long, time-consuming, redundant testing processes. KTern's Automated Enterprise Release Impact (AERI) can help identify the list of impacted processes for a given transport request, which can then be autonomously tested using UiPath's Test Bots.

## Fits and Test Sets

Imagine a list of processes that require testing based on KTern's AERI results. The platform intelligently proposes the test cases for the identified processes with sampled test data. If these test cases are maintained in UiPath's Test Manager, the platform can identify the test cases in UiPath that require testing. The identified test cases appear as **Fits**. These Fits can, in turn, be created as **[Test Sets](https://docs.UiPath.com/orchestrator/lang-ru/docs/test-sets)** in UiPath for automated execution.

## Gaps and Test Requirements

There can be instances where the identified processes that require testing, may or may not have testcases maintained in UiPath. In these cases, the recommended testcases from KTern appear as **Gaps**. These Gaps can inturn be created as **[Test Requirements](https://docs.UiPath.com/test-suite/docs/requirements)**.

## Generate App ID and App Secret

In the UiPath Cloud Portal, go to Admin/External Applications.

</br>1. Click on the **Add Application** button.

   ![Add Application](https://storage.googleapis.com/ktern-public-files/product-documentation/aeri%201.1%20.png 'Add Application')

</br>2. Fill in the required information: App Name, App Type [Confidential Application].

   ![Fill Required Fields](https://storage.googleapis.com/ktern-public-files/product-documentation/aeri%201.2.png 'Fill Required Fields')

</br>3. Edit the Resource and Scope.

   ![Edit Resource and Scope](https://storage.googleapis.com/ktern-public-files/product-documentation/aeri%201.3.png 'Edit Resource and Scope')

</br>4. **Resource**: TestManager.

</br>5. **Scopes**: 'TM.TestCases TM.Requirements TM.Projects TM.TestSets'.

</br>6. Maintain the redirect URL as https://cloud.UiPath.com/identity_/connect/token.

   ![Add Redirect URL](https://storage.googleapis.com/ktern-public-files/product-documentation/aeri%201.4.png 'Add Redirect URL')

</br>7. Click the "Add" button.

</br>**Note:** The Created application contains the **App ID** and **App Secret** needed for the integration between KTern and UiPath.

## Steps to Integrate UiPath and KTern.AI

Now head to KTern.AI, Project Settings -> Integrations.

</br>1. Select the UiPath

</br>2. **Choose Scenario:** Change Impact Analysis.

</br>3. Fill in the required fields.

</br>4. Paste the App ID and App Secret generated in the UiPath External Application.

</br>5. Choose the required UiPath Project.

</br>6. Complete the UiPath Integration.

</div>