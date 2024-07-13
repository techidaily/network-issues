---
title: "[CORRECTED] Rust Legacy 2 Not Starting - DX12 Compatibility Hurdle"
date: 2024-07-12T01:18:57.630Z
updated: 2024-07-13T01:18:57.630Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: This Article Describes [CORRECTED] Rust Legacy 2 Not Starting - DX12 Compatibility Hurdle
excerpt: This Article Describes [CORRECTED] Rust Legacy 2 Not Starting - DX12 Compatibility Hurdle
keywords: Rust Legacy 2 Troubleshooting,DX12 Compatibility Issues,Rust 2D Graphics Failure,Solving Rust Legacy Startup Problems,DirectX 12 and Rust Integration,Rust Legacy 2 Development Error,Finding a Solution for Rust DX12 Compatibility
thumbnail: https://thmb.techidaily.com/7b44dc75606a866e6986fc574670153990f3b9d45bb38823ea9696084a32865c.jpg
---

## [CORRECTED] Rust Legacy 2 Not Starting - DX12 Compatibility Hurdle

 Halo Infinite is a great game but it is really annoying when you get a DirectX12 error and can’t launch the game. Don’t worry, you’re not alone. This post has gathered fixes to solve the error and help you play the game. Read on to find how.

## Try these fixes

