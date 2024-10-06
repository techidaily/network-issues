---
title: Troubleshooting R9 Graphics Issues for Windows 10 Users
date: 2024-10-05T18:50:02.070Z
updated: 2024-10-06T17:07:27.049Z
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
<li><a href="https://youtube-zero.techidaily.com/ed-2024-approved-unleash-your-creative-vision-with-youtubes-filmmaking-courses/"><u>[Updated] 2024 Approved Unleash Your Creative Vision with YouTube's Filmmaking Courses</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-integrated-sound-and-vision-workspace-for-2024/"><u>[Updated] Integrated Sound & Vision Workspace for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/adapt-screen-size-without-losing-resolution-on-win11/"><u>Adapt Screen Size without Losing Resolution on Win11</u></a></li>
<li><a href="https://network-issues.techidaily.com/boosting-performance-windows-10-gains-from-amds-hd-6950-update-v20/"><u>Boosting Performance: Windows 10 Gains From AMD's HD 6950 Update V2.0</u></a></li>
<li><a href="https://tech-hub.techidaily.com/decoding-googles-ai-vision-an-exploration-into-geminis-mission-and-scope/"><u>Decoding Google's AI Vision - An Exploration Into Gemini’s Mission and Scope</u></a></li>
<li><a href="https://network-issues.techidaily.com/decoding-the-purpose-of-4k-high-definition/"><u>Decoding the Purpose of 4K High-Definition</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/digital-masterpieces-by-rob-johnson-the-exclusive-art-of-digiarty/"><u>Digital Masterpieces by Rob Johnson - The Exclusive Art of Digiarty</u></a></li>
<li><a href="https://network-issues.techidaily.com/directcompute-unavailable-fix-applied/"><u>DirectCompute Unavailable: Fix Applied</u></a></li>
<li><a href="https://network-issues.techidaily.com/eliminating-windows-10s-c1900101-problems/"><u>Eliminating Windows 10'S C1900101 Problems</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-lock-apps-on-vivo-t2x-5g-to-protect-your-individual-information-by-drfone-android/"><u>How to Lock Apps on Vivo T2x 5G to Protect Your Individual Information</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/24-tutorial-on-youtube-thumbnail-extraction-for-all-os-enthusiasts/"><u>In 2024, Tutorial on YouTube Thumbnail Extraction for All OS Enthusiasts</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/-ways-to-boost-your-video-watch-count-responsibly/"><u>Legal Ways to Boost Your Video Watch Count Responsibly</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/nail-art-masterclass-series-for-2024/"><u>Nail Art Masterclass Series for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-ways-to-recover-deleted-files-from-vivo-s17e-by-fonelab-android-recover-data/"><u>Possible ways to recover deleted files from Vivo S17e</u></a></li>
<li><a href="https://network-issues.techidaily.com/screenstopper-on-graphicswindow-os-works-awaiting-confirmation/"><u>ScreenStopper on GraphicsWindow OS (Works Awaiting Confirmation)</u></a></li>
<li><a href="https://network-issues.techidaily.com/win-10-fixed-screen-size-adjustment-hurdle-successfully/"><u>Win 10: Fixed Screen Size Adjustment Hurdle Successfully</u></a></li>
<li><a href="https://network-issues.techidaily.com/windows-11-wi-fi-gone-missing-heres-help/"><u>Windows 11 Wi-Fi Gone Missing? Here's Help</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148646/16836" target="_top" id="2148646">
  <img src="//a.impactradius-go.com/display-ad/16836-2148646" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148646/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

