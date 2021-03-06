# MSFSTouchPortalPages

<img src="https://user-images.githubusercontent.com/31976175/94336558-3663e780-ffb2-11ea-872a-36ae009ab90f.png" width="400px" height="300px">

### Background
You must be using version 0.5.1 of the MSFSTouchPortalPlugin (https://github.com/tlewis17/MSFSTouchPortalPlugin).

The MSFSTouchPortalPlugin referenced above starts %appdata%\Roaming\TouchPortal\plugins\MSFS-TouchPortal-Plugin\dist\MSFSTouchPortalPlugin.exe
- This executable is in charge of communicating with MSFS via SimConnect
- This connection provides an API to retrieve/drive events from MSFS

The "Launch OpenTrack & FSJumpStart" button is dependent on https://github.com/AmbitiousPilots/FSJumpStarter2020
- Please download this exe and edit the "Launch OpenTrack & FSJumpStart" buttton to reference the correct path

### Instructions
- Close TouchPortal
- Please copy all .tml files in the pages/ folder to %appdata%/Roaming/TouchPortal/pages and all icons in the icons/ folder into %appdata%/Roaming/TouchPortal/icons
- Open TouchPortal

#### If you do not already have a custom (main).tml
##### Option 1: Use this project's main as the default (main) page
- Close TouchPortal
- Rename the msfstpp_main.tml provided with this project to (main).tml PRIOR to copying it into %appdata%/Roaming/TouchPortal/pages
- Open TouchPortal
- Within each page in this project you must modify the "back to main" button to redirect to (main).tml
##### Option 2: Link to this project's main page
- Within TouchPortal, create a button named "MSFS"
- Click on the button to open the button editor
- In the sidepanel choose Navigation ->  (Action) Go To Page 
- From the dropdown choose msfstpp_main

### Credits
Thanks to tlewis17 for the cooperative work that is in place between this project and https://github.com/tlewis17/MSFSTouchPortalPlugin
Thanks to AmbitiousPilots for the tool to skip the "Press Any Button" screen https://github.com/AmbitiousPilots/FSJumpStarter2020

