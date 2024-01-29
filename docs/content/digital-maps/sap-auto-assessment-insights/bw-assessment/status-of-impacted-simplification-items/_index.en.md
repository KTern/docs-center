---
title: "Status of Impacted Simplification Items"
date: 2024-01-28T11:02:05+06:00
lastmod: 2024-01-28T11:02:05+06:00
weight: 37
draft: false
# search related keywords
keywords: ["induct", "instate"]
---
<div style='text-align: justify;'>

</br>1. The Simplification Item check in KTern.AI determines the relevance of Simplification items in the target SAP S/4HANA system.

</br>2. Each Simplification Item has an associated SAP OSS Note containing details and procedures, which must be installed and executed. KTern automates this process, offering a comprehensive view of all pertinent simplifications for SAP S/4HANA.

</br>3. Trigger the launch icon (3) to get detailed insights into the status of impacted Simplification Items.

![Launch - Status of Impacted Simplification Items](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/117_launch_status_of_impacted-simplification_items_bw_extractors_bw_assessment_digital_maps.png)

</br>4. KTern.AI categorizes Simplification items into relevant and irrelevant ones for your business, presenting the status of each item with SAP note references. 

</br>5. The platform calculates the total number of Simplification Items, classifying them into impacted and non-impacted items, and provides the status of each with SAP Note references. 

![Chart - Status of Impacted Simplification Items](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/118_status_of_impacted-simplification_items_bw_extractors_bw_assessment_digital_maps.png)

</br>6. The impacted items are further categorized based on their status:
<ul>

</br>**i. Change of existing functionality:** Functions available in SAP S/4HANA but adapted in a way that might affect existing processes and custom programs.

</br>**ii. Functionality unavailable (equivalent exists):** Functions not available in SAP S/4HANA, but an equivalent functionality exists.

</br>**iii. Functionality unavailable (no equivalent):** Functions not available in SAP S/4HANA, and no equivalent functionality is available. Organizations may choose to wait for SAP to release that functionality before migrating.

</br>**iv. Non-Strategic Functions (equivalent exists):** Existing ECC modules or functionalities identified as "non-strategic" in S/4HANA, with equivalent functionalities available.

</br>**v. Non-Strategic Functions (no equivalent):** Non-strategic functions with no equivalent in S/4HANA.
</ul>

</br>7. Scrolling down, you can access a table that provides information on the Application Area, Simplification Item, Application Component, Simplification Notes, and Status.

![Table - Status of Impacted Simplification Items](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/119_table_status_of_impacted-simplification_items_bw_extractors_bw_assessment_digital_maps.png)

</div>