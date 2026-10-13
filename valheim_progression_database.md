# Valheim Progression Master Database & Compendium

A comprehensive, plain-text reference database across all 7 biomes plus the Ocean sub-biome. Includes base building, metallurgy, workstations & upgrades, crops, farming, taming, cooked foods, stews, baked goods, potions & meads, gear, weapons, magic, merchants & key purchases, comfort & rested tiers, base raids & world triggers, and boss offerings.

Use this document to edit, add, or refine content before synchronizing with the interactive code.

---

## 📋 Card Creation Reference & Templates

When creating or adding new progression cards to any biome, copy and paste one of the templates below directly under that biome's `### Milestones, Stations, Gear & Crafts` header.

### 1. Standard Progression Card (Copy & Fill Out)
```markdown
#### Card Name Here
- Item ID: unique_card_id
- Category: Weapons & Tools
- Priority: High
- Crafting Station: Forge Lv 1
- Materials: 10 Bronze, 2 Wood
- Summary: Short summary of what this item does and why it matters.
- Strategy & Tip: Practical advice on combat usage, crafting efficiency, or timing.
```

### 2. Available Field Options & Rules

* **Header (`#### Title`)**: The displayed name of your card.
* **`- Item ID:`**: A unique identifier (no spaces, use underscores like `swamp_iron_axe`). Used to remember if a card is checked off.
* **`- Category:`**: Must match one of the filtering categories:
  * `Station & Base`
  * `Weapons & Tools`
  * `Armor & Defense`
  * `Food & Mead`
  * `Farming & Taming`
  * `Boss & Offering`
* **`- Priority:`**: Visual importance badge on the card:
  * `Essential` (Red / Golden glow - critical milestone)
  * `High` (Orange - highly recommended gear or upgrade)
  * `Recommended` (Green - helpful utility or comfort)
  * `Situational` (Gray/Blue - optional or niche)
* **`- Crafting Station:`**: Station name and level needed (e.g., `Workbench Lv 2`, `Black Forge`, `Cauldron`).
* **`- Materials:`**: Comma-separated list of ingredients (e.g., `20 Iron, 2 Leather Scraps, 4 Bark`).
* **`- Summary:`**: 1-2 sentence overview shown directly on the card.
* **`- Strategy & Tip:`**: Pro-tips or tactical gameplay notes revealed when expanding details.

---

## 1. Meadows

- Biome ID: meadows
- Lore: The tranquil birthplace of Viking spirits. Gather basic flint, wood, raspberries, and tame your first boar.
- Forsaken Boss: Eikthyr (Thunder Stag)

### Milestones, Stations, Gear & Crafts

#### Workbench
- Item ID: m_workbench
- Category: Station & Base
- Priority: Essential
- Crafting Station: Hammer (Hand-crafted)
- Materials: 10 Wood
- Summary: Enables tool repair and basic item creation within a building radius.
- Strategy & Tip: Must have roof tiles and walls enclosing at least 70% of the station to function.

#### Chopping Block & Tanning Rack
- Item ID: m_workbench_upgrades
- Category: Station & Base
- Priority: High
- Crafting Station: Hammer (near Workbench)
- Materials: Chopping Block: 10 Wood, 10 Flint | Tanning Rack: 10 Wood, 15 Flint, 20 Leather Scraps, 5 Deer Hide
- Summary: Upgrades Workbench to Levels 2 and 3, unlocking higher tier crafting and equipment upgrades.
- Strategy & Tip: Place extensions within 2 meters of the main workbench.

#### Crude Bow
- Item ID: m_crude_bow
- Category: Weapons & Tools
- Priority: High
- Crafting Station: Workbench Lv 1
- Materials: 10 Wood, 8 Leather Scraps (Arrows: 8 Wood, 2 Flint, 2 Feathers per 20)
- Summary: Allows hunting skittish deer from afar for trophies and leather hides.
- Strategy & Tip: Deer hides are vital for crafting armor and summoning Eikthyr.

#### Flint Axe
- Item ID: m_flint_axe
- Category: Weapons & Tools
- Priority: High
- Crafting Station: Workbench Lv 1
- Materials: 4 Wood, 6 Flint
- Summary: Reliable melee weapon with higher damage than club; fells regular trees.
- Strategy & Tip: Flint spears have rapid stab animations and can be thrown at running deer.

#### Wooden Shield
- Item ID: m_wood_shield
- Category: Weapons & Tools
- Priority: Essential
- Crafting Station: Workbench Lv 1
- Materials: 10 Wood, 4 Resin, 4 Leather Scraps
- Summary: Teaches timing-based parrying to stagger early enemies.
- Strategy & Tip: Timing a block right before an impact triggers a stagger with critical damage multiplier.

#### Leather Armor
- Item ID: m_leather_armor
- Category: Armor
- Priority: Recommended
- Crafting Station: Workbench Lv 2
- Materials: 22 Deer Hide, 5 Leather Scraps (Full Helmet, Tunic, Pants)
- Summary: Provides physical protection against boars, necks, and Greyling raids.
- Strategy & Tip: Upgrade each piece to Level 2 at the Workbench for extra protection without speed penalties.

#### Deer Hide Cape
- Item ID: m_deer_cape
- Category: Armor
- Priority: Recommended
- Crafting Station: Workbench Lv 2
- Materials: 4 Deer Hide, 5 Bone Fragments
- Summary: Completes early armor set and adds aesthetic Viking cloak flair.
- Strategy & Tip: Skeleton remains found in the Black Forest or shoreline graves drop bone fragments.

#### Raft
- Item ID: m_raft
- Category: Station & Base
- Priority: Situational
- Crafting Station: Workbench (near shoreline)
- Materials: 20 Wood, 6 Leather Scraps, 6 Resin
- Summary: Primitive watercraft suited for crossing narrow rivers and sheltered bays before unlocking bronze nails.
- Strategy & Tip: Highly susceptible to wind shifts and ocean waves; avoid sailing into open Ocean biomes where Sea Serpents will easily destroy it.

#### Stagbreaker
- Item ID: m_stagbreaker
- Category: Weapons & Tools
- Priority: High
- Crafting Station: Workbench Lv 2
- Materials: 20 Core Wood, 5 Deer Trophy, 2 Leather Scraps
- Summary: Heavy two-handed wooden hammer that unleashes radial blunt and pierce damage around the impact point.
- Strategy & Tip: Excellent for crowd control against packs of Greydwarfs and Skeletons. Its wide radial burst can strike targets on elevated ledges or behind low barricades.

### Comfort & Rested Tiers

#### Bed & Campfire
- Item ID: m_comfort_tier
- Category: Comfort & Living
- Priority: Essential
- Crafting Station: Hammer
- Materials: 
  - Campfire / Fireplace (Wood x2, Stone x5)
  - Wood Bed (Wood x8)
  - Shelter Roof & Walls (Wood x16)
  - Deer Rug (Deer Hide x4)
- Summary: Grants Comfort Level 4–5, extending the Rested Buff duration to 11–12 minutes.
- Strategy & Tip: The Rested buff is vital (+50% HP regen, +100% Stamina regen, +50% XP gain). Never venture into the wilderness without it active. Ensure campfire smoke is vented with a chimney to prevent suffocation.

### Farming, Flora, Taming & Food Recipes

#### Boar Pen
- Item ID: m_boar_pen_taming
- Category: Farming & Taming
- Priority: High
- Crafting Station: Hammer (Roundpole Fence)
- Materials: 20 Wood, 10 Raspberries, 10 Mushrooms
- Summary: Enclose wild boars with roundpole fences and feed them to cultivate domestic livestock.
- Strategy & Tip: Keep fire and torches away as fire spooks boars and halts taming. Feed Raspberries, Blueberries, or Carrots while staying crouched out of sight.

#### Beehive
- Item ID: m_beehive_farming
- Category: Farming & Taming
- Priority: Essential
- Crafting Station: Hammer (Workbench Area)
- Materials: 1 Queen Bee, 10 Wood
- Summary: Harvest Queen Bees from ruined houses to construct base apiaries for infinite Honey.
- Strategy & Tip: Check "The bees are happy" status. Ensure open sky above hives. Honey is foundational for all food and brewing meads.

#### Cooking Station
- Item ID: m_early_food
- Category: Food & Mead
- Priority: Essential
- Crafting Station: Cooking Station over Campfire
- Materials: Cooked Deer Meat (1 Raw Deer Meat), Cooked Boar Meat (1 Raw Boar Meat), Cooked Neck Tail (1 Neck Tail)
- Stats / Effect: 
  - Cooked Deer Meat: +35 Health, +12 Stamina (20 min)
  - Cooked Boar Meat: +30 Health, +10 Stamina (20 min)
  - Grilled Neck Tail: +25 Health, +8 Stamina (20 min)
- Summary: Core early game health-boosting food staples before obtaining cooking pots.
- Strategy & Tip: Listen for the sizzle and watch meat turn darker brown; take off immediately to avoid charcoal.

#### Raspberry & Mushroom
- Item ID: m_foraged_food
- Category: Food & Mead
- Priority: Essential
- Crafting Station: Foraged (Hand-picked)
- Materials: Raspberries, Yellow Mushrooms (Caves), Red Mushrooms
- Stats / Effect:
  - Raspberry: +7 Health, +20 Stamina (15 min)
  - Red Mushroom: +15 Health, +15 Stamina (15 min)
  - Honey: +8 Health, +35 Stamina, +5 HP/tick (15 min)
