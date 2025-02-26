**![D:\\og-dd-logo-1200x628 (2).jpg](media/0606ca5628079ef13936db4fee95401c.jpeg)**

![D:\\csm_Logipad_Logo_rgb_6a9b8dd7a2.png](media/feb27d0a82e329ed73c7120de86f2efb.png)

**LOGIPAD USER MANUAL**

**![](media/ab36b643f45515574436c82d5c523443.png)**

Manual Code: LM- Logipad Team

Issue Number: 02, Issue date: 14 Feb 2025

Revision Number: 00, Revision date: 14 Feb 2025

Blank page

# LOGIPAD MODULES

## OVERVIEW :

Logipad Solution including the followings 3 modules:

**Documentation module:** The airline's document management system enables users to display, manage, mark documents with priorities assigned, provision documents to content roles, make remarks for various types of documents (PDFs, XMLs, WORDs,…), and distribute operational documentation. The operational documentation includes both manufacture and operator manuals.

**Briefing Module:** The electronic briefing system provides pilots with a series of folders containing essential information such as the Operational Flight Plan (OFP), weather updates, Notice to Airmen (NOTAM), Loadsheet information, NOTOC and any additional details required. The system has a flexible layout and structure to ensure that all information is presented in a clear and logical manner.

**Eform module:** The Digital Forms solution allows you to create your own electronic forms in an intuitive and logical way using a drag-and-drop editor or by using existing templates. The modules can be used for web services, IOS devices and direct synchronization between different devices and platforms, increasing the efficiency of air-to-ground communication management.

## DOCUMENTATION MODULE :

One of the central points of Logipad is the management and role based provisioning of documents.

Documents can be additionally equipped with further attributes to extend their organization. Available functions:

• Provision documents to content roles

• Mark documents with flags

– Confirmable

– Exportable

– Indexable

• Priorities for documents can be assigned

• Control whether the documents should be opened in the app or in an external application

• Control unit to publish the documents time-controlled. “Valid from:” and “Valid until:” fields.

• Comment function for the internal description

• Control to turn on the inventory when opening the document

The system allows the publishing of different content types like:

• video

• txt

• epub

• zip

• pd

• video

• txt

• epub

• zip

• pdf

• htmlzip

• html

• doc

• docx

• xls

• xlsx

• ppt

• pptx

### Organize documents

![](media/8cd5d7afc1f4f324020fb79e90b08c3f.emf)Documents are organized in a folder structure. A Folder can be associated with a document template to assign standard properties.

The two icons at the top right-hand side activate the Folder View or the Document View.

-   ![](media/3672be96da21cf177a1fd0af1445cebe.png) Folder view

    Will show the folder structure with subfolders and files.

    -   ![](media/495c7b16adef0d4e98da6ccb1398260b.png)Document view

        display all documents (including documents within subfolders).

### Document templates

Document templates define a set of properties/settings that later will automatically be applied to new documents.

The first button *Create new Document* is a dropdown select button. The standard selection is *Create new Document*. Other options are:

• Upload multiple documents

• Document Types

• Document Templates

![](media/fcdc0a5b6c849f643e0b308f660262c4.png)

If Document Templates is selected, a Document Template is created to associate default properties once a document is assigned to that template

![](media/abb2423a30762a21bf9be5b79919bc95.png)

### Create Folder

![](media/9cd096b104d0176542fe214b31aef8c6.png)

The main attribute of the folder is the Display Name additionally a document template can be assigned.

If you don’t assign a template the folder will inherit the template of the parent folder. Access Rules are used to limit administrative access.

### Publish a single document

![](media/05ff79ed8c3ff45a46e7296e98e588ca.emf)

A document has two sections of attributes:

• Document attributes

– Display Name

– Folder

– Content Roles

– Document Type

– State

– Document Priority

– Confirmable

Only if ‘Confirmable’ is activated the ‘read confirmation required’ will be activated on the

version.

– Indexable

Included in fulltext index.

– Exportable

User can print the document and export it to other apps.

– Open in External App

