---
title: "Enterprise Mining Widgets"
date: 2024-01-28T11:02:05+06:00
lastmod: 2024-01-28T11:02:05+06:00
weight: 20
draft: false
# search related keywords
keywords: ["induct", "instate"]
---
<div style='text-align: justify;'>

</br>1. KTern.AI drills down the enterprise structure of each module or Line of Business in the existing system, aiding an organized S/4HANA migration. It helps in understanding the type and orientation of the SAP system and also to identify the most effectively used processes and organizational units.

</br>2. In most SAP S/4HANA assessments, as the first step, organizations aim to find out the enterprise structure in SAP and drill down the hierarchy of each functional module. They find out answers to questions like:
<ul>
</br>i. What is the type of the system? 
</br>ii. What is the orientation of the SAP system?
</br>iii. How and who uses the system? 
</br>iv. What is the most effectively used process? 
</br>v. How many company codes are there in the system? 
</br>vi. What are the most effectively used sales organizations / purchase organizations? And much more.
</ul>

</br>3. It drills down from company codes, sales organizations, distribution channels, plants and all the way up to the sales documents generated. 

</br>4. In this way, KTern provides a clear hierarchy and evidently maps the organizational structure. KTern performs the same for 
<ul>
</br>i. Purchase Documents
</br>ii. Order Documents
</br>iii. Sales Documents
</br>iv. Billing Documents and others as well based on the available data. 
</ul> 

### i. Enterprise Structure - Purchase Documents 
<ul>
<li>
The box displays the total count of Purchase Documents. 
</li></br>
<li>
Click on the launch icon (9) adjacent to Purchase Documents to explore a tree view showcasing the complete history of purchase documents.
</li></br>

![Launch - Purchase Documents](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/11_launch_purchase_documents_enterprise_mining_widgets_process_assessment_digital_maps.png)

<li>
By clicking on the node (10) corresponding to the company code, you can reveal the purchasing organization beneath it.
</li></br>

![Tree View - Purchase Documents](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/12_purchase_documents_enterprise_mining_widgets_process_assessment_digital_maps.png)

<li>
Upon further drilling down, the flow includes <b>Company code -> Purchasing Organization -> Purchasing Group -> Plant -> Storage Location -> Number of Purchase Documents created</b>.
</li></br>

![Tree View - Purchase Documents](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/13_purchase_documents_enterprise_mining_widgets_process_assessment_digital_maps.png)

<li>
Scrolling down, you'll encounter a table presenting information related to purchasing organization, purchasing group, plant, storage location, and the number of purchasing documents. You can refine the data based on specific requirements and use keyword searches.
</li></br>
 
![Table View - Purchase Documents](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/14_table_purchase_documents_enterprise_mining_widgets_process_assessment_digital_maps.png)

#### Enterprise Structure - Material Management:
<li>
Each module in SAP has its own enterprise structure. 
</li></br>
<li>
An Enterprise Structure in SAP is nothing but the framework or structure according to which the whole business runs. And every organization has or at least should have some structure. 
</li></br>
<li>
There are several organizational units within an enterprise structure. The Material Management (MM) module in SAP has the following organizational units:
</li>
<ul>
</br>a. Client
</br>b. Company Code
</br>c. Plant
</br>d. Storage Location
</br>e. Purchasing Organization
</br>f. Purchasing Group
</ul>
</ul>

<ul>

##### a. Client:
<ul>
<li>
From a business perspective, the client represents a corporate group. It is the highest hierarchical level in an SAP system. 
</li>
<li>
A client represents the highest node or hierarchy of an enterprise or organizational structure in SAP. Creation of a client in an SAP system is mandatory and a technical requirement. 
</li>
<li>
A client maintains several company codes within it. Data maintained at the client level is valid for all organizational levels.
</li>
</ul>

