---
title: "Graphic Glitch Cleared: Driver Restarted Successfully"
date: 2024-07-12T00:22:56.955Z
updated: 2024-07-13T00:22:56.955Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: "This Article Describes Graphic Glitch Cleared: Driver Restarted Successfully"
excerpt: "This Article Describes Graphic Glitch Cleared: Driver Restarted Successfully"
keywords: Graphic Error Resolution,Crash Recovery for Drivers,Restart Driver After Glitch,Graphic System Error Troubleshooting,Drivers' Performance Optimization,Glitch-Free Graphic Operations,Successful Driver Restart Techniques
thumbnail: https://thmb.techidaily.com/528781abe64eff7e57733460b453c6895f2f9ec8900c30ab49d86e203a9429b2.jpg
---

## Graphic Glitch Cleared: Driver Restarted Successfully

![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58fd77e68afed.jpg)
 _Display driver nvlddmkm stopped responding and has successfully recovered_
  
 Error “Display driver stopped responding and has successfully recovered” usually occurs when playing games. If you have this problem, you should see the black screen appear randomly. This is very frustrating. But don’t worry. You can use solutions below to fix the problem .  
  
**Solution 1: Change Power Supply**
  
 The problem can be caused by lower power to the video card. So make sure the power supply are on high performance. Follow steps below to check and change the settings if necessary.  
  
 1\. Open [Control Panel](https://tools.techidaily.com/drivereasy/download/) .  
  
 2\. View by Large icons and select**Power Options** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58fdc56193bee.jpg)
  
 3\. Click**Change plan settings** in the “High performance plan” **.**
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58fdc6095a244.jpg)
  
 4\. Click**Change advanced power settings** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58fdc662f10a7.png)
  
 5\. Expand**PCI Express** then**Link State Power Management** . Ensure the Setting is turned **Off** . If not, set it to Off.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58fdc6a8bb61b.png)
  
 **Solution 2: Fix Faulty Graphics Card Driver**
  
 The error may be caused by faulty Nvidia graphics driver. So the first thing you can do is uninstall the graphics driver then update the driver to the latest version.  
  
 **Uninstall the Nvidia Driver**
  
 Follow steps below to uninstall the driver.  
 1\. Open [Device Manager](https://tools.techidaily.com/drivereasy/download/) .  
  
 2\. Expand category “Display adapters”. Right-click on the Nvidia graphics card device name and select**Uninstall** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58fd7f5175ab6.jpg)

 3\. When prompted for continue, click the box next to “Delete the driver software for this device” (if you see this), then click**OK**  button.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58fd7f69c729a.png)
  
 4\. Restart your PC for the change to take effect.  
  
 After computer restarts, Windows will install the graphics card driver automatically. Then the problem may resolve. If not, try updating the driver.  
  
