![https://i.imgur.com/CkSehPu.png](https://i.imgur.com/CkSehPu.png)
![https://i.imgur.com/dBf99Od.png](https://i.imgur.com/dBf99Od.png)

Like my mods? Support me:
Paypal: war3spells@gmail.com 
## MOD ONLY WORKS IF YOU USE IT ON DEDICATED SERVER. DON'T TRY TO USE IT IN SINGLEPLAYER / CLIENT HOST
## Mod adds different NPCs and Unique mechanics to server so admins can configure them from serverside with no need to restart server for applying settings:

<details>
  <summary><b><span style="color:aqua;font-weight:200;font-size:20px">
    Patchnotes
</span></b></summary>

| Version     | Changes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|-------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 7.7.1       | 1) Now skill level as quest REWARD will not give skill levels if skill level is 0 (professions)<br/>2) Now all configs (including discord config, territory config and MAIN config (that also got changed) ) updating in server runtime without restart<br/>3) Changed discord connector config so you can write your own messages using {0] {1} {2} string formatting<br/>4) Fixed some patrol errors<br/>5) NPC that visible on map will be displayed as quest complete icon if its Talk quest target<br/>6) Fixed bug where every player would be an owner of any admin zone<br/>New territory flags<br/>7) NPC's now can move if you set their patrol data (example: X0, Y0, X1, Y1, X2, Y2 and so on)<br/>8) Added new NPC name <icon> tag that allows you to add icon to NPC (exampe: <icon>Hammer</icon>), icon may be in-game monster, item or teleporter icon<br/>9) Added caching of teleporter icons<br/>10) Added /zones command to show zones in world<br/>11) Added F8 client GUI to create/remove/edit zones<br/>12) Added new NPC that's visible on map<br/>13) Added caching of quest descriptions<br/>14) Quests now may have multiple restrictions |
| 7.7.2-7.7.6 | 1) Small bugfixes<br/>2) Fixed npc patrol dropping underground because of no collision check<br/>3) Added isModed = true flag for valheim<br/>4) New territory flags were added: CustomPaint, LimitZoneHeight                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | 
| 7.7.7       | 1) Max accepted quest count now controlled by option in serverside<br/>2) Updated accepted quests UI. Added scrollview so you can see a lot of quests now. Also accepted quests UI now expandable in height if you drag its bottom border<br/>3) Fixed visible on map npc icon giving error<br/>4) Fixed patrol npc skyrocket in sky                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| 7.7.8       | 1) Fixed Jewelcrafting incompatibility<br/>2) Added new API methods for my server control bot                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| 7.7.9-7.8.2 | 1) Added new mechanic: Battlepass. (Still it test so no guides atm)<br/>2) Fixed marketplace default NPC models being able to go through (model collider issues)<br/>3) Added marketplace comptibility with ANY EIDF (Extended Item Data Framework) mod, such as my Transmogrification, Jewelcrafting, EpicLoot and so on<br/>4) Items in marketplace now have tooltip in right side with item stats and additional mod effects<br/>5) Added new quest Requirement: HasItem. Example: HasItem: Coins, 500<br/>6) Added new territory flags: LimitZoneHeight, CustomPaint<br/>7) Some additional optimizations<br/>8) Quest system improvements in terms of serverside crashes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| 7.8.3       | 1) Changed marketplace fonts and optimized UI<br/>2) Battlepass fixes<br/>3) Webhooks now having <color> richtext removed                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| 7.8.4       | 1) Added german + portugese languages support<br/>2) HOTFIX for bug that doesn't allow mod to work                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| 7.8.5       | 1) Fixed cooking skill bug<br/>2) Fixed marketplace UI sorting by itemname/price/amount/seller text disappear on click                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| 7.8.6       | 1) Added Korean language support<br/>2) Fixed possible EIDF item dupe                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| 7.8.7       | 1) Now collect and craft quests may also have target level<br/>2) Fixed JC api<br/>3) Added new trader UI buttons: x1, x5, x10, x100                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| 7.8.8       | Fixed Previous Version                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| 7.8.9       | Fixed kill quest sometimes giving double reward                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| 7.9.0       | Fixed problem where item with 5 sockets were shown as 4 sockets max                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| 7.9.1-7.9.2 | 1) Bugfixes<br/>Increase max marketplace pric to 10 mil                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| 7.9.3       | Fixed new Jewelcrafting mod version problem with marketplace display                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
</details>





