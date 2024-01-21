---
title: "UiPath - KTern.AI Integration Guide"
date: 2021-01-15T11:02:05+06:00
lastmod: 2021-01-15T11:02:05+06:00
weight: 2
draft: false
# search related keywords
keywords: ["induct", "instate"]
---


# UiPath Test Manager and KTern.AI

Have you ever wanted to test the testcases that only needs testing when you are preparing for a release ? Or may be you have found yourself testing all of your testcases (may be 1000 or 3000 or 10,000) for a single release cycle. Now you can test only what needs to be tested using _UiPath Integration Bot available in KTern_

Using this you will be able to :

1. Create Test Sets from the identified testcases from KTern.
2. Create Test Requirements from the identified testcases from KTern.

# Introduction

Before we move into the "How to", it is important to understand the terms in the current scenario. There can be 1000s of test cases available in a given environment, With constant change requests from the business, the number of transport requests going into the production system demands long, time consuming, redundant testing processes. KTern's Automated Enterprise Release Impact (AERI) will help identify the list of impacted processes for a given transport request which inturn can be autonomously tested using UiPath's Test Bots.

## Fits and Test Sets

Imagine a list of process that requires testing from KTern's AERI results, The Platform intelligently proposes the testcases for the identified processes with sampled test data. Had the testcases be maintained in UiPath's Test Manager, the platform can identify the testcases in UiPath that require testing. The Identified Test Cases appear as **Fits**. These Fits can inturn be created as [Test Sets](https://docs.UiPath.com/orchestrator/lang-ru/docs/test-sets) in UiPath for automated execution.

## Gaps and Test Requirements

There can be instances where the identified processes that require testing, may or may not have testcases maintained in UiPath. In these cases, The recommended testcases from KTern appear as **Gaps**. These Gaps can inturn be created as [Test Requirements](https://docs.UiPath.com/test-suite/docs/requirements)


# Generate App ID and App Secret

In the UiPath Cloud Portal, Go to Admin / External Applications.

1. Click on **Add Application**
   ![Add Application](https://storage.googleapis.com/ktern-public-files/product-documentation/aeri%201.1%20.png 'Add Application')
2. Fill in the required information : App Name, App Type [Confidential Application]
   ![Fill Required Fields](https://storage.googleapis.com/ktern-public-files/product-documentation/aeri%201.2.png 'Fill Required Fields')
3. Edit Resource and Scope
   ![Edit Resource and Scope](https://storage.googleapis.com/ktern-public-files/product-documentation/aeri%201.3.png 'Edit Resource and Scope')
4. **Resource** : TestManager
5. **Scopes** : 'TM.TestCases TM.Requirements TM.Projects TM.TestSets'
6. Maintain the redirect URL as https://cloud.UiPath.com/identity_/connect/token
   ![Add Redirect URL](https://storage.googleapis.com/ktern-public-files/product-documentation/aeri%201.4.png 'Add Redirect URL')
7. Click Add

The Created application contains **App ID** and **App Secret** need for the integration between KTern and UiPath

# Integrate UiPath and KTern

Now head to KTern.AI, Project Settings -> Integrations.

1. Select UiPath
2. Choose Scenario : Change Impact Analysis
3. Fill in the required fields
4. Paste the App ID and App Secret generated in the UiPath External Application
5. Choose the required UiPath Project
6. Complete the UiPath Integration.
