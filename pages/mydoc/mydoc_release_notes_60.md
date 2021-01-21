---
title: Meta&Data Manager Release notes
tags: [getting_started]
keywords: release notes, announcements, what's new, new features
last_updated: December 03, 2020
sidebar: mydoc_sidebar
permalink: mydoc_release_notes_60.html
folder: mydoc
---

## Version 1.5.1 (Release date: December 03, 2020)

MDM v.1.5.1 (.NET CORE 3.1.0) <br>
Release Date: 02 December 2020 <br>
DDB v.1.3 <br>
MASTORE v.6.10 <br>
AUTHDB v.1.1 <br>
RMDB v.1.2 <br>
MA WS v.1.26.5 (.NET CORE 3.1.0) <br>
NSI WS v.7.13.2 (.NET CORE 3.1.0) <br>
<br>
<i>The following bugs/improvements have been covered:</i> <br>
ISTAT-205 - Dataflow Builder: added connection to Preview in Data Browser and inverted order of two action buttons <br>
ISTAT-300 - Fix on authiomatic update of Data Browser cache (push mode from MDM) <br>
ISTAT-417/2 - Fixed a bug on import attributes with tid <br>
ISTAT-428 - Modified NSI WS and MA WS log paths. <br>
ISTAT-no num - Fix on delete local codes: connection string for SqlServerExpress <br>

## Version 1.5.0 (Release date: November 13, 2020)

MDM v.1.5.0 (.NET CORE 3.1.0) <br>
Release Date: 13 November 2020 <br>
DDB v.1.3 <br>
MASTORE v.6.10 <br>
AUTHDB v.1.1 <br>
RMDB v.1.2 <br>
MA WS v.1.26.5 (.NET CORE 3.1.0) <br>
NSI WS v.7.13.2 (.NET CORE 3.1.0) <br>
<br>
<i>The following bugs/improvements have been covered:</i> <br>
ISTAT-18 - Filters: supported conditions with <= and >= <br>
ISTAT-65 - MDM Manual Updated <br>
ISTAT-67 - DSD: Search field has been enlarged <br>
ISTAT-68 - Upgrade DSD: 'IsFinal' field added to the report <br>
ISTAT-69 - Import Sdmx Artefacts: bold format for 'is final' field in report <br>
ISTAT-72 - Builder: added minimal information on TID <br>
ISTAT-79 - Compare DSD: added explicit message for identical DSDs or DSDs with identical codelists but different versions <br>
ISTAT-93 - Import Attribute File: new functionality implemented <br>
ISTAT-102 - Custom Csv Download: Data preview now takes into account not selected columns in Cube List and Dataflow Builder <br>
ISTAT-105 - DSD: annotation OCSE <br>
ISTAT-108 - Builder: Default Category Scheme Management <br>
ISTAT-149 - Loader: added request for confirmation before loading operation <br>
ISTAT-190 - Advanced filters: corrected a bug on selecting not present items while clicking on 'select descendants' button of an item <br>
ISTAT-200 - Table: codes can now be displayed in more than one row <br>
ISTAT-236 - Layout Annotations: support for 'Last N Periods' for the temporal dimension <br>
ISTAT-298 - Dataflow Builder: support for filtering dataflow when downloading in SDMX formats <br>
ISTAT-300 - Invalidation of Data Browser cache with push modality <br>
ISTAT-310 - Annotations: bug on creation of layout annotations on dataflows without any other annotation <br>
ISTAT-311 - Annotations: added default layout annotations for graphs and maps <br>
ISTAT-313 - Import Sdmx Artefacts: 'isFinal' field is always true <br>
ISTAT-316 - Virtual dataflow: they actually use an ad hoc dsd (temporary workaround) <br>
ISTAT-318 - General Layout Annotation: added annotation for hiding a dataflow in the catalogue <br>
ISTAT-321 - Annotation Default Items: possibility to specify a range of dates and 'Last N Periods' option <br>
ISTAT-353 - EmptyCube: removed constraint on not being present any connected dataflow <br>
ISTAT-376 - Bug on random duplication of hundreds of annotations while modyfing layout annotations on dataflow <br>
ISTAT-401 - ItemScheme: fix bug on import csv files with special characters <br>
ISTAT-402 - DataflowBuilder: now local codes and related records in table ITEM are deleted while deleting transcodings <br>
ISTAT-403 - DataflowBuilder: accessing dataset directly through its dedicated view instead through view's definition <br>
ISTAT-no num - Proxy password is now saved encrypted <br>