##### b. Company Code:
<ul>
<li>
A company code is created in the Finance (FI) module and it is linked to the Material Management (MM) module. 
</li>
<li>
The Company Code is an independent company. A company code, which is a legal entity and statutory requirement, maintains the balance sheets and P&L statements. In fact, the company code maintains all book of accounts.
</li>
</ul>

##### c. Plant:
<ul>
<li>
Plant in an SAP system is a broad term and has varying definitions in different modules.
</li>
<li>
In SAP Material Management (MM) module, a plant refers to a facility where the material stock is kept, stored and the inventory is maintained. 
</li>
<li>
Activities within a company take place within a plant. A plant has a manufacturing facility, warehouse distribution center and a regional sales office.
</li>
</ul>

##### d. Storage Location:
<ul>
<li>
Storage location is an organizational unit, which actually differentiates between different material stocks in a plant. 
</li>
<li>
A storage location maintains the stock physically. A plant can have several storage locations. 
</li>
<li>
There are several types of storage location such as raw material storage location, finished goods storage location, return sales storage location, spares storage location, temperature-controlled storage location etc.
</li>
</ul>

##### e. Purchasing Organization:
<ul>
<li>
A purchasing organization is an organizational unit with SAP Material Management (MM), and it is responsible for all the purchasing activities within a company. 
</li>
<li>
It handles all the procurement activities and documentations such as Request for Quotations (RFQs), contracts, Purchase Orders (Pos) etc. 
</li>
<li>
A purchasing organization carries out all the procurement activities on behalf of the company. There are several types of purchasing organizations:
</li>
</ul>
<ul>
</br>

<ul>

**e1. Centralized Purchasing**
   A purchasing organization at the client level is called as centralized purchasing. For example, if a company has only one procurement department and it carries out all the procurement activities, then a centralized purchasing organization is created.

**e2. Company specific Purchasing:**
   In this case, a purchasing organization is assigned only to one company code. Only the plants belonging to this company code can procure and purchase through this purchasing organization.

**e3. Plant specific Purchasing:**
   There are some cases where the size of the company is too large and having a centralized purchasing organization is not viable. Even company-specific purchasing organizations are too hard to handle. In such cases, each plant has a separate purchasing organization. These plant-specific purchasing organizations are responsible for the procurement of their own plant only.
</ul>
</ul>

##### f. Purchasing Group:
<ul>
<li>
A purchasing group are individuals or group of individuals who are responsible for carrying out the purchasing activities. 
</li>
<li>
In other words, they are responsible for the everyday procurement activities of the organization. They are usually for reporting and approval procedures. 
</li>
<li>
They handle the Purchase Requisitions (PR), Request for Quotations (RFQs), Purchase Orders (POs), Contracts etc.
</li>
<li>
The main purpose of Enterprise Structure Mining before moving S/4HANA is to find out the relevant and active company codes, purchasing organizations, purchasing groups and the other organizational units. 
</li>
<li>
Most of these enterprise purchase organizations would have been modelled long back and the documentation might not be available today. 
</li>
<li>
The organizational units might have gone through several changes since the last update. And the ageing workforce of SAP does not make the situation any better.
</li>
<li>
It is necessary to give proper training and handover to the millennial workforce. However, with the disparate information and inconsistent documentation, it is not always possible. 
</li>
<li>
KTern can help you here by continuous monitoring and providing materiality of where the consultants should focus. 
</li>
<li>
Mostly this information or knowledge is with a privileged few or in the System Integrator's privy. KTern helps you to unearth the enterprise procurement and purchase structure and provide the information in an easy-to-consume format.
</li>
<li>
The findings from this tool, KTern, will help you determine the most useful/most used organizational units. 
</li>
<li>
Such insights can help you re-engineer your business process. Therefore, business stakeholders will have better clarity and make data-driven decisions with confidence.
</li>
</ul>
</ul>

