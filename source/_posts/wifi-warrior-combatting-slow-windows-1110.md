---
title: "WiFi Warrior: Combatting Slow Windows 11/10"
date: 2024-07-12T00:16:49.355Z
updated: 2024-07-13T00:16:49.355Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: "This Article Describes WiFi Warrior: Combatting Slow Windows 11/10"
excerpt: "This Article Describes WiFi Warrior: Combatting Slow Windows 11/10"
keywords: WiFi Performance Optimization,Fast Internet on Windows 11/10,Overcoming Latency Issues with Windows OS,Improving Network Speed in Windows Environment,Solutions for Sluggish WiFi Connectivity (Windows),Enhancing WiFi Speeds for Windows Users,Tips to Boost Your Internet Connection on Windows 11/10
thumbnail: https://thmb.techidaily.com/3fc14c15f73df5f4c8b19f8291c51668294576df82a5964da7eda1f1831694f2.jpg
---

## WiFi Warrior: Combatting Slow Windows 11/10

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
<li><a href="https://screen-sharing-recording.techidaily.com/updated-anonymous-surveillance-methods-hiding-private-data-effectively-for-2024/"><u>[Updated] Anonymous Surveillance Methods  Hiding Private Data Effectively for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/right-angle-sideways-screen-armageddon-ended/"><u>Right Angle: Sideways Screen Armageddon Ended</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-from-fixed-frames-to-fluid-films-an-introduction-to-pixizs-video-magic/"><u>2024 Approved  From Fixed Frames to Fluid Films  An Introduction to Pixiz's Video Magic</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-exclusive-selection-of-8-online-sites-featuring-golden-text-in-3d/"><u>2024 Approved  Exclusive Selection of 8 Online Sites Featuring Golden Text in 3D</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-profit-potential-unlocked-how-to-enroll-in-youtubes-membership/"><u>[Updated] Profit Potential Unlocked  How to Enroll in YouTube's Membership</u></a></li>
<li><a href="https://network-issues.techidaily.com/uninterrupted-video-experience-post-windows-10-upgrade/"><u>Uninterrupted Video Experience Post-Windows 10 Upgrade</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcoming-obscure-video-halt/"><u>Overcoming Obscure Video Halt</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-design-channels-get-free-visuals-now-for-2024/"><u>[Updated] Design Channels - Get Free Visuals Now for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/banish-display-defects-in-windows/"><u>Banish Display Defects in Windows</u></a></li>
<li><a href="https://network-issues.techidaily.com/d3d-startup-error-successfully-overcome/"><u>D3D Startup Error, Successfully Overcome</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-fb-video-direction-whats-the-right-angle-in-2024/"><u>[Updated] FB Video Direction  What's the Right Angle, In 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/improve-windows-graphics-by-installing-current-intel-drivers/"><u>Improve Windows Graphics by Installing Current Intel Drivers</u></a></li>
<li><a href="https://network-issues.techidaily.com/repaired-addressing-the-internet-disconnect-in-cod-cold-war/"><u>[REPAIRED] Addressing the Internet Disconnect in CoD Cold War</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-virtual-realm-highs-the-best-iphoneandroid-apps-for-2024/"><u>[New] Virtual Realm Highs  The Best iPhone/Android Apps for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-no-complications-in-hdr-a-thorough-review/"><u>In 2024, No Complications in HDR  A Thorough Review</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/two-ways-to-track-my-boyfriends-apple-iphone-12-pro-without-him-knowing-drfone-by-drfone-virtual-ios/"><u>Two Ways to Track My Boyfriends Apple iPhone 12 Pro without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-lit-tales-in-just-a-minute/"><u>2024 Approved  Lit Tales in Just a Minute</u></a></li>
<li><a href="https://network-issues.techidaily.com/dampening-discoloration-in-win7-output/"><u>Dampening Discoloration in Win7 Output</u></a></li>
<li><a href="https://network-issues.techidaily.com/visual-configuration-saved-and-fixed/"><u>Visual Configuration Saved & Fixed</u></a></li>
<li><a href="https://network-issues.techidaily.com/overhauling-amd-radeon-r9-driver-stability-in-w10/"><u>Overhauling AMD Radeon R9 Driver Stability in W10</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-easy-walkthrough-for-old-facebook-stories-on-laptops-and-phones/"><u>[New] Easy Walkthrough for Old Facebook Stories on Laptops & Phones</u></a></li>
<li><a href="https://extra-hints.techidaily.com/premium-android-listening-helpers/"><u>Premium Android Listening Helpers</u></a></li>
<li><a href="https://network-issues.techidaily.com/atheros-wi-fi-driver-enhancement-by-qualcomm-for-win11-users/"><u>Atheros Wi-Fi Driver Enhancement by Qualcomm for Win11 Users</u></a></li>
<li><a href="https://network-issues.techidaily.com/revel-in-new-geforce-210-update-for-windows-enthusiasts/"><u>Revel In New GeForce 210 Update For Windows Enthusiasts</u></a></li>
<li><a href="https://network-issues.techidaily.com/fastest-way-getting-rid-of-your-systems-graphics-drivers/"><u>Fastest Way: Getting Rid of Your System's Graphics Drivers</u></a></li>
<li><a href="https://network-issues.techidaily.com/hassle-free-intel-graphics-3000-win11-upgrade/"><u>Hassle-Free Intel Graphics 3000 Win11 Upgrade</u></a></li>
<li><a href="https://network-issues.techidaily.com/clearing-up-blurry-textures-in-far-cry-6-gameplay/"><u>Clearing Up Blurry Textures in Far Cry 6 Gameplay</u></a></li>
<li><a href="https://network-issues.techidaily.com/wi-fi-driver-uninstalled-reinstate-windows-10-card/"><u>Wi-Fi Driver Uninstalled? Reinstate Windows 10 Card</u></a></li>
<li><a href="https://network-issues.techidaily.com/upgraded-windows-experience-release-of-new-amd-radeon-hd-6950-drivers/"><u>Upgraded Windows Experience: Release of New AMD Radeon HD 6950 Drivers</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcoming-screen-flip-issue-with-windows-11/"><u>Overcoming Screen Flip Issue with Windows 11</u></a></li>
<li><a href="https://network-issues.techidaily.com/video-streaming-problems-on-windows-10-after-upgrade-solved/"><u>Video Streaming Problems on Windows 10 After Upgrade [Solved]</u></a></li>
<li><a href="https://network-issues.techidaily.com/tips-for-reinstating-missing-gpu-on-system/"><u>Tips for Reinstating Missing GPU on System</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixing-absent-display-preferences-on-nvidia-graphics/"><u>Fixing Absent Display Preferences on Nvidia Graphics</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-navigating-high-speed-video-transitions-with-ease/"><u>In 2024, Navigating High-Speed Video Transitions with Ease</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/android-unlock-code-sim-unlock-your-realme-gt-3-phone-and-remove-locked-screen-by-drfone-android/"><u>Android Unlock Code Sim Unlock Your Realme GT 3 Phone and Remove Locked Screen</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/precision-audio-capturing-techniques-in-overwatch-for-2024/"><u>Precision Audio Capturing Techniques in Overwatch for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/reverberation-artisan-collection/"><u>Reverberation Artisan Collection</u></a></li>
<li><a href="https://network-issues.techidaily.com/revamping-bdr-for-win-versions-11-to-7/"><u>Revamping BDR for Win Versions 11 to 7</u></a></li>
<li><a href="https://network-issues.techidaily.com/reactivating-all-available-screen-configurations-on-gpu/"><u>Reactivating All Available Screen Configurations on GPU</u></a></li>
<li><a href="https://network-issues.techidaily.com/display-system-recovered-after-hang-up/"><u>Display System Recovered After Hang-Up</u></a></li>
<li><a href="https://network-issues.techidaily.com/illuminate-darkness-in-lenovo-notebooks/"><u>Illuminate Darkness in Lenovo Notebooks</u></a></li>
<li><a href="https://network-issues.techidaily.com/ending-dark-windows-display-post-update/"><u>Ending Dark Windows Display Post-Update</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/top-5-best-video-denoisers-for-2024/"><u>Top 5 Best Video Denoisers for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/optimize-windows-11-screen-size-appearance/"><u>Optimize Windows 11 Screen Size Appearance</u></a></li>
<li><a href="https://network-issues.techidaily.com/the-hidden-truth-about-wi-fi-absence-in-windows-11/"><u>The Hidden Truth About Wi-Fi Absence in Windows 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/unveiling-the-art-of-podcast-storytelling-expert-tips-plus-10plus-sample-scripts/"><u>Unveiling the Art of Podcast Storytelling  Expert Tips + 10+ Sample Scripts</u></a></li>
<li><a href="https://network-issues.techidaily.com/windows-11-advanced-display-missing-adjustments/"><u>Windows 11 Advanced Display Missing Adjustments</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-can-we-bypass-realme-gt-neo-5-se-frp-by-drfone-android/"><u>How Can We Bypass Realme GT Neo 5 SE FRP?</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/winning-gameplay-capture-with-fbx/"><u>Winning Gameplay Capture with FBX</u></a></li>
</ul></div>
