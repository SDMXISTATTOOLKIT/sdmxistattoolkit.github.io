---
title: Meta&Data Manager Release notes
tags: [getting_started]
keywords: release notes, announcements, what's new, new features
last_updated: January 29, 2021
sidebar: mydoc_sidebar
permalink: mydoc_release_notes_60.html
folder: mydoc
---
## Version 2.1.10 (Release Date: November 30, 2023)
MDM v.2.1.10 (.NET 6) <br>
Release Date: 30 November 2023 <br>
DDB v.1.5 <br>
MASTORE v.6.20 <br>
AUTHDB v.1.0 <br>
RMDB v.1.5 <br>
MA WS v.8.15.1 (.NET 6) <br>
NSI WS v.8.15.1 (.NET 6) <br>
<br>
<i> The following bugs/improvements have been covered:</i> <br>
MDM-11: Mapping Handler <br>
MDM-12: Import structure files in sdmx 2.0 format <br>
Mapping Set: Validation errors are now shown paginated <br>
Improvement Mapping: possibility to rename and edit new calculated fields <br>
Improvement Mapping: two messages added in Enable Transformations (initial warning and final report) <br>
Improvement Mapping: possibility to select the operator in IIS and CASE function wizard <br>
Improvement Mapping: possibility to select a field as value in IIS and CASE function wizard <br>
Improvement Mapping: new "Add Condition" button and 'AND/OR' operators added in IIF function wizard <br>
Improvement Mapping: enabled IIF, "CASE" and "FILE" features <br>
Mapping Set: the selected Connection and Dataset now appear in the wizard header <br>
Improvement Mapping: possibility to select and modify the order of the fields in preview and download of the processed dataset <br>
Improvement Mapping: new "Enable Transformations" button added in order to allow the creation of calculated fields <br>
Loader: import data with calculated fields <br>
Loader: new endpoint added in order to include new calculated fields in csv file; if the mapping file does not contain calculated fields, data will be imported with current endpoint <br>
Mapping Set: pagination implemented when viewing the items of the Codelist associated with the component to define the transcoding <br>
Dataflow Publishing: cross sectional 2.0 download implemented <br>
Dataflow Builder: cross sectional 2.0 download implemented <br>
Annotation: set new annotations as working annotation <br>
Improvement Mapping: new “Download” button added in Processed Dataset and Preview <br> 
Improvement Mapping: added the ability to download and import rules file <br>
Improvement Mapping: calculated field used in another calculated field <br>
Improvement Mapping: calculated field visible in the field list of the function page <br>
Improvement Mapping: fixed bug when importing large files <br>
Improvement Mapping: fixed bug when entering fixed values <br>
Improvement Mapping: Replace function with blank value <br>
Improvement Mapping: Substring function with negative values <br>
Dataset Builder: changed the display of the Dataflow and Datacube name <br>
Mapping Set: added the ability to download errors in Data Validation <br>
Import DSD 2.0: managed DSD 2.1 and 2.0 loading <br>

## Version 1.9.0, 1.9.1, 1.9.2, 1.9.3 (Release Date: November 14, 2022 - February 28, 2023)
MDM v.1.9.0 (.NET CORE 3.1) <br>
Release Date: 14 November 2022 <br>
DDB v.1.5 <br>
MASTORE v.6.15 <br>
AUTHDB v.1.0 <br>
RMDB v.1.5 <br>
MA WS v.8.4.1 (.NET CORE 3.1) <br>
NSI WS v.8.4.1 (.NET CORE 3.1)
<br>
<i> The following bugs/improvements have been covered:</i> <br>
Mantaining categorisation when upgrading a dsd <br>
Mapping/Loading - components of a mapping with fixed, calculated or concatenated values <br>
Possibility to create more than a linked dataflow from the same real dataflow <br>
Possibility to create multiple categorisations from "Category-schemes and dataflows" page <br>
Eliminate corrispondent files when a cube is deleted <br>
Allow modification of referred codelist and conceptschemes from inside a DSD <br>
Mapping XML for Multisheet Excel files <br>
Calculation of LastUpdate date for a dataflow <br>
Make password change policies configurable <br>
Improvement of annotation configuration (possibility to define ID and type to use separately) <br>
Possibility to configure footer, homepage and logo of the application <br>
Possibility to manage default values for the configuration of nodes <br>
New user permission management in session to not exceed request headers size <br>
Parameter to show the side menu expanded when opening the application <br>
Annnotation for management of HCLs in Dataflows and DSDs <br>
Import cc from file for data validation in loading <br>
Allow to create file mappings without mapping the OBS_VALUE cube component <br>
Possibility to selectively delete/modify records in a cube <br>


