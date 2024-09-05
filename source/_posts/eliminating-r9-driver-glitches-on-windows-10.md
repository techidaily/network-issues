---
title: Eliminating R9 Driver Glitches on Windows 10
date: 2024-09-04T11:59:56.712Z
updated: 2024-09-05T11:59:56.712Z
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
<li><a href="https://network-issues.techidaily.com/gained-entry-to-gpu-preferences-panel/"><u>[Gained] Entry to GPU Preferences Panel</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-the-ultimate-guide-to-windows-11-gaming-recordings/"><u>[New] 2024 Approved  The Ultimate Guide to Windows 11 Gaming Recordings</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ehind-the-curtains-a-guide-to-youtubes-hidden-videos/"><u>[New] Behind the Curtains  A Guide to YouTube’s Hidden Videos</u></a></li>
<li><a href="https://youtube-data.techidaily.com/tep-by-step-to-craft-flawless-yt-thumbnails-for-2024/"><u>[New] Step-by-Step to Craft Flawless YT Thumbnails for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-top-tools-for-saving-insta-photos-and-videos-for-2024/"><u>[New] Top Tools for Saving Insta Photos & Videos for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolved-sudden-blinks-on-laptop-monitor/"><u>[Resolved] Sudden Blinks on Laptop Monitor</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-smallfile-recorder-review-and-alternatives/"><u>[Updated] 2024 Approved  SmallFile Recorder Review and Alternatives</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-balancing-netflix-stream-quality-and-playtime/"><u>[Updated] Balancing Netflix Stream Quality and Playtime</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-step-by-step-guide-to-creating-compelling-multi-picture-insta-stories-for-2024/"><u>[Updated] Step by Step Guide to Creating Compelling, Multi-Picture Insta Stories for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-video-creation-for-all-ages-crafting-your-first-10-youtube-videos/"><u>[Updated] Video Creation for All Ages  Crafting Your First 10 YouTube Videos</u></a></li>
<li><a href="https://network-issues.techidaily.com/achieving-compatibility-perfection-win10-plus-nvidia/"><u>Achieving Compatibility Perfection: Win10 + Nvidia</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/additional-tips-about-sinnoh-stone-for-nokia-c300-drfone-by-drfone-virtual-android/"><u>Additional Tips About Sinnoh Stone For Nokia C300 | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/addressing-stuttery-screens-on-windows-7/"><u>Addressing Stuttery Screens on Windows 7</u></a></li>
<li><a href="https://network-issues.techidaily.com/adjusting-vision-quality-in-windows-11/"><u>Adjusting Vision Quality in Windows 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/all-you-need-to-know-about-mega-greninja-for-oneplus-nord-3-5g-drfone-by-drfone-virtual-android/"><u>All You Need To Know About Mega Greninja For OnePlus Nord 3 5G | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/beliebteste-screen-recorder-software-fur-windows-1187-pcs-perfekt-zum-aufzeichnen-des-gesamten-oder-teils-der-bildschirmaktion/"><u>Beliebteste Screen Recorder-Software Für Windows 11/8/7 PCs - Perfekt Zum Aufzeichnen Des Gesamten Oder Teils Der Bildschirmaktion</u></a></li>
<li><a href="https://network-issues.techidaily.com/breeze-through-apex-errors-instantly/"><u>Breeze Through Apex Errors, Instantly</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-i-recover-permanently-deleted-photos-from-samsung-galaxy-a25-5g-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>Can I recover permanently deleted photos from Samsung Galaxy A25 5G</u></a></li>
<li><a href="https://network-issues.techidaily.com/clarifying-concepts-behind-4k-extraordinary-definition/"><u>Clarifying Concepts Behind 4K Extraordinary Definition</u></a></li>
<li><a href="https://network-issues.techidaily.com/conquering-youtubes-unwanted-green-screen-effects/"><u>Conquering Youtube's Unwanted Green Screen Effects</u></a></li>
<li><a href="https://network-issues.techidaily.com/correcting-dim-laptop-screen-problem-in-lenovo/"><u>Correcting Dim Laptop Screen Problem in Lenovo</u></a></li>
<li><a href="https://network-issues.techidaily.com/display-configuration-lost-in-windows-11/"><u>Display Configuration Lost in Windows 11</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/essential-tips-for-extracting-vimeo-content-as-high-quality-mp4s-for-2024/"><u>Essential Tips for Extracting Vimeo Content as High-Quality MP4s for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-diagnosing-and-repairing-malfunctioning-function-lock-buttons-on-a-dell-device/"><u>Expert Tips for Diagnosing and Repairing Malfunctioning Function Lock Buttons on a Dell Device</u></a></li>
<li><a href="https://network-issues.techidaily.com/fix-to-w11-screen-refresh-issue/"><u>Fix to W11 Screen Refresh Issue</u></a></li>
<li><a href="https://network-issues.techidaily.com/fix-windows-11-screen-post-update-fix/"><u>Fix Windows 11 Screen Post Update Fix</u></a></li>
<li><a href="https://network-issues.techidaily.com/gpu-troubleshooting-stop-win-minecraft-freezes/"><u>GPU Troubleshooting: Stop Win Minecraft Freezes</u></a></li>
<li><a href="https://network-issues.techidaily.com/guiding-gpu-fan-repair-process/"><u>Guiding GPU Fan Repair Process</u></a></li>
<li><a href="https://network-issues.techidaily.com/hardware-issue-code-43-cleared/"><u>Hardware Issue Code 43 Cleared</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-overcome-hp-laserjet-p2035-printer-drivers-error-on-microsoft-windows/"><u>How to Overcome HP LaserJet P2035 Printer Drivers Error on Microsoft Windows</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-cricket-apple-iphone-15-plus-for-free-by-drfone-ios/"><u>How To Unlock Cricket Apple iPhone 15 Plus for Free</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-cards-of-oppo-reno-8t-5g-without-puk-codes-by-drfone-android/"><u>How To Unlock SIM Cards Of Oppo Reno 8T 5G Without PUK Codes</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/hp-spectre-x360-review-powerful-performance-on-a-big-screen-without-compromises/"><u>HP Spectre X360 Review - Powerful Performance on a Big Screen Without Compromises</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-unlock-iphone-xr-with-forgotten-passcode-different-methods-you-can-try-drfone-by-drfone-ios/"><u>In 2024, Unlock iPhone XR With Forgotten Passcode Different Methods You Can Try | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/lenovo-screen-ignored-repair-success-reported/"><u>Lenovo Screen Ignored: Repair Success Reported</u></a></li>
<li><a href="https://network-issues.techidaily.com/mastering-uninterrupted-media-playback-post-win11-update/"><u>Mastering Uninterrupted Media Playback Post Win11 Update</u></a></li>
<li><a href="https://network-issues.techidaily.com/minecraft-on-pc-fixing-video-driver-failures/"><u>Minecraft on PC: Fixing Video Driver Failures</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcoming-windows-11-window-width-woes/"><u>Overcoming Windows 11 Window Width Woes</u></a></li>
<li><a href="https://network-issues.techidaily.com/overwatch-incompatibility-fixed-graphics-update-successful/"><u>Overwatch Incompatibility Fixed: Graphics Update Successful</u></a></li>
<li><a href="https://network-issues.techidaily.com/removing-intrusive-windows-flash-glitches/"><u>Removing Intrusive Windows Flash Glitches</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolved-wide-screen-problems-on-windows-os/"><u>Resolved Wide-Screen Problems on Windows OS</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolving-conflicts-between-nvidia-and-windows-11/"><u>Resolving Conflicts Between Nvidia and Windows 11</u></a></li>
<li><a href="https://network-issues.techidaily.com/restoring-windows-screen-after-update-fall/"><u>Restoring Windows Screen After Update Fall</u></a></li>
<li><a href="https://network-issues.techidaily.com/settling-the-riddle-peculiar-x-error-in-lol-unraveled/"><u>Settling the Riddle: Peculiar X Error in LoL Unraveled</u></a></li>
<li><a href="https://network-issues.techidaily.com/solving-windows-10-blurry-image-issue/"><u>Solving Windows 10 Blurry Image Issue</u></a></li>
<li><a href="https://network-issues.techidaily.com/steps-to-overcome-c1900101-installation-hiccup/"><u>Steps to Overcome C1900101 Installation Hiccup</u></a></li>
<li><a href="https://network-issues.techidaily.com/streamline-your-system-update-intel-graphics-3000-on-windows-10-now/"><u>Streamline Your System: Update Intel Graphics 3000 on Windows 10 Now!</u></a></li>
<li><a href="https://network-issues.techidaily.com/system-reboot-reverses-screen-returns-to-normal/"><u>System Reboot Reverses - Screen Returns to Normal</u></a></li>
<li><a href="https://network-issues.techidaily.com/the-black-screen-banished-from-lenovo-panels/"><u>The Black Screen Banished From Lenovo Panels</u></a></li>
<li><a href="https://buynow-help.techidaily.com/the-complete-guide-to-editing-images-with-gimp-your-free-multiplatform-solution/"><u>The Complete Guide to Editing Images with GIMP - Your Free, Multiplatform Solution</u></a></li>
<li><a href="https://apple-account.techidaily.com/troubleshooting-error-connecting-to-the-apple-id-server-on-iphone-7-plus-by-drfone-ios/"><u>Troubleshooting Error Connecting to the Apple ID Server On iPhone 7 Plus</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/king-financial-success-through-youtubes-viewer-count/"><u>Unlocking Financial Success Through Youtube's Viewer Count</u></a></li>
<li><a href="https://network-issues.techidaily.com/win11-enhanced-graphics-support-amds-radeon-hd-6950-update/"><u>Win11 Enhanced Graphics Support - AMD's Radeon HD 6950 Update</u></a></li>
<li><a href="https://network-issues.techidaily.com/windows-10-detects-adapter-whats-next/"><u>Windows 10 Detects Adapter: What's Next?</u></a></li>
<li><a href="https://network-issues.techidaily.com/windows-version-updates-fixed-bd-issues-in-ms-driver/"><u>Windows Version Updates: Fixed BD Issues in MS DRIVER</u></a></li>
<li><a href="https://network-issues.techidaily.com/winos-dxgkrnlsys-error-resolved-blue-screen/"><u>WinOS dxgkrnl.sys Error Resolved - Blue Screen</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1977023">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977023.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977023">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977023.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977023%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977023/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->