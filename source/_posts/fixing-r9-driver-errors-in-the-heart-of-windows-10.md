---
title: Fixing R9 Driver Errors in the Heart of Windows 10
date: 2024-11-13T17:31:33.172Z
updated: 2024-11-14T17:06:48.858Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: This Article Describes Fixing R9 Driver Errors in the Heart of Windows 10
excerpt: This Article Describes Fixing R9 Driver Errors in the Heart of Windows 10
keywords: Fixing R9 Driver Errors,Windows 10 Troubleshooting,R9 Driver Installation Guide,Windows 10 System Errors Resolutions,Fixing Common Windows 10 Errors,Troubleshooting Guide for Windows 10 Drivers,Error Recovery in Windows 10 Operating System
thumbnail: https://thmb.techidaily.com/d308f7cbef44fc72492251644b94fc820af3415416f540b09fcf25e37cb1c7dd.jpg
---

## Fixing R9 Driver Errors in the Heart of Windows 10

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
<li><a href="https://network-issues.techidaily.com/solved-god-of-war-performance-issue/"><u>[Solved] God of War Performance Issue</u></a></li>
<li><a href="https://fox-glue.techidaily.com/accelerated-windows-review-strategies-for-2024/"><u>Accelerated Windows Review Strategies for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/dell-desktop-hologram-glitch-resolved/"><u>Dell Desktop Hologram Glitch Resolved</u></a></li>
<li><a href="https://facebook.techidaily.com/eight-paths-how-netizens-bond-across-cyberspace/"><u>Eight Paths: How Netizens Bond Across Cyberspace</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixing-nvidia-7025nforce630a-windows-error/"><u>Fixing Nvidia 7025/nForce630a Windows Error</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/harnessing-skills-a-tailored-approach-to-graphic-careers/"><u>Harnessing Skills A Tailored Approach to Graphic Careers</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-call-logs-from-p55-5g-by-fonelab-android-recover-call-logs/"><u>How to retrieve erased call logs from P55 5G?</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-stream-apple-iphone-13-pro-max-to-computer-drfone-by-drfone-ios/"><u>How to Stream Apple iPhone 13 Pro Max to Computer? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-where-is-the-best-place-to-catch-dratini-on-vivo-y200e-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Where Is the Best Place to Catch Dratini On Vivo Y200e 5G | Dr.fone</u></a></li>
<li><a href="https://discover-great.techidaily.com/macicloud4/"><u>Mac上でiCloudファイル同期がうまくいかない時の方法4つ</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/mastering-visual-storytelling-with-free-images-from-these-esteemed-online-portals-for-2024/"><u>Mastering Visual Storytelling with Free Images From These Esteemed Online Portals for 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-2024-approved-how-to-add-subtitles-in-canva/"><u>New 2024 Approved How to Add Subtitles in Canva?</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcoming-win7-display-jitter/"><u>Overcoming Win7 Display Jitter</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolving-spec-limitations-before-driver-installation/"><u>Resolving Spec Limitations Before Driver Installation</u></a></li>
<li><a href="https://network-issues.techidaily.com/silent-fail-screen-turned-black/"><u>Silent Fail: Screen Turned Black</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389">
  <img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

