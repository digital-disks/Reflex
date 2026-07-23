<p align="center"> <img width="320" height="64" alt="Asset 136" src="https://github.com/user-attachments/assets/fb4883a2-6dae-4faa-80ab-48c1838df641" /> </p>

 

<p align="center">

 

![Version](https://img.shields.io/github/v/release/digital-disks/Reflex?label=&labelColor=6f00ff&color=252525&style=flat-square&logo=github&logoColor=ffffff) ![C++](https://img.shields.io/badge/%20-C%2B%2B-252525?style=flat-square&logo=c%2B%2B&logoColor=ffffff&labelColor=4f00ff) [![Buy Me A Coffee](https://img.shields.io/badge/%20-Buy%20Me%20A%20Coffee-252525?style=flat-square&logo=buy-me-a-coffee&logoColor=ffffff&labelColor=2f00ff)](https://www.buymeacoffee.com/digitaldisks)

</p>

# THIS REPO IS TO PUBLISH MY DEVELOPMENT BUILDS FOR THE SAKE OF TESTING. THERE ARE BUGS AND GLITCHES!!!

Reflex is a lightweight, low-overhead recording and clipping software for Windows. This project will soon be open source once it gains enough recognition and the software is ready for stable releases.


<p align="center"> <a href="https://github.com/digital-disks/Reflex/releases">
  <img width="250" height="50" alt="download-banner" src="https://github.com/user-attachments/assets/0e192307-c2ea-4b71-bad4-ed6347ea7d61"/>
</a> <a href="https://github.com/digital-disks/Reflex/issues/new"> <img width="250" height="50" alt="report-banner" src="https://github.com/user-attachments/assets/7194ff84-37d3-4a1e-a946-256a297ac8bd"/> </a> <a href="https://buymeacoffee.com/digitaldisks"> <img width="250" height="50" alt="donate-banner" src="https://github.com/user-attachments/assets/a65e740a-7b48-44b8-8fe5-d190bc0fa908"/>
 </p>

## Project Status
Currently, Reflex is still being worked on to ensure stability for future releases; therefore, it remains in the Beta stage and closed source. Once the major flaws are resolved and the software is polished, it will become open source.

> *This project is created and maintained by a one-man team, so please be patient with me if some issues take too long to resolve. Additionally, I am still learning C++ and this is essentially my first project. Thank you :D*

## Software Features & Support
Reflex includes these features:

- **Recording:** Reflex can record your apps, games, and displays.
- **Instant Replay:** A clipping mechanism to save the last couple of minutes of your gameplay.
- **Multi-Hardware Support:** Reflex supports NVIDIA, AMD, and Intel hardware.
- **No Accounts or Telemetry:** No account or data is needed from you; run a quick install and you are ready to go.
- **No Ads or Subscriptions:** Completely free with no advertisements. (If you want to show your support, you can donate to me through the links above.)

## System Requirements
Reflex requires the following minimum system specifications:

- **Operating System:** Windows 10 Build 1803 or higher (If you see a yellow border, you are running an older version).
- **Processor:** Any modern 64-bit CPU.
- **Memory:** 4 GB RAM (This is the minimum required to run both Reflex and your game/app).
- **Graphics:** Any integrated or dedicated graphics card that has atleast 1GB of VRAM.
- **DirectX:** Version 11 or higher.

## Current Limitations
Sadly, not everything will be perfect from the start. Due to limitations I am facing with libraries and APIs, here is a list of current issues:

- Recording Exclusive Fullscreen apps/games is inconsistent. Switch to Borderless Fullscreen/Borderless Windowed, or capture the whole display.
- No DLL injection is used to record Exclusive Fullscreen apps/games. This is to avoid triggering Anti-Cheat software and ensure the safety of everyone using the app.
- Some older games might not be recordable due to how their window creation is coded.

With enough support, hopefully all these limitations will be resolved, achieving the app's full potential :)

## Legal & Third-Party Credits
Reflex uses the following libraries:

### NVIDIA Video Codec SDK
This is governed by the NVIDIA Video Codec SDK License Agreement. By using this software, you agree to comply with NVIDIA's terms, including the restriction to use the SDK only with supported NVIDIA GPU hardware.

### AMD AMF
This project utilizes the AMD Advanced Media Framework (AMF) SDK, which is licensed under the MIT License.

### Intel oneVPL
This project utilizes Intel® VPL, which is licensed under the MIT License.