_________________________________
![https://i.imgur.com/iWZO1dp.png](https://i.imgur.com/iWZO1dp.png)

<details><summary>Installation and main configs:</summary>
<p> 

1) Ship plugin to all clients and on your dedicated server
2) After server restart, new folder in BepInEx/config will be created: MarketplaceKG

![](https://i.imgur.com/T4pu03j.png)

Each file / folder description:
1) Battlepass folder - contains battlepass configs for Free / Premium rewards and main battlepass config (battlepass name, exp step)
2) Discord Webhook folder - allows you to configure webhooks for Marketplace notifications (Quest completed, Marketplace item placed, Gambler won)
3) DO NOT TOUCH - this folder only contains encrypted marketplace related data (players messages, players income, marketplace slots and so on). DO NOT TOUCH this folder since you will lose all your marketplace data if you do so. There are none files you can / need to edit
4) MapPinsIcons - folder where you can place small-weight icons for Teleporter NPC. But there is also MarketplaceCachedTeleporterIcons folder in clientside which i recommend you to use, instead of adding icons on serverside
5) PlayerTerritories - folder with json files and .cfg for Player-made territories (Admin territories are inside TerritoryDatabase.cfg)
6) BankerProfiles.cfg - file for configuring banker NPC's
7) BufferDATABASE.cfg - file that contains all your created buffs for Buffer NPC
8) BufferProfiles.cfg - file for configuring Buffer NPC (you can choose which NPC profile has WHICH buffs from database)
9) GamblerProfiles.cfg - file for configuring Gambler NPC
10) LOGS.log - few logs for some marketplace actions (item deposit / withdraw to banker, marketplace item placed, etc)
11) MarketPlace.cfg - main config that contains small config values for various mechanics
12) QuestDATABASE.cfg - file where you have all your written quests
13) QuestProfiles.cfg - file for configuring Quest NPC (you can choose which NPC profile has WHICH quests from database)
14) ServerInfoProfiles.cfg - file for configuring ServerInfo NPC
15) TeleportHubProfiles.cfg - file for configuring Teleporter NPC
16) TerritoryDatabase.cfg - file for configuring territories
17) TraderProfiles.cfg - file for configuring Trader NPC

</p>
</details>

<details><summary>How to spawn/change NPC:</summary>
<p> 

1) Start the game and join your server
2) Use any admin mod to enable DEBUG MODE
3) After enabling debug mode you can open your hammer and "build" NPC you want

There are two types of NPC's: Visible on map and Not Visible on map.

![](https://i.imgur.com/i4hwElW.png)

![](https://i.imgur.com/7A8rr8u.png)

![](https://i.imgur.com/IMQ7hpV.png)

The difference is only that visible on map NPC will have its Pin on map from any distance.

![](https://i.imgur.com/zlm4GR6.png)


After placing NPC in Debug Mode you can start applying few changes to it. You can open 2 menus: Main NPC UI and Fashion Menu.

![](https://i.imgur.com/K6zbBEQ.png)

Main NPC UI:

![](https://i.imgur.com/eSOXkyZ.png)

1) Top buttons - change NPC type (Marketplace, Trader, Info, Teleporter and so on)
2) Change NPC Profile - NPC profile that will hook data from your *NpcType*Profiles.cfg 
3) Override NPC Name - Change NPC name to whatever you want
4) Override NPC Model - Change NPC model to any in-game (even other mod) creature you want
5) Set Patrol Data - You can make npc walk from one spot to another, or even make a full path for it. Example: 300, 200, 305, 200. It will make your NPC walk from 300 x spot to x 305 spot (5 meters), while Z coord is always 200
6) Snap To Ground And Rotate - snaps NPC to ground and rotates it to where you look at
7) Apply - apply changes

P.S: Override NPC Model accepts ANY Character (monster) prefab (Troll, Greydwarf, Hatchling, and so on). But monsters will have their own animator.
If you want to use Overriden NPC with Player animation from fashion menu you can add @humanoid to your prefab name.
Example:
Troll@humanoid, Greydwarf@humanoid, Neck@humanoid.
That will give these creature Player animator so they will be able to use emote_wave animations and so on (crafting animations also)

Let's try it out:

Adding data:

