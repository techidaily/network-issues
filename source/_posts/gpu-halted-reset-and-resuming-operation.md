---
title: GPU Halted, Reset and Resuming Operation
date: 2024-07-12T01:00:40.734Z
updated: 2024-07-13T01:00:40.734Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: This Article Describes GPU Halted, Reset and Resuming Operation
excerpt: This Article Describes GPU Halted, Reset and Resuming Operation
keywords: GPU Failure Recovery,Graphics Card Reset Troubleshooting,Stop GPU Error Resolution,GPU Halted Solution,Resuming GPU Operation Guide,Hardware Interruption and Reinitialization,System Restart After GPU Halt
thumbnail: https://thmb.techidaily.com/8e227e065d730938ce0d6ea2261402d78760be14848998b4f825537e8b545d45.jpg
---

## GPU Halted, Reset and Resuming Operation

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
<li><a href="https://change-location.techidaily.com/in-2024-how-to-fix-pokemon-go-route-not-working-on-xiaomi-redmi-note-12-pro-4g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Pokemon Go Route Not Working On Xiaomi Redmi Note 12 Pro 4G? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/hard-resetting-an-samsung-galaxy-s24plus-device-made-easy-drfone-by-drfone-reset-android-reset-android/"><u>Hard Resetting an Samsung Galaxy S24+ Device Made Easy | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-2-ways-to-monitor-xiaomi-civi-3-activity-drfone-by-drfone-virtual-android/"><u>In 2024, 2 Ways to Monitor Xiaomi Civi 3 Activity | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/restoring-correct-win10-screen-size/"><u>Restoring Correct Win10 Screen Size</u></a></li>
<li><a href="https://network-issues.techidaily.com/display-issue-amdnvidia-missing-cards/"><u>Display Issue: AMD/NVIDIA Missing Cards</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcome-windows-10-expanded-view-errors/"><u>Overcome Windows 10 Expanded View Errors</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/want-to-create-a-stunning-intro-video-on-your-smartphone-legend-intro-maker-is-a-popular-choice-learn-the-steps-to-design-intro-video-legend-intro-maker-for/"><u>Want to Create a Stunning Intro Video on Your Smartphone? Legend Intro Maker Is a Popular Choice. Learn the Steps to Design Intro Video Legend Intro Maker for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/ultimate-roguelike-rankings-the-best-10-games-for-2024/"><u>Ultimate Roguelike Rankings  The Best 10 Games for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-mastering-instagram-video-editing-tips-with-fcpx/"><u>In 2024, Mastering Instagram  Video Editing Tips with FCPX</u></a></li>
<li><a href="https://network-issues.techidaily.com/excellent-display-quality-now-windows-10/"><u>Excellent Display Quality Now, Windows 10</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-be-a-guest-in-the-digital-arena-tips-for-live-viewers/"><u>2024 Approved  Be a Guest in the Digital Arena  Tips for Live Viewers</u></a></li>
<li><a href="https://network-issues.techidaily.com/solution-found-windows-1110-no-amd-adapter-error/"><u>[SOLUTION FOUND] Windows 11/10 No AMD Adapter Error</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolving-windows-7-inverted-display-issue/"><u>Resolving Windows 7 Inverted Display Issue</u></a></li>
<li><a href="https://network-issues.techidaily.com/eliminated-stretching-effect-from-wide-windows-10/"><u>Eliminated Stretching Effect From Wide Windows 10</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcoming-failed-driver-load-of-amd-in-windows-10-os/"><u>Overcoming Failed Driver Load of AMD in Windows 10 OS</u></a></li>
<li><a href="https://screen-capture.techidaily.com/11-ranked-audio-recorders-of-the-year/"><u>11 Ranked Audio Recorders of the Year</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolving-discrepancy-in-windows-7-screen-reversal/"><u>Resolving Discrepancy in Windows 7 Screen Reversal</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-what-does-instantaneous-video-removal-mean-for-user-privacy/"><u>[Updated] What Does Instantaneous Video Removal Mean for User Privacy?</u></a></li>
<li><a href="https://network-issues.techidaily.com/win11-flicker-phenomenon-no-more/"><u>Win11 Flicker Phenomenon, No More!</u></a></li>
<li><a href="https://review-topics.techidaily.com/remove-frp-lock-on-red-magic-9-proplus-by-drfone-android-unlock-remove-google-frp/"><u>Remove FRP Lock on Red Magic 9 Pro+</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-the-ultimate-check-comparing-bandicams-performance-to-competitors/"><u>[Updated] In 2024, The Ultimate Check  Comparing Bandicam's Performance to Competitors</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-integrating-advanced-movie-capture-on-diverse-tech-environments/"><u>In 2024, Integrating Advanced Movie Capture on Diverse Tech Environments</u></a></li>
<li><a href="https://network-issues.techidaily.com/core-i9-pc-lacks-graphics-acceleration/"><u>Core I9 PC Lacks Graphics Acceleration</u></a></li>
<li><a href="https://network-issues.techidaily.com/stop-vertical-distortion-phenomena/"><u>Stop Vertical Distortion Phenomena</u></a></li>
<li><a href="https://network-issues.techidaily.com/gpu-correction-error-43-overcome/"><u>GPU Correction - Error 43 Overcome</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-finalcut-pro-elevating-your-youtube-edits-from-good-to-great/"><u>In 2024, FinalCut Pro  Elevating Your YouTube Edits From Good to Great</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-how-to-upload-a-video-to-instagram-from-a-desktop/"><u>[New] In 2024, How to Upload a Video to Instagram From a Desktop</u></a></li>
<li><a href="https://network-issues.techidaily.com/god-of-thunder-overhaul-complete/"><u>God of Thunder Overhaul Complete</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-learn-how-to-lock-stolen-your-apple-iphone-15-plus-properly-by-drfone-ios/"><u>In 2024, Learn How To Lock Stolen Your Apple iPhone 15 Plus Properly</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/the-insiders-guide-to-preserving-your-spotify-collection-in-local-formats/"><u>The Insiders Guide to Preserving Your Spotify Collection in Local Formats</u></a></li>
<li><a href="https://network-issues.techidaily.com/tilting-trouble-no-more-fixed/"><u>Tilting Trouble No More [Fixed]</u></a></li>
<li><a href="https://network-issues.techidaily.com/how-to-update-intel-hd-graphics-drivers-on-windows/"><u>How to Update Intel HD Graphics Drivers on Windows</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixing-no-display-choices-in-nvidia-control-panel/"><u>Fixing No Display Choices in NVIDIA Control Panel</u></a></li>
<li><a href="https://network-issues.techidaily.com/corrected-display-only-partial-windows-on-monitor-windows-10/"><u>Corrected Display - Only Partial Windows on Monitor (Windows 10)</u></a></li>
<li><a href="https://network-issues.techidaily.com/gained-ground-in-nvidia-admin-interface/"><u>Gained Ground in Nvidia Admin Interface</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-the-ultimate-7-fps-gaming-list-for-2024/"><u>[Updated] The Ultimate 7 FPS Gaming List for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/restoring-clear-windows-10-displays/"><u>Restoring Clear Windows 10 Displays</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-mastering-pip-features-on-ms-edge-for-2024/"><u>[Updated] Mastering PIP Features on MS Edge for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolving-inverted-view-in-windows-10-display/"><u>Resolving Inverted View in Windows 10 Display</u></a></li>
<li><a href="https://network-issues.techidaily.com/how-to-activate-and-install-an-external-wireless-adapter-on-pcs/"><u>How To Activate & Install an External Wireless Adapter on PCs</u></a></li>
<li><a href="https://network-issues.techidaily.com/correcting-the-laptops-sideways-display/"><u>Correcting the Laptop's Sideways Display</u></a></li>
<li><a href="https://network-issues.techidaily.com/turbo-anthem-sidestep-hiccups/"><u>Turbo Anthem: Sidestep Hiccups</u></a></li>
<li><a href="https://network-issues.techidaily.com/qualcomm-atheros-qca61x4-driver-compatibility-in-win10/"><u>Qualcomm Atheros QCA61x4 Driver Compatibility in Win10</u></a></li>
<li><a href="https://network-issues.techidaily.com/windows-10-black-screen-with-cursor-solved/"><u>Windows 10 Black Screen with Cursor [SOLVED]</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-unlock-hd-potential-for-your-social-media-platform-fb/"><u>[Updated] Unlock HD Potential for Your Social Media Platform (FB)</u></a></li>
<li><a href="https://network-issues.techidaily.com/step-in-to-windows-8s-secure-environment-graphics-driver-detachment/"><u>Step-In-To Windows 8’S Secure Environment: Graphics Driver Detachment</u></a></li>
<li><a href="https://network-issues.techidaily.com/direct3d-acceleration-not-available-solved/"><u>Direct3D Acceleration Not Available [SOLVED]</u></a></li>
<li><a href="https://network-issues.techidaily.com/troubleshooting-pro-7-screen-fluctuations/"><u>Troubleshooting Pro 7 Screen Fluctuations</u></a></li>
<li><a href="https://network-issues.techidaily.com/reactivating-supported-mode-on-amd-freesync/"><u>Reactivating Supported Mode on AMD FreeSync</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-web-plus-add-on-fb-story-capture-tool/"><u>2024 Approved  Web + Add-On  FB Story Capture Tool</u></a></li>
<li><a href="https://network-issues.techidaily.com/system-sync-fixed-successfully/"><u>System Sync Fixed Successfully</u></a></li>
<li><a href="https://network-issues.techidaily.com/winspeed-boost-for-laggy-wifi-on-win/"><u>WinSpeed Boost for Laggy WiFi on WIN</u></a></li>
<li><a href="https://network-issues.techidaily.com/controlling-big-screen-size-in-win10/"><u>Controlling Big Screen Size in Win10</u></a></li>
<li><a href="https://network-issues.techidaily.com/solutions-for-quashing-lenovo-flashes/"><u>Solutions for Quashing Lenovo Flashes</u></a></li>
<li><a href="https://howto.techidaily.com/11-ways-to-fix-it-when-my-xiaomi-13-ultra-wont-charge-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Ways to Fix it When My Xiaomi 13 Ultra Wont Charge | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/win11-display-glitch-resolved/"><u>Win11 Display Glitch Resolved</u></a></li>
<li><a href="https://network-issues.techidaily.com/eliminating-low-brightness-lenovo-issue/"><u>Eliminating Low-Brightness Lenovo Issue</u></a></li>
<li><a href="https://network-issues.techidaily.com/revealing-disappearing-monitor-ghosts/"><u>Revealing Disappearing Monitor Ghosts</u></a></li>
</ul></div>
