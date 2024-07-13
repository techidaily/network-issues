---
title: Winning WiFi Woes on WIN 10 & 11
date: 2024-07-12T01:06:58.273Z
updated: 2024-07-13T01:06:58.273Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: This Article Describes Winning WiFi Woes on WIN 10 & 11
excerpt: This Article Describes Winning WiFi Woes on WIN 10 & 11
keywords: WiFi Connection Issues,Windows 10 WiFi Troubleshooting,WiFi Network Problems Windows 11,Optimize WiFi Performance on PC,Resolve Wi-Fi Issues Windows 10/11,Fixing Common WiFi Problems on Microsoft Devices,Improve Wireless Network Speed on Windows
thumbnail: https://thmb.techidaily.com/7dc3990d7127eb4697b62478b58e508110f3846153c4979b3c9a42816701b4b9.jpg
---

## Winning WiFi Woes on WIN 10 & 11

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
<li><a href="https://network-issues.techidaily.com/solving-faded-screen-brightness-on-lenovo-laptops/"><u>Solving Faded Screen Brightness on Lenovo Laptops</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-irresistible-article-announcer/"><u>2024 Approved  Irresistible Article Announcer</u></a></li>
<li><a href="https://network-issues.techidaily.com/swiftly-overcome-sims-4-monochrome-errors/"><u>Swiftly Overcome Sims 4 Monochrome Errors</u></a></li>
<li><a href="https://network-issues.techidaily.com/solved-overcoming-internet-barriers-in-cod-cold-war/"><u>[SOLVED] Overcoming Internet Barriers in CoD Cold War</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-top-5-free-avi-video-editors/"><u>New In 2024, Top 5 Free AVI Video Editors</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-come-up-with-the-best-pokemon-team-on-poco-f5-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Come up With the Best Pokemon Team On Poco F5 5G? | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/discovered-backdoor-shadowplay-controls/"><u>Discovered Backdoor: ShadowPlay Controls</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-in-2024-9-top-notch-free-online-movie-creators/"><u>Updated In 2024, 9 Top-Notch Free Online Movie Creators</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-a-complete-guide-to-oem-unlocking-on-infinix-note-30-pro-by-drfone-android/"><u>In 2024, A Complete Guide To OEM Unlocking on Infinix Note 30 Pro</u></a></li>
<li><a href="https://network-issues.techidaily.com/how-to-fix-this-computer-does-not-meet-the-minimum-requirement-for-installing-software-when-installing-intel-graphics-driver/"><u>How to Fix This Computer Does Not Meet the Minimum Requirement for Installing Software. When Installing Intel Graphics Driver</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-unlock-itel-p55-5g-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>In 2024, Unlock Itel P55 5G Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-6-best-sim-unlock-services-that-actually-work-on-your-oppo-reno-8t-5g-device-by-drfone-android/"><u>The 6 Best SIM Unlock Services That Actually Work On Your Oppo Reno 8T 5G Device</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-developers-guide-to-top-10-android-apps-for-facebook-video-downloading/"><u>In 2024, Developer's Guide to Top 10 Android Apps for Facebook Video Downloading</u></a></li>
<li><a href="https://network-issues.techidaily.com/how-to-fix-monitor-blinking-issues/"><u>How to Fix Monitor Blinking Issues</u></a></li>
<li><a href="https://network-issues.techidaily.com/restored-unwavering-light-on-laptop-screen/"><u>Restored Unwavering Light on Laptop Screen</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-turning-creativity-into-comprehensive-captivating-tiktok-masterpieces-for-2024/"><u>[New] Turning Creativity Into Comprehensive, Captivating TikTok Masterpieces for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-streaming-stardom-and-salary-the-pewdiepie-profit-piece/"><u>2024 Approved  Streaming Stardom and Salary – The PewDiePie Profit Piece</u></a></li>
<li><a href="https://network-issues.techidaily.com/fix-the-sims-4-white-screen-issues-easily/"><u>Fix The Sims 4 White Screen Issues Easily</u></a></li>
<li><a href="https://network-issues.techidaily.com/guiding-users-through-screen-recovery-on-laptops/"><u>Guiding Users Through Screen Recovery on Laptops</u></a></li>
<li><a href="https://network-issues.techidaily.com/how-to-fix-lenovo-laptop-screen-flickering-problem/"><u>How to Fix Lenovo Laptop Screen Flickering Problem</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-top-10-essential-tiktok-insights-to-enhance-engagement-for-2024/"><u>[Updated] Top 10 Essential TikTok Insights to Enhance Engagement for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/banish-buffer-artifacts-watch-fluidly/"><u>Banish Buffer Artifacts, Watch Fluidly</u></a></li>
<li><a href="https://network-issues.techidaily.com/ways-to-stop-acer-display-twinkle/"><u>Ways to Stop Acer Display Twinkle</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-the-essential-list-6-high-performance-voice-alteration-apps-for-2024/"><u>New The Essential List 6 High-Performance Voice Alteration Apps for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/correcting-upside-down-screen-in-windows-11-update/"><u>Correcting Upside-Down Screen in Windows 11 Update</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-top-10-unique-tiktok-filters-sparking-engagement/"><u>[Updated] Top 10 Unique TikTok Filters Sparking Engagement</u></a></li>
<li><a href="https://network-issues.techidaily.com/interactive-lenovo-screen-issue-fixed-done/"><u>Interactive Lenovo Screen Issue Fixed [Done]</u></a></li>
<li><a href="https://network-issues.techidaily.com/addressing-invisible-graphics-cards-your-fix/"><u>Addressing Invisible Graphics Cards: Your Fix</u></a></li>
<li><a href="https://network-issues.techidaily.com/smooth-running-videos-on-updated-windows-11-systems/"><u>Smooth-Running Videos on Updated Windows 11 Systems</u></a></li>
<li><a href="https://network-issues.techidaily.com/swift-streams-over-sluggish-windows-internet/"><u>Swift Streams over Sluggish Windows Internet</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-adding-drama-to-videos-strikethrough-for-emphasis-and-clarity/"><u>[Updated] 2024 Approved  Adding Drama to Videos  Strikethrough for Emphasis and Clarity</u></a></li>
<li><a href="https://android-location-track.techidaily.com/5-ways-to-track-zte-nubia-flip-5g-without-app-drfone-by-drfone-virtual-android/"><u>5 Ways to Track ZTE Nubia Flip 5G without App | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/address-slow-response-roblox-windows-edition/"><u>Address Slow Response: Roblox Windows Edition</u></a></li>
<li><a href="https://network-issues.techidaily.com/eradicating-screen-flicker-on-windows-7/"><u>Eradicating Screen Flicker on Windows 7</u></a></li>
<li><a href="https://network-issues.techidaily.com/1719974710557-graphical-gone-wrong-monster-hunts-fix-successful/"><u>Graphical Gone Wrong? Monster Hunt's Fix Successful</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-your-pictures-after-realme-gt-neo-5-se-has-been-deleted-by-fonelab-android-recover-pictures/"><u>Recover your pictures after Realme GT Neo 5 SE has been deleted.</u></a></li>
<li><a href="https://network-issues.techidaily.com/streamline-wi-fi-connection-upgrade-with-new-card-for-os-xwindows/"><u>Streamline Wi-Fi Connection: Upgrade with New Card for OS X/Windows</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-high-quality-live-streaming-games-via-obs/"><u>[Updated] In 2024, High-Quality Live Streaming  Games via OBS</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-lenovos-secrets-to-effortless-screenshots/"><u>[Updated] 2024 Approved  Lenovo's Secrets to Effortless Screenshots</u></a></li>
<li><a href="https://network-issues.techidaily.com/immediate-fix-for-smooth-video-viewing/"><u>Immediate Fix for Smooth Video Viewing</u></a></li>
<li><a href="https://network-issues.techidaily.com/amds-fast-track-to-bug-free-tarkov/"><u>AMD's Fast-Track to Bug-Free Tarkov</u></a></li>
<li><a href="https://network-issues.techidaily.com/streamlined-guide-how-to-forget-your-computers-graphic-driver/"><u>Streamlined Guide: How to Forget Your Computer's Graphic Driver</u></a></li>
<li><a href="https://network-issues.techidaily.com/minimal-troubleshooting-guide-dormant-gpu-display/"><u>Minimal Troubleshooting Guide: Dormant GPU Display</u></a></li>
<li><a href="https://network-issues.techidaily.com/solutions-for-stabilizing-acer-lcd/"><u>Solutions for Stabilizing Acer LCD</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/enhance-performance-install-new-gpu-drivers/"><u>Enhance Performance: Install New GPU Drivers</u></a></li>
</ul></div>