![](https://i.imgur.com/u5L80rk.png)

Result:

![](https://i.imgur.com/kxIKSm6.png)


Now let's see Fasion Menu:
(Keep in mind that most fashion prefabs / equipment will only work on Player or Player_Female models override. Armors and such won't work on monster override models)

![](https://i.imgur.com/rqGj581.png)

1) Left Hand - left hand prefab
2) Right Hand - right hand prefab
3) Helmet Item - helmet prefab
4) Chest Item - chest prefab
5) Legs Item - legs prefab
6) Cape Item
7) Left Back Item - left back prefab
8) Right Back Item - right back prefab
9) Hair Index - hair index (1 2 3 4 5 and so on) 
10) Hair Color (#hex) - hex color for hair color, example: #ffffff
11) Skin Color (#hex) - hex color for skin color, example: #ffffff
12) Model scale - model size (works on any override model)
13) Interact animation - animation when someone interacts with NPC, example: emote_nonono
14) Greeting animation - animation when someone comes close to NPC, example: emote_thumbsup
15) Bye Animation - animation when someone leaves NPC, example: emote_wave
16) Greeting Text - text when someone comes close to NPC, example: Hello!
17) Bye Text - text when someone leaves NPC, example: Bye!
18) Crafting animation index - animation for Player and Player_Female models that turning on crafting state, there are 0 1 2 3 crafting animation states
19) Beard index - same as hair index, but for beard
20) Beard color (#hex) - hex color for beard color, example: #ffffff

Now let's write some random data:

![](https://i.imgur.com/xK0Kywc.png)

Result:

![](https://i.imgur.com/ULo443R.png)

![](https://i.imgur.com/lFzK72V.png)

Now that we learned how to spawn / edit NPC's lets try to configure some of those from serverside



</p>
</details>

<details><summary>MarketPlace.cfg (misc configs):</summary>
<p> 

![](https://i.imgur.com/48FkIqM.png)

1) ItemMarketLimit - limit of slots a player can post in Marketplace
2) BlockedPlayers - SteamID list of players that can't post items in Marketplace
3) VIPplayersList - SteamID list of players that are VIPs (less taxes)
4) MarketTaxes - taxes for Marketplace items (non-VIP users)
5) VIPplayerTaxes - taxes for Marketplace items (VIP users)
6) CanTeleportWithOre - define if players can teleport with ore in Teleporter NPC
7) MarketSellBlockedPrefabs - prefabs that players cannot sell on marketplace
8) FeedbackWebhookLink - Feedback NPC webhook link
9) ServerCurrency - currency to use in Marketplace. If you have your own prefab - analogue of Coins you can write it here
10) BankerIncomeTime - how often (HOURS) banker will give players income
11) BankerIncomeMultiplier - each #BankerIncomeTime (hours) will add income with multiplier. Example: if player has 100 coins in bank and multiplier is 0.1, then each BankerIncomeTime he will have 100 + 100 * 0.1 (110). Then 110 + 110 * 0.1 = 221. And so on
12) BankerVIPIncomeMultiplier - same as upper, but for VIP players
13) MarketSlotExpirationTime - how many hours should pass, so that player marketplace slot will expire (won't be shown in marketplace list anymore)
14) GamblerEnableWinNotifications - enable global chat win notifications when someone wins something in gambler NPC
15) AllowMultipleQuestsScore - if set to true, then if player has 2 quests with same target, upon adding quest score it will be added to BOTH quests instead of just one
16) MaxAcceptedQuests - maximum number of quests that player can have accepted at once
17) BattlepassVIPlist - SteamID list of players that are VIPs in Battlepass
</p>
</details>

<details><summary>Trader</summary>
<p> 
Trader NPC allows you to set items to be exchanged. Item A x number will be exchanged for Item B x number.

To start with let's make our trader profile in TraderProfiles.cfg:

