# UNRELEASED/COLAB ITEMS IN UEFN

> Status: UNPATCHED

## HOW TO USE
1. Download the **CoreSystem.zip** and extract the content into the content folder of your Project
2. If you want to use pre created items download any collection for example **MarvelItemCollection.zip** and extract the content into your content folder as well
3. Compile Verse and Resave the **UnreleasedItems** Folder in UEFN
4. If youre using any Collections you want to head over to the UnreleasedItems folder and in there you will see Entity Prefabs with the name of a collection (You dont need the to use the content from the collections folder)
5. Drag the Entity Prefab into your level and if youve done it correctly it should spawn the vending machines at round start

> Video tutorial (a bit outdated you but you just need to download the CoreSystem.zip as well and it should work fine) https://youtu.be/7cmP-dnaHxk

## STW ITEMS
> In order for STW items to work, you need to launch STW once (its enough if you go to the homebase)

## ITEMIZATION OVERRIDE
> Can be used to change rarity, name, description or icon!
1. Locate your unreleased_item_collection_component of the entity that youre using
2. Access the definitions and search for the Item you want to modify
3. Click **Set to Value** at the **ItemizationOverride** setting
4. Click **Set to Value** for all the settings you want to override
5. Done
> Note: Rarity override will show wrong options at the start just select any rarity and change the value to use mythic/exotic

> Video tutorial: https://youtu.be/-X4J4gl8Js8

## ADD NEW ITEMS
1. Drag the **UnreleasedItemEntity** Entity Prefab in your level and cut/copy it
2. Use any text editor and paste it in
3. Add the following line between **End Object** and **RestoreParentForPaste<Replace>=""** :

    ```lines
    __verse_0x920DEC02_ItemDefinitionID<Replace>="Weapon:wid_westsausage_parallel"
    ```
    **Weapon:wid_westsausage_parallel** Needs to be replaced with the **ActualAnalyticFName** of the item you wanna add. 
    > Get it through **FModel** or some other simular programm.
4. Now copy everything and paste it back into uefn
5. Right click on the entity in the outliner and press **Save as Prefab...**
6. Give it any name (it doesnt matter what you name it)
7. Add the Prefab youve just created to an **unreleased_item_collection_component** *(You can use any entity for that)*
8. Done

> Video tutorial: https://youtu.be/eMGSOQhey6I

## MARVEL COLLECTION ITEM LIST:
> Main Prefab: **MarvelFull**
* Infinity Gauntlet (Endgame)
* Chitauri set (Skin + Jetpack + Rifle + Launcher + Endgame)
* Buried Treasure (Avengers Version)
* Iron Mans Repulsors (Endgame)
* Thors Stormbreaker (Endgame)
* Captain Americas Shield (Endgame)
* Hawkeyes Bow (Endgame)
* Deadpools Keycard (CH2)
* Iron Mans Repulsors (CH2)
* Iron Man Keycard (CH2)
* Doctor Dooms Arcane Gauntlets (CH2; Mythic)
* Doctor Dooms Arcane Gauntlets (CH2; Rare)
* Doctor Dooms Mysticla Bomb (CH2)
* Doctor Doom Keycard (CH2)
* Thors Mjolnir Strike (CH2)
* Storms Tornado Launch (CH2)
* Groots Bramble Shield (CH2)
* She Hulks Fists (CH2; Mythic)
* She Hulks Fists (CH2; Rare)
* Silver Surfers Board (CH2)
* Venoms Smash & Grab (CH2)
* Mystiques Dual Auto Pistols (Unreleased)
* Stark Jetpack (CH2)
* Stark Rifle (Rare + Epic + Legendary; CH2)
* Venom Symbiote (CH2)
* Carnage Symbiote (CH2)
* Spidermans Web Shooter (CH3)
* Spiderverse Web Shooters (CH4)
* War Machine set (Arsenal + Jetpack + Auto Turret; CH5)
* Iron Mans set (Flight- + Combatkit; CH5)
* Shuris Black Panther Claws (CH5)
* Gwenpools Dual Micro SMGs (CH5)
* Captain Americas Shield (CH5)
* Doctor Dooms Arcane Gauntlets (CH5)
* Magneto Power (CH5)
* Symbiote Scythe (Pickaxe)
* Symbiote Slasher (Pickaxe)
* Adamantium Claws (Pickaxe)

## STORM KING COLLECTION ITEM LIST:
> Main Prefab: StormKingCollectionGenerator
* Storm Kings Wrath
* Storm Kings Scourge
* Storm Kings Onslaught
* Storm Kings Fury
* Storm Kings Ravager

## ANIME COLLECTION ITEM LIST:
> Main Prefab: AnimeCollectionGenerator
* Airbending
* Earthbending
* Waterbending
* Firebending
* Hollow Mask
* Dual Zangetsu
* ODM Gear
* Kamehameha
* Nimbus Cloud

## SIMPSONS COLLECTION ITEM LIST:
> Main Prefab: SimpsonsCollectionGenerator
* Blinky Fish
* Caramber AR
* Cartoon Chainsaw
* Chug Jug
* Chug Splash
* Cobalt Sling Shot
* Deodorant Applicator
* Dragons Belch Shotgun
* Embiggened AR
* Fivegun
* KBBL Keycard
* Krusty Burger
* Mr Blasty (Legendary)
* Krustys Blasty
* Enhanced Tactical Shotgun
* Steamed Hams
* Super Squishee
* Tamzarian SMG
* Tomato
* Mutated Tomato
