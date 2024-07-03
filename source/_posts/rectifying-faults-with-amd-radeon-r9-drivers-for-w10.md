---
title: Rectifying Faults with AMD Radeon R9 Drivers for W10
date: 2024-07-02T03:31:29.116Z
updated: 2024-07-03T03:31:29.116Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: This Article Describes Rectifying Faults with AMD Radeon R9 Drivers for W10
excerpt: This Article Describes Rectifying Faults with AMD Radeon R9 Drivers for W10
keywords: AMD Radeon R9 Drivers W10 Update,Nvidia CUDA Compatibility W10,Windows 10 Graphics Driver Issues,Radeon R9 Driver Installation Guide,Fixed Radeon R9 Performance on Win10,Resolving AMD GPU Problems in Windows 10,Best Drivers for AMD Radeon R9 in W10
thumbnail: https://thmb.techidaily.com/c3853b005ad6636456539b898eb59cf75f875d556870e0b3c55b58ed003b40eb.jpg
---

## Rectifying Faults with AMD Radeon R9 Drivers for W10

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
<li><a href="https://network-issues.techidaily.com/addressing-dimming-on-lenovo-portable-devices/"><u>Addressing Dimming on Lenovo Portable Devices</u></a></li>
<li><a href="https://network-issues.techidaily.com/easy-to-fix-guide-unused-graphics-card-wnvidia/"><u>Easy-to-Fix Guide: Unused Graphics Card W/NVIDIA</u></a></li>
<li><a href="https://network-issues.techidaily.com/steps-to-rectify-acer-screen-glarespeed/"><u>Steps to Rectify Acer Screen Glarespeed</u></a></li>
<li><a href="https://network-issues.techidaily.com/remedy-freezing-screen-in-win10-update/"><u>Remedy Freezing Screen in Win10 Update</u></a></li>
<li><a href="https://network-issues.techidaily.com/troubleshoot-horizontal-display-glitches-on-notebooks/"><u>Troubleshoot Horizontal Display Glitches on Notebooks</u></a></li>
<li><a href="https://network-issues.techidaily.com/windows-10-screen-flashing-or-flickering-solved/"><u>Windows 10 Screen Flashing Or Flickering [SOLVED]</u></a></li>
<li><a href="https://network-issues.techidaily.com/rectifying-windows-10-hologram-error/"><u>Rectifying Windows 10 Hologram Error</u></a></li>
<li><a href="https://location-social.techidaily.com/edit-and-send-fake-location-on-telegram-for-your-infinix-smart-7-in-3-ways-drfone-by-drfone-virtual-android/"><u>Edit and Send Fake Location on Telegram For your Infinix Smart 7 in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-about-factory-reset-what-is-it-and-what-it-does-to-your-oppo-a2-drfone-by-drfone-reset-android-reset-android/"><u>All About Factory Reset, What Is It and What It Does to Your Oppo A2? | Dr.fone</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-in-2024-want-to-clone-voices-in-real-time-explore-these-github-repositories/"><u>Updated In 2024, Want to Clone Voices in Real-Time? Explore These GitHub Repositories</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-behind-the-scenes-sound-management-expert-insights-into-using-ducking-effects/"><u>In 2024, Behind-the-Scenes Sound Management Expert Insights Into Using Ducking Effects</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-ultimate-list-of-3d-typographic-sites/"><u>[Updated] Ultimate List of 3D Typographic Sites</u></a></li>
<li><a href="https://extra-hints.techidaily.com/distortion-driven-the-artists-guide-to-altered-text/"><u>Distortion Driven  The Artist's Guide to Altered Text</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-periscope-presentation-outline-width-height-time/"><u>In 2024, Periscope Presentation Outline  Width, Height, Time</u></a></li>
<li><a href="https://discord-videos.techidaily.com/pioneering-collaboration-sharing-your-screen-on-discord-for-2024/"><u>Pioneering Collaboration  Sharing Your Screen on Discord for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-full-guide-to-fix-itoolab-anygo-not-working-on-samsung-galaxy-f54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Full Guide to Fix iToolab AnyGO Not Working On Samsung Galaxy F54 5G | Dr.fone</u></a></li>
</ul></div>
