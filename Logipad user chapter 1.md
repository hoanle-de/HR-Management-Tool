

# MANAGEMENT AND ADMINISTRATION

## EFB SYSTEM OVERVIEW/ CONTROL AND RESPONSIBLE:

### LOGIPAD EFB SYSTEM

The Logipad Aero EFB System consists of following elements;

#### HARDWARE CONSIDERATION :

Logipad solutions is a set of type B software which can be using for electronic devices. We recommended all airlines should using COTS (Commercial Off-The-Shelf) hardware already approved by EASA and FAA for use as EFB device.

The Hardware should compliance with the following standards: EASA AMC20-25 and FAA AC120-76C for:

-   Electromagnetic Interference (EMI) Demonstrations
-   Environmental Testing (Rapid Depressurization)
-   **Batteries**

    According to the test, these iPads do not affect the performance of aircraft systems, equipment or the ability to operate the aircraft; EFB hardware should be consideration in the following items:

-   **Paper Data Removal**

    Ideally, at least two operational EFBs would be needed to remove paper products that contain aeronautical charts, checklists, or other data required by the operating rules. The design of the EFB function is such that it would not allow for a single failure or common mode error may cause him loss of required aeronautical information.

-   **Electrical Power Source**

    For EFB Hardware, The System design must take into account the source of electrical power, the independence of the power sources for multiple EFBs, and the potential need for an independent battery source. Battery-powered EFBs that have aircraft power available for recharging the EFB battery are considered to have a suitable backup power source. EFBs that do not have a battery power source and that are used in place of paper products required by the operating rules must have at least one EFB connected to an aircraft power bus.

-   **The replacement of Battery**

    In the event that a battery is designed with the option of replacement, the established guidelines for battery replacement interval, as specified by the manufacturer of the original battery (or cell), should be observed. In instances where the manufacturer of the original battery (or cell) has not provided a specified replacement interval, the guidelines established by the manufacturer of the replaceable battery should be adhered to.

-   **Battery Backup:**

    Consider equipping the EFB PED with an alternate power supply to help achieve an acceptable level of safety. For EFBs without an aircraft power source, it's possible that a backup battery might be needed. In addition, backup batteries are required to comply with established lithium battery safety and testing standards concerning fire prevention, environmental testing, and performance testing, . These standards are implemented to ensure that the battery is adequately capable of functioning within the aircraft and fully compliance required of CAAs. The operator should also make sure that batteries are replaced as required, at least as often as the EFB manufacturer's recommended interval.

#### EFB MOUNTING DEVICES :

Logipad is an application and does not require specific mounting device requirements. However, operators should ensure that the mounting devices fully comply with the hardware devices used for the organization and are fully compliant with the requirements of all civil aviation authorities for safety operations.

#### SOFTWARE/ EFB SYSTEM CONSIDERATION :

**Software Classification**: EFB solution is a comprehensive of flight briefing applications, documentation, E-Form, which allow pilots to access their flight package on board the aircraft and also from home/ hotel/crew room via internet connection that replaces day of flight paper documentation. These applications meet all the requirements set by EASA/FAA in **AMC 20-25/FAA AC 120-76D** for use as **EFB Type B software**

### CONTROL AND RESPOSIBILITIES.

The Administration section of this system encompasses all individuals involved, the organizational structure and processes, and the administrative applications utilized for automating control processes. The following groups of people are proposed to interact with the system to enhance its effectiveness.

-   **Head of Flight Operations / Director of Flight Operations**

    The Head of Flight Operations (HOFO) or Director of Flight Operations (DFO) bears the overarching responsibility for all flight operations conducted under their Air Operator Certificate (AOC). This responsibility encompasses ensuring the safety and compliance of flight operations with aviation regulations, as well as overseeing the EFB system. The HOFO/ DFO reports directly to the Accountable Manager for all flight ops status

-   **EFB Program Manager**

    The EFB Program Manager oversees the system's operation and manages the lifecycle of EFB applications, from development to release, including testing protocols, version upgrades, deployment strategy, and communications plans. The EFB Program Manager oversees the system's operation and manages the lifecycle of EFB applications, from development to release, including testing protocols, version upgrades, deployment strategy, and communications plans. The operational structure of the operators dictates the position's independence or integration into the responsibilities of the Technical Office Manager or Chief Pilot.

-   **EFB Administrator/ Operations Engineer**

    The EFB Administrator/ Operations Engineer is responsible for managing the Logipad Portal and configuring the server parameters to align with Operator field. Upon receiving a flight package and documentation data, the EFB Administrator will update the database on a gateway and notify all users to update their iPads accordingly. Logipad’s dynamic admin portal (MUI, Flight Manager, Jasper report server) has been created to assist with administrative tasks. Logipad Team also provided 24/7 Support Center for all client’s tickets.

