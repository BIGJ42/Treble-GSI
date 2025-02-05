# Best Treble GSIs Collection for Android Devices

Welcome to my collection of (in my opinion) the **best Treble GSIs (Generic System Images)** for Android devices. This repository serves as a curated list of high-quality, stable, and feature-rich GSIs for users who want to experience the latest Android versions on Treble-compatible devices.

## About Treble GSIs

A **Treble GSI** is a system image that is designed to work across various Android devices that support Project Treble. Project Treble is a major reorganization of Android's architecture, introduced in Android 8.0 (Oreo), which modularizes the system and separates vendor-specific code from the Android OS framework. This allows for easier updates and custom ROM installations.

## What’s Inside?

This repository contains a collection of the best Treble GSIs that I have personally tested and found to be stable and reliable. These GSIs are chosen based on their performance, features, and compatibility with a wide range of Android devices.

### Features

- **Wide Compatibility**: GSIs that work on most Treble-enabled devices.
- **Latest Android Versions**: Including Android 14, 15, and more.
- **Optimized for Performance**: Only the best-performing GSIs.
- **Easy Installation**: Clear instructions to help you get up and running.
- **Frequent Updates**: Regularly updated with new GSIs as they become available.

## How to Install a Treble GSI

### Prerequisites
1. A **Treble-compatible** Android device.
2. **Unlocked bootloader** and **TWRP** recovery installed.
3. A **custom kernel** that supports Treble (if required for your device).
4. Backup all your data before proceeding.

### Installation Steps

1. **Download the GSI** of your choice from this repository.
2. **Boot into TWRP recovery**.
3. **Wipe System** (Do not wipe other partitions unless instructed).
4. **Install the downloaded GSI** image.
5. (Optional) **Install additional vendor or firmware** if needed for compatibility.
6. **Reboot** the device and enjoy!

> **Note**: Installation steps might vary depending on your device. Always consult your device’s specific forums or documentation if you run into issues.

## Contributions

Feel free to contribute by submitting pull requests or opening issues for suggestions, feedback, or any problems with the GSIs in this collection.

## License

This project is licensed under the [MIT License](LICENSE). See the LICENSE file for more details.

---
Here's a collection of available GSIs, in order to keep it easy to choose what you want.	

