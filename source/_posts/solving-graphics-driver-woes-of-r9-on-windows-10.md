---
title: Solving Graphics Driver Woes of R9 on Windows 10
date: 2024-07-12T00:28:33.306Z
updated: 2024-07-13T00:28:33.306Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: This Article Describes Solving Graphics Driver Woes of R9 on Windows 10
excerpt: This Article Describes Solving Graphics Driver Woes of R9 on Windows 10
keywords: AMD Radeon HD 7970 Graphics Driver Troubleshooting,Windows 10 Compatibility Issues with AMD Graphics Driver,Fixing R9 Graphics Driver Errors in Windows 10,Solving Graphic Driver Conflicts on AMD R9 Windows 10,Overcoming Compatibility Issues Between AMD GPU and Windows 10,Optimizing AMD Radeon HD 7970 Performance on Windows 10,Addressing Common Problems Faced by Users of AMD Graphics Driver in Windows 10
thumbnail: https://thmb.techidaily.com/9f799a63c5ced001089eec847a965c77100b85a292d3d2c56946946b1d875c1f.jpg
---

## Solving Graphics Driver Woes of R9 on Windows 10

![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_58647de6a91e7.jpg)

AMD Radeon R9 series of graphics card is one of the perfect choices for gamers. Windows 10 users have reported that they are having some problem with their AMD Radeon R9 series of graphics card.  
  
For example, some users reported that the screen would go blank after 5 to 20 minutes into the games and the only thing left to do was to restart. And that the screen flickered when they are playing games and the screen brightness could not be adjusted.
  
In such case, you might need to consider getting your graphics card driver checked and fix any problem it has by yourself.
  
In this post, we will show you exactly how to do it. So, just read along and follow the instructions to get your graphics card back to normal.
  
[**Step one: Run DISM command**](#1)
[**Step two: Run SFC command**](#2)
[**Step three: Clean install AMD Radeon R9 display driver**](#3)
  
Before we proceed with the following resolutions, please make sure that you have done the following things:
  
1) Check to see if you have installed the latest patches and fixes updates provided by Windows.In Windows, most patches and fixes are available through**Windows Update**. It is suggested that you check whether your computer has installed the latest released patches in**Settings > Updates & security.**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/settings-updates-security.jpg)

2) Make sure you have installed the latest version of the Microsoft .Net Framework. For more information as to how to install the latest version of Microsoft .Net Framework, please visit this [**post here**](https://tools.techidaily.com/drivereasy/download/).
  
 **Step one: Run DISM command**
  
 DISM stands for Deployment Image Servicing and Management, which is a tool that helps you scan the integrity of your Windows image.
  
 1) Press**Windows key** and**X** at the same time, then choose**Command Prompt (Run as administrator)** .
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_586482f8af0b5.png)
  
 When prompted with administrator permission, press**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_586483a425d5a.jpg)
  
 2) In the command prompt window, type in the following command:

DISM /Online /Cleanup-Image /RestoreHealth

 Make sure that you have made no typo, and hit**Enter** .
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_58648713723c7.jpg)

 3) You need to wait for a while with patience for the process to finish, especially when it reaches 20%. The operation will finish in a few minutes.  
  
 **Step two: Run SFC command**
  
 SFC stands for system file checker, which is another tool that helps you scan for all protected system files and will replace the corrupted, damaged and/or incorrect versions with correct Microsoft versions.
  
 1) Press**Windows key** and**X** at the same time, then choose**Command Prompt (Run as administrator)** .
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_586482f8af0b5.png)
  
 When prompted with administrator permission, press**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_586483a425d5a.jpg)
  
2) In the command prompt window, type in command:**SFC /SCANNOW**. Make sure that you have made no typo and hit**Enter**.
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_58648e300e3c1.jpg)

3) Wait for a while for the process to finish. If no problem is found here, please move on to the next step.
  
 **Step three: Clean install AMD Radeon R9 display driver**
  
**Note**: Before proceeding with the steps below, it is highly suggested that you **[create a restore point first](https://tools.techidaily.com/drivereasy/download/) .**
  
1) Follow the path:**Start**button**\> Control Panel > Uninstall a program**(View by**Category**).  
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_58648e5733e51.jpg)

2) If you are with AMD processors, select**Catalyst Control Center**and choose**Uninstall**.
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_58648f8f4dd21.jpg)
  
 If you are with Intel processors, select to uninstall **ALL** AMD software that you can see in this window.  
  
 3) Press**Windows key** and**X** at the same time, then choose**Device Manager** .