- Summary: Stamina-heavy foraged foods essential for running, building, and chopping wood.
- Strategy & Tip: Never eat your entire honey or berry stock—save reserves for future mead bases and stews.

### Base Raids & World Events

#### Eikthyr Raid
- Item ID: m_raid_triggers
- Category: Base Raids & Defense
- Priority: High
- Trigger Condition: Active prior to defeating Eikthyr.
- Raid Enemies: Swarms of wild Boars and Necks attack your structures.
- Defense Strategy: Surround your base with a stakewall or roundpole fence; boars cannot jump fences. Dig a shallow ditch with the Hoe/Pickaxe if boars threaten crops.

### Boss & Offering

#### Summon & Slay Eikthyr
- Item ID: m_eikthyr_offering
- Category: Boss & Offering
- Priority: Boss Key
- Summoning Station: Meadows Mystical Stone Altar
- Materials / Offering: 2 Deer Trophy
- Summary: Sacrifice 2 Deer Trophies at the Mystical Altar to unlock the Antler Pickaxe and Eikthyr Power.
- Strategy & Tip: Block his lightning discharges with a Wooden Shield. Eikthyr Forsaken Power reduces running and jumping stamina drain by 60%.

---

## 2. Black Forest

- Biome ID: blackforest
- Lore: Dense pine wilderness crawling with Greydwarfs, Trolls, and subterranean Burial Chambers containing Surtling Cores.
- Forsaken Boss: The Elder (Colossal Treant)

### Milestones, Stations, Gear & Crafts

#### Antler Pickaxe
- Item ID: bf_antler_pickaxe
- Category: Weapons & Tools
- Priority: Essential
- Crafting Station: Workbench Lv 1
- Materials: 10 Wood, 1 Hard Antler (Dropped by Eikthyr)
- Summary: Carved from Eikthyr's antlers to mine Copper and Tin deposits.
- Strategy & Tip: Can be repaired at a simple Workbench in an outpost near mining veins without a forge.

#### Charcoal Kiln & Smelter
- Item ID: bf_kiln_smelter
- Category: Station & Base
- Priority: Essential
- Crafting Station: Hammer
- Materials: 40 Stone, 10 Surtling Core (5 cores each)
- Summary: Converts raw Wood into Coal and smelts raw Copper/Tin into metal bars.
- Strategy & Tip: Clear Black Forest Burial Chambers to collect your first 10 Surtling Cores.

#### Forge
- Item ID: bf_forge_station
- Category: Station & Base
- Priority: Essential
- Crafting Station: Hammer
- Materials: Forge: 4 Stone, 4 Coal, 10 Wood, 6 Copper | Anvils: 5 Wood, 20 Bronze | Forge Cooler: 25 Fine Wood, 10 Copper
- Summary: Unlocks bronze metallurgy, metal tools, armor, and upgraded equipment benches.
- Strategy & Tip: Alloy 2 Copper + 1 Tin at the Forge to create 1 Bronze bar.

#### Bronze Axe
- Item ID: bf_bronze_axe
- Category: Weapons & Tools
- Priority: Essential
- Crafting Station: Forge Lv 1
- Materials: 8 Bronze, 4 Wood, 2 Leather Scraps
- Summary: Necessary to chop down Birch and Oak trees for Fine Wood.
- Strategy & Tip: Fine Wood unlocks portals, high-grade furniture, fine wood bows, and ships.

#### Finewood Bow & Bronze Buckler
- Item ID: bf_bow_buckler
- Category: Weapons & Tools
- Priority: High
- Crafting Station: Finewood Bow: Workbench Lv 2 | Buckler: Forge Lv 1
- Materials: Bow: 10 Fine Wood, 10 Core Wood, 2 Deer Hide | Buckler: 10 Bronze, 8 Wood
- Summary: Upgraded sniper bow and bronze buckler capable of parrying Troll club swings.
- Strategy & Tip: Bucklers have a 2.5x parry bonus, making timing windows extremely rewarding.

#### Troll Leather Armor
- Item ID: bf_troll_armor
- Category: Armor
- Priority: Recommended
- Crafting Station: Workbench Lv 3
- Materials: 25 Troll Hide, 3 Bone Fragments
- Summary: Lightweight stealth set granting a +15 Sneak bonus with zero movement speed penalty.
- Strategy & Tip: Dodge-roll under Troll attacks or kite them with fire arrows to collect hides safely.

#### Karve & Portal
- Item ID: bf_karve_portal
- Category: Station & Base
- Priority: Essential
- Crafting Station: Hammer (Workbench Area)
- Materials: Karve: 30 Fine Wood, 10 Deer Hide, 20 Resin, 80 Bronze Nails | Portal: 10 Greydwarf Eye, 20 Fine Wood, 2 Surtling Core
- Summary: Faster sea transport with 4 cargo slots and instantaneous base-to-base portal teleportation.
- Strategy & Tip: Metals cannot be transported through portals; haul ores across oceans with the Karve.

#### Hand Cart
- Item ID: bf_hand_cart
- Category: Station & Base
- Priority: Essential
- Crafting Station: Hammer (Workbench Area)
- Materials: 20 Wood, 10 Bronze Nails
- Summary: Two-wheeled hauler providing extensive storage capacity for overland mining expeditions.
- Strategy & Tip: As cargo weight increases, the cart becomes heavier to pull uphill. Plan routes along natural contours or construct basic wooden bridge ramps over rough trenches.

#### Bronze Spear & Bronze Sword
- Item ID: bf_bronze_weapons
- Category: Weapons & Tools
- Priority: Recommended
- Crafting Station: Forge Lv 1
- Materials: Bronze Spear: 5 Core Wood, 6 Bronze, 2 Deer Hide | Bronze Sword: 2 Wood, 8 Bronze, 2 Leather Scraps
- Summary: The Bronze Spear offers high-speed thrust attacks and throwing utility; the Bronze Sword delivers dependable slash combos without knockback penalty.
- Strategy & Tip: The sword's alternate attack is a high-damage downward thrust that deals triple damage when timed during an enemy's recovery window.

### Comfort & Rested Tiers

#### Chair, Table & Banner
- Item ID: bf_comfort_tier
- Category: Comfort & Living
- Priority: High
- Crafting Station: Hammer
- Materials: 
  - Fine Wood Chair (Fine Wood x4)
  - Fine Wood Table (Fine Wood x6)
  - Hanging Banners (Fine Wood x1, Leather Scraps x2, Coal x1)
  - Round Table & Stools
- Summary: Raises Comfort Level to 7–8, yielding a 14–15 minute Rested duration.
- Strategy & Tip: Banners of differing colors do not stack comfort, but combining Chair + Table + Fire + Bed + Rugs maximizes duration.

### Merchants & Key Purchases

#### Haldor the Merchant
- Item ID: bf_trader_haldor
- Category: Merchants & Trade
- Priority: Essential
- Location: Spawns in a Black Forest within 1500m of map center (marked with a coin bag icon upon getting within 2km).
- Key Inventory Purchases:
  - **Megingjord** (950 Coins): Accessory belt that permanently increases carry weight limit from 300 to 450.
  - **Dvergr Circlet** (620 Coins): Equippable helmet-mounted headlamp providing front-facing light in dark crypts and night.
  - **Ymir Flesh** (120 Coins each): Essential crafting component for Iron Sledge and Frostner mace.
  - **Fishing Rod & Fishing Bait** (350 Coins + 10 Coins/50 bait): Allows catching fish for cooking.
- Strategy & Tip: Save all Ruby gems, Amber, Amber Pearls, and Coins found in burial chambers to purchase Megingjord first!

### Farming, Flora, Taming & Food Recipes

#### Cultivator & Carrot
- Item ID: bf_cultivator_farming
- Category: Farming & Taming
- Priority: Essential
- Crafting Station: Forge Lv 1
- Materials: 5 Bronze, 5 Core Wood
- Summary: Forge the Cultivator to till soil, plant wild carrot seeds, cultivate crops, and replant seed carrots.
- Strategy & Tip: 1 Carrot -> plant as "Seed Carrot" -> yields 3 Carrot Seeds. Never eat your last carrot!

#### Cauldron & Fermenter
- Item ID: bf_cauldron_fermenter
- Category: Station & Base
- Priority: Essential
- Crafting Station: Cauldron: Campfire / Forge | Fermenter: Hammer
- Materials: Cauldron: 10 Tin | Fermenter: 30 Fine Wood, 5 Bronze, 10 Resin
- Summary: Unlocks culinary cooking, hearty broths, and fermentation of medicinal mead bases.
- Strategy & Tip: Fermenting takes approximately 2 in-game days (about 30 minutes of real playtime).

#### Carrot Soup & Deer Stew
- Item ID: bf_stews_food
- Category: Food & Mead
- Priority: Essential
- Crafting Station: Cauldron Lv 1
- Materials: 
  - Carrot Soup: 3 Carrot, 1 Mushroom
  - Deer Stew: 1 Cooked Deer Meat, 1 Blueberry, 1 Carrot
  - Minced Meat Sauce: 1 Boar Meat, 1 Neck Tail, 1 Carrot
- Stats / Effect:
  - Carrot Soup: +15 Health, +45 Stamina (25 min)
  - Deer Stew: +45 Health, +15 Stamina (25 min)
  - Minced Meat Sauce: +40 Health, +13 Stamina (25 min)
