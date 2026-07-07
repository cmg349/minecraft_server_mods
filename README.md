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
> These mods will ahve to be installed locally to access the server. Without the mods installed locally the server will refuse the connection from the given user without them.

------------------------------------------------------------------------------
## **How to install mods locally.**

1. Download packaged mods from this github repo
2. Click the file "minecraft_server_mod_package.zip"
3. In the top right next to the .zip file name click the "..." menu button
4. Select "Download"
5. When the .zip file finishes downloading it should be found in your Windows "Download" folder.
6. Nvigate to the "Download" folder.
7. Right click on the "minecraft_server_mod_package.zip" folder and select "Extract All.."
8. Click "Browse"
9. Navigate to: *C:\Users\<YOUR USERNAME>\AppData\Roaming\.minecraft\mods*
10. Click "Select Folder" once at the above location.
11. Click "Extract" to extract the .jar files from the downloaded package to the *.minecraft\mods* folder location.

> [!NOTE]
> "< YOUR USERNAME >" is a variable place holder and should be replaced with your local Windows Username

If done successfully you should see the following .jar files listed in the *.minecraft\mods* folder:

- balm-fabric-26.2-26.2.0.2.jar
- fabric-api-0.154.2+26.2.jar
- Jade-mc26.2-Fabric-26.2.9.jar
- NaturesCompass-26.2-2.5.1-fabric.jar
- netherportalfix-fabric-26.2-26.2.0.1.jar
- smartbackpacks-1.0.0-fabric-26.2.jar
- waystones-fabric-26.2-26.2.0.3.jar
------------------------------------------------------------------------------

## **Trouble Shooting**

> [!NOTE]
> I DONT SEE THE AppData folder!!
This can happen if you do not have "show invisibile folders enabled on windows.
1. Open a Windows File Explorer
2. Navigate with the menu on top to "View"
3. In the section labeled "Show/Hide" make sure the check box next to "Hidden items" is checked.
------------------------------------------------------------------------------

### **Mod List (Client Side/ User):**

#### -Balm-
**Link:** https://www.curseforge.com/minecraft/mc-mods/balm \
**Description:** Balm is a library mod for mod developers that simplifies the process of creating multi-loader mods by providing common interfaces and events and removing the need for most mod-loader specific code. *(This is a support mod for other mods)*

#### -Fabric API- 
**Link:** https://www.curseforge.com/minecraft/mc-mods/fabric-api \
**Description:** Fabric API is the core library for the most common hooks and inter-compatibility measures utilized by mods using the Fabric toolchain.  *(This is a support mod for other mods)*

#### -Jade-  
**Link:** https://www.curseforge.com/minecraft/mc-mods/jade \
**Description:** Jade is the information HUD mod for modern Minecraft versions. Designed for better user experience and API.

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
