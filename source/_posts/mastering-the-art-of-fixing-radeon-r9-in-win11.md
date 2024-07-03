---
title: Mastering the Art of Fixing Radeon R9 in Win11
date: 2024-07-02T03:34:32.218Z
updated: 2024-07-03T03:34:32.218Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: This Article Describes Mastering the Art of Fixing Radeon R9 in Win11
excerpt: This Article Describes Mastering the Art of Fixing Radeon R9 in Win11
keywords: Radeon R9 Troubleshooting,Windows 11 GPU Optimization,Win11 AMD Graphics Repair,Radeon Performance Enhancement (Win11),Fixing R9 Graphics in Windows 11,RTG Driver Issues Resolution (Win11),Improve R9 on Windows 11
thumbnail: https://thmb.techidaily.com/b7ac3fecaf39cbf4ad53ade68b5607328fb5fc5fabf85fb01691cb6e94c786a0.jpg
---

## Mastering the Art of Fixing Radeon R9 in Win11

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
<li><a href="https://network-issues.techidaily.com/expert-tips-to-correct-laptop-screen-horizontal-distortions/"><u>Expert Tips to Correct Laptop Screen Horizontal Distortions</u></a></li>
<li><a href="https://network-issues.techidaily.com/instant-solution-to-diagonal-screen-issues/"><u>Instant Solution to Diagonal Screen Issues</u></a></li>
<li><a href="https://network-issues.techidaily.com/saved-visuals-post-adjustment-fix/"><u>Saved Visuals Post-Adjustment Fix</u></a></li>
<li><a href="https://network-issues.techidaily.com/windows-11-end-of-black-outage/"><u>Windows 11: End of Black Outage</u></a></li>
<li><a href="https://network-issues.techidaily.com/bringing-back-screen-color-fall-update-fix/"><u>Bringing Back Screen Color: Fall Update Fix</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolving-hd-content-playback-in-new-windows-version/"><u>Resolving HD Content Playback in New Windows Version</u></a></li>
<li><a href="https://network-issues.techidaily.com/correcting-inverted-display-on-windows-7/"><u>Correcting Inverted Display on Windows 7</u></a></li>
<li><a href="https://network-issues.techidaily.com/gateway-broken-geforce-experience-opened/"><u>Gateway Broken: GeForce Experience Opened</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcoming-compatibility-issues-nvidiaintel-switchable-graphics-on-win10/"><u>Overcoming Compatibility Issues: Nvidia/Intel Switchable Graphics on Win10</u></a></li>
<li><a href="https://network-issues.techidaily.com/win11-stabilizing-visuals-no-more-shakes/"><u>Win11: Stabilizing Visuals, No More Shakes</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/ultimate-screen-logger-suite-for-2024/"><u>Ultimate Screen Logger Suite for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-digital-illustration-turning-your-favorite-vimeo-videos-into-gifs/"><u>[New] In 2024, Digital Illustration  Turning Your Favorite Vimeo Videos Into GIFs</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-discover-the-potential-detailed-look-at-showmore-as-your-recording-companion/"><u>In 2024, Discover the Potential  Detailed Look at ShowMore as Your Recording Companion</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-ultimate-free-fb-photovideo-maker/"><u>[Updated] Ultimate Free FB Photo/Video Maker</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/2024-approved-deconstructing-the-efficacy-of-sound-forge-in-music-production/"><u>2024 Approved Deconstructing the Efficacy of Sound Forge in Music Production</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-remove-passcode-from-iphone-12-complete-guide-by-drfone-ios/"><u>In 2024, How To Remove Passcode From iPhone 12? Complete Guide</u></a></li>
<li><a href="https://fake-location.techidaily.com/wondering-the-best-alternative-to-hola-on-motorola-moto-g84-5g-here-is-the-answer-drfone-by-drfone-virtual-android/"><u>Wondering the Best Alternative to Hola On Motorola Moto G84 5G? Here Is the Answer | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-how-to-keep-unwanted-content-away-from-your-computer-and-phone-for-2024/"><u>[New] How to Keep Unwanted Content Away From Your Computer and Phone for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/personalize-your-digital-notepad-a-guide-to-windows-11-customization/"><u>Personalize Your Digital Notepad: A Guide to Windows 11 Customization</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/photoshop-curves-decoded-a-beginners-guide-for-2024/"><u>Photoshop Curves Decoded  A Beginner's Guide for 2024</u></a></li>
</ul></div>
