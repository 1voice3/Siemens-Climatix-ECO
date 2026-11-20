CLIMATIX ECO POL224 TRAINING SIMULATOR
=====================================

FILES TO UPLOAD
---------------
index.html   Complete interactive simulator, including the exact user-supplied controller photo embedded in the page.
README.txt   These upload, use, wiring-reference, and safety notes.

No separate image file is required. The controller photo is embedded inside index.html, so the page will not show a missing-image placeholder when only these two files are uploaded.

GITHUB UPLOAD
-------------
1. Create a GitHub repository, or open the repository where you want the simulator.
2. Upload index.html and README.txt directly into the repository root. Do not upload only the ZIP file.
3. To publish with GitHub Pages, open the repository's Settings > Pages and select the branch and root folder. Follow GitHub's current help if the options have changed.
4. Open the published site on an iPhone or computer. If an older page version is cached, reload the page or close and reopen the tab after updating the files.

CONTROLLER PHOTO AND INTERACTIVE POINTS
---------------------------------------
The controller photo shown on the simulator is the exact image supplied by the user. Its original JPEG bytes are embedded in index.html. The page positions touch-accessible controls over the pictured LCD, Up/Down/Enter keys, three status LEDs, USB port, and terminal blocks. Tap a terminal block or matching wiring card to read its photo location, terminal functions, and linked manual page.

The wiring groups follow the visible locations on the supplied photograph:
- Upper-left green block: RS485 + / − and isolated ground.
- Middle-left blue block: MAT, OAT, humidity, AUX-AI, return-air sensors, and sensor supply/common.
- Lower-left tan block: VFD command and damper actuator feedback, command, common, and power.
- Upper-right block: configurable auxiliary inputs and outputs.
- Lower-right block: occupancy, thermostat cooling-stage I/O, common, and 24 Vac power.
- Upper-left edge: USB service port.

The digital hotspot outlines and number dots are interactive overlays; they are not markings printed on the original photo. The LCD overlay changes with simulated navigation. LED overlay colors show simulated indications only.

USING THE SIMULATOR
-------------------
- Use the photo's Up, Down, and Enter button hotspots or the remote controls beside the simulator.
- Use Menu − / Menu + as the Enter+Up and Enter+Down category shortcuts.
- Enter starts editing or confirms. Up/Down changes values. Enter saves; Cancel or Esc exits edit mode.
- The menu rail reflects the controller's state split: menus 1–5 are Running State; menus 6–8 are Configuration State. Use 5CONFIG STATE to enter configuration and 8RUN STATE to return to running.
- Search parameters, alarms, learning topics, and wiring locations. Search results navigate to the corresponding menu or open the relevant wiring reference.
- The written path records menu changes, searches, tests, and wiring references. It can be copied or downloaded as a separate text file.
- Alarm injection, tests, LED indications, values, restart, and reset are simulated in this browser only. Demo values and path history are stored in browser local storage.

SUGGESTED LEARNING PATH
-----------------------
1. Menu 5: locate 5CONFIG STATE and confirm 5ENTER CONFIG?.
2. Menu 6: review I/O configuration, including occupancy, sensors, outputs, and 6FAN.
3. Menu 7: learn the damper and output tests. Simulator tests do not actuate equipment.
4. Menu 8: select 8RUN STATE and confirm 8ENTER RUN?.
5. Menus 3 and 2: review Advanced Settings and Basic Settings while in Running State.
6. Menu 1: monitor status. Menu 4: inspect alarms and diagnostics.
7. Menu 8 also contains 8FACTORY DEF. Study its purpose and risk; do not use it routinely.

The linked videos describe menus 1–5 as Running State and menus 6–8 as Configuration State. The guided route respects that state transition and visits menu 7 testing before returning to Running State. 8FACTORY DEF is destructive on actual equipment; the simulator's reset affects only its local demo values.

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

Wiring menu references open the official guide at the relevant printed page: wiring tables on pages 10–11, peripheral connection examples on pages 12–13, LED indications on page 15, and firmware update on page 30. Manual PDF page-anchor behavior depends on the viewer; each link also displays the printed page number.

SAFETY AND SCOPE
----------------
This is an independent educational simulator. It does not connect to, control, or validate a Siemens POL224 or any HVAC equipment. It is not an official Siemens product. Wiring summaries are transcribed from the supplied application guide and associated with the locations visible in the user's photograph; confirm the actual terminal labels, controller model, installation drawing, signal type, and equipment-specific wiring diagram before any field work. Isolate power and use qualified personnel and current manufacturer instructions. The location overlay is a learning aid, not a wiring authorization.