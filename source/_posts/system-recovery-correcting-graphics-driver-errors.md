---
title: "System Recovery: Correcting Graphics Driver Errors"
date: 2024-07-12T00:43:09.142Z
updated: 2024-07-13T00:43:09.142Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: "This Article Describes System Recovery: Correcting Graphics Driver Errors"
excerpt: "This Article Describes System Recovery: Correcting Graphics Driver Errors"
keywords: System Recovery Tools (High Relevance),Graphics Driver Troubleshooting (High Relevance),Fixing Graphics Errors (Medium-High Relevance),Adobe DXG1 Driver Correction (Low Competition),Nvidia Driver Repair (Medium Relevance),GPU Error Resolution (Medium-High Relevance),Display Driver Update Guide (Low Competition),System Recovery,Fix Graphics Errors Using System Recovery (Medium-High Relevance)
thumbnail: https://thmb.techidaily.com/25e355cfe41e9e10950c631e4aa9da16590e30c123d991c0d3d8b6703e367f7f.png
---

## System Recovery: Correcting Graphics Driver Errors

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
<li><a href="https://fake-location.techidaily.com/looking-for-a-location-changer-on-apple-iphone-6s-plus-look-no-further-drfone-by-drfone-virtual-ios/"><u>Looking For A Location Changer On Apple iPhone 6s Plus? Look No Further | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/six-winning-strategies-to-recording-and-saving-mov-on-windows-11-for-2024/"><u>Six Winning Strategies to Recording and Saving .mov on Windows 11 for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/debug-evasive-graphics-cards/"><u>Debug Evasive Graphics Cards</u></a></li>
<li><a href="https://network-issues.techidaily.com/a-comprehensive-guide-to-intel-graphics-enhancements-in-windows-7/"><u>A Comprehensive Guide to Intel Graphics Enhancements in Windows 7</u></a></li>
<li><a href="https://network-issues.techidaily.com/restoring-visuals-after-win10-fall-update/"><u>Restoring Visuals After Win10 Fall Update</u></a></li>
<li><a href="https://network-issues.techidaily.com/banished-bug-mh-worlds-graphics-scare-over/"><u>Banished Bug: MH World's Graphics Scare Over</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-the-loom-chronicles-crafting-visual-stories/"><u>[New] In 2024, The Loom Chronicles  Crafting Visual Stories</u></a></li>
<li><a href="https://network-issues.techidaily.com/essential-steps-for-eradicating-uneven-screen-horizontal-lines/"><u>Essential Steps for Eradicating Uneven Screen Horizontal Lines</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-oppo-a18-to-pc-drfone-by-drfone-android/"><u>How to Screen Mirroring Oppo A18 to PC? | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-simplified-game-recording-setups-for-stardew-villagers/"><u>[Updated] Simplified Game Recording Setups for Stardew Villagers</u></a></li>
<li><a href="https://network-issues.techidaily.com/resetting-settings-to-use-asus-cam/"><u>Resetting Settings to Use Asus Cam</u></a></li>
<li><a href="https://network-issues.techidaily.com/success-unlocked-nvidia-control-center/"><u>Success: Unlocked Nvidia Control Center</u></a></li>
<li><a href="https://network-issues.techidaily.com/quash-whiteout-errors-in-sims/"><u>Quash Whiteout Errors in Sims</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-mac-techniques-to-shorten-instagram-vids/"><u>In 2024, Mac Techniques to Shorten Instagram Vids</u></a></li>
<li><a href="https://network-issues.techidaily.com/systems-silent-spotlight-on-nvidia-how-to-fix/"><u>System's Silent Spotlight on NVIDIA - How to Fix?</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-from-video-to-mp3-the-essential-youtube-audio-download-guide-for-2024/"><u>New From Video to MP3 The Essential YouTube Audio Download Guide for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-pro-slow-motion-selecting-the-best-mobile-camera-apps/"><u>[New] Pro Slow Motion  Selecting the Best Mobile Camera Apps</u></a></li>
<li><a href="https://extra-information.techidaily.com/discover-the-best-5-sd-cards-for-gopro-hero-8-and-7/"><u>Discover the Best 5 SD Cards for GoPro Hero 8 and 7</u></a></li>
<li><a href="https://network-issues.techidaily.com/optimizing-video-views-after-switching-to-win10/"><u>Optimizing Video Views After Switching to Win10</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-leading-av-creators-digital-edition-list/"><u>2024 Approved  Leading AV Creators  Digital Edition List</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-adobe-premiere-pro-2023-a-step-by-step-guide-to-video-import-and-export/"><u>Updated In 2024, Adobe Premiere Pro 2023 A Step-by-Step Guide to Video Import and Export</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-ispoofer-update-on-poco-m6-5g-drfone-by-drfone-virtual-android/"><u>Will iSpoofer update On Poco M6 5G | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-best-voice-chat-apps-for-gamers/"><u>New Best Voice Chat Apps for Gamers</u></a></li>
<li><a href="https://network-issues.techidaily.com/boosted-gaming-experience-nvidia-210-for-win10-os/"><u>Boosted Gaming Experience: NVIDIA 210 for WIN10 OS</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixing-win11-dark-mode-post-creators-fix/"><u>Fixing Win11 Dark Mode Post-Creators Fix</u></a></li>
<li><a href="https://driver-install.techidaily.com/install-hp-laserprinter-p1102w-for-windows-users/"><u>Install HP LaserPrinter P1102w for Windows Users</u></a></li>
<li><a href="https://network-issues.techidaily.com/disentangled-power-management-options/"><u>Disentangled: Power Management Options</u></a></li>
<li><a href="https://network-issues.techidaily.com/display-dilemma-solved-nvidia-stable-now/"><u>Display Dilemma Solved: Nvidia Stable Now</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-pokemon-go-no-gps-signal-heres-every-possible-solution-on-samsung-galaxy-a34-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Pokemon Go No GPS Signal? Heres Every Possible Solution On Samsung Galaxy A34 5G | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/enabling-supported-mode-for-amd-freesync-monitor/"><u>Enabling Supported Mode for AMD FreeSync Monitor</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-successfully-bypass-icloud-activation-lock-from-apple-iphone-14-pro-by-drfone-ios/"><u>In 2024, How to Successfully Bypass iCloud Activation Lock from Apple iPhone 14 Pro</u></a></li>
<li><a href="https://network-issues.techidaily.com/find-missing-display-settings-on-windows-11/"><u>Find Missing Display Settings on Windows 11</u></a></li>
<li><a href="https://network-issues.techidaily.com/troubleshooting-win11-dark-display-update-issue/"><u>Troubleshooting Win11 Dark Display Update Issue</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-unraveling-the-mysteries-of-discord-nitro-benefits-and-acquisition-tactics/"><u>[Updated] In 2024, Unraveling the Mysteries of Discord Nitro - Benefits & Acquisition Tactics</u></a></li>
<li><a href="https://network-issues.techidaily.com/hidden-visual-chipset-restore-nvidia-graphics-recognition/"><u>Hidden Visual Chipset: Restore NVIDIA Graphics Recognition</u></a></li>
<li><a href="https://network-issues.techidaily.com/bursting-through-bandwidth-barriers-in-win1011/"><u>Bursting Through Bandwidth Barriers in Win10/11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/6-methods-to-share-apple-iphone-6-screen-with-pc-drfone-by-drfone-ios/"><u>6 Methods to Share Apple iPhone 6 Screen with PC | Dr.fone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-revolutionize-your-content-a-step-by-step-guide-to-tiktoks-audio-amplification/"><u>[Updated] Revolutionize Your Content  A Step-by-Step Guide to TikTok's Audio Amplification</u></a></li>
</ul></div>
