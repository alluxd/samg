# :icon-gear: 2. Core Mods
## :icon-file: Installing core mods.
These mods are essential for the game to run properly.

Includes: 
- Ultimate ASI Loader 
- CLEO
- Largeaddress
- Modloader
-------------------------------------
###  :icon-cpu: Ultimate ASI Loader
Ultimate ASI Loader is a tool that loads .asi files. ASI files are plugins, for example: Cheat Menus, Tuning Mod, etc. Most mods you can find nowadays are .asi files. This ASI Loader is required to load them. Even CLEO itself is an ASI plugin.

#### :icon-download: Installation
1. Download it from: https://github.com/ThirteenAG/Ultimate-ASI-Loader/releases
2. Open the archive using 7-Zip (or WinRAR) and isolate the **dinput8.dll** to a folder.
3. Rename the file to exactly **"vorbisFile.dll"** without any typos.
4. Copy the file to your game directory and replace files when asked.
5. Launch the game (optional)


-------------------------------------


### :icon-apps: CLEO
Cleo is an ASI plugin which loads .cs files. CS files are cleo scripts which add certain functions to the game. Cleo scripts are also very widely used in mods and you can find them in a ton of mods. Cleo scripts were developed to replace modding by modifiying the main.scm file. Cleo scripts also do exist on other platforms like Android and iOS.

#### :icon-download: Installation
1. Navigate to: https://cleo.li
2. Click on Download for GTA SA, you should be in a GitHub page.
3. Download the zip file by clicking on "CLEO4.zip" in the assets tab.
4. Open the archive and copy the following to your game directory:
-![Do not copy the folders/files in red, only the green ones.](/images/cleoInstall.png)-
:icon-check: Your game now has CLEO support.

:icon-alert: The reason why the cleo_sdk and cleo_readme are in red is because they are folders that CLEO doesn't need to run, and since we already have an ASI Loader we don't need the vorbisFile.dll in the archive. Some mods come with this file, so make sure to not move it into your game directory.


#### :icon-gear: CLEO Plugins
Now we need to install two plugins for CLEO which will add more Opcodes to it. This will extend CLEO's functionallity and a ton of mods require them. 
The plugins we need are CLEO+ and NewOpcodes. CLEO+ is a newer alternative to NewOpcodes, but it does not contain all the Opcodes provided by NewOpcodes, so we are going to pair them.

+++ :icon-plus: Installing CLEO+
![](/images/CLEOpluslogo.png)
1. :icon-browser: Navigate to: [MixMods](https://mixmods.com.br)
2. :icon-search: Type in "CLEO+" in the search bar and click on the search button.
3. :icon-clock: Click on the first one that comes up, scroll down and click on download which should redirect you to a ShareMods link.
4. :icon-download: Click on **Create Download Link** and wait 5 seconds, then click **Download Link is Ready**
5. :icon-file-directory-fill: On the next page, click **Start Download** and open the archive and copy the "CLEO" folder to your game directory.
+++ :icon-globe: Installing NewOpCodes
![](/images/newopcodeslogo.png)
1. :icon-browser: Navigate to [MixMods](https://mixmods.com.br) and search for "NewOpCodes" and click the one named "**NewOpcodes.cleo v2.1**"
2. :icon-download: Click on Download and open the archive once finished.
3. :icon-file-directory-fill: Copy the "CLEO" folder inside the mod to your game directory.
4. :icon-check: Launch the game and see if everything works.
+++

-------------------------------------


### :icon-file-directory-fill: Largeaddress
By default, GTA SA can't use more than 1024 MB of ram. This is because it is a 32 bit application and does not have the /LARGEADDRESSAWARE flag in the executable. Largeaddress enables that flag and will allow you to use more than 1024 MB of ram. 

___Work In Progress ___

