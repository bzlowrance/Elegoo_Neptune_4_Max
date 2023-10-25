Hey I'm not sure where the latest update came from but I found a later release here.
https://github.com/eafq78/Neptune-4MAX

1.2.2.39
and 
1.2.2.11

# Elegoo_Neptune_4_Max

Firmware update files for the Elegoo Neptune 4 Max provided to MandicReally by Elegoo.
- Elegoo Neptune 4 Max: https://tinyurl.com/Neptune4Max (affiliate link)
- 

As of today (10/25/2023) the latest release in this repository is:
- Mainboard Firmware: [1.2.2.34](4max-Firmware/1.2.2.34/ELEGOO_UPDATE_DIR)
- Screen UI Firmware: [1.2.9](UI_Touchscreen_Firmware_N4Max/ui_1.2.9_20230926.tft)
 
**NOTE:** Please check Elegoo's website or repository for the latest releases. These were provided to me on October 17th 2023 (10/17/2023).
- Elegoo's Firnware GitHub Repository: https://github.com/NARUTOfzr
- Elegoo's Main Github: https://github.com/elegooofficial
- Elegoo's Website: https://www.elegoo.com/pages/3d-printing-user-support

<h2>Update Instructions:</h2> ( Clarified by MandicReally based on Elegoo's DOC.)

<h3>Mainboard:</h3>

- Ensure the Neptune 4 Max is properly powered & won't accidentally shut off.
- Extract ZIP file contents to your computer.
- Insert the USB stick from the machine into your computer.
- Copy the contents of the firmware version folder onto the root directory of your USB Stick.
- Safely Eject USB Stick.
- Insert USB stick into Machine.
- Navigate through the touchscreen UI: [Settings] -> [Information]
- Press the Upward pointing arrow at the bottom of the screen.
- Follow the on screen prompts.
- DO NOT Power off the machine until Firmware Update is complete.
- Check the Firmware Version in the [Settings] -> [Information] menu to see if it matches version you attempted to install.
- IF Firmware Version DOES NOT Match, reattempt installation. (I had to do this twice before it actually took.)

<h3>Touchscreen Firmware:</h3>

- Power off the machine.
- Extract the Firmware file to your computer: (UI_4&4Pro-Universal firmware)
- Take the provided MicroSD card (TF Card) & insert it into your computer.
- Copy the Firmware .tft File to the root directory of the SD card.
- Safely Eject SD card from computer.
- Remove the touchscreen from its cradle.
- Flip over touchscreen & remove the 4 screws on the back housing.
- Remove the back housing.
<img src="/UI_Touchscreen_Firmware_N4Max/Images/Housing01.png" alt="Back Housing" style="max-width: 100%;">

- Insert the SD Card into the SD Slot on the Touchscreen board.
<img src="/UI_Touchscreen_Firmware_N4Max/Images/SD_Slot.png" alt="SD Slot" style="max-width: 100%;">

- Set aside screen ensure it doesn't touch anything conductive, have the screen visible.
- Power on the Machine, DO NOT POWER OFF UNTIL UPDATE IS COMPLETE.
- Screen should display update text:
<img src="/UI_Touchscreen_Firmware_N4Max/Images/Update_01.png" alt="Update Text Start" style="max-width: 100%;">

- Update is complete when following text displays
<img src="/UI_Touchscreen_Firmware_N4Max/Images/Update_02.png" alt="Update Text Complete" style="max-width: 100%;">

- Power off Machine.
- Remove SD Card from Touchscreen Board
- Reassemble Touchscreen housing.
- Done.

<h4>WARNING:</h4> This firmwre is provided AS-IS from Elegoo to MandicReally. MandicReally makes no claims of safety, security, or code integrity. We are NOT RESPONSIBLE for any issues or errors this firmware or installation of it may cause. Use and update at YOUR OWN RISK.

<h4>License:</h4> Released under GPL-3 Open Source License. Source files not provided by Elegoo for this specific release yet. Check Elegoo's Repositories for updated information.
