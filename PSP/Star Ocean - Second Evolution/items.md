Iventory Memory Layout
----------------------

Iventory starts at 0x09201CC0


Each item uses 4 bytes.

* Bits [0:10] are the item type.
    * Up to 2048 items possible [0:0x7FF]
* Bits [11:15] is the quantity.
    * Normally game doesn't allow more than 20 (0x14) of one item.
    * However, you can hack up to 31 (0x1f) of one item without running out of bits.
* Bits [16:31] are unknown.

Can verify sorted item list by entering the Sell menu at a shop. Note that unsalable items will not show up in this list however.

Item Table
-------------

Special tags:

* (Nothing) means the there will be no item.
* (Cannot be sold)
* (Dummied Item) usually only visible in Sell menu at a shop. Does nothing.

List of Items:

* 0x0: (Nothing)
* 0x1: Magic Canvas
* 0x2: Primavera
* 0x3: The Scream
* 0x4: Starry Night
* 0x5: Death of Socrates
* 0x6: Portrait A
* 0x7: Portrait B
* 0x8: Portrait C
* 0x9: Portrait G
* 0xA: Portrait I
* 0xB: Portrait D
* 0xC: Portrait F
* 0xD: Portrait J
* 0xE: Portrait H
* 0xF: Portrait E
* 0x10: Portrait L
* 0x11: Portrait K
* 0x12: Doodles
* 0x13: Victory Card
* 0x14: Critical Card
* 0x15: Revival Card
* 0x16: Wealth Card
* 0x17: Treasure Card
* 0x18: Experience Card
* 0x19: Faerie Card
* 0x1A: Benefaction Card
* 0x1B: Silence Card
* 0x1C: Hexagram Card
* 0x1D: Magic Rock (Not present in Inventory)
* 0x1E: Wierd Shape
* 0x1F: 3-way Ball (Not present in Inventory)
* 0x20: Hyper Ball (Not present in Inventory)
* 0x21: Rubber Ball (Not present in Inventory)
* 0x22: Angel Statuette
* 0x23: Faerie Statuette
* 0x24: Goddess Statuette
* 0x25: Illusion Doll
* 0x26: Warrior Idol
* 0x27: Veda Idol
* 0x28: Goodie Box
* 0x29: Jack-in-the-Box
* 0x2A: Mirror of Knowledge
* 0x2B: Magic Clay
* 0x2C: Feather Pen
* 0x2D: Piano
* 0x2E: Cembalo
* 0x2F: Mystical Shamisen
* 0x30: Silver Trumpet
* 0x31: Harmonica
* 0x32: Lyre
* 0x33: Violin
* 0x34: Pipe Organ
* 0x35: Conductor Baton
* 0x36: Spectacles
* 0x37: Magic Gumdrop
* 0x38: Moonlight
* 0x39: Silver Idol
* 0x3A: Gold Idol
* 0x3B: Lavish Doll
* 0x3C: Wierd Doll
* 0x3D: Sacrificial Doll
* 0x3E: Silver Pendant
* 0x3F: Storm Ring
* 0x40: Green Bracelet
* 0x41: Froghead
* 0x42: Glass Slippers
* 0x43: Regeneration Ring
* 0x44: Ugly Accessory
* 0x45: Lunar Charm
* 0x46: Amulet of Antivenom
* 0x47: Amulet of Freedom
* 0x48: Amulet of Flexibility
* 0x49: Purple Amulet
* 0x4A: Mystic Amulet
* 0x4B: Necklace
* 0x4C: Chain of Might
* 0x4D: Intimidation Pendant
* 0x4E: Leaf Pendant
* 0x4F: Ruby Pendant
* 0x50: Star Necklace
* 0x51: Faerie Tear
* 0x52: Velvet Tear
* 0x53: Silver Amulet
* 0x54: Blue Talisman
* 0x55: Talisman
* 0x56: Lunar Talisman
* 0x57: Gold Ring
* 0x58: Princess Ring
* 0x59: Ring of Healing
* 0x5A: Ring of Mental Power
* 0x5B: Ring of Wisdom
* 0x5C: Heavy Ring
* 0x5D: Weight Ring
* 0x5E: Hefty Ring
* 0x5F: Ring of Might
* 0x60: Ring of Quietude (Dummied Item)
* 0x61: Ring of Insanity
* 0x62: Ring of Infinity
* 0x63: Ring of the Accursed
* 0x64: Ring of Avoidance
* 0x65: Ring of Fusion
* 0x66: Ring of Absorbsion
* 0x67: Ring of Happiness
* 0x68: Ring of Sadness
* 0x69: Ring of Trust
* 0x6A: Stardust Ring
* 0x6B: Hammer Charm
* 0x6C: Mallet Charm
* 0x6D: Ring of Lightspeed
* 0x6E: Meteor Ring
* 0x6F: Ring of Lunacy
* 0x70: Berserker Ring
* 0x71: Shield Ring
* 0x72: Ring of Resistance
* 0x73: Aqua Ring
* 0x74: Flare Ring
* 0x75: Ring of the General
* 0x76: Prism Ring
* 0x77: Holy Ring
* 0x78: Emerald Ring
* 0x79: Water Ring
* 0x7A: Fire Ring
* 0x7B: Thunder Ring
* 0x7C: Faerie Ring
* 0x7D: Onyx Earring
* 0x7E: Gold Earring
* 0x7F: Ruby Earring
* 0x80: Blood Earring
* 0x81: Shield Earring
* 0x82: Breeze Earring
* 0x83: Earring of the Winds
* 0x84: Lame Earring
* 0x85: Gale Earring
* 0x86: Hefty Earring
* 0x87: Emerald Earring
* 0x88: Star Earring
* 0x89: Earring of Magnetism
* 0x8A: Earring of Readiness
* 0x8B: Earring of Frenzy
* 0x8C: Silver Cross
* 0x8D: Gold Cross
* 0x8E: Magic Cross
* 0x8F: Silver Ring
* 0x90: Light Cross
* 0x91: Shadow Cross
* 0x92: Silver Barrette
* 0x93: Angelic Headband
* 0x94: Gold Bracelet
* 0x95: Anklet
* 0x96: Bracelet of Gambling
* 0x97: Ricochet Bracelet
* 0x98: Dream Bracelet
* 0x99: Dream Bracelet
* 0x9A: Glittering Earring
* 0x9B: Moon Earring
* 0x9C: Mind Ring
* 0x9D: Foot Insignia
* 0x9E: Silver Earring
* 0x9F: Mist Insignia
* 0xA0: Crown
* 0xA1: Dream Crown
* 0xA2: Moon Tiara
* 0xA3: Paper Scrap
* 0xA4: Fountain Pen
* 0xA5: Beret
* 0xA6: Drawing Poses (Learn Sketching)
* 0xA7: Dish of the Day (Learn Recipe)
* 0xA8: Musicology (Learn Music Knowledge)

