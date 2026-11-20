CLIMATIX ECO POL224 TRAINING SIMULATOR
=====================================

FILES
-----
index.html   The complete offline-capable training simulator. It uses no subfolders, packages, or external JavaScript libraries.
README.txt   These upload and training notes.

GITHUB UPLOAD
-------------
1. Create a GitHub repository, or open the repository where you want the simulator.
2. Upload index.html and README.txt directly into the repository root (not into a nested folder).
3. To publish it with GitHub Pages, open the repository's Settings > Pages and select the branch and root folder. GitHub Pages setup can change over time; use GitHub's current help if the options differ.
4. Open the published index.html on an iPhone or computer. The layout adapts to a narrow touchscreen; the simulator works locally in a modern browser as well.

USING THE SIMULATOR
-------------------
- Use the physical-style Up, Down, and Enter keys on the illustrated panel, or the remote key panel beside it.
- Use Menu − / Menu + as the Enter+Up and Enter+Down category shortcuts.
- Enter edits a setting; Up/Down changes it; Enter saves; Cancel/Esc leaves edit mode.
- The menu rail reflects the real mode split: menus 1–5 are Running State; menus 6–8 are Configuration State. Use 5CONFIG STATE to enter configuration and 8RUN STATE to return to running.
- Search a parameter, alarm, or training topic to navigate to its menu and record the route. The written path can be copied or saved as a separate .txt file.
- Alarm injection, tests, LED indications, values, restart, and reset are simulated in this browser only. The app stores demo settings and route history in browser local storage.
- Factory reset is included for training recognition. It is not a normal commissioning step. The simulator's reset does not affect real equipment.

SUGGESTED LEARNING PATH
-----------------------
1. Menu 5: locate 5CONFIG STATE and confirm 5ENTER CONFIG?.
2. Menu 6: review I/O configuration, including occupancy, sensors, outputs, and 6FAN.
3. Menu 7: learn the output tests. Simulator tests do not actuate equipment.
4. Menu 8: select 8RUN STATE and confirm 8ENTER RUN?.
5. Menus 3 and 2: review Advanced Settings and Basic Settings while in Running State.
6. Menu 1: monitor status. Menu 4: inspect alarms and diagnostics.
7. Menu 8 also contains 8FACTORY DEF. Study its purpose and risk; do not run it routinely.

The user-requested conceptual order (5, 6, 3, 2, 8, with monitoring in 1, alarms in 4, and tests in 7) is represented in the guided route, with an explicit note where the actual controller requires a state transition. The videos explain that menus 1–5 are Running State and menus 6–8 are Configuration State; menu 7 testing is therefore visited before returning to Running State.

REFERENCE LINKS
---------------
Official Siemens POL224 Climatix ECO Application Guide (PDF):
https://support.industry.siemens.com/cs/attachments/109800504/A6V12632958.pdf

Siemens document page supplied with the request:
https://sid.siemens.com/r/A6V12632958/17754496907_21362430091__en-US_20769531787

Video 1 — Siemens POL224 front-face programming / basic setup:
https://youtu.be/E8XoByFuk94?feature=shared

Video 2 — Siemens economizer controller setup and menu walkthrough:
https://youtu.be/I1mxRCr_2y0?is=4TsPkLBNWeyX6lFa

The simulator's manual arrows open the official PDF at relevant page numbers in a separate tab. In-browser PDF page anchors depend on browser behavior; the printed page number is also shown beside each reference.

SAFETY AND SCOPE
----------------
This is an independent educational simulator. It does not connect to, control, or validate a Siemens POL224 or any HVAC equipment. It is not an official Siemens product. Display labels and documented menu references are based on the provided Climatix ECO application guide and the linked videos. The real controller may show dynamic or different items depending on the application and configuration. Follow current manufacturer documentation, qualified commissioning procedures, and applicable codes for all field work.
