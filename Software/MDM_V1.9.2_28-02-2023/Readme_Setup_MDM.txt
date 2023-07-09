Prerequisites
a. Windows server 2012 or upper (for laptop or PC, Windows 10 with IIS activated). Warning: Before installing .NET CORE and .NET 6, IIS must be activated
b. .NET CORE 3.1.x with .NET Core hosting bundle for IIS
c. .NET 6.0.x with .NET Core hosting bundle for IIS
d. Microsoft Visual C++ 2015 Redistributable Update 3 o upper
e. MS SQL Server 2012 or upper. SQL Server 2016 o upper is suggested in order to harness ”columnStore ” Indexes to increase performance. MS SQL Server Express Edition can be used
   The installation of SQL Server must include SQL Server Management Studio

Setup
1. Unzip the setup file
2. In the folder containing the unzipped file, edit the "application_parameters_MDM.bat" the "Config_MDM" folder in order to configure the setup parameters (Database names, URLs, Paths, application pool names, etc)
3. Run the command prompt ("cmd" application) as administrator
4. Through the command line statements change directory up to the directory containing the setup files and folders
5. Execute the "Install_MDM.bat" file
6. At the end of the execution of the "Install_MDM.bat" file will be automatically launched on the internet browser the setup wizard of the DM_API_WS for creating the database schemas.
   (Username:admin with no password)
7. launch the MDM application (http(s)://<server_URL>/<virtual_directory(if existing)>/<MDM_folder>/client) and open the administration interface for configuring application and nodes by following the user manual's
   instructions   