---
title: "Corrected Graphics Issue: Driver Reset Successful"
date: 2024-07-12T00:41:55.834Z
updated: 2024-07-13T00:41:55.834Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: "This Article Describes Corrected Graphics Issue: Driver Reset Successful"
excerpt: "This Article Describes Corrected Graphics Issue: Driver Reset Successful"
keywords: Graphics Driver Fix,Resolve Display Issues Windows,Successful Driver Reinstallation Guide,Graphics Error Troubleshooting,Fix Graphics Glitch After Reset,Improve Computer Graphics Performance,Correct Graphic Driver Problems Windows 10
thumbnail: https://thmb.techidaily.com/bf6ce710c3b83bd0300511eb0a114987cd6a644274eb54a39fdf9870b6c3de78.jpg
---

## Corrected Graphics Issue: Driver Reset Successful

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
<li><a href="https://network-issues.techidaily.com/windows-11-enhanced-viewport-management/"><u>Windows 11: Enhanced Viewport Management</u></a></li>
<li><a href="https://network-issues.techidaily.com/hulks-hurdle-purchase-paralysis/"><u>Hulk's Hurdle: Purchase Paralysis</u></a></li>
<li><a href="https://network-issues.techidaily.com/nvidia-setup-unhindered-success/"><u>Nvidia Setup: Unhindered Success</u></a></li>
<li><a href="https://extra-resources.techidaily.com/economical-skydrive-vault-mass-file-management-on-a-dime/"><u>Economical Skydrive Vault  Mass File Management on a Dime</u></a></li>
<li><a href="https://network-issues.techidaily.com/apex-hack-proofing-guide-instant-troubleshooting/"><u>Apex Hack-Proofing Guide: Instant Troubleshooting</u></a></li>
<li><a href="https://network-issues.techidaily.com/shine-and-shimmer-no-more-dells-new-normal/"><u>Shine and Shimmer No More: Dell's New Normal</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-20-free-after-effects-logo-reveal-templates-for-2024/"><u>New 20 Free After Effects Logo Reveal Templates for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/1719974224760-step-up-graphics-performance-update-intels-hd-3000-driver-in-windows-10/"><u>Step up Graphics Performance: Update Intel's HD 3000 Driver in Windows 10</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixing-screen-config-issue-in-win-710/"><u>Fixing Screen Config Issue in Win 7/10</u></a></li>
<li><a href="https://network-issues.techidaily.com/eradicate-off-screen-joints/"><u>Eradicate Off-Screen Joints</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-premier-hd-theater-experience-best-players-list/"><u>In 2024, Premier HD Theater Experience - Best Players List</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolved-slim-monitor-glitches-in-win11/"><u>Resolved Slim Monitor Glitches in Win11</u></a></li>
<li><a href="https://network-issues.techidaily.com/from-problem-to-solution-amd-driver-now-detectable-on-wndows-10/"><u>From Problem to Solution: AMD Driver Now Detectable on Wndows 10</u></a></li>
<li><a href="https://techidaily.com/sign-fodt-file-documents-online-for-free-by-ldigisigner-sign-a-word-sign-a-word/"><u>Sign .fodt file Documents Online for Free</u></a></li>
<li><a href="https://network-issues.techidaily.com/monitor-muted-by-latest-graphics-update/"><u>Monitor Muted by Latest Graphics Update</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/rafting-charismatic-videos-with-diy-camera-setups-for-2024/"><u>[New] Crafting Charismatic Videos with DIY Camera Setups for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-kid-proof-camcorders-the-top-11-beginner-friendly-choices/"><u>2024 Approved  Kid-Proof Camcorders  The Top 11 Beginner-Friendly Choices</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-vpna-to-fake-gps-location-on-nubia-red-magic-8s-proplus-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use VPNa to Fake GPS Location On Nubia Red Magic 8S Pro+ | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/decoding-wow-flaw-code-issue-51900319/"><u>Decoding WoW Flaw Code: Issue #51900319</u></a></li>
<li><a href="https://network-issues.techidaily.com/god-of-war-glitches-gone/"><u>God of War Glitches Gone</u></a></li>
<li><a href="https://network-issues.techidaily.com/quickly-fixed-qualcomms-atheros-wi-fi-drivers-on-win11/"><u>Quickly Fixed Qualcomm's Atheros Wi-Fi Drivers on Win11</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-the-full-picture-of-ustream-and-analogous-services/"><u>[Updated] The Full Picture of Ustream & Analogous Services</u></a></li>
<li><a href="https://network-issues.techidaily.com/quick-fix-for-dell-screen-flicker-issue/"><u>Quick Fix for Dell Screen Flicker Issue</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-sharing-photos-and-videos-between-android-and-iphone/"><u>[New] Sharing Photos & Videos Between Android & iPhone</u></a></li>
<li><a href="https://network-issues.techidaily.com/qualcomm-wi-fi-qca61x4-fixed-in-win10-for-smooth-connectivity/"><u>Qualcomm Wi-Fi QCA61x4 Fixed in Win10 for Smooth Connectivity</u></a></li>
<li><a href="https://screen-capture.techidaily.com/apowersoft-screen-recordings-critical-insights-and-alternatives/"><u>Apowersoft Screen Recordings - Critical Insights and Alternatives</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixing-faulty-video-cards-for-enhanced-mc-play-on-windows/"><u>Fixing Faulty Video Cards for Enhanced MC Play on Windows</u></a></li>
<li><a href="https://network-issues.techidaily.com/graphics-glitch-recent-purchase-no-display/"><u>Graphics Glitch: Recent Purchase No Display</u></a></li>
<li><a href="https://network-issues.techidaily.com/securing-win-minecraft-stability-by-addressing-driver-issues/"><u>Securing Win-Minecraft Stability by Addressing Driver Issues</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-best-ways-on-how-to-unlockbypassswiperemove-honor-magic-6-pro-fingerprint-lock-by-drfone-android/"><u>In 2024, Best Ways on How to Unlock/Bypass/Swipe/Remove Honor Magic 6 Pro Fingerprint Lock</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixing-radeon-r9-drivers-on-new-windows-11/"><u>Fixing Radeon R9 Drivers on New Windows 11</u></a></li>
</ul></div>