• Version attributes

– Revision

– Is visible

– Valid from

– Valid To

– Comment

– Require read confirmation

### Publisher multiple documents

![](media/b737a8459f36d22b189a69a92a869926.png)

You can select the document with a file dialog or use “Drag and drop”.

During the upload you can only assign some attributes.

• Folder

The default folder for the upload is where you started the dialog.

• Use folder template

Should an existing template be applied

• Comment

• State

## BRIEFING MODULE :

The Electronic Flight Folder contains flight plans, NOTAMs, weather charts and additional flight information, structured according to our customer's operational manual and briefing definition and fully compliant with the ARINC 633-2 standard. Briefing data can be exchanged between multiple devices and platforms. The management of your data can also be customized, such as fuel consumption data and the corresponding prices stored in the backend. The data can be transferred to other systems, such as for fuel optimization. Additional information can be collected via separate sections or self-built eForms.

### User interface layout :

#### Logipad Navigation bar :

Logipad Navigation bar are implemented in the following section :

Home Screen:

General update, Review Updated information and notification section for all modules

Briefing section

The data transmitted to your EFB application and into the Logipad app is called a Briefing. A Briefing contains all flight scheduling data, such as aircraft status, flight plan information, and weather charts. The Briefing section allows you to activate, finalize and collect all flight relevant data. It also ensures real-time updates between crews.

### Briefing info and standards layout concept

#### Briefing Info

This is the Briefing main page, here you can find an overview of the active Leg and navigate the different flight phase modules:

-   Flight summary (Basic Trip summary info)
-   OFP
-   Weather & NOTAMs
-   Weather Charts
-   Flight Data
-   Additional Documents

###### Flight Summary

The section contains General info of OFP from Flight Planning system source regarding to the following topic:

-   Flight Scheduling Data (Date & Time, Date, A/C registration)
-   Flight Planning Data
-   Document/ Crew Infor
-   Flight release acceptance and remark

![](media/3b8abae1142d0ec2fa981468a2623bd7.png)

###### Weather & NOTAMs

The section in Briefing Package contains all information from Operator weather data source (PPS system or Independent sources) . All information have been handle and transfer with Logipad MUI platform which generates to general Briefing package (ARINC format compliance)

-   Airport Weather : ( Destination, Departure and Alternate Airport ) METAR & TAF reports
-   Wx Charts (Different charts / SIG / Winds Aloft / etc., as planned)

![](media/45f053100dd1f5946418696f85b3c076.png)

###### Flight Data

The section in Briefing Package contains all information for dispatch, monitor the progress the flight and all relevant data as Operator’s Layout (Alternate Route, Plotting Chart, ATC Flight Plan, Fuel & Mass) regarding the following section:

-   Pre- Flight
-   In- Flight
-   Post- Flight

###### Additional Documents

This section is used to provide additional documents previously received in paper format (Permit docs, Loadsheet, NOTOC,Paper Flight Plan…)

![](media/243c8d0831db394ee0f3f3251a29dee5.png)

#### Data Entry Field/ What need to know ?

Logipad EFB solution using a set of different entry field in order to support users while using App.

-   Mandatory Entry Field :

    Entry fields with a red frame are mandatory fields and must contain a value before the briefing can be processed

-   Optional Entry Field :

    Entry fields with a green frame are optional fields and contain a references information for the flight

-   Data Entry Format Restriction :

    ![](media/985bc21bc406810c6f16dc91263f0302.png)Whenever you see a data entry format like DD.MM.YY or hh:mm you must followed the format to entry into the field

### Briefing package / Activated and transfer data during the flight

#### How to active a Briefing.

Before you can enter and modify data inside a Briefing, the Briefing needs to be activated. Activation can be done by the Master User or by the Non-Master User. After activation, the Briefing icon is green coloured.

![](media/aa5d5ae6bbb2b36c01019ec354074b90.png)

###### Role: Master User

