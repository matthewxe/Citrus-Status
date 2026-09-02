# Citrus Status (Chrome Extension)

Adds emoji status indicators and activity-level solved fractions to the UPD Online Judge at https://oj.dcs.upd.edu.ph/.

## Features
- 😊 Emoji before problems based on verdict
  - ✅ Accepted (AC)
  - ❌ Wrong Answer (WA)
  - ⏰ Time Limit Exceeded (TLE)
  - 💾 Memory Limit Exceeded (MLE)
  - ⚠️ Invalid Return (IR)
  - 👀 Compile Error (CE)
- 🟠 Activity-level progress fraction (e.g., 9/10)
- 💾 Local storage of statuses (no server)

## Sample Screenshots
![Screenshot Sample 1](./assets/screenshot_1.png)
![Screenshot Sample 2](./assets/screenshot_2.png)

## Install (Developer Mode)
Instead of getting the extension verified at an official extension store, we
will install it via developer means.
### Chrome
1. Download the `Citrus-Status-master.zip` and extract (or clone the repo).
2. Go to manage your extensions page (e.g. `chrome://extensions` or
   `brave://extensions`).
3. Toggle **Developer mode**.
4. Click **Load unpacked** and select the `Citrus-Status` folder.
### Firefox
1. Download the `Citrus-Status-master.zip` and extract (or clone the repo).
2. Go to manage your extensions page (e.g. `about:addons`).
3. Click the gear icon on the top right and then **Debug Add-ons**
4. Click **Load Temporary Add-on...** and select the `manifest.json` inside the
   `Citrus-Status` folder.
   > [!NOTE] Because it is a temporary add-on, you would need to add this add-on
   > every time you reopen Firefox.

## License
GNU GENERAL PUBLIC LICENSE Version 3
