---
title: Successful Troubleshooting of R9 Drivers on Win10
date: 2024-11-21T05:14:17.887Z
updated: 2024-11-24T05:15:27.560Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: This Article Describes Successful Troubleshooting of R9 Drivers on Win10
excerpt: This Article Describes Successful Troubleshooting of R9 Drivers on Win10
keywords: Radeon Graphics Driver Fix,Windows 10 GPU Troubleshoot Guide,R9 Driver Compatibility Tips for Windows Users,Easy Steps to Resolve R9 Drivers Issue on Win10,Fix Radeon Driver Errors in Windows 10,How to Troubleshoot R9 Drivers in Windows 10,Overcoming R9 Graphics Driver Challenges on Win10
thumbnail: https://thmb.techidaily.com/3f659a3b4bb25cd415ed00e454404730b9869c867cd294c9e58180160b4e9b56.jpg
---

## Successful Troubleshooting of R9 Drivers on Win10

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
<li><a href="https://extra-information.techidaily.com/new-comprehensive-srt-breakdown-for-professionals/"><u>[New] Comprehensive SRT Breakdown for Professionals</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-streamlabs-vs-obs-which-livestream-tool-reigns-supreme/"><u>[New] In 2024, Streamlabs Vs. OBS Which Livestream Tool Reigns Supreme?</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-the-art-of-keeping-up-with-snapstreaks-for-2024/"><u>[New] The Art of Keeping Up With Snapstreaks for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-1-tiktok-videos-that-trended-on-twitter/"><u>[Updated] 2024 Approved 1 TikTok Videos That Trended on Twitter</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-become-a-pro-at-hosting-virtual-meetings-with-zoom-an-android-users-guide/"><u>2024 Approved Become a Pro at Hosting Virtual Meetings with Zoom An Android User's Guide</u></a></li>
<li><a href="https://network-issues.techidaily.com/how-to-fix-ethernet-not-working-issues-on-windows-11-and-7/"><u>How to Fix Ethernet Not Working Issues on Windows 11 & 7</u></a></li>
<li><a href="https://network-issues.techidaily.com/how-to-troubleshoot-and-resolve-wdf-related-blue-screen-errors-on-various-windows-versions/"><u>How to Troubleshoot and Resolve WDF-Related Blue Screen Errors on Various Windows Versions</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-forgot-your-apple-id-password-and-email-on-iphone-xr-heres-the-best-fixes-by-drfone-ios/"><u>In 2024, Forgot Your Apple ID Password and Email On iPhone XR? Heres the Best Fixes</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-vivo-y27-4g-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Snapchat Location Spoofer to Protect Your Privacy On Vivo Y27 4G? | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/increase-your-fps-top-6-optimization-strategies/"><u>Increase Your FPS: Top 6 Optimization Strategies</u></a></li>
<li><a href="https://tech-hub.techidaily.com/protecting-sensitive-data-a-guide-to-using-chatgpt-responsibly-in-the-workplace/"><u>Protecting Sensitive Data: A Guide to Using ChatGPT Responsibly in the Workplace</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolve-the-gtx-code-43-issue-in-windows-10-complete-guide/"><u>Resolve the GTX #code-43 Issue in Windows 10 – Complete Guide</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolved-fixing-connectivity-issues-with-zoom-on-an-intermittent-internet/"><u>Resolved: Fixing Connectivity Issues with Zoom on an Intermittent Internet</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolved-overcoming-initialization-issues-with-the-graphics-system/"><u>Resolved: Overcoming Initialization Issues with the Graphics System</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolved-troubleshooting-steps-when-your-amd-gpu-is-unrecognized-in-windows-10/"><u>Resolved: Troubleshooting Steps When Your AMD GPU Is Unrecognized in Windows 10</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/w7c5EHp-GDw?si=UTw7lZR0wTmRjp8W&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

