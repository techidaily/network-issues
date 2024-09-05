---
title: "Overcoming Display Driver Problems: R9 & Win10"
date: 2024-09-04T12:01:58.804Z
updated: 2024-09-05T12:01:58.804Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: "This Article Describes Overcoming Display Driver Problems: R9 & Win10"
excerpt: "This Article Describes Overcoming Display Driver Problems: R9 & Win10"
keywords: Radeon HD 7990 Troubleshooting,Win10 Display Driver Fix,Display Adapter Error Resolution,Graphics Driver Update Guide,AirPort Display Drivers Compatibility R9,Nvidia GeForce 7900X2 Display Fixes,Radeon HD Graphics Overcoming Problems
thumbnail: https://thmb.techidaily.com/0a8efd832e4ff850ed2946c105917f658a3e5ec7d74782a26831b6d30a49981c.jpg
---

## Overcoming Display Driver Problems: R9 & Win10

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
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-elevate-your-gaming-with-fbx-capture-pro/"><u>[New] 2024 Approved  Elevate Your Gaming with FBX Capture Pro</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-full-guide-to-creating-minecraft-mashups/"><u>[New] In 2024, Full Guide to Creating Minecraft Mashups</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-insiders-guide-to-top-ranking-titles/"><u>[New] The Insider's Guide to Top-Ranking Titles</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-top-10-secrets-for-successful-youtube-music-reaction-videos/"><u>[New] Top 10 Secrets for Successful YouTube Music Reaction Videos</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-hone-your-skills-how-to-seamlessly-post-videos-to-instagram-via-desktop-for-2024/"><u>[Updated] Hone Your Skills  How to Seamlessly Post Videos to Instagram via Desktop for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-essential-screen-recording-tips-for-windows-8-pros/"><u>[Updated] In 2024, Essential Screen Recording Tips for Windows 8 Pros</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-portraying-paradoxes-with-teleportation-cgi/"><u>2024 Approved  Portraying Paradoxes with Teleportation CGI</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-record-android-internal-voice-4-easy-rootless-techniques/"><u>2024 Approved  Record Android Internal Voice  4 Easy, Rootless Techniques</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-artistic-zoomers-handbook-a-filters-journey/"><u>2024 Approved  The Artistic Zoomer's Handbook  A Filters Journey</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-unleash-your-potential-top-6-head-mounted-cameras-by-gopro/"><u>2024 Approved  Unleash Your Potential  Top 6 Head-Mounted Cameras by GoPro</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/2024-approved-youtube-shorts-earnings-guide-must-knows-and-future-potential/"><u>2024 Approved  Youtube Shorts Earnings Guide  Must-Knows & Future Potential</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/all-you-need-to-know-about-mega-greninja-for-oppo-reno-9a-drfone-by-drfone-virtual-android/"><u>All You Need To Know About Mega Greninja For Oppo Reno 9A | Dr.fone</u></a></li>
<li><a href="https://fox-http.techidaily.com/complete-insight-into-ricoh-theta-s-camera-for-2024/"><u>Complete Insight Into Ricoh Theta S Camera for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/dells-display-disorder-resolved-today/"><u>Dell's Display Disorder: Resolved Today</u></a></li>
<li><a href="https://network-issues.techidaily.com/disable-lcd-flicker-effects/"><u>Disable LCD Flicker Effects</u></a></li>
<li><a href="https://network-issues.techidaily.com/display-driver-fixed-error-43/"><u>Display Driver Fixed Error 43</u></a></li>
<li><a href="https://network-issues.techidaily.com/error-22-in-gpu-drivers-addressed/"><u>Error 22 in GPU Drivers Addressed</u></a></li>
<li><a href="https://tech-revival.techidaily.com/exploring-drm-insights-into-what-it-is-and-strategies-for-bypassing-dvd-content-restrictions/"><u>Exploring DRM: Insights Into What It Is & Strategies for Bypassing DVD Content Restrictions</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixed-problem-windows-10-displaying-only-partial-windows/"><u>Fixed Problem: Windows 10 Displaying Only Partial Windows</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/frp-hijacker-by-hagard-download-and-bypass-your-realme-10t-5g-frp-locks-by-drfone-android/"><u>FRP Hijacker by Hagard Download and Bypass your Realme 10T 5G FRP Locks</u></a></li>
<li><a href="https://network-issues.techidaily.com/graphics-void-card-search-error/"><u>Graphics Void: Card Search Error</u></a></li>
<li><a href="https://vp-tips.techidaily.com/how-to-fix-dvd-playback-problems-when-watching-movies-on-desktop-and-laptops/"><u>How to Fix DVD Playback Problems When Watching Movies on Desktop and Laptops</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-aesthetic-assembly-android-and-ios-video-sets-for-insta/"><u>In 2024, Aesthetic Assembly  Android & iOS Video Sets for Insta</u></a></li>
<li><a href="https://network-issues.techidaily.com/installing-new-wi-fi-card-on-pcs-a-step-by-step-guide/"><u>Installing New Wi-Fi Card on PCs: A Step by Step Guide</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/introductory-insights-crafting-listener-love-for-2024/"><u>Introductory Insights  Crafting Listener-Love for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/kratos-kinks-cured-for-combat/"><u>Kratos Kinks Cured for Combat</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/making-sense-of-blu-ray-tech-buy-or-skip/"><u>Making Sense of Blu-Ray Tech: Buy or Skip?</u></a></li>
<li><a href="https://network-issues.techidaily.com/mastering-driver-matchup-in-windows-10/"><u>Mastering Driver Matchup in Windows 10</u></a></li>
<li><a href="https://network-issues.techidaily.com/navigating-amd-radeon-r9-troubleshooting-in-windows-11/"><u>Navigating AMD Radeon R9 Troubleshooting in Windows 11</u></a></li>
<li><a href="https://network-issues.techidaily.com/navigating-through-youtubes-unwanted-green-mistakes/"><u>Navigating Through YouTube's Unwanted Green Mistakes</u></a></li>
<li><a href="https://network-issues.techidaily.com/nvidia-fixed-system-paused-over-device-error/"><u>NVIDIA Fixed: System Paused Over Device Error</u></a></li>
<li><a href="https://network-issues.techidaily.com/nvidia-geforce-210-drivers-update-for-windows-10/"><u>NVIDIA GeForce 210 Drivers Update for Windows 10</u></a></li>
<li><a href="https://games-able.techidaily.com/paving-the-way-for-interactive-device-management-barrier-method-revealed/"><u>Paving the Way For Interactive Device Management: Barrier Method Revealed</u></a></li>
<li><a href="https://network-issues.techidaily.com/pc-roblox-performance-slowdown/"><u>PC: Roblox Performance Slowdown</u></a></li>
<li><a href="https://network-issues.techidaily.com/performance-tuned-no-anomalies/"><u>Performance Tuned, No Anomalies</u></a></li>
<li><a href="https://network-issues.techidaily.com/quick-fix-for-flickering-win11-monitor/"><u>Quick Fix for Flickering Win11 Monitor</u></a></li>
<li><a href="https://network-issues.techidaily.com/quick-resolution-to-amd-woes/"><u>Quick Resolution to AMD Woes</u></a></li>
<li><a href="https://network-issues.techidaily.com/realigning-windows-10-screens-for-correct-view/"><u>Realigning Windows 10 Screens for Correct View</u></a></li>
<li><a href="https://network-issues.techidaily.com/reconnecting-disconnected-internal-cameras-on-asus/"><u>Reconnecting Disconnected Internal Cameras on Asus</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolving-critical-error-code-c1900101-in-win10/"><u>Resolving Critical Error: Code C1900101 in Win10</u></a></li>
<li><a href="https://network-issues.techidaily.com/solve-video-stuttering-issues-quickly-and-easily/"><u>Solve Video Stuttering Issues. Quickly & Easily!</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-fixes-to-correct-mscorwksdll-not-found-bugs-on-your-pc/"><u>Step-by-Step Fixes to Correct 'Mscorwks.dll Not Found' Bugs on Your PC</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-solutions-for-windows-10-users-experiencing-bluetooth-driver-woes/"><u>Step-by-Step Solutions for Windows 10 Users Experiencing Bluetooth Driver Woes</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-essential-guide-to-launching-a-zoom-session-on-android/"><u>The Essential Guide to Launching a Zoom Session on Android</u></a></li>
<li><a href="https://network-issues.techidaily.com/tighten-monitor-border-clarity/"><u>Tighten Monitor Border Clarity</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshoot-and-fix-nvidia-shadowplay-recording-problems-under-windows-os/"><u>Troubleshoot & Fix Nvidia ShadowPlay Recording Problems Under Windows OS</u></a></li>
<li><a href="https://fox-that.techidaily.com/what-you-should-do-when-the-proximity-alert-system-in-your-iphone-stops-working/"><u>What You Should Do When the Proximity Alert System in Your iPhone Stops Working</u></a></li>
<li><a href="https://network-issues.techidaily.com/wifi-warrior-combatting-slow-windows-1110/"><u>WiFi Warrior: Combatting Slow Windows 11/10</u></a></li>
<li><a href="https://network-issues.techidaily.com/win-graphics-fix-solidarity-against-minecraft-crashes/"><u>Win-Graphics Fix: Solidarity Against Minecraft Crashes</u></a></li>
<li><a href="https://network-issues.techidaily.com/1719974781358-win11-hybrid-graphics-bug-now-solved/"><u>Win11 Hybrid Graphics Bug: Now Solved</u></a></li>
<li><a href="https://network-issues.techidaily.com/winning-the-latency-battle-in-windows-networks/"><u>Winning the Latency Battle in Windows Networks</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528703/16446" target="_top" id="1528703">
  <img src="//a.impactradius-go.com/display-ad/16446-1528703" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528703/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->