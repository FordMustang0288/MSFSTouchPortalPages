# MSFSTouchPortalPages

### Setup
First, you must be on version 0.4.0 of the MSFSTouchPortalPlugin (https://github.com/tlewis17/MSFSTouchPortalPlugin). I will update this as I use newer releases.

Pages in MSFSTouchPortalPages are and will become **more dependent** on MSFSTouchPortalPlugin as functionality of that project increases

### Instructions
WARNING! The instructions below **WILL** overwrite your (main).tml. Please backup accordingly.

- Please copy all .tml files in the pages/ folder to %appdata%/Roaming/TouchPortal/pages and all icons in the icons/ folder into %appdata%/Roaming/TouchPortal/icons
- Restart TouchPortal

##### If you already have a (main).tml
- Rename the (main).tml provided with this project PRIOR to copying it into %appdata%/Roaming/TouchPortal/pages
- Within each page in this project you must modify the "back to main" button to redirect to the former (main).tml which was renamed.
