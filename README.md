# Game Compatibility
This repo will contain a list of games that have been verified to work with FModel and CUE4Parse, provided the right settings.

# Have a game that has known issues?
Make an [issue](https://github.com/FModel/Game-Compatibility/issues/new/choose), and let us know!

### Compatible and verified working (at the time of addition)
| Game | Project Name | Version | Mappings File |
| --- | --- | --- | --- |
| [Kid A Mnesia: Exhibition](https://store.epicgames.com/en-US/p/kid-a-mnesia-exhibition) | Paperbag | GAME_UE4_26 |
| [Fortnite](https://store.epicgames.com/en-US/p/fortnite) | FortniteGame | GAME_UE5_1 |
| [Valorant](https://store.epicgames.com/en-US/p/valorant) | ShooterGame | GAME_Valorant |
| [Spellbreak](https://store.epicgames.com/en-US/p/spellbreak) | g3 | GAME_UE4_22 |
| [Minecraft Dungeons](https://store.steampowered.com/app/1672970/Minecraft_Dungeons/) | Dungeons | GAME_UE4_22 |
| [Borderlands 3](https://store.epicgames.com/en-US/p/borderlands-3) | OakGame | GAME_Borderlands3 |
| [Splitgate](https://store.steampowered.com/app/677620/Splitgate/) | PortalWars | GAME_Splitgate |
| [PUBG: BATTLEGROUNDS](https://store.steampowered.com/app/578080/PUBG_BATTLEGROUNDS/) | TslGame | GAME_PlayerUnknownsBattlegrounds |
| [Dead by Daylight](https://store.epicgames.com/en-US/p/dead-by-daylight) | DeadByDaylight | GAME_UE4_27 |
| [Tower of Fantasy](https://store.steampowered.com/app/2064650/Tower_of_Fantasy/) | Hotta | GAME_TowerOfFantasy |
| [State of Decay 2](https://store.steampowered.com/app/495420/State_of_Decay_2_Juggernaut_Edition/) | StateOfDecay2 | GAME_StateOfDecay2 |
| [Ready or Not](https://store.steampowered.com/app/1144200/Ready_or_Not/) | ReadyOrNot | GAME_ReadyOrNot |
| [Kingdom Hearts 3](https://store.epicgames.com/en-US/p/kingdom-hearts-iii) | TresGame | GAME_KingdomHearts3 |
| [eFootball 2023](http://store.steampowered.com/app/1665460/eFootball_2023/) | PesConsole | GAME_UE4_26 |
| [Hello Neighbor](https://store.steampowered.com/app/521890/Hello_Neighbor/) | HelloNeighbor | GAME_UE4_20 |
| [Hello Neighbor 2](https://store.steampowered.com/app/1321680/Hello_Neighbor_2/) | HelloNeighbor2 | GAME_UE4_27 |
| [Petals](https://petalsgame.itch.io/petals) | Petals | GAME_UE5_0 | [Mapping](https://github.com/OutTheShade/Unreal-Mappings-Archive/raw/main/Petals/Mappings.usmap) |
| [Rumbleverse](https://store.epicgames.com/en-US/p/rumbleverse) | Rumbleverse | GAME_ReadyOrNot |
| [Dauntless](https://store.epicgames.com/en-US/p/dauntless) | Archon | GAME_Dauntless |
| [Paragon: The Overprime](https://store.epicgames.com/en-US/p/paragon-the-overprime-0bca60) | Overprime | GAME_UE4_27 |
| [Tetris Effect](https://store.steampowered.com/app/1003590/Tetris_Effect_Connected/) | TetrisEffect | GAME_UE4_26 |
| [Core](https://store.epicgames.com/en-US/p/core) | Platform | GAME_UE4_26 |
| [Rogue Company](https://store.epicgames.com/en-US/p/rogue-company) | RogueCompany | GAME_RogueCompany |
| [Battle Breakers](https://store.epicgames.com/en-US/p/battle-breakers) | WorldExplorers | GAME_UE4_24 |
| [The Cycle](https://store.epicgames.com/en-US/p/thecycle) | Prospect | GAME_UE4_27 |
| [Kitty May Cry](https://store.steampowered.com/app/2123100/Kitty_May_Cry/) | KittyMayCry | GAME_UE5_0 |
| [BIGFOOT](https://store.steampowered.com/app/509980/BIGFOOT/) | Bigfoot | GAME_UE4_26 |
| [Little Nightmares](https://store.steampowered.com/app/424840/Little_Nightmares/) | Atlas | GAME_UE4_13 |
| [Little Nightmares II](https://store.steampowered.com/app/860510/Little_Nightmares_II/) | Helios | GAME_UE4_24 |
| [Deathly Stillness](https://store.steampowered.com/app/1727650/Deathly_Stillness/) | DeathlyStillnessGame | GAME_UE4_26 |
| [The Anacrusis](https://store.steampowered.com/app/1120480/The_Anacrusis/) | Anacrusis | GAME_UE4_27 |

### Not completely supported / Have issues
| Game | Project Name | Version | Issue |
| --- | --- | --- | --- |
| [HYENAS](https://store.steampowered.com/app/1989910/HYENAS/) | keaton | GAME_UE4_27 | Every asset causes a CLR crash |
| [Divine Knockout](https://store.steampowered.com/app/1294660/Divine_Knockout_DKO/) | DivineKnockout | GAME_UE4_27 | Meshes don't load |
| [Apex Legends Mobile](https://play.google.com/store/apps/details?id=com.ea.gp.apexlegendsmobilefps) | AClient | GAME_ApexLegendsMobile | Meshes don't load |
| [QQ](https://play.google.com/store/apps/details?id=com.tencent.mobileqq) | UE4 | GAME_UE4_26 | FPakInfo modification |
| [Video Horror Society](https://store.epicgames.com/en-US/p/vhs) | Game | GAME_ReadyOrNot | Alternate pak GUIDs with keys |
| [Deliver Us The Moon](https://store.steampowered.com/app/428660/Deliver_Us_The_Moon/) | MoonMan | GAME_UE4_26 | Asset Registry invalid FString length |
| [Scavengers](https://store.steampowered.com/app/1183940/Scavengers/) | Scavenger | GAME_UE4_26 | Blueprints and Asset Registry errors & Meshes don't load |
| [Unreal Tournament](https://store.epicgames.com/en-US/p/unreal-tournament) | UnrealTournament | GAME_UE4_15 | Highly modified engine |
