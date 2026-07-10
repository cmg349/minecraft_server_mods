# Mine Craft Mods Red Render Server

mods for minecraft server 

*mods must be compatible with Fabric and Minecraft version 26.2* 

=========================== 
\
**Server Details** 
- Minecraft Version: 26.2
- Minecraft Edition: Java
- Server Type: Fabric

> [!WARNING]
> These mods will have to be installed locally to access the server. Without the mods installed locally the server will refuse the connection from the given user without them.

> [!WARNING]
> If you have not or do not have Fabric API installed for your Minecraft Launcher you will need to get that & install it here: https://fabricmc.net/use/installer/
> Simply Download and Install and it will find your launcher and set itself up.  this allows you to use mods, specifically Fabric mods. If done successfully you will have
> a drop down option in your Minecraft Lanucher to select "fabric-loader-26.2" directly to the left of the "Play" button.  When you play on the server you will use "fabric-loader-26.2" as the game version.

------------------------------------------------------------------------------
## TLDR Check List to Access the Server
- [ ] Minecraft version 26.2 (Java)
- [ ] Fabric Installation for Minecraft Launcher (Installed)
- [ ] Location of my .minecraft/mods folders
- [ ] Mod list downloaded and added to the Minecraft "mods" folder
- [ ] Server Address (Request or get from Discord)

------------------------------------------------------------------------------
## **How to install mods locally.**

> [!NOTE]
> If you have Minecraft installed on a drive other than "C:", the file paths in the instructions will not work for you.  You will have to find where Minecraft is installed and locate your "mod" folder

> [!NOTE]
> If you have already installed these mods previously, and are re-downloading to get the most recent mods, you can choose to just replace or skip the conflicting mods that windows prompts you with "file already exists or is already found at"

### Finding my "mods" folder
1. Open you Minecraft Lanucher (What you run to click the green "PLAY" button)
2. In the top menu bar you will see "Play" "Installations" "Realms" ... etc; Click "Installations"
3. You should see an item that says "fabric-loader-26.2", If not please see the second WARNING at the top, then return here.
4. To the right of the "fabric-loader-26.2" item you should see a green "Play" button and a folder icon next to it, Click the folder icon.
5. This will bring you to your .minecraft folder. **(Save this file path as you will need to access it later)**
6. Here you should see a "mods" folder.
7. IF you do NOT see or have a "mods" folder you can manually create it.  This is where we will put all the mods for the server you will need.

### Windows OS
1. Download packaged mods from this github repo
2. Click the file "minecraft_server_mod_package.zip"
3. In the top right next to the .zip file name click the "..." menu button
4. Select "Download"
5. When the .zip file finishes downloading it should be found in your Windows "Download" folder.
6. Navigate to the "Download" folder.
7. Right click on the "minecraft_server_mod_package.zip" folder and select "Extract All.."
8. Click "Browse"
9. Navigate to: *C:\Users\<YOUR USERNAME>\AppData\Roaming\.minecraft\mods*  OR your specific file path for your .minecraft/mods folder (See above "Finding my mods folder")
10. Click "Select Folder" once at the above location.
11. Click "Extract" to extract the .jar files from the downloaded package to the *.minecraft\mods* folder location.


If done successfully you should see the following .jar files listed in the *\mods* folder:

- balm-fabric-26.2-26.2.0.2.jar
- enchantments-expansion-1.2.0-[26.2].jar
- fabric-api-0.154.2+26.2.jar
- Jade-mc26.2-Fabric-26.2.9.jar
- jei-26.2-fabric-30.7.0.41.jar
- NaturesCompass-26.2-2.5.1-fabric.jar
- netherportalfix-fabric-26.2-26.2.0.1.jar
- smartbackpacks-1.0.0-fabric-26.2.jar
- waystones-fabric-26.2-26.2.0.3.jar
- xaerominimap-fabric-26.2-26.2.0.jar


## Cursed Forge on Windows
1. Download packaged mods from this github repo
2. Click the file "minecraft_server_mod_package.zip"
3. In the top right next to the .zip file name click the "..." menu button
4. Select "Download"
5. When the .zip file finishes downloading it should be found in your Windows "Download" folder.
6. Navigate to the "Download" folder.
7. Right click on the "minecraft_server_mod_package.zip" folder and select "Extract All.."
8. Click "Browse"
9. Navigate to: *C:\Users\<YOUR USERNAME>\curseforge\minecraft\Instances\minecraft\mods*  OR your specific file path for your .minecraft/mods folder (See above "Finding my mods folder")
10. Click "Select Folder" once at the above location.
11. Click "Extract" to extract the .jar files from the downloaded package to the *.minecraft\mods* folder location.


> [!NOTE]
> "< YOUR USERNAME >" is a variable place holder and should be replaced with your local Windows Username
------------------------------------------------------------------------------