## Management User Interface (MUI) Over view :

The Logipad Management User Interface (MUI) provides web services for retrieving and releasing user data, EFB data (including target associations, properties, metrics, and configuration data), and automation services for performing synchronous tasks for Operators. Furthermore, it assigns and deploys the user's data to users and devices, regardless of the hardware used (iOS, Windows, or Android devices).

The main functions for MUI shall be listed as bellow:

-   User management
-   Create news
-   Provide documents
-   Deploy e-Forms
-   Retrieving the completed e-Forms
-   User reports and statistics

    The user management system is based on a user/role framework, which is customizable to suit the needs of individual users. Content access and permissions are determined based on the user's assigned role.

### MUI Webservice/ Registration and login process;

The Management User Interface also called « MUI ». is a web-based interface.

![](media/4bda1ba2895c85c5610b9e7e30dbc591.png)

When accessing the website, a login window appears, where the user must enter his login name and password.

Depending on the Operator’s \`configuration the local login or the login with a Directory service is possible

After successful login you will get to the start page of MUI

![](media/48785817e2ac4aec43271fe213c14667.png)

### General section :

#### Users/ Add Users :

To add a User to the system click on the button Create a new user to open the dialog with the user settings. To edit an existing user click on the edit button ![](media/edf22fce7555a66cee18ead64765ea45.png)

To delete an existing user press the delete button ![](media/7fe68188a246314a60aed1f85ddf14d4.png)

The user dialog hat the following fileds :

-   Login name

    The login name for the user. This is the only mandatory field

-   Full name
-   eMail

![](media/e28d4f7bca8e99b0bc22e7532a15ed73.png)

-   3LC

    Three letter code

-   Type

    User type. This field is just used to organize the users. The select will automatically add new values

-   Department

    User department. The select will automatically add new values

-   Content role

    Role member ship for content assignment

-   Access groups

    Membership in Logipad security groups. For normal users the default values are ok

-   Reportable

    User should be listed in reports. Useful to exclude test accounts

-   Active

    Only ‘active’ users are able to login

-   Description

#### Exporting and importing users :

The user has also the option to export users or to perform a bulk import

![](media/689d8fcf915014acbdeed44e8d59ec52.png)

By pressing the « Arrow down » button on the right side of the button you can access the additional function.

#### Exporting users :

![](media/ef4aec36612f9583d964b11601fdced2.png)

The user export has only the option to choose the seperator and the escaping. Result will be a CSV file.

#### Importing users :

![](media/e2e46233fd7ecd4041a16e316d57d398.png)

The user import needs a separator and escaping for the file and needs a CSV file as input. The following

fields could be used. Only the login name is mandatory:

• Name

• Type

• FullName

• Email

• ThreeLc

• Department

• Description

• IsActive

• IsReportable

• Roles

The roles need to be separated by a ‘,’.

#### Content Roles :

The second point in the general section is the management of content roles.

![](media/e779a7ff7682c8a7bf1a2ca3e929195e.png)

#### Create a content role

The creation of a content role can be done by clicking the button **Create newcontent role** and assign the role name and type. The type is optional.

![](media/cc9843767ff6a75f2a919a93346fcf87.png)

#### Edit or delete a content role

![](media/4e44f7f1d1adb9043cc3bcef4c8adf9e.png)You can delete a content role by clicking the delete button ![](media/1482e8fc9c71dddbf34fa43d39dddfd0.png) Edit will be start with the edit button

#### Changing the user assignment to the role

![](media/9cb7d566647f9047a47efbd91fb3916e.emf)The role assignment dialog will be visible after clicking on the small arrow at the beginning of the row.

You can remove the member from the role by clicking ![](media/b98cc7ac91754adb5310a414061e2769.png)

![](media/6da6a6855539b0c9bfda1bf745d3e5db.emf)After using the button **Add Users to content role** you will get an additional dialog to add users.

#### Notification

The last entry in the general section is used to create and monitor notifications.

Important:

After the message was created it cannot be changed.

#### ![](media/e16a02e239b511733f4e086e44dc637f.emf)Creating a notification

A notification can include:

• Title

• Message

• Reference to Documents eForm, News or Weblink

and can be assigned to

• Users

• Content Roles

### EFB Approval Process Guidance :

The Operator must obtain approval from their Local Aviation Authority/ National Aviation Authorities (NAAs) before officially using Logipad products for daily flight operations. The approval and certification process depend entirely on the authorities ‘requirements. However, the general EFB system approval process should include the following main steps:

-   **Pre- Application Phase:** The first phase starts when an organization or individual inquiries about or states a need for a change in some aspect of an aviation activity.
-   **Initial Application Review Phase**: The 2 nd phase starts when the applicant formally applies package for the Project evaluation
-   **Document Conformance Phase:** This phase commences when the aviation authorities (NAAs) review, analyze, and evaluate the application package. The NAAs may require a test session, compliance matrix/reports or risk assessment if deemed necessary.
-   **Inspection & Demonstration Phase:** During this phase, the NAAA will finalize plans to inspect and evaluate the applicant's demonstration of their ability to perform in accordance with the formal application package's procedures, guidelines, and parameters. The NAAs can perform inspections and observe the applicant's demonstration through test sessions, tabletop exercises, ramp inspection programs, and other means.
-   **Final Certification Phase.** On this phase the Local Aviation Authority/ National Aviation Authorities (NAAs) finalizes by approval or acceptance by certificates, ops spec for the applicant. If the application is not approval or accepted, the applicant will be notice in phase 3 or 4

## Flight manager - simple to use, control and export of flight data

Flight Manager- Overview:

The Flight Manager platform provides web services to view, select, generate, control and export flight related data including fuel logs, briefing attachment files, flight logs and briefing definitions for daily flight operations. In addition, you can view a list of previously created, activated and completed flights in the operation history

### Briefing section / management, and generate/ upload all flights by status

-   View all flights in a given period by status. Select the flight status (Prod, Test) and the status (Created, Activated, Finalized). Created means the Briefing Package has been created, activated means the Briefing Package is active and ready, and Finalized means all crew have completed and returned the Briefing Package

###### ![](media/eb38df7e7a19fc9f9a96f5cdeab02f2b.png)**View all/ View Finalized/ View released.;** View all flights in a given period by status. Select the flight status (Prod, Test) and the status (Created, Activated, Finalized). Created means the Briefing Package has been created, activated means the Briefing Package is active and ready, and Finalized means all crew have completed and returned the Briefing Package

Dynamic table: You can quickly search and find the flight you want using a table with filters. The following but not limited filter apply for the table

-   Departure IATA code (3- Letter)
-   Departure ICAO code (3- Letter)
-   Arrival IATA code (3- Letter)
-   Arrival IATA code (4- Letter)
-   Flight (Flight number)
-   Aircraft (Aircraft registration)
-   Master user (Pilot in command user)
-   Departure time (The time when Actived the fight)
-   State (Prod/Test)
-   Status (Created/ Activated/ Finalized)

    ![](media/56cdd9cd3f7451c51985dc2258932683.png)![](media/59e7d036274b13c3a650ecf8ce544d60.png)To see detail of the flight, select ![](media/14d622ebdf434ba392a1d60de83c0193.png), To see all the figure of the flight select ![](media/ff03b3759cffde7dfc24042e944af73a.png), to Download all attached files select , In additional is also able to display the briefing details or download the briefing, The dispatcher can make changes or see the crew composition for the fight in the Assignment sheet

###### **New briefing:** The function allows you to manually create a new briefing package by selecting the correct Flight Planning System (.EFF) file and creating a briefing with your attachment files such as fuel receipts, ground reports and METAR/TAF. The crews for the flight have been selected by creating and simply releasing the flights.

###### ![](media/efc1d3beabc97cbf9ab6edd4e7c38494.png)**![](media/4fc5e77b45710114d4d78efc4339e446.png) Import from PPS**: Automatically import and generate multiple flights directly from Flight Planning system from API connection. The crews for multiple flights have been selected by creating and simply releasing the flights

###### Attachment Types: All attachment of the flights can be selected within briefing manager, Easy control and management

### ![](media/754ea4d24382464a8ac88425e6ad746c.png)Definitions section: The section allows you can select, define and assign the layout ( Colour, Texts, Placement of content…) which you want apply for your package

## Logipad Webclient

Logipad Webclient is a software application that facilitates access to and display of module form and document content through a web browser. It functions as an intermediary between users and web servers, enabling users to interact with websites, view multimedia content, support digital formats, and access various online services.

### Logipad user interface :

![](media/bb36c3641b73a57dc1ab61bbb214bc18.png)

After Sign in to Logipad Identity System ( Keycloak), you will see home screen of Web client version. In addition, users have the option of accessing a content summary of the number of documents, electronic forms, and web addresses linked to Logipad. A list of news about the EFB system and acknowledgment button is also available. Logipad web client are available for all Operators users

### Logipad Documents module :

![](media/e4069d19e51201bffc646b23e73ab279.png)

Documentation support for the following functions:

Docs View Section: Select search option for documents using by

-   Folder View
-   Total Documents
-   Number of Docs need confirmed

Docs View Filter: selectively filter documents by:

-   Name
-   Creation Date,
-   Document Priority
-   Document Confirmation Request Date

Document Properties Section:

In this section, you will find the options for each document in the laptop format. These include the following:

-   document creation date,
-   document editing date,
-   document folder path,
-   document version number,
-   option to open document in another window,
-   document request date,
-   vertical priority color bar.
-   Confirmed section

![](media/6d47a0cec016069e60bf90b098150903.png)

Document in view option:

![](media/188f1019e00fa3e2ee7605141e087e8f.png)

### Logipad Eforms Module :

Eforms Template/ History Section :

This section allows you to select pre-made and initialized templates as well as to fill out and submit your own report forms. Additionally, the History section allows users to review previous transmissions and generate electronic reports.

![](media/9756aadbef3aaf3610e840935830ec48.png)

Document View Editing:

With the report correction section. You can edit, fill in the information for the report directly on a web browser, Save the draft, as well as cancel and submit the report

![](media/72bf42709ac378600e11d314853777bc.png)

Show/Hide Eform Option:

![](media/18becb82f0feeff3df12d5851172d270.png)

### Logipad App Center

This section contains the versions of the software that are compatible with different platforms. It also includes QR templates that can be used to download settings and install applications. Additionally, it features modules that are currently under development by Logipad. All Logipad future modules will be integrated into versions of the software that are compatible with each individual platforming an appropriate way.

![](media/e5caf8b095ba24e1f0d4f37c4319748d.png)

## Jasper report/ Logipad reporting server

The Jasper Report Library is an open-source reporting engine for Logipad data regarding users, documents, briefings, and EFF data, as well as eForm reports. The Jasper Reporting Engine is entirely written in Java and is capable of utilizing data from any type of data source to produce pixel-perfect documents. These documents can be viewed, printed, or exported in a variety of document formats, including HTML, PDF, Excel, OpenOffice, MS Word, CSV, and others.

### Administration Folder

This folder contains a list of users categorized according to their access rights, thereby enabling the user to easily control statistics and edit access rights based on visualized report data.

![](media/1ebf009077c74746b4126e3c7477d872.png)

#### Access Group Memberships

This folder contains a list of users categorized according to their access rights, thereby enabling the user to easily control statistics and edit access rights based on visualized report data.

![](media/916f2a24b6d3756c75cbe3be2afd47c3.png)

Report files could be export under:

-   PDF
-   CSV
-   DOCx
-   RTF
-   ODT
-   ODS
-   XLSX
-   PPTX
-   CSV
-   Excel Metadata

#### Active Report Server

The active report server is utilized for the purpose of monitoring the overall status of users who utilize the software. The following information is employed in the following items bellow:

-   Deactivated
-   Excluded
-   Reportable
-   Active
-   Last active time
-   ![](media/35bd8399c55018160a5c69c8efaf8643.png)Last Sync time

#### User reports :

For user reports folder, you could be able to see and analytics status report for each users or list of missing confirmation by user

![](media/f14da13ae49cc1b7822c9369abe04ac2.png)

Confirmation missing by user:

![](media/b894913de99caa586568580f2b8b23c2.png)

### Briefing Report Server :

This folder contains two types of information regarding flights: one type is an overview of flights that have been released, and the other type is a list of flights (briefing package) that have not yet been finalized. The purpose of this folder is to facilitate the identification of the cause of any discrepancies.

#### Not finalized briefing :

The list of flights has not yet been finalized. The person in charge of flight operations (i.e., the "**master user**") has not yet completed the list. The release will be compiled according to the city pair, time, package status, revision

![](media/38b3cd09e9b8eeb51f97719a333f6a1a.png)

#### Release Briefings :

In the release briefing section, each element of the list of flights created from flight planning data over a specified time period is displayed. To access the list, users are required to select the desired time period to initiate the search process. The system will then generate a list of corresponding flights, as well as a list of master users, a list of users, and a list of download times.

![](media/e377bd848670c617104fe329fe311afd.png)

### Document Reports

The document folder has been developed to facilitate the extraction and analysis of reports according to the following criteria:

-   **All documents:** This function is employed to summarize all documents, encompassing assignments, downloads, and read confirmations.
-   **Confirmation by role:** This feature enables the visualization of documents that have been confirmed by each role.
-   **Documents report:** This report provides a comprehensive overview of specific documents.
-   ![](media/355ebae944a62a3c992dbb657579e5fe.png)**Documents by role:** This report illustrates all documents that have been assigned to a particular role.

#### ![](media/24f17b7b72be5e27e826c6aacb37c4e5.png)All Documents Folder:

#### ![](media/016b6610b8c2a32cfd6b759bdddc148d.png)Confirmation by role:

#### Document report:

#### ![](media/f48285692a341e49b809b85082dfb49a.png)Documents by role:

![](media/78e4c47b065dd2805eaaffb5f1ac9c65.png)
