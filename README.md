# SMASH ACE-BUILD ([Click here to see the credits](https://docs.google.com/document/d/1Gf4D1QfHeXMQQrJpcbCatRuUmxijvP8ON1clqmF6uEU/edit?pli=1&tab=t.0))

An add-on to the Base ACE Mod, which aims to include every currently released character and some newcomers making their first public debut in ACE in one big melee build for fun. 
Please note that we're not part of or affiliated with the official ACE Team. This is a free, fun build for those who want all of the characters in one place.

Want to stay up to date on announcements, or looking to hang out and play some matches with the build? Join the [Smash ACE Discord Server](https://discord.gg/AwmmEPQmtG)

*Powered by the [m-ex](https://github.com/akaneia/m-ex) system.*

## Getting Started

### Patching the ISO 

To apply the ACE build patch, you will first need a clean *Super Smash Bros. Melee v1.2* ISO (MD5: `0e63d4223b01d9aba596259dc155a174`). 

You can download the latest patch release from:  
https://github.com/Chri222k/ACE-BUILD-PUBLIC-/releases  

Detailed instructions for applying the patch are included in the release. 

Once patched, your ISO should match the
v1.0.1 (MD5:`072f3f07cfaa1602960be31e68d7e800`)

---

### Building the Project

This repository contains the project data for the latest version of the ACE build.

> **Note:** If you wish to build on top of this project, you will need to extract the files from the patched ISO yourself. 
> 
> Follow the steps below to get started.

#### 1. Clone Repository

#### 2. Get ACE Build ISO

1. See *Patching the ISO* for details on patching your iso.
2. Add iso location to the Dolphin game paths so that it appears in the game list.

#### 3. Extract Files Using Dolphin

1. Open **Dolphin** and locate the **ACE Build** entry in your game list.
2. Right-click the game and select **Properties**.
3. Go to the **Filesystem** tab.
4. Right-click on **Disc** in the file tree and choose **"Extract Entire Disc..."**
5. Choose the **"ACE-build"** as the destination.

After extraction, your project folder should look like this:

```
ACE-build/
├── assets/
├── data/
├── files/
├── sys/
└── ace.mexproj
```

#### 4. Open the Project in MexManager

1. Download MexManager from: https://github.com/Ploaj/MexManager/releases
2. Extract the archive and launch `MexManager.Desktop.exe`.
3. Go to **File → Open** and select the `ace.mexproj` file
4. Make your desired edits (for more information, see Cjag's [Guide to Melee Modding 1](https://docs.google.com/document/d/182_TA9ImYDFKohjvdautMTTK66k-mUaMmBP6Lt5FLhI/edit?tab=t.0))
5. Save your changes via **File → Save**
6. When ready, you may export the modified ISO using **File → Export ISO**
