---
title: Purge Latency in Win11/10 with Easy Fixes
date: 2024-10-30T19:54:21.464Z
updated: 2024-11-04T17:15:53.947Z
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135414/19272" target="_top" id="2135414">
  <img src="//a.impactradius-go.com/display-ad/19272-2135414" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135414/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1061528/11832" target="_top" id="1061528">
  <img src="//a.impactradius-go.com/display-ad/11832-1061528" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1061528/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Fix 3: Update your WiFi drivers

 This problem may occur if you are using the wrong/outdated WiFi drivers. So you should update your WiFi/network adapter driver drivers to see if it fixes your problem. If you don’t have the time, patience, or computer skills to update your drivers manually, you can do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.**Driver Easy handles it all.**

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and**install** Driver Easy.
2. Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://www.drivereasy.com/wp-content/uploads/2024/05/DE-scan-now-6.0.jpg)
3. Click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  which comes with **full support**  and a **30-day money-back**  guarantee. You’ll be prompted to upgrade when you click Update All. If you’re not ready to buy the Pro version, Driver Easy offers a 7-day free trial which includes access to all the Pro features such as high-speed download and one-click install. You won’t be charged anything until your 7-day trial has ended.)  

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134228/18498" target="_top" id="2134228">
  <img src="//a.impactradius-go.com/display-ad/18498-2134228" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134228/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://www.drivereasy.com/wp-content/uploads/2017/10/de-update-all-wireless-6.0.jpg)

**The Pro version of Driver Easy** comes with _full technical support_ . If you need assistance, please contact **Driver Easy’s support team** at **[support@drivereasy.com](mailto:support@drivereasy.com) .**

 Restart your computer and see if the **Windows 10 Slow Internet** problem has been resolved. If yes, then congrats! If the issue still persists, please move on to**Fix 4** , below.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139117/17108" target="_top" id="2139117">
  <img src="//a.impactradius-go.com/display-ad/17108-2139117" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139117/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2080342/19272" target="_top" id="2080342">
  <img src="//a.impactradius-go.com/display-ad/19272-2080342" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080342/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148637/16836" target="_top" id="2148637">
  <img src="//a.impactradius-go.com/display-ad/16836-2148637" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148637/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Click **Yes** when prompted to confirm.
2. Copy & paste **netsh interface tcp show global** into the window and press**Enter** . Then check if**Receive Window Auto-Tuning Level**  is set to**normal** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/img_5b70ff100133c.jpg)
3. If yes, you’ll have to copy & paste**netsh int tcp set global autotuninglevel=disabled** into the window and press**Enter** to disable it.  

![](https://images.drivereasy.com/wp-content/uploads/2018/08/img_5b7134aa2923c.jpg)
4. Check to see if your**Windows 10 slow Internet** problem has been solved. If the issue still lingers on, don’t worry, here’s one more fix to try.

---

<!-- affiliate ads begin -->
<span id="1975555">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975555.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975555">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975555.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975555%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975555/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094415/7443" target="_top" id="2094415">
  <img src="//a.impactradius-go.com/display-ad/7443-2094415" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094415/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://youtube-zero.techidaily.com/024-approved-optimizing-your-yt-ad-revenue-with-effective-monetization-audits/"><u>[New] 2024 Approved Optimizing Your YT Ad Revenue with Effective Monetization Audits</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-a-step-by-step-guide-on-applying-cc-rights-effectively/"><u>[New] In 2024, A Step-by-Step Guide on Applying CC Rights Effectively</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-secure-quick-and-simple-screenshot-techniques-for-w8-users/"><u>[Updated] Secure, Quick & Simple Screenshot Techniques for W8 Users</u></a></li>
<li><a href="https://network-issues.techidaily.com/windows-overcoming-slow-connectivity-issues/"><u>[WINDOWS] Overcoming Slow Connectivity Issues</u></a></li>
<li><a href="https://win-web3.techidaily.com/comment-contourner-la-fonction-deplacer-vers-manquante-dans-windows-11-3-facons-efficaces/"><u>Comment Contourner La Fonction 'Déplacer Vers' Manquante Dans Windows 11 : 3 Façons Efficaces</u></a></li>
<li><a href="https://network-issues.techidaily.com/conquer-whiteout-sims-errors/"><u>Conquer Whiteout Sims Errors</u></a></li>
<li><a href="https://network-issues.techidaily.com/ensure-static-screens-in-windows-11-settings/"><u>Ensure Static Screens in Windows 11 Settings</u></a></li>
<li><a href="https://network-issues.techidaily.com/graphics-performance-restored/"><u>Graphics Performance Restored</u></a></li>
<li><a href="https://network-issues.techidaily.com/hustle-past-game-hold-ups/"><u>Hustle Past Game Hold-Ups</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-10-best-youtube-music-reaction-videos-2023/"><u>In 2024, 10 Best YouTube Music Reaction Videos 2023</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-rotate-your-avi-videos-for-free-top-16-software-and-apps/"><u>New 2024 Approved Rotate Your AVI Videos for Free Top 16 Software and Apps</u></a></li>
<li><a href="https://network-issues.techidaily.com/new-driver-release-amd-radeon-hd-6950-for-win10/"><u>New Driver Release: AMD Radeon HD 6950 for Win10</u></a></li>
<li><a href="https://win11.techidaily.com/quick-start-engaging-snipping-tool-on-windows-11/"><u>Quick Start: Engaging Snipping Tool on Windows 11</u></a></li>
<li><a href="https://fox-that.techidaily.com/ultimate-fixes-for-stuck-airpods-enabling-automatic-device-transition/"><u>Ultimate Fixes for Stuck AirPods: Enabling Automatic Device Transition</u></a></li>
<li><a href="https://techtrends.techidaily.com/ultimate-selection-the-6-greatest-mario-games-available-for-windows-and-mac/"><u>Ultimate Selection: The 6 Greatest Mario Games Available for Windows & Mac</u></a></li>
</ul></div>

