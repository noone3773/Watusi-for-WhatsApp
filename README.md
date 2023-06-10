[original]: https://mega.nz/file/RfhkDCpI#Xd1zVViIM4_yD7WVcoYKpbvBJV9l_bWbfcY3EbFeaQk
[duplicate]: https://mega.nz/file/1Tg0wY7K#gngqp9EuPqLnNlmDsOMopnSvgIjcib9uiNIIFLQii1Q
[business]: https://mega.nz/file/4eJBjTxb#kMcMEGvpjZQIc7JOoXL5dqHBWRLW2CvQYR1Wf5Y5pvU

[original-nofix]: https://mega.nz/file/wbJjRIQS#eb0LuvVDNMOnAEe2YwYx9ljYmjt-_uN4qE1YScI31CY
[business-nofix]: https://mega.nz/file/9GoS2ICb#Ok0tD8CdN8jk1hJuFunrmMJEmQ6Y6q7EJEHyGd0Q6BU

[builds-io-watusi]: https://builds.io/apps/watusi/?aid=1025553
[builds-io-watusi-duplicate]: https://builds.io/apps/duplicatewhatsappwatusi/?aid=1025553
[builds-io-watusi-business]: https://builds.io/apps/whatsappb/?aid=1025553

# Watusi for WhatsApp

The all-in-one tweak for WhatsApp Messenger!


## Download Links

### Jailbroken Devices

Add __[https://apt.fouadraheb.com](https://apt.fouadraheb.com)__ to your Cydia/Zebra/Sileo sources and download it from there. 

(Check [this page](https://idevicecentral.com/jailbreak-tools/ios-jailbreak-downloads-download-jailbreak-tools-for-all-ios-versions/) for more info on how to jailbreak your current iOS version)

### Sideloading (No Jailbreak)

1. (Option 1) Download IPA file from here and follow the instructions below to sign and install the app from your computer.

    The following IPA files have `Plugins` folder deleted and includes some fixes to avoid WhatsApp crashing when not signed with proper entitlements and a developer account.
    | Application | Bundle | Version | Watusi 3 | Stalky | OnlineNotify |
    | ------------------ |:---------:|:------:|:------:|:------:|:------:|
    | [WhatsApp][original] | net.whatsapp.WhatsApp | 23.11.80 | 1.1.62 | 4.1.21 | 3.4.3 |
    | [WhatsApp Duplicate][duplicate] | com.fouadraheb.watusi | 23.11.80 | 1.1.62 | 4.1.21 | 3.4.3 |
    | [WA Business][business] | net.whatsapp.WhatsAppSMB | 23.11.80 | 1.1.62 | 4.1.21 | 3.4.3 |

    ```Stalky and OnlineNotify tweaks are disabled by default and can be enabled from inside Watusi Settings.```
    
2. (Option 2) [Optional] You can get a paid subscription from a signing store where you can download the latest Watusi directly from your device and have it available for 1 year instead of 7 days. I recommend using [builds.io][builds-io-watusi] since they always have the latest IPA from here. Builds.io links: [Watusi][builds-io-watusi] - [Watusi Duplicate][builds-io-watusi-duplicate] - [Watusi WhatsApp Business][builds-io-watusi-business].

<br/>

### Sideloading with TrollStore

Available for iOS 14 - 15.1.1 (All devices) and iOS 14 - 15.5 b4 (iPhone X and older)

1. Install [TrollStore](https://github.com/opa334/TrollStore)
2. Download IPA file from the table below
3. Open IPA in TrollStore

- The following IPA's binary and Plugins are fakesigned with their original entitlements
- It does not include any fixes for WhatsApp, so `IT WILL CRASH` if not used in TrollStore or not signed with proper certificate and entitlements.

| Application | Bundle | Version | Watusi 3 | Stalky | OnlineNotify |
| ------------------ |:---------:|:------:|:------:|:------:|:------:|
| [WhatsApp][original-nofix] | net.whatsapp.WhatsApp | 23.11.80 | 1.1.62 | 4.1.21 |  3.4.3 |
| [WhatsApp Business][business-nofix] | net.whatsapp.WhatsAppSMB | 23.11.80 | 1.1.62 | 4.1.21 |  3.4.3 |


```Stalky and OnlineNotify tweaks are disabled by default and can be enabled from inside Watusi Settings.```
    
<hr />

## How to Sideload on non-jailbroken devices

### Requirements

1. A computer running macOS or Windows
2. Internet connection
3. Apple ID (email & password)
4. If you are on iOS 16, you may need to enable Developer Mode. (Settings > Privacy & Security > Developer Mode)

### AltStore

* Download the IPA file from the link above and copy it to your phone, using iCloud Drive, Airdrop, or any other method.

* Download and install AltServer from [here](https://altstore.io)

* Right click on the AltServer icon with your phone connected and choose "Install Altstore", then the name of your phone. When prompted sign in with your Apple ID. Two-factor Authentication is supported, app-specific passwords are not.

* Make sure no other WhatsApp with the same bundle identifier is installed. (net.whatsapp.WhatsApp if you chose original IPA or com.fouadraheb.watusi for the duplicate)

* Open AltStore and navigate to the "My Apps" tab. Choose the plus in the top right corner and open the IPA file. When prompted sign in with your Apple ID. Two-factor Authentication is supported, app-specific passwords are not.

#### FAQ
* If you receive "Please sign in with app-specific password" error, that's beacuse you have 2-factor authentication enabled for your Apple ID. You have to go into Apple's website https://appleid.apple.com, log in with your account and create an app-specific password to use as your Apple ID's password.

### Note

* Signing with a non developer account will have the app expire in 7 days, but Altstore automates re-signing as long as it is connected to your PC.
* The app will not receive Push Notifications and you won't be able to use iCloud features.
