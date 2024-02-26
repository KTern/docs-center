---
title: "Enterprise Structure - Purchase Documents"
date: 2024-01-28T11:02:05+06:00
lastmod: 2024-02-26T11:02:05+06:00
weight: 21
draft: false
# search related keywords
keywords: ["induct", "instate"]
---
<div style='text-align: justify;'>

</br>1. The box displays the total count of Purchase Documents. Click on the launch icon (9) adjacent to Purchase Documents to explore a tree view showcasing the complete history of purchase documents.

![Launch - Purchase Documents](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/11_launch_purchase_documents_enterprise_mining_widgets_process_assessment_digital_maps.png)

</br>2. By clicking on the node (10) corresponding to the company code, you can reveal the purchasing organization beneath it.

![Tree View - Purchase Documents](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/12_purchase_documents_enterprise_mining_widgets_process_assessment_digital_maps.png)

</br>3. Upon further drilling down, the flow includes:

**Company code -> Purchasing Organization -> Purchasing Group -> Plant -> Storage Location -> Number of Purchase Documents created**.
</li></br>

![Tree View - Purchase Documents](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/13_purchase_documents_enterprise_mining_widgets_process_assessment_digital_maps.png)

</br>4. As seen in the above picture, KTern’s Enterprise Structure Mining feature drills down into various organizational units. 

</br>5. It delves into company codes, purchasing organizations, purchasing groups, plant, storage location and all the way up to the number of purchase documents created. 

</br>6. In this way, KTern provides a clear hierarchy and evidently maps the organizational structure. 

</br>7. The hierarchy of a purchase organization is as follows:

**Company Code -> Purchasing Organization -> Purchasing Groups -> Plant -> Storage Location -> No. of Purchase Documents Created**

</br>8. The functional consultants manually doing this task will definitely not be able to provide such clarity and accuracy in mapping the organization structure. 

</br>9. They have to go through each table, record and t-code to get this information. And even then, they will not be able to get the total picture. 

</br>10. It may take several weeks or even months to complete it. KTern automates the task and provides the results in a span of a few minutes.

</br>11. Another important feature of KTern’s Enterprise Structure Mining is that you can sort and search the company codes, purchasing organizations, purchasing groups, plant, storage location, and the number of purchase documents. 

</br>12. This enables you to determine the most active company codes, purchasing organizations and so on. 

</br>13. For example, if only two purchase documents are generated for the past 5 years in one of the plants, then it can be inferred that that particular plant is not active. 

</br>14. After discussing with the business stakeholders, you need not move that particular plant to S/4HANA.

</br>15. You can gain such insights only when you have such detailed hierarchy and organizational mapping as provided by KTern. 

</br>16. Such observations from KTern helps the MM functional consultants, business stakeholders from both the System Integrator side and the customer side, and the Solution Architects to have a clear picture of the landscape and take better data-driven decisions.

</br>17. Scrolling down, you'll encounter a table presenting information related to purchasing organization, purchasing group, plant, storage location, and the number of purchasing documents. 

</br>18. You can refine the data based on specific requirements and use keyword searches.
 
![Table View - Purchase Documents](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/14_table_purchase_documents_enterprise_mining_widgets_process_assessment_digital_maps.png)

### Enterprise Structure - Material Management:

</br>i. Each module in SAP has its own enterprise structure. An Enterprise Structure in SAP is nothing but the framework or structure according to which the whole business runs. And every organization has, or at least should have, some structure. 

</br>ii. There are several organizational units within an enterprise structure. The Material Management (MM) module in SAP has the following organizational units:
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
A client represents the highest node or hierarchy of an enterprise or organizational structure in SAP. The creation of a client in an SAP system is mandatory and a technical requirement. 
</li>
<li>
A client maintains several company codes within it. Data maintained at the client level is valid for all organizational levels.
</li>
</ul>

##### b. Company Code:
<ul>
<li>
A company code is created in the Finance (FI) module and is linked to the Material Management (MM) module. 
</li>
<li>
The Company Code is an independent company. A company code, which is a legal entity and statutory requirement, maintains the balance sheets and P&L statements. In fact, the company code maintains all book of accounts.
</li>
</ul>

##### c. Plant:
<ul>
<li>
A plant in an SAP system is a broad term and has varying definitions in different modules.
</li>
<li>
In the SAP Material Management (MM) module, a plant refers to a facility where the material stock is kept, stored and the inventory is maintained. 
</li>
<li>
Activities within a company take place within a plant. A plant has a manufacturing facility, warehouse distribution center and a regional sales office.
</li>
</ul>

##### d. Storage Location:
<ul>
<li>
A storage location is an organizational unit that actually differentiates between different material stocks in a plant. 
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
A purchasing organization is an organizational unit within SAP Material Management (MM), and it is responsible for all the purchasing activities within a company. 
</li>
<li>
It handles all the procurement activities and documentation such as Request for Quotations (RFQs), contracts, Purchase Orders (POs), etc. 
</li>
<li>
A purchasing organization carries out all the procurement activities on behalf of the company. There are several types of purchasing organizations:
</li>
</ul>
<ul>
</br>

</br>**e1. Centralized Purchasing**
   A purchasing organization at the client level is called as centralized purchasing. For example, if a company has only one procurement department and it carries out all the procurement activities, then a centralized purchasing organization is created.

</br>**e2. Company specific Purchasing:**
   In this case, a purchasing organization is assigned only to one company code. Only the plants belonging to this company code can procure and purchase through this purchasing organization.

</br>**e3. Plant specific Purchasing:**
   There are some cases where the size of the company is too large and having a centralized purchasing organization is not viable. Even company-specific purchasing organizations are too hard to handle. In such cases, each plant has a separate purchasing organization. These plant-specific purchasing organizations are responsible for the procurement of their own plant only.
</ul>

##### f. Purchasing Group:
<ul>
<li>
A purchasing group consists of individuals or group of individuals who are responsible for carrying out the purchasing activities. 
</li>
<li>
In other words, they are responsible for the everyday procurement activities of the organization. They are usually for reporting and approval procedures. 
</li>
<li>
They handle the Purchase Requisitions (PR), Request for Quotations (RFQs), Purchase Orders (POs), Contracts etc.
</li>
<li>
The main purpose of Enterprise Structure Mining before moving to S/4HANA is to find out the relevant and active company codes, purchasing organizations, purchasing groups and the other organizational units. 
</li>
<li>
Most of these enterprise purchase organizations would have been modeled long back, and the documentation might not be available today. 
</li>
<li>
The organizational units might have gone through several changes since the last update. And the aging workforce of SAP does not make the situation any better.
</li>
<li>
It is necessary to give proper training and handover to the millennial workforce. However, with the disparate information and inconsistent documentation, it is not always possible. 
</li>
<li>
KTern can help you here by continuously monitoring and providing materiality of where the consultants should focus. 
</li>
<li>
Mostly this information or knowledge is with a privileged few or in the System Integrator's privy. KTern helps you to unearth the enterprise procurement and purchase structure and provides the information in an easy-to-consume format.
</li>
<li>
The findings from this tool, KTern, will help you determine the most useful/most used organizational units. 
</li>
<li>
Such insights can help you re-engineer your business process. Therefore, business stakeholders will have better clarity and make data-driven decisions with confidence.
</li>
</ul>
</ul>

</div>