- Summary: Huge step up in stats; allows running longer distances and sustaining heavier hits.
- Strategy & Tip: Pairing Carrot Soup with Deer Stew and Minced Meat Sauce provides maximum early balance.

#### Queens Jam
- Item ID: bf_queens_jam
- Category: Food & Mead
- Priority: High
- Crafting Station: Cauldron Lv 1
- Materials: 8 Raspberries, 8 Blueberries (Yields 4 servings)
- Stats / Effect: +14 Health, +40 Stamina (20 min)
- Summary: Superb stamina food for mining and woodchopping operations.
- Strategy & Tip: Very easy to mass-produce during summer foraging runs in Meadows and Black Forest borders.

#### Minor Healing Mead
- Item ID: bf_mead_minor_healing
- Category: Food & Mead
- Priority: Essential
- Crafting Station: Cauldron Lv 1 -> Fermenter
- Materials: 10 Honey, 5 Blueberries, 10 Raspberries, 1 Dandelion (Ferments into 6 Potions)
- Stats / Effect: Instantly heals +50 Health over 10 seconds (Cooldown: 2 min)
- Summary: Essential life-saving emergency medicine for combat.
- Strategy & Tip: Always keep a stack of healing mead on your hotbar.

#### Minor Stamina Mead
- Item ID: bf_mead_minor_stamina
- Category: Food & Mead
- Priority: High
- Crafting Station: Cauldron Lv 1 -> Fermenter
- Materials: 10 Honey, 10 Raspberries, 10 Yellow Mushrooms (Yields 6 Potions)
- Stats / Effect: Instantly recovers +80 Stamina over a brief period
- Summary: Saves you from drowning or running completely dry during intense boss fights.

#### Poison Resistance Mead
- Item ID: bf_mead_poison_resist
- Category: Food & Mead
- Priority: Essential
- Crafting Station: Cauldron Lv 1 -> Fermenter
- Materials: 10 Honey, 5 Thistle, 1 Neck Tail, 10 Coal (Yields 6 Potions)
- Stats / Effect: Reduces Poison damage taken by 75% for 10 minutes
- Summary: Absolutely mandatory before setting foot into the Swamp biome.
- Strategy & Tip: Swamp leeches, Blobs, and Oozers will kill you without this active buff.

### Base Raids & World Events

#### Black Forest Raids
- Item ID: bf_raid_triggers
- Category: Base Raids & Defense
- Priority: Essential
- Trigger Condition: 
  - *"The forest is moving..."*: Active after killing Eikthyr. Involves Greydwarfs, Brutes, and Shamans.
  - *"The ground is shaking..."*: Active after killing The Elder and at least one Troll. Spawns 2 massive Trolls wielding logs.
- Defense Strategy: 
  - Trolls will demolish wooden houses in two swings! Dig a steep 2-meter deep trench (Moat) around your perimeter using your Pickaxe. Enemies cannot path across steep trenches or vertical cliff edges.

### Boss & Offering

#### Summon & Defeat The Elder
- Item ID: bf_elder_offering
- Category: Boss & Offering
- Priority: Boss Key
- Summoning Station: Black Forest Elder Altar
- Materials / Offering: 3 Ancient Seed (Dropped by Greydwarf Shamans/Brutes & Spawners)
- Summary: Burn 3 Ancient Seeds at the Sacrificial Bowl to obtain the Swamp Crypt Key and Elder Power.
- Strategy & Tip: Hide behind the indestructible stone pillars when he shoots barrage roots. Elder Power speeds up wood cutting by 60%.

---

## 2.5 The Ocean (Sub-Biome Expedition)

- Biome ID: ocean
- Lore: Treacherous open waters connecting the continents of Valheim, teeming with living island Leviathans and predatory Serpents.
- Boss / Threat: Sea Serpent (Apex Marine Hunter)

### Nautical Milestones, Harvesting & Crafts

#### Chitin
- Item ID: oc_leviathan_chitin
- Category: Weapons & Tools
- Priority: High
- Encounter: Giant floating moss-covered islands with Barnacles.
- Equipment: Any Pickaxe
- Materials: Chitin (Harvested from Abyssal Barnacles)
- Summary: Mine barnacles on the Leviathan's shell to obtain Chitin before the beast shakes and submerges into the deep.
- Strategy & Tip: Keep your Karve or Longship parked immediately adjacent to the shell; as soon as you hear the creature groan, you have ~15 seconds to board your boat.

#### Abyssal Harpoon & Abyssal Razor
- Item ID: oc_abyssal_gear
- Category: Weapons & Tools
- Priority: Essential
- Crafting Station: Workbench Lv 2
- Materials: 
  - Abyssal Harpoon: 30 Chitin, 8 Fine Wood, 3 Leather Scraps
  - Abyssal Razor: 20 Chitin, 4 Fine Wood, 2 Leather Scraps
- Summary: The Harpoon tethers large targets (Serpents, Boars, Wolves) with an unbroken rope, allowing players to drag aquatic monsters onto land.
- Strategy & Tip: The Abyssal Razor is one of the highest backstab DPS daggers in early/mid game.

#### Serpent Scale Shield
- Item ID: oc_serpent_hunting
- Category: Weapons & Tools
- Priority: High
- Encounter: Ocean waters during heavy night storms or rain.
- Materials: Serpent Meat, Serpent Scales, Serpent Trophy
- Crafting (Shield): 10 Fine Wood, 4 Iron, 8 Serpent Scale (Workbench Lv 3)
- Summary: The Serpent Scale Shield provides immense passive Pierce Resistance against arrows and Deathsquitoes.
- Strategy & Tip: Drag Serpents onto shallow land with the Abyssal Harpoon before finishing them off, or else their heavy Scales will sink straight to the ocean seafloor!

#### Cooked Serpent Meat & Serpent Stew
- Item ID: oc_serpent_food
- Category: Food & Mead
- Priority: Pro Tip
- Crafting Station: Iron Cooking Station (over Hearth) / Cauldron Lv 2
- Materials: 
  - Cooked Serpent Meat: 1 Raw Serpent Meat (+70 HP, +23 Stamina, 25 min)
  - Serpent Stew: 1 Cooked Serpent Meat, 2 Honey, 1 Mushroom (+80 HP, +26 Stamina, 30 min)
- Summary: The premier early-to-midgame vitality food that carries players through difficult Mountain and Plains boss battles.

---

## 3. Swamp

- Biome ID: swamp
- Lore: Perpetual gloom and sunken crypts. Muddy scrap piles yield Iron, while leach poisons test your resolve.
- Forsaken Boss: Bonemass (Toxic Slime Monolith)

### Milestones, Stations, Gear & Crafts

#### Swamp Key & Sunken Crypt
- Item ID: sw_swamp_key_crypts
- Category: Station & Base
- Priority: Essential
- Crafting Station: Sunken Crypt Gate
- Materials: 1 Swamp Key (Dropped by The Elder)
- Summary: Unlocks submerged stone crypts containing Muddy Scrap Piles and Withered Bones.
- Strategy & Tip: Carry a bronze or antler pickaxe to carve through mud walls, then place campfires inside the crypt entrance to dry off.

#### Stonecutter
- Item ID: sw_stonecutter
- Category: Station & Base
- Priority: Essential
- Crafting Station: Hammer
- Materials: 10 Wood, 2 Iron, 4 Stone
- Summary: Unlocks stone building walls, stone arches, pavers, and high-tier stone fireplaces.
- Strategy & Tip: Stone foundations are essential for supporting tall multi-story towers and the massive Iron Hearth.

#### Iron Pickaxe & Banded Shield
- Item ID: sw_iron_tools
- Category: Weapons & Tools
- Priority: Essential
- Crafting Station: Forge Lv 2
- Materials: Iron Pickaxe: 20 Iron, 3 Core Wood | Banded Shield: 10 Iron, 10 Fine Wood
- Summary: Iron Pickaxe is mandatory to mine Obsidian and Silver in the Mountains.
- Strategy & Tip: Banded shield allows parrying Draugr Elites and Abominations.

#### Iron Mace & Huntsman Bow
- Item ID: sw_iron_mace
- Category: Weapons & Tools
- Priority: High
- Crafting Station: Forge Lv 2
- Materials: Iron Mace: 20 Iron, 4 Wood, 3 Leather Scraps | Huntsman Bow: 10 Iron, 20 Fine Wood, 10 Feathers, 2 Deer Hide
- Summary: Blunt trauma weapon with maximum damage against Skeletons, Blobs, and Bonemass.
- Strategy & Tip: Bonemass takes 1.5x damage from blunt force and is highly resistant to slash and pierce.

#### Iron Armor
- Item ID: sw_iron_armor
- Category: Armor
- Priority: Essential
- Crafting Station: Forge Lv 2
- Materials: 60 Iron, 6 Deer Hide (Scale Mail, Greaves, Helmet)
- Summary: Substantial leap in physical defense at the cost of a -10% movement penalty.
- Strategy & Tip: Craft chestplate first for maximum survivability against Draugr arrows.

#### Root Armor
- Item ID: sw_root_harnesk
- Category: Armor
- Priority: Pro Tip
- Crafting Station: Workbench Lv 2
- Materials: Root Harnesk: 10 Root, 10 Elder Bark, 2 Deer Hide (Full set needs 66 Root)
- Summary: Crafted from Abominations; provides permanent Pierce Resistance and +15 Bow skill.
- Strategy & Tip: Extremely powerful in the Plains because it turns Deathsquito needle attacks into trivial hits.

