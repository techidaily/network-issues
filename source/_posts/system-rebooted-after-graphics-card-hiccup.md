---
title: System Rebooted After Graphics Card Hiccup
date: 2024-07-02T03:24:45.524Z
updated: 2024-07-03T03:24:45.524Z
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
<li><a href="https://network-issues.techidaily.com/nvidia-setup-seamless-installation-achieved/"><u>Nvidia Setup: Seamless Installation Achieved</u></a></li>
<li><a href="https://network-issues.techidaily.com/dxgkrnlsys-error-windows-blue-screen-fix/"><u>dxgkrnl.sys Error: Windows Blue Screen Fix</u></a></li>
<li><a href="https://network-issues.techidaily.com/system-revived-graphics-card-driver-issue-resolved/"><u>System Revived: Graphics Card Driver Issue Resolved</u></a></li>
<li><a href="https://network-issues.techidaily.com/successful-fix-full-screen-windows-in-windows-10-visible-again/"><u>Successful Fix: Full-Screen Windows in Windows 10 Visible Again</u></a></li>
<li><a href="https://network-issues.techidaily.com/efficient-play-speed-up-roblox-pc-game/"><u>Efficient Play: Speed up Roblox PC Game</u></a></li>
<li><a href="https://network-issues.techidaily.com/correcting-the-laptops-sideways-display/"><u>Correcting the Laptop's Sideways Display</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixing-led-backlight-stability-problems/"><u>Fixing LED Backlight Stability Problems</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unveiling-the-magic-crafting-animated-gifs-with-ease/"><u>[New] Unveiling the Magic  Crafting Animated GIFs with Ease</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-harmonious-hues-photographic-pieces-of-lifes-palette/"><u>In 2024, Harmonious Hues  Photographic Pieces of Life's Palette</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-unlocking-the-potential-of-video-posting-within-discords-ecosystem/"><u>[New] Unlocking the Potential of Video Posting Within Discord's Ecosystem</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-in-depth-examination-samsung-gear-360-virtual-reality-lens/"><u>2024 Approved  In-Depth Examination  Samsung Gear 360 Virtual Reality Lens</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-basic-blueprint-for-win-based-fishy-vocal-shifts/"><u>2024 Approved  The Basic Blueprint for Win-Based Fishy Vocal Shifts</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-rapid-fire-guide-to-successful-double-exposures/"><u>[Updated] Rapid-Fire Guide to Successful Double Exposures</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-split-wmv-videos-for-free-top-5-tools-of-the-year-for-2024/"><u>New Split WMV Videos for Free Top 5 Tools of the Year for 2024</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-2024-approved-top-5-apps-to-add-song-to-video/"><u>Updated 2024 Approved Top 5 Apps To Add Song To Video</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-revealing-the-top-6-affordable-web-accessible-tiktok-to-mp3-apps/"><u>[New] In 2024, Revealing the Top 6 Affordable, Web-Accessible TikTok to MP3 Apps</u></a></li>
</ul></div>