![](media/5a7c968a6b000f4eb5d74b50b68ed5fe.png)This is the user responsible to finalize and send the completed Briefing. In general, the PIC is assigned to the “Master User” role. The crown above the briefing icon indicates the assigned “Master User” role.

###### Role: Non- Master Use

![](media/a47f2c0e17e186a685c72e96f230dab8.png)The “Non-Master” user does not own a crown. In general, the F/O is assigned to the “Non-Master” role and cannot “finalize” a Briefing

The Master-User and Non-Master User concept assures that only complete data collected from both devices are sent to the server (single channel concept)

###### To Activate a Briefing as a Master User (Briefing icon with Crow icon)

-   ![](media/a2ef8a2f95eb1a081edd5e5a858abc9f.png)First press on “Briefings” in the Navigation Bar to see the relevant briefings assigned to you
-   Then, on the relevant Briefing, press on the three little dots on the right-hand side and press “Activate master copy”
-   Press “Activate” and observe the briefing Icon status change from yellow “ready” to green “active![](media/3755a8c06750b18bf8828d0b00bbc20b.png)”

![](media/d76defcc54d65fa1db17a92f6765ef01.png)

###### How to active a Briefing as a non-Master User (briefing Icon without Crow)

-   ![](media/a2ef8a2f95eb1a081edd5e5a858abc9f.png)First press on “Briefings” in the Navigation Bar to see the relevant briefings assigned to you
-   Then, on the relevant Briefing, press on the three little dots on the right-hand side and press “Activate non master copy”

![](media/e18da8560468d1f5cf8038852dd63ef2.png)

-   Press “Activate” and observe the briefing Icon status change from yellow “ready” to green “active”

    ![](media/d76defcc54d65fa1db17a92f6765ef01.png)  **Important**

    If the Non-Master User is activating the Briefing, and does all the entries for the trip, then he/she must transfer the briefing to the Master-User Device at the end of the flight, in order to perform the “finalization” of the Briefing. Only the **Master-User** can finalize and send a briefing.

#### Roll Back Briefing Activation

If for any reason you need to roll back a briefing activation (activation of the wrong flight or troubleshooting), here you can find the necessary steps to do so.

-   ![](media/f9ab351a1ec3400cea9d65a95ae8f8a2.png)![](media/4ca4bb237b64f37b6ffc95cc0f0dc163.png)![](media/455fbf9ac04a109512ec119d2f012376.jpeg)Press the information icon to see the briefing properties
-   ![](media/ddcafccd99f754ecd3c572cc2258095f.png)Press the energy icon to see the briefing Actions
-   Press ‘’Roll back activation’’ button
-   ![](media/bc12ca61cd5526019da394b9845cec8d.png)Confirm and check that the briefing status reverts to the yellow “ready” state

#### ![](media/ae230f22ceb55c89c09b2d00f5080d05.png)Real time Sync and Data exchanged

Logipad automatically detects all other devices nearby. Logipad selects the best possible available connection (Bluetooth, Access Point, or Wi-Fi Direct) and establishes a connection in the background, automatically synchronizing data in real-time which is entered by pilots. You can save times and effort for flight operation between Master user and Non-Master user accounts. In addition to connectors, we have developed easy-to-use functions to transfer data to other applications. Performance data from other applications can be imported into Logipad or vice versa. You can exchange data with other applications, provided this is supported by third-party vendors. The steps to steps

For the briefing active data exchanged betwen crews, the connection between the two devices must been established.

-   Press the communication icon ![](media/ac91b8c35b02f6880ce176cdb76a2038.png) in the sending data devices

![](media/603c7dc3606c8955c2daf4f970b5670e.png)

-   Press accept on the receiving device

![](media/ae7574a97b1371c1f2d4223c0847e2d3.png)

-   A successfully established connection is indicated by a green band on both devices.

    ![](media/7dcabc1fe6b1fdb8841988d4095461f9.png)

-   ![](media/c96dba96491698187195562190db3032.png)To get the transfer option press on the three dots

![](media/43d7b08e977ca6f7e6c965e1915e231a.png)

