---
title: GPU Driver Crash Averted, Now Working Fine
date: 2024-07-12T00:14:15.309Z
updated: 2024-07-13T00:14:15.309Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: This Article Describes GPU Driver Crash Averted, Now Working Fine
excerpt: This Article Describes GPU Driver Crash Averted, Now Working Fine
keywords: GPU Driver Update,Graphics Card Recovery,GPU Performance Optimization,System Stability Improvement,Hardware Glitch Resolution,Computer Driver Fix,Crash Prevention Tips
thumbnail: https://thmb.techidaily.com/0d6a66026bc293d990118e0e33da7d0a3d5bf37cd742dae54e5c6356e3964e9a.jpg
---

## GPU Driver Crash Averted, Now Working Fine

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
<li><a href="https://network-issues.techidaily.com/visual-configuration-saved-and-fixed/"><u>Visual Configuration Saved & Fixed</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-audio-blending-techniques-creating-a-unified-soundtrack-for-videos/"><u>2024 Approved Audio Blending Techniques Creating a Unified Soundtrack for Videos</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-top-10-yt-tickets-most-watched-videos-hour-by-hour/"><u>2024 Approved  Top 10 YT Tickets  Most Watched Videos, Hour by Hour</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-easy-solutions-to-hard-reset-oppo-reno-11f-5g-drfone-by-drfone-reset-android-reset-android/"><u>3 Easy Solutions to Hard Reset Oppo Reno 11F 5G | Dr.fone</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-key-considerations-to-put-together-an-invaluable-audiovisual-treasure-trove-on-youtube/"><u>New 2024 Approved Key Considerations to Put Together an Invaluable Audiovisual Treasure Trove on YouTube</u></a></li>
<li><a href="https://network-issues.techidaily.com/uninterrupted-adventure-fixing-fallout-4-pc-issues/"><u>Uninterrupted Adventure: Fixing Fallout 4 PC Issues</u></a></li>
<li><a href="https://network-issues.techidaily.com/improve-windows-graphics-by-installing-current-intel-drivers/"><u>Improve Windows Graphics by Installing Current Intel Drivers</u></a></li>
<li><a href="https://network-issues.techidaily.com/mastering-zoom-cameras-common-fixes-and-solutions/"><u>Mastering Zoom Cameras: Common Fixes and Solutions</u></a></li>
<li><a href="https://network-issues.techidaily.com/dampening-discoloration-in-win7-output/"><u>Dampening Discoloration in Win7 Output</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-superior-free-reproduction-tools-for-switch-games/"><u>2024 Approved  Superior Free Reproduction Tools for Switch Games</u></a></li>
<li><a href="https://network-issues.techidaily.com/banish-display-defects-in-windows/"><u>Banish Display Defects in Windows</u></a></li>
<li><a href="https://network-issues.techidaily.com/overhauling-amd-radeon-r9-driver-stability-in-w10/"><u>Overhauling AMD Radeon R9 Driver Stability in W10</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-conquer-the-clutter-learn-bg-erasure-in-figma-designs/"><u>2024 Approved  Conquer the Clutter  Learn BG Erasure in Figma Designs</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-lava-blaze-curve-5g-system-crash-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Lava Blaze Curve 5G System Crash Issue | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/11-proven-solutions-to-fix-google-play-store-not-working-issue-on-xiaomi-redmi-note-12-pro-4g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Proven Solutions to Fix Google Play Store Not Working Issue on Xiaomi Redmi Note 12 Pro 4G | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-lost-data-of-iphone-11-pro-max-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Lost Data of iPhone 11 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/blackout-blunder-with-latest-graphics-card/"><u>Blackout Blunder with Latest Graphics Card</u></a></li>
<li><a href="https://network-issues.techidaily.com/uninterrupted-video-experience-post-windows-10-upgrade/"><u>Uninterrupted Video Experience Post-Windows 10 Upgrade</u></a></li>
<li><a href="https://network-issues.techidaily.com/clearing-up-blurry-textures-in-far-cry-6-gameplay/"><u>Clearing Up Blurry Textures in Far Cry 6 Gameplay</u></a></li>
<li><a href="https://network-issues.techidaily.com/recovered-lost-wi-fi-adapter-on-latest-os/"><u>[RECOVERED] Lost Wi-Fi Adapter on Latest OS</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-top-picks-for-the-ultimate-offline-game-experience-on-android-for-2024/"><u>[Updated] Top Picks for the Ultimate Offline Game Experience on Android for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/solved-quick-flicker-on-dell-display/"><u>[Solved] Quick Flicker on Dell Display</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-a-guide-for-mobile-filmmakers-on-crafting-youtube-thumbnails/"><u>In 2024, A Guide for Mobile Filmmakers on Crafting YouTube Thumbnails</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-tailor-made-youtube-closings-how-to-get-them-right/"><u>[Updated] Tailor-Made YouTube Closings  How to Get Them Right</u></a></li>
<li><a href="https://network-issues.techidaily.com/ending-dark-windows-display-post-update/"><u>Ending Dark Windows Display Post-Update</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-siri-voice-changer-how-to-change-siri-voice-on-iphone-ipad-or-mac-in-2024/"><u>Updated Siri Voice Changer How to Change Siri Voice on iPhone, iPad or Mac, In 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-the-ultimate-fcp-x-shortcut-adding-effects-in-3-steps-or-less-for-2024/"><u>New The Ultimate FCP X Shortcut Adding Effects in 3 Steps or Less for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-8-best-5k-monitors-for-you/"><u>2024 Approved  8 Best 5K Monitors for You</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-a-step-by-step-guide-share-youtube-vids-with-fb-friends/"><u>2024 Approved  A Step-by-Step Guide  Share YouTube Vids with FB Friends</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-deciphering-instagram-stories-what-youre-not-seeing-as-a-viewer/"><u>2024 Approved  Deciphering Instagram Stories  What You're Not Seeing as a Viewer</u></a></li>
<li><a href="https://network-issues.techidaily.com/hassle-free-intel-graphics-3000-win11-upgrade/"><u>Hassle-Free Intel Graphics 3000 Win11 Upgrade</u></a></li>
<li><a href="https://network-issues.techidaily.com/revamping-bdr-for-win-versions-11-to-7/"><u>Revamping BDR for Win Versions 11 to 7</u></a></li>
<li><a href="https://network-issues.techidaily.com/display-fixed-repaired-nvidia-driver-failure/"><u>Display Fixed: Repaired NVidia Driver Failure</u></a></li>
<li><a href="https://network-issues.techidaily.com/solved-stretched-screen-issues-for-windows-10/"><u>[Solved] Stretched Screen Issues for Windows 10</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-pokemon-emerald-master-ball-cheat-on-vivo-y28-5g-drfone-by-drfone-virtual-android/"><u>How to Use Pokémon Emerald Master Ball Cheat On Vivo Y28 5G | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-quantifying-videography-storage-needs-128gb/"><u>[New] Quantifying Videography Storage Needs, 128GB</u></a></li>
<li><a href="https://network-issues.techidaily.com/solution-found-black-ops-cold-war-launch-xbox-trouble/"><u>[SOLUTION FOUND] Black Ops Cold War Launch - Xbox Trouble</u></a></li>
<li><a href="https://network-issues.techidaily.com/nvidia-boosts-geforce-210-performance-on-win10-os/"><u>NVIDIA Boosts GeForce 210 Performance on WIN10 OS</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-apple-iphone-11-pro-max-by-drfone-ios/"><u>How to Unlock Apple iPhone 11 Pro Max?</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixing-absent-display-preferences-on-nvidia-graphics/"><u>Fixing Absent Display Preferences on Nvidia Graphics</u></a></li>
<li><a href="https://network-issues.techidaily.com/repaired-addressing-the-internet-disconnect-in-cod-cold-war/"><u>[REPAIRED] Addressing the Internet Disconnect in CoD Cold War</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixing-no-compatible-graphics-overwatch-update-resolved/"><u>Fixing No Compatible Graphics: Overwatch Update Resolved</u></a></li>
<li><a href="https://network-issues.techidaily.com/wi-fi-driver-uninstalled-reinstate-windows-10-card/"><u>Wi-Fi Driver Uninstalled? Reinstate Windows 10 Card</u></a></li>
<li><a href="https://network-issues.techidaily.com/solving-hp-display-dimming-troubles/"><u>Solving HP Display Dimming Troubles</u></a></li>
<li><a href="https://network-issues.techidaily.com/nvidia-carrier-lacking-dx-acceleration/"><u>Nvidia Carrier Lacking DX Acceleration</u></a></li>
</ul></div>
