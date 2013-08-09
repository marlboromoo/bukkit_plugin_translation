= Intro =

Ancient powers of true light and darkness have awoken. Through the use of altars these powers tap into our dimension, in recent times the darkness has gained a stronger connection. It spreads as an infectious disease that only the altars of light and holy water can cure. Those who embrace the dark disease are granted the powerful curse of Vampirism.

Anyone can become a vampire, but do you want to? During daytime vampires cower from sunlight. During the night the humans reach for their holy water and wooden stakes as the vampires roam the lands with inhuman strength, speed and levitation-powers. Driven by their endless bloodlust, they devour all living in their way.

= The Vampire Dining Table =

Name		Blood/Food/Hunger
Enderdragon	70x
Giant		25x
Mooshroom	10x
Player		5x	
Villager	5x
Cow		4x
Pig		3x
Sheep		3x
Wolf		3x
Ocelot		3x
Squid		2x
Spider		2x
Cavespider	2x
Chicken		1x
Silverfish	1x

= Commands and Hotkeys =

 * /v ?,h,help [page=1]
 * /v s,show [player=you] Show player info
 * /v b,bloodlust [bool=flip] use bloodlust (SpoutCraft Hotkey “V”)
 * /v i,intend [bool=flip] use intent to infect
 * /v n,nightvision [bool=flip] use nightvision
 * /v o,offer <playername> [amount=4.0] offer blood to someone
 * /v a,accept accept blood offer
 * /v shriek shriek (SpoutCraft Hotkey “X”)
 * /v v,version Show plugin version and information.
 * /v l,list [page=1] list vampires and infected
 * /v set set player attributes

= Vampires… =

 * are destroyed by sunlight.
 * are extremely vulnerable to wood and holy water.
 * spreads the dark disease through combat and their own blood.
 * kill and drink blood instead of eating food.
 * regenerate health quickly at the expense of food-level.
 * won’t be attacked by monsters unless the vampire attacks first.
 * take no fall- or suffocation-damage.
 * have stationary food level unless in bloodlust mode.
 * move faster, jump higher and damage more with bloodlust.

= The Dark Disease =

The dark disease is not to be confused with Vampirism. The dark disease will make you sicker and sicker until you finally turn into a vampire. This will take around 3 in-game day-night cycles. Use /v s,show to see your current state of disease.

To contract the disease you can use an altar of darkness. You also risk infection if you accept a blood offer from a vampire or engage in close-combat with one. Vampires may decide if they intend to infect during combat or not. For each attack (from either you or the vampire) the risk is 5% with intent and an 0.3% without (/v i,intend).

To stop the disease you can use an altar of light or holy water (sparkling splash potion). The disease will not reset if you log off or die.

To cure actual vampirism you need to use an altar of light.

= Offer and Accept Blood =

Anyone (both vampires and humans) can use the commands /v o,offer and /v a,accept to trade blood. What you actually trade is food-level. This way vampires can have “blood-slaves”. It’s also a way to transfer the dark disease. You can at most offer 20 (all your blood). If you offer all 20 the infection risk is 100%. If you offer 4 the risk is 20% etc.

Drinking blood from others is visible to those within 7 block. If you want to keep your vampirism secret you must thus avoid drinking blood in crowded areas.

Finally we suggest you try drinking blood from yourself. Try /v offer yourOwnPlayerName

= The Bloodlust =

Bloodlust is the main vampire advantage. Close combat damage is increased by 20% but most importantly the vampires run with double speed and jump six times as high with increased air maneuvering.

Vampires usually have a stationary foodlevel. In bloodlust their foodlevel will however drop on a time basis. After roughly 1min the vampire is too hungry/thirsty to use bloodlust.

A vampire in bloodlust emits a smoke-trail while moving. Apart from being a nice effect it’s a way to distinguish vampires from flyhackers.

The Nightvision

Vampires can use night vision any time they want. It can be toggled on and off using the command “/v n”. The night vision is free and does not consume food level. It works just like the potion effect but you don’t emit particles. This way others can’t see you are using nightvision.

= The Sun =

The Sun is the main vampire dis-advantage. When vampires are exposed to sunlight their body temperature will increase fast. Vampires simply can’t stand sunlight.

Temperature	Effects
20%		Nausea
30%		Nausea, Weakness
50%		Nausea, Weakness, Slow
80%		Nausea, Weakness, Slow, Blindness
90%		Nausea, Weakness, Slow, Blindness, Burn

Vampires can see their temperature and irradiation/exposure level at any time using the command /v s,show. In full cover the irradiation/exposure is -20 which means the vampire is cooling down. Irradiation is calculated using this formula:
irradiation/exposure = sun * terrain * armor – 20

Sun is calculated as a value between 0 and 100. It depends on the time of the day and if there is rain.

Terrain is calculated as a value between 0 and 1 by looking at the blocks above the player all the way up to the roof of the world. This means we pretend the sun is always directly above the player. Most blocks are completely solid and will block all sun. But it would for example take 4 leaf-blocks to block all sun. See all the values here.

Armor is calculated as a value between 0 and 0.4. Each armor piece grants 0.125. The type of armor does not matter. This means armor never can block irradiation completely. It can however slow down the heatup process.

= Stakes and Holy Water =

A bloodlusting vampire is a very strong opponent. They are however very weak against wooden stakes and holy water. Rely on these two tools and you may protect yourself as the sun goes down.

...........
Wooden stakes deal three times the damage of a diamond-sword to vampires. All of these items are considered wooden stakes: Stick, Wooden Sword, Wooden Axe, Wooden Pickaxe, Wooden Spade, Wooden Hoe, Sign, Torch, Redstone Torch, Fence and Fence Gate.

.
Holy water is a splash potion. The ingredients required are 1 Water Bottle and 1 Lapis Lazuli Dye. Hold the water bottle and right-click an altar of light to create the splash potion. In you inventory this potion is called “Sparkling Potion” and seems to have no effects though it actually has two.

The potion cures those infected with the dark disease. It will not cure full vampires though. A vampire hit with holy water will suffer a 70% temperature increase. This means vampire will go blind and catch fire if they are hit by two holy water potions. The only damage taken is the one from burning but as the vampire is in no condition to fight the best way of action in that case is to flee before someone gets close with a wooden stake.

= The Altars of Darkness and Light =

To use an altar you right-click the main block (gold or lapis lazuli). Altars can be built by anyone. The altars are made of the main block and some secondary blocks. The vampire plugin make dead bushes and web easily obtainable. A web drops a web on destruction and a bush drops a bush.

== Altar of Darkness ==

.

This is just an example. Your altar can have a different design

A Gold Block with these blocks within a 10 block radius:

30 Obsidian
5 Web
5 Dead Bush (Go to a desert. Find a dead bush. Hit it with your fist.)
2 Diamond Block
The altar of darkness can be used to contract the dark disease that after a while will turn you into a vampire (you will not turn instantly). To activate the altar you need these items:
1 Mushroom Soup,10 Bone, 10 Sulphur / Gunpowder, 10 Redstone

== Altar of Light ==

.

This is just an example. Your altar can have a different design

A Lapis Lazuli Block with these blocks within a 10 block radius:

 * 30 Glowstone
 * 5 Yellow Flower
 * 5 Red Rose
 * 2 Diamond Block

The altar of light removes the dark disease for free. To cure yourself from vampirism you need these items: 1 Water Bucket,1 Diamond, 20 Sugar, 20 Wheat. To create holy water you need these items: 1 Water Bottle, 1 Lapis Lazuli Dye and you can’t be a vampire. Only non vampires can create holy water.