**Update the Nvidia Graphics Card Driver**
  
 You can go to the PC manufacturer’s website to check for and download the latest graphics card driver. Alternatively, you can go to Nvidia’s website to download the driver according to the graphics card model. Before you get started, ensure that you know the PC model or the graphics card model and the operating system that you are using (See [How to Get Operating System Version](https://tools.techidaily.com/drivereasy/download/) ).  
  
 Alternatively, download [Driver Easy](https://tools.techidaily.com/drivereasy/download/) and use it to update the driver automatically. Driver Easy will scan your computer in a few seconds and detect all problem drivers. After that, you will get a list of new drivers. Driver Easy has Free version and Pro version. With [Driver Easy PRO version](https://tools.techidaily.com/drivereasy/download/) , you can even update all drivers including the Nvidia graphics card driver with just one-click. What’s more, you will enjoy free tech support guarantee and 30-day money back guarantee. Just contact us for further assistance regarding the graphics card crashing issue.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58fda0c612fb9.png)

**Solution 3: Add Two Related Registry Keys**
  
 If neither of Solution 1 and Solution 2 doesn’t work for you, try adding two related registry keys to the this location:  HKEY\_LOCAL\_MACHINE/SYSTEM/CurrentControlSet/Control/GraphicsDrivers.
  
 Before you get started, it is recommended that you back up the registry, so you can restore it if any problem occurs. See [How to Back Up and Restore Registry](https://tools.techidaily.com/drivereasy/download/)
  
 Follow these steps to add the registry keys:  
  
 1\. Press**Win+R** (Windows key and R key) at the same time. A Run dialog box will appear.  
  
 2\. Type**regedit** in the run box then click**OK** button. Then the “Registry” Editor will open.  
  
![](https://images.drivereasy.com/wp-content/uploads/2016/02/img_56d1514256cf9.png)

 3\. Browse to and then click the following registry subkey:

 **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\GraphicsDrivers**
  
![](https://images.drivereasy.com/wp-content/uploads/2016/02/img_56d15158994b0.png)

  4\. On the**Edit** menu in the right pane, right-click on the blank place. Click**New** , and then select the following registry value from the drop-down menu specific to your version of Windows.

 If your PC is running**32-bit** operating system, follow these steps:  
  
 a. Select**DWORD (32-bit) Value** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2016/02/img_56d151767ad5b.png)

  b. Type**TdrDelay** as the**Name** and click**Enter** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2016/02/img_56d15185e69a6.png)

 c. Double-click TdrDelay and add “20” for the Value data and click**OK** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58fdcefb5f556.png)

 Repeat steps above to add a new DWORD named “**TdrDdiDelay** ” and also add “20” for the Value data.  
  
 If your PC is running**64-bit** operating system, follow steps below:

 a. Select**QWORD (64-bit) Value** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2016/02/img_56d151bc4d971.png)

  b. Type**TdrDelay** as the**Name** and click**Enter** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2016/02/img_56d151caa9437.png)

  c. Double-click TdrDelay and add “20” for the Value data and click**OK** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58fdd06cb443f.png)

 Repeat steps above to add a new DWORD named “ **TdrDdiDelay** ” and also add  “20” for the Value data.  
  
4\. Restart your PC for the changes to take effect.

**Solution 4 : Take out the Graphics Card and Put it back in**
  
 If the graphics card is not seated well in the PCI-E slot, the problem may occur. So take out the graphics card and put it back in the slot. It is recommended that you use a soft cloth to clean the slot before you put it back in.  
  
 Hope you can solve the problem with all solutions here.  
  
 If you are not comfortable with some of these solutions, you can take your computer to the repair store to have it checked.

