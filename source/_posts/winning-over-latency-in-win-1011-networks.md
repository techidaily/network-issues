---
title: Winning Over Latency in Win 10/11 Networks
date: 2024-07-12T00:24:59.169Z
updated: 2024-07-13T00:24:59.169Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: This Article Describes Winning Over Latency in Win 10/11 Networks
excerpt: This Article Describes Winning Over Latency in Win 10/11 Networks
keywords: Latency Reduction,Network Latency Improvement,Windows 10 Network Optimization,Low Latency Configuration (Windows),Smooth Win 10/11 Network Experience,Win 10/11 Latency Solutions,Performance Tuning Win 10/11 Networks
thumbnail: https://thmb.techidaily.com/104fcc0c1e7ba0020bac11684b73c47c97661f3e4742e08d1374a286a48bed4c.jpg
---

## Winning Over Latency in Win 10/11 Networks

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
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-instantvideo-snipper-fb-edition/"><u>[New] In 2024, InstantVideo Snipper - FB Edition</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-10-best-podcast-recording-software/"><u>In 2024, 10 Best Podcast Recording Software</u></a></li>
<li><a href="https://network-issues.techidaily.com/decrease-fallout-4-crashes-in-windows/"><u>Decrease Fallout 4 Crashes in Windows</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-life360-from-tracking-you-on-nokia-c02-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On Nokia C02? | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/corrected-absence-of-advanced-display-in-windows-11/"><u>[Corrected] Absence of Advanced Display in Windows 11</u></a></li>
<li><a href="https://network-issues.techidaily.com/system-revived-graphics-card-driver-issue-resolved/"><u>System Revived: Graphics Card Driver Issue Resolved</u></a></li>
<li><a href="https://network-issues.techidaily.com/graphics-driver-43-troubleshooted/"><u>Graphics Driver 43 Troubleshooted</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcoming-disabled-display-settings-in-nvidia-control-panel/"><u>Overcoming Disabled Display Settings in NVidia Control Panel</u></a></li>
<li><a href="https://network-issues.techidaily.com/narrowing-excessive-win10-display/"><u>Narrowing Excessive Win10 Display</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixed-display-issue-fullscreen-window-not-showed/"><u>Fixed Display Issue - FullScreen Window Not Showed</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-11-best-color-correction-and-color-grading-tutorial-for-2024/"><u>[New] 11 Best Color Correction and Color Grading Tutorial for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-easy-integration-merging-igtv-and-instagram-stories/"><u>[New] Easy Integration  Merging IGTV & Instagram Stories</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolved-dxgkrnlsys-causing-winbsod-error/"><u>[Resolved] dxgkrnl.sys Causing WinBSOD Error</u></a></li>
<li><a href="https://network-issues.techidaily.com/stoplight-flash-on-laptop-ceases/"><u>Stoplight Flash on Laptop Ceases</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/0-editing-skills-every-new-youtuber-must-know-for-2024/"><u>Top 10 Editing Skills Every New YouTuber Must Know for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/bronze-blessings-god-of-war-boost/"><u>Bronze Blessings: God of War Boost</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-13-pro-to-other-iphone-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 13 Pro To Other iPhone devices? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/apply-these-techniques-to-improve-how-to-detect-fake-gps-location-on-honor-x7b-drfone-by-drfone-virtual-android/"><u>Apply These Techniques to Improve How to Detect Fake GPS Location On Honor X7b | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/win11-dark-display-fix-guide/"><u>Win11 Dark Display, Fix Guide</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-revolutionary-approaches-for-rapid-srt-to-text-switch-for-2024/"><u>[Updated] Revolutionary Approaches for Rapid SRT to Text Switch for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-incorporating-captions-in-photography-a-user-friendly-guide-on-pc-and-mac/"><u>2024 Approved  Incorporating Captions in Photography  A User-Friendly Guide on PC & Mac</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-nokia-c12-plus-drfone-by-drfone-virtual-android/"><u>Here are Some Pro Tips for Pokemon Go PvP Battles On Nokia C12 Plus | Dr.fone</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-2024-approved-guide-to-high-quality-voice-capture-with-your-samsung-galaxy-s10s9/"><u>Updated 2024 Approved Guide to High-Quality Voice Capture with Your Samsung Galaxy S10/S9</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-zoom-into-your-workspace-learn-screen-casting-via-ezvide-for-2024/"><u>[New] Zoom Into Your Workspace  Learn Screen Casting via EZvide for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/1719974205145-upgrade-your-systems-graphical-capability-with-intel-graphics-3000-on-windows-10-easily/"><u>Upgrade Your System's Graphical Capability with Intel Graphics 3000 on Windows 10 Easily</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-journey-into-the-heart-of-tiktoks-anime-a-convergence-of-dance-music-and-imagery/"><u>[Updated] Journey Into the Heart of TikTok's Anime  A Convergence of Dance, Music & Imagery</u></a></li>
<li><a href="https://network-issues.techidaily.com/bloodied-barbarian-balance-adjustment/"><u>Bloodied Barbarian Balance Adjustment</u></a></li>
<li><a href="https://network-issues.techidaily.com/restored-graphic-functionality-on-win-10/"><u>Restored Graphic Functionality on Win 10</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-top-qp-value-enhancing-gradual-movement-vids/"><u>In 2024, Top QP Value Enhancing Gradual Movement Vids</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-jailbreak-icloud-locked-apple-iphone-15-plus-by-drfone-ios/"><u>How to jailbreak iCloud locked Apple iPhone 15 Plus</u></a></li>
<li><a href="https://network-issues.techidaily.com/unmasking-the-non-detection-of-pc-gpu-issue/"><u>Unmasking the Non-Detection of PC GPU Issue</u></a></li>
<li><a href="https://network-issues.techidaily.com/eliminating-switchable-graphics-error-with-intel-and-nvidia-on-win10/"><u>Eliminating Switchable Graphics Error with Intel & Nvidia on Win10</u></a></li>
<li><a href="https://network-issues.techidaily.com/win11-update-by-qualcomm-improves-stability-of-atheros-drivers/"><u>Win11 Update by Qualcomm Improves Stability of Atheros Drivers</u></a></li>
<li><a href="https://network-issues.techidaily.com/examining-amds-innovation-and-its-effect-on-gaming-hardware-sales/"><u>Examining AMD's Innovation and Its Effect on Gaming Hardware Sales</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-looking-for-a-location-changer-on-itel-p40plus-look-no-further-drfone-by-drfone-virtual-android/"><u>In 2024, Looking For A Location Changer On Itel P40+? Look No Further | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/the-significance-of-4k-quad-hd-imaging-clarity/"><u>The Significance of 4K Quad-HD Imaging Clarity</u></a></li>
<li><a href="https://network-issues.techidaily.com/screen-reset-nvidia-drivers-are-back/"><u>Screen Reset: Nvidia Drivers Are Back</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-direct-transmission-of-google-meet-into-your-youtube-playlist/"><u>[New] 2024 Approved  Direct Transmission of Google Meet Into Your YouTube Playlist</u></a></li>
<li><a href="https://network-issues.techidaily.com/custom-resolution-restored-on-pc-win10/"><u>Custom Resolution Restored on PC (Win10)</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-t-view-mkv-movies-content-on-galaxy-m54-5g-by-aiseesoft-video-converter-play-mkv-on-android/"><u>Can’t view MKV movies content on Galaxy M54 5G</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-tiktok-to-see-more-content-on-your-oppo-reno-11-pro-5g-drfone-by-drfone-virtual-android/"><u>How to Change Location on TikTok to See More Content On your Oppo Reno 11 Pro 5G | Dr.fone</u></a></li>
</ul></div>
