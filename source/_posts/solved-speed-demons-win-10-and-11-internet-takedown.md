---
title: "[SOLVED] Speed Demons: WIN 10 & 11 Internet Takedown"
date: 2024-07-12T00:48:26.393Z
updated: 2024-07-13T00:48:26.393Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: "This Article Describes [SOLVED] Speed Demons: WIN 10 & 11 Internet Takedown"
excerpt: "This Article Describes [SOLVED] Speed Demons: WIN 10 & 11 Internet Takedown"
keywords: Windows Speed Demons,Internet Speed Optimization,Windows 10/Windows 11 Slow Network,Internet Connectivity Issues,Wi-Fi Connection Speed,Network Latency Windows 10/Windows 11,Slow Internet Speed Fixes
thumbnail: https://thmb.techidaily.com/de2a2439a12942f0b9808810580359ed4223c732cf24aad5cc401c9c124e67ae.jpeg
---

## [SOLVED] Speed Demons: WIN 10 & 11 Internet Takedown

 If you ever run into the**Windows 11 or 10 slow Internet** problem, don’t worry. It’s often quite easy to fix…

## 6 fixes for Windows 11/10 Slow Internet

 All the fixes below work in Windows 11/10; just work your way down the list until the Internet slowdown problem is resolved.

1. **[Disable Peer-to-Peer Update](#F1)**
2. **[Adjust the Internet Bandwidth Settings](#F2)**
3. **[Update your WiFi drivers](#F3)**
4. **[Repair system files](#RE)**
5. **[Disable Windows Auto-Tuning](#F4)**
6. **[Disable Large Send Offload](#F5)**
7. **[Some other modifications to try](#network) [](#F5)**

## Fix 1: Disable Peer to Peer Update

**Peer to Peer Update** is a feature in Windows that allows your computer to share Windows updates peer-to-peer with other computers over the Internet, which can compromise our Internet connection, hence the sluggish Internet issue.

 To disable**Peer to Peer Update** :

1. On your keyboard, press**the Windows logo key** and**R** at the same time, then type**control update** in the box and press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/img_5b70fb4c56bc7.png)
2. Click**Advanced options** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/windowsupdateadvancedoptions.jpg)
3. Click**Delivery Optimization** (or**Choose how updates are delivered** depending on the build of your Windows 10).  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/windowsupdatedeliveryoption.jpg)
4. Turn the**Allow downloads from other PCs** (Or**Update from more than one place**) toggle**Off** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/windowsupdateallowapps.jpg)
5. Check if the**Windows 11/10 slow Internet** issue has been fixed. If yes, then great! But if the problem persists, move on to**Fix 2** , below.

---

## Fix 2: Adjust the Internet Bandwidth Settings

 Please note that Group Policy Editor is not supported on Windows 10/11 Home Edition. So if you’re not using Windows Pro, or Enterprise, please move on to [Fix3](#F3) .

 By default, Windows reserves 20% of your bandwidth for Windows Update, system apps, and other purposes, leaving you with 80% bandwidth of Internet connection. If you don’t use Windows Update on a daily basis and the reservation limit slows your Internet down, then you can remove the limit by setting the value to 0.

Here’s how to do it:

1. On your keyboard, press**Ctrl** ,**Shift,** and**Esc** at the same time to open Task Manager.
2. Click**Run new task** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/taskmanagernewtask.jpg)
3. Copy & paste **gpedit.msc** into the box, tick the box before **Create this task with administrative privileges** , and click **OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/img_5b67c73fda271.png)
4. Under **Computer Configuration** , double-click on**Administrative Templates** \>**Network** \>**QoS Packet Scheduler** . Then double-click on **Limit reservable bandwidth** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/img_5b7121e2c956c.jpg)
5. Click the**Enabled** option and set**Bandwidth limit (%)** value to**0** . Then click**Apply** \>**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/img_5b712108609d3.jpg)
6. Is your Internet getting any faster? If it’s still grinding to a crawl, you should try**Fix 3** , below.

---

