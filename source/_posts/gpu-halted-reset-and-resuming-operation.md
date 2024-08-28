---
title: GPU Halted, Reset and Resuming Operation
date: 2024-08-27T05:07:16.125Z
updated: 2024-08-28T05:07:16.125Z
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
<li><a href="https://network-issues.techidaily.com/fix-dxgkrnlsys-triggering-winbsod-error/"><u>[Fix]: dxgkrnl.sys Triggering WinBSOD Error</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixed-zoom-camera-not-working-2024-guide/"><u>[Fixed] Zoom Camera Not Working 2024 Guide</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-forging-a-massive-online-following-on-facebook-for-2024/"><u>[New] Forging a Massive Online Following on Facebook for 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-in-2024-innovative-acoustic-link-for-speakers/"><u>[New] In 2024, Innovative Acoustic Link for Speakers</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-interactive-presenters-synopsis-update-8/"><u>[New] In 2024, Interactive Presenter's Synopsis, Update 8</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-navigating-safe-mode-and-pip-features-on-iphone-ipad-and-macos-for-2024/"><u>[New] Navigating Safe Mode and PIP Features on iPhone, iPad & MacOS for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolved-age-of-empires-ii-launch-pc-compatibility-woes/"><u>[RESOLVED] Age of Empires II Launch - PC Compatibility Woes</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-social-media-success-todays-powerful-instagram-tags-for-2024/"><u>[Updated] Social Media Success  Today's Powerful #Instagram Tags for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-astounding-vlogs-start-here-easy-to-create-projects/"><u>2024 Approved  Astounding Vlogs Start Here  Easy-to-Create Projects</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-deciphering-cameras-smart-hdr-features-and-their-impact/"><u>2024 Approved  Deciphering Camera's Smart HDR Features and Their Impact</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/7-top-ways-to-resolve-apple-id-not-active-issue-for-iphone-13-pro-drfone-by-drfone-ios/"><u>7 Top Ways To Resolve Apple ID Not Active Issue For iPhone 13 Pro | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/8-solutions-to-solve-youtube-app-crashing-on-realme-11-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Solutions to Solve YouTube App Crashing on Realme 11 Pro | Dr.fone</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/boost-site-engagement-with-advanced-cookiebot-features/"><u>Boost Site Engagement with Advanced Cookiebot Features</u></a></li>
<li><a href="https://network-issues.techidaily.com/breaking-barrier-amd-succeeds-in-loading-driver-on-win10/"><u>Breaking Barrier: AMD Succeeds in Loading Driver on Win10</u></a></li>
<li><a href="https://network-issues.techidaily.com/debugged-drivers-error-22-fixed/"><u>Debugged: Drivers, ERROR #22 Fixed</u></a></li>
<li><a href="https://network-issues.techidaily.com/display-system-reactivated-post-failure/"><u>Display System Reactivated Post-Failure</u></a></li>
<li><a href="https://network-issues.techidaily.com/easy-to-fix-you-are-not-currently-using-a-display-attached-to-an-nvidia-gpu/"><u>Easy To Fix You Are Not Currently Using a Display Attached to an NVIDIA GPU</u></a></li>
<li><a href="https://network-issues.techidaily.com/eliminating-graphics-drivers-from-minecraft-crash-causes/"><u>Eliminating Graphics Drivers From Minecraft Crash Causes</u></a></li>
<li><a href="https://games-able.techidaily.com/emulator-showdown-which-one-crushes-it-on-raspberry-pi/"><u>Emulator Showdown: Which One Crushes It on Raspberry Pi?</u></a></li>
<li><a href="https://network-issues.techidaily.com/1719974250939-enhance-visual-performance-swiftly-update-your-pcs-intel-gpu-driver-in-w10-today/"><u>Enhance Visual Performance Swiftly: Update Your PC's Intel GPU Driver in W10 Today.</u></a></li>
<li><a href="https://extra-tips.techidaily.com/enhance-your-iphone-footage-from-speed-to-extended-muted-visuals/"><u>Enhance Your iPhone Footage  From Speed to Extended, Muted Visuals</u></a></li>
<li><a href="https://network-issues.techidaily.com/falcons-flight-delayed/"><u>Falcon's Flight Delayed</u></a></li>
<li><a href="https://network-issues.techidaily.com/fix-flaws-in-windows-mgmt-sys-reveal-hidden-nvidia/"><u>Fix Flaws in Windows Mgmt Sys – Reveal Hidden NVIDIA</u></a></li>
<li><a href="https://extra-hints.techidaily.com/from-first-use-to-expertise-a-comprehensive-fcp-guidebook/"><u>From First Use to Expertise  A Comprehensive FCP Guidebook</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/galaxy-f54-5g-tutorial-bypass-lock-screen-security-password-pin-fingerprint-pattern-by-drfone-android-unlock-android-unlock/"><u>Galaxy F54 5G Tutorial - Bypass Lock Screen,Security Password Pin,Fingerprint,Pattern</u></a></li>
<li><a href="https://network-issues.techidaily.com/glitch-bygone-smooth-view-on-dell-monitor/"><u>Glitch Bygone: Smooth View on Dell Monitor</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-effective-are-vpns-in-protecting-chatgpt-data/"><u>How Effective Are VPNs in Protecting ChatGPT Data?</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-icloud-lock-from-iphone-14-pro-max-by-drfone-ios/"><u>How to Bypass iCloud Lock from iPhone 14 Pro Max</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-netflix-location-to-get-more-country-version-on-apple-iphone-6-drfone-by-drfone-virtual-ios/"><u>How to Change Netflix Location to Get More Country Version On Apple iPhone 6 | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-play-hevc-h-265-video-on-xiaomi-13-ultra-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>How to play HEVC H.265 video on Xiaomi 13 Ultra?</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/immediate-pause-screen-capture-steps/"><u>Immediate Pause Screen Capture Steps</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-5-solutions-for-nokia-g42-5g-unlock-without-password-by-drfone-android/"><u>In 2024, 5 Solutions For Nokia G42 5G Unlock Without Password</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-delete-icloud-account-remove-your-apple-id-permanently-on-iphone-12-by-drfone-ios/"><u>In 2024, How To Delete iCloud Account Remove Your Apple ID Permanently On iPhone 12</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-on-demand-acting-rights-form/"><u>In 2024, On-Demand Acting Rights Form</u></a></li>
<li><a href="https://network-issues.techidaily.com/odyssey-optimized-for-odin/"><u>Odyssey Optimized for Odin</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcoming-intellnvidia-graphic-mix-up-in-hybrid-card-on-windows-10/"><u>Overcoming Intell/Nvidia Graphic Mix-Up in Hybrid Card on Windows 10</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcoming-lenovo-monitor-flicker/"><u>Overcoming Lenovo Monitor Flicker</u></a></li>
<li><a href="https://network-issues.techidaily.com/override-solid-color-screen-errors/"><u>Override Solid-Color Screen Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-fixing-errors-in-creating-directx-graphics-hardware-interface/"><u>Resolved: Fixing Errors in Creating DirectX Graphics Hardware Interface</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolving-save-failure-in-systems-display-settings/"><u>Resolving Save Failure in System's Display Settings</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolving-windows-screen-stutter-phenomenon/"><u>Resolving Windows Screen Stutter Phenomenon</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/scheduling-podcast-drops-with-peak-engagement-times-for-2024/"><u>Scheduling Podcast Drops with Peak Engagement Times for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/secure-your-perfect-zoom-experience-no-more-camera-issues/"><u>Secure Your Perfect Zoom Experience, No More Camera Issues!</u></a></li>
<li><a href="https://network-issues.techidaily.com/shed-light-on-dark-lcd-in-lenovo-models/"><u>Shed Light on Dark LCD in Lenovo Models</u></a></li>
<li><a href="https://network-issues.techidaily.com/smooth-screenshot-experience-now/"><u>Smooth Screenshot Experience Now</u></a></li>
<li><a href="https://network-issues.techidaily.com/solving-mirror-effect-displays-in-windows-11-pro/"><u>Solving Mirror Effect Displays in Windows 11 Pro</u></a></li>
<li><a href="https://network-issues.techidaily.com/tackling-resized-window-problems-on-w11/"><u>Tackling Resized Window Problems on W11</u></a></li>
<li><a href="https://network-issues.techidaily.com/tech-trouble-elusive-nvidia-graphics-detected/"><u>Tech Trouble: Elusive NVIDIA Graphics Detected?</u></a></li>
<li><a href="https://network-issues.techidaily.com/unveil-the-hidden-screen-brightness-lenovo/"><u>Unveil the Hidden Screen Brightness, Lenovo</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-do-you-want-to-better-your-video-with-premiere-pro-try-transitions-this-article-will-give-you-10-best-premiere-pro-transitions-and-let-you-know-how-/"><u>Updated Do You Want to Better Your Video with Premiere Pro? Try Transitions. This Article Will Give You 10 Best Premiere Pro Transitions and Let You Know How to Add Transitions in Premiere. Check It Out for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-the-ipogo-get-you-banned-and-how-to-solve-it-on-samsung-galaxy-s23-ultra-drfone-by-drfone-virtual-android/"><u>Will the iPogo Get You Banned and How to Solve It On Samsung Galaxy S23 Ultra | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/win11-screen-fix-no-full-screen-view-detected/"><u>Win11 Screen Fix: No Full-Screen View Detected</u></a></li>
<li><a href="https://network-issues.techidaily.com/zoom-windows-speed-up-overcoming-slow-net-issues/"><u>Zoom Windows Speed Up: Overcoming Slow Net Issues</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->