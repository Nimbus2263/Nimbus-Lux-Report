NIMBUS OPTIMA PREMIUM LUX REPORT GENERATOR

CONTENTS
- index.html: responsive premium report generator
- manifest.json: installable web app metadata
- service-worker.js: offline caching after first visit when hosted over HTTPS

START
1. Extract the ZIP.
2. Open index.html in a modern browser.
3. Enter project details, upload the official logo image, add all rooms, and verify fixture data/CU/MF.
4. Select Generate / Save PDF. In the print dialog, choose Save as PDF.
5. Use Export project backup to save your inputs and uploaded logo as JSON; use Import project to restore them later.

ANDROID / WEB INSTALL
Host the files on an HTTPS website to enable PWA installation and service-worker offline caching. Open the hosted URL in Android Chrome and select Install app / Add to Home screen. This package is not a signed APK.

CALCULATION LIMITATIONS
Eavg = (N x lumens per fixture x CU x MF) / area. Room index K = (5 x L x W) / (Hm x (L + W)). This version does not calculate point-by-point illuminance, minimum/maximum lux, uniformity, glare, or photometric heatmaps. Starter fixture data is example data and must be verified before client issue.

LOGO
The official logo was not bundled because its original image asset was not available to this build. Upload the original logo through the app; it will be embedded unchanged in the report and project backup.
