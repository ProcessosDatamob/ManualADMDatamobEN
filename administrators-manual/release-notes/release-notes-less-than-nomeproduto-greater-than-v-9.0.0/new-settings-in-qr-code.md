# New Settings in QR Code

On the "Registration Token" screen of a policy, new fields have been added to facilitate the device enrollment process. They are as follows:

* Manage Wi-Fi Networks - You can select one of the Wi-Fi networks configured on the "Manage Wi-Fi Networks" screen. By selecting a network, the system will include all possible configurations in the QR Code, covering the following security types: WPA/WPA 2, WEP, and no security. When enrolling with the QR Code, the device will automatically connect to the configured network, simplifying the initial device setup process.
* Skip Encryption - By enabling this option, the system will include the following information in the QR Code: "android.app.extra.PROVISIONING\_SKIP\_ENCRYPTION": (true/false - default “false"). When enrolling with the QR Code, the device will skip device encryption during the initial setup process.
* Use Mobile Data - By enabling this option, the system will include the following information in the QR Code: “android.app.extra.PROVISIONING\_USE\_MOBILE\_DATA": (true/false - default “false"). When enrolling with the QR Code, the device will use mobile data during the initial setup process.
