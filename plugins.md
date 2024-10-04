# Tangerine Rust Server - Plugins

This document provides an overview of the plugins used across the Tangerine Rust Server, along with brief descriptions of each plugin's role in server functionality, moderation, and gameplay enhancements.

## Plugins List

### Gameplay Enhancements

- [AlphaLoot.cs](https://chaoscode.io/resources/alphaloot.13/): Modifies loot tables and spawn rates, allowing for customized loot distribution in crates and barrels.
- Bitcoin.cs: Adds a Bitcoin reward system, tying in-game mechanics to Bitcoin mining and hash rewards.
- [DynamicPVP.cs](https://umod.org/plugins/dynamic-pvp): Handles our dynamicPVP zones at monuments
- [RemoverTool.cs](https://umod.org/plugins/remover-tool): Allows players or admins to remove placed structures or objects for a fee or free.
- [SkinBox.cs](https://chaoscode.io/resources/skinbox.17/): Provides players with access to skins for their items via the SkinBox plugin.
- [TruePVE.cs](https://umod.org/plugins/true-pve): Enables PvE environment on server.

### Events & Challenges

- [RaidableBases.cs](https://lone.design/product/raidable-bases-rust-plugin/): Adds bases to the game that players can raid, either as pre-built locations or admin-spawned events.
- [ClaimPlayerRewards.cs](https://github.com/goodmorningbitcoin/Claim-Player-Rewards): Handles the /claim command for players to claim blood or other rewards based on performance in the wipe.
- [DepositBox.cs](https://github.com/goodmorningbitcoin/DepositBox): Manages the deposit of hash (represented as paper) into specific boxes for rewards and events like Hodl Havoc.
- [Sputnik.cs](https://lone.design/product/sputnik/): A plugin for spawning satellite-like objects in-game, offering high-value loot guarded by defenses.

### Utility Plugins

- [BiPlane.cs](https://lone.design/product/biplane-rust-plugin/): Allows the creation and deployment of simple in-game aircraft for enhanced mobility.
- [CarRadio.cs](https://umod.org/plugins/car-radio): Adds functional car radios, allowing players to play music while driving their vehicles.
- [CopyPaste.cs](https://umod.org/plugins/copy-paste): Enables admins to copy and paste structures in the game world, useful for building event arenas or saving player builds.
- [CupboardLimiters.cs](https://umod.org/plugins/cupboard-limiter): Limits the number of tool cupboards a player or team can place, balancing building control.
- [CustomVendingSetup.cs](https://umod.org/plugins/custom-vending-setup): Customizes vending machines to sell specific items or services.
- [DefaultRadioStation.cs](https://umod.org/plugins/default-radio-station): Sets up default radio stations for players to tune into in their bases or vehicles.
- ItemCountTracker.cs: Allows for tracking of paper items on the server in player control.
- [MarketplaceUi.cs](https://codefling.com/plugins/marketplace): A user interface for the in-game marketplace, making it easier for players to buy and sell items.
- [MonumentAddons.cs](https://umod.org/plugins/monument-addons): Enhances or modifies the standard monuments with new features or interactions.
- Orangemart.cs: Handles Bitcoin payment integration
- [RadioStationManager.cs](https://umod.org/plugins/radio-station-manager): Manages in-game radio stations.
- [SignArtist.cs](https://umod.org/plugins/sign-artist): Allows players to upload custom images to in-game signs, useful for personalizing bases.

### Server Information

- [DiscordAuth.cs](https://umod.org/plugins/discord-auth): Connects players’ in-game profiles to Discord for easier verification and integration with the community.
- [DiscordStatus.cs](https://umod.org/plugins/discord-status): Shows the current status of the server in Discord channels, such as player count or server uptime.
- [ServerInfo.cs](https://umod.org/plugins/server-info): Provides players with essential server information, such as rules, commands, or event schedules.
- [ServerPop.cs](https://codefling.com/plugins/server-pop): Tracks and displays server population statistics in real-time, helping admins gauge player activity.
- [Rustcord.cs](https://umod.org/plugins/rustcord): Integrates Discord with the server, allowing admins and players to interact with the server through Discord.
- [VendingMachineLogs.cs](https://umod.org/plugins/vending-machine-logs): Logs all transactions made at vending machines for tracking and balancing the in-game economy.

### Administration & Moderation

- [AdminDeepCover.cs](https://umod.org/plugins/admin-deep-cover): Allows admins to spectate or operate without showing up in the player list, maintaining anonymity.
- [AdminPanel.cs](https://umod.org/plugins/admin-panel): Provides an administrative panel for in-game server management.
- [AdminRadar.cs](https://umod.org/plugins/admin-radar): An admin tool to track players and items on the map for rule enforcement.
- [InventoryViewer.cs](https://umod.org/plugins/inventory-viewer): Allows admins to view and manage players’ inventories for moderation and rule enforcement.
- [NoGiveNotices.cs](https://umod.org/plugins/no-give-notices): Suppresses notifications in the chat when players are given items.
- [PermissionsManager.cs](https://codefling.com/plugins/permissions-manager): Allows admins to easily manage player permissions and access.
- [PlayerAdministration.cs](https://umod.org/plugins/player-administration): A suite of tools for managing player accounts, bans, and other admin-related tasks.
- [Vanish.cs](https://umod.org/plugins/vanish): Allows admins to vanish from player view for covert moderation.

### Miscellaneous

- [ChaosExtensionDownloader.cs](https://chaoscode.io/resources/chaos.321/): A utility to download and manage Chaos extensions for customizable mods.
- [ImageLibrary.cs](https://umod.org/plugins/image-library): A library that helps render custom user interfaces for plugins.
- [MonumentFinder.cs](https://umod.org/plugins/monument-finder): Helps plugins locate monuments on the map, making it easier to find key locations.
- [NpcSpawn.cs](https://codefling.com/extensions/npc-spawn): Manages the spawning of NPCs at monuments or around the map.
- [UpdateChecker.cs](https://codefling.com/plugins/update-checker): Automatically checks for updates to installed plugins, ensuring the server is running the latest versions.
- [ZoneManager.cs](https://umod.org/plugins/zone-manager): Manages different zones on the map, such as safe zones or PvP zones, with different rules.