#### Longship
- Item ID: sw_longship
- Category: Station & Base
- Priority: Essential
- Crafting Station: Hammer (Workbench Area)
- Materials: 100 Iron Nails, 40 Fine Wood, 10 Deer Hide, 40 Elder Bark
- Summary: Largest ship with 18 cargo slots, exceptional speed, and huge hull hit points.
- Strategy & Tip: Build this immediately to haul huge amounts of iron ore back to your primary forge base.

#### Iron Sledge
- Item ID: sw_iron_sledge
- Category: Weapons & Tools
- Priority: High
- Crafting Station: Forge Lv 2
- Materials: 10 Ancient Bark, 30 Iron, 4 Ymir Flesh, 1 Draugr Elite Trophy
- Summary: Massive two-handed warhammer with high blunt area damage and severe knockback.
- Strategy & Tip: Requires Ymir Flesh from Haldor the Merchant. Deals exceptional damage to tightly clustered groups of Draugr and Blobs inside cramped crypt corridors.

#### Iron Atgeir & Battleaxe
- Item ID: sw_iron_heavy_arms
- Category: Weapons & Tools
- Priority: Recommended
- Crafting Station: Forge Lv 2
- Materials: Iron Atgeir: 30 Iron, 10 Wood, 2 Leather Scraps | Battleaxe: 30 Iron, 30 Ancient Bark, 4 Leather Scraps
- Summary: Long-reach polearm and two-handed cleaving axe featuring wide horizontal sweep attacks.
- Strategy & Tip: The Atgeir's secondary spin consumes substantial stamina but guarantees a high-multiplier stagger on surrounding enemies.

### Comfort & Rested Tiers

#### Hearth & Brazier
- Item ID: sw_comfort_tier
- Category: Comfort & Living
- Priority: High
- Crafting Station: Hammer (Stonecutter Area)
- Materials: 
  - Stone Hearth (Stone x15, Iron x2)
  - Standing Wood Brazier / Hanging Brazier (Bronze x5, Coal x2, Chains x1)
  - Iron Cooking Station (Iron x3, Chains x3)
- Summary: Boosts Comfort to 10–11, giving a 17–18 minute Rested buff.
- Strategy & Tip: The Hearth produces superior warmth across a wide radius and replaces flimsy campfires indoors.

### Merchants & Key Purchases

#### The Bog Witch
- Item ID: sw_bog_witch
- Category: Merchants & Trade
- Priority: Recommended
- Location: Found secluded in deep swamp clearings under twisted roots.
- Key Inventory Purchases:
  - **Scythe**: Tool for sweeping field crop harvesting.
  - **Spices & Tonics**: Exotic seasonings that unlock specialty draughts and extended feasts.
- Strategy & Tip: Sells ingredients that significantly reduce kitchen farming tedium.

### Farming, Flora, Taming & Food Recipes

#### Turnip
- Item ID: sw_turnip_domestication
- Category: Farming & Taming
- Priority: Essential
- Crafting Station: Cultivator on Tilled Soil
- Materials: 3 Turnip Seeds (Harvested from rare yellow flowers in the Swamp)
- Summary: Cultivate domestic turnip crops to upgrade your Cauldron and unlock hearty stews.
- Strategy & Tip: Never cook your only turnips! Replant every bulb as a "Seed Turnip" (1 bulb yields 3 seeds) until you have a stockpile of 100+ seeds.

#### Spice Rack
- Item ID: sw_spice_rack
- Category: Station & Base
- Priority: Essential
- Crafting Station: Hammer (near Cauldron)
- Materials: 3 Dandelion, 2 Carrot, 5 Mushroom, 3 Thistle, 3 Turnip
- Summary: Upgrades Cauldron to Level 2, unlocking Swamp culinary dishes.
- Strategy & Tip: Must be placed hanging near the cauldron.

#### Sausages
- Item ID: sw_sausages
- Category: Food & Mead
- Priority: High
- Crafting Station: Cauldron Lv 2
- Materials: 2 Entrails (from Draugr), 1 Raw Meat, 4 Thistle (Yields 4 servings)
- Stats / Effect: +55 Health, +18 Stamina (25 min)
- Summary: Outstanding cost-effective health food for mid-game exploration.
- Strategy & Tip: Farm Draugrs around sunken crypt doorways to easily gather stacks of entrails.

#### Turnip Stew
- Item ID: sw_turnip_stew
- Category: Food & Mead
- Priority: Essential
- Crafting Station: Cauldron Lv 2
- Materials: 3 Turnip, 1 Raw Meat
- Stats / Effect: +18 Health, +55 Stamina (25 min)
- Summary: Massive stamina boost essential for swimming, swinging pickaxes, and dodging.
- Strategy & Tip: Combine Turnip Stew with Sausages and Deer Stew for a balanced Swamp diet.

#### Black Soup & Muckshake
- Item ID: sw_black_soup
- Category: Food & Mead
- Priority: Recommended
- Crafting Station: Cauldron Lv 2
- Materials: 
  - Black Soup: 1 Bloodbag, 1 Honey, 1 Turnip (+50 HP, +17 Stamina)
  - Muckshake: 1 Guck, 2 Honey, 10 Ooze (+16 HP, +50 Stamina)
- Summary: Bloodbags from Leeches and Guck from green swamp trees unlock specialized stat diets.

#### Medium Healing Mead
- Item ID: sw_mead_medium_healing
- Category: Food & Mead
- Priority: Essential
- Crafting Station: Cauldron Lv 2 -> Fermenter
- Materials: 10 Honey, 4 Bloodbag, 10 Raspberries, 1 Dandelion (Yields 6 Potions)
- Stats / Effect: Instantly recovers +75 Health over 10 seconds
- Summary: High-tier medical flask replacing minor healing meads.

#### Frost Resistance Mead
- Item ID: sw_mead_frost_resist
- Category: Food & Mead
- Priority: Essential
- Crafting Station: Cauldron Lv 2 -> Fermenter
- Materials: 10 Honey, 5 Thistle, 2 Bloodbag, 1 Greydwarf Eye (Yields 6 Potions)
- Stats / Effect: Grants complete Freezing Immunity for 10 minutes
- Summary: Mandatory requirement before scaling high Mountain peaks to search for Silver.

### Base Raids & World Events

#### Swamp Raid
- Item ID: sw_raid_triggers
- Category: Base Raids & Defense
- Priority: High
- Trigger Condition: Active after defeating The Elder.
- Raid Enemies: Draugr warriors, Draugr archers, and Skeletons assault your base.
- Defense Strategy: Draugr archers shoot snipe arrows into exposed buildings. Line inner wall perimeters with raised stone earth embankments so arrows harmlessly strike dirt.

### Boss & Offering

#### Summon & Slay Bonemass
- Item ID: sw_bonemass_offering
- Category: Boss & Offering
- Priority: Boss Key
- Summoning Station: Swamp Boiling Skull Altar
- Materials / Offering: 10 Withered Bone (Mined from Sunken Crypts)
- Summary: Sacrifice 10 Withered Bones to awaken Bonemass and obtain the Wishbone and Bonemass Power.
- Strategy & Tip: Mandatory: Drink Poison Resistance Mead. Attack using Iron Mace and blunt strikes. Bonemass Forsaken Power grants huge physical damage resistance against Blunt, Slash, and Pierce.

---

## 4. Mountain

- Biome ID: mountain
- Lore: Sub-zero blizzard peaks home to howling wolves, stone golems, and frozen silver veins.
- Forsaken Boss: Moder (Dragon Matron)

### Milestones, Stations, Gear & Crafts

#### Wishbone & Silver
- Item ID: mt_wishbone_silver
- Category: Weapons & Tools
- Priority: Essential
- Crafting Station: Inventory Equipment (Dropped by Bonemass)
- Materials: Wishbone equipped
- Summary: Pulses with green audio/visual chimes to pinpoint buried Silver veins and buried chests beneath snow.
- Strategy & Tip: Use an Iron Pickaxe to dig down once the chime frequency peaks.

#### Wolf Armor & Cape
- Item ID: mt_wolf_armor
- Category: Armor
- Priority: Essential
- Crafting Station: Forge Lv 3
- Materials: Cape: 6 Wolf Pelt, 4 Silver, 1 Silver Necklace | Armor: 40 Silver, 10 Wolf Pelt
- Summary: Provides permanent passive Freezing resistance, eliminating the need for Frost Resistance Potions.
- Strategy & Tip: Craft the Wolf Fur Cape first to immediately gain frost immunity across mountain ranges.

#### Silver Sword & Draugr Fang
- Item ID: mt_silver_weapons
- Category: Weapons & Tools
- Priority: High
- Crafting Station: Forge Lv 3
- Materials: Silver Sword: 40 Silver, 2 Wood, 5 Leather Scraps, 3 Iron | Draugr Fang: 20 Silver, 10 Ancient Bark, 10 Guck, 2 Deer Hide
- Summary: Silver Sword deals high Spirit holy damage; Draugr Fang bow naturally inflicts poison arrows.
- Strategy & Tip: Draugr Fang glows in dark corridors and remains one of the best ranged weapons in the game.

