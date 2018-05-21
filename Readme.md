### Remove Gapps is a project created 2016 by CHEF-KOCH to remove all Google apps (Gapps).


[![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/fold_left.svg?style=social&label=Follow%20%40CHEF-KOCH)](https://twitter.com/CKsTechNews)
[![Say Thanks!](https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg)](https://saythanks.io/to/CHEF-KOCH)
[![Discord](https://discordapp.com/api/guilds/418256415874875402/widget.png)](https://discord.me/CHEF-KOCH)


<p align="center">
  <img src="https://raw.githubusercontent.com/CHEF-KOCH/Remove-Gapps/master/NoGoogleApps.png">
</p>



The goal is to switch from Gapps to e.g. NanoMod, to remove all Google services (except CoreGms.apk and Webview [cause they're important]) to get control pack to you!


**Please backup all Google apps or a full backup via recovery before you install it. It's highly recommended to wipe dalvik/ART-cache to rid out of unused cache files after flashing the package.**  


How does it work?
=================

* Script removes apps from your _/system_ partition. Probably some of them was updated and additionally stored in your internal memory.
* The flashable-zip supports Android 2.3+ up to Android Oreo 8.1.
* The script can mount /system automatically which means you don't need do it by yourself.
* The script was tested on CyanogenMod (now LineageOS) only but theoretically it should work on most ROM's. 
* It's flashable via CWM (old) or TWRP. 


What will be deleted?
=================

* The Script will delete the default Google Launcher, it also removes Google Dialer, Google Keyboard, Google Maps, Google Play Store & Google Play Store which means you need to install alternatives before you use this script - or simply install NanoMod.
* The full list is viewable/editable under 'delete.sh'.


### Info

* Maybe you face a bootloop or your whole ROM will be broken after applying the ZIP file because modern firmwares very depends from gapps. Keep in mind that's impossible for me to test all firmwares/ROM's. That's why you should always do a NadroidBackup and then report back with your logs from TWRP.
* don't apply script after wipe /data, only after first boot. Otherwise execute these commands
* Before applying the zip ensure you se the defaults to none, it's under _Settings_ > _Apps_ > _Gear icon_ > _Default apps_ > _Voice & assist_ > set both to _"None"_ 
* Script also removes Google Launcher, install 3rd-party app or device will not boot! Like NovaLauncher etc. The same goes for Keyboard, Dialer etc!
* Apps that display Google Maps possible can't be installed or used because the Google Play Store Services is missing, you can try to re-install it (if you really need it or use alternative apps).
* Network location will be unavailable because it's part of gapps
* Recommended to wipe dalvik-cache to rid out of unused odex-files - this is important!



Where I can find the latest release?
=================

* It's under the [release page](https://github.com/CHEF-KOCH/Remove-Gapps/releases).


#### Research and alternatives
* [NanoMod project](https://forum.xda-developers.com/apps/magisk/module-nanomod-5-0-20170405-microg-t3584928) (now called NanoDroid)
* [MicroG Project](https://forum.xda-developers.com/android/apps-games/app-microg-gmscore-floss-play-services-t3217616)
* [MicroG Implementation Status](https://github.com/microg/android_packages_apps_GmsCore/wiki/Implementation-Status)
