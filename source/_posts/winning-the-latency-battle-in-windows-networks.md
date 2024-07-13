---
title: Winning the Latency Battle in Windows Networks
date: 2024-07-12T00:16:52.531Z
updated: 2024-07-13T00:16:52.531Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: This Article Describes Winning the Latency Battle in Windows Networks
excerpt: This Article Describes Winning the Latency Battle in Windows Networks
keywords: Low Latency Optimization Techniques in Windows Networks,Reducing Network Latency in Windows Environments,Improving Network Performance in Windows Systems,Network Latency Troubleshooting for Windows Users,Best Practices for Reducing Latency in Windows Servers,Network Latency Mitigation Strategies for Windows Infrastructure,Network Optimization Strategies to Reduce Latency on Windows
thumbnail: https://thmb.techidaily.com/3376b29faa2d3197bcfcb2a2edc1961849ab5554465668491f874fa276d36a0e.jpg
---

## Winning the Latency Battle in Windows Networks

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
<li><a href="https://network-issues.techidaily.com/guide-swiftly-rectify-screen-lines-at-laptop-level/"><u>Guide: Swiftly Rectify Screen Lines at Laptop Level</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-capturing-views-connecting-users-social-media-for-360-degree-photos/"><u>[Updated] Capturing Views, Connecting Users  Social Media for 360-Degree Photos</u></a></li>
<li><a href="https://network-issues.techidaily.com/mortal-kombats-wait-woes/"><u>Mortal Kombat's Wait Woes</u></a></li>
<li><a href="https://network-issues.techidaily.com/reconciled-error-code-22-in-graphics-driver/"><u>Reconciled Error Code 22 in Graphics Driver</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-6-plus-to-other-iphone-13-pro-max-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 6 Plus to other iPhone 13 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/adjustment-woes-windows-11-resolution-halted/"><u>Adjustment Woes - Windows 11 Resolution Halted</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixed-microsoft-basic-render-driver-issues-in-windows-111087/"><u>[FIXED] Microsoft Basic Render Driver Issues in Windows 11/10/8/7</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/how-to-add-freeze-frame-to-your-video-from-any-device-in-2024/"><u>How to Add Freeze Frame to Your Video From Any Device, In 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-top-10-independent-android-games-for-non-networked-natives/"><u>[Updated] Top 10 Independent Android Games for Non-Networked Natives</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/best-youtube-shorts-video-editing-apps-for-ios-and-android/"><u>Best YouTube Shorts Video Editing Apps for iOS and Android</u></a></li>
<li><a href="https://network-issues.techidaily.com/windows-11-tailor-desktop-size-to-preference/"><u>Windows 11: Tailor Desktop Size to Preference</u></a></li>
<li><a href="https://network-issues.techidaily.com/stopping-quick-flick-in-dell-panels/"><u>Stopping Quick-Flick in Dell Panels</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-eye-catching-insta-highlights-unveiling-3-secrets/"><u>[Updated] Eye-Catching Insta Highlights  Unveiling 3 Secrets</u></a></li>
<li><a href="https://network-issues.techidaily.com/immediate-fix-method-for-screen-horizontal-anomalies-in-computers/"><u>Immediate Fix Method for Screen Horizontal Anomalies in Computers</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixed-screen-responds-post-glitch/"><u>[Fixed]: Screen Responds Post Glitch</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-nokia-c12-plus-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Nokia C12 Plus to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/the-realities-of-youtube-view-calculation-for-2024/"><u>The Realities of YouTube View Calculation for 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-3-easy-ways-to-factory-reset-a-locked-apple-iphone-se-2022-without-itunes-drfone-by-drfone-ios/"><u>In 2024, 3 Easy Ways to Factory Reset a Locked Apple iPhone SE (2022) Without iTunes | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-unleash-creativity-with-free-templates-essential-for-video-makers/"><u>[Updated] Unleash Creativity with FREE Templates – Essential for Video Makers</u></a></li>
<li><a href="https://network-issues.techidaily.com/reversing-graphics-drivers-windows-8s-safe-mode-guide/"><u>Reversing Graphics Drivers: Windows 8'S Safe Mode Guide</u></a></li>
<li><a href="https://network-issues.techidaily.com/dismiss-blank-display-problems/"><u>Dismiss Blank-Display Problems</u></a></li>
<li><a href="https://network-issues.techidaily.com/uniting-windows-7-and-geforce-experience/"><u>Uniting Windows 7 and GeForce Experience</u></a></li>
<li><a href="https://network-issues.techidaily.com/effortlessly-enhance-intel-graphics-3000-via-windows-10-driver-upgrade/"><u>Effortlessly Enhance Intel Graphics 3000 via Windows 10 Driver Upgrade.</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-analyzing-brightness-boost-in-hd-and-its-hdr-impact/"><u>[New] Analyzing Brightness Boost in HD and Its HDR Impact</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-xiaomi-redmi-note-13-5g-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Xiaomi Redmi Note 13 5G</u></a></li>
<li><a href="https://network-issues.techidaily.com/end-window-tearing-phenomena/"><u>End Window Tearing Phenomena</u></a></li>
<li><a href="https://network-issues.techidaily.com/warzone-woes-sluggish-swipes/"><u>Warzone Woes: Sluggish Swipes</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-crafting-the-perfect-first-touch-redefining-unboxing/"><u>2024 Approved  Crafting the Perfect First Touch  Redefining Unboxing</u></a></li>
<li><a href="https://network-issues.techidaily.com/new-windows-update-end-video-buffering-and-jitter/"><u>New Windows Update: End Video Buffering & Jitter</u></a></li>
<li><a href="https://network-issues.techidaily.com/end-monitor-phosphor-sparks-quickly/"><u>End Monitor Phosphor Sparks Quickly</u></a></li>
<li><a href="https://network-issues.techidaily.com/solved-windows-10-wireless-adapter-missing/"><u>[SOLVED] Windows 10 Wireless Adapter Missing</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcoming-wow-anomaly-bug-519/"><u>Overcoming WOW Anomaly: Bug #519</u></a></li>
<li><a href="https://network-issues.techidaily.com/accelerated-adjustment-overcome-loot-mishaps/"><u>Accelerated Adjustment: Overcome Loot Mishaps</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-top-15-augmented-reality-games-like-pokemon-go-to-play-on-vivo-s17t-drfone-by-drfone-virtual-android/"><u>In 2024, Top 15 Augmented Reality Games Like Pokémon GO To Play On Vivo S17t | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/winstopscausedbynvidiaerror-now-fixed/"><u>WinStopsCausedByNvidiaError, Now Fixed</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-in-2024-import-audio-tracks-in-premiere-pro/"><u>[New] In 2024, Import Audio Tracks in Premiere Pro</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-revitalize-your-shots-10-cost-free-expandable-with-additional-luts/"><u>2024 Approved  Revitalize Your Shots  10 Cost-Free, Expandable With Additional LUTs</u></a></li>
<li><a href="https://network-issues.techidaily.com/smooth-operation-taming-amd-radeon-r9-on-windows-11/"><u>Smooth Operation: Taming AMD Radeon R9 on Windows 11</u></a></li>
<li><a href="https://network-issues.techidaily.com/hasten-intels-graphics-update-for-ws11-efficiency/"><u>Hasten Intel's Graphics Update for WS11 Efficiency</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-exploring-the-youtube-content-manager-toolkit/"><u>2024 Approved  Exploring the YouTube Content Manager Toolkit</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-get-steady-best-free-video-stabilization-programs-for-windows-and-mac/"><u>New Get Steady Best Free Video Stabilization Programs for Windows and Mac</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-game-changer-how-to-optimize-your-fb-giveaway-posts-for-2024/"><u>The Game-Changer  How to Optimize Your FB Giveaway Posts for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-facebook-live-cutting-edge-strategies-audiences-for-2024/"><u>[New] Facebook Live  Cutting-Edge Strategies Audiences for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-hideous-heroes-black-vs-gleaming-guardians-silver/"><u>In 2024, Hideous Heroes (Black) VS Gleaming Guardians (Silver)</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/revised-interview-scripts-for-captivating-audiences/"><u>Revised Interview Scripts for Captivating Audiences</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-discovering-realistic-insectoid-noise-samples/"><u>New Discovering Realistic Insectoid Noise Samples</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-solutions-to-find-your-oppo-k11-5g-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Solutions to Find Your Oppo K11 5G Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/display-failure-graphics-device-missing/"><u>Display Failure: Graphics Device Missing</u></a></li>
<li><a href="https://network-issues.techidaily.com/no-anomalies-detected-in-nvidia-setup-process/"><u>No Anomalies Detected in NVIDIA Setup Process</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixing-disabled-amd-freesync-connectivity/"><u>Fixing Disabled AMD FreeSync Connectivity</u></a></li>
<li><a href="https://network-issues.techidaily.com/instant-solution-to-diagonal-screen-issues/"><u>Instant Solution to Diagonal Screen Issues</u></a></li>
<li><a href="https://network-issues.techidaily.com/tech-support-resolved-case/"><u>Tech Support - Resolved Case</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-shooting-mastery-in-mobile-devices-via-optical-image-correction/"><u>In 2024, Shooting Mastery in Mobile Devices via Optical Image Correction</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-showcase-your-story-premium-ig-covers-for-iphone-users/"><u>In 2024, Showcase Your Story  Premium IG Covers for iPhone Users</u></a></li>
<li><a href="https://network-issues.techidaily.com/zoom-camera-repair-made-simple-your-2024-fix-guide/"><u>Zoom Camera Repair Made Simple: Your 2024 Fix Guide</u></a></li>
</ul></div>