#### Frostner
- Item ID: mt_frostner
- Category: Weapons & Tools
- Priority: Pro Tip
- Crafting Station: Forge Lv 3
- Materials: 10 Ancient Bark, 30 Silver, 5 Ymir Flesh, 5 Freeze Gland
- Summary: Sledgehammer combining Blunt, Frost, and Spirit damage with tremendous enemy slow.
- Strategy & Tip: Purchase Ymir Flesh from Haldor the Merchant (120 coins each).

#### Obsidian & Frost Arrows
- Item ID: mt_arrows
- Category: Weapons & Tools
- Priority: Essential
- Crafting Station: Workbench Lv 3
- Materials: Obsidian Arrow: 8 Wood, 4 Obsidian, 2 Feathers | Frost Arrow: 8 Wood, 4 Obsidian, 2 Feathers, 1 Freeze Gland (Per 20)
- Summary: Mined from obsidian rock nodes; Frost Arrows slow and stagger fire-aligned and Plains enemies.
- Strategy & Tip: Frost arrows deal devastating damage against Yagluth and Deathsquitoes.

#### Fenris Armor Set
- Item ID: mt_fenris_armor
- Category: Armor
- Priority: High
- Crafting Station: Workbench Lv 2
- Materials: 60 Fenris Hair, 6 Wolf Pelt, 1 Cultist Trophy (Full Set: Hood, Coat, Leggings)
- Summary: Agile garment set granting +9% passive movement speed, +15 Fists skill, and permanent intrinsic Fire Resistance.
- Strategy & Tip: The built-in Fire Resistance negates the need for fire potions when fighting Cultists and offers strong defensive protection against fire-based attacks in subsequent biomes.

#### Flesh Rippers
- Item ID: mt_flesh_rippers
- Category: Weapons & Tools
- Priority: Recommended
- Crafting Station: Forge Lv 3
- Materials: 10 Silver, 15 Fenris Hair, 10 Wolf Claw
- Summary: Fist-mounted bladed weapons that deal rapid slash damage with a 6x stagger multiplier on sneak attacks.
- Strategy & Tip: Benefits directly from the Fist Skill bonus provided by the Fenris Armor set, making it a potent stealth and close-quarters weapon.

#### Crystal Battleaxe
- Item ID: mt_crystal_battleaxe
- Category: Weapons & Tools
- Priority: Situational
- Crafting Station: Forge Lv 3
- Materials: 40 Silver, 30 Ancient Bark, 8 Crystal
- Summary: Two-handed heavy axe infused with Mountain Golem crystals, dealing Slash and Spirit holy damage.
- Strategy & Tip: Features an initial forward jab attack on middle-click that acts as a quick interrupt before executing heavy swings.

### Comfort & Rested Tiers

#### Dragon Bed & Wolf Rug
- Item ID: mt_comfort_tier
- Category: Comfort & Living
- Priority: High
- Crafting Station: Hammer
- Materials: 
  - Wolf Rug (Wolf Pelt x4)
  - Dragon Bed (Fine Wood x40, Deer Hide x7, Wolf Pelt x4, Feathers x10, Iron Nails x15)
- Summary: Dragon Bed replaces basic wood beds and boosts Comfort to 13–14 (20–21 minute Rested duration).
- Strategy & Tip: Dragon beds require substantial roof headroom; ensure tall ceilings.

### Farming, Flora, Taming & Food Recipes

#### Wolf Pit
- Item ID: mt_wolf_taming_breeding
- Category: Farming & Taming
- Priority: High
- Crafting Station: Stone Pit / Enclosure
- Materials: 15 Raw Meat, 50 Stone
- Summary: Trap mountain wolves inside an earthen pit and feed them raw meat to domesticate guard beasts.
- Strategy & Tip: Hunt at night to locate 1-Star or 2-Star wolves. When bred, pups inherit the parent's star rating for 3x combat damage!

#### Onion
- Item ID: mt_onion_agriculture
- Category: Farming & Taming
- Priority: Essential
- Crafting Station: Cultivator on Tilled Soil
- Materials: 3 Onion Seeds (Looted from chests inside ruined stone cabins in the Mountains)
- Summary: Cultivate onions to upgrade the Cauldron and cook top-tier stamina meals.
- Strategy & Tip: Never cook your only onions! Multiply them: 1 Onion -> 3 Seeds via Seed Onion replanting.

#### Butcher's Table & Pots
- Item ID: mt_cauldron_upgrades
- Category: Station & Base
- Priority: Essential
- Crafting Station: Hammer (near Cauldron)
- Materials: Butcher's Table: 2 Silver, 4 Core Wood, 4 Fine Wood | Pots: 5 Iron, 10 Fine Wood
- Summary: Upgrades Cauldron to Level 3, unlocking mountain recipes.

#### Onion Soup
- Item ID: mt_onion_soup
- Category: Food & Mead
- Priority: Essential
- Crafting Station: Cauldron Lv 3
- Materials: 3 Onion
- Stats / Effect: +20 Health, +60 Stamina (25 min)
- Summary: Simple recipe that provides phenomenal stamina pool boost with rapid digestion.
- Strategy & Tip: Ideal meal for high-stamina requirements like mining silver and building.

#### Wolf Skewer
- Item ID: mt_wolf_skewer
- Category: Food & Mead
- Priority: High
- Crafting Station: Cauldron Lv 3
- Materials: 1 Wolf Meat, 2 Mushroom, 1 Onion (Yields 2 servings)
- Stats / Effect: +65 Health, +21 Stamina (25 min)
- Summary: Primary high-health meal for Mountain expeditions.

#### Eyescream
- Item ID: mt_eyescream
- Category: Food & Mead
- Priority: High
- Crafting Station: Cauldron Lv 3
- Materials: 1 Freeze Gland (from Drakes), 3 Greydwarf Eyes
- Stats / Effect: +21 Health, +65 Stamina (25 min)
- Summary: Outstanding stamina snack created from abundant enemy drops.

### Base Raids & World Events

#### Mountain Raids
- Item ID: mt_raid_triggers
- Category: Base Raids & Defense
- Priority: Essential
- Trigger Condition:
  - *"A cold wind blows from the mountains..."*: Active after killing Bonemass. Flying Drakes freeze base animals and shoot ice shards.
  - *"You are being hunted..."*: Random open-world event triggering anywhere. Spawns 10–20 aggressive Wolves surrounding you.
- Defense Strategy: 
  - For Drake base raids: Protect domestic boars under covered roofs so they aren't killed from above.
  - For Hunted event: Jump onto an elevated boulder or climb a ruin immediately and dispatch wolves with the Iron Sledge or Atgeir.

### Boss & Offering

#### Summon & Vanquish Moder
- Item ID: mt_moder_offering
- Category: Boss & Offering
- Priority: Boss Key
- Summoning Station: Mountain High Sacrificial Nest
- Materials / Offering: 3 Dragon Egg (200 weight each; found in mountain Drake nests)
- Summary: Carry 3 Dragon Eggs to Moder's mountaintop altar to summon the dragon and earn Dragon Tears.
- Strategy & Tip: Shoot her with Obsidian and Poison arrows while she is airborne. Moder Forsaken Power guarantees tailwind behind your ship sails for 5 minutes.

---

## 5. Plains

- Biome ID: plains
- Lore: Golden prairies deceptively filled with ruthless Fuling villages, Deathsquitoes, and colossal Lox beasts.
- Forsaken Boss: Yagluth (Fallen Giant Sorcerer)

### Milestones, Stations, Gear & Crafts

#### Artisan Table
- Item ID: pl_artisan_table
- Category: Station & Base
- Priority: Essential
- Crafting Station: Hammer
- Materials: 2 Dragon Tear (Dropped by Moder), 10 Wood
- Summary: Fundamental workstation that unlocks the Blast Furnace, Windmill, and Spinning Wheel.
- Strategy & Tip: Must be placed before any advanced Plains metallurgy or agriculture processing can begin.

#### Blast Furnace
- Item ID: pl_blast_furnace
- Category: Station & Base
- Priority: Essential
- Crafting Station: Hammer (near Artisan Table)
- Materials: 20 Stone, 5 Surtling Core, 10 Iron, 20 Fine Wood
- Summary: Burns Coal to smelt Black Metal Scrap recovered from defeated Fulings.
- Strategy & Tip: Regular smelters cannot smelt black metal; this specialized furnace is required.

#### Spinning Wheel & Linen Thread
- Item ID: pl_spinning_wheel
- Category: Station & Base
- Priority: Essential
- Crafting Station: Hammer (near Artisan Table)
- Materials: 20 Fine Wood, 10 Wood, 5 Iron Nails
- Summary: Spins harvested Flax crops into durable Linen Thread.
- Strategy & Tip: Linen Thread is the core component for high-tier Padded Armor and weapons.

#### Padded Armor
- Item ID: pl_padded_armor
- Category: Armor
- Priority: Essential
- Crafting Station: Forge Lv 5
- Materials: 30 Iron, 60 Linen Thread (Cuirass, Greaves, Helmet)
- Summary: Top-tier metal armor with superior defense and reduced movement penalty compared to iron.
- Strategy & Tip: Requires farming flax on tilled Plains soil.

