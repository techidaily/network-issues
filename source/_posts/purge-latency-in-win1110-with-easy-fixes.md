---
title: Purge Latency in Win11/10 with Easy Fixes
date: 2024-07-12T01:22:03.685Z
updated: 2024-07-13T01:22:03.685Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: This Article Describes Purge Latency in Win11/10 with Easy Fixes
excerpt: This Article Describes Purge Latency in Win11/10 with Easy Fixes
keywords: Windows 11 Latency Reduction,Latency Issues in Windows 10,Quick Fixes for System Lag,Reduce PC Response Time,Optimize Win11/10 Performance,Improve Windows Latency,Streamline Computer Speed
thumbnail: https://thmb.techidaily.com/cb769af3708fc15b594c9ede31a115d7b902d54d4fbcec56dcebaeb9d186f784.jpg
---

## Purge Latency in Win11/10 with Easy Fixes

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
<li><a href="https://network-issues.techidaily.com/fixing-led-backlight-stability-problems/"><u>Fixing LED Backlight Stability Problems</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/prolonging-gopro-battery-usage-efficiency-for-2024/"><u>Prolonging GoPro Battery Usage Efficiency for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/adjustment-made-added-gpu-driver-for-amd-to-windows-11/"><u>[ADJUSTMENT MADE] Added GPU Driver for AMD to Windows 11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-command-and-conquer-the-pinnacle-of-strategic-sagas-in-7-total-war-games/"><u>[New] Command & Conquer  The Pinnacle of Strategic Sagas in 7 Total War Games</u></a></li>
<li><a href="https://network-issues.techidaily.com/no-longer-disturbed-by-flickering-win11-monitors/"><u>No Longer Disturbed by Flickering Win11 Monitors</u></a></li>
<li><a href="https://network-issues.techidaily.com/mastering-switchable-graphic-performance-on-latest-windows-11/"><u>Mastering Switchable Graphic Performance on Latest Windows 11</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-top-15-augmented-reality-games-like-pokemon-go-to-play-on-vivo-s17t-drfone-by-drfone-virtual-android/"><u>In 2024, Top 15 Augmented Reality Games Like Pokémon GO To Play On Vivo S17t | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-2023s-fb-url-vault-securely-access-8-free-downloads-online/"><u>[Updated] In 2024, 2023'S FB URL Vault  Securely Access 8 Free Downloads Online</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/1714924523805-updated-how-to-convert-whatsapp-audio-to-mp3-in-the-quickest-way/"><u>Updated How to Convert WhatsApp Audio to Mp3 in the Quickest Way?</u></a></li>
<li><a href="https://network-issues.techidaily.com/how-to-fix-far-cry-6-blurry-texture-issue/"><u>How to Fix Far Cry 6 Blurry Texture Issue</u></a></li>
<li><a href="https://network-issues.techidaily.com/displaysystem-halt-on-windows-works-resolved/"><u>DisplaySystem Halt on WIndows (Works Resolved)</u></a></li>
<li><a href="https://network-issues.techidaily.com/eradicate-black-display-on-win10/"><u>Eradicate Black Display on Win10</u></a></li>
<li><a href="https://network-issues.techidaily.com/tighten-up-latency-play-faster-in-roblox/"><u>Tighten Up Latency: Play Faster in Roblox</u></a></li>
<li><a href="https://network-issues.techidaily.com/direct-installation-steps-adding-compatible-wi-fi-adapter-on-computers/"><u>Direct Installation Steps: Adding Compatible Wi-Fi Adapter on Computers</u></a></li>
<li><a href="https://network-issues.techidaily.com/correct-blurring-screens-in-devices/"><u>Correct Blurring Screens in Devices</u></a></li>
<li><a href="https://network-issues.techidaily.com/taming-fallout-4-pc-issues-effortlessly/"><u>Taming Fallout 4 PC Issues Effortlessly</u></a></li>
<li><a href="https://network-issues.techidaily.com/instantly-amend-intel-g3000-graphics-win11-way/"><u>Instantly Amend Intel G3000 Graphics, Win11 Way</u></a></li>
<li><a href="https://network-issues.techidaily.com/solving-c1900101-error-during-installation/"><u>Solving C1900101 Error During Installation</u></a></li>
<li><a href="https://network-issues.techidaily.com/solved-twitch-black-screen-issues/"><u>[SOLVED] Twitch Black Screen Issues</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-enhance-reach-the-top-10-highlight-strategies-unveiled/"><u>[New] In 2024, Enhance Reach  The Top 10 Highlight Strategies Unveiled</u></a></li>
<li><a href="https://network-issues.techidaily.com/mastering-win10-and-geforce-98nvidia/"><u>Mastering Win10 & GeForce 98/Nvidia</u></a></li>
<li><a href="https://network-issues.techidaily.com/remove-delays-in-live-streaming-videos/"><u>Remove Delays in Live Streaming Videos</u></a></li>
<li><a href="https://network-issues.techidaily.com/1719974411432-zero-tolerance-for-zoom-cameras-gone-wrong-weve-got-the-fixes/"><u>Zero Tolerance for Zoom Cameras Gone Wrong? We've Got the Fixes</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixed-no-device-detected-for-wireless-connection-on-pc/"><u>[FIXED] No Device Detected for Wireless Connection on PC</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-top-5-android-clippers-essential-image-editing-apps/"><u>[Updated] Top 5 Android Clippers  Essential Image Editing Apps</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-secrets-unveiled-for-documenting-real-time-sports/"><u>2024 Approved  Secrets Unveiled for Documenting Real-Time Sports</u></a></li>
<li><a href="https://network-issues.techidaily.com/steps-for-stable-hp-display-function/"><u>Steps for Stable HP Display Function</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolved-incompatible-device-errors-in-windows/"><u>Resolved Incompatible Device Errors in Windows</u></a></li>
<li><a href="https://network-issues.techidaily.com/eliminate-unwanted-screen-flashing/"><u>Eliminate Unwanted Screen Flashing</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-from-amateurs-to-pros-mastering-mac-audio-in-audacity/"><u>[New] In 2024, From Amateurs to Pros  Mastering Mac Audio in Audacity</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-rise-through-the-instagram-rankings-fast/"><u>[New] In 2024, Rise Through the Instagram Rankings Fast</u></a></li>
<li><a href="https://network-issues.techidaily.com/qualcomms-patch-atheros-qca61x4-networking-fixed-in-win11/"><u>Qualcomm's Patch: Atheros QCA61x4 Networking Fixed in Win11</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-top-10-tiktok-analytics-tools-to-improve-account-performance/"><u>[New] Top 10 Tiktok Analytics Tools to Improve Account Performance</u></a></li>
<li><a href="https://network-issues.techidaily.com/1719974803129-instantly-elevate-your-systems-intellg3000-on-win11/"><u>Instantly Elevate Your System's IntellG3000 on Win11</u></a></li>
<li><a href="https://network-issues.techidaily.com/win11-display-problems-creators-upgrade/"><u>Win11 Display Problems: Creators Upgrade</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-gps-location-on-oneplus-12r-easily-and-safely-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change GPS Location on OnePlus 12R Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-interactive-storytelling-vrs-entertainment-potential-for-2024/"><u>[New] Interactive Storytelling  VR's Entertainment Potential for 2024</u></a></li>
</ul></div>
