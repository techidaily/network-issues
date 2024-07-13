---
title: Video Card Recovered After Driver Stall
date: 2024-07-12T00:49:58.519Z
updated: 2024-07-13T00:49:58.519Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: This Article Describes Video Card Recovered After Driver Stall
excerpt: This Article Describes Video Card Recovered After Driver Stall
keywords: Video Card Recovery,Graphics Driver Stall Fixation,GPU Failure Resolution,Overheating Video Card Solution,Cleaning Graphics Card Drivers,Troubleshooting Video Card Issues,Reinstalling Graphics Driver
thumbnail: https://thmb.techidaily.com/482c489aae9be3633db03ca123df50eb46b4ca67b2d63a56b54a85ecacf2cf27.jpg
---

## Video Card Recovered After Driver Stall

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
<li><a href="https://network-issues.techidaily.com/curtailing-flickering-on-microsoft-surface-pro-7/"><u>Curtailing Flickering on Microsoft Surface Pro 7</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-special-features-virtual-location-on-vivo-x-fold-2-drfone-by-drfone-virtual-android/"><u>In 2024, How To Use Special Features - Virtual Location On Vivo X Fold 2? | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/optimizing-game-performance-fix-civ-5-crash/"><u>Optimizing Game Performance: Fix Civ 5 Crash</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-how-to-apply-gaussian-blur-effect-to-videos-in-premiere-pro-for-2024/"><u>New How to Apply Gaussian Blur Effect to Videos In Premiere Pro for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-achieving-depth-in-indoor-vlogging-lighting/"><u>[Updated] In 2024, Achieving Depth in Indoor Vlogging Lighting</u></a></li>
<li><a href="https://network-issues.techidaily.com/error-eradicated-mh-worlds-monster-kingdom-revived/"><u>Error Eradicated: MH World's Monster Kingdom Revived</u></a></li>
<li><a href="https://network-issues.techidaily.com/fasten-intels-graphics-3000-update-for-windows-11/"><u>Fasten Intel's Graphics 3000 Update for Windows 11.</u></a></li>
<li><a href="https://network-issues.techidaily.com/navigate-through-null-detected-find-your-unlisted-graphics-card/"><u>Navigate Through Null Detected: Find Your Unlisted Graphics Card</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-xiaomi-redmi-note-12-5g-drfone-by-drfone-virtual-android/"><u>In 2024, What is the best Pokemon for pokemon pvp ranking On Xiaomi Redmi Note 12 5G? | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/how-to-fix-asus-built-in-camera-not-working/"><u>How to Fix Asus Built-In Camera Not Working</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-do-realme-gt-3-screen-sharing-drfone-by-drfone-android/"><u>In 2024, How To Do Realme GT 3 Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-easily-delete-tiktok-logos-best-watermark-removers/"><u>Updated Easily Delete TikTok Logos Best Watermark Removers</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-mastering-the-art-of-deleting-discord-servers-for-2024/"><u>[Updated] Mastering the Art of Deleting Discord Servers for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/restoring-amd-radeon-r9-driver-functionality-in-w10/"><u>Restoring AMD Radeon R9 Driver Functionality in W10</u></a></li>
<li><a href="https://network-issues.techidaily.com/corrected-warhammer-40000-not-starting-dx12-error/"><u>[CORRECTED] Warhammer 40,000 Not Starting - DX12 Error</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reasons-for-realme-narzo-n55-stuck-on-boot-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Realme Narzo N55 Stuck on Boot Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/gpu-mystery-solved-why-nvidia-isnt-listed-in-device-manager/"><u>GPU Mystery Solved: Why NVIDIA Isn't Listed in Device Manager</u></a></li>
<li><a href="https://network-issues.techidaily.com/escape-from-tarkov-graphics-bug-for-amd-users-quick-fix/"><u>Escape From Tarkov Graphics Bug for AMD Users [Quick Fix]</u></a></li>
<li><a href="https://network-issues.techidaily.com/windows-successfully-installed-gpu-after-errors/"><u>Windows: Successfully Installed GPU After Errors</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-2024-approved-anime-and-music-mixing-up-the-next-big-tiktok-hits/"><u>[Updated] 2024 Approved  Anime and Music  Mixing Up the Next Big TikTok Hits</u></a></li>
<li><a href="https://network-issues.techidaily.com/solutions-to-low-lit-lenovo-laptop-screen-issue/"><u>Solutions to Low-Lit Lenovo Laptop Screen Issue</u></a></li>
<li><a href="https://network-issues.techidaily.com/lenovo-tap-latency-issue-now-fixed/"><u>Lenovo Tap Latency Issue, Now Fixed!</u></a></li>
<li><a href="https://network-issues.techidaily.com/addressing-intermittent-hp-display-flicker/"><u>Addressing Intermittent HP Display Flicker</u></a></li>
<li><a href="https://network-issues.techidaily.com/win10-blue-screen-dxgkrnlsys-troubleshoot/"><u>Win10 Blue Screen - dxgkrnl.sys Troubleshoot</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-2024-approved-macs-best-kept-secrets-top-free-speech-to-text-software-you-need-to-try/"><u>New 2024 Approved Macs Best-Kept Secrets Top Free Speech-to-Text Software You Need to Try</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-recorder-at-zero-free-capture-of-your-android-content/"><u>In 2024, Recorder at Zero  Free Capture of Your Android Content</u></a></li>
<li><a href="https://extra-tips.techidaily.com/start-making-movies-8-best-film-cameras-under-300/"><u>Start Making Movies  8 Best Film Cameras Under $300</u></a></li>
<li><a href="https://network-issues.techidaily.com/laptopayer-screen-ghosted-tv-stays-black/"><u>Laptop'ayer Screen Ghosted, TV Stays Black</u></a></li>
<li><a href="https://network-issues.techidaily.com/quick-eradicate-white-blankness/"><u>Quick Eradicate White Blankness</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/pokemon-go-error-12-failed-to-detect-location-on-tecno-spark-20-drfone-by-drfone-virtual-android/"><u>Pokemon Go Error 12 Failed to Detect Location On Tecno Spark 20? | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolving-direct3d-launch-problem/"><u>Resolving Direct3D Launch Problem</u></a></li>
<li><a href="https://network-issues.techidaily.com/ending-nvidia-driver-conflict-on-windows-11/"><u>Ending Nvidia Driver Conflict on Windows 11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-unleash-your-seo-potential-explore-the-most-effective-7-free-video-tags-extractors/"><u>2024 Approved  Unleash Your SEO Potential  Explore the Most Effective 7 Free Video Tags Extractors</u></a></li>
<li><a href="https://network-issues.techidaily.com/optimize-display-alignment-on-desktops/"><u>Optimize Display Alignment on Desktops</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-the-undisclosed-secrets-to-growth-on-social-media/"><u>[New] The Undisclosed Secrets to Growth on Social Media</u></a></li>
<li><a href="https://network-issues.techidaily.com/operating-system-update-resolves-opengl-error/"><u>Operating System Update Resolves OpenGL Error</u></a></li>
<li><a href="https://network-issues.techidaily.com/enhance-your-pcs-web-pace-with-win1011-fixes/"><u>Enhance Your PC's Web Pace with Win10/11 Fixes</u></a></li>
<li><a href="https://network-issues.techidaily.com/the-step-by-step-guide-to-uninstalling-gpus-on-win/"><u>The Step-by-Step Guide to Uninstalling GPUs on Win</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-how-to-get-discord-partner-and-be-verified/"><u>2024 Approved  How To Get Discord Partner And Be Verified</u></a></li>
</ul></div>
