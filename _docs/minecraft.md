---
title: Minecraft
permalink: /docs/games/minecraft/
---

### MultiMC (First time setup)

To launch two separate Minecraft instances, we will need a launcher called MultiMC.

* Download and extract [MultiMC](https://multimc.org/#Download)

* Run MultiMC and log in with your Mojang account.

* Create an instance by Add Instance. At the time of writing, the latest version (1.17.1) doesn't have Forge support which is required for controllers. If you are only using keyboards and mice, you can use 1.17.1, otherwise use 1.16.5

* Launch the instance at least once, then close it (this sets up some necessary files)

* Right click the instance, then `Edit instance`. Then click Install Forge.

![Install Forge](../../../img/games/minecraft/installforge.png)

* If you are using controllers, download the latest [Controllable mod](https://www.curseforge.com/minecraft/mc-mods/controllable/files) for your version of Minecraft. If you want to get better performance, also download the latest [OptiFine](https://optifine.net/downloads).

* In `Loader Mods`, click `Add`, then select the mod files

![Install Forge](../../../img/games/minecraft/mods.png)

* Go back to the main window for MultiMC, right-click on the instance, then `Copy Instance`. Do this until you have as many instances as players.

### Nucleus setup

* Open Nucleus Co-Op and download the Minecraft script from the script browser. Assign your devices as usual, then click Play.

* Nucleus will open MultiMC. You will need to launch each instance, then select the `javaw.exe` processes when Nucleus prompts you.
 * (If you have multiple Minecraft accounts) Select the first instance and click Launch. Change account in the top-right corner, then repeat for the next instance.
 * (If you have one Minecraft account) Select the first instance and click Launch Offline. Set your username to anything. Repeat for the next instance

* Wait for Nucleus to reposition all the windows, then go into the controller settings for each instance and make sure the right controller is selected. For keyboard/mouse instances you will need to deselect any controllers.

* Start a singlepalyer world and open to LAN in the pause menu. The other players can join from the multiplayer menu. Alternatively, you can connect to any server (with multiple Minecraft accounts), or an 'Offline' server (if you are using one Minecraft account).

* Once everything is set up, press End to lock input and start playing. When you want to stop, save and exit your world, press End to unlock input, then Ctrl+Q to close everything.