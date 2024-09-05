---
title: System Rebooted After Graphics Card Hiccup
date: 2024-09-04T12:05:20.327Z
updated: 2024-09-05T12:05:20.327Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: This Article Describes System Rebooted After Graphics Card Hiccup
excerpt: This Article Describes System Rebooted After Graphics Card Hiccup
keywords: System Reboot Troubleshooting,Graphics Card Error Resolution,Computer Graphics Issues Fix,GPU Overheating Solutions,Stabilizing Computer Performance,Graphics Card Failure Prevention,Hardware Recovery After Hiccup
thumbnail: https://thmb.techidaily.com/943166f05e826acb5eb0097146d69c366fc0ed75a4c0f9eeb903504474e41f95.jpg
---

## System Rebooted After Graphics Card Hiccup

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
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-conquering-macs-record-functionality-keyboard-driven-tips/"><u>[New] 2024 Approved  Conquering Mac's Record Functionality  Keyboard-Driven Tips</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-economic-guide-to-capturing-virtual-learning-spaces/"><u>[New] 2024 Approved  Economic Guide to Capturing Virtual Learning Spaces</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-decoding-the-art-of-asmr-filmmaking-techniques-for-2024/"><u>[New] Decoding the Art of ASMR Filmmaking Techniques for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-mastering-the-art-of-instagram-highlight-curation/"><u>[New] Mastering the Art of Instagram Highlight Curation</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-essential-mobile-media-creation-tools-iphone-vs-android-review/"><u>[Updated] 2024 Approved  Essential Mobile Media Creation Tools  IPhone vs Android Review</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-the-beginners-blueprint-for-mobile-youtube-videos/"><u>[Updated] The Beginner's Blueprint for Mobile YouTube Videos</u></a></li>
<li><a href="https://network-issues.techidaily.com/addressing-faded-lenovo-monitor-issues/"><u>Addressing Faded Lenovo Monitor Issues</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-locked-or-disabled-from-apple-iphone-xs-7-mehtods-you-cant-miss-by-drfone-ios/"><u>Apple ID Locked or Disabled From Apple iPhone XS? 7 Mehtods You Cant-Miss</u></a></li>
<li><a href="https://network-issues.techidaily.com/bridging-qca61x4a-wifi-driver-gaps-in-windows-10/"><u>Bridging QCA61x4A WiFi Driver Gaps in Windows 10</u></a></li>
<li><a href="https://network-issues.techidaily.com/bringing-forth-invisible-video-shutdowns/"><u>Bringing Forth Invisible Video Shutdowns</u></a></li>
<li><a href="https://network-issues.techidaily.com/bypassing-wow-problem-fix-51900319/"><u>Bypassing WoW Problem: Fix #51900319</u></a></li>
<li><a href="https://network-issues.techidaily.com/direct-fix-route-no-current-nvidia-output/"><u>Direct Fix Route: No Current NVIDIA Output</u></a></li>
<li><a href="https://network-issues.techidaily.com/discover-unseen-display-options-in-windows-11/"><u>Discover Unseen Display Options in Windows 11</u></a></li>
<li><a href="https://network-issues.techidaily.com/dispatched-glare-fluctuation-on-mobile-display/"><u>Dispatched Glare Fluctuation on Mobile Display</u></a></li>
<li><a href="https://video-capture.techidaily.com/echopause-visual-record-advice-for-2024/"><u>EchoPause Visual Record Advice for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-solutions-for-repairing-compromised-hardware-drivers-fast/"><u>Effortless Solutions for Repairing Compromised Hardware Drivers Fast</u></a></li>
<li><a href="https://network-issues.techidaily.com/enhance-visual-performance-update-windows-intel-gpu/"><u>Enhance Visual Performance: Update Windows Intel GPU</u></a></li>
<li><a href="https://network-issues.techidaily.com/enhancing-visual-content-experience-with-win10/"><u>Enhancing Visual Content Experience with Win10</u></a></li>
<li><a href="https://network-issues.techidaily.com/enhancing-visual-performance-with-intel-update/"><u>Enhancing Visual Performance with Intel Update</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixed-basic-render-drivers-for-win-versions-11-to-7/"><u>Fixed: Basic Render Drivers for Win Versions 11 to 7</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixing-os-hardware-disagreement-nvidia-geforce/"><u>Fixing OS-Hardware Disagreement: Nvidia GeForce</u></a></li>
<li><a href="https://network-issues.techidaily.com/guides-on-fixing-acer-led-displays/"><u>Guides on Fixing Acer LED Displays</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-disabled-apple-iphone-15-proipad-without-computer-drfone-by-drfone-ios/"><u>How to Unlock Disabled Apple iPhone 15 Pro/iPad Without Computer | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-capture-the-best-sound-quality-your-ultimate-guidebook-to-recording-podcasts-via-zoom/"><u>In 2024, Capture the Best Sound Quality  Your Ultimate Guidebook to Recording Podcasts via Zoom</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-celebrating-masterpieces-top-15-outstanding-stop-motion-works/"><u>In 2024, Celebrating Masterpieces  Top 15 Outstanding Stop-Motion Works</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-the-ultimate-guide-to-rapidly-discover-friends/"><u>In 2024, The Ultimate Guide to Rapidly Discover Friends</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-best-spy-watches-for-your-oppo-reno-11f-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Best Spy Watches For your Oppo Reno 11F 5G | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-understanding-instagrams-tunes-and-their-legal-boundaries/"><u>In 2024, Understanding Instagram’s Tunes and Their Legal Boundaries</u></a></li>
<li><a href="https://network-issues.techidaily.com/installation-process-concluded-smoothly-for-nvidia/"><u>Installation Process Concluded Smoothly for NVIDIA</u></a></li>
<li><a href="https://network-issues.techidaily.com/no-compatible-graphics-found-overwatch-update-fixes-issue/"><u>No Compatible Graphics Found - Overwatch Update Fixes Issue</u></a></li>
<li><a href="https://network-issues.techidaily.com/opencl-not-found-fixed-now/"><u>OpenCL Not Found, Fixed Now</u></a></li>
<li><a href="https://network-issues.techidaily.com/opengl-halted-restoration-complete/"><u>OpenGL Halted, Restoration Complete</u></a></li>
<li><a href="https://os-tips.techidaily.com/protect-your-communications-easy-steps-for-archiving-text-messages-on-ios-and-android-phones/"><u>Protect Your Communications: Easy Steps for Archiving Text Messages on iOS & Android Phones</u></a></li>
<li><a href="https://network-issues.techidaily.com/reactivating-silent-gpu-fans/"><u>Reactivating Silent GPU Fans</u></a></li>
<li><a href="https://network-issues.techidaily.com/refresh-windows-sharpen-screens/"><u>Refresh Windows, Sharpen Screens</u></a></li>
<li><a href="https://network-issues.techidaily.com/repaired-failed-gdx-setup-on-pc/"><u>Repaired Failed GDX Setup on PC</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolved-gdx-setup-failure-now-functional-on-ws/"><u>Resolved GDX Setup Failure, Now Functional on WS</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolving-flipped-aspect-ratio-in-display/"><u>Resolving Flipped Aspect Ratio in Display</u></a></li>
<li><a href="https://network-issues.techidaily.com/restoring-transparency-to-win11-screens/"><u>Restoring Transparency to Win11 Screens</u></a></li>
<li><a href="https://tech-haven.techidaily.com/revolutionizing-search-microsofts-new-ai-features-for-bing-explained/"><u>Revolutionizing Search: Microsoft's New AI Features for Bing Explained</u></a></li>
<li><a href="https://network-issues.techidaily.com/streamlining-civ-5-experience-on-computers/"><u>Streamlining Civ 5 Experience on Computers</u></a></li>
<li><a href="https://network-issues.techidaily.com/transform-your-pc-visual-experience-by-updating-intels-graphics-software-in-windows-10/"><u>Transform Your PC Visual Experience by Updating Intel's Graphics Software in Windows 10</u></a></li>
<li><a href="https://extra-information.techidaily.com/unleash-your-creativity-a-guide-to-30-video-inspirations/"><u>Unleash Your Creativity  A Guide to 30 Video Inspirations</u></a></li>
<li><a href="https://network-issues.techidaily.com/1719974620349-update-intel-graphics-3000-driver-for-windows-11-easily/"><u>Update Intel Graphics 3000 Driver for Windows 11. Easily!</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/verify-is-todays-chatgpt-accessible/"><u>Verify: Is Today's ChatGPT Accessible?</u></a></li>
<li><a href="https://network-issues.techidaily.com/win11-easier-screens-on-any-size-device/"><u>Win11: Easier Screens on Any Size Device</u></a></li>
<li><a href="https://network-issues.techidaily.com/windows-11-now-packs-enhanced-driver-for-amds-radeon-hd-6950-gpu/"><u>Windows 11 Now Packs Enhanced Driver for AMD's Radeon HD 6950 GPU</u></a></li>
<li><a href="https://network-issues.techidaily.com/winos-bluescreen-dxgkrnlsys-troubleshooting/"><u>WinOS BlueScreen - dxgkrnl.sys Troubleshooting</u></a></li>
<li><a href="https://network-issues.techidaily.com/winos-interop-issue-addressed/"><u>WinOS Interop Issue Addressed</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111982/7443" target="_top" id="2111982">
  <img src="//a.impactradius-go.com/display-ad/7443-2111982" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111982/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->