1. [Download DX12 file](#fix)
2. [Update your graphic driver](#fix1)
3. [Check your PC specs](#fix2)
4. [Edit your file name](#fix3)
5. [Repair system files](#fix4)

### Fix 1: Download DX12 file

 Before moving to any complicated fixes, make sure you’ve downloaded and installed the latest DX12 files.

 If not, go to the [Microsoft website](https://www.microsoft.com/en-us/download/details.aspx?id=35) and download the latest version.

### Fix 2: Update your graphic driver

 According to the error message from Halo Infinite, apparently, you need to update the graphics driver to the latest version to meet the requirements.

| **Manufacturer** | **Supported driver**                                                            |
| ---------------- | ------------------------------------------------------------------------------- |
| AMD              | Halo Infinite Day Zero Driver 21.12.1 (Recommended) All AMD graphics drivers    |
| NVIDIA           | 497.09 or later (Recommended) All NVIDIA graphics drivers                       |
| Intel            | All Intel graphics driver Intel graphics hardware is not supported at this time |

 There’re mainly 2 ways you can update your graphics driver: manually or automatically.

#### Option 1: Update your graphics driver manually

 Manufacturers like NVIDIA release new graphics drivers on a regular basis. You can spend some time heading to the driver’s official website and updating the driver manually.

To do so, first visit the website of your GPU manufacturer:

* **[NVIDIA](https://tools.techidaily.com/drivereasy/download/)**
* **[AMD](https://www.amd.com/en/support)**
* **[Intel](https://downloadcenter.intel.com/product/80939/Graphics)**

 Then search for your GPU model. Note you should download the latest driver that’s compatible with your operating system. After that, follow the on-screen instructions to update the driver.  
 The process is a bit time-consuming and error-prone. If you want to free yourself, the second option would help.

#### Option 2: Update your graphics driver automatically (Recommended)

 If you don’t have the time, patience, or computer skills to update your video drivers manually, you can, instead, do it automatically with [](https://tools.techidaily.com/drivereasy/download/) **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . Driver Easy will automatically recognize your system and find the correct drivers for your exact graphics card, and your Windows version, and it will download and install them correctly. You don’t need to worry about making a mistake when downloading or installing.

1. **[Download](https://tools.techidaily.com/drivereasy/download/) [](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.
2. Run Driver Easy and click the **Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://images.drivereasy.com/wp-content/uploads/2020/08/Scan-now.jpg)
3. Click **Update All** to automatically download and install the correct version of _all_ the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  – you’ll be prompted to upgrade when you click Update All. If you don’t want to pay for the Pro version, you can still download and install all the drivers you need with the free version; you just have to download them one at a time, and manually install them, the normal Windows way.)  
![](https://images.drivereasy.com/wp-content/uploads/2020/09/de-update-all-rtx-3080.jpg)

**The Pro version of Driver Easy** comes with full technical support.  
 If you need assistance, please contact **Driver Easy’s support team** at **[support@drivereasy.com](mailto:support@drivereasy.com) .**

 Restart your computer for the changes to take effect, then relaunch Halo Infinite.

### Fix 3: Check your PC specification

 Some gamers have reported that they’ve installed DirectX 12 and the latest graphics driver, but the error persists. If you’re in this situation, you need to check your PC specifications again.

#### Minimum Requirements

| OS   | Windows 10 RS5 x64 1809 (October 2018 update) |
| ---- | --------------------------------------------- |
| CPU  | AMD Ryzen 5 1600 or Intel i5-4440             |
| GPU  | AMD RX 570 or Nvidia GTX 1050 Ti              |
| VRAM | 4+ GB                                         |
| RAM  | 8+ GB                                         |
| SSD  | 50+ GB                                        |

You need to check 2 elements:

* DirectX 12 feature levels
* VRAM

 Either your VRAM is less than 4GB, or DirectX 12 feature level is less than 12\_0 will stop you from playing the game.

 If your VRAM meets the minimum requirements but encounters the error message, the culprit should be DirectX12 level. Because Halo Infinite requires 12\_0 or higher to run the game.

 To find out if your system is compatible with DirectX 12 and the DirectX 12 levels, just follow the steps below:

1. Press the**Windows logo key** +**R** together to open the Run box.
2. Type`dxdiag` and press the**Enter** key.  
![](https://images.drivereasy.com/wp-content/uploads/2021/12/dxdiag.jpg)
3. In the DirectX Diagnostic Tool, check the**DirectX Version** .  
![](https://images.drivereasy.com/wp-content/uploads/2021/12/directx12-1.jpg)
4. Go to the**Display 1** tab, and it will show you the version of Direct3D and the supported feature levels.  
![](https://images.drivereasy.com/wp-content/uploads/2021/12/directx12-2.jpg)  
 Also, you can check your VRAM on the left panel.

If your Feature Level is lower than 12\_0, you’ll need a new GPU.

### Fix 4: Edit your file name

 We don’t know the reason but many gamers have tried and it worked for some people. If you’re a Steam user, you can give it a try, it may surprise you.

1. Open File Explorer, find the steam library where you downloaded the game.
2. Go to`C:\Program Files (x86)\SteamLibrary\steamapps\common\MGS Test App 6\data\hardware` The file directory may vary depending on where you installed the game.
3. Find the text file that is applicable to you, then rename this text file to anything you want. **Make sure to create a copy of the file before making any changes to it.**
4. Attempt to relaunch the game.  
**Note** : The game takes some time to load up, just wait for a few minutes when you see a black screen and 3 dots at the top left.

If this fix doesn’t work, move to the next one.

### Fix 5: Repair system files

 If your system files are missing or broken, you’ll encounter various issues including the game not launching issue. When none of the methods have fixed the issue, running **[Fortect](https://tools.techidaily.com/drivereasy/download/)**  to check the system files could make a difference. It will deal with issues related to system errors, critical system files for you.

**[Fortect](https://tools.techidaily.com/drivereasy/download/)**  is a computer repair software that can diagnose problems on your computer and fix them immediately. It’s tailored to your specific system and is working in a private and automatic way. It will first check hardware-related issues to identify problems, and then security issues, and finally it detects programs that crash, missing system files. Once complete, it will find a solution to your specific problem.

* Fortect will replace your missing/damaged DLL files with fresh, clean and up-to-date ones – Even those you don’t know about!

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Fortect.
2. Open Fortect and click**Yes** to run a free scan of your PC.  
![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-1.jpg)
3. Fortect will scan your computer thoroughly. This may take a few minutes.  
![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-2.jpg)
4. Once done, you’ll see a detailed report of all the issues on your PC. To fix them automatically, click**START REPAIR** . This requires you to purchase the full version. But don’t worry. If Fortect doesn’t solve the issue, you can request a refund within 60 days.  
![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-3.jpg)

 That’s all about the DirectX 12 incompatible graphics adapter error that stops you from playing the game. Hope this post would help. If you have any suggestions or working methods, you’re welcome to leave a comment below.

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
<li><a href="https://network-issues.techidaily.com/gpu-troubleshooting-error-43/"><u>GPU Troubleshooting: Error 43</u></a></li>
<li><a href="https://network-issues.techidaily.com/setting-adjustments-stored-effectively/"><u>Setting Adjustments Stored Effectively</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-frameforge-review-the-ultimate-guide-to-capturing-tech/"><u>[New] FrameForge Review  The Ultimate Guide to Capturing Tech</u></a></li>
<li><a href="https://network-issues.techidaily.com/eradicate-win11-opaque-screen-phenomenon/"><u>Eradicate WIN11 Opaque Screen Phenomenon</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-free-hd-video-capture-tools-the-complete-review/"><u>[Updated] Free HD Video Capture Tools  The Complete Review</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/hidden-narratives-unlocked-a-complete-snapguide/"><u>Hidden Narratives Unlocked  A Complete Snapguide</u></a></li>
<li><a href="https://network-issues.techidaily.com/understanding-and-fixing-c1900101-error-during-win11-installation/"><u>Understanding & Fixing C1900101 Error During Win11 Installation</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-top-video-meeting-applications-excluding-zoom-for-2024/"><u>[New] Top Video Meeting Applications Excluding Zoom for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/reducing-windows-10-monitor-span/"><u>Reducing Windows 10 Monitor Span</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-top-5-screen-selections-for-ps5-enthusiasts/"><u>[New] Top 5 Screen Selections for PS5 Enthusiasts</u></a></li>
<li><a href="https://network-issues.techidaily.com/eradicate-sims-4-blackout-problems/"><u>Eradicate Sims 4 Blackout Problems</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-and-where-to-find-a-shiny-stone-pokemon-for-motorola-moto-g73-5g-drfone-by-drfone-virtual-android/"><u>How and Where to Find a Shiny Stone Pokémon For Motorola Moto G73 5G? | Dr.fone</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-text-integration-in-tiktok-creations-step-by-step/"><u>In 2024, Text Integration in TikTok Creations, Step by Step</u></a></li>
<li><a href="https://howto.techidaily.com/play-store-not-working-on-oneplus-11-5g-8-solutions-inside-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Not Working On OnePlus 11 5G? 8 Solutions Inside | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/reversing-upside-down-screen-on-windows-11-os/"><u>Reversing Upside Down Screen on Windows 11 OS</u></a></li>
<li><a href="https://network-issues.techidaily.com/screen-upside-down-in-windows-11-fixed/"><u>Screen Upside Down in Windows 11 [Fixed]</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcoming-the-challenge-of-invisible-pixel-gaps-on-laptops/"><u>Overcoming the Challenge of Invisible Pixel Gaps on Laptops</u></a></li>
<li><a href="https://network-issues.techidaily.com/awaken-your-displays-true-colors/"><u>Awaken Your Display's True Colors</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-master-list-of-10-best-video-chat-programs-today-for-2024/"><u>[New] Master List of 10 Best Video Chat Programs Today for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-a-filmmakers-essential-guide-to-free-royalty-free-audiosites/"><u>[New] In 2024, A Filmmaker's Essential Guide to Free Royalty-Free Audiosites</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/the-ultimate-list-free-online-meeting-software-roundup-for-2024/"><u>The Ultimate List  Free Online Meeting Software Roundup for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/reverse-screenscape-regain-normal-view/"><u>Reverse Screenscape: Regain Normal View</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-venn-of-virtuality-metaverse-and-multiverse-analysis/"><u>[New] The Venn of Virtuality  Metaverse & Multiverse Analysis</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolve-civ-5-glitches-on-windows/"><u>Resolve Civ 5 Glitches on Windows</u></a></li>
<li><a href="https://driver-install.techidaily.com/fix-released-windows-now-handles-hd-audio-flawlessly/"><u>Fix Released: Windows Now Handles HD Audio Flawlessly</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/0-famous-makeupbeauty-gurus-on-youtube-popular-2024/"><u>[New] 10 Famous Makeup/Beauty Gurus on YouTube [Popular 2024]</u></a></li>
<li><a href="https://network-issues.techidaily.com/bloodied-barbarian-balance-adjustment/"><u>Bloodied Barbarian Balance Adjustment</u></a></li>
<li><a href="https://network-issues.techidaily.com/accessing-display-settings-on-nvidia-graphics/"><u>Accessing Display Settings on NVIDIA Graphics</u></a></li>
<li><a href="https://network-issues.techidaily.com/1719974801619-improve-graphical-output-install-a-simple-quick-update-for-intel-graphics-on-windows-10/"><u>Improve Graphical Output: Install a Simple, Quick Update for Intel Graphics on Windows 10.</u></a></li>
<li><a href="https://network-issues.techidaily.com/eradicated-oversized-view-on-windows-pcs/"><u>Eradicated Oversized View on Windows PCs</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/collaborative-video-creation-and-growth-tips/"><u>Collaborative Video Creation & Growth Tips</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcoming-internal-display-flutter/"><u>Overcoming Internal Display Flutter</u></a></li>
<li><a href="https://network-issues.techidaily.com/eliminated-inconsistent-reflective-surface-flashes/"><u>Eliminated Inconsistent Reflective Surface Flashes</u></a></li>
<li><a href="https://network-issues.techidaily.com/system-revived-graphics-card-driver-issue-resolved/"><u>System Revived: Graphics Card Driver Issue Resolved</u></a></li>
<li><a href="https://network-issues.techidaily.com/overwatch-no-compatible-graphics-hardware-was-found-solved/"><u>Overwatch No Compatible Graphics Hardware Was Found [Solved]</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-elite-puzzles-unlocked-discovering-best-escape-halls/"><u>[Updated] In 2024, Elite Puzzles Unlocked  Discovering Best Escape Halls</u></a></li>
<li><a href="https://network-issues.techidaily.com/max-screen-quality-restored-on-windows/"><u>Max Screen Quality Restored on Windows</u></a></li>
<li><a href="https://activate-lock.techidaily.com/a-how-to-guide-on-bypassing-iphone-13-icloud-activation-lock-by-drfone-ios/"><u>A How-To Guide on Bypassing iPhone 13 iCloud Activation Lock</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcoming-initial-d3d-errors-successfully/"><u>Overcoming Initial D3D Errors Successfully</u></a></li>
<li><a href="https://network-issues.techidaily.com/dimming-to-stable-dell-screen-fixes/"><u>Dimming to Stable: Dell Screen Fixes</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-enhance-your-social-presence-with-easy-fb-video-upload-pc-and-android/"><u>[New] Enhance Your Social Presence with Easy FB Video Upload, PC & Android</u></a></li>
</ul></div>
