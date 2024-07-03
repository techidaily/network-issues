---
title: Video Card Driver Restored Post Crash
date: 2024-07-02T03:33:21.965Z
updated: 2024-07-03T03:33:21.965Z
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
<li><a href="https://network-issues.techidaily.com/error-resolved-overwatch-needs-upgraded-graphics-card/"><u>Error Resolved: Overwatch Needs Upgraded Graphics Card</u></a></li>
<li><a href="https://network-issues.techidaily.com/amd-and-windows-10-unite-for-smooth-driver-load-resolution/"><u>AMD and Windows 10 Unite for Smooth Driver Load Resolution</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcoming-limitations-in-unsupported-freesync-setup/"><u>Overcoming Limitations in Unsupported FreeSync Setup</u></a></li>
<li><a href="https://network-issues.techidaily.com/streamline-vertical-calibration-on-computers/"><u>Streamline Vertical Calibration on Computers</u></a></li>
<li><a href="https://network-issues.techidaily.com/optimized-windows-11-experience-new-rtx210-drivers-rollout/"><u>Optimized Windows 11 Experience - New RTX210 Drivers Rollout</u></a></li>
<li><a href="https://network-issues.techidaily.com/qualcomm-wifi-adapter-atheros-issue-windows-10-fixed/"><u>Qualcomm WiFi Adapter, Atheros Issue - Windows 10 Fixed</u></a></li>
<li><a href="https://network-issues.techidaily.com/addressing-pro-7s-flickering-phenomenon/"><u>Addressing Pro 7'S Flickering Phenomenon</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/top-15-recording-software-for-clear-high-quality-windows-screens/"><u>Top 15 Recording Software for Clear, High-Quality Windows Screens</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-top-rated-free-video-rotation-software-for-windows-and-mac/"><u>Updated In 2024, Top-Rated Free Video Rotation Software for Windows and Mac</u></a></li>
<li><a href="https://howto.techidaily.com/zte-axon-40-lite-not-receiving-texts-10-hassle-free-solutions-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>ZTE Axon 40 Lite Not Receiving Texts? 10 Hassle-Free Solutions Here | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-simplify-your-workflow-10-essential-timecode-calculators-for-filmmakers/"><u>Updated Simplify Your Workflow 10 Essential Timecode Calculators for Filmmakers</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-use-device-manager-to-update-your-hardware-drivers-in-windows-11107-by-drivereasy-guide/"><u>How to use Device Manager to update your hardware drivers in Windows 11/10/7</u></a></li>
<li><a href="https://location-social.techidaily.com/proven-ways-in-how-to-hide-location-on-life360-for-oppo-find-x7-drfone-by-drfone-virtual-android/"><u>Proven Ways in How To Hide Location on Life360 For Oppo Find X7 | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-in-2024-record-your-gameplay-3-simple-and-effective-ways/"><u>Updated In 2024, Record Your Gameplay 3 Simple and Effective Ways</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-unveiling-six-techniques-to-screen-record-your-streamed-movies-on-macos/"><u>In 2024, Unveiling Six Techniques to Screen Record Your Streamed Movies on MacOS</u></a></li>
</ul></div>
