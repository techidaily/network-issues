---
title: Fixing Radeon R9 Drivers on New Windows 11
date: 2024-07-12T00:20:49.743Z
updated: 2024-07-13T00:20:49.743Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: This Article Describes Fixing Radeon R9 Drivers on New Windows 11
excerpt: This Article Describes Fixing Radeon R9 Drivers on New Windows 11
keywords: Radeon R9 Driver Update,Windows 11 GPU Drivers,New Windows Driver Installation,Radeon Drivers Compatibility Windows 11,AMD Radeon Driver Fix,Windows 11 Graphics Drivers Update Guide,Radeon R9 Troubleshooting Steps
thumbnail: https://thmb.techidaily.com/d568e250a0c9cf38c4b89f922cd02103ab4f1762aadda7b19c3a1266ed366a54.jpg
---

## Fixing Radeon R9 Drivers on New Windows 11

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
<li><a href="https://fox-http.techidaily.com/new-in-2024-from-filters-to-fun-factors-maximizing-iphones-gif-capabilities/"><u>[New] In 2024, From Filters to Fun Factors  Maximizing iPhone's GIF Capabilities</u></a></li>
<li><a href="https://network-issues.techidaily.com/win11-upgrade-new-amd-hd-6950-graphics-driver-rollout/"><u>Win11 Upgrade: New AMD HD 6950 Graphics Driver Rollout</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-gastronomic-adventures-await-with-these-15-must-watch-food-challenges-on-tiktok/"><u>In 2024, Gastronomic Adventures Await with These 15 Must-Watch Food Challenges on TikTok</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-through-virtual-lenses-a-historical-view/"><u>[Updated] Through Virtual Lenses  A Historical View</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/mac-alternatives-to-windows-movie-maker-top-picks/"><u>Mac Alternatives to Windows Movie Maker Top Picks</u></a></li>
<li><a href="https://network-issues.techidaily.com/banishing-buzzing-visuals-from-win7/"><u>Banishing Buzzing Visuals From Win7</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-how-to-layer-melodies-into-instagram-media-content/"><u>[New] How to Layer Melodies Into Instagram Media Content</u></a></li>
<li><a href="https://network-issues.techidaily.com/missing-visual-hardware-solve-for-nvidia-gpu-lack-of-visibility/"><u>Missing Visual Hardware: Solve for NVIDIA GPU Lack of Visibility</u></a></li>
<li><a href="https://network-issues.techidaily.com/eliminating-hp-lcd-flashes/"><u>Eliminating HP LCD Flashes</u></a></li>
<li><a href="https://network-issues.techidaily.com/success-story-overcoming-amds-windows-10-driver-load-hurdle/"><u>Success Story: Overcoming AMD's Windows 10 Driver Load Hurdle</u></a></li>
<li><a href="https://network-issues.techidaily.com/restore-cursor-functionality-on-black-screen/"><u>Restore Cursor Functionality on Black Screen</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixed-lost-network-card-on-windows-10-desktop/"><u>[FIXED] Lost Network Card on Windows 10 Desktop</u></a></li>
<li><a href="https://network-issues.techidaily.com/improve-gameplay-speed-in-virtual-construction/"><u>Improve Gameplay Speed in Virtual Construction</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-essential-steps-to-designing-exceptional-youtube-thumbnails/"><u>In 2024, Essential Steps to Designing Exceptional YouTube Thumbnails</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-youcamsimplified-quickguidetorecordings/"><u>[Updated] YouCamSimplified  QuickGuideToRecordings</u></a></li>
<li><a href="https://network-issues.techidaily.com/non-responsive-lenovo-touchscreen-resolved/"><u>Non-Responsive Lenovo Touchscreen - Resolved</u></a></li>
<li><a href="https://network-issues.techidaily.com/tackling-graphics-conflict-intel-and-nvidia-fix-on-windows-10-systems/"><u>Tackling Graphics Conflict: Intel & NVIDIA Fix on Windows 10 Systems</u></a></li>
<li><a href="https://network-issues.techidaily.com/1719974137317-install-latest-intel-hd-graphics-3000-on-windows-10-swiftly/"><u>Install Latest Intel HD Graphics 3000 on Windows 10 Swiftly</u></a></li>
<li><a href="https://android-location-track.techidaily.com/5-ways-to-track-vivo-y36i-without-app-drfone-by-drfone-virtual-android/"><u>5 Ways to Track Vivo Y36i without App | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/unveil-the-future-of-graphics-geforce-210-drivers-for-win10/"><u>Unveil the Future of Graphics: GeForce 210 Drivers for Win10</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcoming-freeze-save-display-issue-resolved/"><u>Overcoming Freeze: Save Display Issue Resolved</u></a></li>
<li><a href="https://network-issues.techidaily.com/strategies-for-controlling-lenovo-screenshake/"><u>Strategies for Controlling Lenovo Screenshake</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/easy-steps-to-make-a-talking-avatar-with-ai-from-any-photos-for-2024/"><u>Easy Steps to Make a Talking Avatar with AI From Any Photos for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/gaming-nightmare-nvidias-rtx-3080-fix-guide/"><u>Gaming Nightmare: Nvidia's RTX 3080 Fix-Guide</u></a></li>
<li><a href="https://network-issues.techidaily.com/hack-free-gaming-quick-fix-for-legends-crash/"><u>Hack-Free Gaming: Quick Fix for Legends Crash</u></a></li>
<li><a href="https://extra-support.techidaily.com/prime-tools-for-gopro-action-footage-for-2024/"><u>Prime Tools for GoPro Action Footage for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-apple-iphone-12-drfone-by-drfone-virtual-ios/"><u>In 2024, Simple and Effective Ways to Change Your Country on YouTube App Of your Apple iPhone 12 | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixed-connectivity-glitches-in-cod-cold-war/"><u>[FIXED] Connectivity Glitches in CoD Cold War</u></a></li>
<li><a href="https://network-issues.techidaily.com/tackling-error-c1900101-during-os-setup/"><u>Tackling Error C1900101 During OS Setup</u></a></li>
<li><a href="https://network-issues.techidaily.com/shedding-light-on-inscrutable-x-errors-plaguing-lol/"><u>Shedding Light on Inscrutable X Errors Plaguing LoL</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-perfected-pixelated-photos-follow-the-10-key-composition-guidelines/"><u>[New] Perfected Pixelated Photos  Follow the 10 Key Composition Guidelines</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/silent-display-on-graphics-card/"><u>Silent Display on Graphics Card</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-chkdsk-sfc-and-dism-for-system-repairing/"><u>Decoding CHKDSK, SFC & DISM for System Repairing</u></a></li>
<li><a href="https://network-issues.techidaily.com/ninja-warrior-download-delayed/"><u>Ninja Warrior Download Delayed</u></a></li>
<li><a href="https://network-issues.techidaily.com/correcting-lenovo-screen-brightness-loss/"><u>Correcting Lenovo Screen Brightness Loss</u></a></li>
<li><a href="https://extra-skills.techidaily.com/pro-mkv-reader-for-personal-computers-for-2024/"><u>Pro MKV Reader for Personal Computers for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/windows-8-step-by-step-guide-to-launch-safe-mode-and-driver-uninstallation/"><u>Windows 8: Step-by-Step Guide to Launch Safe Mode and Driver Uninstallation</u></a></li>
<li><a href="https://network-issues.techidaily.com/eliminate-absence-in-sims-screens/"><u>Eliminate Absence in Sims' Screens</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-move-contacts-from-xiaomi-redmi-k70-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways to Move Contacts From Xiaomi Redmi K70 to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/opengl-quirk-found-and-resolved-in-nvidia-graphics/"><u>OpenGL Quirk Found & Resolved in Nvidia Graphics</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-your-apple-iphone-13-mini-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Reset Your Apple iPhone 13 mini Without iTunes? | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/pro-gamers-equipment-showcase-series/"><u>Pro Gamer's Equipment Showcase Series</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolved-error-22-graphics-driver/"><u>Resolved Error #22, Graphics Driver</u></a></li>
<li><a href="https://network-issues.techidaily.com/1719974338033-maximize-display-quality-update-to-the-newest-intel-hd-graphics-driver-for-w10/"><u>Maximize Display Quality: Update to the Newest Intel HD Graphics Driver for W10.</u></a></li>
<li><a href="https://network-issues.techidaily.com/restored-tv-viewing-via-hdmi-laptop-connected-successfully/"><u>[Restored] TV Viewing via HDMI, Laptop Connected Successfully</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-outwit-youtube-visitors-tips-to-evade-automated-audiences/"><u>[Updated] In 2024, Outwit YouTube Visitors  Tips to Evade Automated Audiences</u></a></li>
<li><a href="https://network-issues.techidaily.com/bridge-ghost-graphics-discrepancy/"><u>Bridge Ghost Graphics Discrepancy</u></a></li>
<li><a href="https://network-issues.techidaily.com/quick-fixes-for-youtube-background-issues-green/"><u>Quick Fixes for Youtube Background Issues (Green)</u></a></li>
<li><a href="https://network-issues.techidaily.com/crystal-clear-interface-effortless-change/"><u>Crystal-Clear Interface, Effortless Change</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-turbo-charge-your-tiktok-experience-with-fast-forwarding/"><u>[New] Turbo Charge Your TikTok Experience with Fast Forwarding</u></a></li>
<li><a href="https://some-tips.techidaily.com/the-fastest-way-to-scan-windows-files-for-2024/"><u>The Fastest Way to Scan Windows Files for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-make-the-most-of-your-mobile-audience-resizing-videos-for-vertical-playback-for-2024/"><u>Updated Make the Most of Your Mobile Audience Resizing Videos for Vertical Playback for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/o-download-part-of-youtube-video-in-2024/"><u>How to Download Part of YouTube Video, In 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/solving-asus-internal-webcam-issues/"><u>Solving Asus Internal Webcam Issues</u></a></li>
<li><a href="https://network-issues.techidaily.com/direct3d-launch-attempt-failed-fixed/"><u>Direct3D Launch Attempt Failed, Fixed</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-dive-into-the-world-of-cosmetics-launching-a-beauty-channel/"><u>In 2024, Dive Into the World of Cosmetics  Launching a Beauty Channel</u></a></li>
<li><a href="https://network-issues.techidaily.com/competitive-edge-how-amd-graphics-drives-winning-performance/"><u>Competitive Edge: How AMD Graphics Drives Winning Performance</u></a></li>
<li><a href="https://network-issues.techidaily.com/improve-your-monitors-layout-with-wins11-tools/"><u>Improve Your Monitor's Layout with Wins11 Tools</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-beginners-guide-steady-sound-volume-rise-in-editing/"><u>2024 Approved  Beginner's Guide  Steady Sound Volume Rise in Editing</u></a></li>
</ul></div>
