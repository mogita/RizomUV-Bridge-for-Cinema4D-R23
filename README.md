# RizomUV Bridge for Cinema4D R23

### Installation:

Unpack plugin in your Plugins directory.
Start Cinema4D and open Options window: Plugins > RizomUV Exporter > Options
Specify the work path of the rizomuv.exe ( default location is: C:\Program Files\Rizom Lab\[RizomUV] )

If you are updating the plugin, please, delete the settings.json ( the previous version's configuration file ) file from C:\Users\[USER]\AppData\Roaming\MAXON\Cinema 4D R1X_XXX\prefs\rizomUV folder.

### For macOS Users

The package has been modified to run under macOS version of Cinema4D (tested in R24, should still be working for R23).

#### Setup

**Must read this, or you might encounter the "RizomUV not found" error.**

In Options window, choose the path of the executable of RizomUV instead of just its application package. You can follow these steps if you are not clear what to do:

1. Install RizomUV Bridge as any other Cinema4D Plugins
2. Start Cinema4D and find the "Options" menu item under "RizomUV Bridge" from the Extensions menu
3. Click on "..." button of the "RizomUV Path" option, keep the file choosing window open
4. Open a new Finder window, and go to "Applications" folder, then locate your RizomUV application (ends with ".app")
5. Right click on the application and select "Show Package Contents"
6. Go to "Contents" then "MacOS" folder, there should be a file with the name like "RizomUV.2020.1"
7. Drag this file, then drop it to the file choosing window from step 3
8. The file choosing window should now show you the executable file from step 6
9. Click "Open", then "Save"

Example of the executable:

![macOS RizomUV in Finder](macOS.png)
