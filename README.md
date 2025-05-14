# Credits 

This extension is an upgraded version of AuthAnalyzer with a few additional features.
All credits go to the original authors, and the extension can be found at: https://github.com/PortSwigger/auth-analyzer

# Description

To use the extension, simply download the .jar file from the releases section and add it to your Burp Suite extensions.

## Upgraded features

This upgraded extensions contains the following functionalities:
- Auth Analyzer pauses or stops again after "Repeat request" rather than continuing to run
- Added "Update matching headers in session" button (useful for refreshing Auth Headers after expiry/new login)
- Added "Replace matching headers from session" button (useful for quickly replacing Auth headers in Repeater/Intruder)
- Diff viewer now shows line-by-line differences for JSON data

## Change Log

### v1.0.0

Features:
- Re-pause or re-stop the extension after repeating a request from a different tab
- Added button to automatically update matching Headers in AuthAnalyzer sessions from an existing request
- Added button to automatically update matching Headers in Repeater/Intruder from AuthAnalyzer sessions

![image](https://github.com/user-attachments/assets/d0e71fe9-71fa-4074-9c79-115c5e01dfc6)

Bug fixes:
- Fixed a bug where the config wouldn't update if paused or stopped
- Additional bug fix - config wouldn't update until restarted when paused (also increased repeating delay to 1500ms)

### v1.0.1

Features:
- Added JSON compatibility to diff viewer

## TODO

- Add custom hotkeys to the extension
- Sync scrolling in request/response viewers