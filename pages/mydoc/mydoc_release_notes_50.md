---
title: Data Browser Release notes
tags: [getting_started]
keywords: release notes, announcements, what's new, new features
last_updated: February 4, 2021
sidebar: mydoc_sidebar
permalink: mydoc_release_notes_50.html
folder: mydoc
---

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
