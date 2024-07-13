---
title: Eliminating R9 Driver Glitches on Windows 10
date: 2024-07-12T00:47:57.102Z
updated: 2024-07-13T00:47:57.102Z
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
<li><a href="https://network-issues.techidaily.com/enhanced-visuals-with-geforce-210-driver-on-windows-10/"><u>Enhanced Visuals with GeForce 210 Driver on Windows 10</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-best-ways-on-how-to-unlockbypassswiperemove-xiaomi-redmi-note-12r-fingerprint-lock-by-drfone-android/"><u>In 2024, Best Ways on How to Unlock/Bypass/Swipe/Remove Xiaomi Redmi Note 12R Fingerprint Lock</u></a></li>
<li><a href="https://network-issues.techidaily.com/restored-fullscreen-functionality-on-win11-monitors/"><u>Restored Fullscreen Functionality on Win11 Monitors</u></a></li>
<li><a href="https://network-issues.techidaily.com/steps-for-corrective-actions-with-undetected-gpus/"><u>Steps for Corrective Actions with Undetected GPUs</u></a></li>
<li><a href="https://extra-information.techidaily.com/breaking-down-the-top-ae-title-styles/"><u>Breaking Down the Top AE Title Styles</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixing-the-flaky-wi-fi-flow/"><u>Fixing the Flaky Wi-Fi Flow</u></a></li>
<li><a href="https://network-issues.techidaily.com/1719974863177-enhance-your-systems-graphical-power-with-a-quick-intel-graphics-3000-update-on-w10/"><u>Enhance Your System's Graphical Power with a Quick Intel Graphics 3000 Update on W10</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcome-flashy-windows-11-monitor/"><u>Overcome Flashy Windows 11 Monitor</u></a></li>
<li><a href="https://extra-tips.techidaily.com/aerial-imaging-warfare-djis-pro-vs-gopro-k20-for-2024/"><u>Aerial Imaging Warfare  DJI's Pro Vs GoPro K20 for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-eliminating-soundtracks-in-contemporary-mkv-video-files-mkv-2023-for-2024/"><u>New Eliminating Soundtracks in Contemporary MKV Video Files (MKV-2023) for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/hardware-preferences-retained-post-update/"><u>Hardware Preferences Retained Post-Update</u></a></li>
<li><a href="https://network-issues.techidaily.com/mastering-the-art-of-intel-drivers-refresh-in-windows-7-os/"><u>Mastering the Art of Intel Drivers Refresh in Windows 7 OS</u></a></li>
<li><a href="https://network-issues.techidaily.com/unveiling-hidden-black-screens/"><u>Unveiling Hidden Black Screens</u></a></li>
<li><a href="https://network-issues.techidaily.com/troubleshooting-steps-to-resolve-c1900101-in-windows-11/"><u>Troubleshooting Steps to Resolve C1900101 in Windows 11</u></a></li>
<li><a href="https://network-issues.techidaily.com/syncing-intel-and-nvidia-gpus-problem-resolved-on-win11/"><u>Syncing Intel & Nvidia GPUs - Problem Resolved on Win11</u></a></li>
<li><a href="https://network-issues.techidaily.com/blackout-blues-display-dread/"><u>Blackout Blues: Display Dread</u></a></li>
<li><a href="https://network-issues.techidaily.com/ending-intermittent-windows-display-flashes/"><u>Ending Intermittent Windows Display Flashes</u></a></li>
<li><a href="https://network-issues.techidaily.com/graphics-recovered-after-driver-malfunction-fix/"><u>Graphics Recovered After Driver Malfunction Fix</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-transform-your-podcasts-identity-with-ai-name-makers/"><u>[Updated] Transform Your Podcast's Identity with AI Name Makers</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-refine-your-footage-how-to-stabilize-videos-like-a-pro-in-ae/"><u>2024 Approved Refine Your Footage How to Stabilize Videos Like a Pro in AE</u></a></li>
<li><a href="https://network-issues.techidaily.com/streamline-your-windows-experience-via-intel-graphic-update/"><u>Streamline Your Windows Experience via Intel Graphic Update</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-do-i-stop-someone-from-tracking-my-nokia-c300-drfone-by-drfone-virtual-android/"><u>How Do I Stop Someone From Tracking My Nokia C300? | Dr.fone</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024s-premier-voice-transformation-tools/"><u>Updated 2024S Premier Voice Transformation Tools</u></a></li>
<li><a href="https://network-issues.techidaily.com/countering-hp-lcd-backlight-variability/"><u>Countering HP LCD Backlight Variability</u></a></li>
<li><a href="https://network-issues.techidaily.com/troubleshooting-persistent-asus-webcam-failures/"><u>Troubleshooting Persistent Asus Webcam Failures</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-jokesterjigsaw-toolkit/"><u>In 2024, JokesterJigsaw Toolkit</u></a></li>
<li><a href="https://network-issues.techidaily.com/latest-amd-radeon-hd-6950-drivers-for-win10/"><u>Latest AMD Radeon HD 6950 Drivers for Win10</u></a></li>
<li><a href="https://network-issues.techidaily.com/brightening-blacked-out-win10-post-release/"><u>Brightening Blacked-Out Win10 Post Release</u></a></li>
<li><a href="https://network-issues.techidaily.com/simple-repair-steps-off-gaming-setup-graphics-card/"><u>Simple Repair Steps: Off Gaming Setup Graphics Card</u></a></li>
<li><a href="https://network-issues.techidaily.com/windows-10-resolution-adjustment-problem-no-longer-exists/"><u>Windows 10 Resolution Adjustment - Problem No Longer Exists</u></a></li>
<li><a href="https://network-issues.techidaily.com/seamless-functioning-nvidia-card-on-win11/"><u>Seamless Functioning: Nvidia Card on Win11</u></a></li>
<li><a href="https://network-issues.techidaily.com/1719974361533-fix-laptop-screen-wont-turn-on-issue/"><u>Fix Laptop Screen Won't Turn On Issue</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-best-choice-for-live-video-harvesting/"><u>[New] Best Choice for Live Video Harvesting</u></a></li>
<li><a href="https://network-issues.techidaily.com/updated-graphics-hardware-now-supports-overwatch/"><u>Updated Graphics Hardware Now Supports Overwatch</u></a></li>
<li><a href="https://network-issues.techidaily.com/amd-enhances-radeon-hd-6950-graphics-for-windows-11-with-new-driver-rollout/"><u>AMD Enhances Radeon HD 6950 Graphics for Windows 11 with New Driver Rollout</u></a></li>
<li><a href="https://network-issues.techidaily.com/the-next-step-windows-10-enhancements-with-amds-radeon-hd-6950-drivers/"><u>The Next Step: Windows 10 Enhancements with AMD's Radeon HD 6950 Drivers</u></a></li>
<li><a href="https://network-issues.techidaily.com/elucited-explanation-of-4k-super-hd-resolution/"><u>Elucited Explanation of 4K Super HD Resolution</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolving-backward-image-flip-for-windows-10-users/"><u>Resolving Backward Image Flip for Windows 10 Users</u></a></li>
<li><a href="https://network-issues.techidaily.com/stabilize-windows-11-screens-no-more-stretching/"><u>Stabilize Windows 11 Screens, No More Stretching</u></a></li>
<li><a href="https://network-issues.techidaily.com/ending-blurry-display-in-win11/"><u>Ending Blurry Display in Win11</u></a></li>
<li><a href="https://network-issues.techidaily.com/ending-bdr-issues-on-ws-11-ws-10-ws-8-and-ws-7-windows/"><u>Ending BDR Issues on WS-11, WS-10, WS-8 & WS-7 Windows</u></a></li>
<li><a href="https://network-issues.techidaily.com/master-the-art-of-display-latency-reduction/"><u>Master the Art of Display Latency Reduction</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-change-location-on-facebook-marketplace-for-oppo-reno-10-5g-drfone-by-drfone-virtual-android/"><u>3 Ways to Change Location on Facebook Marketplace for Oppo Reno 10 5G | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-artistic-angles-a-selection-of-hot-snapchat-augments/"><u>[Updated] 2024 Approved  Artistic Angles  A Selection of Hot Snapchat Augments</u></a></li>
<li><a href="https://network-issues.techidaily.com/lenovo-monitor-troubleshooting-no-light/"><u>Lenovo Monitor: Troubleshooting No-Light</u></a></li>
<li><a href="https://network-issues.techidaily.com/addressed-expanded-screen-size-issues-for-windows/"><u>Addressed Expanded Screen Size Issues for Windows</u></a></li>
<li><a href="https://network-issues.techidaily.com/issue-resolved-monitor-shows-portion-not-all-windows-windows-10/"><u>Issue Resolved: Monitor Shows Portion, Not All Windows (Windows 10)</u></a></li>
</ul></div>
