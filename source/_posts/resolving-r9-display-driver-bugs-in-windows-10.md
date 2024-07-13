---
title: Resolving R9 Display Driver Bugs in Windows 10
date: 2024-07-12T00:33:34.379Z
updated: 2024-07-13T00:33:34.379Z
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
<li><a href="https://network-issues.techidaily.com/clearing-up-windows-11s-streaming-obstacles-successfully/"><u>Clearing Up Windows 11’S Streaming Obstacles Successfully</u></a></li>
<li><a href="https://video-capture.techidaily.com/premier-5-time-lapse-camera-apps/"><u>Premier 5 Time-Lapse Camera Apps</u></a></li>
<li><a href="https://network-issues.techidaily.com/restored-tv-viewing-via-hdmi-laptop-connected-successfully/"><u>[Restored] TV Viewing via HDMI, Laptop Connected Successfully</u></a></li>
<li><a href="https://network-issues.techidaily.com/correcting-lenovo-screen-brightness-loss/"><u>Correcting Lenovo Screen Brightness Loss</u></a></li>
<li><a href="https://network-issues.techidaily.com/bridge-ghost-graphics-discrepancy/"><u>Bridge Ghost Graphics Discrepancy</u></a></li>
<li><a href="https://network-issues.techidaily.com/improve-your-monitors-layout-with-wins11-tools/"><u>Improve Your Monitor's Layout with Wins11 Tools</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcoming-freeze-save-display-issue-resolved/"><u>Overcoming Freeze: Save Display Issue Resolved</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixed-lost-network-card-on-windows-10-desktop/"><u>[FIXED] Lost Network Card on Windows 10 Desktop</u></a></li>
<li><a href="https://network-issues.techidaily.com/tackling-graphics-conflict-intel-and-nvidia-fix-on-windows-10-systems/"><u>Tackling Graphics Conflict: Intel & NVIDIA Fix on Windows 10 Systems</u></a></li>
<li><a href="https://network-issues.techidaily.com/strategies-for-controlling-lenovo-screenshake/"><u>Strategies for Controlling Lenovo Screenshake</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-is-coqui-voice-cloning-worth-the-hype-a-comprehensive-review/"><u>New Is Coqui Voice Cloning Worth the Hype? A Comprehensive Review</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolved-error-22-graphics-driver/"><u>Resolved Error #22, Graphics Driver</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-in-2024-exploring-the-most-popular-websites-for-chilling-soundtracks-2023-rankings/"><u>New In 2024, Exploring the Most Popular Websites for Chilling Soundtracks (2023 Rankings)</u></a></li>
<li><a href="https://network-issues.techidaily.com/gaming-nightmare-nvidias-rtx-3080-fix-guide/"><u>Gaming Nightmare: Nvidia's RTX 3080 Fix-Guide</u></a></li>
<li><a href="https://network-issues.techidaily.com/restore-cursor-functionality-on-black-screen/"><u>Restore Cursor Functionality on Black Screen</u></a></li>
<li><a href="https://network-issues.techidaily.com/windows-8-step-by-step-guide-to-launch-safe-mode-and-driver-uninstallation/"><u>Windows 8: Step-by-Step Guide to Launch Safe Mode and Driver Uninstallation</u></a></li>
<li><a href="https://network-issues.techidaily.com/ninja-warrior-download-delayed/"><u>Ninja Warrior Download Delayed</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-fake-gps-location-pro-and-is-it-good-on-apple-iphone-x-drfone-by-drfone-virtual-ios/"><u>What is Fake GPS Location Pro and Is It Good On Apple iPhone X? | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/banishing-buzzing-visuals-from-win7/"><u>Banishing Buzzing Visuals From Win7</u></a></li>
<li><a href="https://network-issues.techidaily.com/eliminate-absence-in-sims-screens/"><u>Eliminate Absence in Sims' Screens</u></a></li>
<li><a href="https://network-issues.techidaily.com/hack-free-gaming-quick-fix-for-legends-crash/"><u>Hack-Free Gaming: Quick Fix for Legends Crash</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2023s-leading-podcast-applications-for-macos-for-2024/"><u>2023'S Leading Podcast Applications for macOS for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/improve-gameplay-speed-in-virtual-construction/"><u>Improve Gameplay Speed in Virtual Construction</u></a></li>
<li><a href="https://network-issues.techidaily.com/solving-asus-internal-webcam-issues/"><u>Solving Asus Internal Webcam Issues</u></a></li>
<li><a href="https://network-issues.techidaily.com/success-story-overcoming-amds-windows-10-driver-load-hurdle/"><u>Success Story: Overcoming AMD's Windows 10 Driver Load Hurdle</u></a></li>
<li><a href="https://network-issues.techidaily.com/crystal-clear-interface-effortless-change/"><u>Crystal-Clear Interface, Effortless Change</u></a></li>
<li><a href="https://network-issues.techidaily.com/opengl-quirk-found-and-resolved-in-nvidia-graphics/"><u>OpenGL Quirk Found & Resolved in Nvidia Graphics</u></a></li>
<li><a href="https://location-fake.techidaily.com/10-best-fake-gps-location-spoofers-for-honor-magic-5-drfone-by-drfone-virtual-android/"><u>10 Best Fake GPS Location Spoofers for Honor Magic 5 | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/direct3d-launch-attempt-failed-fixed/"><u>Direct3D Launch Attempt Failed, Fixed</u></a></li>
<li><a href="https://network-issues.techidaily.com/quick-fixes-for-youtube-background-issues-green/"><u>Quick Fixes for Youtube Background Issues (Green)</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/prime-selections-convert-youtube-videos-quickly/"><u>Prime Selections  Convert YouTube Videos Quickly</u></a></li>
<li><a href="https://network-issues.techidaily.com/missing-visual-hardware-solve-for-nvidia-gpu-lack-of-visibility/"><u>Missing Visual Hardware: Solve for NVIDIA GPU Lack of Visibility</u></a></li>
<li><a href="https://change-location.techidaily.com/here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-vivo-x90s-drfone-by-drfone-virtual-android/"><u>Here are Some Pro Tips for Pokemon Go PvP Battles On Vivo X90S | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/latest-graphics-purchase-blacked-out-monitor/"><u>Latest Graphics Purchase: Blacked-Out Monitor</u></a></li>
<li><a href="https://network-issues.techidaily.com/1719974137317-install-latest-intel-hd-graphics-3000-on-windows-10-swiftly/"><u>Install Latest Intel HD Graphics 3000 on Windows 10 Swiftly</u></a></li>
<li><a href="https://network-issues.techidaily.com/non-responsive-lenovo-touchscreen-resolved/"><u>Non-Responsive Lenovo Touchscreen - Resolved</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-perfect-online-shopping-picks-for-one-of-a-kind-box-packaging/"><u>2024 Approved  Perfect Online Shopping Picks for One-of-a-Kind Box Packaging</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixed-connectivity-glitches-in-cod-cold-war/"><u>[FIXED] Connectivity Glitches in CoD Cold War</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/immediate-flagging-of-insta-de-following-events-for-2024/"><u>Immediate Flagging of Insta De-Following Events for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/shedding-light-on-inscrutable-x-errors-plaguing-lol/"><u>Shedding Light on Inscrutable X Errors Plaguing LoL</u></a></li>
<li><a href="https://driver-install.techidaily.com/improved-connectivity-installing-logitech-hd-camera-c270-for-windows-1011/"><u>Improved Connectivity: Installing Logitech HD Camera (C270) for Windows 10/11</u></a></li>
<li><a href="https://network-issues.techidaily.com/competitive-edge-how-amd-graphics-drives-winning-performance/"><u>Competitive Edge: How AMD Graphics Drives Winning Performance</u></a></li>
</ul></div>
