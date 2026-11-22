# far-cry-2004-aliens-vs-predator-2-aliens-vs-predator-2
## Far Cry 2004 - Aliens vs Predator 2
A total conversion mod for Far Cry 2004 that remakes Aliens vs Predator 2.

## Github Treeview
[https://treegit.macosxjs.com/?url=igiteam/far-cry-2004-aliens-vs-predator-2](https://treegit.macosxjs.com/?url=igiteam/far-cry-2004-aliens-vs-predator-2)

## Github Tree Api Direct JSON
[https://api.github.com/repos/igiteam/far-cry-2004-aliens-vs-predator-2/git/trees/main?recursive=1](https://api.github.com/repos/igiteam/far-cry-2004-aliens-vs-predator-2/git/trees/main?recursive=1)

## Base gameplay
[![farcryigi1](https://img.youtube.com/vi/Hqrr6yR5CwY/maxresdefault.jpg)](https://ytembed.macosxjs.com/?SHFycjZ5UjVDd1k)

[![Aliens VS. Predator 2 - Marine Campaign](https://img.youtube.com/vi/iu_J7HGPWkU/maxresdefault.jpg)](https://ytembed.macosxjs.com/?aXVfSjdIR1BXa1U)

## WS11WineCX20.0.4 (MacOSX Big Sur 32bit)
[WS11WineCX20.0.4.tar.7z](https://github.com/vitor251093/porting-kit-engines/releases/download/wineskin/WS11WineCX20.0.4.tar.7z)

[![wine windows games on macosx](https://raw.githubusercontent.com/igiteam/igi1-macbook-3d-workstation/refs/heads/main/wine-engine-config.png)](https://github.com/igiteam/wine_engines)


## Reference links
[https://archive.org/details/avp-2-gold-edition](https://archive.org/details/avp-2-gold-edition)

[https://archive.org/details/far-cry-1.40-gametools-src](https://archive.org/details/far-cry-1.40-gametools-src)

[![Far Cry MacOSX Wineskin](https://i.ytimg.com/vi/ShjANt3tN8o/hqdefault.jpg)](https://www.youtube.com/playlist?list=PLb8oNKiUbnjHprmtAjCAv7Kkz8XOX_XRb)

[![Far cry 1 Sandbox Editor creating a map tutorial no4](https://img.youtube.com/vi/ijnlG84gcqs/hqdefault.jpg)](https://ytembed.macosxjs.com/?aWpubEc4NGdjcXM)

[![Far Cry 2004](https://raw.githubusercontent.com/igiteam/far-cry-2004-aliens-vs-predator-2/refs/heads/main/farcry1.jpg)](https://archive.org/details/far-cry_202402)

[![Aliens vs Predator 2](https://raw.githubusercontent.com/igiteam/far-cry-2004-aliens-vs-predator-2/refs/heads/main/Aliens_vs._Predator_2_Box_Cover.jpg)](https://archive.org/details/avp-2-gold-edition)


# FarCry

This is mostly unchanged original [leaked Far Cry source tree](https://archive.org/details/far-cry-1.34-complete).
Some modifications were made to original sources and project configuration in order to make it able to be built using Visual Studio 2022 for x64 v143 target.  
This repository has 2 branches:
* [leak](https://github.com/n1f7/FarCry/tree/leak) - contains the original leaked source with project files overwritten by `AMD64_ProjectFiles_VS2005` contents
* [win32_x64 (default)](https://github.com/n1f7/FarCry/tree/win32_x64) - check out this branch if you want to build from sources using Visual Studio 2022

## Building from source
Bundled DirectX SDK was removed, so in order to build from sources you need to install [DirectX 9 SDK from Microsoft](https://www.microsoft.com/en-gb/download/details.aspx?id=6812).  
Just load `Game01.sln`, select `Release64` solution configuration and run `Build solution`.
20 out of 22 project will compile and link, only 2 will fail (`XRenderOGL` and `Editor`), you can unload them for the present if you wish.
## Running the binaries
X64 build was tested using assets from the latest Steam version of the game patched with [64-bit Upgrade Patch from PC Gaming Wiki](https://community.pcgamingwiki.com/files/file/442-far-cry-amd64-64-bit-upgrade-patch/).
Saves work fine, game still has some unhandled exceptions on shutdown only noticeable during debugging.  
1. Create some directory alongside `Bin32` or `Bin64` directories, for example `CustomBuild`
2. Place compiled binaries from `FarCry/x64/Release64/` folder (16 `DLL`s ans 3 `EXE`s in total)
3. You still need to copy the following 5 DLLs from `Bin64` folder: `DivxDecoder.dll`, `DivxMediaLib.dll`, `FileParser.dll`, `msvcr71.dll`, `crysound64.dll`
4. You can optionally copy some `*.pdb` files to aid debugging
   
The resultant file tree should look something like this:
```
CustomBuild
├── Cry3DEngine.dll
├── CryAISystem.dll
├── CryAnimation.dll
├── CryEntitySystem.dll
├── CryFont.dll
├── CryGame.dll
├── CryInput.dll
├── CryMovie.dll
├── CryNetwork.dll
├── CryPhysics.dll
├── CryScriptSystem.dll
├── CrySoundSystem.dll
├── CrySystem.dll
├── DivxDecoder.dll
├── DivxMediaLib.dll
├── FarCry.exe
├── FarCry_WinSV.exe
├── FileParser.dll
├── ResourceCompilerPC64.dll
├── XRenderD3D9.dll
├── XRenderNULL.dll
├── crysound64.dll
├── msvcr71.dll
└── rc64.exe
```

# Editor
Editor builds fine but linking stage still fails due to it still dependent on closed source proprietory XTreme Toolkit for MFC



## Dev Environment

**Official White Wii Remote With Nunchuk — Tested And Working — £14.99**
[https://www.ebay.co.uk/itm/800847189353](https://www.ebay.co.uk/itm/800847189353)

**Infrared Sensor Bar USB for Wii Emulator Remote Motion Detection Setup — £6.69**
[https://www.ebay.co.uk/itm/227423830875](https://www.ebay.co.uk/itm/227423830875)

**Apple MacBook Pro Retina 15in (2014) i7 2.8GHz 16GB 1TB SSD GT 750M — £120.30**
[https://www.ebay.co.uk/itm/800844561513](https://www.ebay.co.uk/itm/800844561513)

**WS11WineCX20.0.4 (Wine engine)**
[https://igiteam.github.io/wine_engines/](https://igiteam.github.io/wine_engines/)

**Official Genuine Sony PS3 PlayStation 3 DualShock 3 Wireless Controller Black — £19.99**
[https://www.ebay.co.uk/itm/840031043465](https://www.ebay.co.uk/itm/840031043465)

**Amazon Basics 4K HDMI Cable 3m — 18Gbps High Speed with Ethernet, 4K@60Hz, 2160p — £8.44**
[https://www.ebay.co.uk/itm/327352257557](https://www.ebay.co.uk/itm/327352257557)

**wiimote_nunchuk_macosx**
[https://github.com/igiteam/wiimote-nunchuk](https://github.com/igiteam/wiimote-nunchuk)

**xbox360_input_gui_py**
[https://github.com/igiteam/xbox360_input_gui_py](https://github.com/igiteam/xbox360_input_gui_py)

**logitec_mx_mouse_3_macos**
[https://github.com/igiteam/logitec_mx_mouse_3_macos](https://github.com/igiteam/logitec_mx_mouse_3_macos)

**igi1-macbook-3d-workstation**
[https://github.com/igiteam/igi1-macbook-3d-workstation](https://github.com/igiteam/igi1-macbook-3d-workstation)

---