## Version 1.4.1 (Release date: September 22, 2020)

MDM v.1.4.1 (.NET CORE 3.1.0) <br>
Release Date: 22 September 2020 <br>
DDB v.1.3 <br>
MASTORE v.6.10 <br>
AUTHDB v.1.1 <br>
RMDB v.1.2 <br>
MA WS v.1.26.5 (.NET CORE 3.1.0) <br>
NSI WS v.7.13.2 (.NET CORE 3.1.0) <br>
<br>
<i>The following bugs/improvements have been covered:</i> <br>
- assignment of ownership to the current user for all the artefacts loaded through the "import structures" utility <br>

## Version 1.4.0 (Release date: September 15, 2020)

MDM v.1.4.0 (.NET CORE 3.1.0) <br>
Release Date: 15 September 2020 <br>
DDB v.1.3 <br> 
MASTORE v.6.10 <br>
AUTHDB v.1.1 <br>
RMDB v.1.2 <br>
MA WS v.1.26.5 (.NET CORE 3.1.0) <br>
NSI WS v.7.13.2 (.NET CORE 3.1.0) <br>
<br>
<i>The following bugs/improvements have been covered:</i> <br>
ISTAT-7 - Download with referenced artefacts is now requested with 'Descendants' parameter <br>
ISTAT-202 - Added LAST_UPDATE annotation for cache improvement <br>
ISTAT-206 - Bug on selection and import of hierarchical codelists <br>
ISTAT-226 - Support for creating virtual dataflow <br>

## Version 1.3.0 (Release date: August 03, 2020)
Release Date: 3 August 2020 <br>
DDB v.1.3 <br>
MASTORE v.6.9 <br>
AUTHDB v.1.1 <br>
RMDB v.1.2 <br>
MA WS v.1.26.1 (.NET CORE 3.1.0) <br>
NSI WS v.7.12.1 (.NET CORE 3.1.0) <br>
<br>
<i>The following bugs/improvements have been covered:</i> <br>
ISTAT-62 - Improvement copy on remote ws <br>
ISTAT-64 - Cube list: added refernces to FiltS and FactS tables <br>
ISTAT-66 - Modified label for Custom Annotations <br>
ISTAT-107 - Manage Series functionality <br>
ISTAT-159 - New agency management: new button to add an agency in current node's configuration available for the superuser <br>
ISTAT-187 - Bug on long codelists not showing correctly <br>
ISTAT-188 - Bug fix on 'CanManageWorkingAnnotation' which did not let publish or modify dataflows <br>
ISTAT-192 - Multirow table also for layout annotations and other long columns <br>
Bug fix on download cubes or dataflow in 'Custom csv' format returning an empty file <br>
Support for loading xml files also in new format (StructureUsage tag instead of Structure) <br>
DDB Reset - permission on cubes in the AuthDB are now reset <br>
Modifies for new policy on browsers' cookies <br>
Not displayed annotation - graphical fix for long inputs and added warning for maximum length (4000 chars) <br>

## Version 1.2.0 (Release date: July 03, 2020)
Release Date: 3 July 2020 <br>
DDB v.1.3 <br>
MASTORE v.6.9 <br>
AUTHDB v.1.1 <br>
RMDB v.1.2 <br>
MA WS v.1.26.1 (.NET CORE 3.1.0) <br>
NSI WS v.7.12.1 (.NET CORE 3.1.0) <br>
<br>
<i>The following bugs/improvements have been covered:</i> <br>
Fix on security (reported from version 1.0.1_SECURITY) <br>
Fix on long filters <br>
Fix on deselecting dimension in Dataflow Builder: not allowed if it is part of a group <br>
ISTAT-5 Various fixes on annotations: <br>
	- management MM side of the annotations <br>
	- zoom on all text fields  <br>
	- add multiple attached data files <br>
	- multilingual for metadata URL, attached data files, dataflow notes <br>
	- add format for URL <br>
	- ISTAT-6: text truncated in 'Attached data file' <br>