* 0xB7: Friends of the Woods (Learn Animal Training)
* 0xB8: All About Herbs (Learn Herbology)

* 0xC7: Advanced Symbology (Leon Book)
* 0xC8: The Blood-Paved Road (Dias Book)
* 0xC9: Alien Cultures (Opera Book)
* 0xCA: S.O. Confidential (Bowman Book)

* 0xD7: I Won't Look Back (Ashton Book)
* 0xD8: A Girl's Secrets (Precis Book)
* 0xD9: Nature's Will (Noel Book)

* 0xE8: Smoke Oil

* 0xF8: Potion of Epiphany

* 0x108: Violent Pill

* 0x116: Medicine Bottle
* 0x117: Seafood
* 0x118: Fruit

* 0x127: Chawanmushi

* 0x137: Egg Fried Rice

* 0x147: Radish in Miso Paste (Dummied Item)
* 0x148: (Nothing)
* 0x149: Vegetable Stir-Fry
* 0x14A: (Nothing)
* 0x14B: (Nothing)
* 0x14C: Yoghurt Salad
* 0x14D: (Nothing)
* 0x14E: Egg-Wrapped Sushi (Dummied Item)
* 0x14F: Plain Omelet
* 0x150: (Nothing)
* 0x151: Tuna Sashimi
* 0x152: (Nothing)
* 0x153: Seaweed Miso Soup
* 0x154: Shumai Dumplings
* 0x155: Amoeba Soup
* 0x156: Godslayer (Cannot be sold)
* 0x157: Knuckles of Hope (Cannot be sold)
* 0x158: Shrimp Gratin
* 0x159: Fine Tuna Sashimi
* 0x15A: Salmon Omelet
* 0x15B: Shrimp Pilaf
* 0x15C: Combo Link (Cannot be sold)
* 0x15D: Cola
* 0x15E: Sunset Island
* 0x15F: Crazy Cow
* 0x160: Bloody Driver
* 0x161: Fire in the Sky
* 0x162: Mango Lassi
* 0x163: Banana Frappe
* 0x164: Bean Paste Bun
* 0x165: Demon Sword Levantine (Cannot be sold)
* 0x166: Radish Miso Soup
* 0x167: Gruel
* 0x168: Rice Cake
* 0x169: Hotcake
* 0x16A: Holy Sword Farewell (Cannot be sold)
* 0x16B: Ooze Cocktail
* 0x16C: Seraphic Garb
* 0x16D: Shrimp Doria
* 0x16E: Rice Omelet
* 0x16F: Mindhealer
* 0x170: Flat Soda
* 0x171: Luxury Grape Juice
* 0x172: Orange Sherbet
* 0x173: Banana Crepe
* 0x174: Lime Cooler
* 0x175: Pickled Plum
* 0x176: Strawberry Bavarois
* 0x177: Apple Crepe
* 0x178: White Peach Sherbet
* 0x179: Rose de Mai
* 0x17A: Orange Gratin
* 0x17B: Bitter Juice
* 0x17C: Steamed Bun
* 0x17D: Gyoza Dumplings
* 0x17E: Beef Croquette
* 0x17F: Chicken Shish Kebab
* 0x180: Jambalaya
* 0x181: Archangel's Bracelet
* 0x182: Chicken Doria
* 0x183: Steak
* 0x184: Rabbit Risotto
* 0x185: Lamb Burger Steak
* 0x186: Gelatin Steak
* 0x187: Tasteless Stew
* 0x188: Phantom Slayer (Cannot be sold)
* 0x189: Bunny Shoes
* 0x18A: Pumpkin Croquette
* 0x18B: Cream of Corn Soup
* 0x18C: Scumbag Slayer
* 0x18D: Spring Roll
* 0x18E: Carrot Juice
* 0x18F: Cabbage Roll
* 0x190: Pumpkin Spring Roll
* 0x191: Vegetable Juice
* 0x192: Green Cream Soup
* 0x193: Wilted Salad
* 0x194: Fried Egg
* 0x195: Slimy Gelatin
* 0x196: Fruit Milk
* 0x197: Yoghurt
* 0x198: Egg Sandwich
* 0x199: Chocolate Crepe
* 0x19A: Egg on Bacon
* 0x19B: Vanilla Ice Cream
* 0x19C: Shortcake
* 0x19D: Flan
* 0x19E: Macaroni Gratin
* 0x19F: Bitter Cake
* 0x1A0: Old Milk
* 0x1A1: Nectar
* 0x1A2: Pet Food
* 0x1A3: Iron
* 0x1A4: Gold
* 0x1A5: Silver
* 0x1A6: Moonstone
* 0x1A7: Orichalcum
* 0x1A8: Meteorite
* 0x1A9: Mithril
* 0x1AA: Damascus
* 0x1AB: Rune Metal
* 0x1AC: Pebbles
* 0x1AD: Green Beryl
* 0x1AE: Sapphire
* 0x1AF: Ruby
* 0x1B0: Star Ruby
* 0x1B1: Crystal
* 0x1B2: Philospher's Stone
* 0x1B3: Diamond
* 0x1B4: Rainbow Diamond
* 0x1B5: Thief's Glove
* 0x1B6: Blurry Photo
* 0x1B7: Magic Camera
* 0x1B8: Magic Film
* 0x1B9: Music Box
* 0x1BA: Element Analyzer
* 0x1BB: Graphic Tool
* 0x1BC: Magician's Glove
* 0x1BD: RIRICA
* 0x1BE: Deadly Poison Bomb
* 0x1BF: Daze Bomb
* 0x1C0: Mind Bomb
* 0x1C1: Flare Bomb
* 0x1C2: 4-way Bomb
* 0x1C3: Assualt Bomb
* 0x1C4: Defense Bomb
* 0x1C5: Megabomb
* 0x1C6: (Nothing)
* 0x1C7: Nuclear Bomb
* 0x1C8: Mechanic's Toolbox
* 0x1C9: Music Editor
* 0x1CA: Triangle Flask
* 0x1CB: Magical Rasp
* 0x1CC: Soldering Iron
* 0x1CD: Survival Kit
* 0x1CE: Word Processor
* 0x1CF: Sterile Glove
* 0x1D0: (Nothing)
* 0x1D1: Plasma Generator (Precis KM: Forcefield, Cannot be sold)
* 0x1D2: Megalauncher (Precis KM: Superbeam, Cannot be sold)
* 0x1D3: White Upgrade (Opera KM: Healing Star, Cannot be sold)
* 0x1D4: Black Upgrade (Opera KM: Refraction Beam, Cannot be sold)
* 0x1D5: Green Upgrade (Opera KM: Hyperlauncher, Cannot be sold)
* 0x1D6: Smith's Hammer
* 0x1D7: Strange Potion
* 0x1D8: Ladyfingers
* 0x1D9: Premium Paper
* 0x1DA: Bounced Check
* 0x1DB: Item Order
* 0x1DC: Forged Bill
* 0x1DD: Forged Check
* 0x1DE: Forged Document
* 0x1DF: Secret Account
* 0x1E0: Stock Certificate
* 0x1E1: Counterfeit Medal
* 0x1E2: Seizure Warrant
* 0x1E3: Contract
* 0x1E4: Health Insurance
* 0x1E5: Dull Blade
* 0x1E6: Stringy Sword
* 0x1E7: Golden Fang
* 0x1E8: Silver Fang
* 0x1E9: Broad Sword
* 0x1EA: Longsword
* 0x1EB: Sinclair
* 0x1EC: Flame Sword
* 0x1ED: Walloon Sword
* 0x1EE: Guthgwine
* 0x1EF: Farcutter
* 0x1F0: Deadly Edge
* 0x1F1: Veil Piercer
* 0x1F2: Metalcrusher
* 0x1F3: Searing Sword
* 0x1F4: Soulbreaker
* 0x1F5: Sword of Marvels
* 0x1F6: Blade of Minos
* 0x1F7: Saad Blade
* 0x1F8: Force Sword
* 0x1F9: Famed Sword Vainslay
* 0x1FA: Silvance
* 0x1FB: Aeterna
* 0x1FC: Aurora Blade
* 0x1FD: Keen Kitchen Knife
* 0x1FE: Bastard Sword
* 0x1FF: Baselard

