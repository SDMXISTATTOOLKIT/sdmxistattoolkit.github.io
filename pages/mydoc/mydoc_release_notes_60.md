---
title: Meta&Data Manager Release notes
tags: [getting_started]
keywords: release notes, announcements, what's new, new features
last_updated: January 29, 2021
sidebar: mydoc_sidebar
permalink: mydoc_release_notes_60.html
folder: mydoc
---

## Version 1.0.1 (Release date: April 20, 2020)
Release Date: 20 April 2020 <br>
DDB v.1.2 <br>
MASTORE v.6.7 <br>
AUTHDB v.1.1 <br>
RMDB v.1.2 <br>
MA WS v.1.24.9 (.NET CORE 2.2.5) <br>
NSI WS v.7.10.10 (.NET CORE 2.2.5) <br>
<i>The following bugs/improvements have been covered:</i> <br>
- fix on creating a filter on a coded attribute with no values available in the cube <br>
<U>Fixes for DCAT and Referential Metadata:</U> <br>
 - The validity check for reportingBegin - reportingEnd fields has been added <br>
 - All attributes of type "String" can be modified through the XHTML editor, with the possibility to switch to classic text (with zoom functionality) <br>
 - Added the possibility to zoom on the name of the MetadataSet <br>
 - All String and XHTML attributes are by default multilingual (the current annotation is ignored) <br>
 - If a report is exposed via API it will be read-only <br>
 - Removed the ability to add categories from the MetadataSet tree <br>
 - IDs from categories and attributes were removed when compiling the report <br>
 - After having saved a report it remains open <br>
 - The deletion of dataflows is not permitted when associated reports are present <br>
 - The HTML editor has been configured to allow the user to directly insert/edit HTML <br>
 - Added the management of the IsPresentational implementation associated to the MSD (checkbox in interface) <br>
 - Problems of slow compilation of attributes have been solved <br>
 - DCAT: catalog report deletion is prevented if dataflow reports are present <br>
 - DCAT: a new version of the MSD has been released <br>
 - DCAT: annotations and attachments have been removed from the compilation of attributes <br>

## Version 1.0.0 (Release date: March 20, 2020)
Release Date: 20 March 2020 <br>
DDB v.1.2 <br>
MASTORE v.6.7 <br>
AUTHDB v.1.1 <br>
RMDB v.1.2 <br>
MA WS v.1.24.9 (.NET CORE 2.2.5) <br>
NSI WS v.7.10.10 (.NET CORE 2.2.5) <br>
<br>
<i>The following bugs/improvements have been covered:</i> <br>
 - OBS_VALUE column in FactS table is now of type float instead of real <br>
 - fix bug on blank page on create artefact <br>
 - fix on AssociatedCube annotation when upgrading a cube <br>
 - fix on concurrent uploads management <br>
 - modified default configuration for NSI WS and MA WS (commented configLocation parameter) <br>
 - added new configuration parameter for timeouts of single web services <br>
 - added new applicative error for import of dsds referencing not final artefacts <br>
 - fix download in sdmx formats for very big dataflows <br>
 - fix download in CUSTOM CSV format for very big dataflows <br>
 - Derived ItemScheme: support for creation of hierarchical itemscheme derived not at root level <br>
 - Fixed a bug on creation of dataflows with header template <br>
 - Updated MA WS default configuration for supporting content constraint automatic creation while putting into production a dataflow <br>
 - New management of 'isFinal' field for artefacts in 'Export on remote ws' functionality <br>
 - Minor fix on codelist's items order management <br>
 - security fix on Recover Password functionality <br>
<U>Fixes for DCAT and Referential Metadata:</U><br>
 - It is now possible to save generic referential metadata reports without configuring the DCAT module first <br>
 - Support for OrganisationUnitScheme references in MSDs <br>