## Version 1.8.4 (Release Date: August 31, 2022)
MDM v.1.8.4 (.NET CORE 3.1) <br>
Release Date: 31 August 2022 <br>
DDB v.1.4 <br>
MASTORE v.6.15 <br>
AUTHDB v.1.0 <br>
RMDB v.1.2 <br>
MA WS v.8.4.1 (.NET CORE 3.1) <br>
NSI WS v.8.4.1 (.NET CORE 3.1) <br>
<br>
<i> The following bugs/improvements have been covered:</i> <br>
SDMX-ML export: populating the header's Name tag with the name of the header metadataset <br>

## Version 1.8.3 (Release Date: July 27, 2022)
MDM v.1.8.3 (.NET CORE 3.1) <br>
Release Date: 27 July 2022 <br>
DDB v.1.4 <br>
MASTORE v.6.15 <br>
AUTHDB v.1.0 <br>
RMDB v.1.2 <br>
MA WS v.8.4.1 (.NET CORE 3.1) <br>
NSI WS v.8.4.1 (.NET CORE 3.1) <br>
<br>
<i> The following bugs/improvements have been covered:</i> <br>
Modification of metadataset and report export function in SDMX-ML 2.0 for import into Metadata Handler <br>
Now all the possible items for a dimension or an attribute are always shown while creating a cc <br>
Removing HTML encoding within non-XHTML attributes <br>
Import "NaN" values as strings in cubes with alphanumeric observation values <br>
Modification to the authorization's mechanism <br>

## Version 1.8.1 (Release Date: April 8, 2022)
MDM v.1.8.1 (.NET CORE 3.1) <br>
Release Date: 08 April 2022 <br>
DDB v.1.4 <br>
MASTORE v.6.15 <br>
AUTHDB v.1.0 <br>
RMDB v.1.2 <br>
MA WS v.8.4.1 (.NET CORE 3.1) <br>
NSI WS v.8.4.1 (.NET CORE 3.1) <br>
<br>
<i> The following bugs/improvements have been covered:</i> <br>
Validate input from CC: now all cc built on dataflows using the same dsd of the cube are shown <br>


## Version 1.8.0 (Release Date: February 25, 2022)
MDM v.1.8.0 (.NET CORE 3.1) <br>
Release Date: 25 February 2022 <br>
DDB v.1.4 <br>
MASTORE v.6.15 <br>
AUTHDB v.1.0 <br>
RMDB v.1.2 <br>
MA WS v.8.4.1 (.NET CORE 3.1) <br>
NSI WS v.8.4.1 (.NET CORE 3.1) <br>
<br>
<i> The following bugs/improvements have been covered:</i> <br>
Improving Upgrade DSD functionality with support for adding conditional attributes <br>
Creating Content Constraints from file and validation through them in Loading <br>
Support for authomatic creation of Content Constraints for a dataflow from transcoding also without admin permission <br>
Dataflow Builder Publishing - Possibility to create either actual or allowed Content Constraints <br>


## Version 1.7.3 (Release Date: February 10, 2022)
MDM v.1.7.3 (.NET CORE 3.1) <br>
Release Date: 10 February 2022 <br>
DDB v.1.4 <br>
MASTORE v.6.15 <br>
AUTHDB v.1.0 <br>
RMDB v.1.2 <br>
MA WS v.8.4.1 (.NET CORE 3.1) <br>
NSI WS v.8.4.1 (.NET CORE 3.1) <br>
<br>
Improvement of security policies for changing passwords.<br>


## Version 1.7.2 (Release Date: December 6, 2021)
MDM v.1.7.2 (.NET CORE 3.1) <br>
Release Date: 6 December 2021 <br>
DDB v.1.4 <br>
MASTORE v.6.15 <br>
AUTHDB v.1.0 <br>
RMDB v.1.2 <br>
MA WS v.8.4.1 (.NET CORE 3.1) <br>
NSI WS v.8.4.1 (.NET CORE 3.1) <br>
<br>
Merge versions 1.7.1 and 1.6.3. <br>
Reference metadata module is now included in the main release line.<br>


