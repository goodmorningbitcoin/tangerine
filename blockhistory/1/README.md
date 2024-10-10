## Block 1 - Overview

### Key Features
- **Bitcoin Rewards**: Players can continue to earn Bitcoin by turning in hash generated through mining rigs or found scattered across the map.
- **Custom Raidable Bases**: Raidable bases are present with special loot, providing new raid challenges for players.
- **SkinBox Access**: Players can use the SkinBox plugin to customize their items with a variety of skins.
- **Sputnik**: Satellite fragments will crash-land across the map, guarded by helicopters, NPCs, and turrets. Players must use Space Cards to access high-value loot.
- **New Mining Event**: Special mining events will periodically take place, allowing players to compete for additional hash rewards.

### Server Environment Variables
- **Map Size**: 4500, procedurally generated.
- **Map Seed**: 1951016938.
- **PVP Server**: Base protection is enabled, with specific rules outlined below.
- **Team Limits**: Maximum of 8 players per team.
- **Tool Cupboard (TC) Limit**: 3 TCs per player.
- **Max Players**: 50 players at one time.
- **Region**: North America.
- **Gather Rate**: Vanilla.
- **Crafting Speed**: Vanilla.
- **Decay Rate**: Vanilla.

### Base Protection
- **Base Protection**: 100% base protection is enabled for the entirety of Block 1.
- **Twig Structures**: Not protected—upgrade to wood or higher for protection.

### Hash and Rewards
- **Satoshi Reward Pool**: Players will compete for a total of 100,000 satoshis in rewards, generously provided by Orangemart, our main sponsor for this wipe.
- **Bitcoin Miner**: Utilize your own /bitcoin miner to generate hash to turn in throughout the wipe.
- **Hash**: Hash can be generated via mining rigs or earned from various in-game events.
- **Bitcoin Rewards**: Earn Bitcoin by turning in hash at the Outpost Community Center. The more hash you submit, the greater your share of the prize pool.

### Wipe Schedule
- **Map Wipe**: The map will wipe on the first Thursday of every month, with the next wipe scheduled for Thursday, November 7th, 2024.
- **Blueprint Wipe**: Blueprints wipe alongside the map, the next blueprint wipe is also scheduled for Thursday, November 7th, 2024.

## Changelog for Block 1
- **10/04/2024**: Block 1 begins.
- **10/08/2024**: Memory error caused miner error, daily restart implemented, claim reward given to authed players
- **10/09/2024**: Raidable Bases relaunched

## Logs and Additional Information
- [Bitcoin Miner Log](./bitcoin.json)
- [Hash Deposits Log](./depositboxlog.json)
- [Claim Rewards](./ClaimPlayerRewards.json)
- [Claimed Rewards](./claimedrewards.json)

## Plugins Used in Block 0
- **AdminDeepCover.cs**: Allows admins to spectate anonymously.
- **AdminPanel.cs**: Provides an in-game admin panel for managing the server.
- **AdminRadar.cs**: Tracks players and items for admin use.
- **AlphaLoot.cs**: Modifies loot tables and spawn rates.
- **BiPlane.cs**: Allows players to use simple in-game aircraft.
- **Bitcoin.cs**: Adds a Bitcoin reward system for in-game activities.
- **CarRadio.cs**: Adds functional car radios.
- **ChaosExtensionDownloader.cs**: Manages Chaos extensions for the server.
- **ClaimPlayerRewards.cs**: Handles `/claim` command for claiming blood or rewards.
- **CopyPaste.cs**: Enables admins to copy and paste structures.
- **CupboardLimiters.cs**: Limits the number of TCs a player can place.
- **CustomVendingSetup.cs**: Customizes vending machines for in-game services.
- **DefaultRadioStation.cs**: Sets up default radio stations for players.
- **DepositBox.cs**: Manages hash deposits for rewards.
- **DiscordAuth.cs**: Connects in-game profiles with Discord.
- **DiscordStatus.cs**: Shows server status in Discord.
- **DynamicPVP.cs**: Handles our dynamicPVP zones at monuments
- **ImageLibrary.cs**: Renders custom user interfaces for plugins.
- **InventoryViewer.cs**: Allows admins to manage player inventories.
- **ItemCountTracker.cs**: Tracks in-game paper across the server.
- **MarketplaceUi.cs**: Adds a UI for in-game marketplaces.
- **MonumentAddons.cs**: Adds features to standard monuments.
- **MonumentFinder.cs**: Helps players locate monuments.
- **NoGiveNotices.cs**: Suppresses notifications when items are given.
- **NpcSpawn.cs**: Manages NPC spawns at monuments.
- **Orangemart.cs**: Handles Bitcoin payment integration
- **PermissionsManager.cs**: Allows easy management of player permissions.
- **PlayerAdministration.cs**: Manages player accounts, bans, and tasks.
- **RadioStationManager.cs**: Manages in-game radio stations.
- **RaidableBases.cs**: Adds bases that can be raided.
- **RemoverTool.cs**: Allows players or admins to remove structures.
- **Rustcord.cs**: Integrates Discord with the server for interaction.
- **ServerInfo.cs**: Displays essential server information.
- **ServerPop.cs**: Tracks server population in real-time.
- **SignArtist.cs**: Lets players upload custom images to signs.
- **SkinBox.cs**: Provides access to item skins.
- **Sputnik.cs**: Adds satellite-like objects to the game.
- **TruePVE.cs**: Enables PvE environment on server.
- **UpdateChecker.cs**: Checks for plugin updates automatically.
- **Vanish.cs**: Allows admins to become invisible to players.
- **VendingMachineLogs.cs**: Logs vending machine transactions.
- **ZoneManager.cs**: Manages safe and PvP zones on the map.
