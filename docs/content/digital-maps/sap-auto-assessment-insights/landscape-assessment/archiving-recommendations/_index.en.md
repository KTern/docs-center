---
title: "Archiving Recommendations"
date: 2024-01-28T11:02:05+06:00
lastmod: 2024-01-28T11:02:05+06:00
weight: 15
draft: false
# search related keywords
keywords: ["induct", "instate"]
---
<div style='text-align: justify;'>

With the Archiving Recommendations feature, KTern automatically analyses the system and identifies the documents, tables and custom programs which can be archived. You can then archive these data to any other third-party storage database.


![](https://storage.googleapis.com/ktern-docs-files/landscape-4.png)

SAP Data Archiving Process essentially involves three major steps:

1. Creating archive files
2. Running delete programs
3. Storing the archive file

KTern provides a detailed report on archiving recommendations. The results are as follows:

1. Documents archiving potential
2. Tables archiving potential
3. Custom programs archiving potential

![](https://storage.googleapis.com/ktern-docs-files/landscape-5.png)

#### Documents Archiving Potential

KTern determines the potential documents in an SAP ECC system that you can archive. All types of documents such as Material Ledger documents, change documents, purchase documents can be archived. Archiving documents means that you delete data from the database and archive it in the file system. You can then store the data from the file system in external archives. You can thereby relieve the burden on your database at regular intervals.

Archiving takes place in two steps. The first step is to write the data to an archive file in the file system. Then you delete the data from the database based on this archive. You can still access data that you have archived to the archive file in the file system. If you need the data on the database again (for example, because you have to make changes to it or because you archived it by mistake), you can also reload archives.

#### Table Archiving Potential

KTern determines which objects archive the data records from a specific table or enables you to display all the tables for a specific archiving object. You can also call various statistics for the amount of used database space.

![](https://storage.googleapis.com/ktern-docs-files/landscape-6.png)

#### Custom programs archiving potential

All Standard SAP tables have corresponding archiving objects that can be configured to perform archiving based on the required conditions and at specific time periods. Since the development of SAP objects generally involves the creation of custom Z-Tables there may arise a need for the creation of custom archiving objects for the newly created tables.

All archiving objects have the following reports linked to them to achieve end-to-end archiving.

1. **Write Program**– To create an archive file and write the database table entries into it based on the selection criteria specified in the variant
2. **Delete Program**– The Delete program is used to delete the records that are successfully archived and stored
3. **Reload Program**– The reload program is used to retrieve the data stored in the selected archive file and update the records back into the table
4. **Pre-Processing Program** – This program may contain some functionality to be carried out before data is archived and deleted from the database
5. **Post-Processing Program** – This program may contain some functionality to be carried out after data is archived and deleted from the database

Project Managers, Solution Architects and the key Stakeholders from the customer side use this feature predominantly. In some countries, it is mandatory to store 5 years of system data or 7 years of system data. The customer can decide to archive their data based on KTern’s archiving recommendations and their country’s legal compliance.

Moving to S/4HANA with minimal amount of data will not only ease the transition process but also reduce significant costs in the future.



![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/54_launch_archiving_recommendations_landscape_assessment_digital_maps.png)
 
![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/55_archiving_recommendations_landscape_assessment_digital_maps.png)

![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/56_custom_objects_archiving_recommendations_landscape_assessment_digital_maps.png)
 
![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/57_documents_archiving_recommendations_landscape_assessment_digital_maps.png)

</div>