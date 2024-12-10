---
title: Resolving R9 Graphics Drivers on Win10, Finally
date: 2024-12-06T07:05:19.879Z
updated: 2024-12-10T03:45:23.615Z
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
<li><a href="https://network-issues.techidaily.com/solved-windows-11-wireless-adapter-missing/"><u>[SOLVED] Windows 11 Wireless Adapter Missing</u></a></li>
<li><a href="https://network-issues.techidaily.com/troubleshooted-driver-installed-gpu-adapter-in-win1110/"><u>[TROUBLESHOOTED DRIVER] Installed GPU Adapter in Win11/10</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-enhancing-media-creation-skills-with-windows-movie-maker-windows-8-edition/"><u>2024 Approved Enhancing Media Creation Skills with Windows Movie Maker (Windows 8 Edition)</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-solitary-speaker-issue-solution-steps/"><u>2024 Approved Solitary Speaker Issue Solution Steps</u></a></li>
<li><a href="https://android-location.techidaily.com/9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-infinix-smart-7-hd-drfone-by-drfone-virtual/"><u>9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Infinix Smart 7 HD | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/addressing-save-issues-in-win-107-default-settings/"><u>Addressing Save Issues in Win 10/7 Default Settings</u></a></li>
<li><a href="https://network-issues.techidaily.com/correcting-lenovo-monitor-flicker/"><u>Correcting Lenovo Monitor Flicker</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-one-way-outlook-on-secure-windows-operating-system/"><u>Dealing with One-Way Outlook on Secure Windows Operating System</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/how-the-iphone-14-hits-the-perfect-balance-a-comprehensive-review/"><u>How the iPhone 14 Hits the Perfect Balance - A Comprehensive Review</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-check-distance-and-radius-on-google-maps-for-your-samsung-galaxy-a05-drfone-by-drfone-virtual-android/"><u>How to Check Distance and Radius on Google Maps For your Samsung Galaxy A05 | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-why-is-ipogo-not-working-on-samsung-galaxy-f34-5g-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, Why is iPogo not working On Samsung Galaxy F34 5G? Fixed | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/1719974730085-lenovo-tap-resistance-quick-fixed/"><u>Lenovo Tap Resistance: Quick Fixed!</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-discount-alert-4-authorized-ways-to-get-cheap-filmora-subscriptions/"><u>New 2024 Approved Discount Alert! 4 Authorized Ways to Get Cheap Filmora Subscriptions</u></a></li>
<li><a href="https://network-issues.techidaily.com/nvidia-driver-issue-fixed-post-failure/"><u>Nvidia Driver Issue Fixed Post-Failure</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/overcoming-initialization-problems-with-mozilla-thunderbird-a-comprehensive-fix/"><u>Overcoming Initialization Problems with Mozilla Thunderbird: A Comprehensive Fix</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolved-overwatch-gpu-compatibility-concerns/"><u>Resolved: Overwatch GPU Compatibility Concerns</u></a></li>
<li><a href="https://network-issues.techidaily.com/win11-flicker-free-vision-achieved/"><u>Win11: Flicker-Free Vision Achieved</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fvAC8jgs62o?si=xqEXZ7dpAXZ4sZ7A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