#### Blackmetal Atgeir & Shield
- Item ID: pl_blackmetal_weapons
- Category: Weapons & Tools
- Priority: High
- Crafting Station: Forge Lv 4
- Materials: Atgeir: 30 Black Metal, 10 Fine Wood, 5 Linen Thread | Shield: 10 Black Metal, 8 Fine Wood, 5 Linen Thread
- Summary: High slash damage and a 360-degree secondary spin attack that staggers groups of Fulings.
- Strategy & Tip: The Atgeir secondary sweep neutralizes circling Fuling horde swarms instantly.

#### Windmill & Stone Oven
- Item ID: pl_windmill_oven
- Category: Station & Base
- Priority: Essential
- Crafting Station: Hammer (near Artisan Table)
- Materials: Windmill: 20 Stone, 30 Wood, 30 Iron Nails | Oven: 20 Stone, 15 Surtling Core, 12 Iron
- Summary: Windmill grinds Barley into Barley Flour; Stone Oven bakes raw dough into bread and pies.
- Strategy & Tip: Keep the windmill in open terrain for faster rotation from coastal winds.

#### Porcupine
- Item ID: pl_porcupine
- Category: Weapons & Tools
- Priority: Essential
- Crafting Station: Forge Lv 4
- Materials: 5 Fine Wood, 20 Iron, 5 Needle, 10 Linen Thread
- Summary: Formidable one-handed mace that deals split Blunt and Pierce damage simultaneously.
- Strategy & Tip: Extremely versatile across mixed enemy types because few creatures resist both blunt force and piercing damage at the same time.

#### Blackmetal Sword & Blackmetal Knife
- Item ID: pl_blackmetal_blades
- Category: Weapons & Tools
- Priority: High
- Crafting Station: Forge Lv 4
- Materials: Sword: 20 Black Metal, 2 Fine Wood, 5 Linen Thread | Knife: 10 Black Metal, 4 Fine Wood, 5 Linen Thread
- Summary: High-tier slashing weapons offering high base damage and critical backstab scaling.
- Strategy & Tip: The Blackmetal Knife features a 6x backstab multiplier and negligible movement penalty, enabling devastating stealth ambushes against roaming Lox.

### Comfort & Rested Tiers

#### Hot Tub & Raven Throne
- Item ID: pl_comfort_tier
- Category: Comfort & Living
- Priority: High
- Crafting Station: Hammer
- Materials: 
  - Hot Tub (Wood x20, Tar x10, Iron x2, Stone x8)
  - Raven Throne (Fine Wood x20, Darkwood x10)
  - Darkwood Chair & Table (Tar x2, Fine Wood x6)
- Summary: Tar harvested from Plains tar pits unlocks Darkwood furniture, elevating Comfort to 17 (24 minute Rested buff).
- Strategy & Tip: Hot Tubs must be kept outdoors or beside vented chimneys and fueled with wood to emit bubbles and warmth.

### Merchants & Key Purchases

#### Hildir & Haldor (Egg)
- Item ID: pl_traders
- Category: Merchants & Trade
- Priority: High
- Key Interactions:
  - **Hildir**: Sells dresses, tunics, hats, and unlocks quest crypts (Sealed Tower, Howling Cavern).
  - **Haldor's Post-Yagluth Stock**: Once Yagluth is slain, Haldor begins stocking **Chicken Eggs** (1500 coins each).
- Strategy & Tip: Buy at least 2 Eggs from Haldor to establish your home base poultry farm.

### Farming, Flora, Taming & Food Recipes

#### Barley & Flax
- Item ID: pl_barley_flax_plantation
- Category: Farming & Taming
- Priority: Essential
- Crafting Station: Cultivator (Plains Dirt Only)
- Materials: 10 Barley, 10 Flax (Looted from Fuling village farm plots)
- Summary: Establish agricultural fields to mass-produce Barley for flour and Flax for armor.
- Strategy & Tip: WARNING: Barley and Flax will ONLY grow when planted within the Plains biome! Planting them in the Meadows or Black Forest will wither them.

#### Lox Saddle
- Item ID: pl_lox_taming_riding
- Category: Farming & Taming
- Priority: High
- Crafting Station: Workbench Lv 1 (Saddle)
- Materials: Saddle: 10 Leather Scraps, 20 Linen Thread, 15 Black Metal | Taming: 20 Cloudberries
- Summary: Tame massive wild Lox with Cloudberries and equip a saddle to ride them as destructive mounts.
- Strategy & Tip: Lox demolish wooden fences; corral them with raised earthen walls made using a Hoe while taming.

#### Chicken & Egg
- Item ID: pl_chicken_farming
- Category: Farming & Taming
- Priority: High
- Crafting Station: Warm Fire Enclosure
- Materials: 2 Egg (Purchased from Haldor after defeating Yagluth for 1500 coins each), 1 Campfire
- Summary: Keep eggs warm near a campfire to hatch chicks; breed chickens for endless feathers, chicken meat, and fresh eggs.
- Strategy & Tip: Build a small chicken coop over a fire pit. Feed adult chickens Barley, Seeds, or Dandelions.

#### Bread
- Item ID: pl_bread_food
- Category: Food & Mead
- Priority: Essential
- Crafting Station: Cauldron Lv 4 -> Stone Oven
- Materials: 10 Barley Flour (Bakes Bread Dough in Stone Oven)
- Stats / Effect: +23 Health, +70 Stamina (25 min)
- Summary: One of the best high-stamina foods in the game.
- Strategy & Tip: Bake multiple loaves in the stone oven once wood coals reach full heat.

#### Blood Pudding & Lox Meat Pie
- Item ID: pl_pies_pudding
- Category: Food & Mead
- Priority: High
- Crafting Station: Cauldron Lv 4 -> Stone Oven
- Materials: 
  - Blood Pudding: 2 Bloodbag, 4 Barley Flour, 2 Thistle (+25 HP, +75 Stamina)
  - Lox Meat Pie: 2 Lox Meat, 2 Cloudberries, 4 Barley Flour (+75 HP, +24 Stamina)
- Summary: The pinnacle of physical stat-boosting meals in the Plains era.
- Strategy & Tip: Pair Lox Meat Pie, Blood Pudding, and Bread for legendary health and stamina pools.

#### Fire Resistance Barley Wine
- Item ID: pl_fire_resist_barley
- Category: Food & Mead
- Priority: Essential
- Crafting Station: Cauldron Lv 4 -> Fermenter
- Materials: 10 Barley, 10 Cloudberries (Yields 6 Potions)
- Stats / Effect: Reduces incoming Fire damage by 50% for 10 minutes
- Summary: Crucial for surviving Yagluth's meteors, flame breath, and Surtlings.
- Strategy & Tip: You will be incinerated during the Yagluth fight without this potion active.

### Base Raids & World Events

#### Plains Raid
- Item ID: pl_raid_triggers
- Category: Base Raids & Defense
- Priority: Essential
- Trigger Condition: Active after defeating Moder.
- Raid Enemies: Massive Fuling squads, Fuling Shamans, and towering 2-Star Berserkers attack.
- Defense Strategy: Berserkers can shatter stone walls quickly. Maintain an outer moat and station tamed 2-Star wolves or Lox guards in courtyard choke points.

### Boss & Offering

#### Summon & Slay Yagluth
- Item ID: pl_yagluth_offering
- Category: Boss & Offering
- Priority: Boss Key
- Summoning Station: Plains Stone Hand Altar
- Materials / Offering: 5 Fuling Totem (Looted from Fuling goblin village altars)
- Summary: Place 5 Fuling Totems into the sacrificial bowls of the giant stone hand to awaken Yagluth.
- Strategy & Tip: Drink Fire Resistance Wine. Use a Silver Sword or Frostner for massive holy Spirit damage. Yields the Torn Spirit to unlock Mistlands crafting. Yagluth Forsaken Power gives resistance to elemental fire, frost, and lightning damage.

---

## 6. Mistlands

- Biome ID: mistlands
- Lore: Jagged crags shrouded in impenetrable magical fog. Home to Dvergr dwarves, Gjalls, and ancient Eitr magic.
- Forsaken Boss: The Queen (Seeker Broodmother)

### Milestones, Stations, Gear & Crafts

#### Wisp Fountain & Wisplight
- Item ID: ml_wisplight
- Category: Weapons & Tools
- Priority: Essential
- Crafting Station: Wisp Fountain
- Materials: Fountain: 1 Torn Spirit (from Yagluth), 10 Stone | Wisplight: 1 Silver, 1 Wisp
- Summary: Catches nocturnal wisps to craft an equipped spirit light that banishes thick fog around the player.
- Strategy & Tip: You cannot navigate the Mistlands or spot jagged cliffs without an active Wisplight equipped.

#### Sap Extractor & Eitr Refinery
- Item ID: ml_sap_extractor_refinery
- Category: Station & Base
- Priority: Essential
- Crafting Station: Hammer
- Materials: Extractor: 1 Dvergr Needle, 5 Black Metal, 10 Yggdrasil Wood | Refinery: 20 Black Marble, 5 Black Core, 10 Yggdrasil Wood
- Summary: Drive extractors into glowing Yggdrasil roots to pump Sap; refine Sap with Soft Tissue into Refined Eitr.
- Strategy & Tip: Unrefined Eitr radiation sparks cause damage to structures; encase refinery walls in Black Marble.

