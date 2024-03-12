---
title: "Archiving Recommendations"
date: 2024-01-28T11:02:05+06:00
lastmod: 2024-03-03T11:02:05+06:00
weight: 15
draft: false
# search related keywords
keywords: ["induct", "instate"]
---
<div style='text-align: justify;'>

</br>1. With the Archiving Recommendations feature, KTern automatically analyses the system and identifies the documents, tables and custom programs that can be archived. You can then archive these data to any other third-party storage database.

</br>2. SAP Data Archiving Process essentially involves three major steps:
<ul>
i. Creating archive files
</br>ii. Running delete programs
</br>iii. Storing the archive file
</ul>

</br>3. Click on the launch icon (5) to access an analytical horizontal bar chart displaying the document types to be achieved. 

![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/54_launch_archiving_recommendations_landscape_assessment_digital_maps.png)
 
![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/55_archiving_recommendations_landscape_assessment_digital_maps.png)


</br>4. Additionally, access a detailed table containing two tabs:
<ul>

</br>**i. Custom Objects tab:** This tab contains the names and types of the custom objects present in the system.

</br>**ii. Documents tab:** This tab lists the document types that need to be archived, along with the number of documents in each category.
</ul>

</br>5. KTern provides a detailed report on archiving recommendations. The results are as follows:
<ul>
i. Documents archiving potential
</br>ii. Tables archiving potential
</br>iii. Custom programs archiving potential

![](https://storage.googleapis.com/ktern-docs-files/landscape-5.png)

#### i. Documents Archiving Potential

![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/57_documents_archiving_recommendations_landscape_assessment_digital_maps.png)

<ul>
<li> KTern determines the potential documents in an SAP ECC system that you can archive. All types of documents, such as Material Ledger documents, change documents, purchase documents, can be archived. 
</li>
<li>Archiving documents means that you delete data from the database and archive it in the file system. You can then store the data from the file system in external archives, thereby relieving the burden on your database at regular intervals.
</li>
<li>
Archiving takes place in two steps. The first step is to write the data to an archive file in the file system. 
</li>
<li>
Then you delete the data from the database based on this archive. You can still access data that you have archived to the archive file in the file system. 
</li>
<li>
If you need the data in the database again (for example, because you have to make changes to it or because you archived it by mistake), you can also reload archives.
</li>
</ul>

#### ii. Table Archiving Potential
<ul>
<li>KTern determines which objects archive the data records from a specific table or enable you to display all the tables for a specific archiving object. 
</li>
<li>
You can also call various statistics for the amount of used database space.
</li>
</ul>

![](https://storage.googleapis.com/ktern-docs-files/landscape-6.png)

#### iii. Custom programs archiving potential
 
![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/56_custom_objects_archiving_recommendations_landscape_assessment_digital_maps.png)

<ul>
<li>
All Standard SAP tables have corresponding archiving objects that can be configured to perform archiving based on the required conditions and at specific time periods. 
</li>
<li>
Since the development of SAP objects generally involves the creation of custom Z-Tables, there may arise a need for the creation of custom archiving objects for the newly created tables.
</li>
<li>
All archiving objects have the following reports linked to them to achieve end-to-end archiving.
<ul>

**a. Write Program:** To create an archive file and write the database table entries into it based on the selection criteria specified in the variant
**b. Delete Program:** The Delete program is used to delete the records that are successfully archived and stored
**c. Reload Program:** The reload program is used to retrieve the data stored in the selected archive file and update the records back into the table
**d. Pre-Processing Program:** This program may contain some functionality to be carried out before data is archived and deleted from the database
**e. Post-Processing Program:** This program may contain some functionality to be carried out after data is archived and deleted from the database
</ul>
</li>
</ul>

</br>6. Project Managers, Solution Architects and the key Stakeholders from the customer side use this feature predominantly. In some countries, it is mandatory to store 5 years of system data or 7 years of system data. 

</br>7. The customer can decide to archive their data based on KTern’s archiving recommendations and their country’s legal compliance.

</br>8. Moving to S/4HANA with minimal amount of data will not only ease the transition process but also reduce significant costs in the future.

</div>