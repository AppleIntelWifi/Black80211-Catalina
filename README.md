# Black80211-Catalina

This project aims to be used like a simulator of IEEE80211 stack for MacOS. (only for Catalina)

The intent for this project is to provide a clean base that you can manipulate the 802.11 stack through,
and to eventually write drivers for.

## READ ME FIRST

**THIS ISN'T A WIRELESS DRIVER**
**I WILL NOT PROVIDE SUPPORT.**
**PLEASE DO NOT EMAIL ME OR MAKE ISSUES REGARDING IT NOT WORKING.**
***I WILL SLAP YOU.***

## Known issues

- Unable to unload kext (something is retaining the driver)
- IO80211Interface needs to be populated with the actual variables, and not a massive uint8 array