## **Trouble Shooting**

> [!NOTE]
> I DONT SEE THE AppData folder!!
This can happen if you do not have "show invisibile folders enabled on windows.
1. Open a Windows File Explorer
2. Navigate with the menu on top to "View"
3. In the section labeled "Show/Hide" make sure the check box next to "Hidden items" is checked.

> [!NOTE]
> Zip wont open or says its empty
If you are having issue with the normal download instructions.
1. On Github, after clicking on the .zip file, there should be a "View Raw" button of blue text.
2. Click this and you should be able to download the files with this method IF the original method is not working.

> [!NOTE]
> I don't see a "mods" folder in ".minecraft"
If you have never installed mods before this folder might not exist.
1. Right click on a blank area of your windows explorer window inside the ".minecraft" folder
2. select New>Folder
3. Name your new folder "mods"
4. you can now add your mods to this new folder

> [!NOTE]
> I installed the mods to the mods folder but I'm seeing "Miney Map" when I select multiplayer in Minecraft.
So you downloaded the mods, put them in the right spot, loaded up Minecraft version 26.2 Java edition but now this!?
1. You might have skipped or missed an important step in the set up Fabic Launcher install.
2. See the second WARNING at the top of the README.md and make sure you have that installed.
3. Once installed restart Minecraft and you should be good to go.
------------------------------------------------------------------------------

### **Mod List (Client Side/ User):**

#### -Balm-
**Link:** https://www.curseforge.com/minecraft/mc-mods/balm \
**Description:** Balm is a library mod for mod developers that simplifies the process of creating multi-loader mods by providing common interfaces and events and removing the need for most mod-loader specific code. *(This is a support mod for other mods)*

#### -Enchantment Expansion-
**Link:** https://www.curseforge.com/minecraft/mc-mods/enchantments-expansion \
**Description:** New vanilla-friendly enchantments, expanding the gameplay progression for tools, weapons, armor, shields, bows, pickaxes, axes, leggings, chestplates, boots and helmets.

#### -Fabric API- 
**Link:** https://www.curseforge.com/minecraft/mc-mods/fabric-api \
**Description:** Fabric API is the core library for the most common hooks and inter-compatibility measures utilized by mods using the Fabric toolchain.  *(This is a support mod for other mods)*

#### -Jade-  
**Link:** https://www.curseforge.com/minecraft/mc-mods/jade \
**Description:** Jade is the information HUD mod for modern Minecraft versions. Designed for better user experience and API.

#### -JEI-  
**Link:** https://www.curseforge.com/minecraft/mc-mods/jei \
**Description:** JEI is an item and recipe viewing mod for Minecraft, built from the ground up for stability and performance.

#### -Nature's Compass- 
**Link:** https://www.curseforge.com/minecraft/mc-mods/natures-compass \
**Description:** Nature's Compass is a utility item that allows you to search for a biome's location anywhere in the world and view information about it.

#### -Nether Portal fix-
**Link:** https://www.curseforge.com/minecraft/mc-mods/netherportalfix \
**Description:** keeps track of what portals a player went through in order to ensure correct destinations when the player is going back through the same portals. The 1:8 ratio remains, portals just get smarter and remember where you came from.

#### -Shogi-
**Link:** https://www.curseforge.com/minecraft/mc-mods/shogi
**Description:** This is a library mod that adds a rule-based effect system for use in Minecraft mods. Its most notable use is Waystones.

#### -Smart Backpacks-
**Link:** https://www.curseforge.com/minecraft/mc-mods/smart-backpacks \
**Description:** Smart Backpacks adds upgradeable portable storage backpacks to Minecraft, giving you a flexible inventory system that can grow from simple early-game storage into advanced automation, fluid, energy, and utility setups.

#### -WayStones-
**Link:** https://www.curseforge.com/minecraft/mc-mods/waystones \
**Description:** This mod adds waystone blocks that the player can return to once they've been activated, either through a Warp Scroll, a rechargeable Warp Stone, or by using an existing waystone to hop from one to the other.

#### -Xaero's Mini Map-  
**Link:** https://www.curseforge.com/minecraft/mc-mods/xaeros-minimap \
**Description:** Displays the nearby world terrain, players, mobs, entities in the corner of your screen.



**++++++++++ Server Admin Notes ++++++++++**
### **Mod List Server Side:**
*do NOT need to be installed locally*

#### -Dark Smithing- 
**Link:** https://www.curseforge.com/minecraft/mc-mods/darksmithing \
**Description:** Custom recipes for Smithing Templates used in Netherite upgrades and Armor Trims.

### **Dependancy Mods:**
*All fabric mods need Fabric API*

- NetherPortalFix --> Balm 
- Waystones --> Balm 
- Waystones --> Shogi
