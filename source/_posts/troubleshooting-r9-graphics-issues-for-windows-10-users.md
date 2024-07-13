---
title: Troubleshooting R9 Graphics Issues for Windows 10 Users
date: 2024-07-12T01:10:35.674Z
updated: 2024-07-13T01:10:35.674Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: This Article Describes Troubleshooting R9 Graphics Issues for Windows 10 Users
excerpt: This Article Describes Troubleshooting R9 Graphics Issues for Windows 10 Users
keywords: R9 Graphics Troubleshooting,Windows 10 Graphics Fixes,NVIDIA R9 GPU Error Resolution,Graphics Card Support for Windows 10,Troubleshoot Graphics Issues in Windows,Fixing NVIDIA Graphics Problems,R9 Graphics Card Compatibility with Windows 10
thumbnail: https://thmb.techidaily.com/96ca9c739207d23d042e7f8016b381f18f2564ff73ddf98034c5d696bcc3f7e9.jpg
---

## Troubleshooting R9 Graphics Issues for Windows 10 Users

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
<li><a href="https://ai-editing-video.techidaily.com/updated-2024-approved-best-video-editing-courses-online-with-certificate/"><u>Updated 2024 Approved Best Video Editing Courses Online with Certificate</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-unveiling-the-power-of-photo-editing-techniques-to-add-text-in-windowsmacos/"><u>[Updated] In 2024, Unveiling the Power of Photo Editing  Techniques to Add Text in Windows/MacOS</u></a></li>
<li><a href="https://network-issues.techidaily.com/repaired-addressing-the-internet-disconnect-in-cod-cold-war/"><u>[REPAIRED] Addressing the Internet Disconnect in CoD Cold War</u></a></li>
<li><a href="https://network-issues.techidaily.com/nvidia-carrier-lacking-dx-acceleration/"><u>Nvidia Carrier Lacking DX Acceleration</u></a></li>
<li><a href="https://network-issues.techidaily.com/banish-display-defects-in-windows/"><u>Banish Display Defects in Windows</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixing-absent-display-preferences-on-nvidia-graphics/"><u>Fixing Absent Display Preferences on Nvidia Graphics</u></a></li>
<li><a href="https://network-issues.techidaily.com/improve-windows-graphics-by-installing-current-intel-drivers/"><u>Improve Windows Graphics by Installing Current Intel Drivers</u></a></li>
<li><a href="https://network-issues.techidaily.com/wi-fi-driver-uninstalled-reinstate-windows-10-card/"><u>Wi-Fi Driver Uninstalled? Reinstate Windows 10 Card</u></a></li>
<li><a href="https://network-issues.techidaily.com/nvidia-boosts-geforce-210-performance-on-win10-os/"><u>NVIDIA Boosts GeForce 210 Performance on WIN10 OS</u></a></li>
<li><a href="https://network-issues.techidaily.com/uninterrupted-adventure-fixing-fallout-4-pc-issues/"><u>Uninterrupted Adventure: Fixing Fallout 4 PC Issues</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024s-premier-voice-transformation-tools/"><u>Updated 2024S Premier Voice Transformation Tools</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/android-call-history-recovery-recover-deleted-call-logs-from-hot-40-by-fonelab-android-recover-call-logs/"><u>Android Call History Recovery - recover deleted call logs from Hot 40</u></a></li>
<li><a href="https://network-issues.techidaily.com/solved-quick-flicker-on-dell-display/"><u>[Solved] Quick Flicker on Dell Display</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-expand-your-viewing-realm-on-youtube-platforms/"><u>[New] Expand Your Viewing Realm on YouTube Platforms</u></a></li>
<li><a href="https://network-issues.techidaily.com/clearing-up-blurry-textures-in-far-cry-6-gameplay/"><u>Clearing Up Blurry Textures in Far Cry 6 Gameplay</u></a></li>
<li><a href="https://network-issues.techidaily.com/revamping-bdr-for-win-versions-11-to-7/"><u>Revamping BDR for Win Versions 11 to 7</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-adjust-your-timeline-facebook-look-back-guide/"><u>[Updated] In 2024, Adjust Your Timeline  Facebook Look Back Guide</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-the-ultimate-list-top-10-free-online-video-editors-without-watermarks/"><u>New In 2024, The Ultimate List Top 10 Free Online Video Editors Without Watermarks</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/does-htc-u23-support-mov-videos-by-aiseesoft-video-converter-play-mov-on-android/"><u>Does HTC U23 support MOV videos ?</u></a></li>
<li><a href="https://network-issues.techidaily.com/visual-configuration-saved-and-fixed/"><u>Visual Configuration Saved & Fixed</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-after-deleting-from-recently-deleted-on-iphone-6s-plus-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to recover deleted photos after deleting from Recently Deleted on iPhone 6s Plus | Stellar</u></a></li>
<li><a href="https://network-issues.techidaily.com/solving-hp-display-dimming-troubles/"><u>Solving HP Display Dimming Troubles</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixing-no-compatible-graphics-overwatch-update-resolved/"><u>Fixing No Compatible Graphics: Overwatch Update Resolved</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-navigating-through-top-film-makers-landscape/"><u>[New] Navigating Through Top Film Makers' Landscape</u></a></li>
<li><a href="https://network-issues.techidaily.com/hassle-free-intel-graphics-3000-win11-upgrade/"><u>Hassle-Free Intel Graphics 3000 Win11 Upgrade</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-hastening-social-media-sharing-between-fb-and-tiktok/"><u>[Updated] In 2024, Hastening Social Media Sharing Between FB and TikTok</u></a></li>
<li><a href="https://network-issues.techidaily.com/ending-dark-windows-display-post-update/"><u>Ending Dark Windows Display Post-Update</u></a></li>
<li><a href="https://network-issues.techidaily.com/overhauling-amd-radeon-r9-driver-stability-in-w10/"><u>Overhauling AMD Radeon R9 Driver Stability in W10</u></a></li>
<li><a href="https://network-issues.techidaily.com/recovered-lost-wi-fi-adapter-on-latest-os/"><u>[RECOVERED] Lost Wi-Fi Adapter on Latest OS</u></a></li>
<li><a href="https://network-issues.techidaily.com/dampening-discoloration-in-win7-output/"><u>Dampening Discoloration in Win7 Output</u></a></li>
<li><a href="https://network-issues.techidaily.com/uninterrupted-video-experience-post-windows-10-upgrade/"><u>Uninterrupted Video Experience Post-Windows 10 Upgrade</u></a></li>
</ul></div>
