**![D:\\og-dd-logo-1200x628 (2).jpg](media/0606ca5628079ef13936db4fee95401c.jpeg)**

![D:\\csm_Logipad_Logo_rgb_6a9b8dd7a2.png](media/feb27d0a82e329ed73c7120de86f2efb.png)

**LOGIPAD USER MANUAL**

**![](media/ab36b643f45515574436c82d5c523443.png)**

Manual Code: LM- Logipad Team

Issue Number: 02, Issue date: 14 Feb 2025

Revision Number: 00, Revision date: 14 Feb 2025

Blank page

# RISK ASSESSMENT FOR LOGIPAD AERO FUNCTIONS

## RISK ASSESSMENT FOR LOGIPAD DOCUMENTATION MODULE

This section provides the risks assessment for the use of the Documentation module that is part of the Logipad with Dextra Data software suite.

The objective of this risks assessment is to demonstrate that the application achieves at least the same level of integrity and availability as the “traditional” paper means

### Failure Cases and Mitigation Means

Types of risks are looked at and their consequences defined and mitigated. They are:

-   Total loss of the application
-   Data corruption
-   Undetected false output from the application.

Mitigation means are processes and procedures defined to compensate each identified failure case. They are means to provide availability of the application and to ensure detection of a false output.

Table 1: Failure cases and Mitigation means in Documentation module

| **FAILURE CASES**                                                                                                                                                                         | **MITIGATION MEANS**                                                                                                                                                                                                                                                                              |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|  When updating documents using the same name, the operation manuals are not correctly updated. Unable to access the latest version of Documents.                                          | Logipad has an offline functionality. Previous documents ver-sions will be available.   PDF expert/ One drive can be used as backup option                                                                                                                                                        |
| Long time for downloaded content                                                                                                                                                          | The content dowload size can be huge for the first syn-chronization. Therefore, ensure that a good and stable wifi connection is available. Logipad will only doing partial updates for all other synchronization  EFB admin can mark documents for dowload only when wifi connecttion availlable |
| Erroneous Documents output   Sometimes Documents are visible to users even if expired/ Documents are not visible to users even validity date is set Document’s confirmation cannot be set | EFB admin need to setting a new expiration/validity date and need to initiate a new release to productive.  Logipad is operates in offline mode. Once a connection is establised the confirmation is automatically sent for users PDF expert/One drive can be used as backup option               |

## RISK ASSESSMENT FOR LOGIPAD electronic Flight Folder ( EFF) MODULE

This section provides the risks assessment for the use of the Documentation module that is part of the Logipad with Dextra Data software suite.

The objective of this risks assessment is to demonstrate that the application achieves at least the same level of integrity and availability as the “traditional” paper means

### Failure Cases and Mitigation Means

Types of risks are looked at and their consequences defined and mitigated. They are:

-   Total loss of the application
-   Data Corruption
-   Sent function was lost

Mitigation means are processes and procedures defined to compensate each identified failure case. They are means to provide availability of the application and to ensure detection of a false output.

Table 2: Failure cases and Mitigation means in EFF module

| **FAILURE CASES**                                                               | **MITIGATION MEANS**                                                                                                                                                                                                                           |
|---------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Briefing package is not syn-chronized to client.                                | Users Re-install and sync again, EFB admin do hash checking Sharepoint folder/ paper flight plan can be as backup method                                                                                                                       |
| Briefing package gets cor-rupted during synchroniza-tion from Backend System.   | Users Re-install and sync again, EFB admin do hash checking Logipad offers a copy function to copy existing Briefing Pack-ages from crew members related to the same flight.                                                                   |
| Filled eBriefing Package can-not be sent.                                       | When Users filled eBriefings cannot be sent to the Logipad Backend System They will be stored on the device (Offline Mode). Logipad will automatically resent the filled eBriefing package once a connection (WIFI, 4G, LTE, 5G) is available. |

## RISK ASSESSMENT FOR electronic Forms (eForms) MODULE

This section provides the risks assessment for the use of the eForms module that is part of the Logipad with Dextra Data software suite.

The objective of this risks assessment is to demonstrate that the application achieves at least the same level of integrity and availability as the “traditional” paper means

### Failure Cases and Mitigation Means

Types of risks are looked at and their consequences defined and mitigated. They are:

-   Total loss of the application
-   Server Corruption
-   Sent and filled function was lost

Mitigation means are processes and procedures defined to compensate each identified failure case. They are means to provide availability of the application and to ensure detection of a false output.

Table 3: Failure cases and Mitigation means in EForms module

| **FAILURE CASES**                                                          | **MITIGATION MEANS**                                                                                                                                                                                                                                                        |
|----------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Electronic forms do not syn-chronize to clients.                           | Existing eForms will be available and not deleted by the application. Logipad can work in offline mode. Digital form can be storage in PDF expert or paper forms as backup method                                                                                           |
| Electronic forms inputs are not imported into Logipad’s Server database.   | Once eForms are sent to the server, eForms are cached an can be imported manually to the database at a later time.                                                                                                                                                          |
|  Electronic forms cannot be filled and sent                                | Use spare spare device, or paper backup form.  Logipad have offline functionality. Even during a connection loss (WIFI, eforms cannot be sent), eForms are stored in an out-box. Once the WIFI access is available Logipad will automatically resend the missing eForm(s).  |
