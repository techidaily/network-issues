---
title: "Graphic Glitch Cleared: Driver Restarted Successfully"
date: 2024-07-02T03:17:17.463Z
updated: 2024-07-03T03:17:17.463Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: "This Article Describes Graphic Glitch Cleared: Driver Restarted Successfully"
excerpt: "This Article Describes Graphic Glitch Cleared: Driver Restarted Successfully"
keywords: Graphic Error Resolution,Crash Recovery for Drivers,Restart Driver After Glitch,Graphic System Error Troubleshooting,Drivers' Performance Optimization,Glitch-Free Graphic Operations,Successful Driver Restart Techniques
thumbnail: https://thmb.techidaily.com/528781abe64eff7e57733460b453c6895f2f9ec8900c30ab49d86e203a9429b2.jpg
---

## Graphic Glitch Cleared: Driver Restarted Successfully

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
<li><a href="https://network-issues.techidaily.com/1719974349923-efficiently-upgrade-intel-g3000-driver-in-windows-11/"><u>Efficiently Upgrade Intel G3000 Driver in Windows 11.</u></a></li>
<li><a href="https://network-issues.techidaily.com/rectifying-driver-issues-for-stable-win-minecraft-experience/"><u>Rectifying Driver Issues for Stable Win-Minecraft Experience</u></a></li>
<li><a href="https://network-issues.techidaily.com/rectifying-ripple-on-windows-7-screens/"><u>Rectifying Ripple on Windows 7 Screens</u></a></li>
<li><a href="https://network-issues.techidaily.com/restoring-display-settings-configuration-functionality/"><u>Restoring Display Settings Configuration Functionality</u></a></li>
<li><a href="https://network-issues.techidaily.com/tweak-hidden-gpu-status/"><u>Tweak Hidden GPU Status</u></a></li>
<li><a href="https://network-issues.techidaily.com/removing-mysterious-monitor-darkness/"><u>Removing Mysterious Monitor Darkness</u></a></li>
<li><a href="https://network-issues.techidaily.com/mastering-wows-bug-519-solutions-step-by-step/"><u>Mastering WoW's Bug #519: Solutions Step-by-Step</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-ipogo-will-be-the-new-ispoofer-on-samsung-galaxy-s23-fe-drfone-by-drfone-virtual-android/"><u>In 2024, iPogo will be the new iSpoofer On Samsung Galaxy S23 FE? | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/normalizing-audio-in-davinci-resolve-a-step-by-step-guide-for-2024/"><u>Normalizing Audio in DaVinci Resolve A Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-call-logs-from-oppo-a78-by-fonelab-android-recover-call-logs/"><u>How to rescue lost call logs from Oppo A78</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-prime-selection-of-webcams-for-optimal-zoom-video-quality/"><u>2024 Approved  Prime Selection of Webcams for Optimal Zoom Video Quality</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-get-the-apple-id-verification-code-on-apple-iphone-11-pro-in-the-best-ways-by-drfone-ios/"><u>In 2024, How To Get the Apple ID Verification Code On Apple iPhone 11 Pro in the Best Ways</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-airplane-mode-turn-off-gps-location-on-oppo-reno-11-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Does Airplane Mode Turn off GPS Location On Oppo Reno 11 5G? | Dr.fone</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/o-turn-on-av1-settings-on-youtube-and-why-you-should-do-it-for-2024/"><u>How to Turn on AV1 Settings on YouTube and Why You Should Do It for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-remove-a-previously-synced-google-account-from-your-tecno-pop-7-pro-by-drfone-android/"><u>How to Remove a Previously Synced Google Account from Your Tecno Pop 7 Pro</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-experts-guide-to-infinite-space-utilization/"><u>2024 Approved  Expert's Guide to Infinite Space Utilization</u></a></li>
</ul></div>
