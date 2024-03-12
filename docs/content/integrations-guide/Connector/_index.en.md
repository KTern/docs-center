---
title: "KTern Connector"
date: 2022-11-05T11:02:05+06:00
lastmod: 2022-11-05T11:02:05+06:00
weight: 1
draft: false
# search related keywords
keywords: ["induct", "instate"]
---

<div style='text-align: justify;'>

### Introduction

The KTern.AI On-Premise Connector facilitates client-side connectivity with any NetWeaver systems of SAP like SAP ECC, SAP S/4HANA, SAP CRM , SAP SRM and SAP BW enabling seamless integration with the KTern.AI web application. 

### Prerequisites

1. Ensure access to the SAP client network or establish a connection through Remote Access VPN or Site-to-Site VPN.
2. Port 33xx must be accessible in the client network, serving as the default SAP Gateway port.
Where xx relates to the Instance number of SAP system, SAP Ports reference : [https://help.sap.com/viewer/ports](https://help.sap.com/viewer/ports).
3. If translation of IP addresses is carried out using NAT, kindly refer to the SAP Note 148832​ for further instructions.
4. Users must have authorization for RFC communication.
5. WiFi/LAN network bandwidth and stability should be ensured for optimal performance.

### Procedure

#### 1. Download KTern.AI Connector
Click 'Download KTern Connector' and save the file in a preferred location on your desktop/laptop.

![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/Connector_1.png)

#### 2. Unzip the Downloaded File
Unzip the downloaded 'KTern.zip' file to access its contents.

#### 3. Launch the Application
From the unzipped contents,click and launch the Application.

#### 4. Wait for Initialization
Wait for a few seconds for the application to launch and settle down in the taskbar system tray.

#### 5. Access KTern.AI Web Application
Once the application is settled in the system tray, proceed to use the KTern.AI web application.

#### 6. Add a System in Landscape Management
In the web app, navigate to 'Landscape Management' and click on '+ Add New System'.

Enter the required details for the system configuration.

![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/Connector_2.png)

#### 7. Considerations
Ensure compliance with the following considerations listed below the system configuration:

a. Connectivity within the SAP client network or via VPN.
b. Accessibility of Port 33xx in the client network.
c. Adherence to NAT translation guidelines if applicable.
d. Authorization for RFC communication to the user.
e. Network bandwidth and stability assurance.

#### 8. Connect to the System
Click 'Connect' to initiate the connection to the respective system.

#### 9. Provide Credentials
Enter the username and password of the respective system.

Click 'Submit' and wait for a few seconds for the connection result.

![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/Connector_3.png)

#### 10. Verify Connection
Upon successful connection, the system status will indicate 'Connected' with a success message.

In case of failure, an error message will be displayed. Refer to the provided instructions to troubleshoot and attempt connection again if necessary.

With the successful establishment of the connection, users can now execute KTern.AI automated activities seamlessly, leveraging the connectivity facilitated by the KTern.AI On-Premise Connector.


Note: In all the above approaches, the client team shall ensure stable connectivity without interruptions.

</div>