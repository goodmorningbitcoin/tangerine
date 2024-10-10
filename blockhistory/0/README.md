# Block 0 - Overview

## Key Features
- **Bitcoin Rewards**: Players can earn Bitcoin by turning in hash generated through mining rigs or found on the map.
- **Custom Raidable Bases**: Raidable bases have been introduced with special loot, providing players new raid challenges.
- **SkinBox Access**: Players can use the **SkinBox** plugin to customize their items with a selection of skins.
- **Sputnik**: Satellite fragments crash-land across the map, guarded by helicopters, NPCs, and turrets. Players must use special Space Cards to access high-value loot.

## Server Environment Variables
- **Map Size**: 3000, procedurally generated.
- **Map Seed**: 1163722885.
- **PVP Server**: Base protection is enabled, with restrictions outlined below.
- **Team Limits**: Maximum of 8 players per team.
- **Tool Cupboard (TC) Limit**: 3 TCs per team.
- **Max Players**: 75 players at one time.
- **Region**: North America.
- **Gather Rate**: Vanilla
- **Crafting Speed**: Vanilla
- **Decay Rate**: Vanilla

## Base Protection
- **Base Protection**: 100% until Friday, September 27th, 2024, at 12:00 AM UTC.
- **Twig Structures**: Not protected—upgrade to wood or higher for protection.

## Hash and Rewards
- **Satoshi Reward Pool**: Players will compete for a total of **100,000 satoshis** in rewards, generously provided by **Orangemart**, our main sponsor for this wipe.
- **Bitcoin Miner**: Utilize your own /bitcoin miner to generate hash to turn in during the **Hodl Havoc**
- **Hash**: Not only can you mine for hash but lots of events will reward players with hash as well. 
- **Bitcoin Rewards**: Earn Bitcoin by turning in hash at the Outpost during the **Hodl Havoc** event. The more hash you submit, the greater your share of the prize pool.

## Hodl Havoc Event
- **Starts**: Friday, September 27th, 2024, at 12:00 AM UTC.
- **Ends**: Sunday, September 29th, 2024, at 11:59 PM UTC.
- **Event Details**:  
  - During **Hodl Havoc**, base protection is lifted, and players can raid and turn in their accumulated **hash** (represented as in-game paper) at the community center near the Outpost.
  - Each deposit logs the player's SteamID, the amount of hash turned in, and the time of the deposit.
  - Players can earn bonus credits for hash deposits based on when they turn it in:
    - **Friday**: 1.0x credit
    - **Saturday**: 1.1x credit
    - **Sunday**: 1.25x credit
  - The more hash you submit, the larger your share of the **100,000 satoshi reward pool**, courtesy of **Orangemart**.

## Wipe Schedule
- **Map Wipe**: The map will wipe on the first Thursday of every month, with the next wipe scheduled for **Thursday, October 3rd, 2024**.
- **Blueprint Wipe**: Blueprints wipe alongside the map, the next blueprint wipe scheduled for **Thursday, October 3rd, 2024**.
- **Base Protection Lifted**: Base protection will be lifted on **Friday, September 27th, 2024**, at 12:00 AM UTC for **Hodl Havoc**.

## Changelog for Block 0
- **09/27/2024**: Hodl Havoc begins. Players can now turn in hash for Bitcoin rewards and RaidProtection has been removed.
- **09/05/2024**: Block 0 begins.

## Logs and Additional Information
- [Hash Deposits Log](./DepositBoxLog.json)

## Plugins Used in Block 0
- **AdminDeepCover.cs**: Allows admins to spectate anonymously.
- **AdminPanel.cs**: Provides an in-game admin panel for managing the server.
- **AdminRadar.cs**: Tracks players and items for admin use.
- **AlphaLoot.cs**: Modifies loot tables and spawn rates.
- **AnyMapVendor.cs**: Adds a traveling vendor to maps without looping roadways.
- **BiPlane.cs**: Allows players to use simple in-game aircraft.
- **Bitcoin.cs**: Adds a Bitcoin reward system for in-game activities.
- **CarRadio.cs**: Adds functional car radios.
- **ChaosExtensionDownloader.cs**: Manages Chaos extensions for the server.
- **ClaimRewards.cs**: Handles `/claim` command for claiming blood or rewards.
- **CopyPaste.cs**: Enables admins to copy and paste structures.
- **CupboardLimiters.cs**: Limits the number of TCs a team can place.
- **CustomVendingSetup.cs**: Customizes vending machines for in-game services.
- **DeathNotes.cs**: Shows kill notifications in the chat.
- **DefaultRadioStation.cs**: Sets up default radio stations for players.
- **DepositBox.cs**: Manages hash deposits for rewards.
- **DiscordAuth.cs**: Connects in-game profiles with Discord.
- **DiscordStatus.cs**: Shows server status in Discord.
- **ImageLibrary.cs**: Renders custom user interfaces for plugins.
- **InventoryViewer.cs**: Allows admins to manage player inventories.
- **ItemCountTracker.cs**: Tracks in-game paper across the server.
- **MarketplaceUi.cs**: Adds a UI for in-game marketplaces.
- **MonumentAddons.cs**: Adds features to standard monuments.
- **MonumentFinder.cs**: Helps players locate monuments.
- **NoGiveNotices.cs**: Suppresses notifications when items are given.
- **NoGreen.cs**: Prevents admins from being marked with green chat.
- **NpcSpawn.cs**: Manages NPC spawns at monuments.
- **PermissionsManager.cs**: Allows easy management of player permissions.
- **PlayerAdministration.cs**: Manages player accounts, bans, and tasks.
- **RadioStationManager.cs**: Manages in-game radio stations.
- **RaidProtection.cs**: Handles base protection mechanics.
- **RaidableBases.cs**: Adds bases that can be raided.
- **RemoverTool.cs**: Allows players or admins to remove structures.
- **Rustcord.cs**: Integrates Discord with the server for interaction.
- **ServerInfo.cs**: Displays essential server information.
- **ServerPop.cs**: Tracks server population in real-time.
- **SignArtist.cs**: Lets players upload custom images to signs.
- **SkinBox.cs**: Provides access to item skins.
- **Sputnik.cs**: Adds satellite-like objects to the game.
- **UpdateChecker.cs**: Checks for plugin updates automatically.
- **Vanish.cs**: Allows admins to become invisible to players.
- **VendingMachineLogs.cs**: Logs vending machine transactions.
- **ZoneManager.cs**: Manages safe and PvP zones on the map.
