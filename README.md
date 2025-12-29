# anOrangeDoggo's SAIN Presets

Just another SAIN preset. Nothing groundbreaking here.

See the commits for the changes made to the preset. I've also added further thoughts into each commit so make sure you check it out. This is not exactly a wiki, but it should, more or less, be of help in making your own preset.

Also, check out other presets' repos and their commits. Don't take mine as a done and all source.

I try to keep most of the changes on the default branch for easier development and reading. Feel free to check out other branches if you want to see how I adjust things for that particular ones.

## Before You Use My Preset

**DO NOT** report any bug or strange behaviour to SAIN's maintainers during the use of my presets. Confirm your finding by switching back to SAIN's built-in Default preset and try to reproduce the bug. Also, make sure to take screenshots if not videos with BotDebug enabled.

_DO NOT_ view my presets in the in-game GUI. Some of the values are outside of the acceptable ranges and, upon revealing through GUI, will be clamped to what are allowed. Although, unless you hit Save or Export All, it should not be affecting the presets. SAIN will work just fine even if some of the values are a bit odd.

_Nothing less of another mod_ will save you from head-eyes. Almost no preset if none at all will save you from the inevitable. Enabling Aim Center Mass in global settings with the trade off of constant blacked stomach can only lessen the chance. Bot's recoil and BSG's janks are simply unpredictable.

## Installation

On the right side, under Releases, click Tags. Then download any version `0.2.0` or newer source code. Then extract `anOrangeDoggo - <difficulty>` to SAIN preset folder.

The path should look like this: `<SPT>\BepInEx\plugins\SAIN\Presets\<Preset Folder>`. For example, `SPT 4.0\BepInEx\plugins\SAIN\Presets\anOrangeDoggo - Hard`.

For now, there are 2 presets I'm working on:

- Default has relatively shallow modifications and should overall behave similarly to SAIN's default, but with tightened shot groupings so bots can stand a bit of chance of fighting. This preset also serves as my base preset for any other variations.
- Hard is derived from Default and is planned to have a bit deeper modifications. But for now, I don't have an idea on how it should be just yet, other than significantly tighter shot groupings than Default. This is the preset I regularly play on.

You can have all the presets existing together at any time since they're contained within their respective folder.

The versioning numbers are respective to their variations of the presets and shoul not be cross compared. For example, `hard-0.2.5` should not be considered "newer" or "better" than `default-0.2.2` as it is being worked and iterated on in a different pipeline, even though it might be based on that particular version of Default.
## How Are My Presets Tested

I'm an average Tarkov player. I play with Recoil Rework and mostly shoot in semi. All Acid's mods are mostly default except for spawns which are set to _spawn everything at Normal difficulty_. For how Difficulty and SAIN preset work, see [this](https://cdn.discordapp.com/attachments/1121357894068224031/1270106508230787122/SAIN_Scale.png?ex=6952329d&is=6950e11d&hm=3ce1a300310afaa13beb710d60fd943c0022a31858e2dd10be719b6b6ed5297c&)

99% of the tests are done with Scavs and PMCs with minimal tests against bosses and next to none against Rogues, Cultists, other ninche factions, during daytime.

The settings are pre-adjusted before starting EFT with almost no further adjustments in-game.

All mods are loaded via Mod Organizer 2 just like my 3.11 setup. Here is my mod list:

```
#Mod_Name
"AgonySFX-1.1.5"
"AmmoClarity-1.0.0"
"Armory-WTT-2.0.0"
"AutoDeposit-5.0.0"
"BalancedOverhaulOfBulletSpawns-3.2.0"
"BetterAmmoLoadingList-1.1.0"
"BigBrain-1.4.0"
"BlackDivision-WTT-1.0.0"
"BossesHaveLegaMedals-2.0.0"
"BotDebug-1.7.0"
"BotPlacementSystem-Acid-2.0.9"
"CaliberSplitAmmoCases-2.0.0"
"CaliberSplitMagazineCases-2.0.0"
"CantedAiming-1.0.7"
"ColorConverterAPI-1.1.1"
"CommonLib-WTT-2.0.8"
"ContentBackport-WTT-1.0.0"
"ContinuousLoadAmmo-1.1.2"
"CustomInteractions-1.8.0"
"DynamicExternalResolutionPatch-1.1.0"
"DynamicMaps-1.0.4"
"EOTechFix-1.0.1"
"EquipFromWeaponRack-1.5.0"
"ExpandedTaskText-2.0.2"
"FleaAdjustment-2.0.0"
"Foldables-1.0.1"
"FOVFix-4.0.1"
"Freecam-1.4.7"
"GildedKeyStorage-2.0.4"
"HandsAreNotBusy-1.6.0"
"HeadVoiceSelector-1.0.6"
"HealingAutoCancel-5.0.0"
"HideoutInProgress-2.0.1"
"HollywoodFx-1.8.3"
"IncreaseClimbHeight-2.0.0"
"ItemAttributeFix-1.7.0"
"ItemContextMenuExt-1.8.0"
"ItemPreviewQoL-4.0.3"
"LacyPvETweaks-1.1.0"
"LetMeOut-1.0.2"
"MagazineInspector-1.7.0"
"MergeConsumables-1.5.3"
"ModdingStatsHelper-1.1.1"
"MoreBotsAPI-1.1.0"
"MoreTagColours-1.4.0"
"MunitionsExpert-1.7.0"
"NerfBotGrenades-1.2.0"
"Phobos-0.0.1"
"PlayerEncumbranceBar-1.2.2"
"PreviewSizer-1.0.2"
"ProgressiveBotSystem-Acid-2.0.11"
"QuestTracker-1.6.0"
"QuickMoveToContainer-1.4.0"
"RecoilRework-1.10.0"
"RefSPTFriendlyQuests-2.0.1"
"RepairMaxDurability-2.0.1"
"SAIN-Build.Local"
"SearchOpenContainers-1.4.0"
"ServerValueModifier-2.0.2-hotfix.1"
"ShadowFlickerFix-1.5.2"
"ShowMeTheMoney-2.5.3"
"ShowMeTheMoney.QuickSell-2.2.2"
"SimpleWorkoutQte-2.0.0"
"StartCollectorEarly-1.4.0"
"StatTrack-2.0.0"
"TaskListFixes-1.7.1"
"TraderModding-2.1.0"
"TraderScrolling-4.0.0"
"UIFixes-5.1.1"
"UnderFireAdrenalineEffect-2.0.1"
"UseLooseLoot-1.5.1"
"Waypoints-1.8.1"
"WeaponCustomizer-3.0.2"
"WikiLinks-1.0.0"
"WishlistExtended-1.0.0"
```

## Porting Back to SPT 3.11

To my knowledge, presets for latest SAIN can be ported back to SPT 3.11. While some of the settings are added to the newer version, most of the identical parameters should work exactly the same.

If you wish to port any preset made for newer verion of SAIN back, make sure you only take the values of the settings which exist in both versions and leave the rest out. I don't recommend outright overwriting the files. Manually review through each and make the change by hand so you know what you touch.