* 0x20C: Swords of Deflection
* 0x20D: Twin Fury

* 0x21D: Cestus

* 0x22D: Burst of Fire

* 0x23D: Silver Moon

* 0x242: Ruby Rod
* 0x243: Thunderclap Rod
* 0x244: Scrap Iron
* 0x245: Booster Clip
* 0x246: Wave Clip
* 0x247: Black Clip
* 0x248: White Clip
* 0x249: Seventh Ray
* 0x24A: X Clip
* 0x24B: Magic Clip
* 0x24C: Alpha Clip
* 0x24D: Burst Clip
* 0x24E: Energy Clip
* 0x24F: Beta Clip
* 0x250: Gamma Clip
* 0x251: Pulse Clip
* 0x252: Robot Puncher

* 0x25C: Burning Puncher

* 0x26C: Spark Whip

* 0x27C: Encyclopedia

* 0x28C: Heat Gun
* 0x28D: Electron Gun
* 0x28E: Psychic Gun
* 0x28F: Leather Helmet
* 0x290: Wierd Helmet
* 0x291: Wierd Cap
* 0x292: Padded Helmet
* 0x293: Magical Cap
* 0x294: Open Helmet
* 0x295: Iron Helmet
* 0x296: Rune Cap
* 0x297: Plate Helmet
* 0x298: Tiara of Isis
* 0x299: Steel Helmet
* 0x29A: Tiaria of the Arc
* 0x29B: Wizard's Cap
* 0x29C: Mithril Helmet
* 0x29D: Sylvian Helmet
* 0x29E: Dueling Helmet
* 0x29F: Hermit's Cap
* 0x2A0: Helmet of Odin
* 0x2A1: Bloody Helmet
* 0x2A2: Dragon's Ribbon
* 0x2A3: Wyrm King's Ribbon
* 0x2A4: Holey Armor

