---
title: Data Browser Release notes
tags: [getting_started]
keywords: release notes, announcements, what's new, new features
last_updated: February 4, 2021
sidebar: mydoc_sidebar
permalink: mydoc_release_notes_50.html
folder: mydoc
---
## Version 4.1.11 (Release date: March 3, 2025)
.NET CORE 6.0
<br>
<i> The following bugs/improvements have been covered:</i> <br>
Update of SdmxSource libraries to version 9.11.0 <br>
Improved performance in json-stat conversion <br>
The filter popup has been evolved to support any hierarchies present in classic Codelists <br>
The hierarchical representation in the table has been improved <br>
The performance of the tree (in Criteria) has been improved <br>
In the dashboards the possibility of zooming the graphed area has been added, for all graphs that support it <br>
A new annotation has been implemented, to be able to order the presentation of Category Schemes <br>
Added the possibility of configuring the scale extremes in graphs with Cartesian axes (lower extreme set to zero or that adapts to the data) <br>
Possibility of defining the layout for the graph family <br>
Exclusion from the catalog of linked dataflows on private/inactive nodes <br>
Possibility of presenting attributes as dimensions in multidimensional table <br>
Added the ability to configure the Time Period representation <br>
Added the ability to merge/split grouping cells in the side and header in the multidimensional table <br>
Added support for the lastNObservations parameter of the NSIWS <br>
Added the management of Hierarchical Code Lists (value based) in the Criteria <br>
Final technological adaptation <br>
Added new permissions for creating and sharing dashboards at node level <br>
Changed the dashboard organization <br>
Generalization of (external) dashboard and CRUD filters via GUI <br>
Added the ability to share specific data representations via widgets <br>
Added the ability to share Dashboards as widgets <br>
Added the ability to categorize dashboards in the catalog <br>
Receive layout annotations in Linked Dataflow <br>
Optimized the space in the criteria for selecting a hierarchy, in the presence of HCL <br>
By logging in while viewing a data, the application reloads exactly the current view <br>
(Various) optimizations of the vertical spaces, released in custom.css <br>
Changed the icons and display logic of the icons for zooming on the graphs <br>
The positioning of the data access buttons and metadata in custompage has been fixed <br>
Added an option to decide whether to display the categories inserted in custompages expanded or collapsed <br>
Added an option to hide the title of the custompages in display <br>
Added the zoom on the selected category <br>
Changed the background color and font in the tooltips of the attributes <br>
Improved the performance of saving the node, which was slow in the presence of many users <br>
Removal of the id in the presence of unencoded dimensions/attributes <br>
Software adapted to receive encrypted microservice passwords (ExternalAuth) <br>
Changed the hierarchical representation in the table, if intermediate levels are not selected: each item is positioned as a direct child of the first ascendant present in the table or as a root if no ascendant is present. <br>
Removal of the double error message in the case of incorrect login <br>
When updating the machine-to-machine password via the graphical interface (GUI), it is automatically synchronized with the microservices as well. It is necessary to remove the 'ExternalAuth' configuration under the 'AuthServiceConfig' key from the microservices, as it is no longer needed. Then, update the machine-to-machine password using the dedicated function in the GUI. <br>
Updated the manual to explain the dashboard migration utility logging system <br>
Removed ID from attribute name labels, in Excel export <br>
Added translation for error message, in case of incorrectly configured dashboard microservice <br>
Checked block timing; more details directly on the ticket and in the user manual <br>
Standardized the order of the geometry table fields between SQL Server and SQLite <br>
Adjusted the management of the number of decimals in Excel display/export and improved the related configuration at node and template level <br>
Removed the 30-second timeout for clearing caches <br>
Updated the criteria icon <br>
Changed the encoding supported in loading dashboard filters: UTF-8  <br>
Improved the management of the case in which parametric filters did not give results (the white card remained)  <br>
Added translations of the names of the languages ​​supported by the ISO 639-1 standard  <br>
Added application-level configuration to decide how to display the widget metadata  <br>
Physical deletion of cached artifacts, deleting all structures  <br> <br>
BUGFIX  <br>
Restored the Time Period in filters for data with frequencies other than annual (ALL PARTIAL OPTIMIZED mode)  <br>
Restored the last column in the header of the Excel export  <br>
Fixed blue screens in the presence of tables (e.g. user list, dashboard, ..)  <br>
Restored the consistency of the Time Period selector with the set frequency  <br>
Fixed the check for the presence of a node with the same identifier during import  <br>
Fixed the overlapping of the asterisk of the attributes with the axes and opened a ticket for the chartjs community for the disappearance of the line in the presence of zoom: https://github.com/chartjs/chartjs-plugin-zoom/issues/816  <br>
Negative values ​​taken into account when adapting the scale to the data range  <br>
Fixed the scale in the case of stacked bar chart  <br>
Fixed the display of alphanumeric data of the form "number - number"  <br>
Added the possibility to select the category schema, even if it is unique in the node  <br>
In the absence of content constraint on the TIME PERIOD, the time dimension is still shown in FULL mode (previously the dimension was hidden)  <br>
Fixed the opening of an existing view, following the migration from sqlite to sqlserver  <br>
Fixed the problem in ALL_PARTIAL_OPTIMIZED mode, where changing the language or login did not correctly apply the filters to data requests  <br>
In the data cache management interface, the synchronization issue between the text filters applied to the dataflow list and the underlying table has been fixed  <br>
Fixed the import of geometries via CSV file, at node level  <br>
Fixed the rounding of numbers in Excel export  <br>
Restored the union of the cells on the side in the Excel export  <br>
Restored in the Excel export Id and Label, if requested (even if identical)  <br>
Corrected the management of the attributes treated as dimension, in the Excel export  <br>
Fixed the alignment of the filter tree with any text filters set  <br>
Fixed the error in the Excel download in the case of decimals not set in the node configuration  <br>
Fixed the error in the dashboard display, applying filters parametric  <br>
Restored Excel export functionality, in case of parametric filters application  <br>
Added HTTP authentication configured to the endpoint Ping request  <br>
Fixed restoring hierarchies in the filter popup, including previously missing elements without children  <br>
Fixed restoring hierarchies in the filter popup, in size selection modes other than ALL_PARTIAL_OPTIMIZED  <br>

