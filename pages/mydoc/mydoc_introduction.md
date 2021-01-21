---
title: ISTAT Statkit building blocks
sidebar: mydoc_sidebar
permalink: mydoc_introduction.html
folder: mydoc
---

### 3.1 Excel2csv
<p style="text-align:justify;">Desktop application that allows to transform a multidimensional statistical table in excel into a CSV “verticalized” file (one observation per row). It allows also to create CSV files containing code lists.</p>
[Github repo](https://github.com/SDMXISTATTOOLKIT/EXCEL2CSV)<br>
<img src="./images/Excel2csv.png"> <br>

### 3.2 Meta&Data manager
<p style="text-align:justify;">SDMX based web application that integrates and exdends the functions of the old Metamanager and Datamanager. The architecture is technologically advanced and composed by a completely service-based back-end developed in .NET Core and a REACT/REDUX component based front-end. The application allows to: manage/disseminate structural metadata; create dissemination/reporting databases; create/disseminate reference metadata; create/disseminate Open Datasets Digital Catalogues (DCAT); create/disseminate thematic glossaries. </p>
[Github repo](https://github.com/SDMXISTATTOOLKIT/META-DATA.MANAGER)<br>
<img src="./images/MDM_Schema.png"> <br>

### 3.3 Data Browser
<p style="text-align:justify;">Interacts with SDMX web services allowing data-users to browse, present and visualize datasets. it can be used within a single Organization in order to disseminate datasets stored into one or more databases, or in the context of a “multi-source” project (Hub architecture), where more Organizations expose their databases through SDMX Web Services based on the SDMX-RI. A data user” can: switch between the available dashboards; switch between different distributed databases (web services); browse one or more tree-themes and select the dataset of interest ( the same leaf-tree, can categorize datasets coming from different databases); set filter for each dataset; specify the layout of the table; calculate cyclical and trend variation; create graphs; store queries (only for authenticated users) that can be used in other working sessions.</p>
[Github repo](https://github.com/SDMXISTATTOOLKIT/DATABROWSER)<br>
<img src="./images/DB_Schema.png"> <br>
