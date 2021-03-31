<p align="center">
  <img src="https://raw.githubusercontent.com/ImmanuelRajTheContributor/404-Extended-Manifest/main/project404-darkbanner_edited.jpeg" />
</p>

A project that shouldn't have existed by the laws of the internet and yet it does; we present you Project 404 Extended , just like the Schrödinger's cat!

 Credits
 -------
  * [**AOSP**](https://android.googlesource.com)
  * [**LineageOS**](https://github.com/LineageOS)
  * [**Dirty Unicorns**](https://github.com/DirtyUnicorns)
  * [**Potato Project**](https://github.com/PotatoProject)
  * [**AOSPA**](https://github.com/AOSPA)  

 # 404 Extended
Error 404: Bugs not found!

 ### Requirements
 - Around 100G disk space
 - 50G or more usable internet
 - A computer with at least 8G RAM running Linux or MacOS
 - A brain

 ### Instructions
 1. Make sure you have a build environment setup.
 2. Run the following commands to sync Project-404 source

 	```bash
         mkdir p-404 && cd p-404
         repo init -u https://github.com/404-Extended/android_manifest -b rippa
         repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
 	```

 3. Once the source is downloaded prepare your trees and build.

 ### Reporting compilation issues
 - For common porting related errors, visit [**Android Building Help**](https://t.me/AndroidBuildingHelp)

 ### Happy Building :)
