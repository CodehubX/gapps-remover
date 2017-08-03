### Remove Gapps is a project created 2017 by CHEF-KOCH to remove all Google apps (Gapps).


[![GitHub release](https://img.shields.io/github/release/CHEF-KOCH/Remove-Gapps.svg)](https://github.com/CHEF-KOCH/Remove-Gapps/releases/latest)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/CHEF-KOCH/Remove-Gapps/master/LICENSE)
[![Build status](https://ci.appveyor.com/api/projects/status/o6kwuifjotbo6t5a/branch/master?svg=true)](https://ci.appveyor.com/project/CHEF-KOCH/Remove-Gapps/branch/master)

[![GitHub issues](https://img.shields.io/github/issues/CHEF-KOCH/Remove-Gapps.svg?style=plastic)](https://github.com/CHEF-KOCH/Remove-Gapps/issues)
[![Stories in Ready](https://badge.waffle.io/CHEF-KOCH/Remove-Gapps.png?label=ready&title=Ready)](https://waffle.io/CHEF-KOCH/Remove-Gapps)
[![Stories in Progress](https://badge.waffle.io/CHEF-KOCH/Remove-Gapps.png?label=in%20progress&title=In%20Progress)](https://waffle.io/CHEF-KOCH/Remove-Gapps)

![Remove Gapps Logo](https://raw.githubusercontent.com/CHEF-KOCH/Remove-Gapps/master/anti-google.jpg)



The goal is to switch from Gapps to e.g. NanoMod, to remove all Google services (except CoreGms.apk and Webview [cause they're important]) to get control pack to you!


**Please backup all Google apps or a full backup via recovery before you install it. It's highly recommended to wipe dalvik/ART-cache to rid out of unused cache files after flashing the package.**  


How does it work?
=================

* Script removes apps from /system partition. Probably some of them was updated and additionally stored in your internal memory.
* The flashable-zip supports Android 2.3+ up to Android Nougat 7.1.2.
* The script can mount /system automatically which means you don't need do it by yourself.
* The script was tested on CyanogenMod (LineageOS) only but theoretically should work on most ROM's. 
* It's flashable via CWM and TWRP. 


What will be deleted?
=================

* The Script will delete the default Google Launcher, it also removes Google Dialer, Google Keyboard, Google Maps, Google Play Store & Google Play Store which means you need to install alternatives before you use this script - or simply install NanoMod.
* The full list is viewable/editable under 'delete.sh'.


Where I can find the latest release?
=================

* It's under the [release page](https://github.com/CHEF-KOCH/Remove-Gapps/releases).


Research and alternatives
* [NanoMod project](https://forum.xda-developers.com/apps/magisk/module-nanomod-5-0-20170405-microg-t3584928)
* [MicroG Project](https://forum.xda-developers.com/android/apps-games/app-microg-gmscore-floss-play-services-t3217616)
* [MicroG Implementation Status](https://github.com/microg/android_packages_apps_GmsCore/wiki/Implementation-Status)
