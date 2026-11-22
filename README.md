# Frosty Chrome Theme
*A type of nostalgia.*

## How to Test (Local)

1. Open [chrome://extensions](chrome://extensions).
2. Toggle on **Developer mode**.
3. Load unpacked -> choose the folder that contains `manifest.json` (root of this repo).
4. Open a new tab and inspect the new design.

## How to Package for the Chrome Web Store

1. Zip from this folder so `manifest.json` is at the root of the zip, next to `images/` and `icons/`. Do not wrap them in an extra folder.
2. In the [developer dashboard](https://chrome.google.com/webstore/devconsole), add a new item and upload that zip.
3. On the listing, add at least one full-bleed screenshot at 1280×800 or 640×400, pick a theme category, and state that the theme collects no user data.
4. Submit for review. For a later update, increase `version`, zip again, and upload the new zip.