## Version 1.6.3 (Release Date: November 12, 2021)
MDM v.1.6.3 (.NET CORE 3.1.0) <br>
Release Date: 12 November 2021 <br>
DDB v.1.3 <br>
MASTORE v.6.10 <br>
AUTHDB v.1.0 <br>
RMDB v.1.2 <br>
MA WS v.1.26.5 (.NET CORE 3.1.0) <br>
NSI WS v.7.13.2 (.NET CORE 3.1.0) <br>
<br>
<i> The following bugs/improvements have been covered:</i> <br>
BUGFIX: fixed the generation of <TargetValues> in SDMX-ML2.0 format <br>
BUGFIX: fixed the generation of <MetadataStructureAgencyRef> in SDMX-ML2.0 format <br>
BUGFIX: solved the url generation for the single dataflow reports (catalog widget) <br>
BUGFIX: solved the numbering present in the report summary <br>
BUGFIX: corrected the behavior of clicking on the "open information page" button of the metadataset <br>
The single report can now be downloaded in SDMX-ML 2.0 format <br>
The download of the entire metadataset in sdmx-ml 2.0 format has been removed (since the SDMX 2.0 standard, unlike SDMX 2.1, required a 1:1 association between report and Metadataset) <br>
Updated the manual, specifying the sender id customization key for the reports generated (key "EXPORT_RM_SDMX_SENDER_ID" in the appsettings of NODE_API and METADATA_API) <br>
The ID tag in the header of the sdmx-ml 2.0 report export is now set to the id of the report <br>

## Version 1.7.1 (Release Date: November 3, 2021)
MDM v.1.7.1 (.NET CORE 3.1) <br>
Release Date: 3 November 2021 <br>
DDB v.1.4 <br>
MASTORE v.6.15 <br>
AUTHDB v.1.0 <br>
RMDB v.1.2 <br>
MA WS v.8.4.1 (.NET CORE 3.1) <br>
NSI WS v.8.4.1 (.NET CORE 3.1) <br>
<br>
<i> The following bugs and small improvements have been covered:</i> <br>
ISTAT-734 - Functionality "Update Data Browser Cache" now updates catalog cache only <br>
Fix bug on preview on pc-axis file columns <br>
Dataflow Builder: 'Force cache update' button is now disabled if the user has no rights on Dataflow Production <br>
html documentation is now directly accessible from the client under "docs" subfolder <br>
configLocation parameter in NSI WS default configuration file has been commented <br>
in the client config file an example url of the Node Api WS has been added <br>

## Version 1.6.2 (Release Date: October 22, 2021)
MDM v.1.6.2 (.NET CORE 3.1.0) <br>
Release Date: 22 October 2021 <br>
DDB v.1.3 <br>
MASTORE v.6.10 <br>
AUTHDB v.1.0 <br>
RMDB v.1.2 <br>
MA WS v.1.26.5 (.NET CORE 3.1.0) <br>
NSI WS v.7.13.2 (.NET CORE 3.1.0) <br>
<br>
<i> The following bugs/improvements have been covered:</i> <br>
ISTAT-139 Report import/export functionality added <br>
ISTAT-733 Added the possibility to clone single reports within the same Metadataset <br>
ISTAT-702 All URL type fields will be fillable in multi-language <br>
ISTAT-703 The sub-theme has been removed as a dedicated field in the MSD and the categorization (on two levels) is managed hierarchically by the single "theme" field <br>
ISTAT-707 In the catalog widget (data list) the HTML formatting of the dataflow description is maintained ("Dataset description" field) <br>
ISTAT-708 Changing the language in the catalog and dataflow widget reloads the same page in the selected language, avoiding going back to the home page. <br>
ISTAT-715 Removed metadataset information (useless to the end user) in the header of catalog and dataflow (DCAT) widgets <br>
ISTAT-711 BUGFIX: for multilingual fields the behavior when opening the zoom, which was not initialized with the current language, has been corrected <br>
ISTAT-712 BUGFIX: the selection of an artifact in the compilation of a report now considers possible rights of the user on the specific agency <br>
ISTAT-705 BUGFIX: the numbering of hierarchical attributes in the widget has been resolved <br>