- *Only use GSI images with an Android version that's higher or equal to the version of Android that came with your device.*
- *If your device uses VNDKLite, only use VNDKLite GSIs. To verify what image is right for your device, check the "Required Image" section of the [Treble Info](https://github.com/phhusson/treble_experimentations/wiki/Frequently-Asked-Questions-(FAQ)#how-can-i-check-if-my-device-is-treble-enabled) app.*
- *All images here require a System-as-Root ("A/B") partition style, unless otherwise specified through a column.*

## Official Android 15 Beta builds
|Updated|Image|Maintainer|Links|Sources|Architecture|Security|		
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|19 Oct|FlexUI|FlexUITeam|[Telegram](https://t.me/FlexUITeamChat) / [Download](https://t.me/FlexUITeam/106)|-|ARM64|Oct 2024|
|16 Oct|AOSP|TrebleDroid Builders|[Download](https://github.com/TrebleDroid/treble_experimentations/releases)|[GitHub](https://github.com/TrebleDroid)|ARM64 - Binder|Oct 2024|
|12 Sep|QPR1 Google GSI|Google|[Download](https://dl.google.com/developers/android/vic/images/gsi/gsi_gms_arm64-exp-AP41.240823.009-12329489-9899f8a0.zip) / [Build](https://source.android.com/docs/setup/start/initializing)|[Google](https://android.googlesource.com/platform/manifest)|ARM64 - X86|Aug 2024|
|18 Jul|initial release Google GSI|Google|[Download](https://dl.google.com/developers/android/vic/images/gsi/gsi_gms_arm64-exp-AP31.240617.009-12094726-732980f0.zip) / [Build](https://source.android.com/docs/setup/start/initializing)|[Google](https://android.googlesource.com/platform/manifest)|ARM64 - X86|Jul 2024|

## Unofficial Android 15 Beta builds	
|Updated|Image|Maintainer|Links|Sources|Architecture|Security|		
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|16 Oct|AOSP|ponces|[Telegram](https://t.me/phhtreble) / [Download](https://github.com/ponces/treble_aosp/releases)|[GitHub](https://github.com/ponces/treble_aosp)|ARM64|Oct 2024|


## Official Android 14	
|Updated|Image|Maintainer|Links|Sources|Architecture|Security|		
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|17 Oct|FlexUI|FlexUITeam|[Telegram](https://t.me/FlexUITeamChat) / [Download](https://t.me/FlexUITeam/76)|-|ARM64|Aug 2024|
|17 Oct|iodéOS|iodé.tech|[Download release](https://gitlab.iode.tech/ota/release/-/tree/master/gsi) / [Download beta](https://gitlab.iode.tech/ota/betas)|[GitLab](https://gitlab.iode.tech/os/public/manifests/android)|ARM64|Oct 2024|
|25 Sep|RisingOS (End of Life)|UniversalX|[Download](https://sourceforge.net/projects/risingos-official/files/5.x/) / [Telegram](https://t.me/universalgsi)|[GitHub](https://github.com/RisingOSS-devices/android_device_phh_treble)|ARM64|Sep 2024|
|09 Sep|EverestOS (End of Life)|kaii-lb|[Telegram](https://t.me/kaiis_stuff/) / [Download](https://github.com/kaii-lb/treble_manifest/releases/tag/v1.3)|[GitHub](https://github.com/kaii-lb/treble_everest)|ARM64|Sep 2024|
|20 Aug|LeafOS|LeafOS Project|[Download](https://leafos.org/wiki/device/leaf_gsi_arm64)| [Gerrit](https://review.leafos.org/) / [Git](https://git.leafos.org/LeafOS-Project/leaf_build) - [Mirror](https://github.com/LeafOS-Project/leaf_build) |ARM64|Aug 2024|
|14 Jun|Google GSI|Google|[Download](https://ci.android.com/builds/branches/aosp-android14-gsi/grid?) / [Build](https://source.android.com/docs/setup/start/initializing)|[Google](https://android.googlesource.com/platform/manifest)|ARM64 - X86|Jun 2024|
|08 May|AOSP|TrebleDroid Builders|[Download](https://github.com/TrebleDroid/treble_experimentations/releases)|[GitHub](https://github.com/TrebleDroid)|ARM64 - Binder|Mar 2024|

## Unofficial Android 14	
|Updated|Image|Maintainer|Links|Sources|Architecture|Security|		
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|12 Oct|Evolution X|mytja|[Download](https://github.com/mytja/treble_evo/releases) / [Mirror 1](https://git.severkar.eu/mytja/treble_evo/releases)|[GitHub](https://github.com/mytja/treble_evo)|ARM64|Oct 2024|
|02 Oct|SuperiorOS (End of Life) |ChonDoit|[Telegram](https://t.me/elranchodecornelio/271) / [Download](https://github.com/ChonDoit/treble_superior_patches/releases/tag/A14)|[Github](https://github.com/ChonDoit/treble_superior_patches)|ARM64|Sep 2024|
|19 Sep|LineageOS<br>TD-based|AndyYan|[XDA](https://xdaforums.com/t/gsi-14-lineageos-21-trebledroid-based.4654132//) / [Download](https://sourceforge.net/projects/andyyan-gsi/files/lineage-21-td//)|[Github](https://github.com/AndyCGYan/lineage_build_unified/tree/lineage-21-td)|ARM64 - Binder|Sep 2024|
|15 Sep|VoltageOS (End of Life) |chrisaw|[Telegram](https://t.me/ahnetgsi) / [Download](https://github.com/cawilliamson/treble_voltage/releases/)|[GitHub](https://github.com/cawilliamson/treble_voltage)|ARM64 - Binder|Sep 2024|
|13 Sep|LineageOS<br>"Light"|AndyYan|[XDA](https://xdaforums.com/t/gsi-14-lineageos-21-light.4653433/) / [Download](https://sourceforge.net/projects/andyyan-gsi/files/lineage-21-light/)|[Github](https://github.com/AndyCGYan/lineage_build_unified/tree/lineage-21-light)|ARM64|Sep 2024|
|13 Sep|crDroid|Nazim|[Telegram](https://t.me/naz_dev) / [Download](https://github.com/naz664/crDroid_gsi/releases)| [GitHub](https://github.com/naz664/crDroid_gsi)|ARM64 - Binder|Sep 2024|
|24 Aug|PixelOS (Archived)|MisterZtr|[Download](https://github.com/MisterZtr/PixelOS_gsi/releases)|[GitHub](https://github.com/MisterZtr/PixelOS_gsi)|ARM64|Aug 2024|
|18 Aug|ImbrogliOS|imbroglius|[XDA](https://xdaforums.com/t/gsi-14-imbroglios-v2024-08-09-aosp-android-14-0-0_r61-pure-full-edition.4681055//) / [Download](https://github.com/imbroglius/imbroglios_gsi/releases/tag/v2024.08.18//)|[Github](https://github.com/imbroglius/imbroglios_gsi)|ARM64|Aug 2024|
|16 Aug|AOSP|ponces|[Telegram](https://t.me/phhtreble) / [Download](https://github.com/ponces/treble_aosp/releases)|[GitHub](https://github.com/ponces/treble_aosp)|ARM64|Aug 2024|
|10 Aug|Miku UI|xiaoleGun|[Download](https://github.com/xiaoleGun/treble_build_miku/releases)|[GitHub](https://github.com/xiaoleGun/treble_build_miku)|ARM64 - Binder|Aug 2024|
|18 Jul|Project Sakura|ChonDoit|[Telegram](https://t.me/elranchodecornelio/252) / [Download](https://github.com/ChonDoit/treble_sakura_patches/releases)|[Github](https://github.com/ChonDoit/treble_sakura_patches)|ARM64|Jul 2024|
|21 May|Evolution XYZ|ngankbka|[Download](https://github.com/ngankbka/treble_evolution/releases/)|[GitHub](https://github.com/ngankbka/treble_evolution)|ARM64|May 2024|
|10 Mar|HorizonDroid|Braia|[Telegram](https://t.me/TrebleUniverseChat) / [Download](https://sourceforge.net/projects/braiagsi/files/HorizonDroid/)|-|ARM64|Feb 2024|
|12 Feb|DerpFest|KoysX|[Download](https://github.com/KoysX/treble_DerpFest_GSI/releases)|[GitHub](https://github.com/KoysX/treble_DerpFest_GSI) |ARM64|Feb 2024|
|07 Feb|Evolution X|Ahnet|[Telegram](https://t.me/ahnetgsi) / [Download](https://github.com/ahnet-69/treble_evo/releases)|[GitHub](https://github.com/ahnet-69/treble_evo)|ARM64|Feb 2024|


## Official Android 13	

|Updated|Image|Maintainer|Links|Sources|Architecture|Security|		
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|27 Mar|Google GSI|Google|[Download](https://ci.android.com/builds/branches/aosp-android13-gsi/grid?) / [Build](https://source.android.com/docs/setup/start/initializing)|[Google](https://android.googlesource.com/platform/manifest)|ARM64 - X86|May 2024|
|13 Jan|LeOS 20 (Out of Maintenance) |Harvey186|[DL1](https://drive.proton.me/urls/JF352AYSS4#YkXliW8T03Cp) / [DL2](https://leos-cloud.de/s/JFrFgLgSSTEMtmL) / [Telegram](https://t.me/LeOS_Support)|-|ARM64 - Binder|Jan 2024|

## Unofficial Android 13	

|Updated|Image|Maintainer|Links|Sources|Architecture|Security|		
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|20 Aug|SuperiorOS|ChonDoit|[Telegram](https://t.me/elranchodecornelio/250) / [Download](https://github.com/ChonDoit/treble_superior_patches/releases/tag/A13)|[Github](https://github.com/ChonDoit/treble_superior_patches)|ARM64|Aug 2024|
|18 Aug|LineageOS<br>TD-based|AndyYan|[XDA](https://forum.xda-developers.com/t/gsi-13-lineageos-20-trebledroid-based.4517345/) / [Download](https://sourceforge.net/projects/andyyan-gsi/files/lineage-20-td/)|[GitHub](https://github.com/AndyCGYan/lineage_build_unified/tree/lineage-20-td)|ARM64 - Binder|Aug 2024|
|21 Jul|DerpFest|MarisaDAZA|[Download](https://github.com/MarisaDAZA/treble_DerpFest_GSI/releases)|[GitHub](https://github.com/MarisaDAZA/treble_DerpFest_GSI)|ARM64|Jul 2024|
|01 Jul|crDroid|ChonDoit|[Telegram](https://t.me/elranchodecornelio/250) / [Download](https://github.com/ChonDoit/treble_crdroid_patches/releases/tag/A13-Signed)|[GitHub](https://github.com/ChonDoit/treble_crdroid_patches)|ARM64|May 2024|
|29 Jun|Pixel Experience Plus|ChonDoit|[Telegram](https://t.me/elranchodecornelio/250) / [Download](https://github.com/ChonDoit/treble_peplus_patches/releases/tag/A13)|[GitHub](https://github.com/ChonDoit/treble_peplus_patches)|ARM64|Jun 2024|
|14 Mar|AfterLifeOS (Out of Maintenance)|ChonDoit|[Telegram](https://t.me/elranchodecornelio/192) / [Download](https://github.com/ChonDoit/treble_afterlife_patches/releases)|[Github](https://github.com/ChonDoit/treble_afterlife_patches)|ARM64|Feb 2024|
|24 Jan|ColtOS|ChonDoit|[Telegram](https://t.me/elranchodecornelio/192) / [Download](https://github.com/ChonDoit/treble_colt_patches/releases)|[Github](https://github.com/ChonDoit/treble_colt_patches)|ARM64|Jan 2024|





## Latest Android 10, 11, 12 GSIs	
|Updated|Version|Image|Maintainer|Links|Sources|Partition Style|Architecture|Security|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|18 Aug|12|LineageOS 19.1|AndyYan|[Download](https://sourceforge.net/projects/andyyan-gsi/files/lineage-19.x/)|[GitHub](https://github.com/AndyCGYan/lineage_build_unified/tree/lineage-19.1)|SAR|ARM64 - Binder|Jul 2024|
|22 Mar|11|AOSP|Google|[Download](https://ci.android.com/builds/branches/aosp-android11-gsi/grid?)|[Android](https://android.googlesource.com/platform/manifest) / [Build](https://source.android.com/docs/setup/start/initializing)|non-SaR - SaR|ARM64 - X86|Apr 2024|
|22 Mar|10|AOSP|Google|[Download](https://ci.android.com/builds/branches/aosp-android10-gsi/grid?)|[Android](https://android.googlesource.com/platform/manifest) / [Build](https://source.android.com/docs/setup/start/initializing)|non-SaR - SaR|ARM64 - X86|Apr 2024|
|05 Mar|12|AOSP|Google|[Downloads](https://ci.android.com/builds/branches/aosp-android12-gsi/grid?)|[Android](https://android.googlesource.com/platform/manifest) / [Build](https://source.android.com/docs/setup/start/initializing)|SAR|ARM64 - X86|May 2024|
|21 Jan|11|LineageOS 18.1|AndyYan|[Download](https://sourceforge.net/projects/andyyan-gsi/files/lineage-18.x/)|[GitHub](https://github.com/AndyCGYan/lineage_build_unified/tree/lineage-18.1)|non-SaR - SaR|ARM - ARM64 - Binder|Jan 2024|




<br>
<details>
<summary><i><b>Legacy GSIs (Discontinued)</b></i></summary>
<br>

## Official Android 14		
|Updated|Image|Maintainer|Links|Sources|Architecture|Security|		
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|15 Apr|Project Elixir|UniversalX|[XDA](https://xdaforums.com/t/gsi-14-0-gsi-project-elixir-official-stable-aosp.4650522/) / [Download](https://projectelixiros.com/device/gsi) / [Telegram](https://t.me/universalgsi)|[GitHub](https://github.com/projectelixir-devices/device_phh_treble/)|ARM64|Apr 2024|

## Unofficial Android 14	
|Updated|Image|Maintainer|Links|Sources|Architecture|Security|		
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|12 Mar|CherishOS (Archived)|YukiMetaa|[Download](https://github.com/YukiMetaa/treble_cherish/releases/)|[GitHub](https://github.com/YukiMetaa/treble_cherish)|ARM64|Feb 2024|
|17 Mar|ApolloOS (Archived)|YukiMetaa|[Download](https://github.com/YukiMetaa/treble_apollo/releases/)|[GitHub](https://github.com/YukiMetaa/treble_apollo)|ARM64|Feb 2024|
|24 Feb|LeOS-U (Archived)|Harvey186|[DL1](https://drive.proton.me/urls/JF352AYSS4#YkXliW8T03Cp) / [DL2](https://leos-cloud.de/s/JFrFgLgSSTEMtmL) / [Telegram](https://t.me/LeOS_Support)|-|ARM64 - Binder|Feb 2024|
|Dec 2023|CRdroid|Braia|[Telegram](https://t.me/DroidZoneBR) / [Download](https://sourceforge.net/projects/braiagsi/files/Test/)|[GitHub](https://github.com/Antony-Braiano)|ARM64|Dec 2023|
|Dec 2023|Evolution X|KoysX|[Download](https://github.com/KoysX/treble_build_evo/releases)|[GitHub](https://github.com/KoysX/treble_build_evo) |ARM64|Nov 2023|
|Oct 2023|Evolution X (Archived)|boydaihungst|[Download](https://github.com/boydaihungst/treble_build_evo/releases)| [GitHub](https://github.com/boydaihungst/treble_build_evo/)|ARM64|Oct 2023|

## Official Android 13		
|Updated|Image|Maintainer|Links|Sources|Architecture|Security|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|Nov 2023|Project Elixir|KrutosX & Lynix|[XDA](https://forum.xda-developers.com/t/gsi-rom-project-elixir-3-5-android-13-0-aosp-official-13-01-2023.4541063/) / [Download](https://www.pling.com/p/1960767/) / [Telegram](https://t.me/universalgsi)|[GitHub](https://github.com/projectelixir-devices/device_phhgsi_generic/)|ARM64|Oct 2023|
|Sep 2023|AOSP|TrebleDroid Builders|[Download](https://github.com/TrebleDroid/treble_experimentations/releases)|[GitHub](https://github.com/TrebleDroid)|ARM64 - Binder|Aug 2023|
|Jul 2023|LeafOS BETA|Linux4|[DL](https://dl.leafos.org/beta/leaf_gsi_arm64/) / [Telegram](https://t.me/leafos)|[GitHub](https://github.com/LeafOS-Project/)|ARM64|July 2023|

## Unofficial Android 13		
|Updated|Image|Maintainer|Links|Sources|Architecture|Security|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|15 Feb|LineageOS<br>"Light"|AndyYan|[XDA](https://forum.xda-developers.com/t/gsi-13-lineageos-20-light.4509315/) / [Download](https://sourceforge.net/projects/andyyan-gsi/files/lineage-20-light/)|[GitHub](https://github.com/AndyCGYan/lineage_build_unified/tree/lineage-20-light)|ARM64|Feb 2024|
|Nov 2023|Miku UI|xiaoleGun|[Download](https://github.com/xiaoleGun/treble_build_miku/releases)|[GitHub](https://github.com/xiaoleGun/treble_build_miku)|ARM64 - Binder|Nov 2023|
|Nov 2023|BaikalOS|ChonDoit|[Telegram](https://t.me/elranchodecornelio/192) / [Download](https://github.com/ChonDoit/treble_baikal_patches/releases)|[Github](https://github.com/ChonDoit/treble_baikal_patches)|ARM64|Oct 2023| 
|Nov 2023|Superior OS|ChonDoe|[Telegram](https://t.me/elranchodecornelio/192) / [Download](https://github.com/ChonDoit/treble_superior_patches/releases)|[GitHub](https://github.com/ChonDoit/treble_superior_patches)|ARM64|Oct 2023|
|Oct 2023|ArrowOS|Nazim|[Telegram](https://t.me/naz_dev) / [Download](https://github.com/naz664/ArrowOS_gsi/releases)| [GitHub](https://github.com/naz664/)|ARM64 - Binder|Sep 2023|
|Oct 2023|Cherish OS|ChonDoe|[Telegram](https://t.me/elranchodecornelio) / [Download](https://github.com/ChonDoit/treble_cherishos_patches/releases)|[GitHub](https://github.com/ChonDoit/treble_cherishos_patches)|ARM64|Sep 2023|
|Oct 2023|crDroid|Nazim|[Telegram](https://t.me/naz_dev) / [Download](https://github.com/naz664/crDroid_gsi/releases)| [GitHub](https://github.com/naz664/)|ARM64 - Binder|Oct 2023|
|Oct 2023|SparkOS|Nazim|[Telegram](https://t.me/naz_dev) / [Download](https://github.com/naz664/SparkOS_gsi/releases/tag/v2023.10.15)| [GitHub](https://github.com/naz664/)|ARM64 - Binder|Sep 2023|
|Oct 2023|AlphaDroid|ChonDoe|[Telegram](https://t.me/elranchodecornelio) / [Download](https://github.com/ChonDoit/treble_alphadroid_patches/releases/tag/A13-v20231009)|[GitHub](https://github.com/ChonDoit/treble_alphadroid_patches)|ARM64|Oct 2023|
|Oct 2023|DerpFest|KoysX| [Download](https://github.com/KoysX/treble_DerpFest_GSI/releases)|[GitHub](https://github.com/KoysX/treble_DerpFest_GSI)|ARM64|Oct 2023|
|Oct 2023|RisingOS|MisterZtr|[Download](https://github.com/MisterZtr/RisingOS_gsi/releases)|[GitHub](https://github.com/MisterZtr/RisingOS_gsi)|ARM64|Sep 2023|
|Sep 2023|VoltageOS|Ahnet|[Telegram](https://t.me/ahnetgsi) / [Download](https://github.com/ahnet-69/treble_voltage/releases)|[GitHub](https://github.com/ahnet-69/treble_voltage)|ARM64|Sep 2023|
|Sep 2023|Evolution X|ponces|[Telegram](https://t.me/poncesgsi) / [Download](https://github.com/ponces/treble_build_evo/releases/tag/v2023.09.14)|[GitHub](https://github.com/ponces/treble_build_evo)|ARM64|Aug 2023|
|Sep 2023|Pixel Experience (Plus)|ponces|[XDA](https://forum.xda-developers.com/t/gsi-unofficial-12-pixel-experience.4354695/) / [Download](https://github.com/ponces/treble_build_pe/releases/) / [Telegram](https://t.me/poncesgsi)|[GitHub](https://github.com/ponces/treble_build_pe/tree/thirteen)|ARM64|Aug 2023|
|Sep 2023|YAAP|Ahnet|[Telegram](https://t.me/ahnetgsi) / [Download](https://github.com/ahnet-69/treble_yaap/releases)|[GitHub](https://github.com/ahnet-69/treble_yaap)|ARM64|Aug 2023|
|Aug 2023|ProjectBlaze|j7b3y|[Download](https://sourceforge.net/projects/any-artifact/files/GSI/ProjectBlaze/v2.5_230224/)|[GitHub](https://github.com/j7b3y/treble_pb)|ARM64|Aug 2023|
|Aug 2023|PixelOS|MisterZtr|[Download](https://github.com/MisterZtr/PixelOS_gsi/releases/tag/v2023.08.21)|[GitHub](https://github.com/MisterZtr/PixelOS_gsi)|ARM64|Aug 2023|
|July 2023|LeaOS (LOS20)|Iceows|[Telegram](https://t.me/leaos_group) / [Download](https://sourceforge.net/projects/altairfr-huawei/files/LeaOS-20.0/)|[GitHub](https://github.com/Iceows/lineage_build_leaos)|ARM64|July 2023|
|Jul 2023|Firmware Collection|TheAtt1la|[Download](https://sourceforge.net/projects/thegsis/files/) / [Telegram](https://t.me/the_gsis)|[GitHub](https://github.com/TheAtt1la/)|ARM64 - Binder|June 2023|
|Jul 2023|AlphaDroid|KoysX|[Download](https://github.com/KoysX/treble_alpha_gsi/releases)| [GitHub](https://github.com/KoysX/treble_alpha_gsi)|ARM64|June 2023|
|Jun 2023|BiancaProject|ItzKaguya|[Telegram](https://t.me/shirayuki_plygrnd) / [Download](https://sourceforge.net/projects/itzkaguya-gsi/files/BiancaProject/)|[GitHub](https://github.com/BiancaProject)|ARM64|May 2023|
|Jun 2023|LeaOS (AOSP)|Iceows|[Telegram](https://t.me/leaos_group) / [Downloads](https://sourceforge.net/projects/altairfr-huawei/files/TrebleDroid-GSI/)|[GitHub](https://github.com/Iceows/aosp_patches_leaos/tree/android-13)|ARM64|July 2023|
|May 2023|RisingOS|Ahnet|[Telegram](https://t.me/ahnetgsi) / [Download](https://github.com/ahnet-69/treble_rising/releases)|[GitHub](https://github.com/ahnet-69/treble_rising)|ARM64|May 2023|
|May 2023|LMODroid|Lynix|[Download](https://github.com/ItsLynix/pineapple1/releases/tag/LMOdroid) / [Telegram](https://t.me/lynixsuddenlypineapples/)|[GitHub](https://github.com/ItsLynix/pineapple1/releases/tag/LMOdroid)|ARM64|May 2023|
|Mar 2023|VoltageOS|Soli|[Download](https://github.com/Soli666/VoltageOS-GSI/releases) |[GitHub](https://github.com/Soli666)|ARM64 - Binder|Feb 2023|
|Dec 2022|RiceDroid|Lynix|[Telegram](https://t.me/lynixgsi/) / [Downloads](https://sourceforge.net/projects/lynixgsiprojects/files/A13/RiceDroid/)|[GitHub](https://github.com/universalx-devs/rice_treble)|ARM64|Dec 2022|
|Dec 2022|Bliss OS|Nazim|[Telegram](https://t.me/naz_dev) / [Download](https://sourceforge.net/projects/gsi-projects/files/A13/BlissOS/v16.2/24122022/)| [GitHub](https://github.com/naz664/)|ARM64|Dec 2022|
|Nov 2022|YAAP|Lynix|[Telegram](https://t.me/lynixgsi/) / [Downloads](https://sourceforge.net/projects/lynixgsiprojects/files/A13/YAAP/29102022)|[GitHub](https://github.com/ItsLynix/multi_patch)|ARM64 - Binder|Oct 2022|


## Official Android 12/12L
|Updated|Image|Maintainer|Links|Sources|Architecture|Security|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|Sep 2023|LeOS 19.1|Harvey186| [Downloads](https://drive.proton.me/urls/JF352AYSS4#YkXliW8T03Cp) / [Telegram](https://t.me/LeOS_Support)|[GitHub](https://github.com/LeOS-GSI/LeOS-S-patches)|SAR|ARM64 - Binder|Sep 2023|
|Nov 2022|AOSP 12.1|Phhusson|[Downloads](https://github.com/phhusson/treble_experimentations/releases)|[GitHub](https://github.com/phhusson/treble_experimentations)|SAR|ARM64 - Binder|July 2022|
|Oct 2022|Corvus OS|TipzTeam2|[XDA](https://forum.xda-developers.com/t/gsi-beta-12-phh-corvusos-v1-0-thebeginning.4415529/) / [Telegram](https://t.me/CorvusGSI) / [Downloads](https://sourceforge.net/projects/tipzbuilds/files/GSIs/CorvusROM/Unofficial/20221008/)|[GitLab](https://gitlab.com/TipzTeam/vendor_generify)|ARM64|July 2022|
|Aug 2022|Ancient OS|Nazim|[Telegram](https://t.me/naz_dev/)/[Downloads](https://sourceforge.net/projects/ancientrom/files/gsi/V6.4/)|-|ARM64 - Binder|August 2022|
|Aug 2022|LeOS (S) discontinued|Harvey186|[XDA](https://forum.xda-developers.com/t/aosp-12-0-leos-ungoogled-gsi.4356501/) / [Downloads](https://leos-cloud.de/s/JFrFgLgSSTEMtmL?path=%2FLeOS-S-discontinued) / [Telegram](https://t.me/LeOS_Support)|-|ARM64 - Binder|August 2022|
|July 2022|KaleidoscopeOS|alk3p|[Downloads](https://kaleidoscope.ink/download.html?device=meowmobile/treble)|-|ARM64|July 2022|
|June 2022|DescendantOS|Dil3mm4|[Telegram](https://t.me/joinchat/UVg3KMbRfu4cV2lp) / [Downloads](https://downloads.descendant.me/)|[GitHub](https://github.com/Descendant/manifest)|ARM64|May 2022|
|June 2022|StatiXOS|StatiX Team|[Telegram](https://t.me/StatiXOSReleases) / [Downloads](https://downloads.statixos.com/12-GSI/)|[GitHub](https://github.com/StatiXOS/android_manifest)|ARM64|June 2022|

## Unofficial Android 12/12L	
|Updated|Image|Maintainer|Links|Sources|Architecture|Security|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|Aug 2023|SuperiorOS|ChonDoe|[Download](https://github.com/ChonDoit/treble_superior_patches/releases/tag/A12L)|[GitHub](https://github.com/ChonDoit/treble_superior_patches/tree/12L)|-|ARM 64|July 2023|
|Jun 2023|Pixel Experience 12 |MeowIce| [Download](https://sourceforge.net/projects/meowice-gsi/files/Pixel%20Experience%2012/) / [Telegram](https://t.me/meowicegsi)|-|SaR|ARM64|
|Nov 2022|Pixel Experience 12|ponces|[XDA](https://forum.xda-developers.com/t/gsi-unofficial-beta-12-pixel-experience.4354695/) / [Base](https://github.com/ponces/treble_build_pe/releases/tag/v416) / [Plus](https://github.com/ponces/treble_build_pe/releases/tag/v416-plus) /[Telegram](https://t.me/poncesgsi)|[GitHub](https://github.com/ponces/treble_build_pe)|SAR|ARM64|Nov 2022|
|Oct 2022|Stag OS|TheAtt1la|[Download](https://sourceforge.net/projects/thegsis/files/StagOS/)|-|ARM64|Jul 2022|
|Oct 2022|Evolution X|TheAtt1la|[Download](https://sourceforge.net/projects/thegsis/files/Evolution-X/)|-|ARM64|Aug 2022|
|Oct 2022|Arrow OS|Nazim|[Download](https://sourceforge.net/projects/gsi-projects/files/A12.1/ArrowOS-12.1/19102022/)|-|ARM64 - Binder|Oct 2022|
|Oct 2022|KomodoOS|TheAtt1la|[Download](https://sourceforge.net/projects/thegsis/files/KomodoOS/)|-|ARM64|Aug 2022|
|Oct 2022|crDroid|Nazim|[Telegram](https://t.me/naz_dev/)/[Download](https://sourceforge.net/projects/gsi-projects/files/A12.1/crDroid-8.10/16102022/)|[GitHub](https://github.com/naz664/crDroid_gsi)|ARM64 - Binder|Oct 2022|
|Oct 2022|RiceDroid|TheAtt1la|[Download](https://sourceforge.net/projects/thegsis/files/riceDroid/)|-|ARM64|Aug 2022|
|Oct 2022|Xdroid|TheAtt1la|[Download](https://sourceforge.net/projects/thegsis/files/xdroid/)|-|ARM64|Aug 2022|
|Oct 2022|PixysOS|TheAtt1la|[Download](https://sourceforge.net/projects/thegsis/files/PixysOS/)|-|ARM64|Aug 2022|
|Oct 2022|Nitrogen OS|TheAtt1la|[Download](https://sourceforge.net/projects/thegsis/files/NitrogenOS/)|-|ARM64|Aug 2022|
|Sep 2022|ProjectBlaze|j7b3y|[Download](https://sourceforge.net/projects/any-artifact/files/GSI/ProjectBlaze/)|[GitHub](https://github.com/j7b3y/blaze_patches_unified)|ARM64|Sep 2022|
|Sep 2022|Xdroid|Nazim|[Telegram](https://t.me/naz_dev/)/[Download](https://github.com/naz664/xdroid_gsi/releases/tag/v1)|[GitHub](https://github.com/naz664/xdroid_gsi)|ARM64 - Binder|Aug 2022|
|Aug 2022|ProtonAOSP|Haridhayal|[Telegram](https://t.me/c/1772196556/5526)/[Download](https://github.com/haridhayal11/treble_proton_aosp/releases/tag/v415-21-08-2022)|[GitHub](https://github.com/haridhayal11/treble_proton_aosp)|ARM64|Jul 2022|
|Aug 2022|Awaken OS|ChonDoe|[Telegram](https://t.me/elranchodecornelio/175)/[Download](https://xiaomemeindex.com/treble/?dir=Awaken)|-|ARM64|Aug 2022|
|Aug 2022|Spark OS|Nazim|[Telegram](https://t.me/naz_dev/) /[Download](https://sourceforge.net/projects/gsi-projects/files/v415-Aug/SparkOS-12.6-Experimental/)|-|ARM64- Binder|Aug 2022|
|Aug 2022|Superior OS|ChonDoe|[Telegram](https://t.me/elranchodecornelio/174)/[Download](https://xiaomemeindex.com/treble/?dir=Superior/12L)|-|ARM64|Aug 2022|
|Aug 2022|Cherish OS|ChonDoe|[Telegram](https://t.me/elranchodecornelio/173)/ [Download](https://xiaomemeindex.com/treble/?dir=Cherish)|-|ARM64|Jul 2022|
|Aug 2022|dotOS|AngelaCool|[Download](https://sourceforge.net/projects/dotos-6-0-phh-gsi/files/)|[GitHub](https://github.com/AngelaCooljx/treble_build_pe)|ARM64|Jul 2022|
|Jul 2022|Miku UI|xiaoleGun|[Download](https://github.com/xiaoleGun/treble_build_miku/releases)|[GitHub](https://github.com/xiaoleGun/treble_build_miku)|ARM64|Jul 2022|
|Jan 2022|OctaviOS|Yillié|[Telegram](https://t.me/dev_yilliee/163)/[Download](https://sourceforge.net/projects/yilliee-projects/files/GSIs/Octavi/v3.2/)|[GitHub](https://github.com/Yilliee/octavi_patches)|ARM64 - Binder|Dec 2021|
|Dec 2021|ProtonAOSP|Amy|[Download](https://sabina.amyrom.ml/phhgsis/protonaosp/)|-|ARM64 - Binder|Dec 2021|
|Dec 2021|exTHmUI (Discontinued)|xiaoleGun|[Telegram](https://t.me/LZYGSI/1851) / [Download](https://pan.xiaolegun.cn/GSI/Phh-Treble/exTHmUI/Android-12-Dev)|-|ARM64|Dec 2021|


## Official Android 11
|Last Updated|Image|Maintainer|Thread/Download|Partition Style|Architecture|
|:-:|:-:|:-:|:-:|:-:|:-:|
|Mar 2022|CAOS|eremitein|[XDA](https://forum.xda-developers.com/t/official-aosp-r-mod-caos11.4265059/) / [Telegram](https://t.me/joinchat/CdHnpVThoZCgvPZx7ESNBA) / [Download](https://github.com/eremitein/treble-patches/wiki/CAOS11-Project)|non-SaR - SaR|arm - arm64 - binder|
|Dec 2021|Corvus OS|TipzTeam1|[XDA](https://forum.xda-developers.com/t/gsi-alpha-11-phh-corvus-v12-5-xmas.4212765/) / [Telegram](https://t.me/CorvusGSI) / [Download](https://sourceforge.net/projects/tipzbuilds/files/GSIs/CorvusROM/)|non-SaR - SaR|arm - arm64 - binder|
|Oct 2021|Dot OS|Community|[Website](https://www.droidontime.com/) / [Telegram](https://telegram.me/dotos) / [Download](https://www.droidontime.com/devices) |non-SaR - SaR|arm - arm64 - binder|
|Oct 2021|AOSP|Phhusson|[Telegram](https://t.me/phhtreble) / [Download](https://github.com/phhusson/treble_experimentations/releases/tag/v313)|non-SaR - SaR|arm - arm64 - binder|
|Sep 2021|OctaviOS|Yilliee|[Website](https://octavi-os.com/) / [Telegram](http://t.me/octavigsi) / [Download](https://downloads.octavi-os.com/?dir=GSI)|non-SaR - SaR|arm - arm64 - binder|
|Sep 2021|Descendant 11.5|Dil3mm4|[Download](https://downloads.descendant.me/)|non-SaR - SaR|arm64|
|Aug 2021|NusantaraProject|wulan17|[Telegram](https://t.me/NusantaraUpdates/1634) / [Download](https://www.pling.com/p/1438186/)|non-SaR - SaR|arm - arm64 - binder|
|Aug 2021|PixelBlaster-OS 2.5|TipzTeam1|[Telegram](https://t.me/PixelBlasterUpdates/94) / [Download](https://sourceforge.net/projects/tipzbuilds/files/GSIs/PixelBlasterOS/20210805/PixelBlaster_2.5_treble_arm64_ab-11.0-20210805-0215-OFFICIAL.img.xz/download)|SaR|arm64|
|Jun 2021|Ancient OS|ankitkene|[Telegram](https://t.me/ancientofficialgsi) / [Download](https://sourceforge.net/projects/ancientrom/files/gsi/)|non-SaR - SaR|arm - arm64 - binder|
|May 2021|Havoc|Braialindo|[Download](https://download.havoc-os.com/)/[Telegram](https://t.me/havocgsi)|non-SaR - SaR|arm - arm64 - binder|
|May 2021|BlissROMs|eremitein|[Telegram](https://t.me/joinchat/CdHnpVThoZCgvPZx7ESNBA) / [Download](https://github.com/eremitein/treble-patches/wiki/BLESS11-Project)|non-SaR - SaR|arm - arm64 - binder|
|Apr 2021|CherishOS 2.6|Braialindo|[Website](https://cherishos.com/) /[Telegram](https://t.me/treblechat) / [Download](https://sourceforge.net/projects/braiagsi/files/CherishOS/)|non-SaR - SaR|arm - arm64 - binder|
|Feb 2021|Havoc|xEugW|[XDA](https://forum.xda-developers.com/t/11-official-havoc-os-4-1-arm64-arm-a64-a-ab-ab-vndklite-gapps-vanilla.4076903/) /Discontinued|non-SaR - SaR|arm - arm64 - binder|

## Unofficial Android 11
|Last Updated|ROM|Maintainer|Thread/Download|Partition Style|Architecture|
|:-:|:-:|:-:|:-:|:-:|:-:|
|Sep 2023|SuperiorOS|ChonDoe|[Download](https://github.com/ChonDoit/treble_superior_patches/releases/tag/A11)|[GitHub](https://github.com/ChonDoit/treble_superior_patches/tree/12L)|SAR|ARM 64|Sep 2023|
|Jun 2023|LineageOS 18.1|MeowIce| [Download](https://sourceforge.net/projects/meowice-gsi/files/LineageOS/) / [Telegram](https://t.me/meowicegsi)|-|SaR|ARM64|
|Jun 2023|LeOS (R)|harvey186|[Info](https://t.me/LeOS_Support) / [Download](https://drive.proton.me/urls/JF352AYSS4#YkXliW8T03Cp)|[GitHub](https://github.com/LeOS-GSI/aosp_patches_leaos)|non-SaR - SaR|ARM - ARM64 - Binder|
|Oct 2022|FLOS (A11)|Chondoe|[Download](https://github.com/ChonDoit/treble_flos_patches/releases/tag/A11)/[Telegram](https://t.me/elranchodecornelio/187)|[GitHub](https://github.com/ChonDoit/treble_flos_patches/tree/11)|SaR|ARM64|
|Mar 2022|LineageOS R Mod|eremitein|[Telegram](https://t.me/joinchat/CdHnpVThoZCgvPZx7ESNBA) / [Download](https://github.com/eremitein/treble-patches/wiki/LiR-Project)|non-SaR - SaR|arm - arm64 - binder|
|Mar 2022|crDroid R Mod|eremitein|[Telegram](https://t.me/joinchat/CdHnpVThoZCgvPZx7ESNBA) / [Download](https://github.com/eremitein/treble-patches/wiki/crDRom11-Project)|non-SaR - SaR|arm - arm64 - binder|
|Dec 2021|exTHmUI Discontinued|xiaoleGun|[Telegram](https://t.me/LZYGSI/1837) / [Download](https://pan.xiaolegun.cn/GSI/Phh-Treble/exTHmUI)|SaR|arm64|
|Oct 2021|Pixel Experience/Plus|ponces|[XDA](https://forum.xda-developers.com/t/gsi-unofficial-11-pixel-experience.4269051/) / [Download](https://github.com/ponces/treble_build_pe/releases)|non-SaR - SaR|arm - arm64 - binder|
|May 2021|Firmware collection|Igor-s7|[Telegram](https://t.me/Ambergsi) / [Download](https://sourceforge.net/projects/amber-gsi/files/)|non-SaR - SaR|arm - arm64 - binder|
|May 2021|Firmware collection|Braialindo|[Telegram](https://t.me/treblechat) / [Download](https://sourceforge.net/projects/braiagsi/files/)|non-SaR - SaR|arm64 - binder|

## Official Android 10
|Last Updated |ROM|Maintainer|Thread/Download|Partition Style|Architecture|
|:-:|:-:|:-:|:-:|:-:|:-:|
|Nov 2023|/e/ OS|[e Foundation](https://e.foundation/)|[Installation](https://doc.e.foundation/how-tos/install-GSI)|non-SaR - SaR|ARM - ARM64 - Binder|Oct 2023|
|Mar 2023|AOSP 10| Google | [Download](https://ci.android.com/builds/branches/aosp-android10-gsi/grid?)|non-SaR - SaR| ARM64 - X86|
|Dec 2020|Havoc| skulshady, zenixxx|[Download](https://sourceforge.net/projects/havoc-os/files/) |non-SaR - SaR|arm - arm64 - binder|
|Oct 2020|CAOS|eremitein|[XDA](https://forum.xda-developers.com/t/official-aosp-q-mod-caos.4137289/) / [Telegram](https://t.me/joinchat/CdHnpVThoZCgvPZx7ESNBA) / [Download](https://github.com/eremitein/treble-patches/wiki/CAOS-Project)|non-SaR - SaR|arm - arm64 - binder|
|Oct 2020|BlissROMs|eremitein|[XDA](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/unofficial-blissroms-q-mod-bless-t4138687) / [Telegram](https://t.me/joinchat/CdHnpVThoZCgvPZx7ESNBA) / [Download](https://github.com/eremitein/treble-patches/wiki/BLESS-Project)|non-SaR - SaR|arm - arm64 - binder|
|Aug 2020|AOSP|phhusson|[XDA](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/-t3992559) / [Download](https://github.com/phhusson/treble_experimentations/releases/tag/v222)|non-SaR - SaR|arm - arm64 - binder|

## Unofficial Android 10
|ROM|Maintainer|Thread/Download|Partition Style|Architecture|
|:-:|:-:|:-:|:-:|:-:|
|LeOS (Q) 23/01/23|harvey186|[Info](https://t.me/LeOS_Support) / [Download](https://drive.proton.me/urls/JF352AYSS4#YkXliW8T03Cp)|non-SaR - SaR|ARM - ARM64 - Binder|
|exTHmUI 23/12/22|xiaoleGun|[Download](https://github.com/exthmui-10-treble/Release/releases)|SAR|ARM64|
|Firmware collection|turbolukex5|[XDA](https://forum.xda-developers.com/project-treble/trebleenabled-device-discussion/-t4003457) / [Telegram](https://t.me/expresslukegsi) / [Download](https://sourceforge.net/projects/expressluke-gsis/files/)|non-SaR - SaR|arm - arm64 - binder|
|Firmware collection|eremitein|[Telegram](https://t.me/joinchat/CdHnpVThoZCgvPZx7ESNBA) / [Download](https://sourceforge.net/projects/treblerom/files/)|non-SaR - SaR|arm - arm64 - binder|
|Firmware collection|Igor-s7|[Download](https://sourceforge.net/projects/amber-gsi/files/)|non-SaR - SaR|arm - arm64 - binder|
|Firmware collection|Trisquel|[Download](https://sourceforge.net/projects/gsi-albus/files/arm64-aonly/android10/)|non-SaR|arm64|
|Firmware collection|Diust|[Download](https://sourceforge.net/projects/androidgsi/files/)|non-SaR - SaR|arm - arm64 - binder|
|LineageOS 17.1|AndyYan|[XDA](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/-t4004673) / [Download](https://sourceforge.net/projects/andyyan-gsi/files/lineage-17.x/)|non-SaR - SaR|arm - arm64 - binder|
|Resurrection Remix 8.7.3|RobotHanzo|[Download](https://sourceforge.net/projects/resurrection-remix-q-gsi/files/)|non-SaR - SaR|arm - arm64 - binder|
|POSP|twsunset|[Download](https://drive.google.com/drive/folders/1K3TiZ8QhxaAlyNR6SA5JQyVj2hWO8-Ps)|non-SaR - SaR|arm64|
|Firmware collection|Braialindo|[Download](https://sourceforge.net/projects/braiagsi/files/) / [Telegram](https://t.me/stragoOS)|non-SaR - SaR|arm - arm64 - binder|

## Official Android 9 Pie
|ROM|Maintainer|Thread/Download|Partition Style|Architecture|
|:-:|:-:|:-:|:-:|:-:|
|AOSiP|akhilnarang|[Download](https://sourceforge.net/projects/illusionproject/files/GSI/)|non-SaR - SaR|arm - arm64|
|AOSP|phhusson|[XDA](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/-t3831915/) / [Download](https://github.com/phhusson/treble_experimentations/releases/tag/v123)|non-SaR - SaR|arm - arm64 - binder|
|AospExtended|EnesSastim|[Download](https://sourceforge.net/projects/aospextended-rom/files/treble_gsi/)|non-SaR - SaR|arm - arm64 - binder|
|ArrowOS|ganesh varma|[XDA](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/-t3835111/) / [Download](https://sourceforge.net/projects/arrow-os/files/arrow-9.x/GSI/)|non-SaR - SaR|arm64|
|Bliss OS|sixohtew|[XDA](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/-t3918303/) / [Download](https://sourceforge.net/projects/blissroms/files/GSI/)|non-SaR - SaR|arm - arm64|
|Descendant|Dil3mm4|[XDA](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/-t3840578/) / [Download](https://github.com/Descendant/InOps/releases)|non-SaR - SaR|arm - arm64|
|EvolutionX|peaktogoo|[Download](https://sourceforge.net/projects/evolution-x/files/GSI/)|non-SaR - SaR|arm - arm64 - binder|
|Havoc-OS|vince31fr|[XDA](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/-t3930030/)|non-SaR - SaR|arm - arm64 - binder|
|OctopusOS|Deepflex|[XDA](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/-t3859233/)|non-SaR - SaR|arm - arm64|
|Paranoid Android|joshuous|[XDA](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/-t3886750/) / [Download](https://androidfilehost.com/?w=files&flid=288192&sort_by=date&sort_dir=DESC)|non-SaR|arm64|
|ProjectTitanium|XTutorials|[XDA](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/-t3944646/) / [Download](https://sourceforge.net/projects/projecttitanium/files/GSI-Beta/)|non-SaR - SaR|arm64|
|RainOS|yey59|[Download](https://sites.google.com/view/nitros-rom/devices/gsi)|non-SaR - SaR|arm64|
|ResurrectionRemix|mracar|[XDA](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/-t3891636/) / [Telegram](https://t.me/rrgsi) / [Download](https://get.resurrectionremix.com/?dir=pie/gsi)|non-SaR - SaR|arm - arm64 - binder|
|UltraSuccROM|DanielTheCzlek|[XDA](https://forum.xda-developers.com/android/development/ultraleanrom-lightweight-joke-t3717775/) / [Download](https://androidfilehost.com/?w=files&flid=281786&sort_by=date&sort_dir=DESC)|non-SaR - SaR|arm64|
|ViperOS|peaktogoo|[XDA](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/-t3895410/) / [Download](https://sourceforge.net/projects/viper-project/files/GSI/)|non-SaR - SaR|arm - arm64|
|ZirconiumAosp|peaktogoo|[XDA](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/-t3916107/) / [Download](https://sourceforge.net/projects/zirconiumaosp/files/GSI/)|non-SaR - SaR|arm - arm64|

## Unofficial Android 9 Pie
|ROM|Maintainer|Thread/Download|Partition Style|Architecture|
|:-:|:-:|:-:|:-:|:-:|
|AOKP|NFound|[Download](https://androidfilehost.com/?w=files&flid=290688&sort_by=date&sort_dir=DESC)|non-SaR - SaR|arm64|
|AOSP [MicroG]|oF2pks|[XDA](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/-t3878115/) / [Download](https://androidfilehost.com/?w=files&flid=286761&sort_by=date&sort_dir=DESC)|non-SaR - SaR|arm - arm64 - binder|
|AospExtended|ashu7073|[Download](https://sourceforge.net/projects/aospextended-gsi/files/)|SaR|arm64|
|AospExtended|NFound|[Download](https://androidfilehost.com/?w=files&flid=289419&sort_by=date&sort_dir=DESC)|non-SaR - SaR|arm - arm64|
|BeastROMs|NFound|[Download](https://androidfilehost.com/?w=files&flid=289638&sort_by=date&sort_dir=DESC)|non-SaR - SaR|arm - arm64|
|Benzo Rom|yshalsager|[XDA](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/-t3837127/)|non-SaR - SaR|arm64|
|BootleggersROM|NFound|[Download](https://androidfilehost.com/?w=files&flid=291038&sort_by=date&sort_dir=DESC)|non-SaR - SaR|arm - arm64|
|BootleggersROM|Technical|[XDA](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/-t3919828/) / [Download](https://androidfilehost.com/?w=files&flid=292505&sort_by=date&sort_dir=DESC)|non-SaR - SaR|arm64|
|dotOS|ashu7073|[XDA](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/-t3952035/) / [Download](https://sourceforge.net/projects/dotos-treble/files/)|non-SaR - SaR|arm - arm64 - binder|
|/e/|Phie|[XDA](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/-t3960376/)|non-SaR - SaR|arm - arm64|
|EvolutionX|turbolukex5|[arm](https://drive.google.com/a/turbox.uk/uc?id=1Xv70rvOJfWtsSOpsgoBOQ8oNv_DHcNsc&export=download) / [arm64](https://drive.google.com/a/turbox.uk/uc?id=1wdqWzQaNg9wOkbxO_9JG4ZSHKtA8cmA5&export=download) / [binder](https://drive.google.com/a/turbox.uk/uc?id=1ZG1fzm6XzhclS7WCk38ub0tiQz-QGecE&export=download)|non-SaR|arm - arm64 - binder|
|EvolutionX|NFound|[Download](https://androidfilehost.com/?w=files&flid=291542&sort_by=date&sort_dir=DESC)|non-SaR - SaR|arm - arm64|
|Havoc-OS|turbolukex5|[arm](https://drive.google.com/a/turbox.uk/uc?id=1GCwWJu_KEJMEltp8RTU9t9lRTCAhxn1O&export=download) / [arm64](https://drive.google.com/a/turbox.uk/uc?id=1xiqS-nWzzqPDdZnaifpihfcuDLIwLvDF&export=download) / [binder](https://drive.google.com/a/turbox.uk/uc?id=1NJ7LV4nxF8Dy0qE1_YXpskA_AqI2bih3&export=download)|non-SaR|arm - arm64 - binder|
|Havoc-OS|NFound|[Download](https://androidfilehost.com/?w=files&flid=290552&sort_by=date&sort_dir=DESC)|non-SaR - SaR|arm64|
|Havoc-OS|Technical|[XDA](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/-t3914038/) / [Download](https://androidfilehost.com/?w=files&flid=291817&sort_by=date&sort_dir=DESC)|non-SaR - SaR|arm64|
|ion|NFound|[Download](https://androidfilehost.com/?w=files&flid=290933&sort_by=date&sort_dir=DESC)|non-SaR - SaR|arm64|
|LegionOS|NFound|[Download](https://androidfilehost.com/?w=files&flid=292989&sort_by=date&sort_dir=DESC)|non-SaR|arm64|
|LineageOS|AndyYan|[XDA](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/-t3908029/) / [Download](https://sourceforge.net/projects/andyyan-gsi/files/)|non-SaR - SaR|arm - arm64 - binder|
|LineageOS|Deepflex|[XDA](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/-t3840801/) / [Download](https://mega.nz/#F!3XwFlAaC!VdzCKlrR-f6D-a8oEz9JkQ)|non-SaR - SaR|arm64|
|LiquidRemix|king1990|[XDA](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/-t3889160/)|non-SaR - SaR|arm - arm64 - binder|
|LLuviaOS|NFound|[Download](https://androidfilehost.com/?w=files&flid=291872&sort_by=date&sort_dir=DESC)|non-SaR - SaR|arm - arm64|
|NitrogenOS|NFound|[Download](https://androidfilehost.com/?w=files&flid=289421&sort_by=date&sort_dir=DESC)|non-SaR - SaR|arm - arm64|
|OmniROM|king1990|[XDA](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/-t3901305/)|non-SaR - SaR|arm - arm64 - binder|
|Pixel Dust|amarbajpai|[XDA](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/-t3862484/) / [Download](https://sourceforge.net/projects/pixeldust-treble/files/)|non-SaR - SaR|arm64|
|Pixel Experience|EnesSastim|[XDA](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/-t3833294/) / [Download](https://github.com/EnesSastim/Downloads/releases)|non-SaR - SaR|arm - arm64 - binder|
|PixelDirty|NFound|[Download](https://androidfilehost.com/?w=files&flid=292133&sort_by=date&sort_dir=DESC)|non-SaR - SaR|arm64|
|POSP|NFound|[Download](https://androidfilehost.com/?w=files&flid=291595&sort_by=date&sort_dir=DESC)|non-SaR - SaR|arm64|
|PrismaOS|NFound|[Download](https://androidfilehost.com/?w=files&flid=293030&sort_by=date&sort_dir=DESC)|non-SaR - SaR|arm - arm64|
|SuperiorOS|NFound|[Download](https://androidfilehost.com/?w=files&flid=291324&sort_by=date&sort_dir=DESC)|non-SaR - SaR|arm - arm64|
|SyberiaOS|NFound|[Download](https://androidfilehost.com/?w=files&flid=289418&sort_by=date&sort_dir=DESC)|non-SaR - SaR|arm - arm64|
|Treble-ized 0s|noobstyle1337|[XDA](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/-t3835092/) / [Download](https://mega.nz/#F!rBsUyYYC!QlOfpjv7lnhrrgYssjLivA)|non-SaR - SaR|arm64|
|ZirconiumAosp|NFound|[Download](https://androidfilehost.com/?w=files&flid=291634&sort_by=date&sort_dir=DESC)|non-SaR - SaR|arm - arm64|

## OEM Android 9 Pie Ports
|ROM|Maintainer|Thread/Download|Partition Style|Architecture|
|:-:|:-:|:-:|:-:|:-:|
|Android P|erfanoabdi|[XDA](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/-t3906486/) / [Telegram](https://t.me/ErfanGSIs) / [Download](https://mirrors.lolinet.com/firmware/gsi/)|non-SaR - SaR|arm64|
|Android P (PQ2A)|GabrielHoward|[Telegram](https://t.me/Psemigsi) / [Notes](https://gist.github.com/TheGabrielHoward/71d22d6d7c6bb71d02a37f8cc5dc8d3f) / [Donwload](https://mega.nz/#F!gpp1DQYZ!vLjcKGHvaZL4gqw0QsiAtg)|non-SaR - SaR|arm64|
|ColorOS|ataberkozen|[XDA](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/-t3919861/) / [Download](https://sourceforge.net/projects/mactavishao-builds/files/GSI/ColorOS%206/)|non-SaR - SaR|arm64|
|RedmagicOS|ataberkozen|[XDA](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/-t3909798/) / [Download](https://sourceforge.net/projects/mactavishao-builds/files/GSI/Nubia%20-%20RedMagic%20OS/)|non-SaR - SaR|arm64|

## Android 8 Oreo
|ROM|Maintainer|Thread/Download|Partition Style|Architecture|
|:-:|:-:|:-:|:-:|:-:|
|AOSIP|noobstyle1337|[Here](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/aosip-t3792494)|non-SaR - SaR|arm64|
|AOSP 8.1|phhusson|[Here](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/experimental-phh-treble-t3709659)|non-SaR - SaR|arm - arm64|
|AOSP Extended|AryanPatidar|[Here](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/rom-aosp-extended-t3821934)|non-SaR - SaR |arm - arm64|
|AOSP Extended|TingyiChen|[Here](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/rom-aospextended-rom-v5-5-t3797509)|non-SaR|arm64|
|AOKP|sixohtew|[Here](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/aokp-t3772379)|non-SaR - SaR|arm64|
|AquariOS|a1Pha|[Here](https://www.storozhev.net/p20pro/aquarios-system-arm64_aonly_0.1.img)|non-SaR|arm64|
|ArrowOS|bauuuuu|[Here](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/rom-arrowos-gsi-t3819467)|non-SaR - SaR|arm64|
|BootleggersROM|merothh|[Here](https://www.androidfilehost.com/?fid=890278863836285424)|non-SaR|arm64|
|BootleggersROM|dil3mm4|[Here](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/shishufied-bootleggers-2-3-gsi-t3808144)|non-SaR - SaR|arm64|
|CarbonRom|AryanPatidar|[Here](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/rom-carbonrom-noct-t3821947)|non-SaR - SaR |arm - arm64|
|CosmicOS|noobstyle1337|[Here](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/cosmic-ospulsar8-1-0201805243-2-t3794806)|non-SaR - SaR|arm64|
|CrDroid|dil3mm4|[Here](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/official-crdroid-4-4-t3813104)|non-SaR - SaR|arm64|
|dotOS|dotOS Team|[Here](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/official-droidontime-dotos-2-x-t3794338)|non-SaR - SaR|arm64|
|DU|ATechnoHazard|[Here](https://androidfilehost.com/?fid=674106145207487736)|non-SaR|arm64|
|DU|Faiyaz|[Here]( https://drive.google.com/folderview?id=1SsPuw3ZtTvoslJyqwSJsmDQ42qvJvYVN)|non-SaR|arm - arm64|
|DU|MZO|[Here](https://androidfilehost.com/?fid=890129502657595791)|non-SaR|arm64|
|FireHound|ATechnoHazard|[Here](https://basketbuild.com/uploads/devs/ATechnoHazard/FireHound-4.5-UNOFFICIAL-20180430-treble.zip)|non-SaR|arm64|
|Havoc-OS|EnesSastim|[Here](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/rom-havoc-os-8-1-t3819050)|non-SaR|arm64|
|LineageOS|phhusson|[Here](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/lineage-phh-treble-t3767690)|non-SaR - SaR|arm - arm64|
|LineageOS|iamsaalim|[XDA](https://forum.xda-developers.com/project-treble/trebleenabled-device-discussion/lineage-iamsaalim-t3938438) / [Download](https://sourceforge.net/projects/lineage-15-1-gsi/files/)|non-SaR - SaR|arm - arm64|
|OmniROM|planetera|[Here](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/rom-omnirom-8-1-t3824159)|non-SaR|arm64|
|OmniROM Treskmod|Letzen|[Here](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/rom-8-1-omnirom-treskmod-t3818188)|non-SaR|arm64|
|Resurrection Remix|mracar|[Here](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/gsi-resurrection-remix-o-6-1-0-t3811299)|non-SaR - SaR|arm - arm64|
|Resurrection Remix|phhusson|[Here](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/resurrection-remix-phh-treble-t3767688)|non-SaR - SaR|arm - arm64|
|Resurrection Remix|pchatzop|[Here](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/unofficial-treble-enabled-resurrection-t3761279)|non-SaR - SaR|arm - arm64|
|Pixel Experience|jhenrique09|[Here](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/8-1-0-pixel-experience-t3796011)|non-SaR - SaR|arm64|
|XenonHD|yshalsager|[Here](https://forum.xda-developers.com/project-treble/trebleenabled-device-development/8-1-0-xenonhd-t3800543)|non-SaR - SaR|arm - arm64|

</details>

<details>
<summary><i><b>List Maintainence Practices</b></i></summary>

1. List should be sorted by update time.
2. Outdated = not updated in 2 months.
3. Outdated GSI's are transferred to legacy whether or not they are still being maintained is not taken into account.
4. GSI's that are not Outdated should not be transferred to legacy whether or not they are still being maintained is not taken into account.
5. If only a single GSI in a column has been Outdated, it shall remain in the column & Rule 3 would not apply here.
6. Do not add any Telegram channels to the Wiki.
</details>

---

Enjoy flashing your Android device with the best Treble GSIs available!
