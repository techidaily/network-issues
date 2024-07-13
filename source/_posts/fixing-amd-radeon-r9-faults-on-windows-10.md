---
title: Fixing AMD Radeon R9 Faults on Windows 10
date: 2024-07-12T00:32:32.899Z
updated: 2024-07-13T00:32:32.899Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: This Article Describes Fixing AMD Radeon R9 Faults on Windows 10
excerpt: This Article Describes Fixing AMD Radeon R9 Faults on Windows 10
keywords: Fix AMD Radeon R9 Errors Windows 10,Troubleshoot AMD Graphics Card Issues in Windows 10,Resolve AMD Radeon Faults on Windows Operating System,Fix Common Problems with AMD Radeon on Windows 10,Remedy AMD Radeon Compatibility Errors in Windows OS,Repair AMD Graphics Card Glitches on Windows 10,Solve AMD Radeon Hardware Faults on Windows 10
thumbnail: https://thmb.techidaily.com/7dc3990d7127eb4697b62478b58e508110f3846153c4979b3c9a42816701b4b9.jpg
---

## Fixing AMD Radeon R9 Faults on Windows 10

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
<li><a href="https://network-issues.techidaily.com/gpu-troubleshooting-stop-win-minecraft-freezes/"><u>GPU Troubleshooting: Stop Win Minecraft Freezes</u></a></li>
<li><a href="https://network-issues.techidaily.com/nvidia-intel-r-switchable-graphics-card-problem-on-windows-11-solved/"><u>NVIDIA/ Intel (R) Switchable Graphics Card Problem on Windows 11 [SOLVED]</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-how-to-record-gameplay-on-ps4/"><u>2024 Approved  How to Record Gameplay on PS4</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-enhancing-storytelling-with-jump-cuts-technique/"><u>[New] Enhancing Storytelling with Jump Cuts Technique</u></a></li>
<li><a href="https://network-issues.techidaily.com/clarifying-concepts-behind-4k-extraordinary-definition/"><u>Clarifying Concepts Behind 4K Extraordinary Definition</u></a></li>
<li><a href="https://network-issues.techidaily.com/gained-entry-to-gpu-preferences-panel/"><u>[Gained] Entry to GPU Preferences Panel</u></a></li>
<li><a href="https://network-issues.techidaily.com/hardware-issue-code-43-cleared/"><u>Hardware Issue Code 43 Cleared</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolving-conflicts-between-nvidia-and-windows-11/"><u>Resolving Conflicts Between Nvidia and Windows 11</u></a></li>
<li><a href="https://network-issues.techidaily.com/overwatch-incompatibility-fixed-graphics-update-successful/"><u>Overwatch Incompatibility Fixed: Graphics Update Successful</u></a></li>
<li><a href="https://network-issues.techidaily.com/guiding-gpu-fan-repair-process/"><u>Guiding GPU Fan Repair Process</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/2024-approved-the-best-online-photo-background-remover-tools-for-free/"><u>2024 Approved The Best Online Photo Background Remover Tools for Free</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/pokemon-go-cooldown-chart-on-apple-iphone-se-drfone-by-drfone-virtual-ios/"><u>Pokémon Go Cooldown Chart On Apple iPhone SE | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/solutions-for-win7-screen-pulsation-issue/"><u>Solutions for Win7 Screen Pulsation Issue</u></a></li>
<li><a href="https://network-issues.techidaily.com/troubleshooting-c1900101-error-for-win10/"><u>Troubleshooting C1900101 Error for Win10</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-dissecting-the-hidden-mechanics-behind-youtubes-popularity-index/"><u>[New] 2024 Approved  Dissecting the Hidden Mechanics Behind YouTube's Popularity Index</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/professional-streams-from-obs-to-insta-for-2024/"><u>Professional Streams From OBS to Insta for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-the-art-of-targeting-optimizing-ad-reach-on-snap/"><u>[Updated] The Art of Targeting  Optimizing Ad Reach on Snap</u></a></li>
<li><a href="https://network-issues.techidaily.com/rectifying-reversed-computer-screen-angle/"><u>Rectifying Reversed Computer Screen Angle</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcoming-windows-11-window-width-woes/"><u>Overcoming Windows 11 Window Width Woes</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixing-non-fullscreen-windows-11-on-monitors/"><u>Fixing Non-Fullscreen Windows 11 on Monitors</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixing-windows-10s-critical-c1900101-error/"><u>Fixing Windows 10'S Critical C1900101 Error</u></a></li>
<li><a href="https://network-issues.techidaily.com/fix-windows-11-screen-post-update-fix/"><u>Fix Windows 11 Screen Post Update Fix</u></a></li>
<li><a href="https://network-issues.techidaily.com/graphical-gone-wrong-monster-hunts-fix-successful/"><u>Graphical Gone Wrong? Monster Hunt's Fix Successful!</u></a></li>
<li><a href="https://network-issues.techidaily.com/windows-8-securely-accessing-safe-mode-and-removing-gpu-drivers/"><u>Windows 8: Securely Accessing Safe Mode & Removing GPU Drivers</u></a></li>
<li><a href="https://network-issues.techidaily.com/conquering-youtubes-unwanted-green-screen-effects/"><u>Conquering Youtube's Unwanted Green Screen Effects</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixing-video-output-glitches-without-hiring-help/"><u>Fixing Video Output Glitches Without Hiring Help</u></a></li>
<li><a href="https://network-issues.techidaily.com/the-essence-and-impact-of-4k-super-hd-imaging/"><u>The Essence and Impact of 4K Super HD Imaging</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-exploring-vivas-video-experience/"><u>[Updated] Exploring Viva's Video Experience</u></a></li>
<li><a href="https://network-issues.techidaily.com/achieving-compatibility-perfection-win10-plus-nvidia/"><u>Achieving Compatibility Perfection: Win10 + Nvidia</u></a></li>
<li><a href="https://network-issues.techidaily.com/correcting-dim-laptop-screen-problem-in-lenovo/"><u>Correcting Dim Laptop Screen Problem in Lenovo</u></a></li>
<li><a href="https://network-issues.techidaily.com/mastering-uninterrupted-media-playback-post-win11-update/"><u>Mastering Uninterrupted Media Playback Post Win11 Update</u></a></li>
<li><a href="https://network-issues.techidaily.com/adjusting-vision-quality-in-windows-11/"><u>Adjusting Vision Quality in Windows 11</u></a></li>
<li><a href="https://network-issues.techidaily.com/addressing-c1900101-errors-when-setting-up-new-windows-11/"><u>Addressing C1900101 Errors When Setting Up New Windows 11</u></a></li>
<li><a href="https://network-issues.techidaily.com/tips-and-tricks-eliminating-flickering-on-acer-devices/"><u>Tips & Tricks: Eliminating Flickering on Acer Devices</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-to-use-pokemon-go-joystick-on-vivo-s18-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Pokemon Go Joystick on Vivo S18? | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolved-error-12-monster-quest-restored/"><u>Resolved Error 12 - Monster Quest Restored</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-inexpensive-quality-camera-solutions/"><u>[New] Inexpensive Quality Camera Solutions</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-mastering-the-art-of-online-presence-with-innovative-tiktok-names-for-2024/"><u>[Updated] Mastering the Art of Online Presence with Innovative TikTok Names for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/new-improved-graphics-driver-for-win10s-nvidia-210/"><u>New Improved Graphics Driver for Win10's Nvidia 210</u></a></li>
<li><a href="https://network-issues.techidaily.com/addressing-stuttery-screens-on-windows-7/"><u>Addressing Stuttery Screens on Windows 7</u></a></li>
<li><a href="https://network-issues.techidaily.com/settling-the-riddle-peculiar-x-error-in-lol-unraveled/"><u>Settling the Riddle: Peculiar X Error in LoL Unraveled</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-no-cost-windowsmac-video-software-top-picks/"><u>[New] No-Cost Windows/Mac Video Software, Top Picks</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/in-2024-from-footage-to-film-the-ultimate-free-gopro-hd-video-editing-guide/"><u>In 2024, From Footage to Film The Ultimate Free GoPro HD Video Editing Guide</u></a></li>
<li><a href="https://network-issues.techidaily.com/windows-10-detects-adapter-whats-next/"><u>Windows 10 Detects Adapter: What's Next?</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-maximizing-soundcloud-music-tips-for-mp3-conversion/"><u>2024 Approved Maximizing Soundcloud Music Tips for MP3 Conversion</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-2024-approved-the-art-of-cartoonization-a-comprehensive-guide-to-video-conversion/"><u>Updated 2024 Approved The Art of Cartoonization A Comprehensive Guide to Video Conversion</u></a></li>
<li><a href="https://fake-location.techidaily.com/is-pgsharp-legal-when-you-are-playing-pokemon-on-vivo-s18-pro-drfone-by-drfone-virtual-android/"><u>Is pgsharp legal when you are playing pokemon On Vivo S18 Pro? | Dr.fone</u></a></li>
<li><a href="https://facebook.techidaily.com/altering-facebook-pages-avatar-and-title/"><u>Altering Facebook Page's Avatar & Title</u></a></li>
<li><a href="https://network-issues.techidaily.com/amd-troubleshoot-driver-detection-errors-cleared-in-win10/"><u>AMD Troubleshoot: Driver Detection Errors Cleared in Win10</u></a></li>
<li><a href="https://network-issues.techidaily.com/the-black-screen-banished-from-lenovo-panels/"><u>The Black Screen Banished From Lenovo Panels</u></a></li>
<li><a href="https://network-issues.techidaily.com/fix-to-w11-screen-refresh-issue/"><u>Fix to W11 Screen Refresh Issue</u></a></li>
<li><a href="https://network-issues.techidaily.com/lenovo-screen-ignored-repair-success-reported/"><u>Lenovo Screen Ignored: Repair Success Reported</u></a></li>
<li><a href="https://network-issues.techidaily.com/removing-intrusive-windows-flash-glitches/"><u>Removing Intrusive Windows Flash Glitches</u></a></li>
<li><a href="https://network-issues.techidaily.com/navigating-wows-issue-519-with-ease/"><u>Navigating WoW's Issue #519 With Ease</u></a></li>
<li><a href="https://network-issues.techidaily.com/corrected-graphics-issue-driver-reset-successful/"><u>Corrected Graphics Issue: Driver Reset Successful</u></a></li>
</ul></div>
