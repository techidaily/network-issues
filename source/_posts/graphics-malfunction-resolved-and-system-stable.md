---
title: Graphics Malfunction Resolved and System Stable
date: 2024-07-02T03:27:51.190Z
updated: 2024-07-03T03:27:51.190Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: This Article Describes Graphics Malfunction Resolved and System Stable
excerpt: This Article Describes Graphics Malfunction Resolved and System Stable
keywords: Graphics Issue Fixed,System Stability Achieved,Resolved Display Errors,Graphics Correction Tutorial,Repair Graphic Glitches,Stable Graphics Environment Setup,Fixed Visual System Errors
thumbnail: https://thmb.techidaily.com/b8fca16a34b5411c86475482e61fa021f5aeb02943a66dd5dba0e650f0e39da1.jpg
---

## Graphics Malfunction Resolved and System Stable

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
<li><a href="https://network-issues.techidaily.com/elevate-your-gameplay-geforce-210-and-win10-combined-power/"><u>Elevate Your Gameplay: GeForce 210 & WIN10 Combined Power</u></a></li>
<li><a href="https://network-issues.techidaily.com/overwatch-fixed-gpu-incompatibility-problems/"><u>Overwatch: Fixed GPU Incompatibility Problems</u></a></li>
<li><a href="https://network-issues.techidaily.com/windows-10-screen-fix-advanced-features-on/"><u>Windows 10 Screen Fix - Advanced Features On</u></a></li>
<li><a href="https://network-issues.techidaily.com/dealing-with-c1900101-on-new-operating-system/"><u>Dealing with C1900101 on New Operating System</u></a></li>
<li><a href="https://network-issues.techidaily.com/next-gen-windows-driver-amd-radeon-graphics-drivers-v20/"><u>Next-Gen Windows Driver: AMD Radeon Graphics Drivers V2.0</u></a></li>
<li><a href="https://network-issues.techidaily.com/cure-freezing-screen-in-win10-os/"><u>Cure Freezing Screen in Win10 OS</u></a></li>
<li><a href="https://network-issues.techidaily.com/hidden-display-settings-return-in-windows-11/"><u>Hidden Display Settings Return in Windows 11</u></a></li>
<li><a href="https://network-issues.techidaily.com/restoring-brightness-to-lenovos-invisible-display/"><u>Restoring Brightness to Lenovo’s Invisible Display</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-remove-screen-lock-pin-on-honor-80-pro-straight-screen-edition-like-a-pro-5-easy-ways-by-drfone-android/"><u>How To Remove Screen Lock PIN On Honor 80 Pro Straight Screen Edition Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-is-greyed-out-on-apple-iphone-se-how-to-bypass-by-drfone-ios/"><u>Apple ID is Greyed Out On Apple iPhone SE How to Bypass?</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-effective-visual-brand-strategies-for-your-youtube-logo/"><u>[New] Effective Visual Brand Strategies for Your YouTube Logo</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-advanced-strategies-for-youtube-audio-editing-mastery/"><u>[Updated] 2024 Approved  Advanced Strategies for YouTube Audio Editing Mastery</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/elevating-your-videos-status-on-youtube/"><u>Elevating Your Video's Status on YouTube</u></a></li>
<li><a href="https://extra-hints.techidaily.com/conquering-consumer-attention-metaverse-marketing-tips-for-2024/"><u>Conquering Consumer Attention  Metaverse Marketing Tips for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-transform-your-text-expert-guide-to-mp3-conversion/"><u>Updated Transform Your Text Expert Guide to MP3 Conversion</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/best-anti-tracker-software-for-apple-iphone-11-pro-drfone-by-drfone-virtual-ios/"><u>Best Anti Tracker Software For Apple iPhone 11 Pro | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-adobe-premiere-pro-101-for-youtube-clips-and-edits/"><u>[New] 2024 Approved  Adobe Premiere Pro 101 for YouTube Clips and Edits</u></a></li>
</ul></div>
