# ArchaeoBase
This project outlines an application to upload, process, analyze, and store archaeological data following the HOMER data collection protocols.
<br>
<br>

# Application download
<br>
<br>
To download Version 9.2 of this application, download the zip folder and extract to a permenant location on your computer.
<br>
<br>
## Software requirements
The current version of this application only currently works on Windows OS.
This application was written in Python version 3.14.3
Ensure that you have at least this version of python installed on your device.
<br>
<br>

## File contents
This file contains 5 subfolders, 1 *requirements.txt*, 1 installation file, and 1 execution file.
<br>
<br>
*testFiles*: This folder contains several documents used to test the application including total station coordinate data, lab data, and recorder data. Please ensure that all files are saved as a CSV to import into the application. the *StratUnitDescription.csv* needs to be UTF-8 coded. This is an option when exporting from a .xlsx document
<br>
<br>
*sql*: contains a file with queries for generating the database tables.
<br>
<br>
*scripts*: This folder contains the python scripts to run the applications.
<br>
<br>
*data*: This folder will contain the local database after the first launch of the application in the currentl folder directory.
<br>
<br>
*backups*: This folder will contain backups of the local database before it is synced with the online database. NOTE: the app is set to work offline for stability testing.
<br>
<br>
### Install and and run the application
1. Run the *install.bat* file to automatically install all required packages and modules for the application, which are saved in the *requirements.txt.*
2. Run the *run.bat* file that initializes the application and should launch on a local host in your machine's browser