</br><li>
As seen in the above picture, KTern’s Enterprise Structure Mining feature drills down the various organizational units. 
</li></br>
<li>
It drills down from company codes, purchasing organizations, purchasing groups, plant, storage location and all the way up to the number of purchase documents created. 
</li></br>
<li>
In this way, KTern provides a clear hierarchy and evidently maps the organizational structure. The hierarchy of a purchase organization is as follows:
</li></br>

**Company Code -> Purchasing Organization -> Purchasing Groups -> Plant -> Storage Location -> No. of Purchase Documents Created**

<li>
The functional consultants manually doing this task will definitely not be able to provide such clarity and accuracy in mapping the org structure. 
</li></br>
<li>
They have to go through each table, record and t-code to get this information. And even then, they will not be able to get the total picture. 
</li></br>
<li>
It may take several weeks or even months to complete it. KTern automates the task and provides the results in a span of a few minutes.
</li></br>
<li>
Another important feature of KTern’s Enterprise Structure Mining is that you can sort and search the company codes, purchasing organizations, purchasing groups, plant, storage location, and the number of purchase documents. This enables you to determine the most active company codes, purchasing organizations and so on. 
</li></br>
<li>
For example, if only two purchase documents are generated for the past 5 years in one of the plants, then it can be inferred that that particular plant is not active. After taking a call with the business stakeholders, you need not move that particular plant to S/4HANA.
</li></br>
<li>
You can gain such insights only when you have such detailed hierarchy and organizational mapping as provided by KTern. 
</li></br>
<li>
Such observations from KTern helps the MM functional consultants, business stakeholders from both the System Integrator side and the customer side, and the Solution Architects to have a clear picture of the landscape and take better data-driven decisions.
</li></br>

### ii. Enterprise Structure - Order Documents

https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/15_launch_order_documents_enterprise_mining_widgets_process_assessment_digital_maps.png
 
https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/16_order_documents_enterprise_mining_widgets_process_assessment_digital_maps.png
 
https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/17_table_order_documents_enterprise_mining_widgets_process_assessment_digital_maps.png


### iii. Enterprise Structure - Sales Documents

KTern’s Enterprise Structure Mining – Sales documents feature drills down the various organizational units. Each module in SAP has its own enterprise structure. An Enterprise Structure in SAP is nothing but the framework or structure according to which the whole business runs. And every organization has or at least should have some structure. There are several organizational units within an enterprise structure.

An enterprise structure in SAP clearly defines the numerous levels in an organization. Each level has a distinct functionality associated with it, and the levels are categorized according to some hierarchy. The levels, when combined, describe the working of an organization. The Sales and Distribution module in SAP has the following organizational units:

1. Sales Organization
2. Distribution Channel
3. Sales Office
4. Division
5. Sales Group
6. Company Code (maintained by Finance module)
7. Plant (maintained by MM module)
8. Storage location (maintained by PM module)
9. Sales Area

![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/18_flowchart_sales_documents_enterprise_mining_widgets_process_assessment_digital_maps.png)
 
![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/19_launch_sales_documents_enterprise_mining_widgets_process_assessment_digital_maps.png)
 
![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/20_sales_documents_enterprise_mining_widgets_process_assessment_digital_maps.png)
 
![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/21_table_sales_documents_enterprise_mining_widgets_process_assessment_digital_maps.png)

