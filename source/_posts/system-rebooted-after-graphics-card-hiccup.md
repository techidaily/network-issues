---
title: System Rebooted After Graphics Card Hiccup
date: 2024-07-12T00:44:35.924Z
updated: 2024-07-13T00:44:35.924Z
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
<li><a href="https://network-issues.techidaily.com/simplified-trick-to-straighten-laptop-views/"><u>Simplified Trick to Straighten Laptop Views</u></a></li>
<li><a href="https://network-issues.techidaily.com/enabling-saving-of-screen-config-changes-on-windows-710/"><u>Enabling Saving of Screen Config Changes on Windows 7/10</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-blurring-faces-with-best-video-editing-software/"><u>In 2024, Blurring Faces with Best Video Editing Software</u></a></li>
<li><a href="https://network-issues.techidaily.com/tackle-hidden-vram-issues/"><u>Tackle Hidden VRAM Issues</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-revolutionize-your-reach-on-tiktoks-hot-list/"><u>[Updated] 2024 Approved  Revolutionize Your Reach on TikTok's Hot List</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-is-a-sim-network-unlock-pin-get-your-samsung-galaxy-a14-5g-phone-network-ready-by-drfone-android/"><u>What Is a SIM Network Unlock PIN? Get Your Samsung Galaxy A14 5G Phone Network-Ready</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-facebooks-recent-views-uncovered-for-you/"><u>[Updated] In 2024, Facebook’s Recent Views Uncovered for You</u></a></li>
<li><a href="https://network-issues.techidaily.com/display-driver-resolved-code-43/"><u>Display Driver Resolved Code 43</u></a></li>
<li><a href="https://network-issues.techidaily.com/seamlessly-enhance-g3000-on-windows-11-intel/"><u>Seamlessly Enhance G3000 on Windows 11, Intel.</u></a></li>
<li><a href="https://network-issues.techidaily.com/opaque-output-offline-operations/"><u>Opaque Output, Offline Operations</u></a></li>
<li><a href="https://network-issues.techidaily.com/win10-fall-screen-fix-after-cu-installation/"><u>Win10 Fall Screen Fix After CU Installation</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-a-whole-new-world-of-animated-emojis-top-7-free-online-destinations/"><u>[Updated] In 2024, A Whole New World of Animated Emojis  Top 7 FREE Online Destinations</u></a></li>
<li><a href="https://network-issues.techidaily.com/jive-without-jitters-anti-lag-tactics/"><u>Jive Without Jitters: Anti-Lag Tactics</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-impact-of-fake-subscriptions-on-channel-success/"><u>2024 Approved  Impact of Fake Subscriptions on Channel Success?</u></a></li>
<li><a href="https://network-issues.techidaily.com/atheros-and-qualcomm-wifi-seamlessly-work-in-win10/"><u>Atheros & Qualcomm WiFi Seamlessly Work in Win10</u></a></li>
<li><a href="https://network-issues.techidaily.com/easing-pro-7s-shimmering-issue/"><u>Easing Pro 7'S Shimmering Issue</u></a></li>
<li><a href="https://network-issues.techidaily.com/fix-desktop-orientation-backward-problem/"><u>Fix: Desktop Orientation Backward Problem</u></a></li>
<li><a href="https://network-issues.techidaily.com/transforming-visual-experience-refreshing-intel-drivers-in-windows-7/"><u>Transforming Visual Experience: Refreshing Intel Drivers in Windows 7</u></a></li>
<li><a href="https://network-issues.techidaily.com/step-by-step-wow-glitch-remedy-51900319/"><u>Step-by-Step WoW Glitch Remedy #51900319</u></a></li>
<li><a href="https://network-issues.techidaily.com/display-quality-enhancement-no-more-resolution-woes-on-windows-10/"><u>Display Quality Enhancement - No More Resolution Woes on Windows 10</u></a></li>
<li><a href="https://network-issues.techidaily.com/remedying-loss-of-display-on-personal-computers/"><u>Remedying Loss of Display on Personal Computers</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-frp-hijacker-by-hagard-download-and-bypass-your-nokia-frp-locks-by-drfone-android/"><u>In 2024, FRP Hijacker by Hagard Download and Bypass your Nokia FRP Locks</u></a></li>
<li><a href="https://network-issues.techidaily.com/nvidiaintel-card-syncing-a-win11-update-success-story/"><u>Nvidia/Intel Card Syncing, A Win11 Update Success Story</u></a></li>
<li><a href="https://network-issues.techidaily.com/enabling-intel-drivers-on-systems-below-threshold/"><u>Enabling Intel Drivers on Systems Below Threshold</u></a></li>
<li><a href="https://fox-glue.techidaily.com/comparing-googles-flat-cube-and-samsungs-headset-for-2024/"><u>Comparing Google's Flat Cube and Samsung's Headset for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/9-quick-fixes-to-unfortunately-touchwiz-has-stopped-of-infinix-smart-8-plus-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Quick Fixes to Unfortunately TouchWiz has stopped Of Infinix Smart 8 Plus | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-xiaomi-civi-3-by-drfone-android/"><u>In 2024, AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Xiaomi Civi 3</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-2024-approved-5-popular-guitar-recording-software-for-guitarists/"><u>New 2024 Approved 5 Popular Guitar Recording Software for Guitarists</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-poco-m6-5g-find-my-friends-no-location-found-drfone-by-drfone-virtual-android/"><u>How to Fix Poco M6 5G Find My Friends No Location Found? | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/diminishing-disturbance-on-win11-panels/"><u>Diminishing Disturbance on Win11 Panels</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-mastering-tiktok-video-posts-on-twitter-for-2024/"><u>[Updated] Mastering TikTok Video Posts on Twitter for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolving-resolution-challenges-with-updated-windows-10/"><u>Resolving Resolution Challenges with Updated Windows 10</u></a></li>
<li><a href="https://network-issues.techidaily.com/explaining-shadowed-video-blackouts/"><u>Explaining Shadowed Video Blackouts</u></a></li>
<li><a href="https://network-issues.techidaily.com/fix-window-fuzziness-boost-productivity/"><u>Fix Window Fuzziness, Boost Productivity</u></a></li>
<li><a href="https://network-issues.techidaily.com/navigating-the-process-of-win-7s-intel-driver-updates/"><u>Navigating the Process of Win 7'S Intel Driver Updates</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-debating-platform-preferences-igtv-versus-youtube-video-sharing/"><u>[Updated] Debating Platform Preferences  IGTV Versus YouTube Video Sharing</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixed-dxgkrnlsys-crash-in-windows-blue-screen/"><u>Fixed dxgkrnl.sys Crash in Windows' Blue Screen</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-in-2024-from-lol-to-omg-the-best-meme-generator-apps/"><u>New In 2024, From LOL to OMG The Best Meme Generator Apps</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-pixelpower-boost-your-phone-pics-for-free/"><u>[New] PixelPower  Boost Your Phone Pics for Free</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/treamline-your-browsing-eliminate-youtube-ads-in-chrome-firefox-ios-for-2024/"><u>[New] Streamline Your Browsing  Eliminate YouTube Ads in Chrome, Firefox, iOS for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-splitcam-assessment-best-video-recorder-ranking/"><u>[New] In 2024, SplitCam Assessment  Best Video Recorder Ranking?</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-many-attempts-to-unlock-iphone-8-plus-drfone-by-drfone-ios/"><u>How Many Attempts To Unlock iPhone 8 Plus | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/calm-the-currents-resolve-dells-flicker/"><u>Calm the Currents: Resolve Dell's Flicker</u></a></li>
<li><a href="https://location-social.techidaily.com/3-things-you-must-know-about-fake-snapchat-location-on-itel-a60s-drfone-by-drfone-virtual-android/"><u>3 Things You Must Know about Fake Snapchat Location On Itel A60s | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/the-best-8-vpn-hardware-devices-reviewed-on-apple-iphone-xr-drfone-by-drfone-virtual-ios/"><u>The Best 8 VPN Hardware Devices Reviewed On Apple iPhone XR | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixing-the-upside-down-screen-issue/"><u>Fixing the Upside-Down Screen Issue</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-smartphone-tools-for-perfecting-your-pronunciation/"><u>[New] In 2024, Smartphone Tools for Perfecting Your Pronunciation</u></a></li>
<li><a href="https://network-issues.techidaily.com/darkened-view-post-driver-change/"><u>Darkened View Post-Driver Change</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-the-key-to-successful-collaborations-in-the-digital-age/"><u>[Updated] The Key to Successful Collaborations in the Digital Age</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-innovative-approaches-to-customizing-your-tiktok-videos-for-2024/"><u>[Updated] Innovative Approaches to Customizing Your TikTok Videos for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/screen-size-fix-for-windows-10-users-achieved/"><u>Screen Size Fix for Windows 10 Users Achieved</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/sierras-best-top-5-mac-videography-software-insights/"><u>Sierra's Best  Top 5 Mac Videography Software Insights</u></a></li>
<li><a href="https://network-issues.techidaily.com/clearing-up-youtube-green-screen-faux-pas/"><u>Clearing Up YouTube Green Screen Faux Pas</u></a></li>
<li><a href="https://network-issues.techidaily.com/windows-8-safe-mode-mastery-revoking-gpu-driver-integrity/"><u>Windows 8 Safe Mode Mastery: Revoking GPU Driver Integrity</u></a></li>
<li><a href="https://network-issues.techidaily.com/addressing-c1900101-issue-in-windows-setup/"><u>Addressing C1900101 Issue in Windows Setup</u></a></li>
<li><a href="https://network-issues.techidaily.com/tighten-display-line-precision/"><u>Tighten Display Line Precision</u></a></li>
<li><a href="https://screen-recording.techidaily.com/formulating-windowsmac-skype-group-chats-easily-for-2024/"><u>Formulating Windows/Mac Skype Group Chats Easily for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-your-youtube-shorts-have-been-restored/"><u>[New] Your YouTube Shorts Have Been Restored</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-unleash-your-fun-with-todays-favorite-tiktoks-for-2024/"><u>[Updated] Unleash Your Fun with Today's Favorite TikToks for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/end-of-frustrations-fallout-4-stable-on-windows/"><u>End of Frustrations: Fallout 4 Stable on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/rectify-stalling-windows-guard-mechanism-in-win-11/"><u>Rectify Stalling Windows Guard Mechanism in Win 11</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-leading-6-virtual-venues-propelling-professional-connections/"><u>[Updated] Leading 6 Virtual Venues Propelling Professional Connections</u></a></li>
<li><a href="https://network-issues.techidaily.com/high-dpi-settings-easier-to-adjust-post-update-in-windows-10/"><u>High-DPI Settings: Easier to Adjust Post-Update in Windows 10</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-zoom-session-division-for-starters/"><u>[New] Zoom Session Division for Starters</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-2024-approved-8-best-online-facebook-video-to-mp3-converters/"><u>Updated 2024 Approved 8 Best Online Facebook Video to MP3 Converters</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-best-practices-for-identifying-premier-free-srt-translation-services/"><u>2024 Approved  Best Practices for Identifying Premier Free SRT Translation Services</u></a></li>
<li><a href="https://network-issues.techidaily.com/no-response-from-monitor-post-update/"><u>No Response From Monitor Post Update</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-comedy-central-the-best-laughter-inducing-channels-online/"><u>2024 Approved  Comedy Central  The Best Laughter-Inducing Channels Online</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcame-control-panel-lockout-issue/"><u>Overcame: Control Panel Lockout Issue</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-a-symphony-of-signals-top-5-groundbreaking-audiovideo-mixing-devices-set-for-2024/"><u>Updated A Symphony of Signals Top 5 Groundbreaking Audio/Video Mixing Devices Set for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/hardware-hiccup-error-43-done/"><u>Hardware Hiccup: Error 43 Done</u></a></li>
</ul></div>
