# Azule

A CLI tool used to inject iOS jailbreak tweaks into jailed iOS apps.

## For installation instructions [click here](https://github.com/Al4ise/Azule/wiki)

## Features
* Works with almost every app-targeted tweak
* Supports fetching tweaks through [Canister](https://canister.me/)
* [iOS Only] Supports fetching tweaks through APT (-a option)
* Supports importing multiple tweaks at once
* Supports importing custom files and folders:
  - .deb .dylib and .framework files will be processed and imported/injected 
  - other files and folders will be copied to the root directory of the app
* [iOS Only] Supports fetching and decrypting apps from the App Store
* Easy to use:
  - Just specify an iPA and a Tweak. Azule will do the rest for you.
  - Includes the global commands `azule` and `update-azule` to further simplify invocation and updating

## Advanced Options
* Change an app's version
* Change an app's bundleid
* Change an app's display name
* Remove UISupportedDevices from app
* Fakesign app
* Remove app extensions
* Remove Apple Watch support from app

For the extended usage instructions, run `azule -h` your terminal

## Updating (Macos/Linux/Windows)
Run `update-azule` in your terminal to update Azule

## Credits

* [Kabir Oberai](https://github.com/kabiroberai/theos-jailed) - Wrote Theos Jailed
* [Tyilo](https://github.com/Tyilo/insert_dylib) - Wrote insert_dylib
* [LeanVel](https://github.com/LeanVel/insert_dylib) - Ported insert_dylib to Linux
* [screenplaydev](https://github.com/screenplaydev/plutil) - Wrote a Linux alternative for plutil
* [Majd Alfhaily](https://github.com/majd/ipatool) - Wrote ipatool
* [dlevi309](https://github.com/dlevi309/ipatool-ios) - Ported ipatool to iOS
* [Saurik](https://github.com/saurik) - Wrote CydiaSubstrate
* [Sam Bingner and Pwn20wnd](https://github.com/sbingner/substitute) - Wrote the the fork of Substitute, used in Azule
* [NyaMisty](https://github.com/NyaMisty/fouldecrypt) - Wrote fouldecrypt
