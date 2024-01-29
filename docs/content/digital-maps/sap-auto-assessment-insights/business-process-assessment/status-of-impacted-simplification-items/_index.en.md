---
title: "Status of Impacted Simplification Items"
date: 2024-01-28T11:02:05+06:00
lastmod: 2024-01-28T11:02:05+06:00
weight: 22
draft: false
# search related keywords
keywords: ["induct", "instate"]
---
<div style='text-align: justify;'>


## Simplification Item Check

The Simplification List describes the potential adaptation work that is required to convert your SAP ERP system to SAP S/4HANA at a functional level. Simplification list items (for short, Simplification Items) illustrate the business adaptation requirements and effects to custom developments for each function described. For more complex modifications, the Simplification Items provide the relevant guides to support your transformation.

![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/30_launch_status_of_impacted_simplification_items_process_assessment_digital_maps.png)
 
![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/31_status_of_impacted_simplification_items_process_assessment_digital_maps.png)
 
![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/32_table_status_of_impacted_simplification_items_process_assessment_digital_maps.png)
 
![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/33_table_status_of_impacted_simplification_items_process_assessment_digital_maps.png)

The Simplification Item list is an essential early-stage tool used for planning an SAP S/4HANA Conversion project. Many necessary adaptations can be implemented on the existing SAP ERP source system itself. As a result, you will be able to begin an SAP S/4HANA Conversion Project even before installing the software in the first place. Consequently, the Simplification Item List is an essential source of information to organize crucial project tasks and assign the required resources.


### Components present in Simplification Item

A Simplification Item consists of the following elements:

1. **Business Impact Note**
   The Business Impact Note describes how that particular Simplification Item impacts the system as well as the business processes.
2. **Source Release and Target Release**
   The source and target release outline the basic relevant information; For instance, an item is said to be relevant if the customer comes from the source release and goes to the target release maintained in that Simplification Item.
3. **Check**
   Checks in a Simplification Item provides more relevant information like table checks for certain content, activated business functions etc. In addition, if a Simplification Item is relevant, you can also check the consistency. In other words, the check analyzes the prerequisite conditions in the system.

Typically, each Simplification Item consists of an SAP OSS Note. The OSS Note has the description and details on how to run that Simplification Item. You have to install the OSS Note into the system and run the Simplification Items Check. However, with KTern, you can automate the process of Simplification Item Check and it provides a comprehensive overview of all the relevant simplifications for SAP S/4HANA – that is, all mandatory solution adjustments in a system conversion project.

KTern covers the Simplification Item check in its Impact Analysis module. It is one of the preliminary and vital steps in a system conversion project and comes in the Discover phase itself. The Simplification Item check covers the relevancy of the Simplification Items in the target SAP S/4HANA system. This analysis, combined with the productivity and collaboration features of KTern such as forum, discussions and stakeholder management, forms a potent formula to get started with the SAP S/4HANA system conversion.

The forum provides a platform within KTern to collaborate, announce and have discussions regarding the simplification items and also assign them to the respective stakeholders. In addition, you can also upload files and track the work item hierarchy within KTern itself. Several useful Simplification Item links and references are also provided as part of the Knowledge Base called “S/4HANAPEDIA” within KTern.

KTern's Simplification Item check calculates the total number of Simplification Items in a system. It then classifies them into impacted and non-impacted Simplification Items. KTern also provides the status of each Simplification Item with SAP Note references. It also specifies why a particular Simplification Item is relevant or not relevant to your business.

![](https://storage.googleapis.com/ktern-docs-files/bpa-11.png)

Further, the impacted simplification items are classified based on the status as follows:

**Change of existing functionality**
Simplification items in this category refer to functions that are generally available in some form in SAP S/4HANA but have been adapted in such a way that might affect existing processes and custom programs.

**Functionality unavailable (equivalent exists)**
Simplification items in this category refer to functions that are not available in SAP S/4HANA. However, the equivalent functionality is available in SAP S/4HANA.

**Functionality unavailable (no equivalent)**
Simplification items in this category refer to functions that are not available in SAP S/4HANA. And, there is no equivalent functionality available. If you think that such impacted items are critical to your business, then it makes sense to wait until SAP releases that functionality and then make the move to S/4HANA.

**Non-Strategic Functions (equivalent exists)**
SAP has identified many of the existing core ECC modules/sub-modules/functionalities as "non-strategic" in S/4HANA. If current ECC-users or new businesses require these functionalities which are part of a "non-strategic module/functions" then they have to adopt the "strategic solution" as per S/4HANA roadmap. These "strategic-solutions" may or may not have its equivalent in S/4HANA. Generally, the non-strategic functions with equivalents can be classified into: oNew S/4HANA solutions part of extended S/4HANA product or oIn some cases, existing SAP products which are being enhanced/built for S/4HANA.

**Non-Strategic Functions (no equivalent):**
The Simplification Items where these "strategic-solutions" have no equivalent in S/4HANA are classified into this category.