[WA-SL]: https://fouadraheb.com/dl/storage/ipa/1768147037295-5m3b6/net.whatsapp.WhatsApp_25.37.76_watusi3_1.3.1_sl.ipa
[WA-SL-Duplicate]: https://fouadraheb.com/dl/storage/ipa/1768147037295-mo87f/com.fouadraheb.watusi_25.37.76_watusi3_1.3.1_sl.ipa
[SMB-SL]: https://fouadraheb.com/dl/storage/ipa/1768147037295-kai2b/net.whatsapp.WhatsAppSMB_25.37.76_watusi3_1.3.1_sl.ipa
[SMB-SL-Duplicate]: https://fouadraheb.com/dl/storage/ipa/1768147037295-7hc8t/com.fouadraheb.watusiSMB_25.37.76_watusi3_1.3.1_sl.ipa
[WA-TS]: https://fouadraheb.com/dl/storage/ipa/1768147037295-rgvnw/net.whatsapp.WhatsApp_25.37.76_watusi3_1.3.1_ts.ipa
[SMB-TS]: https://fouadraheb.com/dl/storage/ipa/1768147037294-ujjhs/net.whatsapp.WhatsAppSMB_25.37.76_watusi3_1.3.1_ts.ipa
[WA-TS-NoPlugins]: https://fouadraheb.com/dl/storage/ipa/1768147037294-yrt5s/net.whatsapp.WhatsApp_25.37.76_watusi3_1.3.1_ts_noplugs.ipa
[SMB-TS-NoPlugins]: https://fouadraheb.com/dl/storage/ipa/1768147037291-2my0i/net.whatsapp.WhatsAppSMB_25.37.76_watusi3_1.3.1_ts_noplugs.ipa


[builds-io-watusi]: https://builds.io/apps/watusi/?aid=1025553
[builds-io-watusi-duplicate]: https://builds.io/apps/duplicatewhatsappwatusi/?aid=1025553
[builds-io-watusi-business]: https://builds.io/apps/whatsappb/?aid=1025553

[flekstore-link]: https://flekstore.com/wa
[kravasign-link]: https://kravasign.com/fouadraheb
[changelogs-link]: https://apt.fouadraheb.com/package/com.fouadraheb.watusi3/changelogs

<p align="center">
<a href="https://patreon.com/FouadRaheb">
<img align="center" src="images/regram.png">
</a>
</p>


<h1 align="center">
Watusi for WhatsApp
</h1>
<p align="center">
The all-in-one tweak for WhatsApp Messenger!
</p>

# How to install Watusi

### Jailbroken Devices

