# anOrangeDoggo's SAIN Presets

Just want to share the repo of my presets along with the commit history in the off chance it might help people make their own. I might make a wiki or something, idk. SoonTM. Maybe never.

If you have questions, try look through the commit history. Or, search through the Discord conversations. Many topics related to the core gameplay aspects are mostly already answered.

I also want to give a shout-out to Solarint, the maker of SAIN, and all the maintainers and contributors for the amazing mod, and the SPT devs for years of SPT support.

## How Are These Compared to XYZ

My presets are all Default SAIN through and through, so you should be expecting standard SAIN experience in the bot behavior department.

The only things I made significant changes to are related to aiming, shooting, and hearing stuff. And a bit on the vision speed and some other stuff I probably forget. Again, it's all in the commit history.

Many areas are standardized to Default, with mostly aiming and shooting varied for Hard and Challenging. Challenging is more difficult than Hard (I nO EnGlIsH SpOkE) as it offers substantially tighter shot grouping and faster aim time. Hard is essentially Default with basic knobs turned a bit more.

Overall, I don't really know. I haven't played any other presets for weeks if not months now on top of jumping in and out of other games. All I can say is that they all should be easier than Twitch Players in the sense that they don't give bots eagle eyes and extreme reaction time, and harder than SAIN's Default because bots shoot more accurately. That leaves only one way to find out.

Or, check out my gameplay of Challenging 0.2.1 (YMMV, obviously):

