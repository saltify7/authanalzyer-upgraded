# Credits 

This extension is an upgraded version of AuthAnalyzer with a few additional features.
All credits go to the original authors, and the extension can be found at: https://github.com/PortSwigger/auth-analyzer

# Description

## Upgraded features

This upgraded extensions contains the following functionalities:
- Re-pause or re-stop the extension after repeating a request from a different tab
- Added button to automatically update matching Headers in AuthAnalyzer sessions from an existing request (useful for refreshing Auth Headers after expiry/new login)
- Added button to automatically update matching Headers in Repeater/Intruder from AuthAnalyzer sessions (useful for quickly replacing Auth headers in Repeater)

![image](https://github.com/user-attachments/assets/d0e71fe9-71fa-4074-9c79-115c5e01dfc6)

## Bug fixes

- Fixed a bug where the config wouldn't update if paused or stopped
- Additional bug fix - config wouldn't update until restarted when paused (also increased repeating delay to 1500ms)


## TODO

- Add custom hotkeys to the extension
- Add beautified JSON diff
  - (maybe) Set "show diff" button to remember if diff was expanded
- Sync scrolling