## Version 2.0.8 (Release date: May 30, 2024)
.NET CORE 6.0
<br>
<i> The following bugs/improvements have been covered:</i> <br>
BUGFIX: update of the migration tool to resolve problems encountered in the presence of large amounts of data <br>
Improved performance when converting to json-stat <br>
BUGFIX: restored the dashboard preview <br>


## Version 2.0.6 (Release date: March 20, 2024)
.NET CORE 6.0
<br>
<i> The following bugs/improvements have been covered:</i> <br>
Introduction of new caches to optimize queries with NSIWS <br>
Use of content constraints in retrieving Codelists (PARTIAL) <br>
Introduction of new caches for partial codelists ("step by step partial" and "all partial" modes) <br>
Introduction of the possibility of anticipating the verification of exceeding the threshold of the maximum number of records, estimating the number of resulting observations <br>
Introduction of a new dimension/data navigation mode: OPTIMIZED ALL PARTIAL <br>
Introduction of the possibility of configuring SQL Server as a database, as an alternative to SQLite <br>
Improvement in the management of exceeding the maximum threshold of the number of cells <br>
Improvement in the management of exceeding the maximum number of observations allowed, which allows you to guide the user in positioning dimensions in the filters <br>
Technological adaptation on the client (partial) and server side (SdmxSource) <br>
When navigating to a "potential" data/dashboard, login is now requested <br>
Added a new configuration to enable/disable pan&zoom on the category axes <br>
Improved the times for generating the export file in CSV format <br>
The default Annotation configurations have been standardized with MDM version 1.10 <br>
The email verification mechanism during registration has been made configurable, via appsettings.json <br>
In the release package, for all configurations that require access to the database, in addition to the classic SQLite mode, active by default, a commented example with the parameters for SQL Server has also been included <br>
Password autocomplete for NSIWS (HTTP Authentication and Proxy) has been disabled <br>
Improved management of display of names that are too long in filters <br>
Improved the performance of the table to manage user permissions on individual nodes <br>
In the registration and user creation form the only mandatory fields are: email, password <br>
The annotation dedicated to the implementation of Content Constraints has been made configurable <br>
Creation of the SQL Server Geometries table at application startup <br>
Adaptation of the configurations released in the package to ISTAT specifications <br>
Added details on configuration with SQL Server to the manual <br>
Optimization of the query for downloading data for the current view only (ALL PARTIAL OPTIMIZED mode) <br>
Fixed the inconsistency between the time period filters in the criteria tab and the SDMX query (ALL PARTIAL OPTIMIZED mode) <br>
Removed double catalog request following cache invalidation <br>
Resolution of misalignment between header and contents in multidimensional table <br>
Improved performance when downloading data in CSV format <br>
rimozione della possibilità di scaricare l'intero dataset in modalità ALL PARTIAL OPTIMIZED <br>
removal of the possibility of downloading the entire dataset in ALL PARTIAL OPTIMIZED mode <br>

