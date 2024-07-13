---
title: "[FIXED] Rust Legacy Launch Issue - DX12 Failure"
date: 2024-07-12T00:52:30.825Z
updated: 2024-07-13T00:52:30.825Z
tags:
  - win11
  - win10
  - win7
categories:
  - NetworkIssues
description: This Article Describes [FIXED] Rust Legacy Launch Issue - DX12 Failure
excerpt: This Article Describes [FIXED] Rust Legacy Launch Issue - DX12 Failure
keywords: Rust Legacy Launch Issue,DX12 Failure,Rust Legacy Projects,DX12 Difficulties,Graphics API Errors,Rust Development Bugs,Legacy Codebase Fixes
thumbnail: https://thmb.techidaily.com/e03e43d6c35d148960447c0d2ee89542320d7730a8e124f95538e772fc1bdf8a.jpg
---

## [FIXED] Rust Legacy Launch Issue - DX12 Failure

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
<li><a href="https://network-issues.techidaily.com/solved-stretched-screen-issues-for-windows-10/"><u>[Solved] Stretched Screen Issues for Windows 10</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixing-no-compatible-graphics-overwatch-update-resolved/"><u>Fixing No Compatible Graphics: Overwatch Update Resolved</u></a></li>
<li><a href="https://network-issues.techidaily.com/how-to-solve-strobe-like-effect-in-acer-displays/"><u>How to Solve Strobe-Like Effect in Acer Displays</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-fresh-alternative-films-to-dive-into-7-favorites-for-2024/"><u>[New] Fresh Alternative Films to Dive Into, #7 Favorites for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-breaking-down-triller-its-distinctive-position-in-the-video-world/"><u>[Updated] Breaking Down Triller  Its Distinctive Position in the Video World</u></a></li>
<li><a href="https://network-issues.techidaily.com/win11-resume-operation-post-creators-patch/"><u>Win11 Resume Operation Post Creator's Patch</u></a></li>
<li><a href="https://network-issues.techidaily.com/curing-black-displays-on-laptop-monitors/"><u>Curing Black Displays on Laptop Monitors</u></a></li>
<li><a href="https://network-issues.techidaily.com/repaired-lost-connection-to-wi-fi-on-windows-11/"><u>[REPAIRED] Lost Connection to Wi-Fi on Windows 11</u></a></li>
<li><a href="https://network-issues.techidaily.com/endless-wi-fi-outage-mystery/"><u>Endless Wi-Fi Outage Mystery</u></a></li>
<li><a href="https://activate-lock.techidaily.com/the-most-effective-ways-to-bypass-iphone-12-pro-activation-lock-by-drfone-ios/"><u>The Most Effective Ways to Bypass iPhone 12 Pro Activation Lock</u></a></li>
<li><a href="https://network-issues.techidaily.com/nvidia-graphics-disablement-overcome/"><u>Nvidia Graphics Disablement Overcome</u></a></li>
<li><a href="https://network-issues.techidaily.com/solved-amd-radeon-r9-fatal-errors-in-win11/"><u>Solved: AMD Radeon R9 Fatal Errors in Win11</u></a></li>
<li><a href="https://network-issues.techidaily.com/mastered-gpu-settings-entry-point/"><u>Mastered: GPU Settings Entry Point</u></a></li>
<li><a href="https://network-issues.techidaily.com/glitch-uncovered-nvidia-opengl-repaired/"><u>Glitch Uncovered: Nvidia OpenGL Repaired</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-tecno-pova-5-to-pc-drfone-by-drfone-android/"><u>How to Screen Mirroring Tecno Pova 5 to PC? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/revamping-educational-experiences-through-vr-for-2024/"><u>Revamping Educational Experiences Through VR for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/perfecting-media-streaming-in-newest-microsoft-operating-system/"><u>Perfecting Media Streaming in Newest Microsoft Operating System</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-mp4-screen-grabber-free-easy-access/"><u>2024 Approved  MP4 Screen Grabber  Free, Easy Access</u></a></li>
<li><a href="https://network-issues.techidaily.com/solved-quick-flicker-on-dell-display/"><u>[Solved] Quick Flicker on Dell Display</u></a></li>
<li><a href="https://network-issues.techidaily.com/solution-found-black-ops-cold-war-launch-xbox-trouble/"><u>[SOLUTION FOUND] Black Ops Cold War Launch - Xbox Trouble</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-how-to-record-screen-with-ultra-screen-recorder/"><u>In 2024, How to Record Screen With Ultra Screen Recorder</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-vivid-pfp-designs-unleash-the-potential-of-your-tiktok-profile/"><u>2024 Approved  Vivid PFP Designs, Unleash the Potential of Your TikTok Profile</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-elite-6-urban-home-structures-in-minecraft-for-2024/"><u>[Updated] Elite 6 Urban Home Structures in Minecraft for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-from-clips-to-masterpiece-essential-video-editing-techniques/"><u>In 2024, From Clips to Masterpiece Essential Video Editing Techniques</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-instantly-convert-dailymotion-videos-to-mp3mp4-for-free-for-2024/"><u>New Instantly Convert Dailymotion Videos to MP3/MP4 for Free for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/mastering-zoom-cameras-common-fixes-and-solutions/"><u>Mastering Zoom Cameras: Common Fixes and Solutions</u></a></li>
<li><a href="https://network-issues.techidaily.com/enhance-visual-performance-swiftly-update-your-pcs-intel-gpu-driver-in-w10-today/"><u>Enhance Visual Performance Swiftly: Update Your PC's Intel GPU Driver in W10 Today</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/visionary-filmmaker-blending-clips-and-chords/"><u>Visionary Filmmaker  Blending Clips & Chords</u></a></li>
<li><a href="https://howto.techidaily.com/fixes-for-apps-keep-crashing-on-nokia-g22-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixes for Apps Keep Crashing on Nokia G22 | Dr.fone</u></a></li>
<li><a href="https://youtube-data.techidaily.com/op-effort-for-quick-setup-youtube-biz-channel-ideas/"><u>[New] Top Effort for Quick Setup  YouTube Biz Channel Ideas</u></a></li>
<li><a href="https://network-issues.techidaily.com/windows-blackout-after-fixed-fall-release/"><u>Windows Blackout After Fixed Fall Release</u></a></li>
<li><a href="https://network-issues.techidaily.com/changing-display-in-w11-encountered-errors-resolved/"><u>Changing Display in W11 Encountered Errors [Resolved]</u></a></li>
<li><a href="https://network-issues.techidaily.com/windows-1011-enable-and-setup-external-wi-fi-interface-driver/"><u>Windows 10/11 - Enable and Setup External Wi-Fi Interface Driver</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-10-must-have-screen-capture-tools-for-online-instructors/"><u>In 2024, 10 Must-Have Screen Capture Tools for Online Instructors</u></a></li>
<li><a href="https://network-issues.techidaily.com/effortlessly-refresh-intel-g3000-on-ws11/"><u>Effortlessly Refresh Intel G3000 on WS11</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-unleashing-inspiration-ideas-for-engaging-channels/"><u>[Updated] In 2024, Unleashing Inspiration  Ideas for Engaging Channels</u></a></li>
<li><a href="https://network-issues.techidaily.com/blackout-blunder-with-latest-graphics-card/"><u>Blackout Blunder with Latest Graphics Card</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-easycapture-pro-free-for-windows-10-for-2024/"><u>[New] EasyCapture Pro - Free for Windows 10 for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/apex-bug-busters-efficiently-resolve-crashes/"><u>Apex Bug Busters: Efficiently Resolve Crashes</u></a></li>
<li><a href="https://network-issues.techidaily.com/disentangled-rtx-manager-access/"><u>Disentangled: RTX Manager Access</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-integrated-sound-and-vision-workspace/"><u>In 2024, Integrated Sound & Vision Workspace</u></a></li>
<li><a href="https://facebook.techidaily.com/8-tips-to-avoid-phishing-scams-on-facebook/"><u>8 Tips to Avoid Phishing Scams on Facebook</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-add-my-signature-to-rtf-file-by-ldigisigner-sign-a-word-sign-a-word/"><u>How to add my signature to .rtf file</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-digital-audio-tutorial-removing-drum-beats-from-your-songs-with-ease/"><u>In 2024, Digital Audio Tutorial Removing Drum Beats From Your Songs with Ease</u></a></li>
<li><a href="https://network-issues.techidaily.com/nvidia-rendering-armored-post-fix/"><u>Nvidia Rendering Armored Post-Fix</u></a></li>
<li><a href="https://games-able.techidaily.com/protecting-personal-progress-implementing-passcode-on-your-switch/"><u>Protecting Personal Progress: Implementing Passcode on Your Switch</u></a></li>
<li><a href="https://network-issues.techidaily.com/optimized-windows-11-experience-new-rtx210-drivers-rollout/"><u>Optimized Windows 11 Experience - New RTX210 Drivers Rollout</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixing-win11-and-geforce-7025-hardware-clash/"><u>Fixing Win11 & GeForce 7025 Hardware Clash</u></a></li>
<li><a href="https://network-issues.techidaily.com/display-fixed-repaired-nvidia-driver-failure/"><u>Display Fixed: Repaired NVidia Driver Failure</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-from-ordinary-to-spectacular-making-wow-worthy-tiktok-videos-with-templates/"><u>[New] 2024 Approved  From Ordinary to Spectacular  Making Wow-Worthy TikTok Videos with Templates</u></a></li>
<li><a href="https://network-issues.techidaily.com/reconnecting-to-lost-wireless-network-in-windows-10/"><u>Reconnecting to Lost Wireless Network in Windows 10</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-4-ways-to-trace-samsung-galaxy-a25-5g-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 4 Ways to Trace Samsung Galaxy A25 5G Location | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-the-art-of-merging-sound-and-visuals-audio-addition-in-gifs-on-a-mac-system/"><u>Updated The Art of Merging Sound and Visuals Audio Addition in GIFs on a Mac System</u></a></li>
<li><a href="https://network-issues.techidaily.com/recovered-lost-wi-fi-adapter-on-latest-os/"><u>[RECOVERED] Lost Wi-Fi Adapter on Latest OS</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-xiaomi-13t-phone-without-any-data-loss-by-drfone-android/"><u>How to Unlock Xiaomi 13T Phone without Any Data Loss</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-how-can-you-choose-the-best-sound-editor-for-2024/"><u>New How Can You Choose the Best Sound Editor for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-unleashing-potential-the-best-anime-ideas-in-videos/"><u>[New] In 2024, Unleashing Potential  The Best Anime Ideas in Videos</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/2024-approved-masterful-melodies-discovering-the-top-software-for-capturing-guitars/"><u>2024 Approved Masterful Melodies Discovering the Top Software for Capturing Guitars</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-easy-guide-to-honor-x50-gt-frp-bypass-with-best-methods-by-drfone-android/"><u>In 2024, Easy Guide to Honor X50 GT FRP Bypass With Best Methods</u></a></li>
<li><a href="https://network-issues.techidaily.com/scale-down-windows-11-oversized-display/"><u>[SCALE DOWN] Windows 11 Oversized Display</u></a></li>
<li><a href="https://network-issues.techidaily.com/reactivating-non-operational-asus-webcam/"><u>Reactivating Non-Operational Asus Webcam</u></a></li>
<li><a href="https://network-issues.techidaily.com/restoring-display-settings-configuration-functionality/"><u>Restoring Display Settings Configuration Functionality</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-quick-tips-initiating-discord-video-conversations-anywhere/"><u>[New] 2024 Approved  Quick Tips  Initiating Discord Video Conversations Anywhere</u></a></li>
<li><a href="https://network-issues.techidaily.com/solved-no-amd-graphics-driver-is-installed-on-windows-1110/"><u>[SOLVED] No AMD Graphics Driver Is Installed on Windows 11/10</u></a></li>
<li><a href="https://network-issues.techidaily.com/how-to-address-screen-reflections-in-acer-notebooks/"><u>How to Address Screen Reflections in Acer Notebooks</u></a></li>
<li><a href="https://network-issues.techidaily.com/seeking-stability-in-wireless-signal/"><u>Seeking Stability in Wireless Signal</u></a></li>
<li><a href="https://network-issues.techidaily.com/effortlessly-entering-window-8s-secure-environment-for-graphics-updates/"><u>Effortlessly Entering Window 8’S Secure Environment for Graphics Updates</u></a></li>
<li><a href="https://fake-location.techidaily.com/spoofing-life360-how-to-do-it-on-vivo-v27-drfone-by-drfone-virtual-android/"><u>Spoofing Life360 How to Do it on Vivo V27? | Dr.fone</u></a></li>
</ul></div>