## Version 1.7.0 (Release Date: October 1, 2021)
MDM v.1.7.0 (.NET CORE 3.1) <br>
Release Date: 1 October 2021 <br>
DDB v.1.4 <br>
MASTORE v.6.15 <br>
AUTHDB v.1.0 <br>
RMDB v.1.2 <br>
MA WS v.8.4.1 (.NET CORE 3.1) <br>
NSI WS v.8.4.1 (.NET CORE 3.1) <br>
<br>
<i> The following functionalities have been released:</i> <br>
ISTAT-430 - Support for attributes at level Group or DimensionGroup linked to TimePeriod <br>
ISTAT-509 - Documentation in md format <br>
ISTAT-516 - Derived Item Schemes: tree view mode <br>
ISTAT-517 - CSV Mappings: now shown as a tree <br>
ISTAT-531 - Possibility to hide cubes and folders in which a user does not have permissions <br>
ISTAT-535 - Support for loading from Excel file with an XML Mapping generated by the tool ExcelToCsv <br>
ISTAT-633 - Support for loading from PC-Axis file <br>
<br>
<i> The following bugs and small improvements have been covered:</i> <br>
ISTAT-625 - Changed labels for linked and virtual dataflows <br>
ISTAT-687 - Small updates for supporting MA WS v8.4.1 <br>
ISTAT-688 - Annotation update with multiple text entries <br>
ISTAT-689 - Fix while doing zoom on multilingual text boxes <br>
ISTAT-690 - Fix on annotation preview for multilingual text boxes with no value for a language <br>
ISTAT-691 - Minor fixes on conversion from sdmx-ml files to csv with complex textual attributes <br>
ISTAT-697 - Fix on creating dataflows with a filter OBS_VALUE <> '' <br>
ISTAT-698 - Bug on loading data in cubes with associated CurrentData view longer than 4000 chars <br>
ISTAT-699 - Bug on creating a dataflow deselecting a column with only null values <br>
ISTAT-701 - Bug on moving a category with categorised dataflow under a different category <br>
ISTAT-716 - Slow typing while inserting names of a derived category scheme <br>
ISTAT-718 - Fix in item selection in dataflow's default and not displayed annotations <br>
ISTAT-725 - Removed from custom dsd conditional attributes not selected in the cube <br>
ISTAT-731 - Fix on update dataset level attribute with NULL values <br>
Dataflow Builder now creates automatically Allowed Content Constraint instead of Actual Content Constraint <br>
Fixed a bug when updating a dataflow's header in Dataflow Builder <br>
Fix on maximum length of dataflow's ID in Dataflow Builder <br>
Increased timeout for node connection <br>
Fix for 'set as default order' with data languages different from user interface languages <br>

## Version 1.5.7 (Release Date: June 14, 2021)
MDM v.1.5.7 (.NET CORE 3.1.0)  <br>
Release Date: 14 June 2021  <br>
DDB v.1.3  <br>
MASTORE v.6.10  <br>
AUTHDB v.1.0  <br>
RMDB v.1.2  <br>
MA WS v.1.26.5 (.NET CORE 3.1.0)  <br>
NSI WS v.7.13.2 (.NET CORE 3.1.0)  <br>
<br>
<i> The following bugs/improvements have been covered:</i> <br>
ISTAT-670	Dataflow Builder: bug on generating transcodings from content constraint <br>
ISTAT-686	Bug while storing items of content constraints selecting a sublevel from tree <br>
Referential Metadata Module has been excluded from this version<br>

## Version 1.6.1 (Release Date: June 11, 2021)
MDM v.1.6.1 (.NET CORE 3.1.0) <br>
Release Date: 11 June 2021 <br>
DDB v.1.3 <br>
MASTORE v.6.10 <br>
AUTHDB v.1.0 <br>
RMDB v.1.2 <br>
MA WS v.1.26.5 (.NET CORE 3.1.0) <br>
NSI WS v.7.13.2 (.NET CORE 3.1.0) <br>
<br>
<i> The following bugs/improvements have been covered:</i> <br>
ISTAT-670	Dataflow Builder: bug on generating transcodings from content constraint <br>
ISTAT-686	Bug while storing items of content constraints selecting a sublevel from tree <br>

## Version 1.6.0 (Release Date: May 03, 2021)
MDM v.1.6.0 (.NET CORE 3.1.0) <br>
Release Date: 03 May 2021 <br>
DDB v.1.3 <br>
MASTORE v.6.10 <br>
AUTHDB v.1.0 <br>
RMDB v.1.2 <br>
MA WS v.1.26.5 (.NET CORE 3.1.0) <br>
NSI WS v.7.13.2 (.NET CORE 3.1.0) <br>
<br>
<i> The following bugs/improvements have been covered:</i> <br>
Improved performances on referential metadata in the case of many reports <br>
ISTAT-117	Colorare diversamente (in verde) gli attributi compilati <br>
ISTAT-119	Nell'albero di metadataSet i MetadataSet sono stati anticipati rispetto alle categorie <br>


