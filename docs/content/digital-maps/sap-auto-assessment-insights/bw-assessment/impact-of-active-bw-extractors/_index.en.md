---
title: "Impact of Active BW Extractors"
date: 2024-01-28T11:02:05+06:00
lastmod: 2024-01-28T11:02:05+06:00
weight: 35
draft: false
# search related keywords
keywords: ["induct", "instate"]
---
<div style='text-align: justify;'>

</br>1. Click on the launch icon (1) to explore detailed insights into the "Impact of Active BW Extractors".

![Launch Impact of Active BW Extractors](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/111_launch_impact_of_active_bw_extractors_bw_assessment_digital_maps.png)

</br>2. The chart seen in the below image will depict information about the impact status of active BW extractors.

</br>3. KTern classifies data sources into Whitelisted and Not Whitelisted categories. 

<ul>

</br>**i. Whitelisted sources**, authorized by SAP, ensure a secure migration to S/4HANA, adhering to standard best practices. 

</br>**ii.** In contrast, **Not Whitelisted sources** lack SAP authorization, potentially causing challenges during the system conversion.
</ul>

</br>4. Data sources are further classified based on their statuses:

![Chart - Impact Status of Active BW Extractors](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/112_impact_of_active_bw_extractors_bw_assessment_digital_maps.png)

<ul>

</br>**i. DS working (no restrictions):** Functions perfectly with SAP S/4HANA.

</br>**ii. DS working (with restrictions):** Available with SAP S/4HANA but may have some limitations, such as certain fields being unavailable.

</br>**iii. DS not working (alternative planned):** Not functional in S/4HANA but has an alternative solution.

</br>**iv. DS not working (no alternative):** Critical category where data sources don't function in S/4HANA and lack an immediate alternative in the roadmap.

</br>**v. Obsolete (not relevant):** Extractors no longer relevant in SAP S/4HANA.
</ul>

</br>5. KTern presents a table view of all BW data sources, including application components, classification, status, and associated SAP Notes. 

![Table - Impact Status of Active BW Extractors](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/113_table_impact_of_active_bw_extractors_bw_assessment_digital_maps.png)

</br>6. This table allows sorting and searching to identify the most impacted data source/extractor. The report can be downloaded for use in subsequent stages of the system conversion process.

</br>7. Primarily these inferences from the BW Extractor Check are utilized by SAP Analytics and BI/BW consultants, this feature helps estimate the effort required for S/4HANA conversion. 

</br>8.For instance, if a data source is non-functional or not whitelisted, consultants may need to create a custom data source, migrate data, and integrate it into the new system. 

</br>9. Similarly, for non-relevant data sources, consultants may opt for a custom solution, ensuring crucial data is retained even if the original source is deprecated in S/4HANA.

</div>