## Fix 3: Update your WiFi drivers

 This problem may occur if you are using the wrong/outdated WiFi drivers. So you should update your WiFi/network adapter driver drivers to see if it fixes your problem. If you don’t have the time, patience, or computer skills to update your drivers manually, you can do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.**Driver Easy handles it all.**

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and**install** Driver Easy.
2. Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://www.drivereasy.com/wp-content/uploads/2024/05/DE-scan-now-6.0.jpg)
3. Click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  which comes with **full support**  and a **30-day money-back**  guarantee. You’ll be prompted to upgrade when you click Update All. If you’re not ready to buy the Pro version, Driver Easy offers a 7-day free trial which includes access to all the Pro features such as high-speed download and one-click install. You won’t be charged anything until your 7-day trial has ended.)  

![](https://www.drivereasy.com/wp-content/uploads/2017/10/de-update-all-wireless-6.0.jpg)

**The Pro version of Driver Easy** comes with _full technical support_ . If you need assistance, please contact **Driver Easy’s support team** at **[support@drivereasy.com](mailto:support@drivereasy.com) .**

 Restart your computer and see if the **Windows 10 Slow Internet** problem has been resolved. If yes, then congrats! If the issue still persists, please move on to**Fix 4** , below.

## Fix 4: Repair system files

 Missing, corrupt, or damaged system files may reduce your internet connection speeds. To eliminate this issue as a possible cause, you can try the 2 ways below to repair possible system file issues.

1. **[Repair & replace corrupt system files with Fortect](#fortect)**
2. [**Run SFC scan**](#SFC)

### Repair & replace corrupt system files with Fortect

 The slow internet in your Windows 10 computer could be caused by corrupt system files. **[Fortect](https://tools.techidaily.com/drivereasy/download/)**  is a tool that auto-detects slow internet and specializes in Windows repair.

 With [](https://tools.techidaily.com/drivereasy/download/) **[Fortect](https://tools.techidaily.com/drivereasy/download/)**  , the preliminary will scan your computer’s operating system for viruses, malware, and missing, damaged, or corrupt files, then it removes all problematic files found and replaces them with new healthy files. It’s like a clean reinstall of your operating system, except that you won’t lose any user data, and all programs, and settings are exactly as they are before the repair.

Here’s how to use Fortect to repair system files on your PC:

1. [**Download**](https://tools.techidaily.com/drivereasy/download/) and install Fortect.
2. Open Fortect and Wait for Fortect to run a scan on your PC. The process might take a couple of minutes.
3. Once the scan finishes, you will get a summary of the issues found on your computer. If you need to proceed with the repair function, you’ll be required to purchase the full version.  
![](https://www.drivereasy.com/wp-content/uploads/2023/07/fortectstartrepair.png)
4. Restart your computer for the changes to take effect.
5. Check your computer to see if the internet speed has returned to normal.

 The full version of Fortect comes with a 60-day money-back guarantee and full customer support. If you run into any problems while using Fortect, or if it doesn’t work for you, don’t hesitate to contact [Fortect Customer Support Team](https://www.fortect.com/support/) .

### Run SFC scan

**System File Checker** (**SFC**) is a handy feature in Windows that helps scan your system files and repair missing or corrupted system files(including those related to **BSOD**). To **run the SFC scan** :

1. On your keyboard, press the**Windows logo key** and type **cmd** . Then right-click on **Command Prompt** and click **Run as administrator** .  
![](https://www.drivereasy.com/wp-content/uploads/2018/06/img_5b28ad73ad4a9.png)
2. Click**Yes** when prompted to confirm.
3. In the command prompt window, type**sfc /scannow** and press **Enter** .  
![](https://www.drivereasy.com/wp-content/uploads/2018/06/img_5b28aee247664.jpg)  
 It’ll take some time for the SFC to replace the corrupted system files with new ones if it detects any, so please be patient.
4. Restart your computer for the changes to take effect.
5. Check your computer to see if the**Windows 10 slow internet** problem has been fixed. If yes, then congrats! If the issue still persists, please move on to**Fix 5** , below.

---

## Fix 5: Disable Windows Auto-Tuning

**Window Auto-Tuning** is a feature in our Windows 10 to allow for more efficient data transfers. But it can also interfere with the network and cause loss of connectivity. So to disable the feature:

1. On your keyboard, press the **Windows logo key** and type **cmd** . Then right click on **Command Prompt**   and click **Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b28ad73ad4a9.png)  

 Click **Yes** when prompted to confirm.
2. Copy & paste **netsh interface tcp show global** into the window and press**Enter** . Then check if**Receive Window Auto-Tuning Level**  is set to**normal** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/img_5b70ff100133c.jpg)
3. If yes, you’ll have to copy & paste**netsh int tcp set global autotuninglevel=disabled** into the window and press**Enter** to disable it.  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/img_5b7134aa2923c.jpg)
4. Check to see if your**Windows 10 slow Internet** problem has been solved. If the issue still lingers on, don’t worry, here’s one more fix to try.

---

## Fix 6: Disable Large Send Offload

**Large Send Offload** (**LSO**) is another feature in Windows designated for better network performance. Well-intended, but then the whole thing of allowing background apps to consume large amounts of network bandwidth is the reason why our Internet speed takes a hit. To disable**LSO** :

1. On your keyboard, press **the Windows logo key** and **R**  at the same time, then type **devmgmt.msc** into the box and press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/img_5b7105728b9d7.png)
2. Double-click on**Network adapters** \>**your network adapter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/img_5b7106291012e.jpg)
3. Click the**Advanced** tab, then click **Large Send Offload V2 (IPv4)** and set the**value** to**Disabled** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/img_5b71075272c84.jpg)
4. Click **Large Send Offload V2 (IPv6)**  and set the**value** to**Disabled** . Then click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/img_5b7107f56920e.jpg)
5. Hopefully, your **Windows 10/11 Slow Internet** issue has been resolved successfully.

## Some other modifications

 If none of the above network-related changes prove effective, here are some other tweaks that you can do to improve your network connectivity situation, and thus help to improve the network speed on your computer. Check the following to see if you’ve done them all:

* **Reduce the number of devices connected to the same router** to make sure that your main computer gets the most speed.
* **Use a wired network connection** (with an Ethernet cable) instead of Wi-Fi. If this is not an option, move your computer closer to the router.
* **Update your router firmware** if you haven’t already.
* In your router settings, try to **enable QoS to prioritize gaming traffic** . If you’re not sure where to find it, please visit your router’s official website to find the manual or seek help from your ISP.
* **Contact your ISP** . If you’ve tried everything and your internet is still slow, it might be an issue with your ISP (Internet Service Provider). Contact them for support.
* **Upgrade Your Plan** : If your internet plan is outdated or doesn’t provide enough bandwidth for your needs, consider upgrading to a plan with higher speeds.
* **Upgrade your hardware** . If the network settings are set up all correctly, but the network speed is still slow, it’s possible that your hardware is throttling the network speed. In that case, you may need to consider a more advanced router or modem, network cables and network adapters.

---

 There you have it – 6 useful fixes for your**Windows 11/10 Slow Internet** problem. Hope this helps and feel free to comment below if you have any further questions. 🙂

* [driver](https://tools.techidaily.com/drivereasy/download/)
* [network adapter](https://tools.techidaily.com/drivereasy/download/)
* [Windows 10](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://network-issues.techidaily.com/adjusting-your-win11-display-for-peak-performance/"><u>Adjusting Your Win11 Display for Peak Performance</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-8-essential-tools-for-your-youtube-to-avi-needs-for-2024/"><u>[Updated] 8 Essential Tools for Your YouTube-to-AVI Needs for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/conquering-crest-flicker-in-win11/"><u>Conquering Crest Flicker in Win11</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-affordable-subscriber-boost-buy-and-sell-youtube-views/"><u>[New] 2024 Approved  Affordable Subscriber Boost  Buy & Sell YouTube Views</u></a></li>
<li><a href="https://network-issues.techidaily.com/kratos-quest-mechanics-mastered/"><u>Kratos Quest: Mechanics Mastered</u></a></li>
<li><a href="https://network-issues.techidaily.com/gpu-ghosting-track-down-the-missing-nvidia-in-device-manager/"><u>GPU Ghosting? Track Down the Missing NVIDIA in Device Manager</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-downgrade-iphone-13-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade iPhone 13 without iTunes? | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolve-win11-monitor-flashing-issue/"><u>Resolve Win11 Monitor Flashing Issue</u></a></li>
<li><a href="https://network-issues.techidaily.com/driver-update-for-error-22-rectified/"><u>Driver Update for Error 22 Rectified</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/aiff-conversion-made-easy-top-converter-options-for-2024/"><u>Aiff Conversion Made Easy Top Converter Options for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/1719974766895-hasten-intels-graphics-update-for-ws11-efficiency/"><u>Hasten Intel's Graphics Update for WS11 Efficiency.</u></a></li>
<li><a href="https://network-issues.techidaily.com/nvidia-control-panel-status-green/"><u>Nvidia Control Panel - Status Green</u></a></li>
<li><a href="https://network-issues.techidaily.com/display-output-normalized/"><u>Display Output Normalized</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-apple-iphone-xs-max-to-other-iphone-without-icloud-drfone-by-drfone-transfer-from-ios/"><u>In 2024, How to Transfer Photos from Apple iPhone XS Max to other iPhone without iCloud | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/win11-arm-screen-adjustment-no-more-troubles/"><u>Win11: Arm Screen Adjustment No More Troubles</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-unbrick-a-dead-xiaomi-redmi-k70-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Unbrick a Dead Xiaomi Redmi K70 Pro | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/tdr-alert-nvidia-opengl-driver-now-stable/"><u>TDR Alert: NVIDIA OpenGL Driver Now Stable</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-insightful-analysis-of-modifying-photographic-genders-on-social-platforms/"><u>2024 Approved  Insightful Analysis of Modifying Photographic Genders on Social Platforms</u></a></li>
<li><a href="https://howto.techidaily.com/8-quick-fixes-unfortunately-snapchat-has-stopped-on-vivo-y27-4g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Quick Fixes Unfortunately, Snapchat has Stopped on Vivo Y27 4G | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/persistent-wi-fi-connection-issues/"><u>Persistent Wi-Fi Connection Issues</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-unleash-your-creativity-best-gopro-video-editing-software-beyond-gopro-studio/"><u>2024 Approved Unleash Your Creativity Best GoPro Video Editing Software (Beyond GoPro Studio)</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-free-youtube-download-methods-without-apps/"><u>[New] Free YouTube Download Methods Without Apps</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolving-windows-10-unresponsive-pointer/"><u>Resolving Windows 10 Unresponsive Pointer</u></a></li>
<li><a href="https://network-issues.techidaily.com/counteract-black-screen-and-recover-mouse-on-w10/"><u>Counteract Black Screen & Recover Mouse on W10</u></a></li>
<li><a href="https://network-issues.techidaily.com/streamline-visual-line-continuity/"><u>Streamline Visual Line Continuity</u></a></li>
<li><a href="https://network-issues.techidaily.com/restored-disabled-wi-fi-functionality-on-windows-10/"><u>Restored Disabled Wi-Fi Functionality on Windows 10</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-discover-key-methods-to-store-discord-livestream-videos-efficiently/"><u>[New] 2024 Approved  Discover Key Methods to Store Discord Livestream Videos Efficiently</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-integrating-tracks-adding-songs-and-soundscapes-into-final-cut-pro-editing/"><u>New Integrating Tracks Adding Songs and Soundscapes Into Final Cut Pro Editing</u></a></li>
<li><a href="https://network-issues.techidaily.com/rectified-drivers-fixederror-22/"><u>Rectified Drivers' FixedError 22</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-a-compre-market-leaders-guide-to-the-most-effective-fb-video-ad-approaches/"><u>[Updated] In 2024, A Compre Market Leader's Guide to the Most Effective FB Video Ad Approaches</u></a></li>
<li><a href="https://network-issues.techidaily.com/techniques-for-fixing-lenovo-glare/"><u>Techniques for Fixing Lenovo Glare</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-frp-on-camon-20-premier-5g-by-drfone-android-unlock-remove-google-frp/"><u>How To Bypass FRP on Camon 20 Premier 5G</u></a></li>
<li><a href="https://network-issues.techidaily.com/restore-wi-fi-capability-wireless-card-reinstalled-in-windows-10/"><u>Restore Wi-Fi Capability: Wireless Card Reinstalled in Windows 10</u></a></li>
<li><a href="https://network-issues.techidaily.com/quickly-boost-intel-g3000-on-win11/"><u>Quickly Boost Intel G3000 on Win11!</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolving-nvidia-conflict-with-win10/"><u>Resolving Nvidia Conflict with Win10</u></a></li>
<li><a href="https://facebook.techidaily.com/beware-of-phishing-schemes-in-your-news-feed/"><u>Beware of Phishing Schemes in Your News Feed</u></a></li>
<li><a href="https://network-issues.techidaily.com/rectified-cuda-toolkit-access-denial/"><u>[Rectified] CUDA Toolkit Access Denial</u></a></li>
<li><a href="https://network-issues.techidaily.com/re-enabling-display-set-configurations-on-windows-107/"><u>Re-Enabling Display Set Configurations on Windows 10/7</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/in-2024-video-maestro-convert-casual-clips-into-cinematic-masterpieces/"><u>In 2024, Video Maestro Convert Casual Clips Into Cinematic Masterpieces</u></a></li>
<li><a href="https://network-issues.techidaily.com/restoring-lost-display-settings-in-windows-oses/"><u>Restoring Lost Display Settings in Windows OSes</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/-to-buy-a-monetized-youtube-channel-a-complete-guide-for-2024/"><u>Where to Buy a Monetized YouTube Channel  A Complete Guide for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/uninstalling-graphics-drivers-a-step-by-step-tutorial/"><u>Uninstalling Graphics Drivers: A Step-by-Step Tutorial</u></a></li>
<li><a href="https://network-issues.techidaily.com/no-issues-detected-post-nvidia-installation/"><u>No Issues Detected Post-Nvidia Installation</u></a></li>
<li><a href="https://network-issues.techidaily.com/interpreting-invisible-stream-errors/"><u>Interpreting Invisible Stream Errors</u></a></li>
<li><a href="https://network-issues.techidaily.com/fullscreen-performance-restored-in-win10-version/"><u>Fullscreen Performance Restored in Win10 Version</u></a></li>
<li><a href="https://network-issues.techidaily.com/skip-the-glitch-with-amd-fixes/"><u>Skip the Glitch with AMD Fixes</u></a></li>
<li><a href="https://network-issues.techidaily.com/neutralizing-screen-volatility-pro-7-guide/"><u>Neutralizing Screen Volatility: Pro 7 Guide</u></a></li>
<li><a href="https://network-issues.techidaily.com/introducing-an-effortless-upgrade-for-intel-hd-graphics-on-windows-10-devices/"><u>Introducing an Effortless Upgrade for Intel HD Graphics on Windows 10 Devices.</u></a></li>
<li><a href="https://network-issues.techidaily.com/direct-rendering-error-solved/"><u>Direct Rendering Error Solved</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-share-and-celebrate-with-instagram-videos/"><u>[New] Share & Celebrate with Instagram Videos</u></a></li>
<li><a href="https://network-issues.techidaily.com/nvidia-rtx-feedback-resolved/"><u>Nvidia RTX Feedback - Resolved</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-auditory-precision-in-filmmaking-employing-audio-ducking-strategies/"><u>Updated 2024 Approved Auditory Precision in Filmmaking Employing Audio Ducking Strategies</u></a></li>
<li><a href="https://youtube-help.techidaily.com/mastering-personal-content-management-building-a-structured-watch-later-list-for-2024/"><u>Mastering Personal Content Management  Building a Structured 'Watch Later' List for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/error-correction-mh-world-crashed-no-more/"><u>Error Correction: MH World Crashed No More</u></a></li>
<li><a href="https://network-issues.techidaily.com/conquering-windows-11-no-display-dilemma/"><u>Conquering Windows 11 No-Display Dilemma</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-tracking-apps-to-track-oppo-reno-10-5g-without-them-knowing-drfone-by-drfone-virtual-android/"><u>Top 5 Tracking Apps to Track Oppo Reno 10 5G without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/unblocking-asus-camera-from-hardware-issues/"><u>Unblocking Asus Camera From Hardware Issues</u></a></li>
</ul></div>
