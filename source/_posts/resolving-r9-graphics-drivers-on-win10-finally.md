---
title: Resolving R9 Graphics Drivers on Win10, Finally
date: 2024-07-29T02:57:45.581Z
updated: 2024-07-30T02:57:45.581Z
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

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/settings-updates-security.jpg)

2) Make sure you have installed the latest version of the Microsoft .Net Framework. For more information as to how to install the latest version of Microsoft .Net Framework, please visit this [**post here**](https://tools.techidaily.com/drivereasy/download/).
  
 **Step one: Run DISM command**
  
 DISM stands for Deployment Image Servicing and Management, which is a tool that helps you scan the integrity of your Windows image.
  
 1) Press**Windows key** and**X** at the same time, then choose**Command Prompt (Run as administrator)** .
  
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
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
  
<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633309&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/3_premium-icon.png" border="0"> Take advantage of PREMIUM features for 12 months. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Yearly Membership</a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_586490d260746.png)

4) Locate**Display adapters**category, then double click the**AMD Radeon R9**series of display driver that you have.
  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_5864a9af8c728.jpg)

5) Under**Driver**tab, choose**Uninstall**.
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_5864a9dcb005b.jpg)
  
 Tick the box for**Delete the driver software for this device** option and click**OK** to continue.
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_5864ab747efcd.png)

 6) Reboot your PC.
  
 7) Then**download** the AMD Clean Uninstall Utility from its support website. Then double click the**AMDCleanUtility.exe** icon to run the application.  
  
<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_5864ac776f616.png)
  
 Then just follow the instructions on screen to get all your AMD driver and application components removed.  
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_5864acd59401a.jpg)
  
 Your computer will restart when the whole process if finished.
  
**Note** : If you already have a trusted application or driver remover, you can use it to do the full uninstall too.
  
 8) When your computer restart again, download the latest version of the AMD Radeon R9 series driver from AMD website and then install it manually.  
  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_5864b2625647d.png)

 If you want to save yourself more time and energy for other things, you can leave your driver problems to [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) . It automatically help you detects, downloads and updates device drivers that are missing or outdated on your computer. And, there are only two steps you take to do it:
  
 Step one: press the**Scan Now** button so [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) can help you detect for needed drivers.
  
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58e894bc3e848.png)
  
 Step two: press the**Update** button so [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) can help you download the setup file for the device driver that you need.  
  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://network-issues.techidaily.com/resolution-settings-adjust-windows-11-screen-size/"><u>[RESOLUTION SETTINGS] Adjust Windows 11 Screen Size</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-access-hq-facebook-content-anytime-offline/"><u>[Updated] 2024 Approved  Access HQ Facebook Content Anytime Offline</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-cutting-edge-techniques-for-youtube-video-edits-via-wm-maker-for-2024/"><u>[Updated] Cutting-Edge Techniques for YouTube Video Edits via WM Maker for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-ghoul-gags-generator/"><u>[Updated] Ghoul Gags Generator</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-pro-tips-iphone-in-the-dark-spotlight/"><u>2024 Approved  Pro Tips  IPhone in the Dark Spotlight</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-creators-guide-to-mastering-youtube-aspect-ratios/"><u>2024 Approved  The Creator's Guide to Mastering YOUTUBE Aspect Ratios</u></a></li>
