# FlightEye Matt's Planet Edition: update files

This repository holds the update files the FlightEye Matt's Planet Edition device downloads
when you tap **Update** in recovery mode. There is nothing to install by hand.

- `manifest.txt` names the latest version, its size and its SHA-256 checksum.
- `releases/` holds the firmware files. The device checks the checksum before it switches to a new version.
