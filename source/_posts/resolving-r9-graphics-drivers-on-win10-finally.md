---
title: Resolving R9 Graphics Drivers on Win10, Finally
date: 2024-07-12T00:08:44.405Z
updated: 2024-07-13T00:08:44.405Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: This Article Describes Resolving R9 Graphics Drivers on Win10, Finally
excerpt: This Article Describes Resolving R9 Graphics Drivers on Win10, Finally
keywords: Windows 10 Graphics Driver,R9 Graphics Drivers,Resolve Graphics Issues on Win10,Troubleshooting R9 Drivers for Windows 10,NVIDIA Graphics Driver Update on Win10,R9 Drivers Installation Guide,Win10 Graphics Driver Correction Techniques
thumbnail: https://thmb.techidaily.com/84dab43ab035d91cb56a4eae408b40758af9a9a2b096c95f61afee80ed15090c.jpg
---

## Resolving R9 Graphics Drivers on Win10, Finally

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
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-digital-migration-made-simple-top-5-file-transfer-routes-for-computers/"><u>[New] 2024 Approved  Digital Migration Made Simple  Top 5 File Transfer Routes for Computers</u></a></li>
<li><a href="https://network-issues.techidaily.com/mastering-the-mighty-spartans-move-set/"><u>Mastering the Mighty Spartan's Move Set</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-basic-knowledge-about-jazz-music-that-you-may-not-know-for-2024/"><u>New Basic Knowledge About Jazz Music That You May Not Know for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/the-ultimate-guide-to-fb-messenger-call-archiving-for-2024/"><u>The Ultimate Guide to FB Messenger Call Archiving for 2024</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/2024-approved-navigating-through-tiktoks-visual-communication-tools/"><u>2024 Approved  Navigating Through TikTok's Visual Communication Tools</u></a></li>
<li><a href="https://network-issues.techidaily.com/clearing-up-invisible-display-problems/"><u>Clearing Up Invisible Display Problems</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-elevating-your-channels-identity-with-titles/"><u>[New] 2024 Approved  Elevating Your Channel's Identity with Titles</u></a></li>
<li><a href="https://network-issues.techidaily.com/overwatch-displaying-error-missing-graphical-specs/"><u>Overwatch Displaying Error: Missing Graphical Specs</u></a></li>
<li><a href="https://network-issues.techidaily.com/overclock-issue-resolved/"><u>Overclock Issue Resolved</u></a></li>
<li><a href="https://network-issues.techidaily.com/troubleshooting-stuck-video-feature-on-asus-device/"><u>Troubleshooting Stuck Video Feature on Asus Device</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolution-settings-adjust-windows-11-screen-size/"><u>[RESOLUTION SETTINGS] Adjust Windows 11 Screen Size</u></a></li>
<li><a href="https://network-issues.techidaily.com/conquering-media-stutter-win11s-stream-success-story/"><u>Conquering Media Stutter: Win11's Stream Success Story</u></a></li>
<li><a href="https://network-issues.techidaily.com/1719974453129-accelerate-your-graphical-display-experience-update-intels-hd-graphics-to-windows-10/"><u>Accelerate Your Graphical Display Experience: Update Intel's HD Graphics to Windows 10.</u></a></li>
<li><a href="https://network-issues.techidaily.com/amd-graphics-drivers-radeon-hd-6950-version-20/"><u>AMD Graphics Drivers: Radeon HD 6950, Version 2.0</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcoming-graphics-driver22-hurdle/"><u>Overcoming Graphics DRIVER#22 Hurdle</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-streamline-game-saves-mastering-fbx-recording/"><u>[New] In 2024, Streamline Game Saves  Mastering FBX Recording</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-download-instagram-songs-a-comprehensive-tutorial/"><u>Updated In 2024, Download Instagram Songs A Comprehensive Tutorial</u></a></li>
<li><a href="https://network-issues.techidaily.com/geforce-experience-not-working-solved/"><u>GeForce Experience Not Working [SOLVED]</u></a></li>
<li><a href="https://network-issues.techidaily.com/enhance-video-quality-no-jitter/"><u>Enhance Video Quality: No Jitter</u></a></li>
<li><a href="https://network-issues.techidaily.com/repairing-saving-mechanism-for-display-configurations-on-windows/"><u>Repairing Saving Mechanism for Display Configurations on Windows</u></a></li>
<li><a href="https://network-issues.techidaily.com/amd-radeon-6950-new-windows-10-driver-release/"><u>AMD Radeon 6950: New Windows 10 Driver Release</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-the-art-of-condensation-editing-youtube-video-durations/"><u>[Updated] The Art of Condensation  Editing YouTube Video Durations</u></a></li>
<li><a href="https://network-issues.techidaily.com/blink-no-more-notebook-screen-stabilized/"><u>Blink No More: Notebook Screen Stabilized</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-boosting-roi-in-fb-ads-through-animation-techniques/"><u>[Updated] Boosting ROI in FB Ads Through Animation Techniques</u></a></li>
<li><a href="https://network-issues.techidaily.com/restoring-original-aspect-ratios-in-windows-11/"><u>Restoring Original Aspect Ratios in Windows 11</u></a></li>
<li><a href="https://network-issues.techidaily.com/rtx-3080-troubleshooting-resurrect-your-gaming-experience/"><u>RTX 3080 Troubleshooting: Resurrect Your Gaming Experience</u></a></li>
<li><a href="https://network-issues.techidaily.com/aligning-backups-fix-desktop-upside-down/"><u>Aligning Backups: Fix Desktop Upside Down</u></a></li>
<li><a href="https://network-issues.techidaily.com/win11-dark-mode-a-step-by-step-fix/"><u>Win11 Dark Mode: A Step-by-Step Fix</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2023s-best-screen-recorder-discover-with-camstudio/"><u>2023'S Best Screen Recorder? Discover with CamStudio</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-route-to-revenue-crafting-content-around-consumer-commodities/"><u>In 2024, The Route to Revenue  Crafting Content Around Consumer Commodities</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcoming-screen-jitter-on-windows-7/"><u>Overcoming Screen Jitter on Windows 7</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/in-2024-windows-10-webcam-recording-made-easy-top-10-software/"><u>In 2024, Windows 10 Webcam Recording Made Easy Top 10 Software</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-monitoring-and-alerts/"><u>[New] Monitoring and Alerts</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-essential-tips-for-successful-youtube-broadcasts-for-2024/"><u>[Updated] Essential Tips for Successful YouTube Broadcasts for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/unveiled-fix-for-msdn-error-nvidia-card-missing/"><u>Unveiled Fix for MSDN Error - NVIDIA Card Missing</u></a></li>
<li><a href="https://network-issues.techidaily.com/fix-inverted-screens-on-microsofts-windows-10/"><u>Fix: Inverted Screens on Microsoft's Windows 10</u></a></li>
<li><a href="https://network-issues.techidaily.com/screen-customization-saved-successfully/"><u>Screen Customization Saved Successfully</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-essential-tips-for-wirecast-live-streaming-to-youtube/"><u>[Updated] In 2024, Essential Tips for WireCast Live Streaming to Youtube</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-master-your-tiktok-vibe-explore-top-7-emojis-plus-elusive-signals/"><u>[Updated] Master Your TikTok Vibe - Explore Top 7 Emojis + Elusive Signals</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-niconico-stars-in-snapchat-moments/"><u>[New] 2024 Approved  Niconico Stars in Snapchat Moments</u></a></li>
<li><a href="https://network-issues.techidaily.com/recover-lost-display-settings-in-win10/"><u>Recover Lost Display Settings in Win10</u></a></li>
<li><a href="https://network-issues.techidaily.com/correct-video-glitches-on-monitors/"><u>Correct Video Glitches on Monitors</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-reviving-the-past-top-5-desktop-friendly-gb-emulation-software/"><u>[New] Reviving the Past  Top 5 Desktop-Friendly GB Emulation Software</u></a></li>
<li><a href="https://network-issues.techidaily.com/fix-sudden-screen-glitch-on-win11/"><u>Fix: Sudden Screen Glitch on Win11</u></a></li>
</ul></div>
