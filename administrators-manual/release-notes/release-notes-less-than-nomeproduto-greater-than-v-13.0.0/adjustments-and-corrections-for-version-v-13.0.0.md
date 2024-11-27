# Adjustments and Corrections for Version - V 13.0.0

In this version, the following corrections have been made:

**Settings - Manage Policies - Edit Policy - Screen** - After formatting and activating devices in the portal, an issue was identified where devices did not automatically adopt the wallpaper set as default in the policy, even when the "Disable Wallpaper Change" function was disabled. To resolve this, a control was implemented in the "Screen" configuration that automatically reapplies the wallpaper when modifying the policy, eliminating the need to upload the wallpaper again and ensuring that settings are correctly applied.

**Remove Screen Lock (Block SIM)** - Upon unlocking the screen, especially after the device had been turned off, the message: “Pin it to use only this app?” appeared repeatedly. Even when selecting the option to pin, the message continued to display. To fix this issue, the behavior of Block SIM was adjusted so that the message does not reappear after the app is activated, allowing the user to use the device normally after unlocking.

**Mob Settings** - There was an error when installing the Mob Settings app in Kiosk Mode, where attempting to enable Bluetooth caused the app to close automatically, preventing access to Bluetooth settings and the use of this function on the device. To resolve the problem, the app's behavior was adjusted to ensure that Bluetooth settings can be accessed and modified correctly, even with Kiosk Mode active.
