# KNX Leads app

Installable offline web app (PWA) for working through KNX partner leads.

This repository holds only the app. The lead data (`leads.json`) is not stored here: on each
device, open the app, install it, then tap **Load leads file** once. Status and notes stay on
the device (IndexedDB); use **Backup** / **Restore** to move them between devices.

Built from `leads/knx-electricians/pwa/` in the volotech-website repository
(`python3 s08_export.py`, then copy `output/pwa/` here without `leads.json`).