-   To hand over the “active briefing” and, therefore, make it possible for your colleague to enter data (e.g. for a flight log, RVSM checklist & fuel entry), press here
-   To back up data on the other device (e.g. after a waypoint check), press here (only data is sent to the other device, the activation of the briefing remains on your device)
-   “**Failover copy**” is the new status of the briefing that remains on your EFB after transferring the “active briefing” to another device. This is a redundant copy with the data stored before transferring the “active briefing” to your colleague’s EFB. The “failover copy” can be activated in case the “active briefing on the other device becomes corrupted or if there is a hardware failure.

IMPORTANT: When an active briefing is transmitted, the briefing on the sending device (“failover copy”), becomes “read only” and the briefing on the receiving EFB becomes “active”, and is the only briefing that can accept crew inputs.

If the Non-Master User is activating the Briefing, and does all the entries for the trip, then he/she must transfer the briefing to the Master-User Device at the end of the flight, in order to perform the “finalization” of the Briefing. Only the **Master-User** can finalize and send a briefing.

#### Force Failover Function/ Transfer role between devices for abnormal operation

If the sending devices ( non-master users) unbale to transfer briefingd data due to connection, you can using the “Force Failover” function. This function allows the “Non-Master User” to become the “Master User” and therefore, finalize and send the Briefing. In order to do so please follow the steps to steps as bellow:

-   Tap “ information” ![](media/06c3471df25b4f2226622cc978ac41b6.png) icon for briefing properties

![](media/0be2335bb178d31fa0794e3414a5a71a.png)

-   Tap ‘’enery ‘’ icon ![](media/35f67cb33a09fdba0fa4992cd207c9ef.png) for Briefing actions
-   Tap “ Force failover” button

![](media/8ebf29ea770a13df97a41c45436d12de.png)

## EFORMS MODULE :

### Overview :

The Digital Forms solution allows you to create your own electronic forms in an intuitive and logical way using a drag-and-drop editor or by using existing templates

Logipad offers 3 subsidinary applications to for generated E- Forms templated, Data entry field in the template and send, Data collection and analysis as followed:

-   E- Forms Generator (Creating the operational form templated by your own)
-   E-Form Modules (To view, Entry field in and send Operational Forms when needed)
-   Report view dashboard (For post flight reports data collection)

### eForm Generator :

The Digital Forms solution allows users to easily and intuitively create custom electronic forms using either a drag-and-drop editor or pre-existing templates. The tools working in Computer tools and direct sync with Eform modules in EFB devices for templated updated.

-   General ERP ![](media/58a4a71099e9c3b32f06432b2ddfbe2a.png) function :

    ![](media/9e49b8635094ef54db6f4d72a87e5eef.png)With the General section you are able to see total existing Eform template on Logipad System, retrieve previous erp templated and re-updated in case you need modified, dowload erp, export files and erp template or created your new template

-   Editable ![](media/c78abcbfadb2cefbf9c741e05d9184b8.png) function :

    With Editable function you can able start to create your operation digital templated by your own requirement with out Coding. Our dynamics field have been deploy to support for you.

    The dynamic field have been set in 4 different fields with different purposes :

-   Layout- Created Section, Row for Eform
-   Input control- Created text area, time & date picker, select and input
-   Buttons – Created buttons for Radio and Checkbox
-   Views- Created table, Dynamic table, Navtab,..
-   \------- Created support field for Draw, picture attached or Signature signed

![](media/c69688d29d945d6682b9263b80eccb49.png)

-   eForms Calculations :

    The Editable function allows you to easily select the calculation method and field you want, and the result will be updated accordingly.

![](media/43397a3bfb7c9f9d95d205eb3e0b3661.png)

The eForms module offers several subfunctions for calculations :

-   **Time Difference** for effortless time conversion and calculation,
-   **Date Time Difference** for calculating the duration between two dates,
-   **Number Sum** for easily summing numbers without a traditional calculator,.
-   **Number Difference** : Subtraction the number easily without tradition calculator

![](media/668259db4e1a434aa3477178ca4c8b92.png)
