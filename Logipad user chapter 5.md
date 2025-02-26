**![D:\\og-dd-logo-1200x628 (2).jpg](media/0606ca5628079ef13936db4fee95401c.jpeg)**

![D:\\csm_Logipad_Logo_rgb_6a9b8dd7a2.png](media/feb27d0a82e329ed73c7120de86f2efb.png)

**LOGIPAD USER MANUAL**

**![](media/ab36b643f45515574436c82d5c523443.png)**

Manual Code: LM- Logipad Team

Issue Number: 02, Issue date: 14 Feb 2025

Revision Number: 00, Revision date: 14 Feb 2025

Blank page

# EFB PRINCIPLE CREW PROCEDURES

## General

### The operator should have procedures for using the EFB in conjunction with the other flight deck equipment. The procedures should adress and focust on the following topics :

-   Which information source will be primary;
-   Which source will be used as secondary information;
-   Under what conditions to use the secondary source; and
-   What actions to take when information provided by an EFB does not agree with that from other flight deck sources, or, if more than one EFB is used, when one EFB disagrees with another.

### The Operators should include the requirements for EFB availability in the Operations Manual and/or as part of the minimum equipment list.

### Flight crews should not have to confirm the revision dates for other databases that would not adversely affect flight operations in case of outdated data. Procedures should specify what actions to take if the software applications or databases loaded on the EFB are out-of-date.

## Workload and Coordination

### In general, using an EFB should not increase crew’s workload during critical phases of flight. For other flight phases, crew operating procedures should be designed to mitigate and/or control additional workload created by using an EFB.

### Crews Workload should be distributed between flight crew members to ensure ease of use and continued monitoring of other flight crew functions and aircraft equipment. The procedures should include specification of the phases of flight at which the flight crew may not use the EFB, if applicable.

## Reporting

### A reporting system for EFB failures should be established. Procedures should be in place to inform maintenance and flight crews about a fault or failure of the EFB, including actions to isolate it until corrective action is taken.

## Recommendation practice for EFB admin procedures

### Data Generation and Validation before generated package

The EFB Administrator validates the data and flight plan data with Flight Dispatch Team, ensuring that it is complete, correct, and traceable. This includes verifying performance data, weather, NOTAMs, and any other relevant information which integrated with Logipad system

### Ensure that the release is sent to the Test Server prior to publishing:

Prior to updating the prod environment, the EFB Administrator publishes the new data on a test server first. This step allows for testing and minimizes operational risk in case of errors.

The system should log all updates to ensure traceability in the event of discrepancies.

### EFB Notification and Testing:

The EFB Administrator has informed the EFB Manager that new data is available on the backup server for validation. The EFB Manager or responsible parties should verify that all data are correct and current.

Once the EFB Manager confirms that the data is satisfactory, the EFB Administrator will publish the final data and release the EFB notification to all users. This notification will include a summary of the update information in each time release, the version number, and other pertinent details to ensure that flight data is always current.

If the data is unsatisfactory, it is sent back to the EFB Administrator for update new revision

The EFB Administrator continuously monitors synchronization through the Flight Manager portal, MUI to ensure that all end-users (flight crew, dispatch) update their devices. Any discrepancies must be addressed immediately.

### Back-up system :

Ensure a reliable backup system is in place for both the back-up server and manual processes (e.g., printed documents) in case of an EFB or system outage. This provides a fallback mechanism for dispatchers and flight crews to access critical flight data.

## Recommendation practice for Flight Crew procedures

### Pre- Flight Preparation :

Flight crews must synchronize their EFBs and cross-check with the EFB Notification, EFB New Data Package to ensure they have the latest data, including flight plans, weather updates, and ARINC 633 briefing packages. For Briefing Package. The crew team should always check the flight ID, master user information, city pair, with their roster schedule to ensure that they received the correct package from the flight planning system.

### In Flight updates :

During flight, it is the responsibility of the crew to gather and record any deviations from the planned flight path, performance, or weather conditions. This data is then entered into the EFF system or documented. The crew should cross-check with the flight checklist to ensure that no information has been missed. The master user is responsible for final checking and releasing the package when all information has been filled in.

### Post Flight Synchronization :

Following the flight, the crews will synchronize their EFBs with the Logipad server once more. This will ensure that all flights have been sent successfully for briefing and that the Eform has been released from Outlook. If necessary, the Eform will be resent. Consult with the EFB team to verify that all pertinent information regarding their duties has been thoroughly reviewed.

## Recommendation practice for OCC/ Flight Dispatch procedures

### Pre- Flight Preparation :

Flight dispatchers utilize the Flight Manager portal to prepare, verify, and manually dispatch flight packages to the crew. These packages include flight plans, NOTAMs, and performance data as required. Dispatchers must verify the accuracy of the data and coordinate with the EFB team to ensure that the crew has synchronized their devices prior to departure.

### In- Flight Monitoring :

Dispatchers are responsible for continuously monitoring flight progress through the Flight Manager portal with the EFB team in real time. They are also responsible for communicating any necessary changes to the crew, especially in cases of weather updates or route adjustments that require updated flight packages

### Post – Flight Data collection :

The dispatcher will coordinate with the EFB team to verify that all Logipad data is current and stored in the server. The data is stored in the central system and backed up to ensure full traceability for future auditing or operational review.
