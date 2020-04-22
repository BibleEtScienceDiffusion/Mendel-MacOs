---------------------------------------------
INSTALLATION AND SIMPLE USAGE FOR MENDEL 2.5:
---------------------------------------------

NOTE: This version works on Mac OS X 10.10 systems using Google Chrome browser.  
Other versions of OS and browser may give unstable results.  If Mendel's Accountant
will not run on your system, please visit http://mendelsaccountant.info for 
more information.

1. Download mendelsp-2.5.zip

2. Unzip folder

3. The first time right click on the "start_server" script and click "Open".
   (Subsequent starts can be opened by double clicking on "start_server").  
   This should open the browser to the page http://0.0.0.0:8580/mendel

4. Enter parameters and click "Continue".  Click the "help" button to 
   get more information about various parameters.

5. Click "Execute" to start the simulation.  

6. At any time, click "Plot" to see output plots.

7. Click the "Jobs" button to manage (e.g. delete) jobs

---------------------------------------------------------------------------
INSTALLATION and USAGE INSTRUCTIONS for iMENDEL2:
---------------------------------------------------------------------------

NOTE: This version will only work on Mac OS X systems.
If you have a Windows or Linux machines, please select
the specific download for your platform.

INSTALLATION:

Easy method to install Mendel's Accountant:

1. Right click on "install" and select "Open"
   (Note: double clicking on "install" will not work)

2. After install, point your web browser to:
 
    http://localhost/mendel-2.5.0/index.html

3. To uninstall, double click "uninstall"

ADDITIONAL NOTES: 

1. If you need to change the amount of memory which Mendel uses, edit the file:
/Library/WebServer/CGI-Executables/2.5.0/perl/config.inc
and the set value of the variable $ram_per_job to the amount of RAM you 
have available.  More RAM means larger population sizes, more linkage 
blocks, etc.

2. If you already have Mendel installed, you may want to uninstall
before installing a new version.  If you uninstall Mendel, your 
data will still remain on your system and you will have access
with the newer version.