## Version 1.6.3 (Release date: February 24, 2023)
.NET CORE 6.0
<br>
<i> The following bugs/improvements have been covered:</i> <br>
ISTAT-914 The order of presentation of the territorial levels has been changed<br>
ISTAT-915 Fixed the "not selectable" (in some cases) of the level of detail selector in the map<br>
ISTAT-916 Correction of some polygons in the geographical database (e.g. countries bordering the Caspian Sea)<br>
ISTAT-918 Extension of the area displayed in the map of the whole world, to facilitate its use<br>
ISTAT-919 Fixed deletion of temporary files for downloads<br>

## Version 1.6.1 (Release date: January 9, 2023)
.NET CORE 6.0
<br>
<i> The following bugs/improvements have been covered:</i> <br>
ISTAT-901(a) Addition of confirmation message, before deleting the template via "shortcut"<br>
ISTAT-901(b) Addition of the timetable (hh:mm:ss format) in the PDF export<br>
ISTAT-901(c) Fix catalog tree navigation<br>
ISTAT-901(d) Removal of the level of detail selector in the case of single geometry<br>
ISTAT-902 Addition of the new geographical database<br>
ISTAT-909 BUGFIX: restored correct functioning of search in filters<br>
ISTAT-910 BUGFIX: manual update<br>
ISTAT-911 BUGFIX: items marked for hierarchy purposes only have been hidden<br>

## Version 1.6.0 (Release date: December 12, 2022)
.NET CORE 6.0
<br>
<i> The following bugs/improvements have been covered:</i> <br>
ISTAT-883 Added the possibility to download the Excel of the entire dataset in the dashboard<br>
ISTAT-866 Added the possibility to enable the Progressive Web App (PWA) for the Data Browser<br>
ISTAT-865 Added the possibility to sort the data, in multidimensional table<br>
ISTAT-864 Added the possibility to make filters, in multidimensional table<br>
ISTAT-863 Added ability to customize translations for an installation<br>
ISTAT-862 Added the News module<br>
ISTAT-861 Added the possibility to define some default behaviors for the graphs, from configuration files<br>
ISTAT-860 Added new features to the map: configure new background maps, perform geographic filters, define custom class intervals, define some default behaviors<br>
ISTAT-858 Added the possibility to configure private nodes, i.e. accessible only to some users<br>
ISTAT-856 Addition of email verification during registration<br>
ISTAT-855 API update to .NET6<br>

