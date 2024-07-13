---
title: Fixing Problems With AMD FreeSync Support
date: 2024-07-12T00:11:56.478Z
updated: 2024-07-13T00:11:56.478Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: This Article Describes Fixing Problems With AMD FreeSync Support
excerpt: This Article Describes Fixing Problems With AMD FreeSync Support
keywords: AMD FreeSync,FreeSync Troubleshooting,AMD FreeSync Support Guide,FreeSync Display Sync Issues,Fixing FreeSync Problems,AMD FreeSync Performance Optimization,FreeSync Compatibility Tips
thumbnail: https://thmb.techidaily.com/03b9d4f25f53b702691684fe2aacadda124f8e51ce8909742113d79362ddfedd.jpg
---

## Fixing Problems With AMD FreeSync Support

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
<li><a href="https://network-issues.techidaily.com/no-video-display-laptop-to-tv-hdmi-misalignment/"><u>No Video Display - Laptop to TV HDMI Misalignment</u></a></li>
<li><a href="https://network-issues.techidaily.com/remedy-for-reversed-screens-on-windows-10/"><u>Remedy for Reversed Screens on Windows 10</u></a></li>
<li><a href="https://network-issues.techidaily.com/tackling-c1900101-in-new-windows-installation/"><u>Tackling C1900101 in New Windows Installation</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/how-to-end-your-youtube-void-top-10-insights-on-igniting-video-interest-for-2024/"><u>How To End Your Youtube Void  Top 10 Insights on Igniting Video Interest for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/enhance-networking-adding-a-wireless-lan-card-in-windowsmacos/"><u>Enhance Networking: Adding a Wireless LAN Card in Windows/macOS</u></a></li>
<li><a href="https://network-issues.techidaily.com/master-flat-panel-fixation-methods/"><u>Master Flat-Panel Fixation Methods</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-mkvtoolnix-for-mac-an-easy-editing-application-for-all-mac-users/"><u>New In 2024, MKVtoolnix for Mac An Easy Editing Application for All Mac Users</u></a></li>
<li><a href="https://network-issues.techidaily.com/dell-visuals-smooth-out-after-repair/"><u>Dell Visuals Smooth Out After Repair</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-windows-leading-video-chat-pros-top-8-for-2024/"><u>[New] Windows' Leading Video Chat Pros  Top 8 for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-pioneering-tiktok-creations-with-foundational-tools/"><u>[Updated] 2024 Approved  Pioneering TikTok Creations with Foundational Tools</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-elevating-live-tiktok-content-via-zoom/"><u>2024 Approved  Elevating Live TikTok Content via Zoom</u></a></li>
<li><a href="https://network-issues.techidaily.com/remedying-gpu-fan-non-operational-state/"><u>Remedying GPU Fan Non-Operational State</u></a></li>
<li><a href="https://network-issues.techidaily.com/1719974606177-lenovo-tap-latency-issue-now-fixed/"><u>Lenovo Tap Latency Issue, Now Fixed</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/comprehensive-fb-video-ad-execution-manual/"><u>Comprehensive FB Video Ad Execution Manual</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-in-2024-the-essential-blueprint-for-configuring-a-zoom-space/"><u>[New] In 2024, The Essential Blueprint for Configuring a Zoom Space</u></a></li>
<li><a href="https://network-issues.techidaily.com/monitor-unresponsive-to-new-graphics-card/"><u>Monitor Unresponsive to New Graphics Card</u></a></li>
<li><a href="https://some-techniques.techidaily.com/infographic-dji-mavic-air-vs-dji-spark-a-gamer-changer-again-in-2024/"><u>[Infographic] DJI Mavic Air Vs. DJI Spark - A Gamer Changer Again, In 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/how-to-tackle-persistent-video-output-errors/"><u>How to Tackle Persistent Video Output Errors</u></a></li>
<li><a href="https://network-issues.techidaily.com/turning-upside-down-screen-rightside-up/"><u>Turning Upside-Down Screen Rightside Up</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-how-to-zoom-in-on-powerpoint-easy-ways/"><u>New How to Zoom in on PowerPoint Easy Ways</u></a></li>
<li><a href="https://network-issues.techidaily.com/nvidia-driver-fix-system-normalized/"><u>Nvidia Driver Fix - System Normalized</u></a></li>
<li><a href="https://network-issues.techidaily.com/beat-the-system-cutting-lag-time/"><u>Beat the System: Cutting Lag Time</u></a></li>
<li><a href="https://location-fake.techidaily.com/4-methods-to-turn-off-life-360-on-motorola-edge-2023-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>4 Methods to Turn off Life 360 On Motorola Edge 2023 without Anyone Knowing | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/solutions-to-absent-screen-behavior-on-devices/"><u>Solutions to Absent Screen Behavior on Devices</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-oppo-k11-5g-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Oppo K11 5G | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-fading-out-sound-fl-studio-guide/"><u>In 2024, Fading Out Sound  FL Studio Guide</u></a></li>
<li><a href="https://network-issues.techidaily.com/eliminate-amd-glitches-tarkov/"><u>Eliminate AMD Glitches, Tarkov</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-earning-edge-advanced-tactics-for-monetizing-videos-on-vimeo-for-2024/"><u>[New] Earning Edge  Advanced Tactics for Monetizing Videos on Vimeo for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/screens-silent-sob-laptop-troubles/"><u>Screen's Silent Sob: Laptop Troubles</u></a></li>
<li><a href="https://network-issues.techidaily.com/upgrade-visual-capabilities-windows-plus-new-intel-hd-driver/"><u>Upgrade Visual Capabilities: Windows + New Intel HD Driver</u></a></li>
<li><a href="https://network-issues.techidaily.com/seamless-media-playback-post-upgrade-on-win10/"><u>Seamless Media Playback Post-Upgrade on Win10</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-perfect-your-pics-ideal-apps-list-for-iphonesandroids/"><u>In 2024, Perfect Your Pics  Ideal Apps List for iPhones/Androids</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-screenmaster-review-the-latest-in-tech-capture-for-2024/"><u>[Updated] ScreenMaster Review  The Latest in Tech Capture for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/rectifying-switchable-graphics-issue-with-intel-and-nvidia-win10/"><u>Rectifying Switchable Graphics Issue with Intel & NVIDIA Win10</u></a></li>
<li><a href="https://network-issues.techidaily.com/solved-signal-struggle-laptop-to-tv-no-success/"><u>[Solved] Signal Struggle: Laptop to TV No Success</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-dissecting-the-newest-features-of-facebook/"><u>2024 Approved  Dissecting the Newest Features of Facebook</u></a></li>
<li><a href="https://network-issues.techidaily.com/solve-curser-freeze-in-win10/"><u>Solve Curser Freeze in Win10</u></a></li>
<li><a href="https://network-issues.techidaily.com/correcting-asymmetric-display-issue-wins-11-version/"><u>Correcting Asymmetric Display Issue, Wins 11 Version</u></a></li>
<li><a href="https://network-issues.techidaily.com/fix-stuck-pointer-in-dark-window-w10/"><u>Fix Stuck Pointer in Dark Window, W10</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-asmrists-aiding-the-nighttime-ritual-for-2024/"><u>Top ASMRists Aiding the Nighttime Ritual for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/wi-fi-disconnects-and-frustrates-us/"><u>Wi-Fi Disconnects and Frustrates Us</u></a></li>
<li><a href="https://network-issues.techidaily.com/smooth-transition-of-windows-11-playback-post-update/"><u>Smooth Transition of Windows 11 Playback Post-Update</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-best-steadicams-for-dslr/"><u>[New] Best Steadicams for DSLR</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolve-horizontal-line-disruptions/"><u>Resolve Horizontal Line Disruptions</u></a></li>
<li><a href="https://extra-resources.techidaily.com/universal-vmix-adapter/"><u>Universal VMix Adapter</u></a></li>
<li><a href="https://network-issues.techidaily.com/qualcomm-wifi-adapter-atheros-issue-windows-10-fixed/"><u>Qualcomm WiFi Adapter, Atheros Issue - Windows 10 Fixed</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-motorola-g54-5g-to-outlook-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Motorola G54 5G to Outlook | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/ranking-the-best-ios-devices-tools-to-download-fb-movies-and-tunes/"><u>Ranking the Best iOS Devices' Tools to Download FB Movies & Tunes</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-futures-canvas-unveiling-6-pioneers-of-nft-artistry/"><u>[Updated] The Future's Canvas  Unveiling 6 Pioneers of NFT Artistry</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcoming-windows-wide-view-resolution-fix/"><u>Overcoming Window's Wide View Resolution Fix</u></a></li>
<li><a href="https://network-issues.techidaily.com/1719974543137-the-display-settings-could-not-be-saved-solved/"><u>“The Display Settings Could Not Be Saved” [Solved]</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixed-installer-error-on-nvidia/"><u>Fixed Installer Error on NVIDIA</u></a></li>
<li><a href="https://network-issues.techidaily.com/hybrid-graphics-enhanced-after-windows-11-upgrade-fixes/"><u>Hybrid Graphics Enhanced After Windows 11 Upgrade Fixes</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-ipogo-will-be-the-new-ispoofer-on-samsung-galaxy-a05s-drfone-by-drfone-virtual-android/"><u>In 2024, iPogo will be the new iSpoofer On Samsung Galaxy A05s? | Dr.fone</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-essential-tips-for-online-photo-cropting/"><u>2024 Approved  Essential Tips for Online Photo Cropting</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-a-xiaomi-redmi-k70-phone-that-is-locked-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset a Xiaomi Redmi K70 Phone That Is Locked | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-ultimate-clearer-eliminate-backgrounds-effectively/"><u>[Updated] Ultimate Clearer  Eliminate Backgrounds Effectively</u></a></li>
<li><a href="https://network-issues.techidaily.com/windows-10-gets-a-boost-with-new-geforce-210-graphics-driver/"><u>Windows 10 Gets a Boost with New GeForce 210 Graphics Driver</u></a></li>
</ul></div>
