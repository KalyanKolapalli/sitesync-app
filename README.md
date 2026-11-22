# SiteSync – mobile web app prototype

Interactive prototype of **SiteSync**, a construction-site coordination app designed for the University of Leicester module CO4223/CO7223 *Interaction Design and User Experience* (CW1 design portfolio), used for the CW2 user evaluation study.

**Open on a phone:** https://kalyankolapalli.github.io/sitesync-app/

## What it does
- 10 screens from the CW1 design: Dashboard, Notifications, Project comparison, Project details, AI delay insight, Smart calendar, Tasks, Task detail, Material tracking and 3D construction view
- Add, edit and delete projects, tasks and deliveries
- Scan delivery QR codes (live camera, photo of the code, or typed code) – print `SiteSync_QR_Delivery_Labels.pdf` to test
- Attach site photos, offline "Pending sync" behaviour, side-by-side project comparison
- Data is stored only in the browser on each device; use *initials button → Reset demo data* between participants

## Notes
- Demo data and scenario (Riverside Tower, 22 October 2026) are fictional.
- The delay insight uses simple demo rules, not a real prediction model.
- Built from the CW1 Figma design with the help of a generative AI tool (Claude). QR decoding uses [jsQR](https://github.com/cozmo/jsQR) (Apache-2.0).
