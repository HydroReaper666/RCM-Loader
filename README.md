# RCM Loader
Payload and Lakka launcher written in Kotlin. 

**Application doesn't require Root on your device.**

[Hekate](https://github.com/CTCaer/hekate) payload bundled as default.
[Lakka](https://github.com/lakka-switch/boot-scripts/tree/master/payloads) payload and coreboot files bundled in application.

## Usage
* Launch application
* Find a cable to connect your device to the Switch. For proper operation, this should be a cable that is designed for data transmission, not just for charging. It is advisable to use an **A-to-C** cable and an **USB OTG** adapter.
* In the **"Payloads"** category, click the **"+"** button to select preloaded payload from your device's storage. Or simply transfer your payload to the Rekado folder in the device's memory. Or you can use the default payload (**Hekate**)
* Enter your Nintendo Switch into **RCM** mode in any convenient way. Your Nintendo Switch will power on by itself when plugged in, be sure to hold **VOLUME +**
* Connect the device to the Switch and allow permission for the **USB** access if necessary. Wait until the program prompts you to select what do you want to inject, payload or Lakka. If you will select payload, than you will have to choose the one you need. If you will choose Lakka, you should simply wait for it to load.
* Wait for payload to finish loading on your console


## FAQ
**Does application require Root?**

Application doesn't require Root on your device.

**Can it brick my device/console?**

This should not happen when using the "correct" payloads. But I am not responsible for possible problems.

**Can RCM Loader launch Linux?**

Yes, starting from 2.0 update RCM Loader can launch Lakka distribution. However it is now recommended to boot Lakka through the hekate payload instead.

## Credits
* [fail0verflow](https://github.com/fail0verflow) for ShofEL2 exploit
* [ktemkin](https://github.com/ktemkin) for discovering and implementing the Fusee Launcher
* [DavidBuchanan314](https://github.com/DavidBuchanan314) for creating NXLoader.
* [natinusala](https://github.com/natinusala) for creating Lakka_linux_launcher.
* [ealfonso93](https://github.com/ealfonso93) for contributing in this project.
* [CTCaer](https://github.com/CTCaer) for picking up and maintaining the hekate payload
* [MenosGrante](https://github.com/MenosGrante) for originally writing Rekado