## Version 1.5.6 (Release date: April 23, 2021)
MDM v.1.5.6 (.NET CORE 3.1.0) <br>
Release Date: 23 April 2021 <br>
DDB v.1.3 <br>
MASTORE v.6.10 <br>
AUTHDB v.1.0 <br>
RMDB v.1.2 <br>
MA WS v.1.26.5 (.NET CORE 3.1.0) <br>
NSI WS v.7.13.2 (.NET CORE 3.1.0) <br>
<br>
<i>The following bugs/improvements have been covered:</i> <br>
ISTAT-650 - Error while inserting data in a cube with TID and at least an attribute at dataset-level <br>
ISTAT-651 - Impossible to save a virtual (linked) dataflow after having added layout annotations <br>
Referential Metadata Module has been excluded from this version <br>

## Version 1.5.5 (Release date: April 15, 2021)

MDM v.1.5.5 (.NET CORE 3.1.0) <br>
Release Date: 15 April 2021 <br>
DDB v.1.3 <br>
MASTORE v.6.10 <br>
AUTHDB v.1.0 <br>
RMDB v.1.2 <br>
MA WS v.1.26.5 (.NET CORE 3.1.0) <br>
NSI WS v.7.13.2 (.NET CORE 3.1.0) <br>
<br>
<i>The following bugs/improvements have been covered:</i> <br>
ISTAT-592 - Duplicate artefact: annotation order is not maintained anymore also on codelists <br>
ISTAT-623 - Category Schemes and Dataflow: error message when trying to move a dataflow under a category where it is already categorised <br>
ISTAT-628 - Bug when entering an ID if characters are inserted in the middle of the string <br>
ISTAT-629 - Fix generate transcodings for dataflow from a cube with tid <br>
ISTAT-639/a - Possibility to enter empty password in Data Browser configuration <br>
ISTAT-639/b - Wrong message while trying to update Data Browser cache wrongly configurated <br>
ISTAT-648 - Export in other WS: fix on check on credentials <br>
Referential Metadata Module has been excluded from this version <br>

## Version 1.5.4 (Release date: April 15, 2021)

MDM v.1.5.4 (.NET CORE 3.1.0) <br>
Release Date: 10 March 2021 <br>
DDB v.1.3 <br>
MASTORE v.6.10 <br>
AUTHDB v.1.0 <br>
RMDB v.1.2 <br>
MA WS v.1.26.5 (.NET CORE 3.1.0) <br>
NSI WS v.7.13.2 (.NET CORE 3.1.0) <br>
<br>
<i>The following bugs/improvements have been covered:</i> <br>
- Improved performances on referential metadata in the case of many reports <br>


## Version 1.5.3 (Release date: February 26, 2021)

MDM v.1.5.3 (.NET CORE 3.1.0) <br>
Release Date: 26 February 2021 <br>
DDB v.1.3 <br>
MASTORE v.6.10 <br>
AUTHDB v.1.0 <br>
RMDB v.1.2 <br>
MA WS v.1.26.5 (.NET CORE 3.1.0) <br>
NSI WS v.7.13.2 (.NET CORE 3.1.0) <br>
<br>
<i>The following bugs/improvements have been covered:</i> <br>
ISTAT-76  - Codelist: urn field is now saved correctly <br>
ISTAT-87  - More explicit error while trying to upload a file already loaded from the file system that has been modified <br> 
ISTAT-197 - Import Default Category Scheme from MSDB: now the order of categories is maintained <br>
ISTAT-198 - Slow typing in forms to create/modify items of itemscheme <br>
ISTAT-204 - TimePeriod is now supported in Content Constraint <br>
ISTAT-320 - Slow typing when updating concept schemes and in some other cases <br>
ISTAT-332 - Bug when entering an ID if characters are inserted in the middle of the string <br>
ISTAT-442 - Dataflow builder: 'Show categorisations' button now mantain the order among categorisations <br>
ISTAT-474 - MergeCategorySchemes: fixed bug on duplicated categories in the merged artefact <br>
ISTAT-484 - Dataflow Builder: bug while searching in category schemes <br>
ISTAT-502 - Filters: bug on available codes retrieved from the whole cube  instead from the dataflow <br>
ISTAT-528 - Builder: while creating manually a new Default Category Scheme permissions on categories are now assigned automatically <br>
ISTAT-568 - Managing only-file dataflow with virtual DSD <br>
ISTAT-569 - Loading: Error message for attributes linked to TimePeriod <br>
ISTAT-571 - SMTP Mail provider - password field is now encrypted <br>
ISTAT-591 - DSD: bug on getting details with AllCompleteStub parameter set to true <br>
ISTAT-592 - Duplicate artefact: annotation order is not maintained anymore <br>
ISTAT-593 - ConceptScheme: CoreRepresentation is now maintained when an artefact is updated or duplicated <br>
ISTAT-598 - Fix: DMApi's swagger not working <br>
ISTAT-606 - Added some missing IDs in confirmation popups <br>
ISTAT-607 - Default layout annotation: only available time periods are now shown <br>
ISTAT-XXX - Loader: 'CheckFiltAttributes' is now set to true by default <br>