* 0x2AD: Amber Robe
* 0x2AE: Evening Gown
* 0x2AF: Plate Armor
* 0x2B0: Silver Robe
* 0x2B1: Eagle's Shawl
* 0x2B2: Robe of Deception
* 0x2B3: Mithril Coat
* 0x2B4: Holy Cloak
* 0x2B5: Mithril Dress
* 0x2B6: Cloak of the Stars
* 0x2B7: Armor of the Arc
* 0x2B8: Steel Armor
* 0x2B9: Battle Suit
* 0x2BA: Wizard's Armor
* 0x2BB: Robe of Ishtar
* 0x2BC: Blessed Plate Armor
* 0x2BD: Mithril Mesh
* 0x2BE: Magic Armor
* 0x2BF: Sylvian Mail
* 0x2C0: Valiant Mail
* 0x2C1: Dueling Suit
* 0x2C2: Reflecting Plate
* 0x2C3: Chaos Mail
* 0x2C4: Bloody Armor
* 0x2C5: Wooden Shield

* 0x2CD: Crested Shield
* 0x2CE: Hand of Kali
* 0x2CF: Star Guard
* 0x2D0: Guantlet of Air
* 0x2D1: Shield of the Arc
* 0x2D2: Shield of Algol
* 0x2D3: Mithril Shield
* 0x2D4: Valiant Shield
* 0x2D5: Valkyrie's Bracelet
* 0x2D6: Barrier Shield
* 0x2D7: Shield of Athena
* 0x2D8: Sandals
* 0x2D9: Leather Greaves
* 0x2DA: Boots
* 0x2DB: Boots of Happiness
* 0x2DC: Suede Boots
* 0x2DD: Iron Greaves
* 0x2DE: Wierd Boots
* 0x2DF: Leather Boots
* 0x2E0: Plate Greaves
* 0x2E1: High Heels
* 0x2E2: Laced Boots
* 0x2E3: Silver Greaves
* 0x2E4: Wierd Shoes
* 0x2E5: Pin Heels
* 0x2E6: Santa's Boots
* 0x2E7: Mud Shoes (Cannot be sold)
* 0x2E8: Valkyrie's Boots
* 0x2E9: Safety Shoes
* 0x2F0: Star Greaves
* 0x2F1: Neumann Boots (Might be dummied out)
* 0x2F2: Cindarella Glass
* 0x2F3: Aquaberries
* 0x2F4: Blackberries
* 0x2F5: Blueberries
* 0x2F6: Strawberry Jam
* 0x2F7: Raspberry Jam
* 0x2F8: Apple Jam
* 0x2F9: Aloe Jam
* 0x2FA (Nothing)
* 0x2FB: tri-Emblem (Good one Purchased from Santa)
* 0x2FC: Rice Croquette
* 0x2FD: Soy Milk
* 0x2FE: Stinky Bean Cake
* 0x2FF: Pickled Vegetables
* 0x300: Rice-Bran Pickles
* 0x301: Carrot Ice Cream
* 0x302: Stone Cure
* 0x303: Sprite's Bracelet
* 0x304: Pixie's Bracelet
* 0x305: Fortune's Bracelet
* 0x306: Rotting Sashimi
* 0x307: Jewel of the Frog
* 0x308: ?HERB (???)
* 0x309: ?HERB (???)
* 0x30A: ?HERB (???)
* 0x30B: ?HERB (???)
* 0x30C: ?HERB (???)
* 0x30D: ?HERB (???)
* 0x30E: Organic Vegetables
* 0x30F: Sirloin
* 0x310: Top-Quality Tuna
* 0x311: Marenne Oysters
* 0x312: Magic rice
* 0x313: Creamy Cheese
* 0x314: Sweet Fruit
* 0x315: Gelatinous Slime
* 0x316: Wobbly Slime
* 0x317: Milky Potage
* 0x318: Special Stir-Fry
* 0x319: Magical Salad
* 0x31A: Golden Stew
* 0x31B: Chicken Filet
* 0x32B: Luscious Gratin
* 0x33B: ?MINERAL (???)
* 0x34B: ?WEAPON (???)
* 0x35B: ?WEAPON (???)
* 0x36B: ?WEAPON (???)
* 0x37B: ?ARMOR (???)
* 0x38B: ?ARMOR (???)
* 0x39B: ?JEWELRY (???)
* 0x3AB: ?JEWELRY (???)
* 0x3BB: ?ITEM (???)
* 0x3CB: ?FOOD (???)
* 0x3DB: ?FOOD (???)
* 0x3EB: ?FOOD (???)
* 0x3FB: ?FOOD (???)
* 0x3FF: ?MACHINE (???)
* 0x400: Ice Blades
* 0x401: Assassin's Sickle

