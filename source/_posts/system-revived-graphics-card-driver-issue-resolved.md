---
title: "System Revived: Graphics Card Driver Issue Resolved"
date: 2024-07-02T03:25:16.150Z
updated: 2024-07-03T03:25:16.150Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: "This Article Describes System Revived: Graphics Card Driver Issue Resolved"
excerpt: "This Article Describes System Revived: Graphics Card Driver Issue Resolved"
keywords: Graphics Card Driver Fix,Resolved GPU Problems,Updated Nvidia/AMD Drivers,Improved System Performance,Troubleshooting Graphic Issues,Fixed Display Errors,Optimized Graphics Hardware
thumbnail: https://thmb.techidaily.com/92f2629e0a1f1e2f3516b5bfb12e18e1391be680411487e21618499fabf10e50.jpg
---

## System Revived: Graphics Card Driver Issue Resolved

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
<li><a href="https://network-issues.techidaily.com/how-to-mend-lenovo-non-touch-screen/"><u>How To Mend Lenovo Non-Touch Screen</u></a></li>
<li><a href="https://network-issues.techidaily.com/banishing-screen-glitches-on-pro-7/"><u>Banishing Screen Glitches on Pro 7</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixed-cod-cold-war-offline-issues-persist/"><u>[FIXED] CoD Cold War - Offline Issues Persist</u></a></li>
<li><a href="https://network-issues.techidaily.com/screensavers-silent-struggle/"><u>Screensaver's Silent Struggle</u></a></li>
<li><a href="https://network-issues.techidaily.com/remedy-frequent-display-flickering/"><u>Remedy Frequent Display Flickering</u></a></li>
<li><a href="https://network-issues.techidaily.com/troubleshooting-non-functioning-amd-freesync/"><u>Troubleshooting Non-Functioning AMD FreeSync</u></a></li>
<li><a href="https://network-issues.techidaily.com/conquering-compatibility-issues-nvidiaintel-switchable-fixes-on-win10/"><u>Conquering Compatibility Issues: NVIDIA/Intel Switchable Fixes on Win10</u></a></li>
<li><a href="https://video-capture.techidaily.com/record-computer-sound-and-microphone-for-2024/"><u>Record Computer Sound and Microphone for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-fake-gps-location-pro-and-is-it-good-on-itel-a60-drfone-by-drfone-virtual-android/"><u>What is Fake GPS Location Pro and Is It Good On Itel A60? | Dr.fone</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713940696409-as-a-designer-color-is-the-most-powerful-and-the-most-diverse-tool-at-your-disposal-here-are-ten-matching-color-combinations-to-get-you-started-on-your-next/"><u>As a Designer, Color Is the Most Powerful and the Most Diverse Tool at Your Disposal. Here Are Ten Matching Color Combinations to Get You Started on Your Next Project</u></a></li>
<li><a href="https://extra-tips.techidaily.com/zoom-efficiency-top-three-strategies-for-format-finesse/"><u>Zoom Efficiency  Top Three Strategies for Format Finesse</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-can-we-unlock-our-infinix-smart-8-plus-phone-screen-by-drfone-android/"><u>In 2024, How Can We Unlock Our Infinix Smart 8 Plus Phone Screen?</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/melodic-mastery-mac-studio-tips-for-2024/"><u>Melodic Mastery  Mac Studio Tips for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/closer-look-techniques-for-effective-collaboration-on-ms-teams/"><u>Closer Look Techniques for Effective Collaboration on MS Teams</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-crafting-gopro-professionals-a-filmmaking-guide/"><u>[New] Crafting GoPro Professionals  A Filmmaking Guide</u></a></li>
</ul></div>