ISTAT-13 Modified default configuration for ORDER annotation, default agencies and parameters for pagination <br>
ISTAT-55 id and type are not mandatory for annotations any more <br>
ISTAT-56 message on loader's report stating only the first error for each row is shown <br>
ISTAT-60 Mapping sets are now orderrf from the oldest to the newest <br>
ISTAT-74 bug fix for creating a content-constraint from a DSD without attributes <br>
ISTAT-85 added permission to manage 'work annotation' <br>
ISTAT-94 Check on coded observation values during loading <br>
ISTAT-95 added annotation for categorisations' order <br>
ISTAT-96 Support for multirow table <br>
ISTAT-98 support for new version of NSI WS and WS implemented in .Net Core 3.1 <br>
ISTAT-99 Support for architectural scenario whith read/write access to MDM without installing a DDB/RMDB <br>
ISTAT-99 Support for installing both MSDB and DDB on the same database <br>
ISTAT-99 Support for having Oracle MSDB <br>
ISTAT-103 Difference in number of codelists' item in Simple and Advanced Filter <br>
ISTAT-104 Fix on download codelist CL_SERIES in csv format <br>
STAT-166 Various improvements on layout annotations <br>
ISTAT-186 Bug on empty codes in Advanced Filters (Dataflow Builder) <br>
<br>
<U> DCAT and Referential Metadata:</U> <br>
Bugs solved: <br>
- Corrupted images in the DCAT-AP_EN catalog <br>
- The HTML editor does not remember whether a field was compiled in HTML or flat text mode <br>
- The deletion of a field affects the compilation of the others (it doesn't let you fill in anything anymore) <br>
- In the attributes tree you lose values when you change language or settings <br>
- In the DCAT report (HTML widget) there is not all the information in the package_show <br> 
small improvements: <br>
- Edited some MSD labels <br>
- Added the "CL_" prefix for Codelist in the DCAT MSD (MSD) <br>
- Removed complete URIs from the interface <br>
- Added all licenses in the controlled vocabulary: https://github.com/italia/daf-ontologie-vocabolari-controllati/blob/master/VocabolariControllati/licences/licences.csv <br>
- Removed the "DCAT_AP_LICENSE_TYPE" attribute from the MSD, which is no longer referenced <br>
- Added (sequential) numbers to attributes in reports <br>
New features: <br>
- New architecture support (the HTML widget has API Metadata as its only dependency and structural metadata is retrieved from API Metadata via API Node; a cache has also been introduced, both on structural and referential metadata) <br>


## Version 1.1.0 (Release date: May 19, 2020)
Release Date: 19 May 2020 <br>
DDB v.1.2 <br>
MASTORE v.6.7 <br>
AUTHDB v.1.1 <br>
RMDB v.1.2 <br>
MA WS v.1.24.9 (.NET CORE 2.2.5) <br><br>
NSI WS v.7.10.10 (.NET CORE 2.2.5) <br> 
<br>
<i>The following bugs/improvements have been covered:</i> <br>
- new management of Dataset level attributes <br>
- Loader: added check for coherence of attributes in Filt table <br>
- loading: delete FactS_TEMP table if empty <br>
- fix on CatDataflow > 500 char <br>
- Modified layout annotation (DM side) and added new ones <br> 
- Added the possibility to use '-' char in IDs <br>
- Blocking error for conflict at attribute level <br>
- Added items' codes in Dataflow Builder - Filters (advanced mode) <br>
- Fix on export of artefacts with referenced organization schemes: “Organisation Schemes can not be set to final” <br>
- Support for Trusted Connection <br>
- MM: implementation of Hierarchical Codelist (only at stub level) <br>

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
