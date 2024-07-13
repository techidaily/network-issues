---
title: Enabling Functional State for FreeSync Devices
date: 2024-07-12T01:17:19.524Z
updated: 2024-07-13T01:17:19.524Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: This Article Describes Enabling Functional State for FreeSync Devices
excerpt: This Article Describes Enabling Functional State for FreeSync Devices
keywords: FreeSync Sync Technology,Display Adaptive Refresh Rate,HDR Gaming Performance,Enable Functional State Mode,Nvidia FreeSync Compatible Devices,Freesync Latency Reduction,Optimized Visual Experience on GPUs
thumbnail: https://thmb.techidaily.com/5cb2e70fe5fc4984663e55071f50818b86ad28c6053861679577418a188e88c7.jpg
---

## Enabling Functional State for FreeSync Devices

![](https://images.drivereasy.com/wp-content/uploads/2021/12/freesync-not-supported.jpg)

 FreeSync is an AMD hack that can reduce screen tearing and stuttering. But 6 years after its release, gamers are still complaining about the**FreeSync not working** issue. And for some, their FreeSync monitors even say**FreeSync is not supported** .

 But don’t worry if you’re on the same boat. We’ve gathered most of the working fixes down below. Just try them and get FreeSync working right away.

 Before you start troubleshooting, first**make sure your monitor is AMD FreeSync compatible** . You can find out by checking the product page on the official website.

## Try these fixes

 You might not need to try them all. Simply work your way down until you hit the one that does the charm.

1. [**Try different ports**](#fix1)
2. [**Make sure you have the latest correct drivers**](#fix2)
3. [**Perform a clean boot**](#fix3)
4. [**Check for Windows updates**](#fix4)
5. [**Check the monitor settings**](#fix5)
6. [**Disable Fullscreen optimizations**](#fix6)
7. **[Configure the default GPU](#fix7)**

### Fix 1: Try different ports

 First you should check if it’s a hardware issue by changing to another port. For example, if you’re using HDMI, try DP instead and see how it goes. Note that you’ll need**a HDMI 2.0 or DP 1.2 cable** for FreeSync to work properly. If the other ports work perfectly, you might be looking at a faulty GPU/cable/monitor.

For your reference, here’s what HDMI and DP ports look like:

![](https://images.drivereasy.com/wp-content/uploads/2021/12/graphics-card-hdmi-dp-ports.jpg)

If the problem persists, take a look at the next fix.

### Fix 2: Check the monitor settings

 Some FreeSync monitors require users to**configure this function manually in OSD (on-screen display)** . If you don’t know what OSD is, it’s a jargon for the monitor control panel, where you can change viewing options and adjust general settings like brightness and contrast.

 To bring up OSD, look for**buttons or joysticks** at the bottom or the back of your monitor. You can also refer to the manual and explore the settings. If FreeSync is on by default, do a**factory reset** and see how it goes.

![](https://images.drivereasy.com/wp-content/uploads/2021/12/freesync-osd-dell.jpg)

 If this doesn’t fix the issue, simply continue to the next solution.

### Fix 3: Make sure you have the latest correct drivers

 This issue could also be graphics related. In other words, you could be using**a buggy or outdated graphics driver** . Before you try anything more advanced, first make sure you have the latest correct GPU driver.

 You can update your graphics drivers manually, by visiting the AMD website, finding the latest correct installer and installing step by step. But if you’re not comfortable playing with device drivers, you can use [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) to scan, repair and update all your drivers.

1. [**Download**](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy.
2. Run Driver Easy, then click **Scan Now** . Driver Easy will then scan your computer and detect any problem drivers.  
![](https://images.drivereasy.com/wp-content/uploads/2021/08/scan-now-v5_7_0.jpg)
3. Click **Update All** to automatically download and install the correct version of _all_ the drivers that are missing or out of date on your system.  
 (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  – you’ll be prompted to upgrade when you click Update All. If you don’t want to pay for the Pro version, you can still download and install all the drivers you need with the free version; you just have to download them one at a time, and manually install them, the normal Windows way.)  
![](https://images.drivereasy.com/wp-content/uploads/2021/10/de-update-6700-xt-driver.jpg)

**The Pro version of Driver Easy** comes with _full technical support_ . If you need assistance, please contact **Driver Easy’s support team** at **[support@drivereasy.com](mailto:support@drivereasy.com) .**

 After updating all the drivers, restart your PC and check if FreeSync is working.

 If the latest drivers can’t solve your problem, simply check out the next method. (Or you can follow [this guide](https://tools.techidaily.com/drivereasy/download/) and do a clean reinstallation with DDU.)

### Fix 4:**Perform a clean boot**

 This issue could also indicate a compatibility issue, meaning that some other programs might be conflicting with each other. To rule out this possibility, you can do a clean boot.

1. On your keyboard, press**Win+R** (the Windows logo key and the r key) at the same time to invoke the Run box. Type or paste**msconfig** and click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/11/msconfig-clean-boot-1.jpg)
2. In the pop-up window, navigate to the **Services**  tab and check the box next to **Hide all Microsoft services** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/09/msconfig-hide-all-windows-services.jpg)
3. **Uncheck**  all the services EXCEPT those belong to your hardware manufacturers, such as **Realtek** , **AMD** , **NVIDIA** ,**Logitech** and **Intel** . Then click **OK**  to apply the changes.  
![](https://images.drivereasy.com/wp-content/uploads/2020/09/msconfig-disable-services-except-gpu-audio.jpg)
4. On your keyboard, press **Ctrl** , **Shift**  and **Esc**  at the same time to open Task Manager, then navigate to the **Startup**  tab.  
![](https://images.drivereasy.com/wp-content/uploads/2020/08/task-manager-startup.jpg)
5. One at a time, select any programs you suspect might be interfering, and click **Disable** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/08/task-manager-startup-disable-startup-program.jpg)
6. Restart your PC.

 If FreeSync works after a clean boot, you can root out the offending program by repeating these steps and disabling half of the services every time.

 If this trick doesn’t give you luck, take a look at the next one below.

### Fix 5: Check for Windows update

 You also need to make sure you have the latest patches for your system. Normally this is done automatically by your system, but you can also check if you’re missing any feature updates.

Here’s how:

1. On your keyboard, press**Win+I** (the Windows logo key and the i key) to open the Windows Settings app. Click**Update & Security** .  
![update & security](https://images.drivereasy.com/wp-content/uploads/2020/10/update-security-2.jpg)
2. Click**Check for updates** . Windows will then download and install the available patches. It might take some time (up to 30 mins).  
![](https://images.drivereasy.com/wp-content/uploads/2020/08/windows-security-update-click-check-for-update.jpg)

 To confirm you’ve installed _all_  the system updates, **repeat these steps** until it prompts “You’re up to date” when you click **Check for updates** .

 After installing all the system updates, restart and check if FreeSync is working.

If the issue is still there, simply try the next fix.

### Fix 6: Disable Fullscreen optimizations

 You can try this when FreeSync isn’t working in certain games or programs.

**Fullscreen optimization** is a Windows 10 feature which could improve the overall experience of full screen apps. But according to some users, this feature might be conflicting with FreeSync. You can try to disable it and see if that helps:

1. Right-click the program and select**Properties** .
2. Navigate to the **Compatibility**  tab. Under the **Settings**  section, check the box next to **Disable fullscreen optimizations** . Then click **OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/10/disable-fullscreen-optimizations.jpg)

Now restart the program and check if FreeSync is working.

If this doesn’t help, you can continue to the next method.

### Fix 7: Configure the default GPU

 If your PC has dual GPUs, say an integrated one comes with the CPU and a dedicated one, you might need to**specify the default GPU for your program** . Since FreeSync is currently only compatible with AMD GPUs, besides connecting the monitor to an AMD graphics card, you can also configure the default GPU for the program.

1. At the empty area of your desktop, right-click and select **Display settings** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/10/change-preferred-gpu-1.jpg)
2. Under the **Multiple displays** section, click **Graphics settings** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/10/change-preferred-gpu-2.jpg)
3. Click **Browse**  to specify the file location of the program/game launcher.  
![](https://images.drivereasy.com/wp-content/uploads/2021/12/change-preferred-gpu-3-clean.jpg)
4. Click**Options** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/10/change-preferred-gpu-4.jpg)
5. You’ll see three**graphics preference** . Select the**AMD** one and click**Save** .

Now launch the program/game and check if FreeSync is working.

---

 Hopefully you can now enjoy FreeSync with zero issues. If you have any questions or ideas, feel free to leave your thoughts in the comments below.

* [AMD](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://some-approaches.techidaily.com/updated-symphony-in-softness-playback-reduction-guide/"><u>[Updated] Symphony in Softness  Playback Reduction Guide</u></a></li>
<li><a href="https://network-issues.techidaily.com/correcting-lenovo-screen-brightness-loss/"><u>Correcting Lenovo Screen Brightness Loss</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-studio-technique-breakdown-comprehensive-xvideooverview/"><u>In 2024, Studio Technique Breakdown  Comprehensive XVideoOverview</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-marketers-methods-detecting-illusory-engagement-signals/"><u>[Updated] In 2024, Marketers’ Methods  Detecting Illusory Engagement Signals</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-masterclass-in-cutting-edge-video-editing-vivacuts-2024-insight/"><u>[New] Masterclass in Cutting Edge Video Editing - VivaCut's 2024 Insight</u></a></li>
<li><a href="https://network-issues.techidaily.com/shedding-light-on-inscrutable-x-errors-plaguing-lol/"><u>Shedding Light on Inscrutable X Errors Plaguing LoL</u></a></li>
<li><a href="https://network-issues.techidaily.com/hack-free-gaming-quick-fix-for-legends-crash/"><u>Hack-Free Gaming: Quick Fix for Legends Crash</u></a></li>
<li><a href="https://network-issues.techidaily.com/competitive-edge-how-amd-graphics-drives-winning-performance/"><u>Competitive Edge: How AMD Graphics Drives Winning Performance</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-eternal-vision-recorder-tool/"><u>[Updated] 2024 Approved  Eternal Vision Recorder Tool</u></a></li>
<li><a href="https://network-issues.techidaily.com/bridge-ghost-graphics-discrepancy/"><u>Bridge Ghost Graphics Discrepancy</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-finishing-touch-journalisms-close-call/"><u>2024 Approved  The Finishing Touch  Journalism's Close Call</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-exclusive-reveals-on-securing-high-quality-live-cricket-broadcasting/"><u>[New] Exclusive Reveals on Securing High-Quality Live Cricket Broadcasting</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-unveiling-the-secret-sauce-for-massive-tiktok-content-grabs/"><u>[New] Unveiling the Secret Sauce for Massive TikTok Content Grabs</u></a></li>
<li><a href="https://some-guidance.techidaily.com/transform-videos-for-free-leading-enhancement-pages-for-2024/"><u>Transform Videos for Free  Leading Enhancement Pages for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/restored-tv-viewing-via-hdmi-laptop-connected-successfully/"><u>[Restored] TV Viewing via HDMI, Laptop Connected Successfully</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixed-connectivity-glitches-in-cod-cold-war/"><u>[FIXED] Connectivity Glitches in CoD Cold War</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/024-approved-skyrocket-to-youtube-partner-status-with-10k-vistas-goal/"><u>[New] 2024 Approved  Skyrocket to YouTube Partner Status with 10K Vistas Goal</u></a></li>
<li><a href="https://network-issues.techidaily.com/eliminate-absence-in-sims-screens/"><u>Eliminate Absence in Sims' Screens</u></a></li>
<li><a href="https://network-issues.techidaily.com/direct3d-launch-attempt-failed-fixed/"><u>Direct3D Launch Attempt Failed, Fixed</u></a></li>
<li><a href="https://network-issues.techidaily.com/success-story-overcoming-amds-windows-10-driver-load-hurdle/"><u>Success Story: Overcoming AMD's Windows 10 Driver Load Hurdle</u></a></li>
<li><a href="https://network-issues.techidaily.com/latest-graphics-purchase-blacked-out-monitor/"><u>Latest Graphics Purchase: Blacked-Out Monitor</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-professional-graphics-selecting-between-srgb-and-rgb/"><u>2024 Approved  Professional Graphics  Selecting Between Srgb and Rgb</u></a></li>
<li><a href="https://network-issues.techidaily.com/screenshutdown-window-graphics-ui-fix-exists/"><u>ScreenShutdown, Window Graphics UI (Fix Exists)</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-gag-galore-a-treasury-of-no-cost-memes-for-2024/"><u>[Updated] Gag Galore  A Treasury of No-Cost Memes for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-macbooks-camera-unleashed-recording-made-simple/"><u>2024 Approved  MacBook's Camera Unleashed  Recording Made Simple</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-pivot-to-popularity-mastering-video-flip-on-social-for-2024/"><u>[Updated] Pivot to Popularity  Mastering Video Flip on Social for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/improve-gameplay-speed-in-virtual-construction/"><u>Improve Gameplay Speed in Virtual Construction</u></a></li>
<li><a href="https://network-issues.techidaily.com/flipped-image-remedy-for-windows-display-issue/"><u>Flipped Image Remedy for Window's Display Issue</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-comprehensively-curated-list-15-prime-gear-for-gopro/"><u>2024 Approved  Comprehensively Curated List  15 Prime Gear for GoPro</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcoming-freeze-save-display-issue-resolved/"><u>Overcoming Freeze: Save Display Issue Resolved</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolving-display-setting-failures-on-windows-7-and-10/"><u>Resolving Display Setting Failures on Windows 7 & 10</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-comprehensive-list-of-premier-webinars/"><u>2024 Approved  Comprehensive List of Premier Webinars</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/dissecting-the-language-and-significance-of-pfp-on-tiktok-for-2024/"><u>Dissecting the Language and Significance of 'PFP' On TikTok for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/sidestep-graphics-hiccup-amd/"><u>Sidestep Graphics Hiccup, AMD</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-the-compass-for-content-creators-steering-towards-viral-instagram-success/"><u>[New] The Compass for Content Creators  Steering Towards Viral Instagram Success</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-without-jailbreak-on-nubia-red-magic-8s-proplus-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location without Jailbreak On Nubia Red Magic 8S Pro+ | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-infinix-gt-10-pro-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Infinix GT 10 Pro to New Android? | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/gaming-nightmare-nvidias-rtx-3080-fix-guide/"><u>Gaming Nightmare: Nvidia's RTX 3080 Fix-Guide</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/integrating-language-support-in-igtv-posts-for-2024/"><u>Integrating Language Support in IGTV Posts for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/unleash-your-devices-new-tone-with-top-5-chrome-extensions-for-2024/"><u>Unleash Your Device's New Tone with Top 5 Chrome Extensions for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/clearing-up-windows-11s-streaming-obstacles-successfully/"><u>Clearing Up Windows 11’S Streaming Obstacles Successfully</u></a></li>
<li><a href="https://network-issues.techidaily.com/tackling-graphics-conflict-intel-and-nvidia-fix-on-windows-10-systems/"><u>Tackling Graphics Conflict: Intel & NVIDIA Fix on Windows 10 Systems</u></a></li>
<li><a href="https://network-issues.techidaily.com/non-responsive-lenovo-touchscreen-resolved/"><u>Non-Responsive Lenovo Touchscreen - Resolved</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-leveraging-imovies-power-for-youtube-presence-and-growth/"><u>[Updated] Leveraging IMovie's Power for YouTube Presence and Growth</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-auditory-data-extraction-and-analysis-for-2024/"><u>[Updated] Auditory Data Extraction & Analysis for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-digital-domain-your-playground-for-1000-titles-for-2024/"><u>[New] Digital Domain  Your Playground for 1,000 Titles for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/banishing-buzzing-visuals-from-win7/"><u>Banishing Buzzing Visuals From Win7</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-best-8-mirrorless-cameras-to-elevate-your-vlogging-game-for-2024/"><u>[Updated] Best 8 Mirrorless Cameras to Elevate Your Vlogging Game for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/in-2024-reducing-ambient-acoustic-disturbances-a-guide-to-minimizing-hiss/"><u>In 2024, Reducing Ambient Acoustic Disturbances A Guide to Minimizing Hiss</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolved-winsoft-com-crash/"><u>Resolved WinSOFT COM Crash</u></a></li>
<li><a href="https://network-issues.techidaily.com/ninja-warrior-download-delayed/"><u>Ninja Warrior Download Delayed</u></a></li>
<li><a href="https://network-issues.techidaily.com/strategies-for-controlling-lenovo-screenshake/"><u>Strategies for Controlling Lenovo Screenshake</u></a></li>
<li><a href="https://network-issues.techidaily.com/opengl-quirk-found-and-resolved-in-nvidia-graphics/"><u>OpenGL Quirk Found & Resolved in Nvidia Graphics</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolved-error-22-graphics-driver/"><u>Resolved Error #22, Graphics Driver</u></a></li>
<li><a href="https://network-issues.techidaily.com/restore-cursor-functionality-on-black-screen/"><u>Restore Cursor Functionality on Black Screen</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixed-lost-network-card-on-windows-10-desktop/"><u>[FIXED] Lost Network Card on Windows 10 Desktop</u></a></li>
<li><a href="https://network-issues.techidaily.com/missing-visual-hardware-solve-for-nvidia-gpu-lack-of-visibility/"><u>Missing Visual Hardware: Solve for NVIDIA GPU Lack of Visibility</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-gps-location-on-motorola-edge-40-easily-and-safely-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change GPS Location on Motorola Edge 40 Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/1719974137317-install-latest-intel-hd-graphics-3000-on-windows-10-swiftly/"><u>Install Latest Intel HD Graphics 3000 on Windows 10 Swiftly</u></a></li>
</ul></div>
