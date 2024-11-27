---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Safety

In the "**Settings**" tab of the "**Policy Editing**" screen, click on "Safety" to view the device's security configuration options. Click on the selector buttons to enable or disable a setting. The following table describes the security settings.

<table data-header-hidden><thead><tr><th width="252"></th><th></th></tr></thead><tbody><tr><td><strong>Configuration</strong></td><td><strong>Description</strong></td></tr><tr><td>Google Play Protect Verification</td><td>Allows the administrator to define whether Google Play Protect app verification will be enforced on managed devices. This ensures that all installed apps are automatically checked for security threats. The administrator can choose to enforce this verification on all devices or allow the user to decide whether to activate it, providing greater control over the security of installed apps.</td></tr><tr><td>Block account changes</td><td>If enabled, the option to add or remove accounts is disabled.</td></tr><tr><td>Account types with management disabled</td><td>The device will block the creation of accounts from all domains that have been entered in the "Account types with management disabled" setting, and will allow the creation of accounts from any other domain</td></tr><tr><td>Block factory reset</td><td>Once enabled, factory reset is blocked.</td></tr><tr><td>Administrator's e-mail for FRP</td><td>Allows you to define the e-mail address that will be requested when you reset the device</td></tr><tr><td>Block SD Card</td><td>If enabled, mounting external physical media is blocked.</td></tr><tr><td>USB Transfer Settings</td><td>Defines which files and/or data can be transferred via USB. This does not affect charging functions. Note: The "Disallow transferring all types of data" option is only compatible with devices running Android 12 or later and with USB HAL 1.3 or later.</td></tr><tr><td>Untrusted applications policy</td><td><p>This setting establishes restrictions on the installation of applications from unknown sources. The restriction options are:</p><ul><li>do not allow installations of untrusted applications;</li><li>allow installations of untrusted applications.</li></ul><p>NOTE: For this setting to work, the Google Play app selection mode must be set to OPEN, see details in the Apps section.</p></td></tr><tr><td>Permission policy</td><td><p>Defines default permission policy for permission requests in applications. There are three options that can be set:</p><ul><li>Allow Automatically;</li><li>Deny Automatically;</li></ul></td></tr><tr><td>Developer settings</td><td><p>Use this setting to restrict the use of developer mode where more resources are released to the application developer. This setting can be:</p><ul><li>Disable developer settings;</li><li>Enable developer mode settings.</li></ul></td></tr><tr><td>Encryption policy</td><td><p>Allows you to select the required encryption policy. There are three options that can be selected:</p><ul><li>Activate without password </li><li>Activate with password </li><li>Disabled</li></ul></td></tr><tr><td>Enable private key selection</td><td>It allows the interface on the device to be shown so that the user can choose a private key alias if there are no private key rules defined. On devices below Android 9, the setting can leave corporate keys vulnerable.</td></tr><tr><td>Private key selection rules</td><td>Identify the rule that allows the private key to be read. To define the private password rules, click add and complete the Name, URL and Application fields. Then click Save.</td></tr></tbody></table>