## Version 1.5.2 (Release date: January 29, 2021)

MDM v.1.5.2 (.NET CORE 3.1.0) <br>
Release Date: 29 January 2021 <br>
DDB v.1.3 <br>
MASTORE v.6.10 <br>
AUTHDB v.1.1 <br>
RMDB v.1.2 <br>
MA WS v.1.26.5 (.NET CORE 3.1.0) <br>
NSI WS v.7.13.2 (.NET CORE 3.1.0) <br>
<br>
<i>The following bugs/improvements have been covered:</i> <br>
ISTAT-9 - Error message while trying to connect to a not-available web service <br>
ISTAT-15 - Advanced filters - manage filters on time period with a range <br>
ISTAT-80 - CompareDSD now available also for anonymous user (if properly set in configuration) <br>
ISTAT-83 - Upgrade DSD - bug on preview codelist's details <br>
ISTAT-84 - App Configuration: removed 'Prepared' field from Default Header Submit Structure <br>
ISTAT-86 - Compare itemschemes from file: corrected bug on itemscheme's preview <br>
ISTAT-100 - Buttons for 'Clone' and 'Export on Remote Ws' for MSD and HCL <br>
ISTAT-103 - Different number of items between Simple and Advanced filters <br>
ISTAT-191 - Layout Annotations (General Parameters) - Added 'Include annotations' option <br>
ISTAT-314 - Fix on not allowing the import of a concept scheme referencing a not final artefact <br>
ISTAT-317 - Dataflow Builder - Download: option allDimensions at observation level and possibility to specify dimensions at observation level also for sdmx-json format <br>
ISTAT-322 - Default layout annotation: only available codes in the dataflow are now shown <br>
ISTAT-354 - Added ID in confirmation popups <br>
ISTAT-401 - Fix on uploading files with special characters <br>
ISTAT-411 - Default Category Scheme Management: possibility to move a category to its parent level <br>
ISTAT-411 - Default Category Scheme Management: disabled ID field while updating a category <br>
ISTAT-412 - MDM manual updated <br>
ISTAT-417/a - Import Attribute File: added report on wrong references for coded attributes <br>
ISTAT-417/c - Warning for attributes with attachment level Series or Group linked to TimePeriod (not supported yet) <br>
ISTAT-418 - Filter, simple mode: bug on obs_value and time period  <br>
ISTAT-419 - Fix on filters on Time-Period in Advanced mode  <br>
ISTAT-429 - Support for download DDBDataflow with filter in POST: still not supported in MA WS  <br>
ISTAT-431 - Dataflow Builder: attributes cannot be selected in filters for SDMX formats  <br>
ISTAT-434 - Possibility to return to the Home from 'Select Default Category Scheme' popup  <br>
ISTAT-445 - Loader: Fix on upload SDMX-ML data file without frequency dimension  <br>
ISTAT-476 - Merge itemscheme: fix when result itemscheme has a multilanguage name  <br>
ISTAT-478 - Wrong message while uploading csv in cube with tid and dataset level attributes  <br>
ISTAT-479 - Empty cube: table AttNoCode@XX is not truncated  <br>
ISTAT-485 - Fix on refresh endpoint when creating a virtual dataflow  <br>
ISTAT-486 - Hidden not available annotation for virtual and linked dataflows  <br>
ISTAT-489 - Reset DDB: also dataset are now deleted from the MSDB  <br>
ISTAT-495 - Minor fixes on Update Data Browser Cache (push mode)  <br>
ISTAT-496 - Bug on blank AttachedDataFile annotations  <br>
ISTAT-503 - Derived Item Schemes: enlarged search box  <br>
ISTAT-504 - Local fix on accessing Eurostat's DSDs in a specific format  <br>
ISTAT-530 - AttributeFile - Bug for SqlServer version 2012  <br>

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