#### Black Forge & Galdr Table
- Item ID: ml_black_forge_galdr
- Category: Station & Base
- Priority: Essential
- Crafting Station: Hammer
- Materials: Black Forge: 10 Black Marble, 10 Yggdrasil Wood, 5 Black Core | Galdr Table: 20 Yggdrasil Wood, 10 Black Marble, 5 Black Core, 5 Refined Eitr
- Summary: Black Forge crafts physical mechanical gear; Galdr Table weaves magical staves and enchanted robes.
- Strategy & Tip: Raid Infested Mines to gather your first 5 to 10 Black Cores.

#### Carapace Armor
- Item ID: ml_carapace_armor
- Category: Armor
- Priority: Essential
- Crafting Station: Black Forge Lv 1
- Materials: 44 Carapace, 6 Scale Hide, 9 Iron, 8 Refined Eitr
- Summary: Heavy chitin plate set forged from Seeker exoskeletons; highest physical armor rating before Ashlands.

#### Eitr-Weave Robes
- Item ID: ml_eitr_weave_armor
- Category: Armor
- Priority: Recommended
- Crafting Station: Galdr Table Lv 1
- Materials: 60 Refined Eitr, 40 Linen Thread, 10 Feather
- Summary: Lightweight mage vestments that boost Eitr Magic Regeneration by +100%.
- Strategy & Tip: Essential set for sorcery playstyles using elemental staves.

#### Staff of Protection & Staff of Embers
- Item ID: ml_magic_staves
- Category: Weapons & Tools
- Priority: Pro Tip
- Crafting Station: Galdr Table Lv 1
- Materials: Staff of Protection: 20 Yggdrasil Wood, 15 Refined Eitr, 4 Blood Clot | Staff of Embers: 20 Yggdrasil Wood, 15 Refined Eitr, 4 Surtling Core
- Summary: Staff of Protection creates a blood shield absorbing 700+ burst damage; Staff of Embers launches explosive fireballs.
- Strategy & Tip: Staff of Protection keeps you and friendly tamed creatures alive in dangerous situations.

#### Feather Cape
- Item ID: ml_feather_cape
- Category: Armor
- Priority: Essential
- Crafting Station: Galdr Table Lv 1
- Materials: 10 Feather, 5 Scale Hide, 20 Refined Eitr
- Summary: Grants slow-fall gliding ability and eliminates all fall damage.
- Strategy & Tip: Completely changes mobility when scaling high Mistlands cliffs and prevents fatal falls.

#### Dead Raiser
- Item ID: ml_dead_raiser
- Category: Weapons & Tools
- Priority: Essential
- Crafting Station: Galdr Table Lv 1
- Materials: 20 Yggdrasil Wood, 15 Refined Eitr, 4 Skeleton Trophy
- Summary: Sacrifices health and Eitr to summon friendly skeleton thralls that engage hostile targets and train your Blood Magic skill.
- Strategy & Tip: Casting the Staff of Protection's barrier over your summoned skeletons shields them from heavy hits, allowing them to remain active longer in battle.

#### Staff of Frost
- Item ID: ml_staff_of_frost
- Category: Weapons & Tools
- Priority: High
- Crafting Station: Galdr Table Lv 1
- Materials: 20 Yggdrasil Wood, 15 Refined Eitr, 10 Freeze Gland
- Summary: Channeled elemental staff that unleashes a rapid, continuous stream of frost shards, applying progressive chill and slow.
- Strategy & Tip: Consumes Eitr steadily while firing. Its rapid hit rate quickly drains an opponent's stagger threshold.

#### Arbalest
- Item ID: ml_arbalest
- Category: Weapons & Tools
- Priority: High
- Crafting Station: Black Forge Lv 1
- Materials: 10 Wood, 8 Iron, 4 Root
- Summary: High-power mechanical ranged weapon firing heavy bolts with high flat damage and flat projectile trajectory.
- Strategy & Tip: The cocking animation is performed beforehand; you can travel with the weapon pre-loaded and fire immediately upon spotting an enemy.

#### Krom & Demolisher
- Item ID: ml_krom_demolisher
- Category: Weapons & Tools
- Priority: Recommended
- Crafting Station: Black Forge Lv 1
- Materials: Krom: 30 Iron, 20 Bronze, 5 Scale Hide | Demolisher: 10 Refined Eitr, 20 Iron, 10 Yggdrasil Wood
- Summary: The game's primary two-handed greatsword and the highest-tier heavy sledgehammer.
- Strategy & Tip: Krom features a lunging thrust on its secondary attack with massive stagger capability, while the Demolisher delivers the widest radial blunt shockwave in its tier.

### Comfort & Rested Tiers

#### Black Marble Throne & Jute Rug
- Item ID: ml_comfort_tier
- Category: Comfort & Living
- Priority: High
- Crafting Station: Hammer
- Materials: 
  - Black Marble Bench & Throne (Black Marble x15)
  - Blue / Red / Yellow Jute Rugs & Curtains (Jute x4, Linen x2)
- Summary: Pushes Comfort to Level 19–20, giving a 26–27 minute Rested duration.

### Farming, Flora, Taming & Food Recipes

#### Magecap & Jotun Puff
- Item ID: ml_magecap_jotunpuffs
- Category: Farming & Taming
- Priority: Essential
- Crafting Station: Cultivator (Mistlands Soil Only)
- Materials: 5 Magecap, 5 Jotun Puff
- Summary: Cultivate glowing mushrooms inside the Mistlands to supply baking and magical brewing.
- Strategy & Tip: Will only grow in Mistlands soil! Build a protected base surrounded by ballistas to protect crops from Gjalls.

#### Mortar & Pestle
- Item ID: ml_mortar_pestle
- Category: Station & Base
- Priority: Essential
- Crafting Station: Hammer (near Cauldron)
- Materials: 4 Black Marble, 2 Fine Wood, 3 Core Wood
- Summary: Upgrades Cauldron to Level 5, unlocking Eitr magic infusions and high-tier baked goods.

#### Yggdrasil Porridge & Stuffed Mushroom
- Item ID: ml_eitr_foods
- Category: Food & Mead
- Priority: Essential (for Mages)
- Crafting Station: Cauldron Lv 5
- Materials: 
  - Yggdrasil Porridge: 4 Sap, 3 Barley, 2 Royal Jelly (+27 HP, +13 Stamina, +80 Eitr)
  - Stuffed Mushroom: 3 Magecap, 1 Turnip, 2 Blood Clot (+25 HP, +75 Eitr)
- Summary: Unlocks and refills your purple Eitr magic bar to cast spells and shields.
- Strategy & Tip: You must eat at least one Eitr meal to cast magic spells.

#### Meat Platter & Honey Glazed Chicken
- Item ID: ml_meat_feast
- Category: Food & Mead
- Priority: High
- Crafting Station: Cauldron Lv 5 -> Stone Oven
- Materials: 
  - Meat Platter: 1 Seeker Meat, 1 Lox Meat, 1 Hare Meat (+80 HP, +26 Stamina)
  - Honey Glazed Chicken: 1 Chicken Meat, 3 Honey, 2 Jotun Puff (+80 HP, +26 Stamina)
- Summary: Elite high-health meals delivering maximum vitality against Seeker Soldiers.

#### Salad
- Item ID: ml_salad_food
- Category: Food & Mead
- Priority: High
- Crafting Station: Cauldron Lv 5
- Materials: 3 Jotun Puff, 3 Onion, 3 Cloudberries (Yields 3 servings)
- Stats / Effect: +15 Health, +80 Stamina (25 min)
- Summary: Best stamina food in the Mistlands; easy to mass-produce with automated farming.

#### Major Healing Mead
- Item ID: ml_mead_major_healing
- Category: Food & Mead
- Priority: Essential
- Crafting Station: Cauldron Lv 5 -> Fermenter
- Materials: 10 Honey, 4 Blood Clot, 5 Royal Jelly (Yields 6 Potions)
- Stats / Effect: Instantly heals +100 Health over 10 seconds
- Summary: Highest tier standard healing potion.

#### Lingering Stamina Mead
- Item ID: ml_mead_lingering_stamina
- Category: Food & Mead
- Priority: High
- Crafting Station: Cauldron Lv 5 -> Fermenter
- Materials: 10 Honey, 10 Jotun Puff, 5 Yellow Mushroom
- Stats / Effect: Increases stamina regeneration by +25% for 5 minutes
- Summary: Excellent potion for long uphill climbing in rugged terrain.

### Base Raids & World Events

#### Mistlands Raids
- Item ID: ml_raid_triggers
- Category: Base Raids & Defense
- Priority: Essential
- Trigger Condition: Active after defeating Yagluth.
- Raid Enemies: Floating Gjalls raining fire bombs and Tik ticks, plus flying Seeker swarms.
- Defense Strategy: 
  - Build automated **Ballistas** loaded with Black Metal bolts or Wooden missiles targeting airborne enemies.
  - Gjall fire bombs bypass standard wooden roofs; roof your base in stone or black marble.

### Boss & Offering

#### Unlock & Slay The Queen
- Item ID: ml_queen_offering
- Category: Boss & Offering
- Priority: Boss Key
- Summoning Station: Infested Citadel Vault Door
- Materials / Offering: 1 Sealbreaker (Crafted at Galdr Table from 9 Sealbreaker Fragments found in Infested Mines)
- Summary: Use the Sealbreaker to open the vault door of the Infested Citadel and defeat The Queen.
- Strategy & Tip: Use the Staff of Protection to absorb brood strikes, and Staff of Embers or Demolisher hammer to clear swarm adds on the stairs. Yields Majestic Carapace and Queen Forsaken Power (faster Eitr regeneration and mining speed).