![](https://i.imgur.com/cYxd3gH.png)

The data format is:

ItemA, ItemA quantity, ItemB, ItemB quantity, ItemB level (If needed)

For example i want to make a trader that will trader 100 coins for 1 swordiron level 2, and trade 1 wood for 10 Rubies:

My profile will look like that:

```
[TestTrader]
Coins, 100, SwordIron, 1, 2
Wood, 1, Ruby, 10
```

Adding that to TraderProfiles.cfg

![](https://i.imgur.com/PSpqNPL.png)

(As in any other NPC you are able to add as many profiles as you want so you can have 100 different NPCs trading different items)

Now let's assign profile to our trader NPC:

![](https://i.imgur.com/BjPrHIS.png)

On interact trader UI will open:

![](https://i.imgur.com/WMFaYl4.png)

Because i have wood and coins in my inventory i can actually exchange that. On clicking big green > (arrow) button in middle i will exchange item A on item B.

Also you can add Pets as trader items. Example: Stone, 100, Wolf, 1, 5. Will exchange 100 stone on one pet wolf level 5

Let's add another profile with pets only!

```
[PetsTrader]
Stone, 100, Wolf, 1, 5
Ruby, 25, Boar, 10, 2
```

![](https://i.imgur.com/10OELul.png)

Assigning PetsTrader profile to our NPC will give us this result:

![](https://i.imgur.com/W4YHMKr.png)

Note that wolf level 5 is 4 stars because stars starts from 0 and level starts from 1. Same for Boar

On top right you have x1, x5, x10 , x100 modifier buttons so player can change exchange rate for faster trading. Note that it applies original rate so Coins, 5, Wood, 1 on exchange rate x100 will be 500 coins to 100 wood


</p>
</details>

<details><summary>Quest System</summary>
<p> 

In order to create your own Quests you would need to focus on two file: QuestDATABASE.cfg and QuestProfiles.cfg

![](https://i.imgur.com/4l2Kshv.png)

QuestDATABASE.cfg - a file that contains ALL your created quests. Think about it as a place where all your quests getting their ID there, so later you can add that ID to QuestProfiles NPC

QuestProfiles.cfg - a file that allows you to distribute quests into NPC profiles. You may have 5 NPCs giving SAME quest, as well as 10 NPCs giving different quests

So... Let's create our own first quest! First think you should do is to create a new Quest in QuestDATABASE.cfg.

Here's the quest structure:
```
[QuestID]
QuestType
Name
Description
Quest Target Prefab , Amount, Min Level (min level works only on Kill quest in order to set minimum level or target you need to kill)
QuestRewardType: Item/Skill/Pet: prefab, Amount, Level
In-Game Days Cooldown
QuestRequirementType: Skill/OtherQuest/GlobalKey: Name, MinLevel (only use with Skill requirement)
```

There are 6 types of quests: Kill, Collect, Harvest, Craft, Talk and Build:
```
1) Kill - a quest where the Target is a Character (any creature) prefab. You can set minimum level of target creature to kill
2) Collect - a quest where the Target is an Item prefab. Please note that COLLECT is the only quest type that actually TAKES item from player inventory in order to be finished
3) Harvest - a quest where the Target is a Pickable prefab. Example: Pickable_Carrot, Pickable_Stone and so on. For adding score to this quest you would need to Harvest any of those "farm" prefabs
4) Craft - a quest where the Target is a Item prefab. You can set an item level that should be crafted or leave it 1
5) Talk - a quest where the Target is a full NPC name. After interacting with NPC target quest will autocomplete and rewards will be given
6) Build - a quest where the Target is a Piece prefab. Please note that prefabs that you build for quest target won't return any resources on destroy
```
Quest rewards type:
```
1) Item - a reward where the Target is an ItemDrop prefab. You can set amount and level of given item
2) Skill - a reward where the Target is Skill name. Example Skill: Run, 10. Will give +10 levels of run skill to player who finished a quest
3) Pet - a reward where the Target is a Tameable Creature prefab that will spawn already tamed. You can set amount and level of given pet
```

Quest Requirements Types:
```
1) Skill - example: Skill: Run, 10. Will make so that only if you have skill Run at least 10 levels you can accept this quest
2) OtherQuest - example: OtherQuest: MyQuestID123. Will make so that only if you have completed quest with ID MyQuestID123 you can accept this quest
3) GlobalKey - example: GlobalKey: defeated_gdking. Will make so that quest is only acceptable if yagluth was killed on server
4) EpicMMO_Level - example: EpicMMO_Level: 20. Will make so that quest is only acceptable if player has at least 20 EpicMMO levels (other mod API)
5) HasItem - example: HasItem: SwordIron. Will make so that quest is only acceptable if player has at least 1 SwordIron in inventory
```

Please note that Quest Rewards and Quest Requirements may be multiple in one quest. You can add them as much as you want with | symbol. Example:


```
Item: SwordIron, 1, 5 | Pet: Wolf, 2, 10 | Skill: Run, 2 | Item: Coins, 100
```
^ quest will give 1 Iron Sword level 5, 2 Wolves level 10, +2 levels of Run skill and 100 coins

Same for requirements:
```
OtherQuest: MyQuest123 | HasItem: PickaxeIron | Skill: Run, 10
```
^ quest will be only acceptable if player has completed quest with ID MyQuest123, has at least 1 PickaxeIron in inventory and has at least 10 levels of Run skill

So... Now that we know all of these things lets create our first quest! I will create a quest where player will need to kill 10 wolves and get 100 Coins + Iron Sword level 3 as a reward with no quest requirements (i will leave it to None). I will set quest cooldown to be 10 in-game days (5 hours real time)

My quest looks like that:
```
[MyTestQuest1]
Kill
This is my first quest!
And this is my first quest description!
Wolf, 10
Item: SwordIron, 1, 3 | Item: Coins, 100
10
None
```
Now we can add this data to out QuestDATABASE.cfg file:

![](https://i.imgur.com/ejk2NIl.png)

After that we are able to give this quest to any NPC profile we create in QuestProfiles.cfg

I will create NPC profile named TestQuests and add my quest to it:

![](https://i.imgur.com/rhuUwUh.png)

Now let's assign this profile to our NPC:

![](https://i.imgur.com/ba3gJUh.png)

On iteract with NPC you should get your result!

![](https://i.imgur.com/lleU3rp.png)

![](https://i.imgur.com/c4FHGqG.png)

As you can see I didn't specify the Wolf target level (Wolf, 10). So it will by default be level 0 (0 stars). So killing any Wolf will be acceptable for this quest.

Let's take quest and try it out!

![](https://i.imgur.com/nVKKAud.png)

Note that Kill, Collect, Harvest quests will have a markers about target. You can disable marker in local Marketplace config on client

![](https://i.imgur.com/GQKiXZG.png)

On killing wolf i get score 1/10

![](https://i.imgur.com/RIOapFp.png)

Now let's change our quest a little. I will change Wolf, 10 to Wolf, 10, 2. This will make so that only wolves level 2 or higher (2 stars) will be acceptable for this quest 

![](https://i.imgur.com/hgInMiO.png)

As you can see our quest target in-game changed:

![](https://i.imgur.com/ZjP5S3z.png)

![](https://i.imgur.com/r47i7qA.png)

Only wolf with 2 stars and higher now acceptable as quest target. You can see that by quest marker above wolf's head

After finishing quest you can come to same NPC that gave it to you and click "Complete" button to receive rewards.

![](https://i.imgur.com/5qZiacv.png)

![](https://i.imgur.com/tlMY7jW.png)

If quest cooldown is lower than 5000 days then it will be still visible in Quest UI. Use quest cooldown 10000+ for one-time quests

Some Quick Screenshots with few other quest types:

Database:
![](https://i.imgur.com/IzGyHHV.png)

Profiles:
![](https://i.imgur.com/nJTMq4r.png)

Results:

Markers on Build quest targets
![](https://i.imgur.com/AGJ4bGI.png)

Markers on harvest + collect targets
![](https://i.imgur.com/Rr3SMac.png)


Markers on Talk Targets

![](https://i.imgur.com/Ejrhf5u.png)

Good luck with creating your own quests!
</p>
</details>

<details><summary>Marketplace</summary>
<p> 

The only NPC that doesn't really need anything to be configured. Its working out of box.

![](https://i.imgur.com/Av5NuBe.png)

To sell items click "Sell" tab => choose item you want to sell => choose quantity / price and click "Sell"

![](https://i.imgur.com/Js9QC2r.png)

After clicking "Sell" item should appear in "BUY" tab with all other items. If you're slot owner you can click on it and "Cancel" your sell.

![](https://i.imgur.com/QKmf1Gl.png)

When someone will buy your item you will get currency in "Income: 0 (it will be bigger when you sell)". To redeem your gold just click + button (Income). Currency will be added to your inventory

Marketplace supports all EIDF (Extended Item Data Framework) mods, such as EpicLoot, Jewelcrafting, Professions and such


</p>
</details>

<details><summary>Banker</summary>
<p> 
Banker is an NPC that allows you to deposit / withdraw your items in bank. Also if you set Banker Income and Banker Income Time in Marketplace.cfg then each N hours (Banker Income Time) every player will get % Income to their bank resources.

To create a Banker profile go to BankerProfiles.cfg and add a new profile:

![](https://i.imgur.com/n7TZqfI.png)

I want to make a Banker profile that will accept Coins + Rubies. For that i would need to add profile [profileName] and add acceptable items on each new line

![](https://i.imgur.com/Zt1lTbw.png)

Let's assign Banker profile to our Banker NPC in-game:

![](https://i.imgur.com/dQriWbn.png)

On Interact with NPC you should see this:

![](https://i.imgur.com/KlarEFR.png)

Green number = resource amount in bank account. Bottom text = inventory amount

So if i want to deposit (put) 250 coins into bank i would need to write "250" and press "+" :

![](https://i.imgur.com/f22k5fQ.png)

![](https://i.imgur.com/SFOAvma.png)

As you can see now i have 250 coins in bank that will be kept there forever and getting income if server admin wants to be so

You may have multiple banker NPCs with different slots (resources) to keep your items in. For example you can have 1 banker that will keep your coins and another one that will keep your rubies

Think about banker as a "global" big chest with infinite space :D



</p>
</details>

<details><summary>Info </summary>
<p> 

NPC will read info from ServerInfo.cfg and display that on GUI.
Rich text markers can be applied to text you write
ServerInfo npc uses "default" profile by default. But you can add as many info profiles you want (same as Trader NPC profiles). Example below:

![](https://i.imgur.com/JSZ90if.png)

![](https://i.imgur.com/cwOiOsO.png)

![](https://i.imgur.com/MfZXnVH.png)

To add data you need to create profile with [ProfileName], and then uder it you can write info you need. Later just assign this profile to Info NPC and it will show it.
Non-profiled text will be applied to every new Info NPC with "default" profile.
</p>
</details>

<details><summary>Teleporter</summary>
<p> 

NPC acts as teleport-hub but all in one. Its profile/data controlled by BepInEx/MarketplaceKG/TeleportHubProfiles.cfg

![](https://i.imgur.com/pTjanHG.png)

![](https://i.imgur.com/MpIGCz8.png)

To Add new teleport spots you need to add them new line each with structure: Spot Name, X coord, Y coord, Z coord, Icon name

You can add Icons in BepInEx/config/MarketplaceKG/MapPinsIcons folder

![https://i.imgur.com/yZVRMLF.png](https://i.imgur.com/yZVRMLF.png)

I recommend you to use 32x32 icons. 
Also you can write ItemPrefab name instead of icon in order to use its icon as map pin
When you click Interact on Teleporter NPC with profile you will open map and it will show pins to you. After Left Mouse click on icon you will teleport to XYZ coords of spot.

![https://i.imgur.com/Hoy6Gg1.png](https://i.imgur.com/Hoy6Gg1.png)

XYZ COORDS SHOULD BE INTEGERS VALUE ONLY (5.6 <= WRONG, 5 <= good)

If you want to make teleport not instant but be more like "magic" teleport, then you can add <speed=value> parameter to teleport spot name

Example:

Spawn <speed=10>, 0,30,0

That will make teleport to spawn not instant but more magic-alike with speed of 10 meters / second

</p>
</details>

<details><summary>Gambler</summary>
<p>
Currently no guide. Please use guide inside GamblerProfiles.cfg itself
</p>
</details>

<details><summary>Buffer</summary>
<p> 
Currently no guide. Please use guide inside BufferProfiles.cfg itself
</p>
</details>

<details><summary>Territory System</summary>
<p> 
Currently no guide. Please use guide inside TerritoryDatabase.cfg itself
</p>
</details>

<details><summary>Battlepass</summary>
<p> 
Currently no guide
</p>
</details>

## ALL OPTIONS / PROFILES / NPCs DATA ARE AUTO-RELOADED IN SERVER RUNTIME WITHOUT RESTART

## ![https://i.imgur.com/5ZHfxlo.png](https://i.imgur.com/5ZHfxlo.png)

## To install mod place MarketPlaceRevamped.dll into Client Plugins folder AND Server Plugins Folder


![https://i.imgur.com/gTTJ9HJ.png](https://i.imgur.com/gTTJ9HJ.png)

﻿For Questions or Comments, find ## KG![https://i.imgur.com/CPYNjXV.png](https://i.imgur.com/CPYNjXV.png)﻿ in the Odin Plus Team Discord:
[![https://i.imgur.com/XXP6HCU.png](https://i.imgur.com/XXP6HCU.png)](https://discord.gg/5gXNxNkUBt)