Add __[https://apt.fouadraheb.com](https://apt.fouadraheb.com)__ to your Cydia/Zebra/Sileo sources and download it from there. 

(Check [this page](https://appledb.dev/device-selection/) for more info on how to jailbreak your device if possible)

### Sideloading (No Jailbreak)

* (Option 1) Download IPA file from here and follow the below [Sideloading with AltStore](#sideloading-with-altstore) instructions to sign and install the app from your computer. You can also follow the [Sideloading as a linked device](#sideloading-as-linked-device-push-notifictions--icloud-backup) tutorial to sideload a duplicate and still receive push notifications from original.

    <sub>The following IPA files have `Plugins` folder deleted and include some fixes to avoid WhatsApp crashing when not signed with proper entitlements and a developer account.</sub>
    | Application | Bundle | Version | Watusi 3 |
    | ------------------ |:---------:|:------:|:------:|
    | [WhatsApp][WA-SL] | net.whatsapp.WhatsApp | 25.37.76 | 1.3.1 |
    | [WhatsApp Duplicate][WA-SL-Duplicate] | com.fouadraheb.watusi | 25.37.76 | 1.3.1 |
    | [WA Business][SMB-SL] | net.whatsapp.WhatsAppSMB | 25.37.76 | 1.3.1 |
    | [WA Business Duplicate][SMB-SL-Duplicate] | com.fouadraheb.watusiSMB | 25.37.76 | 1.3.1 |

    <sup>Stalky, OnlineNotify, and ContactSync tweaks are disabled by default and can be enabled from inside Watusi Settings.</sup>
    
* (Option 2) You can use a signing certificate to download the latest Watusi directly to your device and keep it valid for 1 year instead of just 7 days.<br/>[Flekstore][flekstore-link] is one of the most reliable options for sideloading, you can add our sideloading source (https://source.fouadraheb.com) to it to download the apps directly.

### Sideloading (TrollStore)
* If you are on <b>iOS 14 - 16.6.1</b> (iPhone X - A11 and older) or <b>iOS 14 - 16.6 beta 1</b> (iPhone 11 and newer), install with TrollStore to receive push notifications and use iCloud features:

    * Install [TrollStore](https://github.com/opa334/TrollStore) (or [this guide](https://ios.cfw.guide/installing-trollstore/))
    * Install and activate WhatsApp from the AppStore
    * Download the IPA file from the table below
    * Open IPA in TrollStore
    * Install to overwrite original WhatsApp


    <sub>The following IPAs binary and plugins are fake-signed with their original entitlements. They do not include any fixes for WhatsApp, so THEY WILL CRASH if not used in TrollStore or not signed with proper certificate and entitlements.</sub>
    | Application | Bundle | Version | Watusi 3 |
    | ------------------ |:---------:|:------:|:------:|
    | [WhatsApp][WA-TS] | net.whatsapp.WhatsApp | 25.37.76 | 1.3.1 |
    | [WA Business][SMB-TS] | net.whatsapp.WhatsAppSMB | 25.37.76 | 1.3.1 | 4.2.7 | 3.5.0 |
    
    <sup>Stalky, OnlineNotify, and ContactSync tweaks are disabled by default and can be enabled from inside Watusi Settings.</sup>

    If you have issues with notifications, try using the below TrollStore IPAs that doesn't inject into WhatsApp extensions. This issue used to happen a few years ago on jailbroken devices (I wrote [this blog](https://blog.fouadraheb.com/posts/service-extension-notifications/#how-they-are-related) post about it back then)
    | Application | Bundle | Version | Watusi 3 |
    | ------------------ |:---------:|:------:|:------:|
    | [WhatsApp][WA-TS-NoPlugins] | net.whatsapp.WhatsApp | 25.37.76 | 1.3.1 |
    | [WA Business][SMB-TS-NoPlugins] | net.whatsapp.WhatsAppSMB | 25.37.76 | 1.3.1 |
    

## Sideloading Guides

<details>
<summary><h2>Sideloading with AltStore</h2></summary>

### Requirements

1. A computer running macOS or Windows
2. Internet connection
3. Apple ID (email & password)
4. If you are on iOS 16, you may need to enable Developer Mode. (Settings > Privacy & Security > Developer Mode)

### AltStore

* Download and install AltServer from [here](https://altstore.io)

* Right-click on the AltServer icon with your phone connected and choose "Install AltStore", then the name of your phone. When prompted sign in with your Apple ID. Two-factor Authentication is supported, but app-specific passwords are not.

* Make sure no other WhatsApp with the same bundle identifier is installed. (net.whatsapp.WhatsApp if you chose the original IPA or com.fouadraheb.watusi for the duplicate)

* If you have AltStore Beta, you can add our AltStore source (https://source.fouadraheb.com) and download apps directly from AltStore.

* If you don't have access to AltStore sources, download the IPA file from the link above and copy it to your phone, using iCloud Drive, AirDrop, or any other method. Open AltStore and navigate to the "My Apps" tab. Choose the plus in the top right corner and open the IPA file. When prompted sign in with your Apple ID. Two-factor Authentication is supported, but app-specific passwords are not.
</details>

<details>
<summary><h2>Sideloading as linked device (Push Notifictions + iCloud Backup)</h2></summary>

Since WhatsApp added the option to link a device on mobile, you can now use the original WhatsApp from the AppStore and install Watusi IPA as a duplicate and link your original WhatsApp to it.

* Install and activate original WhatsApp from the AppStore
* Download and install [duplicated Watusi IPA](#sideloading-no-jailbreak) from the table above.
* We need to enable Watusi's `Local Notifications` feature on your duplicate to keep the app active while linking.
  * Open duplicated Watusi, from the welcome screen, tap 3 times on the animated image and select `Watusi` preferences, go to the `Notifications` section and activate `Enable Local Notifications`, and set it to `Audio` (If `Audio` doesn't work, try `Location` instead).
* Move back to the welcome screen, tap `Agree and Continue`, and click on `Link this device` to get the QR Code. Screenshot this code and send it to another device. (Keep Watusi open in background)
* Switch to your original WhatsApp
  * Go to `Settings > Linked Devices > Link a Device`
  * Scan the QR code from your other device and wait for it to link and load your chats. The QR code is only valid for less than a minute.
* Disable `Enable Local Notifications` feature from your duplicated app Watusi settings. Keeping it enabled is known to cause a logout and will require linking again.

You will now receive notifications from your original WhatsApp and use the duplicated app with Watusi and other tweaks.

Tips:
* You can remove the original WhatsApp from your home screen so you only use the duplicated app.
* You can create automation from the Shortcuts app to have your duplicated app open automatically when opening the original WhatsApp (especially from notifications).
* Turn off the notifications for the duplicated app from iOS notifications settings so you don't receive notifications when the duplicate is in the background.
* Make sure to open the original WhatsApp from time to time to keep chats in sync and backed up to iCloud.

</details>

<details>
<summary><h2>Manually Backup and Restore Chats</h2></summary>

Note: if you are using a duplicate as linked-device, you don't need to do this method as the chats will be sycned from main WhatsApp.

Chats cannot be restored from iCloud to Sideloaded Watusi. However, you can manually back up and restore your chats in case you need to delete and reinstall the app.

The currently installed app must have the "Document Browser" feature enabled to access its data from the Files app. (All Watusi IPAs have this option enabled by default)
    
1. Open the Files app and go to the WhatsApp folder.
2. Select all items and copy them.
3. Go back, create a new folder, and paste what you copied earlier.
4. Delete WhatsApp from your device.
5. Install the latest version of Watusi IPA, open it once, then close it from the background.
6. Return to the Files app, go to the backup folder you created earlier, and copy all items.
7. Go back to the WhatsApp folder, delete everything inside, then paste what you copied earlier.
8. Open WhatsApp and complete the registration process. Your chats should now be restored.
</details>

## Version History
You can check Watusi's release notes from [this page][changelogs-link].<br/>
Some versions are first released for Jailbroken devices and later for Sideloading.

## FAQ
* If you receive "Please sign in with app-specific password" error, that's because you have 2-factor authentication enabled for your Apple ID. You have to go to Apple's website https://appleid.apple.com, log in with your account and create an app-specific password to use as your Apple ID password.
* Signing the app with a non-developer account will have it expire in 7 days, but AltStore automates re-signing as long as it is connected to your PC.
* The app will not receive Push Notifications and you won't be able to use iCloud features (Except for TrollStore on supported devices).

## Support
If you need any assistance or have a feature request, feel free to contact us through the following channels.
* Join our [Discord server](https://discord.gg/8z3zY93) and use the corresponding channel
* Use the Contact Support button from the tweak settings
* Send an email directly to [support@fouadraheb.com](https://fouadraheb.com/)
