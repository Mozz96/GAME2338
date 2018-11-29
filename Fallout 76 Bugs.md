# Fallout 76 Bugs:

**1. Picking up large amounts of items (i.e. grenades), items will not appear in inventory while still being counted towards weight limit, causing "invisible weight":**

Types of testing (Box type and other type): Black Box, Playtesting

Reasoning: Something like this would've been caught during gameplay, where one may be stashing lots of recovery items or grenades for use during combat or to stash later. 

Steps to identify and test: First, I would gather (or spawn, if in a playtesting environment) a large quantity of an item in the world space. I would then collect all items at once and check my inventory menu to see if said items are in there. Afterwards, I would gather a second large amount in a single stack, collecting it to see if there is a certain limit the game itself is able to handle at present.

**2. Collecting all Holotapes in the "Follow the Overseer's Journey" side quest doesn't cause said quest to finish:**

Types of testing (Box type and other type): Black Box, Functional Testing

Reasoning: The quest component should see that all objectives have been completed, marking the quest as complete as it should with all other quests.

Steps to identify and test: In order to identify the bug, I would follow the questline as normal, checking if the quest completes as intended. In order to test the bug, I would try listening to the final Holotape in different locations, the spot it was found, etc.

**3. Getting hit with the Cryolator causes a movement penalty lasting 2 hours:**

Types of testing (Box type and other type): Black Box, Balance Testing

Reasoning: The slowing effect can seriously throw off the balance of combat, whether it be in a PvP situation or a griefer slowing down another player that may be fighting a tough enemy. 

Steps to identify and test: Have one player shoot another with the Cryolator until they are inflicted with said movement penalty, then checking to see how long said penalty will last.

**4. When charging Tesla Rifle to fire, getting hit with ranged or melee attacks that do more than 1 type of damage causes the game to crash:**

Types of testing (Box type and other type): Black Box, Playtesting 

Reasoning: While this bug seems to only be affecting one weapon presently, this presents lots of potential problems to the players that may be using said weapon, and it should have been caught during playtesting.       

Steps to identify and test: Firstly, I would equip the Tesla Rifle, finding an enemy that deal 2 types of damage (i.e melee and fire-based). I would then engage in combat with it, charging the rifle as it attacks. In order to test the bug, I would try testing out different Tesla Rifles, with differing conditions and attributes.

**5. Legendary Items that have the "90% reduced weight" attribute have the wrong weight values:**

Types of testing (Box type and other type): White Box, Usability Testing 

Reasoning: The code/values that coincide with this particular attribute are off, causing the actual weight values to be different than what it should be in-game, which can result in rendering a player overencumbered through no fault of their own. 

Steps to identify and test: First, I would find or spawn an item with the attribute listed above in a testing environment, noting it's weight and properties before adding it into my inventory. I then would check my current weight limit, checking to see if the noted values and the values in my inventory are the same.
