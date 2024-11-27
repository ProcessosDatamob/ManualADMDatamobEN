# Adjustments and Corrections of Version - V 12.0.0

In this version, the following corrections have been made:

* **Remove SIM Lock (Block SIM)** - When sending the Remove SIM Lock command from the Devices menu in the portal, the screen lock was being removed incorrectly.
* **Remove Screen Lock (Block SIM)** - When the Remove Screen Lock command was sent to the device from the Devices menu in the portal, the device continued to prompt for the password. Even when trying to enter the previous password or any other password, access was not granted.
* **Settings - Manage Policies - Edit Policy** - In the Applications tab, the footer counter on the policy applications page was incorrect, as it did not reflect the actual number of applications included in the policy, showing a number lower than the actual quantity.
* **Settings - Manage Wi-Fi Networks** - The SSID Password field was mandatory, so when selecting a WPA-EAP network that does not require this type of password, the system would not allow saving the network without filling in the field.
