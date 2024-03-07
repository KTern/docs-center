---
title: "Custom Objects Impact Analysis"
date: 2024-01-28T11:02:05+06:00
lastmod: 2024-03-07T11:02:05+06:00
weight: 35
draft: false
# search related keywords
keywords: ["induct", "instate"]
---
<div style='text-align: justify;'>

Using the custom code impact analysis feature of KTern in SAP S/4HANA assessment, you can assess and analyze the syntactical change impact of all the custom Z tables, Z programs, and Z objects. It is a pre-requisite to check the impact on the standard SAP code and the custom code before moving to S/4HANA. Without completing this step, you cannot proceed further in the system conversion process.

KTern automates the process of SAP custom code impact analysis. As a result, this section gives you an analytical view of the custom code present in an SAP ECC system. After connecting an ECC system, KTern runs the custom code impact analytics check and analyzes the custom programs and objects present in a system.

The key activities that can be performed using KTern with respect to the custom code are:

i. Identification of affected custom objects
ii. Scope definition of custom code migration
iii. Define which custom code needs to be taken to S/4HANA
iv. Define usage frequency
v. Custom code analysis parameters
vi. Syntactically incompatible change of existing functionality
vii. Functionality not available but functional equivalent available
viii. Functionality not available
ix. Change of existing functionality with a performance impact

You can also upload the custom objects by exporting from SCMON.

This helps in prioritizing the high impact code with a high frequency of usage. You can eliminate the low usage custom programs and objects after taking a call with the business stakeholders.

[comment]:![](https://storage.googleapis.com/ktern-docs-files/cc-2.png)

Based on the information provided by KTern, you can plan your SAP S/4HANA system conversion with confidence.

KTern’s AI-powered rule engine automatically calculates the impact score of a custom program based on its analysis parameters and the number of impact cases. For example, if the custom program has many impact cases and its equivalent functionality is not available in S/4HANA, then it is given a high impact score.

KTern also provides the roadmap and effort for the S/4HANA system conversion based on the results from the custom code impact analysis.

</div>