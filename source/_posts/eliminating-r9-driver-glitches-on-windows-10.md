---
title: Eliminating R9 Driver Glitches on Windows 10
date: 2024-07-02T03:26:09.050Z
updated: 2024-07-03T03:26:09.050Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: This Article Describes Eliminating R9 Driver Glitches on Windows 10
excerpt: This Article Describes Eliminating R9 Driver Glitches on Windows 10
keywords: Windows 10 R9 Driver Issues,Fixing R9 Driver Bugs on Windows 10,Eliminating Graphics Errors with R9 Driver Update,Troubleshooting R9 Driver Problems on Windows 10,Resolving R9 Glitches in Windows 10 OS,Preventive Maintenance for R9 Drivers on Windows 10,How to Fix R9 Graphics Issues on Windows 10 System
thumbnail: https://thmb.techidaily.com/46562a4985b29bb04ac045f40f195ad5a81e8c6a78d3deb58b3600f2a5e9d7c1.jpg
---

## Eliminating R9 Driver Glitches on Windows 10

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
<li><a href="https://network-issues.techidaily.com/resolved-graphic-device-discrepancy-win/"><u>Resolved Graphic Device Discrepancy - Win</u></a></li>
<li><a href="https://network-issues.techidaily.com/immediate-rectification-of-diagonal-distortion/"><u>Immediate Rectification of Diagonal Distortion</u></a></li>
<li><a href="https://network-issues.techidaily.com/revealing-hidden-windows-10-color-after-cu/"><u>Revealing Hidden Windows 10 Color After CU</u></a></li>
<li><a href="https://network-issues.techidaily.com/win11-display-issue-resolved-no-fullscreen/"><u>Win11 Display Issue - Resolved No Fullscreen</u></a></li>
<li><a href="https://network-issues.techidaily.com/shine-through-fixing-win11-screen-flicker/"><u>Shine Through: Fixing Win11 Screen Flicker</u></a></li>
<li><a href="https://network-issues.techidaily.com/adjusting-improper-orientation-in-windows-10-screen/"><u>Adjusting Improper Orientation in Windows 10 Screen</u></a></li>
<li><a href="https://network-issues.techidaily.com/remedying-undetected-gigabyte-hardware-on-system/"><u>Remedying Undetected Gigabyte Hardware on System</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixed-unsuccessful-gdx-creation-on-vistawin/"><u>Fixed Unsuccessful GDX Creation on VistaWin</u></a></li>
<li><a href="https://network-issues.techidaily.com/removing-mysterious-monitor-darkness/"><u>Removing Mysterious Monitor Darkness</u></a></li>
<li><a href="https://network-issues.techidaily.com/fix-window-fuzziness-boost-productivity/"><u>Fix Window Fuzziness, Boost Productivity</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-the-premier-selection-of-logic-pro-x-extensions-8-plugins-to-elevate-your-sound-design/"><u>Updated 2024 Approved The Premier Selection of Logic Pro X Extensions 8 Plugins to Elevate Your Sound Design</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-lava-blaze-2-pro-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>In 2024, How to Cast Lava Blaze 2 Pro to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/unlock-your-nokias-potential-the-top-20-lock-screen-apps-you-need-to-try-by-drfone-android/"><u>Unlock Your Nokias Potential The Top 20 Lock Screen Apps You Need to Try</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-meme-ing-in-virtual-space-top-funny-vr-imagery-and-how-to-make-it/"><u>2024 Approved  Meme-Ing in Virtual Space  Top Funny VR Imagery and How to Make It</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-gmail-password-on-infinix-smart-7-devices-by-drfone-android/"><u>How to Reset Gmail Password on Infinix Smart 7 Devices</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-2023-complete-guide-twitter-reaction-videos/"><u>[New] 2024 Approved  2023 Complete Guide | Twitter Reaction Videos</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-whats-cooking-10-viral-food-scenes-on-tiktok/"><u>2024 Approved  What's Cooking? 10 Viral Food Scenes on TikTok</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-essential-hashtag-analyzers-facebook-twitter-and-instagram-edition/"><u>[New] In 2024, Essential Hashtag Analyzers  Facebook, Twitter & Instagram Edition</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-uncluttered-window-logger-w10-version/"><u>2024 Approved  Uncluttered Window Logger  W10 Version</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/how-to-dominate-the-viral-video-edit-scene-on-tiktok/"><u>How to Dominate the Viral Video Edit Scene on TikTok</u></a></li>
</ul></div>
