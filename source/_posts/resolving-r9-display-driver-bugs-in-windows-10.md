---
title: Resolving R9 Display Driver Bugs in Windows 10
date: 2024-11-10T22:47:14.355Z
updated: 2024-11-13T22:23:05.286Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: This Article Describes Resolving R9 Display Driver Bugs in Windows 10
excerpt: This Article Describes Resolving R9 Display Driver Bugs in Windows 10
keywords: Fixing R9 GPU Issues on Windows 10,Troubleshooting R9 Graphics Driver Crashes,Solutions for R9 Display Driver Errors in Windows,R9 Graphics Card Compatibility Guide,NVIDIA R9 Driver Optimization Tips,Fix Common R9 Display Driver Problems,R9 GPU Support and Troubleshooting for Windows
thumbnail: https://thmb.techidaily.com/f379595bc7b1cd3050b5ae0744653e1ab5e0a38460cd4cd6298021feb9a9cc65.jpg
---

## Resolving R9 Display Driver Bugs in Windows 10

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
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-easy-guide-online-tools-to-save-your-youtube-videos/"><u>[Updated] 2024 Approved Easy Guide Online Tools to Save Your YouTube Videos</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-stream-like-a-champion-top-3-techniques-for-successful-lol-gameplay-capture-for-2024/"><u>[Updated] Stream Like a Champion Top 3 Techniques for Successful LOL Gameplay Capture for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-best-handheld-cameras-for-uninterrupted-shots/"><u>2024 Approved Best Handheld Cameras for Uninterrupted Shots</u></a></li>
<li><a href="https://win-able.techidaily.com/best-screen-capture-software-of-the-year-our-selection-for-mac-and-windows-users/"><u>Best Screen Capture Software of the Year: Our Selection for Mac and Windows Users!</u></a></li>
<li><a href="https://vp-tips.techidaily.com/concealed-identities-quick-tips-for-face-obscuration-in-images-for-2024/"><u>Concealed Identities Quick Tips for Face-Obscuration in Images for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/correcting-blackout-on-windows-11-post-fall/"><u>Correcting Blackout on Windows 11 Post-Fall</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-activate-and-use-life360-ghost-mode-on-nubia-red-magic-8s-pro-drfone-by-drfone-virtual-android/"><u>How To Activate and Use Life360 Ghost Mode On Nubia Red Magic 8S Pro | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-facts-you-need-to-know-about-screen-mirroring-oneplus-ace-2-drfone-by-drfone-android/"><u>In 2024, 3 Facts You Need to Know about Screen Mirroring OnePlus Ace 2 | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-remove-or-bypass-knox-enrollment-service-on-vivo-v29-pro-by-drfone-android/"><u>In 2024, How To Remove or Bypass Knox Enrollment Service On Vivo V29 Pro</u></a></li>
<li><a href="https://network-issues.techidaily.com/monster-hunt-rebooted-crashed-game-restored/"><u>Monster Hunt Rebooted: Crashed Game Restored</u></a></li>
<li><a href="https://games-able.techidaily.com/navigate-to-peak-gaming-the-top-9-software-for-steam-decks/"><u>Navigate to Peak Gaming: The Top 9 Software for Steam Decks</u></a></li>
<li><a href="https://network-issues.techidaily.com/optimizing-windows-via-intel-gpu-update/"><u>Optimizing Windows via Intel GPU Update</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolved-invisible-wireless-adapter-in-windows-11/"><u>Resolved: Invisible Wireless Adapter in Windows 11</u></a></li>
<li><a href="https://network-issues.techidaily.com/1719974504839-screen-flicker-no-more/"><u>Screen Flicker, No More!</u></a></li>
<li><a href="https://network-issues.techidaily.com/solving-screen-flash-a-guide/"><u>Solving Screen Flash: A Guide</u></a></li>
<li><a href="https://network-issues.techidaily.com/understanding-the-excellence-in-4k-ultra-hds/"><u>Understanding the Excellence in 4K Ultra HDs</u></a></li>
<li><a href="https://network-issues.techidaily.com/visual-void-in-virtual-ventures/"><u>Visual Void in Virtual Ventures</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094422/7443" target="_top" id="2094422">
  <img src="//a.impactradius-go.com/display-ad/7443-2094422" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094422/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

