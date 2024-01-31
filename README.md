<p align="center">
	<img src="logo.png" width="376" height="128" alt="Winlator Logo" />  
</p>

<p align="center">
      <b><a href="https://github.com/XHYN-PH/winlator-mod/issues">GAME COMPATIBILITY LIST</a> • <a href="https://winlator.com/">VISIT WINLATOR SITE</a></b>
</p>

<h4 align="center">Winlator is an Android application that lets you to run Windows (x86_64) applications with Wine and Box86/Box64.
</h4>

<p align="center">
    <a href="https://youtube.com/@xhyn_ph">
        <img src="https://img.shields.io/badge/YouTube-red?color=bd2c00&label=SUBSCRIBE&logo=youtube&logoColor=white"
            alt="YouTube">
     <a href="https://github.com/brunodev85/winlator">
        <img src="https://img.shields.io/badge/GitHub-100000?&label=WINLATOR&logo=github&logoColor=white"
            alt="Github">
     </a>
    <a href="https://discord.com/invite/q842JB4gCm">
        <img src="https://img.shields.io/discord/398318088170242053?color=5865F2&label=EmuGear&logo=discord&logoColor=white"
            alt="Discord">
    </a>
</p>

---

# Winlator
- This is an unofficial modication of Winlator based on Afei Mod & Main.
- I'm not the creator of any cache I modified. All files used on this cache is from respective owners/developers.

---

## ❓ FAQ - Frequently Asked Question(s)
Question #1: **DOES THIS SUPPORTS X64 or 64-BITS ???**
- Yes, It supports x64 applications. You may want to check other alternatives such as **[Termux-Box](https://github.com/olegos2/termux-box)**, **[Box64Droid](https://github.com/Ilya114/Box64Droid)**, **[MoBox](https://github.com/olegos2/mobox)**, **[Box4Droid](https://github.com/Herick75/Box4Droid)**, **[MiceWine](https://github.com/KreitinnSoftware/MiceWine)**, **[BRVM](https://github.com/Gamelover7825/BRVM)**, **[Fex-Android](https://github.com/AllPlatform/Fex-Android)**, **[androBox](https://github.com/Pipetto-crypto/androBox)**

Question #2: **DOES IS SUPPORT MALI-GPU ???**
- Yes, It's supported via VirGL Renderer and only OpenGL.

Question #3: **DOES IT SUPPORTS WINE ESYNC ???**
- Yes, Starting from version 4.0 it was implemented.

Question #4: **IS IT MUCH FASTER THAN OTHER EMULATORS ???**
- Can't say, It will be based on the game you will run but in Winlator case... Mobox is much faster than Winlator.

---

### 📲 PHONE REQUIREMENTS
Android 9 above is supported (8.x is also maybe supported)
#### COMPATIBLE GPU(s)
| GPU        | DDRAW | VIRGL OVERLAY | LLVM RENDERER | TURNIP | DXVK |
| ---------- | ----- | ------------- | ------------- | ------ | ---- |
| Mali GPUs  | SUPPORTED | SUPPORTED | SUPPORTED | NO | NO |
| PowerVR GPUs | SUPPORTED | SUPPORTED | SUPPORTED | NO | NO |
| Adreno 5xx | SUPPORTED | SUPPORTED | SUPPORTED | NO | NO |
| Adreno 6xx | SUPPORTED | SUPPORTED | SUPPORTED | SUPPORTED | YES |
| Adreno 7xx | SUPPORTED | SUPPORTED | SUPPORTED | PARTIALLY | YES |

#### VIRGL OVERLAY
> VirGL Overlay uses `virgl-renderer` as the renderer. To run VirGL Overlay in Exagear, you need any graphics accelerator with support for **OpenGL ES 2.1(3.0)** and higher. Author of original development VirGL Overlay is [Mittorn](https://github.com/mittorn/virglrenderer-android), author of modifications is [alexvorxx](https://github.com/alexvorxx/VirGL-Overlay-Rebuild).
#### TURNIP
> [Turnip](https://www.exagear.wiki/index.php?title=Turnip) open source Vulkan driver for Adreno. It uses the files `/dev/kgsl-3d0`, `/dev/dri/card0` to access the GPU. It requires Adreno 610+ GPU to run.
#### DDRAW & LLVM
> DDRAW is part of windows from very old OS, It supported all devices. While LLVM is software renderer which is very slow but good compatibility.

Turnip+Zink are part of the Mesa drivers.

---

### BUGS & TIPS
Some problems, bugs, and tips for the Winlator

> [!CAUTION]
> Winlator task manager is broken, process isn't showing.

> [!CAUTION]
> "Stop services on startup" button isn't functioning, you can kill it manually though.

> [!CAUTION]
> **Adreno 7xx** has flickering problems due to Turnip problems.

> [!TIP]
> To solve not woking renderers For **Snapdragon 845** please turn off Dri3 extension in Winlator Settings.

---

### 📂 DOWNLOAD

---

### 🌐 COMMUNITIES

- [Alien's Community](https://t.me/exageartesting)
- [MishkaKolos Telegram](https://t.me/MishkaKolosExagear)
- [MishkaKolos Discord](https://discord.com/invite/qJ4HvDt)
- [ExaGear Allmod](https://t.me/exagearallmod)
- [Ajay's Community](https://discord.gg/XpbEp3dWv3)
- [Denis Rachev Community](https://t.me/denis_rachev2)
- [WEmu WIP](https://t.me/+IubWjXHbtScwOWQy)
- [Cassia WIP](https://discord.gg/XnbXNQM)
- [Project009's Community](https://discord.com/invite/GAg9eYg24G)
- [Box64Droid Discord](https://discord.gg/thjpZ4P7Bm)
- [Box64Droid Telegram](https://t.me/box64droidchat)
- [CoreLand's Community](https://t.me/CoreLand)
- [JotarOS Commmunity](https://t.me/EmulatorsROM)

---

### 📚 ACKNOWLEDGEMENTS

- [Windows Compatibility Layer by WineHQ](https://www.winehq.org/)
- [Input-Bridge by @DotNetBurst](https://github.com/DotNetBurst/)
- [Ubuntu RootFS](https://releases.ubuntu.com/focal)
- [PRoot](https://proot-me.github.io)
- [Mesa3D](www.mesa3d.org)
- [DXVK by @Doitsujin](https://github.com/doitsujin/dxvk)
- [D8VK by AlpyneDreams](https://github.com/AlpyneDreams/d8vk)
- [WineD3D For Windows by @Adolfintel](https://github.com/adolfintel/wined3d4win)

And Special Thanks to [alexvorxx](https://github.com/alexvorxx) for the Mesa mods and build instructions
