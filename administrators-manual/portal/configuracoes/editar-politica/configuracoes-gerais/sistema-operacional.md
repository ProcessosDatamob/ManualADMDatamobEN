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

# Operating System

In the "**Settings**" tab of the "**Policy Editing**" screen, click on "**Operating System**" to view the device's operating system configuration options. The following table describes the operating system settings.

<table data-header-hidden><thead><tr><th width="241"></th><th></th></tr></thead><tbody><tr><td><strong>Configuration</strong></td><td><strong>Description</strong></td></tr><tr><td>Minimum Android API level</td><td>Considering updates and security, the administrator can set the minimum Android version, which requires users to update their device for it to function properly. The device is not deactivated if it does not have the minimum Android version, but its use is limited to Google apps and calls until the operating system is updated.</td></tr><tr><td>Set automatic date and time</td><td><p>Indicates whether automatic time is mandatory, which prevents the user from setting the date and time manually. The following options can be set:</p><ul><li>User-defined;</li><li>Automatic;</li></ul></td></tr><tr><td>System update policy</td><td><p>The system update policy controls how operating system updates are applied. The configuration options are:</p><ul><li>Automatic within a window - choosing this option enables the update window time setting. The update window will also be applied automatically to Google Play application updates.</li><li>Automatic - Installs automatically as soon as an update is available.</li><li>Postponed - Postpone automatic installation up to a maximum of 30 days.</li></ul></td></tr><tr><td>Time of the update window</td><td>By setting the "Automatic within a window" policy, system updates will be executed within the specified window time. Set the "Start time" and "End time" by clicking on the respective calendars and the desired times.</td></tr><tr><td>Freeze periods for updates</td><td>All incoming system updates (including security patches) are blocked and will not be installed. When a device is outside the freeze period, normal update behavior applies. To set a freeze period, define "Start month and day" and "End month and day" by clicking on the respective calendars. Click on "+Add freeze period" to set other freeze periods. Click on the trash can icon next to the freeze period to delete it.</td></tr></tbody></table>