[![Preset Gameplay](https://img.youtube.com/vi/LN3b77atI2c/0.jpg)](https://youtu.be/LN3b77atI2c)

Note that bots walking around with their guns down aren't part of my presets or SAIN. It's an in-development mod by the creator of [HollywoodFX](https://forge.sp-tarkov.com/mod/2003/hollywoodfx) and [HollywoodCam](https://forge.sp-tarkov.com/mod/2201/hollywoodcam). I highly recommend these mods.

Here's a gameplay with just SAIN, Acid's bot mods, and other QoL, item, etc mods of my choice. I think this setup should be pretty close to what average SPT enjoyers have.

[![Preset Gameplay Standard Setup](https://img.youtube.com/vi/6WG1O9xDt0I/0.jpg)](https://youtu.be/6WG1O9xDt0I)

## Before You Install

**DO NOT** report any bug or strange behaviour to SAIN's maintainers during the use of my presets.

*DO NOT* view my presets in the in-game GUI. Simply select one without expanding/droping down anything. Some of the values are outside of the acceptable ranges and, upon revealing through the GUI, will be clamped to what are actually allowed. Although, unless you hit Save or Export All, it should not be affecting the presets. SAIN will work just fine even if some of the values are a bit odd.

Nothing less of another mod will save you from head-eyes if that's your kryptonite. I personally increase the head's health to 85 via Server Value Modifier, so I can survive small to intermediate, high pen rounds. But anything bigger than that I'm cooked.

If you find any issues, like bots not moving, are blind and/or deaf, etc, chances are you already have that before you even download the presets. Make sure everything is up-to-date and your standard SAIN is already working normally. [Ombarella](https://forge.sp-tarkov.com/mod/2315/ombarella) is known to make bots go blind if not being configured correctly. I personally don't use it.

## Installation

If you download directly from the Forge, you should get the latest version of each preset all bundled in one zip and properly structured. You can extract the zip directly into your SPT folder.

If you're on the GitHub page, on the right side, under Releases, click Tags. Then download any version `0.2.0` or newer of the source code of your choosing preset. Then extract `anOrangeDoggo - <difficulty>` to your SAIN's preset folder.

The path should look like this: `<SPT>\BepInEx\plugins\SAIN\Presets\<Preset Folder>`. For example, `SPT 4.0\BepInEx\plugins\SAIN\Presets\anOrangeDoggo - Hard`.

Since I have many presets available at once, each will have its own versioning to track the development, which is also independent of the others. The versioning of the bundle on the Forge will be incremented only when I decide to include any new version of a preset and thus does not represent the actual versioning.

## How Are My Presets Tested

I'm an average Tarkov player. I play with Recoil Rework and mostly shoot in semi. All Acid's mods are mostly default except for spawns which are set to _spawn everything at Normal difficulty_. For how Difficulty and SAIN preset work, see [this](https://cdn.discordapp.com/attachments/1121357894068224031/1270106508230787122/SAIN_Scale.png?ex=6952329d&is=6950e11d&hm=3ce1a300310afaa13beb710d60fd943c0022a31858e2dd10be719b6b6ed5297c&)

99% of the tests are done with Scavs and PMCs with minimal tests against bosses and next to none against Rogues, Cultists, other ninche factions, during daytime.

The settings are pre-adjusted before starting EFT with almost no further adjustments in-game.

All mods are loaded via Mod Organizer 2 just like my 3.11 setup. Here is my mod list:

```
AgonySFX-1.1.5
AmmoClarity-1.0.0
Armory-WTT-2.0.0
AutoDeposit-5.0.0
BalancedOverhaulOfBulletSpawns-3.2.0
BetterAmmoLoadingList-1.1.0
BigBrain-1.4.0
BlackDivision-WTT-1.0.0
BossesHaveLegaMedals-2.0.0
BotDebug-1.7.0
BotPlacementSystem-Acid-2.0.9
CaliberSplitAmmoCases-2.0.0
CaliberSplitMagazineCases-2.0.0
CantedAiming-1.0.7
ColorConverterAPI-1.1.1
CommonLib-WTT-2.0.8
ContentBackport-WTT-1.0.0
ContinuousLoadAmmo-1.1.2
CustomInteractions-1.8.0
DynamicExternalResolutionPatch-1.1.0
DynamicMaps-1.0.4
EOTechFix-1.0.1
EquipFromWeaponRack-1.5.0
ExpandedTaskText-2.0.2
FleaAdjustment-2.0.0
Foldables-1.0.1
FOVFix-4.0.1
Freecam-1.4.7
GildedKeyStorage-2.0.4
HandsAreNotBusy-1.6.0
HeadVoiceSelector-1.0.6
HealingAutoCancel-5.0.0
HideoutInProgress-2.0.1
HollywoodFx-1.8.3
IncreaseClimbHeight-2.0.0
ItemAttributeFix-1.7.0
ItemContextMenuExt-1.8.0
ItemPreviewQoL-4.0.3
LacyPvETweaks-1.1.0
LetMeOut-1.0.2
MagazineInspector-1.7.0
MergeConsumables-1.5.3
ModdingStatsHelper-1.1.1
MoreBotsAPI-1.1.0
MoreTagColours-1.4.0
MunitionsExpert-1.7.0
NerfBotGrenades-1.2.0
Phobos-0.0.1
PlayerEncumbranceBar-1.2.2
PreviewSizer-1.0.2
ProgressiveBotSystem-Acid-2.0.11
QuestTracker-1.6.0
QuickMoveToContainer-1.4.0
RecoilRework-1.10.0
RefSPTFriendlyQuests-2.0.1
RepairMaxDurability-2.0.1
SAIN-Build.Local
SearchOpenContainers-1.4.0
ServerValueModifier-2.0.2-hotfix.1
ShadowFlickerFix-1.5.2
ShowMeTheMoney-2.5.3
ShowMeTheMoney.QuickSell-2.2.2
SimpleWorkoutQte-2.0.0
StartCollectorEarly-1.4.0
StatTrack-2.0.0
TaskListFixes-1.7.1
TraderModding-2.1.0
TraderScrolling-4.0.0
UIFixes-5.1.1
UnderFireAdrenalineEffect-2.0.1
UseLooseLoot-1.5.1
Waypoints-1.8.1
WeaponCustomizer-3.0.2
WikiLinks-1.0.0
WishlistExtended-1.0.0
```

## Porting Back to SPT 3.11

To my knowledge, presets for latest SAIN can be ported back to SPT 3.11. While some of the settings are added to the newer version, most of the identical parameters should work exactly the same.

If you wish to port any preset made for newer version of SAIN back, make sure you only take the values of the settings which exist in both versions and leave the rest out. I don't recommend outright overwriting the files. Manually review through each and make the change by hand so you know what you touch.
