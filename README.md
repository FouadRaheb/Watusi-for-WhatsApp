[original]: https://mega.nz/file/hHBw1SrD#as50PpZVSD5ZaizcUtkPDtnA_XJ1NsY3SOnqpZlbvn4
[duplicate]: https://mega.nz/file/8Tgm3ZxL#S8PPA7E_2HQW2qpTRZgUOy85IcHLPw6_yn8QvQPLvQM
[business]: https://mega.nz/file/lPBBQBzb#Ii9Y_aA7NDgCrshTwHD9SNGffP85CJwA-kAliEJRgtI
[business-duplicate]: https://mega.nz/file/sWByhQjQ#I9JM3ffg-zMAXF_RDbIqnv7PLSmY_57LOfNzsh4FxHk

[original-ts]: https://mega.nz/file/JfYzyCyJ#nzhUG3m1l7koxCOWUI1reHKTbdEeV2YCUZbybJJyws4
[business-ts]: https://mega.nz/file/JGwhDb7a#Az96WmZ_mCOQrK-sXNAUmZgae8YfYNOxPgao2_b1PR4

[builds-io-watusi]: https://builds.io/apps/watusi/?aid=1025553
[builds-io-watusi-duplicate]: https://builds.io/apps/duplicatewhatsappwatusi/?aid=1025553
[builds-io-watusi-business]: https://builds.io/apps/whatsappb/?aid=1025553

[flekstore-link]: https://flekstore.com/wa
[mega-folder-link]: https://mega.nz/folder/UPgADK5L#zpS9_Cjr1jAwFYIheg6HDQ

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
    | Application | Bundle | Version | Watusi 3 | Stalky | OnlineNotify |
    | ------------------ |:---------:|:------:|:------:|:------:|:------:|
    | [WhatsApp][original] | net.whatsapp.WhatsApp | 24.20.78 | 1.2.42 | 4.1.29 | 3.4.6 |
    | [WhatsApp Duplicate][duplicate] | com.fouadraheb.watusi | 24.20.78 | 1.2.42 | 4.1.29 | 3.4.6 |
    | [WA Business][business] | net.whatsapp.WhatsAppSMB | 24.20.78 | 1.2.42 | 4.1.29 | 3.4.6 |
    | [WA Business Duplicate][business-duplicate] | com.fouadraheb.watusiSMB | 24.20.78 | 1.2.42 | 4.1.29 | 3.4.6 |

    <sup>Stalky, OnlineNotify, and ContactSync tweaks are disabled by default and can be enabled from inside Watusi Settings.</sup>
    
    <sup>For faster download speeds, download files from this [mega.nz folder][mega-folder-link]</sup>
    
* (Option 2) You can get a paid subscription from a signing store where you can download the latest Watusi directly from your device and have it available for 1 year instead of 7 days. I recommend using [https://flekstore.com)][flekstore-link] since they always have the latest official IPA from this page.

### Sideloading (TrollStore)
* If you are on <b>iOS 14 - 16.6.1</b> (iPhone X - A11 and older) or <b>iOS 14 - 16.6 beta 1</b> (iPhone 11 and newer), install with TrollStore to receive push notifications and use iCloud features:

    * Install [TrollStore](https://github.com/opa334/TrollStore) (or [this guide](https://ios.cfw.guide/installing-trollstore/))
    * Install and activate WhatsApp from the AppStore
    * Download the IPA file from the table below
    * Open IPA in TrollStore
    * Install to overwrite original WhatsApp


    <sub>The following IPAs binary and plugins are fake-signed with their original entitlements. They do not include any fixes for WhatsApp, so THEY WILL CRASH if not used in TrollStore or not signed with proper certificate and entitlements.</sub>
    | Application | Bundle | Version | Watusi 3 | Stalky | OnlineNotify |
    | ------------------ |:---------:|:------:|:------:|:------:|:------:|
    | [WhatsApp][original-ts] | net.whatsapp.WhatsApp | 24.20.78 | 1.2.42 | 4.1.29 | 3.4.6 |
    | [WA Business][business-ts] | net.whatsapp.WhatsAppSMB | 24.20.78 | 1.2.42 | 4.1.29 | 3.4.6 |
    
    <sup>Stalky, OnlineNotify, and ContactSync tweaks are disabled by default and can be enabled from inside Watusi Settings.</sup>

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

* If you have AltStore Beta, you can add our AltStore source (https://altstore.fouadraheb.com) and download apps directly from AltStore.

* If you don't have access to AltStore sources, download the IPA file from the link above and copy it to your phone, using iCloud Drive, AirDrop, or any other method. Open AltStore and navigate to the "My Apps" tab. Choose the plus in the top right corner and open the IPA file. When prompted sign in with your Apple ID. Two-factor Authentication is supported, but app-specific passwords are not.
</details>

<details>
<summary><h2>Sideloading as linked device (Push Notifictions + iCloud Backup)</h2></summary>

Since WhatsApp added the option to link a device on mobile, you can now use the original WhatsApp from the AppStore and install Watusi IPA as a duplicate and link your original WhatsApp to it.

* Install and activate original WhatsApp from the AppStore
* Download and install [duplicated Watusi IPA](#sideloading-no-jailbreak) from the table above.
* Enable Watusi's `Local Notifications` feature on your duplicate to keep the app active while linking.
  * Open duplicated Watusi, from the welcome screen, tap 3 times on the animated image and select `Watusi` preferences, go to the `Notifications` section and activate `Enable Local Notifications`, and set it to `Audio`.
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

## FAQ
* If you receive "Please sign in with app-specific password" error, that's because you have 2-factor authentication enabled for your Apple ID. You have to go to Apple's website https://appleid.apple.com, log in with your account and create an app-specific password to use as your Apple ID password.
* Signing the app with a non-developer account will have it expire in 7 days, but AltStore automates re-signing as long as it is connected to your PC.
* The app will not receive Push Notifications and you won't be able to use iCloud features (Except for TrollStore on supported devices).
