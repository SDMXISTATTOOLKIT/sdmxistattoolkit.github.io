---
title: Excel2csv Release notes
tags: [getting_started]
keywords: release notes, announcements, what's new, new features
last_updated: October 15, 2018
sidebar: mydoc_sidebar
permalink: mydoc_Excel2csv_release_notes.html
folder: mydoc
---

## Version 1.2.10 (Release date: October 15, 2018)
<i>The following bugs/improvements have been covered:</i> <br>
- Added Header Info
<br>
<br>
## Version 1.2.9
<i>The following bugs/improvements have been covered:</i> <br>
- Added Control for duplicate keys (possible memory leaks)
<br>
<br>
## Version 1.2.8
<i>The following bugs/improvements have been covered:</i> <br>
- Speed improvement
<br>
<br>
## Version 1.2.7
<i>The following bugs/improvements have been covered:</i> <br>
- Added "Convert in SDMX format" window
<br>
<br>
## Version 1.2.6
<i>The following bugs/improvements have been covered:</i> <br>
- Added Unicode UTF-8 (without BOM) on Output Encoding
<br>
<br>
## Version 1.2.5
<i>The following bugs/improvements have been covered:</i> <br>
- Fixed style issues, including a proper encapsulation for P/Invoke calls with safe access modifiers.<br>
- Encapsulate csv field values in a container that reports whether the field refers to a time series value.<br>
- Do not let the Expression Editor affect the values for time series dimensions. <br>
<br>
## Version 1.2.4
<i>The following bugs/improvements have been covered:</i> <br>
- Adding an attribute column sets its offset to the least maximum value available.<br>
- Suppress warning on empty column headers for attribute columns while detecting axis.<br>
- Suppress errors on empty column headers for attribute columns while extracting data.<br>
- Check for xml format compatibility.<br>
<br>
## Version 1.2.3
<i>The following bugs/improvements have been covered:</i> <br>
- Changing the coordinates of the first data cell or the last one does not  reset the field configuration anymore.<br>
- Support column attributes by specifing a column offset for each attribute.<br>
- Version is back to the major.minor.micro.build format.<br>
- Fixed a bug making the codelists appear more than once when multiple
  language labels are present.<br>
<br>
## Version 1.2.0
This document describes the features of version 1.2 of Excel2Csv, released
on 23th February 2018. The following changes and improvements have been
added since version 1.1.6530.26781 released on 17/11/2017.<br>
<i>The following bugs/improvements have been covered:</i> <br>
- new code list extraction mode featuring what hereby follows:<br>
  * possibility to mark a field as "code list" in order not to have repeated
    codes.<br>
  * possibility to add a field that contains a description embedded in a
    "code + description expression" cell.<br>
- Accept "NaN" as a valid data value.<br>
- Added a switch that lets users process non-numeric data by not attempting
  to cast data values.<br>
- Creation of MDI windows and switching between them have been made faster.<br>
- Changing either the first data cell or the last table one does not reset
  the field settings.<br>
- Let users work with empty dimension values by accepting to continue after
  a warning.<br>
- Fixed a bug appearing on codelists with multiple columns.<br>
- Fixed a bug letting the time mapping to be overwritten that appeared after
  the improvements on the changes to the first and last data cells.<br>
- Fixed a bug that wasn't letting the Expression Editor to appear while
  working on a completely new session.<br>
- Fixed a bug that let the wrong callbacks to be called from the Time Editor<br>
- Fixed a bug in the code list mode that made codes in merged cells to be
  repeated in the output.<br>
- Add a check against null merged regions.<br>
- Huge code and comment refactoring.<br>
- Added a check that prevents the Progressbar from crashing the application.<br>
<br>