## Version 1.5.1 (Release date: November 24, 2022)
.NET CORE 3.1.0
<br>
<i> The following bugs/improvements have been covered:</i> <br>
ISTAT-875 The CSV export has been adjusted to always include all the decimals present in the data<br>
ISTAT-882 Added the ability to download the CSV, in dashboards, considering all the criteria with which the view was created<br>
ISTAT-884 Added an identifier to the CSV download button next to the viewers, to be able to customize its style (or hide it)<br>
ISTAT-886 Optimization of dashboard retrieval queries<br>
ISTAT-889 Addition of CSV export in dashboard, also for charts and maps<br>
ISTAT-890 Preparation of a new generic error page<br>
ISTAT-876 BUGFIX: fixed the omission of the zero for decimal digits representing values below the unit<br>
ISTAT-877 BUGFIX: fixed the behavior that led to an inconsistent graphic status, clicking on the browser back button while a data was being viewed in fullscreen mode<br>
ISTAT-879 BUGFIX: fixed the inconsistency of selected level of detail, between view and dashboard<br>
ISTAT-887 BUGFIX: fix the failed initialization of maps in dashboard, starting from the second visualization<br>
ISTAT-888 BUGFIX: Restore the behavior that, regardless of the filters applied, opens the Criteria window by selecting the first available dimension<br>
​

## Version 1.5.0 (Release date: September 20, 2022)
.NET CORE 3.1.0
<br>
<i> The following bugs/improvements have been covered:</i> <br>
ISTAT-287 Added the display of hierarchical codelists (no HCL) in the table, in case the dimension with hierarchy is put in line<br>
ISTAT-291 Added the possibility to define, at node level, which data languages are actually available<br>
ISTAT-391 Inclusion of the title by placing the individual viewers in full screen<br>
ISTAT-394 Added the shortcut, when viewing a data, for modifying the cache and deleting the template<br>
ISTAT-609 Added the concept of visibility of a node, so you can have active but not visible nodes in the portal<br>
ISTAT-784 Added the possibility to invert the time dimension, in tables and graphs<br>
ISTAT-785 Added the possibility to remove, by customizing the template, some of the available viewers<br>
ISTAT-786 Improved the resolution of the image in the download of the graphs<br>
ISTAT-794 Added the possibility, via template, to fix some dimensions in graphs and tables so as not to change their positioning through pivoting<br>
ISTAT-804 Changed the display logic of the images for the categories<br>
ISTAT-805 Added support for authentication via Shibboleth, via the ShibO2Module module<br>
ISTAT-810 The representation of the attributes in the table has been changed (in the new version the presence of an attribute is always indicated with an asterisk)<br>
ISTAT-811 Addition of the tree navigation mode in the exploration of the categories<br>
ISTAT-812 Added the possibility to export maps and graphs in PDF<br>
ISTAT-820 Added the possibility to configure the baseUrl of the SDMX web service, to be shown in the "query view" popup, available for the end user<br>
ISTAT-831 Addition, in the criteria, the possibility of displaying only the selected items<br>
ISTAT-832 Added the possibility, in the filters, to search for items by code<br>

## Version 1.3.3 (Release date: December 07, 2021)
.NET CORE 3.1.0
<br>
<i> The following bugs/improvements have been covered:</i> <br>
ISTAT-247	Added the possibility to download the multidimensional table in Excel format (xlsx)<br>
ISTAT-741	Customization of the management of views and templates created on a given data, in the event that a "last N periods" type filter on the time dimension is set in the criteria<br>
ISTAT-185	Added the configuration, at the node level, for setting the default values of the time range (used in case it is not possible to retrieve the effective range from the NSIWS)<br>
ISTAT-738	Adjustment of the time range reading from Cube Region (NSIWS version 8.4.0 and later) <br>
ISTAT-742	BUGFIX: improved the management of the space dedicated to the filters of the views in the dashboard <br>
ISTAT-743	BUGFIX: enabled the possibility to select the detail level of the views, if the view filters are enabled <br>
ISTAT-746	BUGFIX: resolution of error message in saving template <br>
ISTAT-747	BUGFIX: resolution of the TIME PERIOD initialization problem by configuring the default range at the node level <br>

