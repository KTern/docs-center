---
title: "Business Function Analysis"
date: 2024-01-28T11:02:05+06:00
lastmod: 2024-01-28T11:02:05+06:00
weight: 23
draft: false
# search related keywords
keywords: ["induct", "instate"]
---
<div style='text-align: justify;'>

## Business Function Analysis

![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/34_launch_business_function_analysis_process_assessment_digital_maps.png)


SAP provides new features and enhancements for the existing SAP installations in self-contained units called business functions. You can use them for your various business processes. You can either switch on or switch off a business function. However, you cannot undo the activation of a business function.

For example, consider a certain business function to be part of an enhancement package. That business function can enable you to run your business better, but you don’t want to use all the functions of that enhancement package. Hence, you should install only the technical components required for that business function. After installation, you should activate only that particular business function.
 
![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/35_business_function_analysis_process_assessment_digital_maps.png)
 
![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/36_table_business_function_analysis_process_assessment_digital_maps.png)
 
![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/37_business_function_state_process_assessment_digital_maps.png)

KTern automates the process of analyzing business functions. After connecting the system, KTern runs the business functions analytics check and automatically classifies the installed business functions into active and inactive business functions. KTern also classifies the business functions into the following types:

**Enterprise Extensions:** These are the type of business functions which activate industry-independent and industry-specific applications and business processes.

**Enterprise Business Functions:** They can activate special features in SAP S/4HANA. They contain both industry-specific and industry-independent enterprise business functions.

**Industry Business Functions:** They contain functions specific to a particular industry and are part of the industry business function sets.

If one of your critical add-ons is not compatible with S/4HANA, then your entire business could be at risk. In such cases, you will have to wait for SAP’s roadmap to make that particular add-on compatible with S/4HANA. Only then, you can plan your transition from ECC to S/4HANA.

Before migrating to SAP S/4HANA, it is mandatory to assess the existing ECC landscape including your business processes, business functions, custom codes, architecture, and user interface. This enables you to take a data-driven approach to S/4HANA. KTern’s Business Function Analytics feature analyzes all the business functions installed in an ECC system in the Discover phase itself. It then classifies them into active and inactive business functions. The main objective of this feature is to analyze the impact of migrating these active business functions to S/4HANA. If any critical active business function is not compatible with S/4HANA, then you cannot migrate to S/4HANA. Business Function Analytics is part of the Impact Analysis module of KTern.

![](https://storage.googleapis.com/ktern-docs-files/bpa-12.png)

**Enterprise Extensions**
These are the type of business functions which activate industry-independent and industry-specific applications and business processes.

**Enterprise Business Functions**
They can activate special features in SAP S/4HANA. They contain both industry-specific and industry-independent enterprise business functions.

**Industry Business Functions**
They contain functions specific to a particular industry and are part of the industry business function sets.

After classifying the business functions into the above classifications, KTern also analyzes whether the business functions are compatible with S/4HANA or not. In addition, you can also sort and search the business functions according to the status, compatibility and types of business functions.

![](https://storage.googleapis.com/ktern-docs-files/bpa-13.jpg)

A business function in SAP ECC can have only two states, Active (ON) and Inactive (OFF). However, a business function usually has one of the following three states in S/4HANA:

1. Always ON
2. Always OFF
3. Customer Switchable

![](https://storage.googleapis.com/ktern-docs-files/bpa-14.png)

The above table indicates the various permutations and combinations with respect to the status of each business function. The following inferences can be made from the above table:

1. If a business function is switched on in your SAP ECC landscape, but the corresponding S/4HANA state is always OFF, then you cannot go for conversion. You will have to wait until SAP makes the business function compatible with S/4HANA or release a patch or have a look at the roadmap and then plan the transition.

2. If a business function is switched off in the ECC system, but the corresponding S/4HANA is always ON, then the conversion is possible and the business function will be switched on after the transition. You will have to assess the implications of such a business function being switched on in S/4HANA.

3. If the business function state in S/4HANA is customer switchable, then the conversion is possible and the state of the business function remains the same as before the transition, i.e these business functions keep their state after the conversion.

KTern makes this entire process simple by identifying the state of the business functions in SAP ECC and analyzing whether the functions are compatible with S/4HANA or not. With this information, the solution architects and the respective functional consultants can make the above inferences with ease.

</div>