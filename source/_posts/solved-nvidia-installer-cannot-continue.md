---
title: "[Solved] NVIDIA Installer Cannot Continue"
date: 2024-10-21T16:02:56.372Z
updated: 2024-10-24T01:21:17.129Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: This Article Describes [Solved] NVIDIA Installer Cannot Continue
excerpt: This Article Describes [Solved] NVIDIA Installer Cannot Continue
keywords: Troubleshooting NVIDIA Installation Issues,Fixing Failed NVIDIA Driver Setup,Resolving Errors in NVIDIA Software Installation,Steps to Successfully Install NVIDIA Graphics Card,Guidelines for Completing an Unsuccessful NVIDIA Installer,How to Overcome Obstacles During NVIDIA Setup Process,Tips for a Smooth and Complete NVIDIA Driver Installation
thumbnail: https://thmb.techidaily.com/b75342051a1eed044885b06ddc777260c76924178d810e45fd7a89223f0c20e7.jpg
---

## [Solved] NVIDIA Installer Cannot Continue

 Do you get this error message when installing your NVIDIA Graphics driver?:

“   **NVIDIA Installer cannot continue. This graphics driver could not find compatible graphics hardware.”**

![](https://images.drivereasy.com/wp-content/uploads/2019/08/image-608.png)

 If so, don’t worry. It’s a really common issue and one you can usually fix yourself. You can install the driver successfully by following the instructions we’ve put together in this article.

## Firstly, try to install the driver using Driver Easy

 Installing an incompatible driver can cause this error. Before you try anything else, you should use **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  to install the driver.  It’s as quick and simple as 2 mouse clicks.

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. **But with the Pro version it takes just 2 clicks (and you get full support and a 30-day money back guarantee)** . Here’s what you need to do:

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click **Scan Now** . Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2019/08/image-606.png)

 3) Click the **Update** button next to a flagged Nvidia driver to automatically download the correct version of this driver, then you can manually install it (you can do this with the FREE version).

 Or click **Update All**  to automatically download and install the correct version of _all_   the drivers that are missing or out of date on your system (this requires the Pro version – you’ll be prompted to upgrade when you click Update All).

 In the below example, you can see that NVIDIA GeForce GT 640 needs to be updated. Driver Easy will detect the Nvidia graphics card installed on your computer.

![](https://images.drivereasy.com/wp-content/uploads/2019/08/image-607.png)

 If you can’t install the driver with Driver Easy, the graphics card may be disabled or sending the wrong information.  If this happens to you, follow the instructions below to check.

<!-- affiliate ads begin -->
<a href="https://jalbum-affiliate-program.sjv.io/c/5597632/1584040/17916" target="_top" id="1584040">
  <img src="//a.impactradius-go.com/display-ad/17916-1584040" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://jalbum-affiliate-program.sjv.io/i/5597632/1584040/17916" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## **Check if the Graphics Card is Disabled**

 If your graphics card is disabled, you won’t be able to install the driver, which is likely to be what’s causing the error. You can check this setting in Device Manager:

 1) Go to [Device Manager,](https://tools.techidaily.com/drivereasy/download/)  if you see a small down arrow next to the device, as shown in the picture below, it’s been disabled. All you need to do is right-click the device and click **Enable** .

![](https://images.drivereasy.com/wp-content/uploads/2016/11/img_581c50591ccf5.png)

2) Restart your PC if it asks you to. Then reinstall the driver.

## **Check if the Graphics Card is Detected Incorrectly**

 Under category the “ **Display adapters**  “, if you can’t see your graphics card listed, it’s probably not being detected properly. It could be listed under “Other devices” or somewhere else, or coming up as another device name.

 To check if this is happening, locate the devices with yellow marks on them. One of these devices may be your NVIDIA graphics card. If you’re not sure how to figure out which one is your graphics card, you can follow the steps below:

 1) Right-click on a device with a yellow mark on it and click **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2016/11/img_581c568d597b7.png)

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137976/21526" target="_top" id="2137976">
  <img src="//a.impactradius-go.com/display-ad/21526-2137976" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137976/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 2) Go to the **Details** tab, select**Hardware Ids** from the drop-down menu under **Property** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_5785de836c928.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075483/7443" target="_top" id="2075483">
  <img src="//a.impactradius-go.com/display-ad/7443-2075483" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075483/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) The Hardware Id Value should be similar to the below screenshot. The VEN code means vendor and the DEV code means device. In the example below, the VEN code is 15AD and the device is 0740.

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_5785df1376590.png)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657396/16446" target="_top" id="1657396">
  <img src="//a.impactradius-go.com/display-ad/16446-1657396" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657396/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 4) Go to [https://pci-ids.ucw.cz/](https://pci-ids.ucw.cz/) . You use the VEN code and the DEV code you got from Step 3) to find the device.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b56e6603c4e9.jpg)

 This will give you the device name and the vendor name (NVIDIA).

 Once you figure out the specific NVIDIA graphics card you have, you should update your driver to the latest version.

 If you’ve tried these solutions and continue to get an error, let us know! Leave a comment below and we’ll do our best to help.

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
<li><a href="https://network-issues.techidaily.com/repaired-overcoming-disconnect-issues-with-cod-cold-war/"><u>[REPAIRED]: Overcoming Disconnect Issues with CoD Cold War</u></a></li>
<li><a href="https://network-issues.techidaily.com/battlezone-buffering-blunder/"><u>Battlezone Buffering Blunder</u></a></li>
<li><a href="https://network-issues.techidaily.com/cure-blackout-on-newest-win11-version/"><u>Cure Blackout on Newest Win11 Version</u></a></li>
<li><a href="https://network-issues.techidaily.com/defeating-wow-error-no-519-with-ease/"><u>Defeating WoW Error No. 519 with Ease</u></a></li>
<li><a href="https://techidaily.com/guide-accessing-and-analyzing-windows-crash-reports/"><u>Guide: Accessing and Analyzing Windows Crash Reports</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-change-vivo-x-flip-lock-screen-password-by-drfone-android/"><u>How To Change Vivo X Flip Lock Screen Password?</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-music-from-motorola-moto-g14-by-fonelab-android-recover-music/"><u>How to retrieve erased music from Motorola Moto G14</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-on-infinix-smart-8-hd-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock on Infinix Smart 8 HD Devices</u></a></li>
<li><a href="https://network-issues.techidaily.com/mastering-youtubes-green-screen-problems/"><u>Mastering YouTube's Green Screen Problems</u></a></li>
<li><a href="https://network-issues.techidaily.com/mend-visual-split-issues-in-pc/"><u>Mend Visual Split Issues in PC</u></a></li>
<li><a href="https://common-error.techidaily.com/stop-worrying-about-your-huion-device-discover-these-5-quick-pen-repair-tips/"><u>Stop Worrying About Your Huion Device; Discover These 5 Quick Pen Repair Tips!</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/the-best-free-video-rotators-for-mov-files/"><u>The Best Free Video Rotators for MOV Files</u></a></li>
<li><a href="https://buynow-help.techidaily.com/the-ultimate-ranking-how-fifa-19-dominates-the-world-of-e-sports-titles/"><u>The Ultimate Ranking: How FIFA 19 Dominates the World of E-Sports Titles</u></a></li>
</ul></div>

