# arcripper
Download and use games from Apple Arcade after your subscription has ended

### Requirements
~~~
Jailbroken iOS device, or TrollStore 1/2 (iOS 14-iOS 17.0 excluding any iOS 16 version above 16.6.1)
Payment method
Apple Arcade subscription/trial
At least iOS 13
Apple ID
2GB free space
~~~
### Utilities
~~~
Filza
TrollStore
bfDecrypt, TrollDecrypt, cra*kerXI (jailbroken)
~~~
| iOS      | Tool |
| ----------- | ----------- |
| 10-13      | bfDecrypt, cra*kerXI+       |
| 14+   | TrollDecrypt        |
### Guide

Activate the one month trial (do not cancel yet)

Download as many Arcade apps you want

Go to your decrypter app of choice and decrypt the app

In Filza, locate the decrypted IPA
| Tool     | Location |
| ----------- | ----------- |
| TrollDecrypt      | App or /var/mobile/Libary/TrollDecrypt/decrypted       |
| bfDecrypt   | /var/mobile/Containers/Data/Application/(device specific)/Documents/decrypted-app.ipa        |
| cra*kerXI+ | /var/mobile/Documents/CrackerXI |

Extract IPA to folder (Should be named Payload)

Go to Info.plist

Delete any value starting with "NS"

Zip Payload folder app and rename <AppName>.IPA

Sideload via TrollStore and verify app runs

Profit!

(Then cancel the trial [access lost immdiently])

### Note:

Some apps may have an online login screen, this may or may not work

Game Center ofc will be broken, so progress may not be saved (CHECK!)
