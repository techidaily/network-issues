---
title: Video Card Driver Restored Post Crash
date: 2024-10-11T10:28:16.728Z
updated: 2024-10-11T20:24:08.761Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: This Article Describes Video Card Driver Restored Post Crash
excerpt: This Article Describes Video Card Driver Restored Post Crash
keywords: Restored Video Card Driver,Repairing Graphics Drivers After Crash,Fix Video Card Driver Failure,Troubleshooting Graphics Drivers Post Crash,Update Video Card Driver After System Crash,Reinstall Graphics Drivers Post-Crash Recovery,Graphics Driver Restoration After Crashing PC
thumbnail: https://thmb.techidaily.com/ff7dea50eb587133c9c080dfe92ef9382e6bba6eef0863a0474a1aae2b4b5f25.jpg
---

## Video Card Driver Restored Post Crash

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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-guide-to-quick-video-recording-on-youtube-for-2024/"><u>[New] Guide to Quick Video Recording on YouTube for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-how-to-step-into-virtual-entertainment-and-gain-notoriety/"><u>[New] In 2024, How to Step Into Virtual Entertainment and Gain Notoriety</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-melody-and-memes-adding-audio-to-instagrams-visual-medley/"><u>[New] In 2024, Melody & Memes Adding Audio to Instagram's Visual Medley</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-2024-approved-navigating-the-cross-platform-exchange-of-tweets-and-vids-on-whatsapp/"><u>[Updated] 2024 Approved Navigating the Cross-Platform Exchange of Tweets and Vids on WhatsApp</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixing-hybrid-gpu-error-in-nvidiaintel-on-windows-10/"><u>Fixing Hybrid GPU Error in NVIDIA/Intel on Windows 10</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixing-windows-10-inverted-screen-view/"><u>Fixing Windows 10: Inverted Screen View</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixing-windows-11-screen-mirror-reversal/"><u>Fixing Windows 11 Screen Mirror Reversal</u></a></li>
<li><a href="https://driver-install.techidaily.com/freshen-your-graphics-experience-with-rx-5500xt-updates/"><u>Freshen Your Graphics Experience with RX 5500XT Updates</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-iphone-6s-plus-asking-for-passcode-after-ios-1714-update-what-to-do-by-drfone-ios/"><u>In 2024, iPhone 6s Plus Asking for Passcode after iOS 17/14 Update, What to Do?</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-transforming-viewers-into-vendors-ajey-nagars-earnings-excellence-on-youtube/"><u>In 2024, Transforming Viewers Into Vendors Ajey Nagar’s Earnings Excellence on YouTube</u></a></li>
<li><a href="https://network-issues.techidaily.com/no-display-just-a-blink/"><u>No Display, Just a Blink</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcoming-media-playback-woes-in-new-windows-10-release/"><u>Overcoming Media Playback Woes in New Windows 10 Release</u></a></li>
<li><a href="https://win11.techidaily.com/reconnect-and-revive-windows-11-bt-audio-devices/"><u>Reconnect and Revive Windows 11 BT Audio Devices</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolved-windows-10-lacks-wireless-card-detection/"><u>Resolved: Windows 10 Lacks Wireless Card Detection</u></a></li>
<li><a href="https://network-issues.techidaily.com/revive-windows-clarity-swiftly/"><u>Revive Windows Clarity Swiftly</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/top-10-reliable-mkv-to-mp4-conversion-tools-compatible-with-windows-and-mac/"><u>Top 10 Reliable MKV to MP4 Conversion Tools Compatible with Windows and Mac</u></a></li>
<li><a href="https://network-issues.techidaily.com/windows-10-rectifying-backward-screen-orientation/"><u>Windows 10: Rectifying Backward Screen Orientation</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148639/16836" target="_top" id="2148639">
  <img src="//a.impactradius-go.com/display-ad/16836-2148639" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148639/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