* 0x404: Vorpal Sword

* 0x408: Shockwave Sword

* 0x40F: Claymore + 2
* 0x410: Magnifying Blade

* 0x420: Slayer Sword

* 0x430: Flamberge

* 0x440: Long Spear

* 0x450: Violent Handy Stick

* 0x460: Dwarven Guardyy

* 0x470: Elven Powder

* 0x480: Cream Soda

* 0x490: Book of Phrophecy 5 (Dummied Item)

* 0x4A0: Astral Ring (Cannot be sold)

* 0x4B0: Umai-bo Candy 14

* 0x4C0: Granadilla Juice

* 0x4D0: Plum Rice Ball

* 0x4E0: Golden Stew (Dummied Item)

* 0x4F0: Agar Drink

* 0x500: Saucy Rice

* 0x510: Survival for Dummies (Dias Book, Cannot be used)
* 0x511: Men of Sweat (Dias Book, Dummied Item)
* 0x512: The Innocent Knight (Leon Book, Cannot be used)
* 0x513: Taming of the Prude (Leon Book, Dummied Item)
* 0x514: Tales of a Young Boy (Ashton Book, Cannot be used)
* 0x515: White Bird of Bliss (Ashton Book, Dummied Item)
* 0x516: This Cruel World (Opera Book, Cannot be used)
* 0x517: Miss Peal (Opera Book, Dummied Item)
* 0x518: Little Kitty Lost (Chisato Book, Cannot be used)
* 0x519: Tie Me Up! (Chisato Book, Dummied Item)
* 0x51A: The Seven Veterans (Ernest Book, Cannot be used)
* 0x51B: Book of Seven Rings (Ernest Book, Dummied Item)
* 0x51C: Suisuiden (Noel Book, Cannot be used)
* 0x51D: Hakkenden (Noel Book, Dummied Item)
* 0x51E: Assassin's Manual (A book written by DUMMY, Cannot be used)
* 0x51F: The Birds' Wings (A book written by DUMMY, Dummied Item)
* 0x520: How to Use Your boss (Welch Book, Cannot be used)
* 0x521: Hey, I'm Talking! (Welch Book, Dummied Item)
* 0x522: Ultimate Ramen

* 0x532: Butter-fried Oysters

* 0x533: Csss (Dummied Item)

* 0x543: Flame Orb (Cannot be sold)

* 0x562: (Nothing)

* 0x572: (Nothing)

