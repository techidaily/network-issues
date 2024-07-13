---
title: "Removing Obstacles: Fixing Drivers of R9 on Win10"
date: 2024-07-12T00:36:34.251Z
updated: 2024-07-13T00:36:34.251Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: "This Article Describes Removing Obstacles: Fixing Drivers of R9 on Win10"
excerpt: "This Article Describes Removing Obstacles: Fixing Drivers of R9 on Win10"
keywords: R9 Driver Troubleshooting,Fixing R9 Compatibility Issues on Windows 10,Removing Obstacles with R9 Drivers on Windows 10,Optimize R9 Performance on Windows 10,Resolving Graphics Rendering Problems (R9) in Windows 10,Improve Nvidia GeForce R9 on Win10,Enhancing Driver Stability for Nvidia R9 on Windows 10
thumbnail: https://thmb.techidaily.com/5f9bdb089a72cbfbce20351e13d8c69867a47335c73b8710c5509727c5e15028.jpg
---

## Removing Obstacles: Fixing Drivers of R9 on Win10

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
<li><a href="https://network-issues.techidaily.com/fix-laptop-screen-wont-turn-on-issue/"><u>Fix Laptop Screen Won’t Turn On Issue</u></a></li>
<li><a href="https://fox-info.techidaily.com/wave-riders-guide-tips-on-underwater-video-with-your-gopro-camera-for-2024/"><u>Wave Riders' Guide  Tips on Underwater Video with Your GoPro Camera for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/zoom-past-stumbles-in-games/"><u>Zoom Past Stumbles in Games</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-elite-sound-recording-tools-11-selection/"><u>[Updated] Elite Sound Recording Tools - #11 Selection</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/in-2024-s-top-rated-mp4-to-mp3-converter-apps-for-smartphone-users/"><u>In 2024, S Top-Rated MP4 to MP3 Converter Apps for Smartphone Users</u></a></li>
<li><a href="https://network-issues.techidaily.com/gpu-detected-none-found-latest-resolution/"><u>GPU Detected: None Found - Latest Resolution</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixed-monitor-not-displaying-full-screen-windows-11/"><u>Fixed: Monitor Not Displaying Full Screen Windows 11</u></a></li>
<li><a href="https://network-issues.techidaily.com/skip-the-wait-amd-bugs-solved/"><u>Skip the Wait: AMD Bugs Solved</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-from-disc-to-digital-how-to-transfer-your-dvd-collection-to-computer-or-mobile/"><u>2024 Approved From Disc to Digital How to Transfer Your DVD Collection to Computer or Mobile</u></a></li>
<li><a href="https://network-issues.techidaily.com/meeting-min-reqs-upgrading-hardware-for-driver-success/"><u>Meeting Min Reqs: Upgrading Hardware for Driver Success</u></a></li>
<li><a href="https://network-issues.techidaily.com/gaming-revolution-nvidias-latest-driver-upgrade-for-win10/"><u>Gaming Revolution: Nvidia's Latest Driver Upgrade for Win10</u></a></li>
<li><a href="https://network-issues.techidaily.com/ensuring-a-fluid-gaming-session-with-civ-5-on-pc/"><u>Ensuring a Fluid Gaming Session with Civ 5 on PC</u></a></li>
<li><a href="https://network-issues.techidaily.com/nvidia-driver-anomaly-corrected-display-normalized/"><u>Nvidia Driver Anomaly Corrected - Display Normalized</u></a></li>
<li><a href="https://network-issues.techidaily.com/strategies-for-cpugpu-fan-synchronization/"><u>Strategies for CPU/GPU Fan Synchronization</u></a></li>
<li><a href="https://network-issues.techidaily.com/rectify-diagonal-glyph-anomalies/"><u>Rectify Diagonal Glyph Anomalies</u></a></li>
<li><a href="https://network-issues.techidaily.com/how-do-i-fix-0xc1900101-error-when-installing-windows-11/"><u>How Do I Fix 0xC1900101 Error When Installing Windows 11</u></a></li>
<li><a href="https://network-issues.techidaily.com/effortless-anthem-playback-handling-lag/"><u>Effortless Anthem Playback: Handling Lag</u></a></li>
<li><a href="https://network-issues.techidaily.com/smoothen-screen-fluctuations-pro-7/"><u>Smoothen Screen Fluctuations (Pro 7)</u></a></li>
<li><a href="https://network-issues.techidaily.com/diagnosing-hidden-lcd-blackout-causes/"><u>Diagnosing Hidden LCD Blackout Causes</u></a></li>
<li><a href="https://network-issues.techidaily.com/reintroduced-lost-network-interface-on-windows-10-laptop/"><u>Reintroduced Lost Network Interface on Windows 10 Laptop</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-sharpen-your-iphone-hdri-discover-the-top-4-fixes-for-premiere-pro-professionals/"><u>2024 Approved  Sharpen Your iPhone HDRI  Discover the Top 4 Fixes for Premiere Pro Professionals</u></a></li>
<li><a href="https://network-issues.techidaily.com/balance-screens-horizontal-boundaries/"><u>Balance Screen's Horizontal Boundaries</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixed-display-component-reset-and-reboot/"><u>[Fixed] Display Component Reset and Reboot</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-overwatch-gameplay-recording-made-easy-for-2024/"><u>[Updated] Overwatch Gameplay Recording Made Easy for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/unveil-solution-to-sims-4-blankness/"><u>Unveil Solution to Sims 4 Blankness</u></a></li>
<li><a href="https://android-unlock.techidaily.com/10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-htc-u23-by-drfone-android/"><u>10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On HTC U23</u></a></li>
<li><a href="https://network-issues.techidaily.com/onyx-outcome-new-driver/"><u>Onyx Outcome: New Driver?</u></a></li>
<li><a href="https://network-issues.techidaily.com/nvidia-gfx-210-driver-enhancement-on-w10-os/"><u>NVIDIA GFX-210 Driver Enhancement on W10 OS</u></a></li>
<li><a href="https://network-issues.techidaily.com/crisp-image-window-purity/"><u>Crisp Image: Window Purity</u></a></li>
<li><a href="https://network-issues.techidaily.com/driver-disruption-ends-nvidia-display-works/"><u>Driver Disruption Ends: Nvidia Display Works</u></a></li>
<li><a href="https://network-issues.techidaily.com/1719974889342-solve-video-stuttering-issues-quickly-and-easily/"><u>Solve Video Stuttering Issues. Quickly & Easily</u></a></li>
<li><a href="https://network-issues.techidaily.com/lenovo-touch-screen-not-working-solved/"><u>Lenovo Touch Screen Not Working [SOLVED]</u></a></li>
<li><a href="https://network-issues.techidaily.com/amd-releases-new-drivers-boosting-windows-11-performance-on-hd-6950/"><u>AMD Releases New Drivers, Boosting Windows 11 Performance on HD 6950</u></a></li>
<li><a href="https://network-issues.techidaily.com/win11-unable-to-alter-screen-settings/"><u>Win11: Unable To Alter Screen Settings</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-in-2024-making-bank-with-youtube-an-analysis-of-pewdiepies-earnings/"><u>[New] In 2024, Making Bank with YouTube  An Analysis of PewDiePie’s Earnings</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-exclusive-free-mcb-banner-designs/"><u>In 2024, Exclusive Free MCB Banner Designs</u></a></li>
<li><a href="https://network-issues.techidaily.com/guiding-through-windows-7-screenshake-solutions/"><u>Guiding Through Windows 7 Screenshake Solutions</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-comprehensive-compilation-of-world-class-e-learning-sites-minus-udemy/"><u>[New] 2024 Approved  Comprehensive Compilation of World-Class E-Learning Sites (Minus Udemy)</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcoming-windows-blackout-after-fall-update/"><u>Overcoming Windows Blackout After Fall Update</u></a></li>
<li><a href="https://network-issues.techidaily.com/monitor-glitch-fix-blinking-solution/"><u>Monitor Glitch Fix: Blinking Solution</u></a></li>
<li><a href="https://network-issues.techidaily.com/cut-down-windows-10-monitor-range/"><u>Cut Down Windows 10 Monitor Range</u></a></li>
</ul></div>