<li><a href="https://network-issues.techidaily.com/1719974453129-accelerate-your-graphical-display-experience-update-intels-hd-graphics-to-windows-10/"><u>Accelerate Your Graphical Display Experience: Update Intel's HD Graphics to Windows 10.</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-things-you-need-to-know-about-wipe-datafactory-reset-for-honor-magic-5-lite-drfone-by-drfone-reset-android-reset-android/"><u>All Things You Need to Know about Wipe Data/Factory Reset For Honor Magic 5 Lite | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/amd-radeon-6950-new-windows-10-driver-release/"><u>AMD Radeon 6950: New Windows 10 Driver Release</u></a></li>
<li><a href="https://network-issues.techidaily.com/better-pc-experience-with-swift-roblox-action/"><u>Better PC Experience with Swift Roblox Action</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/chasing-the-cause-of-frozen-photobooth-videos/"><u>Chasing the Cause of Frozen Photobooth Videos</u></a></li>
<li><a href="https://network-issues.techidaily.com/clearing-up-invisible-display-problems/"><u>Clearing Up Invisible Display Problems</u></a></li>
<li><a href="https://network-issues.techidaily.com/conquering-wow-malfunction-no-519/"><u>Conquering WoW Malfunction No. 519</u></a></li>
<li><a href="https://network-issues.techidaily.com/correct-video-glitches-on-monitors/"><u>Correct Video Glitches on Monitors</u></a></li>
<li><a href="https://extra-information.techidaily.com/deciphering-apples-chip-strength-an-in-depth-look-at-m1-pro-vs-m1-max/"><u>Deciphering Apple’s Chip Strength  An In-Depth Look at M1 Pro Vs. M1 Max</u></a></li>
<li><a href="https://network-issues.techidaily.com/eliminate-screen-horizon-lines/"><u>Eliminate Screen Horizon Lines</u></a></li>
<li><a href="https://network-issues.techidaily.com/fix-inverted-screens-on-microsofts-windows-10/"><u>Fix: Inverted Screens on Microsoft's Windows 10</u></a></li>
<li><a href="https://network-issues.techidaily.com/fix-sudden-screen-glitch-on-win11/"><u>Fix: Sudden Screen Glitch on Win11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-enable-usb-debugging-on-a-locked-oppo-a79-5g-phone-by-drfone-android/"><u>In 2024, How To Enable USB Debugging on a Locked Oppo A79 5G Phone</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-circle-everything-you-need-to-know-on-vivo-y78plus-drfone-by-drfone-virtual-android/"><u>Life360 Circle Everything You Need to Know On Vivo Y78+ | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/mastering-the-mighty-spartans-move-set/"><u>Mastering the Mighty Spartan's Move Set</u></a></li>
<li><a href="https://extra-tips.techidaily.com/maximize-browser-functionality-chromes-full-screen-video-playback/"><u>Maximize Browser Functionality  Chrome's Full-Screen Video Playback</u></a></li>
<li><a href="https://network-issues.techidaily.com/navigate-sims-4-black-screen-fixes/"><u>Navigate Sims 4 Black Screen Fixes</u></a></li>
<li><a href="https://network-issues.techidaily.com/overclock-issue-resolved/"><u>Overclock Issue Resolved</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcoming-graphics-driver22-hurdle/"><u>Overcoming Graphics DRIVER#22 Hurdle</u></a></li>
<li><a href="https://network-issues.techidaily.com/overwatch-displaying-error-missing-graphical-specs/"><u>Overwatch Displaying Error: Missing Graphical Specs</u></a></li>
<li><a href="https://network-issues.techidaily.com/recover-lost-display-settings-in-win10/"><u>Recover Lost Display Settings in Win10</u></a></li>
<li><a href="https://network-issues.techidaily.com/refine-visual-clarity-on-latest-windows-11/"><u>Refine Visual Clarity on Latest Windows 11</u></a></li>
<li><a href="https://network-issues.techidaily.com/repairing-saving-mechanism-for-display-configurations-on-windows/"><u>Repairing Saving Mechanism for Display Configurations on Windows</u></a></li>
<li><a href="https://network-issues.techidaily.com/restoring-original-aspect-ratios-in-windows-11/"><u>Restoring Original Aspect Ratios in Windows 11</u></a></li>
<li><a href="https://network-issues.techidaily.com/screen-customization-saved-successfully/"><u>Screen Customization Saved Successfully</u></a></li>
<li><a href="https://network-issues.techidaily.com/streamline-vertical-calibration-on-computers/"><u>Streamline Vertical Calibration on Computers</u></a></li>
<li><a href="https://network-issues.techidaily.com/successful-installation-no-complaints-for-nvidia/"><u>Successful Installation, No Complaints for NVIDIA</u></a></li>
<li><a href="https://network-issues.techidaily.com/taming-nvidia-rtx-3080-glitches-in-games/"><u>Taming NVIDIA RTX 3080 Glitches in Games</u></a></li>
<li><a href="https://network-issues.techidaily.com/techniques-to-ensure-computer-identifies-gpu/"><u>Techniques to Ensure Computer Identifies GPU</u></a></li>
<li><a href="https://network-issues.techidaily.com/techniques-to-eradicate-hp-screensaver-glare/"><u>Techniques to Eradicate HP Screensaver Glare</u></a></li>
<li><a href="https://network-issues.techidaily.com/troubleshooting-stuck-video-feature-on-asus-device/"><u>Troubleshooting Stuck Video Feature on Asus Device</u></a></li>
<li><a href="https://network-issues.techidaily.com/visuals-preserved-after-update-attempt/"><u>Visuals Preserved After Update Attempt</u></a></li>
</ul></div>
