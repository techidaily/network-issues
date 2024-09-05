---
title: "System Revived: Graphics Card Driver Issue Resolved"
date: 2024-09-04T12:03:17.906Z
updated: 2024-09-05T12:03:17.906Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: "This Article Describes System Revived: Graphics Card Driver Issue Resolved"
excerpt: "This Article Describes System Revived: Graphics Card Driver Issue Resolved"
keywords: Graphics Card Driver Fix,Resolved GPU Problems,Updated Nvidia/AMD Drivers,Improved System Performance,Troubleshooting Graphic Issues,Fixed Display Errors,Optimized Graphics Hardware
thumbnail: https://thmb.techidaily.com/92f2629e0a1f1e2f3516b5bfb12e18e1391be680411487e21618499fabf10e50.jpg
---

## System Revived: Graphics Card Driver Issue Resolved

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
<li><a href="https://network-issues.techidaily.com/corrected-wolfenstein-2-no-start-windows-compatibility/"><u>[CORRECTED] Wolfenstein 2 No Start - Windows Compatibility</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixed-cod-cold-war-restoring-online-playability/"><u>[FIXED] CoD Cold War - Restoring Online Playability</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-a-beginners-roadmap-to-professional-video-sound-recording/"><u>[New] 2024 Approved  A Beginner's Roadmap to Professional Video Sound Recording</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-improve-your-videography-the-itunes-way/"><u>[New] 2024 Approved  Improve Your Videography  The iTunes Way</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-how-to-effortlessly-record-movies-on-win10/"><u>[Updated] 2024 Approved  How to Effortlessly Record Movies on Win10</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-collaborative-screen-recording/"><u>[Updated] Collaborative Screen Recording</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-pinnacle-pathfinders-the-ultimate-10-game-guide-for-2024/"><u>[Updated] Pinnacle Pathfinders  The Ultimate 10 Game Guide for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-top-mac-studio-for-exceptional-video-and-audiophile-recordings/"><u>[Updated] Top Mac Studio for Exceptional Video & Audiophile Recordings</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-unhackable-blueprint-for-inserting-your-tiktok-links/"><u>[Updated] Unhackable Blueprint for Inserting Your TikTok Links</u></a></li>
<li><a href="https://games-able.techidaily.com/a-deep-dive-no-disc-drive-for-next-gen-gaming-consoles/"><u>A Deep Dive: No Disc Drive for Next-Gen Gaming Consoles</u></a></li>
<li><a href="https://tech-haven.techidaily.com/boost-productivity-streamline-writing-with-hix-ai-and-gpt-4/"><u>Boost Productivity: Streamline Writing with HIX AI & GPT-4</u></a></li>
<li><a href="https://network-issues.techidaily.com/clearing-up-your-youtube-video-bugs-green-screen-edition/"><u>Clearing Up Your YouTube Video Bugs: Green Screen Edition</u></a></li>
<li><a href="https://network-issues.techidaily.com/decrease-delay-duration-in-pc-based-gaming/"><u>Decrease Delay Duration in PC-Based Gaming</u></a></li>
<li><a href="https://network-issues.techidaily.com/direct2d-not-active-armor-applied/"><u>Direct2D Not Active, Armor Applied</u></a></li>
<li><a href="https://network-issues.techidaily.com/eliminate-screen-flicker-easily/"><u>Eliminate Screen Flicker Easily</u></a></li>
<li><a href="https://network-issues.techidaily.com/eliminate-screen-flicker-with-easy-fixes/"><u>Eliminate Screen Flicker with Easy Fixes</u></a></li>
<li><a href="https://network-issues.techidaily.com/enhancing-windows-10-screen-image-flip-fix/"><u>Enhancing Windows 10 Screen Image Flip Fix</u></a></li>
<li><a href="https://network-issues.techidaily.com/error-fixed-nvidia-related-stoppage-in-windows-os/"><u>Error Fixed: Nvidia-Related Stoppage in Windows OS</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixing-ghostly-video-interruptions/"><u>Fixing Ghostly Video Interruptions</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixing-windows-10-nvidiaintel-graphic-card-compatibility-issue/"><u>Fixing Windows 10: NVIDIA/Intel Graphic Card Compatibility Issue</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixing-windows-10s-erroneous-code-c1900101/"><u>Fixing Windows 10'S Erroneous Code: C1900101</u></a></li>
<li><a href="https://network-issues.techidaily.com/graphic-resolution-achieved-post-error-normalization/"><u>Graphic Resolution Achieved: Post-Error Normalization</u></a></li>
<li><a href="https://network-issues.techidaily.com/graphics-glitch-repair-complete/"><u>Graphics Glitch Repair Complete</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-pc-to-apple-iphone-11-pro-max-drfone-by-drfone-ios/"><u>How to Mirror PC to Apple iPhone 11 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-apple-id-is-greyed-out-on-iphone-se-2020-how-to-bypass-by-drfone-ios/"><u>In 2024, Apple ID is Greyed Out On iPhone SE (2020) How to Bypass?</u></a></li>
<li><a href="https://network-issues.techidaily.com/methods-to-stop-hp-screen-blinking/"><u>Methods to Stop HP Screen Blinking</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/perfecting-synchronized-recording-webcam-plus-display-techniques-for-2024/"><u>Perfecting Synchronized Recording  Webcam + Display Techniques for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/quelling-quivering-windows-7-graphics/"><u>Quelling Quivering Windows 7 Graphics</u></a></li>
<li><a href="https://network-issues.techidaily.com/rectified-stretched-screens-on-windows-os/"><u>Rectified Stretched Screens on Windows OS</u></a></li>
<li><a href="https://network-issues.techidaily.com/removing-inverted-image-feature-from-w11/"><u>Removing Inverted Image Feature From W11</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolving-display-settings-save-issue/"><u>Resolving Display Settings Save Issue</u></a></li>
<li><a href="https://network-issues.techidaily.com/reversing-black-screen-phenomenon-in-portables/"><u>Reversing Black Screen Phenomenon in Portables</u></a></li>
<li><a href="https://network-issues.techidaily.com/streamlining-radeon-r9-integration-in-newest-win11/"><u>Streamlining Radeon R9 Integration in Newest Win11</u></a></li>
<li><a href="https://network-issues.techidaily.com/tackled-screen-resizing-quirks-in-window-10/"><u>Tackled Screen Resizing Quirks in Window 10</u></a></li>
<li><a href="https://network-issues.techidaily.com/the-evolution-and-relevance-of-4k-uhd-video/"><u>The Evolution and Relevance of 4K UHD Video</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/top-rated-wireless-routers-with-extended-range-2024-edition/"><u>Top Rated Wireless Routers with Extended Range - 2024 Edition</u></a></li>
<li><a href="https://network-issues.techidaily.com/win-updates-microsofts-drive-fixed-in-bd-version/"><u>Win Updates: Microsoft's DRIVE Fixed in BD Version</u></a></li>
<li><a href="https://network-issues.techidaily.com/windows-10-and-qualcomm-adapter-wireless-unity/"><u>Windows 10 & Qualcomm Adapter: Wireless Unity</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896532/19272" target="_top" id="1896532">
  <img src="//a.impactradius-go.com/display-ad/19272-1896532" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896532/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->