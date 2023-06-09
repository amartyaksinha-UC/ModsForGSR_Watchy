Hi! Welcome to ModsForGSR_Watchy. This repository is made to document my efforts to supplement [the excellent Watchy_GSR watchface developed by GuruSR](https://github.com/GuruSR/Watchy_GSR). I will add modded files to add/enhance features to this watchface. Please refer to the original repo for installation instructions. All modified files are available in /Modified files to be used in src/ and /src/1.4.7/filename.extnsn
IMPORTANT: To use modified files, rename the modded file by removing the "Modded_" prefix (so, rename "Modded_WatchyClassicsAddOn.h" to "WatchyClassicsAddOn.h") and place it in the GSR folder replacing the original file before compiling. Built on version 1.4.7A of GSR_Watchy.

* "Modded_Watchy_GSR.cpp"
*   Added homescreen shortcut to cycle through watchfaces (ie, when menu is not selected) using the Up (SW3) and Down (SW4) buttons.
*   Added homescreen shortcut to switch between light and dark borders via SW1 + SW4 button press (Menu and down pressed together)

* "Modded_WatchyClassicsAddOn.h"
*   Added working secondary time zone thanks to using code from [Thomas Habets' watchy-face](https://github.com/ThomasHabets/watchy-face). 
*   Removed "Basic" watch face using modified WatchyClassicsAddOn file named as "Modded_WatchyClassicsAddOn.h" in aforementioned locations. Secondary clock added, planning to add a multi-timezone feature by being able to switch between multiple secondary timezones on the homescreen.
