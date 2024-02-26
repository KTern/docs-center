---
title: "Add On Analytics"
date: 2024-01-28T11:02:05+06:00
lastmod: 2024-01-28T11:02:05+06:00
weight: 14
draft: false
# search related keywords
keywords: ["induct", "instate"]
---
<div style='text-align: justify;'>


### Add-on Analytics

Your transition from ECC to S/4HANA can stop in its tracks if there is an incompatible add-on. All add-ons must be certified in order to run on S/4HANA. For SAP’s own add-ons or the ones sold through SAP’s pricelist, you can directly request the status of add-ons and additional packages from SAP themselves. However, SAP is not responsible for the independent third-party add-ons.

KTern automates the process of add-on compatibility check during the SAP S/4HANA assessment and does not require the installation of any SAP Notes in the system. After connecting the system, KTern runs the check and automatically classifies the installed add-ons into compatible and incompatible add-ons.

![](https://storage.googleapis.com/ktern-docs-files/landscape-3.jpg)

#### Process of Add-on Analytics

1. First, you need to check the add-ons which are compatible and incompatible for the S/4HANA version you are targeting. The compatible add-ons can be migrated to S/4HANA without any trouble.
2. For incompatible add-ons, you must notify SAP or third-party vendors. Advance notification will enhance the chances of your add-ons certification in time for your implementation/ deployment.
3. You can contact third-party software vendors of incompatible add-ons and ask them to accelerate their certification process.
4. You can uninstall the add-ons which are not in use.

Add-on compatibility check is one of the most important and decisive features in KTern’s Impact Analysis module. It is part of the Discover phase in the SAP Activate methodology. KTern automates the process of add-on compatibility check. The main objective of this feature is to determine the add-ons incompatible with S/4HANA, and how it impacts the transition process.

KTern automates the process of add-on compatibility check and does not require the installation of any SAP Notes in the system. After connecting the system, KTern runs the check and automatically classifies the installed add-ons into compatible and incompatible add-ons. KTern also goes a step further and classifies the add-ons into three broad categories. They are:

1. Software components
2. Installed products
3. Correction packages

The add-on compatibility check is one of the most important pre-checks before the move to S/4HANA. You can safely migrate the compatible add-ons to S/4HANA. However, if one of your critical add-ons is not compatible with S/4HANA, then your entire business could be at risk. In such cases, you will have to wait for SAP’s roadmap to make that particular add-on compatible with S/4HANA. Only then, you can plan your transition from ECC to S/4HANA.

This add-on compatibility check is performed by the Basis consultants and the results are evaluated by the respective functional consultants. For example, in SAP ECC treasure management is part of the Finance (FI) module. But, in S/4HANA, it is a separate add-on and treasury management cannot function on its own. So, the finance consultants will evaluate this particular impact.

![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/51_launch_add_on_analytics_landscape_assessment_digital_maps.png)
 
![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/52_add_on_analytics_landscape_assessment_digital_maps.png)
 
![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/53_table_add_on_analytics_landscape_assessment_digital_maps.png)

</div>