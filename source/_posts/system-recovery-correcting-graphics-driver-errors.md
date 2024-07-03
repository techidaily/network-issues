---
title: "System Recovery: Correcting Graphics Driver Errors"
date: 2024-07-02T03:24:21.432Z
updated: 2024-07-03T03:24:21.432Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: "This Article Describes System Recovery: Correcting Graphics Driver Errors"
excerpt: "This Article Describes System Recovery: Correcting Graphics Driver Errors"
keywords: System Recovery Tools (High Relevance),Graphics Driver Troubleshooting (High Relevance),Fixing Graphics Errors (Medium-High Relevance),Adobe DXG1 Driver Correction (Low Competition),Nvidia Driver Repair (Medium Relevance),GPU Error Resolution (Medium-High Relevance),Display Driver Update Guide (Low Competition),System Recovery,Fix Graphics Errors Using System Recovery (Medium-High Relevance)
thumbnail: https://thmb.techidaily.com/25e355cfe41e9e10950c631e4aa9da16590e30c123d991c0d3d8b6703e367f7f.png
---

## System Recovery: Correcting Graphics Driver Errors

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
<li><a href="https://network-issues.techidaily.com/nvidia-rtx-3080-game-savior-a-troubleshooting-companion/"><u>NVIDIA RTX 3080 Game Savior: A Troubleshooting Companion</u></a></li>
<li><a href="https://network-issues.techidaily.com/mitigate-monitor-blinking-quick-guide/"><u>Mitigate Monitor Blinking: Quick Guide</u></a></li>
<li><a href="https://network-issues.techidaily.com/network-interface-misplaced-finding-wireless-adapter-in-windows-10/"><u>Network Interface Misplaced: Finding Wireless Adapter in Windows 10</u></a></li>
<li><a href="https://network-issues.techidaily.com/rectified-screen-expansion-glitches-for-windows/"><u>Rectified Screen Expansion Glitches for Windows</u></a></li>
<li><a href="https://network-issues.techidaily.com/troubleshooting-rapid-screen-changes-in-acer-models/"><u>Troubleshooting Rapid Screen Changes in Acer Models</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolved-visual-interface-rebooted-successfully/"><u>[Resolved] Visual Interface Rebooted Successfully</u></a></li>
<li><a href="https://network-issues.techidaily.com/avoiding-hp-lcd-stuttering-events/"><u>Avoiding HP LCD Stuttering Events</u></a></li>
<li><a href="https://network-issues.techidaily.com/screenfreeze-gfx-window-issue-resolution-ready/"><u>ScreenFreeze, GFX Window Issue (Resolution Ready)</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-fast-track-channel-growth-to-partner-status-aim-for-10000-views/"><u>In 2024, Fast-Track Channel Growth to Partner Status – Aim for 10,000 Views</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-tutorial-windows-movie-maker-for-effective-animation-designs-for-2024/"><u>[Updated] Tutorial  Windows Movie Maker for Effective Animation Designs for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-how-often-to-post-a-guide-to-youtube-video-upload-patterns-for-success/"><u>[New] 2024 Approved  How Often to Post  A Guide to YouTube Video Upload Patterns for Success</u></a></li>
<li><a href="https://audio-editing.techidaily.com/2024-approved-four-innovative-techniques-to-embed-sound-into-your-films-without-spending-a-dime/"><u>2024 Approved Four Innovative Techniques to Embed Sound Into Your Films without Spending a Dime</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-disabled-iphone-14-how-to-unlock-a-disabled-iphone-14-drfone-by-drfone-ios/"><u>In 2024, Disabled iPhone 14 How to Unlock a Disabled iPhone 14? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/from-finish-to-start-the-art-of-negative-playback-on-instagram/"><u>From Finish to Start  The Art of Negative-Playback on Instagram</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-why-does-the-pokemon-go-battle-league-not-available-on-oppo-a78-drfone-by-drfone-virtual-android/"><u>In 2024, Why does the pokemon go battle league not available On Oppo A78 | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-from-spoken-word-to-memo-iphone-audio-guidance/"><u>[New] In 2024, From Spoken Word to Memo  IPhone Audio Guidance</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-best-free-vob-video-editor-options-ranked/"><u>New Best Free VOB Video Editor Options Ranked</u></a></li>
</ul></div>