## Version 1.3.2 (Release date: November 15, 2021)

ISTAT-603	Changed the download query of the SDMX-ML structure to also include referenced artifacts (descendants)<br>
ISTAT-723	Improved the tabular representation, to avoid carriage returns in the cells in some particular cases
ISTAT-728	Added a cleanup task for expired cache files<br>
ISTAT-727	The possibility of configuring the "last N periods" also in Partial navigation modes has been enabled<br>
ISTAT-730	Improved error handling in case exceptions occur when saving a node: it prevents the popup with all the configured configurations from being closed<br>
ISTAT-719	BUGFIX: fixed the transposition of the annotation not displayed for the attributes<br>
ISTAT-721	BUGFIX: corrected the transposition of the ordering of the dimensions set in the filters (layout annotation)<br>
ISTAT-726	BUGFIX: restored the warning that warns the user of a possible exceeding of the maximum number of observations (set in configuration)<br>
ISTAT-696	BUGFIX: fixed the interpretation of the attribute attachment level<br>
ISTAT-729	BUGFIX: corrected the number of results per category in the case of dataflow categorized simultaneously in multiple categories, also adding a note indicating that the dataflow has a "multiple" categorization<br>
ISTAT-740	Management of the case in which, among the DEFAULT annotations on the TIME PERIOD, only the start date (and not the end date) is valued and the SOAP 2.0 workaround is enabled on the databrowser side<br>
ISTAT-739	BUGFIX: use of the SOAP workaround even in the presence of the last N periods<br>
ISTAT-735 	BUGFIX: corrected the deletion of the dataflow cache for all languages, putting into production a dataflow on the MDM side
ISTAT-736	BUGFIX: fixed the clearing of the catalog cache, for all languagese<br>
ISTAT-737	BUGFIX: corrected the transposition of the DEFAULT annotation for the TIME PERIOD range<br>

## Version 1.1.1 (Release date: December 03, 2020)
.NET CORE 3.1.0
<br>
<i>The following bugs/improvements have been covered:</i> <br>
- Resolution of the scrollbars not displayed in the table
- Openstreetmap background map removed
- Accessibility improvements

## Version 1.1.0 (Release date: November 25, 2020)
.NET CORE 3.1.0
<br>
<i>The following bugs/improvements have been covered:</i> <br>
ISTAT-230 Accessible version refinement <br>
ISTAT-343 Color selection for items of the graphed dimension <br>
ISTAT-356 Move image files (categories) to node level <br>
ISTAT-383 Added the ability to collapse the legend on the map <br>
ISTAT-387 Move "schedulable" service configurations externally to the appconfig.json file <br>
ISTAT-386 Introduced the use of the count of the record number <br>
ISTAT-378 Loading of maps <br>
ISTAT-414 Application level dashboard duplication and normalization <br>
ISTAT-264 Cursor scrolling problem in dashboards <br>
ISTAT-269 Filter management problems <br>
ISTAT-280 Templates created on maps are not maintained <br>
ISTAT-290 In flat codelists (criteria) added the "deselect all" <br>
ISTAT-365 Disabled internal scrolling of views by scrolling the dashboard <br>
ISTAT-367 Dashboard, Maps -  lack of synchronization with the wait wheel <br>
ISTAT-374 Problems creating map views <br>
ISTAT-380 Query efficiency check <br>
Password change and recovery problem <br>
Problem with saving map configuration in view / template <br>
Check that cache expiration works correctly <br>
In dashboards some objects are not displayed randomly <br>
In registration, the "Organization" field must not be mandatory <br>
The configured default language has to win when you reopen the application  <br>
The combo-box must not be visible at the top left if you start with the default node and the node is the only one present <br>
The "other nodes" button must not be visible on the home-page of the default node if the node is the only one present <br>
The node combo box on the top left must show the node name and not the node ID <br>
