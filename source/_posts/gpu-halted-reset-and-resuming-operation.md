---
title: GPU Halted, Reset and Resuming Operation
date: 2024-07-02T03:30:50.524Z
updated: 2024-07-03T03:30:50.524Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: This Article Describes GPU Halted, Reset and Resuming Operation
excerpt: This Article Describes GPU Halted, Reset and Resuming Operation
keywords: GPU Failure Recovery,Graphics Card Reset Troubleshooting,Stop GPU Error Resolution,GPU Halted Solution,Resuming GPU Operation Guide,Hardware Interruption and Reinitialization,System Restart After GPU Halt
thumbnail: https://thmb.techidaily.com/8e227e065d730938ce0d6ea2261402d78760be14848998b4f825537e8b545d45.jpg
---

## GPU Halted, Reset and Resuming Operation

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
<li><a href="https://network-issues.techidaily.com/windows-8-step-by-step-guide-to-launch-safe-mode-and-driver-uninstallation/"><u>Windows 8: Step-by-Step Guide to Launch Safe Mode and Driver Uninstallation</u></a></li>
<li><a href="https://network-issues.techidaily.com/dispel-blackouts-of-sims-screens/"><u>Dispel Blackouts of Sims' Screens</u></a></li>
<li><a href="https://network-issues.techidaily.com/win10-no-more-amd-radeon-r9-crashes-now/"><u>Win10: No More AMD Radeon R9 Crashes Now</u></a></li>
<li><a href="https://network-issues.techidaily.com/integrating-nvidia-into-new-windows-ecosystem/"><u>Integrating Nvidia Into New Windows Ecosystem</u></a></li>
<li><a href="https://network-issues.techidaily.com/heroes-unleashed-sluggish-swap/"><u>Heroes Unleashed: Sluggish Swap</u></a></li>
<li><a href="https://network-issues.techidaily.com/easy-steps-to-refresh-intel-graphics-drivers-on-windows-7-systems/"><u>Easy Steps to Refresh Intel Graphics Drivers on Windows 7 Systems</u></a></li>
<li><a href="https://network-issues.techidaily.com/new-driver-release-maximize-graphics-on-amd-radeon-hd-6950-for-windows-11/"><u>New Driver Release: Maximize Graphics on AMD Radeon HD 6950 for Windows 11</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-can-we-bypass-asus-rog-phone-7-frp-by-drfone-android/"><u>How Can We Bypass Asus ROG Phone 7 FRP?</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-fresh-footage-first-episode-insight-for-2024/"><u>[New] Fresh Footage First-Episode Insight for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/decoding-the-full-scope-of-obs-screen-recorder/"><u>Decoding the Full Scope of OBS Screen Recorder</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-winsnappers-best-pick-5-superior-screenshots-and-recorders/"><u>[New] 2024 Approved  WinSnapper's Best Pick  5 Superior Screenshots & Recorders</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-instagram-pro-tips-10-crucial-tools-to-increase-followers-for-2024/"><u>[New] Instagram Pro Tips  10 Crucial Tools to Increase Followers for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-securing-your-work-top-10-photo-watermark-solutions/"><u>2024 Approved  Securing Your Work  Top 10 Photo Watermark Solutions</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/1716483957882-updated-2024-approved-how-to-join-someones-live-on-tiktok-as-a-guest/"><u>[Updated] 2024 Approved  How to Join Someone’s Live on TikTok as a Guest</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-unleash-creativity-your-comprehensible-guide-to-sharing-animated-messages-in-snapchat/"><u>In 2024, Unleash Creativity  Your Comprehensible Guide to Sharing Animated Messages in Snapchat</u></a></li>
</ul></div>
