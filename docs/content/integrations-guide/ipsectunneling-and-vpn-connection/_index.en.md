---
title: "IPsec Tunneling and VPN Connection"
date: 2022-11-05T11:02:05+06:00
lastmod: 2022-11-05T11:02:05+06:00
weight: 1
draft: false
# search related keywords
keywords: ["induct", "instate"]
---

<div style='text-align: justify;'>

## I. Client-side IPSec Tunnel Connectivity

### Introduction

The KTern.AI facilitates client-side IPSec Tunnel connectivity with any NetWeaver systems of SAP like SAP ECC, SAP S/4HANA, SAP CRM , SAP SRM and SAP BW enabling seamless integration with the KTern.AI using IPsec Tunneling.

KTern.AI connects to SAP system via standard SAP RFC protocol, inorder to call RFC enabled function modules (SAP Business APIs). This connectivity can be enabled via IPSec tunnelling approach by the customer.

Note : As per SAP standard architecture guidelines, the SAP Gateway carries out RFC services within the SAP world, which are based on TCP/IP. These services enable SAP Systems & external programs to communicate with one another.  

 
### Prerequisites

1. KTern.AI team will provide the necessary firewall details required to configure an IPSec tunnel to the client team.

2. Client Network Team is responsible for generating a pre-shared key for the IPSec tunnel.

3. Client Network Team will configure the IPSec tunnel on the client network firewall using the provided details.

4. They will also share the required configuration details along with the pre-shared key with the KTern.AI team.
5. KTern.AI team will configure the IPSec tunnel on KTern.AI firewall based on the details provided by the client team.

6. KTern.AI team will initiate the traffic and troubleshoot the IPSec tunnel connection if required.

7. Client team will provide SAP system connectivity details as per pre-requisites to the KTern.AI team.

8. KTern.AI team will test and establish the IPSec tunneling and SAP system connectivity based on the provided details.
 
### SAP System Prerequisites

1. A copy of the latest SAP Production system ('PRD') is required to set up the SAP Sandbox ('SBX') system.

2. The following connection details for the 'SBX' system must be provided(Application Server, System ID, Instance Number,Client Number, Username, Password).

3. The last 6 months' ST03N statistics from the SAP 'PRD' system must be made available in the provided SAP 'SBX' system.

4.  Implementation of the following SAP Notes in the SBX system are required for custom code impact analysis KPI (SAP Notes: 2270689, 2485231, 2190065, 2196792).

5. An RFC Communication User with 'SAP_ALL' authorization profile must be ensured in the SBX system. This user should have READ-ONLY access.

6. Port 33xx must be accessible in the client network, as it is the default SAP Gateway port. (Where 'xx' refers to the Instance Number of the SAP 'SBX' system).
 
### References 

1. If translation of IP addresses is carried out using NAT, kindly refer to this SAP Note 148832.

2. KTern.AI Digital Maps prerequisites rely on ST03N statistics, RFC communication user with ‘SAP_ALL’ authorization profile, as KTern.AI does a read-only scan and comprehensive analysis of the business processes, custom objects and landscape of SAP system through SAP RFC protocol for assessment. 

3. SAP Ports reference:
 [https://help.sap.com/docs/Security/575a9f0e56f34c6e8138439eefc32b16/616a3c0b1cc748238de9c0341b15c63c.html](https://help.sap.com/docs/Security/575a9f0e56f34c6e8138439eefc32b16/616a3c0b1cc748238de9c0341b15c63c.html)

4. SAP Gateway reference:
 [https://help.sap.com/saphelp_gbt10/helpdata/EN/48/ace6623b1e35bae10000000a42189d/content.htm?no_cache=true](https://help.sap.com/saphelp_gbt10/helpdata/EN/48/ace6623b1e35bae10000000a42189d/content.htm?no_cache=true)


Note: In all the above approaches, the client team shall ensure stable connectivity without interruptions.



## II. Client VPN Connection

### Introduction

The KTern.AI facilitates Client VPN Connection with any NetWeaver systems of SAP like SAP ECC, SAP S/4HANA, SAP CRM , SAP SRM and SAP BW enabling seamless integration with the KTern.AI web application using IPsec Tunneling.

KTern.AI connects to SAP system via standard SAP RFC protocol, inorder to call RFC enabled function modules (SAP Business APIs). This connectivity can be enabled via client VPN approach by the customer.
 

Note : As per SAP standard architecture guidelines, the SAP Gateway carries out RFC services within the SAP world, which are based on TCP/IP. These services enable SAP Systems & external programs to communicate with one another. 


### Prerequisites

1. The Client Network team is responsible for furnishing the VPN client details, including remote gateway, port, username, password/certificate, and MFA (Multiple Factor Authentication).

2. KTern.AI team will initiate the traffic and troubleshoot the IPSec tunnel connection if required.

3. Client team will provide SAP system connectivity details as per pre-requisites to the KTern.AI team.

4.  KTern.AI team will test and establish the Client VPN Connection and SAP system connectivity based on the provided details.
 
### SAP System Prerequisites

1. A copy of the latest SAP Production system ('PRD') is required to set up the SAP Sandbox ('SBX') system.

2. The following connection details for the 'SBX' system must be provided(Application Server, System ID, Instance Number,Client Number, Username, Password).

3. The last 6 months' ST03N statistics from the SAP 'PRD' system must be made available in the provided SAP 'SBX' system.

4.  Implementation of the following SAP Notes in the SBX system are required for custom code impact analysis KPI (SAP Notes: 2270689, 2485231, 2190065, 2196792).

5. An RFC Communication User with 'SAP_ALL' authorization profile must be ensured in the SBX system. This user should have READ-ONLY access.

6. Port 33xx must be accessible in the client network, as it is the default SAP Gateway port. (Where 'xx' refers to the Instance Number of the SAP 'SBX' system).
 
### References 

1. If translation of IP addresses is carried out using NAT, kindly refer to this SAP Note 148832.

2. KTern.AI Digital Maps prerequisites rely on ST03N statistics, RFC communication user with ‘SAP_ALL’ authorization profile, as KTern.AI does a read-only scan and comprehensive analysis of the business processes, custom objects and landscape of SAP system through SAP RFC protocol for assessment. 

3. SAP Ports reference:
 [https://help.sap.com/docs/Security/575a9f0e56f34c6e8138439eefc32b16/616a3c0b1cc748238de9c0341b15c63c.html](https://help.sap.com/docs/Security/575a9f0e56f34c6e8138439eefc32b16/616a3c0b1cc748238de9c0341b15c63c.html)

4. SAP Gateway reference:
 [https://help.sap.com/saphelp_gbt10/helpdata/EN/48/ace6623b1e35bae10000000a42189d/content.htm?no_cache=true](https://help.sap.com/saphelp_gbt10/helpdata/EN/48/ace6623b1e35bae10000000a42189d/content.htm?no_cache=true)
 
Note: In all the above approaches, the client team shall ensure stable connectivity without interruptions.

</div>