![](https://storage.googleapis.com/ktern-docs-files/bpa-3.png)

Typically, in most S/4HANA assessments, as the first step, organizations aim to find out the enterprise structure in SAP and drill down the hierarchy of each functional module. They find out answers to questions like - What is the type of the system? What is the orientation of the SAP system? How and who uses the system? What is the most effectively used process? How many company codes are there in the system? What are the most effectively used sales organizations? And much more.

Finding out answers to these questions is a very manual task. Many functional consultants are deployed for this purpose. The functional consultants then go through each T-Code, Table and Report to map the hierarchy of the enterprise structure in SAP and find out the complexity of the system. Sounds tiring, right? But this step is mandatory and cannot be skipped. Only after this step, you can proceed with the next step in the system conversion process.

With KTern, you can automate and find out the entire enterprise structure in SAP with just the click of a button. You can find the answers to the above crucial questions easily. This feature is in the Discover phase of the Activate Methodology and is covered in the Impact Analysis module of KTern.

![](https://storage.googleapis.com/ktern-docs-files/bpa-4.png)

As seen in the above picture, KTern’s Enterprise Structure Mining feature drills down the various organizational units. It drills down from company codes, sales organizations, distribution channels, plants and all the way up to the sales documents generated. In this way, KTern provides a clear hierarchy and evidently maps the organizational structure. The hierarchy of a sales organization is as follows:

**Company Code -> Sales Organization -> Distribution Channel -> Division -> Plant -> Number of Sales Documents Generated**

The functional consultants manually doing this task will definitely not be able to provide such clarity and accuracy in mapping the org structure. They have to go through each table, record and t-code to get this information. And even then, they will not be able to get the total picture. And, let’s not talk about the time required to complete the task. It may take several weeks or even months to complete it. KTern automates the task and provides the results in a span of few minutes.

![](https://storage.googleapis.com/ktern-docs-files/bpa-5.png)

Another important feature of KTern’s Enterprise Structure Mining is that you can sort and search the company codes, sales organizations, distribution channels, divisions, plants and the number of sales documents. This enables you to determine the most active company codes, sales organizations and so on. For example, if only two sales documents are generated for the past 5 years in one of the plants, then it can be inferred that that particular plant is not active. After taking a call with the business stakeholders, you need not move that particular plant to S/4HANA. You can gain such insights only when you have such detailed hierarchy and organizational mapping as provided by KTern. Such observations from KTern helps the functional consultants, business stakeholders from both the System Integrator side and the customer side, and the Solution Architects to have a clear picture of the landscape and take better data-driven decisions.

KTern also provides the option of downloading this report. In addition, you can also post it in the forum, assign stakeholders and collaborate. You can upload the files in KTern and subsequently use it any other stage of the system conversion process. Thus, KTern provides a platform to join forces and work together in determining the relevant enterprise structures in SAP and plan the path to S/4HANA.

**iv. Enterprise Structure - Billing Documents**

<ul>
i. The box signifies the total count of Billing Documents. Click on the launch icon (13) near the Billing Documents to explore the list of company codes.

ii. Upon further drilling down, the flow includes:

Company code -> Currency (in USD) -> Created by user -> Delivery-related Billing Document

iii. Scrolling down, you'll encounter a table presenting information related to purchasing organization, purchasing group, plant, storage location, and the number of purchasing documents. You can refine the data based on specific requirements and use keyword searches.

![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/22_launch_billing_documents_enterprise_mining_widgets_process_assessment_digital_maps.png)
 
![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/23_billing_documents_enterprise_mining_widgets_process_assessment_digital_maps.png)
 
![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/24_billing_documents_enterprise_mining_widgets_process_assessment_digital_maps.png)
 
![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/25_table_billing_documents_enterprise_mining_widgets_process_assessment_digital_maps.png)

</br> 5. KTern also provides the option of downloading this report. In addition, you can also post it in the forum, assign stakeholders and collaborate. 

</br>6. You can upload the files in KTern and subsequently use it any other stage of the system conversion process. Thus, KTern provides a platform to join forces and work together in determining the relevant enterprise structures in SAP and plan the path to S/4HANA.

</br>7. One more important use case of this feature is that you that perform a pre-Go-Live check in a greenfield implementation. 

</br>8. In a greenfield implementation, the customer usually provides the configuration requirement. The System Integrator then maps the enterprise structure according to the configuration and tests them accordingly. 

</br>9. Enterprise Structure Mining feature of KTern can be used to audit the configured landscape. This allows the customer to Go-Live with the system without any apprehensions.

</div>