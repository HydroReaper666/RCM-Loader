# RCM Loader
Payload and Lakka launcher for the Switch using your Android!

Download it on the [Google Play Store](https://play.google.com/store/apps/details?id=com.thirdeclarity.rcmloader)
**Application doesn't require Root on your device.**

**BEGINNERS SHOULD START WITH [THIS GUIDE](https://guide.sdsetup.com/#/beforestarting)**

[Hekate](https://github.com/CTCaer/hekate) payload bundled as default. Make sure your SD card on the Switch is properly setup first. I recommend this [pre-packaged SD Card Files by tumGER](https://github.com/tumGER/SDFilesSwitch/releases/) that you can simply extract to your SD. **This link is now known as Kosmos and is still highly recommended.**

[Lakka](https://lakka-switch.github.io/documentation/) payload is bundled with the application but you will have to get your coreboot.rom file separately and then add it. [Click to download coreboot for Lakka.](https://github.com/ThirdEyeClarity/RCM-Loader/raw/Lakka-Loader/coreboot.rom) This version of coreboot is extracted from "Lakka-Switch.arm-2.2-devel-20181004171647-r28346-g2df642137.tar.gz" which is the stable release from 10/04/2018.

## Usage
* Launch application
* Find a cable to connect your device to the Switch. For proper operation, this should be a cable that is designed for data transmission, not just for charging. It is advisable to use a **A-to-C** cable and an **USB OTG** adapter. If you are having trouble with a C-to-C cable, consider getting an OTG adapter. **Your device does not need root** for this to work, however some devices do not support USB OTG. If you are not able to get it to work after trying different cables, try another Android device. Additionally, Android devices with xHCI controllers(USB 3.0) should work fine, but EHCI(USB 2.0) drivers may not work without a [kernel patch](https://github.com/fail0verflow/shofel2/blob/master/linux-ehci-enable-large-ctl-xfers.patch).

* In the **"Payloads"** category, click the **"+"** button to select preloaded payload from your device's storage. Or simply transfer your payload to the RCM Loader folder in the device's memory. Or you can use the default payload (**Hekate**)
* Enter your Nintendo Switch into **RCM** mode in any convenient way. Your Nintendo Switch will power on by itself when plugged in, be sure to hold **VOLUME +**
* Connect the device to the Switch and allow permission for the **USB** access if necessary. Wait until the program prompts you to select what do you want to inject, payload or Lakka. If you will select payload, than you will have to choose the one you need. If you will choose Lakka, you should simply wait for it to load.
* Wait for payload to finish loading on your console


## FAQ
**Does application require Root?**

Application doesn't require Root on your device. You will need to accept the storage permission for the app to locate payloads and work correctly. 

**Can it brick my device/console?**

This should not happen when using the "correct" payloads. Make sure you download trusted payloads as I cannot be held responsible for bricks due to user error. There is a rare chance of freezing while in RCM mode. If this happens just hold down the Switch's power button for 15 seconds and let go to power off, and then you may repeat the steps to enter RCM mode again. This application is typically kept up to date with the latest [Hekate payload](https://github.com/CTCaer/hekate/releases), however it should be your responsibility to manually check for Hekate updates in case RCM Loader is behind.

**Can RCM Loader launch Linux?**

Yes, RCM Loader can launch the latest Lakka distribution as long as your SD card is properly formatted as FAT32, the [latest stable Lakka release](https://lakka-switch.github.io/documentation/archives.html) is extracted to your SD ("lakka" & "bootloader" folder) and you have the correct coreboot file in the app. **However it is now recommended to boot Lakka through the hekate payload instead.**

## Credits
* [MenosGrante](https://github.com/MenosGrante) for originally writing Rekado
* [SciresM](https://github.com/SciresM) for development of the Atmosphère CFW for the Switch
* [CTCaer](https://github.com/CTCaer) for regularly developing the Hekate bootloader payload
* [fail0verflow](https://github.com/fail0verflow) for ShofEL2 exploit
* [DavidBuchanan314](https://github.com/DavidBuchanan314) for creating NXLoader
* [natinusala](https://github.com/natinusala) for creating Lakka_linux_launcher


