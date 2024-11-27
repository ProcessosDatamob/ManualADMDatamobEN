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

# Managed Google Play

Managed Google Play allows you to select the applications that will be available for download on the company's devices.

Once you have entered the Administration Portal, one of the first steps is to define which applications you want to manage for your organization. In the "[Application Management](./)" menu, you can manage all the applications authorized for installation on your Android devices. You can manage three different types of applications:

* **Public apps** - apps available in the public Google Play Store;
* **Private apps** - your own Android apps for your company;
* **Web Apps -** turn a web page into an Android application.

To access Google Play Managed, go to the "**Application Management**" menu and select "**Google Play Managed**".

<figure><img src="../../../.gitbook/assets/Captura de tela 2024-05-15 180510 (1).png" alt=""><figcaption></figcaption></figure>

1. Click on the category you want to show more apps in that category.
2. The "See more" button shows more apps in the same category.

### Public Applications <a href="#id-2et92p0" id="id-2et92p0"></a>

To choose a public app, go to the "Managed Google Play" menu. The home screen already has the "**Search the Play Store**" option open. Click on the app and the app information screen will open. To select it, click on the "Select" button.&#x20;

When you select an application, the system will ask you to confirm it before adding it to the list of applications. Click on "**Confirm**" to include the application or choose "**Cancel**" to not include it.

To see a list of the applications included, go back to the "[**Managed Applications**](aplicativos-gerenciados.md)" screen. For more settings on application policies, see the [**Manage Policies**](../configuracoes/gerenciar-politicas/) section.

### Private Applications <a href="#tyjcwt" id="tyjcwt"></a>

To upload your company's own applications, follow these steps:

1. Go to the "**Private Applications**" icon;
2. Click on the cross "+" that appears at the bottom right of the screen;
3. Specify the name of your application in the Title field and upload your APK file.

{% hint style="danger" %}
**IMPORTANT**

Private apps must have a unique package name that has not been used before when uploaded to your managed Google Play store.
{% endhint %}

### Web Applications <a href="#id-3dy6vkm" id="id-3dy6vkm"></a>

A "**web app**" turns a web page into an Android application, making it easier to find and use on mobile devices.

To create a web application, follow these steps (numbered in the image below):

1. Go to the "Web Apps" menu;
2. Click on the plus button in the bottom right-hand corner of the screen;
3. Specify a title that will be displayed on the device, in the managed Play Store and in the company's list and apps
4. Specify the URL where web applications open
5. Choose a screen mode that defines how the web application is displayed on the mobile device.
6. Define an icon for the web application to help users identify it. Icons are optional, but recommended.
7. Click on create.

Once an application has been registered, it will appear on the screen, as can be seen in the figure below. You can add as many applications as you need.

Clicking on the application brings up the screen for editing the web application, as can be seen in the following image. The buttons positioned below the screen allow you to:

8. Select the Application for inclusion in the company's Managed Applications.
9. Edit the application's settings and icon.
10. Delete the app from Google Play Managed.

{% hint style="warning" %}
**IMPORTANT**

Deleting an app from Managed Google Play and not deleting it from the Managed Apps list can cause inconsistencies if the app is, or already is, linked to a policy. For this reason, whenever you delete an app from Managed Google Play, also delete it from the company's Managed Apps list and from all policies that use this app.
{% endhint %}