* [Windows](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://network-issues.techidaily.com/systemruntimeinteropservicescomexception-error-on-windows-solved/"><u>System.Runtime.InteropServices.COMException Error on Windows [SOLVED]</u></a></li>
<li><a href="https://network-issues.techidaily.com/gpu-reinstates-problem-overcome/"><u>GPU Reinstates, Problem Overcome</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-epic-escapades-in-playtime-paradise-for-2024/"><u>[New] Epic Escapades in Playtime Paradise for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/agriculture-adventures-with-comrades-top-10-farmers-craft/"><u>Agriculture Adventures with Comrades  Top 10 Farmer's Craft</u></a></li>
<li><a href="https://network-issues.techidaily.com/overwatch-displays-error-inadequate-graphics-hardware/"><u>Overwatch Displays Error: Inadequate Graphics Hardware</u></a></li>
<li><a href="https://network-issues.techidaily.com/windows-elevate-your-web-experience-post-slowdowns/"><u>[WINDOWS] Elevate Your Web Experience Post Slowdowns</u></a></li>
<li><a href="https://network-issues.techidaily.com/qualcomm-atheros-qca61x4a-fixed-in-windows-10-installation/"><u>Qualcomm Atheros QCA61x4A Fixed in Windows 10 Installation</u></a></li>
<li><a href="https://network-issues.techidaily.com/monitor-configuration-for-correct-fullscreen-display/"><u>Monitor Configuration for Correct Fullscreen Display</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-sign-docm-file-free-by-ldigisigner-sign-a-word-sign-a-word/"><u>How to sign .docm file free</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-the-art-of-time-lapse-2-proven-methods-for-stunning-videos/"><u>New 2024 Approved The Art of Time Lapse 2 Proven Methods for Stunning Videos</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-2024-approved-7-must-listen-episodes-transform-your-strategy-with-todays-social-media-trends/"><u>Updated 2024 Approved 7 Must-Listen Episodes Transform Your Strategy with Todays Social Media Trends</u></a></li>
<li><a href="https://network-issues.techidaily.com/1719974046950-resolve-playback-jitters-fast/"><u>Resolve Playback Jitters Fast!</u></a></li>
<li><a href="https://network-issues.techidaily.com/unearthing-the-hidden-source-behind-mysterious-dx-issues-in-leagues/"><u>Unearthing the Hidden Source Behind Mysterious DX Issues in Leagues</u></a></li>
<li><a href="https://network-issues.techidaily.com/rtx210-driver-upgrade-nvidias-win11-improvement/"><u>RTX210 Driver Upgrade: NVIDIA's Win11 Improvement</u></a></li>
<li><a href="https://network-issues.techidaily.com/fix-no-signage-in-sims-games/"><u>Fix No Signage in Sims Games</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-gps-location-on-meizu-21-easily-and-safely-drfone-by-drfone-virtual-android/"><u>How to Change GPS Location on Meizu 21 Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/gfxwindowlock-up-error-windows-fix-ready/"><u>GfxWindowLock Up Error, WIndows Fix (Ready)</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-ideal-5k-tactile-gaming-sets-8/"><u>2024 Approved  Ideal 5K Tactile Gaming Sets (#8)</u></a></li>
<li><a href="https://howto.techidaily.com/calls-on-vivo-s17-pro-go-straight-to-voicemail-12-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Calls on Vivo S17 Pro Go Straight to Voicemail? 12 Fixes | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-open-your-apple-iphone-13-without-a-home-button-drfone-by-drfone-ios/"><u>How To Open Your Apple iPhone 13 Without a Home Button | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-the-classic-questline-versus-the-dynamic-strategy/"><u>[Updated] 2024 Approved  The Classic Questline versus the Dynamic Strategy</u></a></li>
<li><a href="https://network-issues.techidaily.com/stepwise-methodology-for-quick-remediation-of-portable-display-lines/"><u>Stepwise Methodology for Quick Remediation of Portable Display Lines</u></a></li>
<li><a href="https://network-issues.techidaily.com/rampage-resolved-frustrating-fetches/"><u>Rampage Resolved: Frustrating Fetches</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/beating-buffering-bars-in-twitch-broadcasts-today-for-2024/"><u>Beating Buffering Bars in Twitch Broadcasts Today for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/evaluating-amds-strategies-for-a-winning-place-in-gaming-hardware/"><u>Evaluating AMD's Strategies for a Winning Place in Gaming Hardware</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-exploring-with-tomtom-actioncam-new-year/"><u>2024 Approved  Exploring with TomTom ActionCam New Year</u></a></li>
<li><a href="https://network-issues.techidaily.com/graphics-hardware-regains-functionality/"><u>Graphics Hardware Regains Functionality</u></a></li>
<li><a href="https://network-issues.techidaily.com/eradicated-erratic-code-22-in-gdriver/"><u>Eradicated Erratic Code #22 in GDRIVER</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-video-editing-on-chromebook-a-step-by-step-guide-to-using-any-app/"><u>New Video Editing on Chromebook A Step-by-Step Guide to Using Any App</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-game-on-in-reality-discover-the-top-5-samsung-vr-titles/"><u>In 2024, Game On in Reality! Discover the Top 5 Samsung VR Titles</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-ways-to-recover-deleted-files-from-oppo-a79-5g-by-fonelab-android-recover-data/"><u>Possible ways to recover deleted files from Oppo A79 5G</u></a></li>
<li><a href="https://network-issues.techidaily.com/unpacking-4k-extreme-clarity-and-quality/"><u>Unpacking 4K Extreme Clarity and Quality</u></a></li>
<li><a href="https://network-issues.techidaily.com/successful-fix-for-nvidia-related-windows-stoppage/"><u>Successful Fix for Nvidia-Related Windows Stoppage</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-from-amateur-to-expert-iphones-audio-recording-journey/"><u>[Updated] In 2024, From Amateur to Expert  IPhone's Audio Recording Journey</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-conquer-iphone-podcast-downloads-a-step-by-step-guidebook/"><u>2024 Approved  Conquer iPhone Podcast Downloads – A Step-by-Step Guidebook</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-understanding-and-mastering-video-content-on-yt-shorts/"><u>[New] Understanding and Mastering Video Content on YT Shorts</u></a></li>
<li><a href="https://network-issues.techidaily.com/post-update-success-uninterrupted-video-streaming-on-win10/"><u>Post-Update Success: Uninterrupted Video Streaming on Win10</u></a></li>
</ul></div>