![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_586490d260746.png)

4) Locate**Display adapters**category, then double click the**AMD Radeon R9**series of display driver that you have.
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_5864a9af8c728.jpg)

5) Under**Driver**tab, choose**Uninstall**.
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_5864a9dcb005b.jpg)
  
 Tick the box for**Delete the driver software for this device** option and click**OK** to continue.
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_5864ab747efcd.png)

 6) Reboot your PC.
  
 7) Then**download** the AMD Clean Uninstall Utility from its support website. Then double click the**AMDCleanUtility.exe** icon to run the application.  
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_5864ac776f616.png)
  
 Then just follow the instructions on screen to get all your AMD driver and application components removed.  
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_5864acd59401a.jpg)
  
 Your computer will restart when the whole process if finished.
  
**Note** : If you already have a trusted application or driver remover, you can use it to do the full uninstall too.
  
 8) When your computer restart again, download the latest version of the AMD Radeon R9 series driver from AMD website and then install it manually.  
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_5864b2625647d.png)

 If you want to save yourself more time and energy for other things, you can leave your driver problems to [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) . It automatically help you detects, downloads and updates device drivers that are missing or outdated on your computer. And, there are only two steps you take to do it:
  
 Step one: press the**Scan Now** button so [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) can help you detect for needed drivers.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58e894bc3e848.png)
  
 Step two: press the**Update** button so [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) can help you download the setup file for the device driver that you need.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58e897add407d.jpg)
  
 If you want to enjoy more features such as driver backup and driver restore, as well as professional tech support waiting to solve your driver problems, you can have a try at the [**professional version of Driver Easy**](https://tools.techidaily.com/drivereasy/download/) . If you are not satisfied with it, you can always ask for a refund thirty days within the purchase. Guaranteed.
  
 What’s with the waiting, come on and have a try at [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) now!

* [AMD](https://tools.techidaily.com/drivereasy/download/)

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>



<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://network-issues.techidaily.com/battery-of-patience-with-wi-fi-drops/"><u>Battery of Patience with Wi-Fi Drops</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-itel-a60-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Itel A60</u></a></li>
<li><a href="https://network-issues.techidaily.com/solved-fallout-4-crashing-on-pc-easily/"><u>[Solved] Fallout 4 Crashing on PC [Easily]</u></a></li>
<li><a href="https://network-issues.techidaily.com/mending-windows-10-rapid-flash-problem/"><u>Mending Windows 10 Rapid Flash Problem</u></a></li>
<li><a href="https://network-issues.techidaily.com/leap-over-delays-in-your-gaming/"><u>Leap Over Delays in Your Gaming</u></a></li>
<li><a href="https://network-issues.techidaily.com/installing-latest-intel-graphic-drivers-in-windows/"><u>Installing Latest Intel Graphic Drivers in Windows</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-direct-engagement-broadcasting-from-your-xbox-to-fb/"><u>In 2024, Direct Engagement  Broadcasting From Your Xbox to FB</u></a></li>
<li><a href="https://network-issues.techidaily.com/no-graphics-card-match-overwatch-update-fixed-issue/"><u>No Graphics Card Match - Overwatch Update Fixed Issue</u></a></li>
<li><a href="https://network-issues.techidaily.com/taming-the-beast-resolving-fallout-4-pc-problems/"><u>Taming the Beast: Resolving Fallout 4 PC Problems</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-perfect-your-soundtracks-essential-edits-for-crafting-podcasts-in-garageband/"><u>In 2024, Perfect Your Soundtracks  Essential Edits for Crafting Podcasts in GarageBand</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcoming-amd-radeon-r9-hurdles-with-ease-on-win11/"><u>Overcoming AMD Radeon R9 Hurdles with Ease on Win11</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixing-gpus-fixedcode-22-issue/"><u>Fixing GPU's FixedCode #22 Issue</u></a></li>
<li><a href="https://network-issues.techidaily.com/solved-dxgkrnlsys-blue-screen-of-death-on-windows/"><u>[Solved] dxgkrnl.sys Blue Screen of Death on Windows</u></a></li>
<li><a href="https://network-issues.techidaily.com/enabling-internal-cameras-on-asus-systems/"><u>Enabling Internal Cameras on Asus Systems</u></a></li>
<li><a href="https://network-issues.techidaily.com/correct-overseen-graphics-setup/"><u>Correct Overseen Graphics Setup</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-5-premium-ps1-game-simulators-for-pc-gamers/"><u>[New] 5 Premium PS1 Game Simulators for PC Gamers</u></a></li>
<li><a href="https://network-issues.techidaily.com/hardware-compatibility-success-for-nvidia-install/"><u>Hardware Compatibility Success for NVIDIA Install</u></a></li>
<li><a href="https://network-issues.techidaily.com/repaired-offline-mode-cod-cold-war-2024-update/"><u>[REPAIRED] Offline Mode: CoD Cold War 2024 Update</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-everlasting-screen-saving-utility/"><u>2024 Approved  Everlasting Screen Saving Utility</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-cash-creation-in-content-a-deep-dive-into-vids-and-videos/"><u>[Updated] In 2024, Cash Creation in Content  A Deep Dive Into Vids and Videos</u></a></li>
<li><a href="https://network-issues.techidaily.com/plain-fix-advice-no-current-gfx-with-nvidia/"><u>Plain Fix Advice: No Current GFX with NVIDIA</u></a></li>
<li><a href="https://network-issues.techidaily.com/nvidia-sync-problem-addressed/"><u>Nvidia Sync: Problem Addressed</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixed-windows-11-wireless-network-disappearing-act/"><u>[FIXED] Windows 11 Wireless Network Disappearing Act</u></a></li>
<li><a href="https://network-issues.techidaily.com/install-completed-without-nvidia-errors/"><u>Install Completed Without NVIDIA Errors</u></a></li>
<li><a href="https://network-issues.techidaily.com/eliminate-sims-4-white-screen-anomalies/"><u>Eliminate Sims 4 White Screen Anomalies</u></a></li>
<li><a href="https://network-issues.techidaily.com/display-driver-fix-smooth-operation-resumed/"><u>Display Driver Fix: Smooth Operation Resumed</u></a></li>
<li><a href="https://network-issues.techidaily.com/lifted-locks-thermal-settings-reached/"><u>Lifted Locks: Thermal Settings Reached</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcoming-inverted-display-issue-in-wins11-update/"><u>Overcoming Inverted Display Issue in Wins11 Update</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolution-windows-11-excessive-width/"><u>[RESOLUTION] Windows 11 Excessive Width</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolution-found-windows-stopped-on-nvidia-error/"><u>Resolution Found: Windows Stopped on Nvidia Error</u></a></li>
<li><a href="https://network-issues.techidaily.com/accelerate-gaming-experience/"><u>Accelerate Gaming Experience</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/bridging-the-gap-integrating-spotify-and-youtube-music-playlists-for-2024/"><u>Bridging the Gap  Integrating Spotify and YouTube Music Playlists for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/gaming-triumph-crashed-game-repaired-swiftly/"><u>Gaming Triumph: Crashed Game Repaired Swiftly</u></a></li>
<li><a href="https://network-issues.techidaily.com/solved-epic-games-download-slow-download-stuck/"><u>[SOLVED] Epic Games Download Slow /Download Stuck</u></a></li>
<li><a href="https://network-issues.techidaily.com/direct-troubleshooting-route-no-current-gfx-wnvidia/"><u>Direct Troubleshooting Route: No Current GFX W/NVIDIA</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-premiere-pro-mastering-full-screen-views/"><u>2024 Approved  Premiere Pro  Mastering Full-Screen Views</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-top-15-apps-to-hack-wifi-password-on-realme-c33-2023-by-drfone-android/"><u>In 2024, Top 15 Apps To Hack WiFi Password On Realme C33 2023</u></a></li>
<li><a href="https://network-issues.techidaily.com/nvidias-nighthawk-encounters-overcoming-game-crashes/"><u>Nvidia's Nighthawk Encounters - Overcoming Game Crashes</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-top-meme-maker-apps-for-android-and-ios-devices-2023-update/"><u>New In 2024, Top Meme Maker Apps for Android & iOS Devices (2023 Update)</u></a></li>
<li><a href="https://network-issues.techidaily.com/seamless-coexistence-of-win10-and-geforce-98/"><u>Seamless Coexistence of Win10 & GeForce 98</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-enrich-your-brain-with-these-15-ultimate-science-youtubes/"><u>In 2024, Enrich Your Brain with These 15 Ultimate Science Youtubes</u></a></li>
</ul></div>