---

## 7. Ashlands

- Biome ID: ashlands
- Lore: The burning southern edge of the world. Boiling seas, Charred undead legions, and molten Flametal fortress sieges.
- Forsaken Boss: Fader (Lord of the Blighted Flame)

### Milestones, Stations, Gear & Crafts

#### Drakkar
- Item ID: al_drakkar_ship
- Category: Station & Base
- Priority: Essential
- Crafting Station: Workbench near Shore
- Materials: 100 Yggdrasil Wood, 20 Iron, 30 Ceramic Plate, 2 Shield Core
- Summary: The only ship reinforced with ceramic plate that can cross the boiling ocean safely.
- Strategy & Tip: Any normal Karve or Longship will boil, burn, and sink within seconds upon touching boiling seas!

#### Shield Generator
- Item ID: al_shield_generator
- Category: Station & Base
- Priority: Essential
- Crafting Station: Hammer
- Materials: 5 Copper, 5 Iron, 1 Shield Core (Found in Charred Fortresses)
- Summary: Casts an energy dome that shields wooden/stone buildings from cinder storms, volcanic rain, and falling meteors.
- Strategy & Tip: Fuel the generator with Bone Fragments or Charred Bones to maintain defense shields.

#### Flametal Ore
- Item ID: al_flametal_mining
- Category: Weapons & Tools
- Priority: Essential
- Crafting Station: Black Metal Pickaxe in Lava Fields
- Materials: Flametal Ore
- Summary: Ore pillars rising from boiling lava oceans yielding pure Flametal.
- Strategy & Tip: Warning: Flametal spires start sinking into the lava the moment you strike them with a pickaxe—plan your escape grapple!

#### Flametal Armor
- Item ID: al_flametal_armor
- Category: Armor
- Priority: Essential
- Crafting Station: Black Forge Lv 3
- Materials: Heavy: 60 Flametal, 6 Morgen Sinew | Asksvin Set: 12 Asksvin Hide, 20 Flametal
- Summary: Heaviest armor in the game or lightweight Asksvin agility set granting stamina reduction and bow buffs.

#### Battering Ram & Catapult
- Item ID: al_siege_weapons
- Category: Weapons & Tools
- Priority: High
- Crafting Station: Hammer (Battlefield deployment)
- Materials: Catapult: 30 Ashwood, 10 Iron, 10 Flametal | Ram: 20 Ashwood, 10 Iron
- Summary: Break down the outer gates and walls of Charred Fortresses.
- Strategy & Tip: Load catapults with exploding bile bombs or giant boulders to wipe out fortress archers on the ramparts.

#### Slayer & Nidhogg
- Item ID: al_ashlands_weapons
- Category: Weapons & Tools
- Priority: High
- Crafting Station: Black Forge Lv 3
- Materials: Flametal, Bloodstone, Jade, or Iolite gems
- Summary: Weapons can be infused at the forge with Blood (life-steal), Nature (poison roots), or Storm (lightning chain).
- Strategy & Tip: Lightning-infused storm weapons chain damage through dense crowds of Charred warriors.

#### Stone Portal
- Item ID: al_stone_portal
- Category: Station & Base
- Priority: Essential
- Crafting Station: Hammer (near Workbench)
- Materials: 20 Greydwarf Eye, 2 Molten Core, 20 Grausten
- Summary: Arcane stone gate that enables player teleportation while carrying raw ores, metal bars, and non-teleportable items.
- Strategy & Tip: Requires Molten Cores retrieved from Charred Fortresses. Eliminates the necessity of oceanic ore freight for established bases.

#### Basalt Bomb
- Item ID: al_basalt_bomb
- Category: Weapons & Tools
- Priority: Essential
- Crafting Station: Black Forge Lv 1
- Materials: 2 Ashwood, 1 Smoke Puff, 3 Volcanic Ash
- Summary: Throwable device that temporarily cools molten lava into solid, walkable basalt platforms lasting approximately 15 seconds.
- Strategy & Tip: Vital for establishing temporary paths to reaching sinking Flametal spires or safely crossing interior lava hazards.

#### Staff of the Wild & Staff of Fracturing
- Item ID: al_ashlands_staves
- Category: Weapons & Tools
- Priority: High
- Crafting Station: Galdr Table Lv 3
- Materials: Staff of the Wild: 20 Ashwood, 15 Refined Eitr, 4 Jade | Staff of Fracturing: 20 Ashwood, 15 Refined Eitr, 4 Bloodstone
- Summary: High-tier magic staves: Staff of the Wild summons defensive entangling thorn roots; Staff of Fracturing fires cascading clusters of explosive flame.
- Strategy & Tip: Staff of the Wild's summoned roots divert enemy aggression, providing space to cast heavier area-of-effect spells.

### Comfort & Rested Tiers

#### Ashwood Throne & Ceramic Hearth
- Item ID: al_comfort_tier
- Category: Comfort & Living
- Priority: High
- Crafting Station: Hammer
- Materials: 
  - Ashwood Tables & Imperial Thrones (Ashwood x20, Flametal x2)
  - Ceramic Fire Hearth & Brazier (Ceramic Plate x5, Ashwood x10)
- Summary: Reaches the maximum game Comfort cap of 24, delivering up to a 31-minute Rested Buff.
- Strategy & Tip: Long Rested duration is critical during deep Ashlands fortress sieges where building a forward bed is risky.

### Farming, Flora, Taming & Food Recipes

#### Asksvin Saddle
- Item ID: al_asksvin_taming_ranch
- Category: Farming & Taming
- Priority: High
- Crafting Station: Workbench Lv 1 (Asksvin Saddle)
- Materials: Saddle: 15 Fiddlehead, 6 Flametal, 4 Morgen Sinew | Taming: Fiddleheads or Smoke Puffs
- Summary: Tame fast two-legged Asksvin reptiles using local flora, then breed them and saddle them for battle.
- Strategy & Tip: Asksvins lay durable eggs when fed. They are fast war mounts capable of leaping across rocky lava terrain.

#### Fiddlehead & Vineberry
- Item ID: al_ashlands_agriculture
- Category: Farming & Taming
- Priority: High
- Crafting Station: Cultivator (Ashlands Protected Soil)
- Materials: 3 Fiddlehead, 3 Vineberry Seeds
- Summary: Till volcanic Ashlands soil to cultivate exotic Fiddleheads and Vineberry clusters inside protected dome settlements.
- Strategy & Tip: Plant under active Shield Generator fields so firestorms and meteor cinders do not incinerate crops before harvest.

#### Boiling Cauldron & Roaster
- Item ID: al_cauldron_upgrade
- Category: Station & Base
- Priority: Essential
- Crafting Station: Hammer (near Cauldron)
- Materials: 5 Flametal, 10 Ashwood
- Summary: Upgrades Cauldron to Level 6, unlocking volcanic roasted meats and pies.

#### Roasted Asksvin & Piquant Pie
- Item ID: al_ashlands_food
- Category: Food & Mead
- Priority: High
- Crafting Station: Cauldron Lv 6 -> Stone Oven
- Materials: 
  - Roasted Asksvin: 2 Asksvin Meat, 3 Fiddlehead, 2 Smoke Puff (+85 HP, +28 Stamina)
  - Piquant Pie: 2 Asksvin Meat, 2 Vineberry, 4 Barley Flour (+85 HP, +28 Stamina)
  - Scorching Broth: 1 Morgen Heart, 3 Fiddlehead, 2 Bone (+30 HP, +90 Stamina)
- Summary: Extreme top-tier health and stamina meals required to survive endless hordes of Charred soldiers.

#### Lingering Eitr Mead
- Item ID: al_mead_eitr_potion
- Category: Food & Mead
- Priority: Essential (for Mages)
- Crafting Station: Cauldron Lv 6 -> Fermenter
- Materials: 10 Honey, 5 Smoke Puff, 3 Vineberry
- Stats / Effect: Increases Eitr magic regeneration rate by +25% for 5 minutes
- Summary: Enables continuous casting of high-tier sorceries and blood shields without burning out.

### Base Raids & World Events

#### Ashlands Raid
- Item ID: al_raid_triggers
- Category: Base Raids & Defense
- Priority: Essential
- Trigger Condition: Active after defeating The Queen or setting foot in the Ashlands.
- Raid Enemies: Charred Swordsmen, Charred Marksmen, Charred Warlocks, and Morgen abominations.
- Defense Strategy: 
  - All wooden and basic stone structures will quickly burn. Enclose bases with Grausten stone and keep Shield Generators fully charged with bones at all times.

### Boss & Offering

#### Summon & Slay Fader
- Item ID: al_fader_offering
- Category: Boss & Offering
- Priority: Boss Key
- Summoning Station: Ashlands Obsidian Circle Altar
- Materials / Offering: 3 Bell Fragment (Looted from Charred Fortresses), 2 Emerald Gem
- Summary: Place 3 Bell Fragments and 2 Emerald Gems onto the Obsidian Ring Altar to awaken the dragon demon Fader.
- Strategy & Tip: Equip Frost-infused weapons or the Staff of Frost. Stay mobile to dodge scorched magma geysers and green firestorms erupting from the ground. Yields Fader Relic and Fader Forsaken Power (stamina buffs and carrying capacity).
