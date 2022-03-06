# EhBMinecraftServer
Minecraft server configuration for the EhB Gaming Community. Uses [Fabric Modloader](https://fabricmc.net/).<br>
Configured for Minecraft version 1.18.2. Mods for version 1.18.0, 1.18.1 or other minor versions should still be compatible but need to be tested first.<br>

# Installation

1. Clone this repository.
2. cd EhBMinecraftServer
3. run ./start.bat

# Config Guides
- Text Formatting: [(guide)](https://placeholders.pb4.eu/user/default-placeholders/)
- Styled Nicknames: [(guide)](https://www.curseforge.com/minecraft/mc-mods/styled-nicknames)
- Styled Player List: [(guide)](https://github.com/Patbox/StyledPlayerList#configuration)


# Installed Server Mods
- [Fabric API](https://www.curseforge.com/minecraft/mc-mods/fabric-api): Dependency.
- [Collective (Fabric)](https://www.curseforge.com/minecraft/mc-mods/collective-fabric): Dependency.
- [Cloth Config API (Fabric)](https://www.curseforge.com/minecraft/mc-mods/cloth-config): Dependency.
- [Mod Menu](https://www.curseforge.com/minecraft/mc-mods/modmenu/): Dependency.
- [Textile Backup](https://www.curseforge.com/minecraft/mc-mods/textile-backup): Server Backups.
- [FerriteCore](https://modrinth.com/mod/ferrite-core): Memory usage optimizer. [Explanation]((https://github.com/malte0811/FerriteCore/blob/main/summary.md)) For the Java nerds.
- [ServerCore](https://www.curseforge.com/minecraft/mc-mods/servercore): Various minor server-side performance improvements.  
- [First Join Message](https://www.curseforge.com/minecraft/mc-mods/first-join-message-fabric): Sends a message to players who join a world for the first time.
- [Spark](https://www.curseforge.com/minecraft/mc-mods/spark): Performance profiler.
- [Clumps](https://www.curseforge.com/minecraft/mc-mods/clumps): Clumps groups XP orbs together into a single entity to reduce lag when there are many in a small area.
- [Lithium](https://modrinth.com/mod/lithium): improve a number of systems (game physics, mob AI, block ticking, etc) with the goal of not changing any vanilla mechanics.
- [Phosphor](https://www.curseforge.com/minecraft/mc-mods/phosphor): Phosphor is a Minecraft mod which works to optimize one of game's most inefficient areas-- the lighting engine.
- [Dynamic View](https://www.curseforge.com/minecraft/mc-mods/dynamic-view): Dynamically changed chunk loading distance based on server load.
- [FastBench](https://www.curseforge.com/minecraft/mc-mods/fastbench-for-fabric): Performance fix for crafting tables.
- [Styled Chat](https://www.curseforge.com/minecraft/mc-mods/styled-chat): It's a simple mod that allows server owners to change how their chat looks!
- [Styled Nicknames](https://www.curseforge.com/minecraft/mc-mods/styled-nicknames): It's a configurable mod allowing your server's players (and admins) to change their nickname with full Simplified Text Formatting support.
- [Styled Player List](https://www.curseforge.com/minecraft/mc-mods/styled-player-list): It's a simple mod that allows server owners to style their player list as they like! With full permission support, placeholder API support, multiple styles and player name overrides.
- [BanHammer](https://www.curseforge.com/minecraft/mc-mods/patboxs-banhammer): Simple, customizable punishment utility mod for Fabric. Allows moderators to permanently/temporary ban, mute or kick players.
- [Compact Help Command](https://www.curseforge.com/minecraft/mc-mods/compact-help-command-fabric): Better /help command.
- [Ksyxis](https://www.curseforge.com/minecraft/mc-mods/ksyxis): Faster loading when booting server. VM is very slow.
- [LazyDFU](https://modrinth.com/mod/lazydfu): Performance improvements by making some initialization lazy.
- [Krypton](https://www.curseforge.com/minecraft/mc-mods/krypton): Networking performance optimizer.
- [Server Chat History](https://modrinth.com/mod/server-chat-history): Sends the chat history to players on join.
- [Plan | Player Analytics](https://www.curseforge.com/minecraft/mc-mods/plan-player-analytics): Dashboard with analytics.

### Mods of interest
- [MCDiscordChat](https://modrinth.com/mod/mcdiscordchat): Discord integration.
- [LuckPerms](https://luckperms.net/): Very advanced permissions management.
- [Fast Furnace](https://www.curseforge.com/minecraft/mc-mods/fast-furnace-for-fabric): Performance fix for furnaces. Currently broken? Try again later.
- [FabricHomes](https://www.curseforge.com/minecraft/mc-mods/fabrichomes): Enkele commands om home locatie in te stellen. Misschien handig om met discord te integreren.
- [Multiplayer Server Pause](https://www.curseforge.com/minecraft/mc-mods/multiplayer-server-pause-fabric): Helps save server resources by pausing server when nobody is connected.
- [Chat+](https://www.curseforge.com/minecraft/mc-mods/chat): More chat stuff. Not sure if it required client-side install.
- [Essential Commands](https://www.curseforge.com/minecraft/mc-mods/essential-commands): More commands.
- [Factions](https://www.curseforge.com/minecraft/mc-mods/factions-fabric): Multiplayer Factions. Might be interesting for teams PvP stuff. (Not updated yet?)
- [Teams](https://www.curseforge.com/minecraft/mc-mods/teams): Teams. Not sure if it required client-side install.
- [Ledger](https://www.curseforge.com/minecraft/mc-mods/ledger): Server logger.
- [MoreCommands](https://www.curseforge.com/minecraft/mc-mods/morecommands): Adds more commands. Discord integration?
- [Alternate Current](https://www.curseforge.com/minecraft/mc-mods/alternate-current): Much faster redstone implementation. Redstone will no longer be directional so some redstone builds will break.
- [Server Holograms](https://www.curseforge.com/minecraft/mc-mods/server-holograms): Server side holograms with full support for formatting and items.
- [Chunky Pregenerator](https://www.curseforge.com/minecraft/mc-mods/chunky-pregenerator): Pre-generate chunks.
- [KubeJS](https://www.curseforge.com/minecraft/mc-mods/kubejs-fabric): Write JavaScript scripts to manage the server.
- [Starter Kit](https://www.curseforge.com/minecraft/mc-mods/starter-kit-fabric): Give players server rules or something.
- [Fabric Tree Chopper](https://www.curseforge.com/minecraft/mc-mods/fabric-tree-chopper): Destroys entire trees.
- [Polymer](https://www.curseforge.com/minecraft/mc-mods/polymer): For developers. Server-side library for creating custom blocks, items and entities.

# Recommended Client-side Mods
These mods are entirely optional.
- [Sodium](https://modrinth.com/mod/sodium): Requires [Fabric](https://fabricmc.net/) Launcher. Sodium is a free and open-source rendering engine replacement for the Minecraft client that greatly improves frame rates, reduces micro-stutter, and fixes graphical issues in Minecraft. Up to 5x FPS increase. Like optifine but better.
- [MoreCommands](https://www.curseforge.com/minecraft/mc-mods/morecommands): Adds more commands. Discord integration?

# TODO
- Auto-start server when VM starts.
- Auto-download all mods script.
- ServerCore mod complicated configuration.
