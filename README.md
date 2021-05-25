# NI Add-on Guide

## Uploading wardrobe from iOS
1. Download [iMazing](https://imazing.com).
2. Connect your iPhone by cable.
3. On the app view, scroll to the bottom and click `New Shortcut`. Add LN.
4. Click LN.
5. Click on `clothes_date...`.
6. Click `Copy to Mac` or whatever equivalent.
7. Upload that file to NI in the [user page](https://my.nikkis.info/user/ln).

## Adding User Scripts
This is a snippet of code that is run when you go on NI. No information is saved! The script will only be run on NI.

Additional features include:
* Wardrobe page
  * Add wardrobe items by number
  * Add by suit
  * Store completion
  * Checking for safe decompose
* Item page
  * Drop location tags
  * Identify items necessary for crafting
* Stage pages
  * Show base score for arenas in initial page + if new items exist
  * Show commission stage base scores by progress
* and more...

All the features that [holatuwol](https://github.com/holatuwol/myni-userscript) implemented (and how they work) are described in the `features.md` file.

### Safari
1. Install the [UserScripts extension](https://apps.apple.com/us/app/userscripts/id1463298887?mt=12).
2. Open the extension and click on `Open Safari Preferences`. Enable UserScripts and give it whatever permissions.
3. In Safari, to the left of the address bar on top, click the `</>` icon > `Open`.
4. In the new Safari window, click `+` > `New Javascript`.
5. Copy the script from [here](https://openuserjs.org/scripts/holatuwol/Nikkis_Info_Add_By_Number/source) and paste into TamperMonkey's new script
6. Save.
7. Open NI and the features should show up.

### Chrome
1. Install the [TamperMonkey extension](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=en)
2. Click the new extension icon > `Create a new script...`.
3. Copy the script from [here](https://openuserjs.org/scripts/holatuwol/Nikkis_Info_Add_By_Number/source) and paste into TamperMonkey's new script.
4. Save.
5. Open NI and the features should show up.