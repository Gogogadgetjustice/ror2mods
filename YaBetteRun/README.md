# You Better Run  - Frantic Fungus Beta 

> *"A survivor stepped on some fungus in the void. You are that fungus. You better run."*

The only thing keeping you alive is forward momentum and an army of infected drones and corpses.

---

## The Conceit

As a Void Fungal Clone, you are dying. You are propagating. You are part of nature's plan.

Standing still is a death sentence. Void fungus was meant to sprint. 

Using skills is a death sentence. Fortunately, the field overflows with drones to infect. Let them die for you.

Your spores also take the form of every creature that dies. They too die for you.

Everything dies but maybe you'll die last.

---

## What's the Deal?

The deal is mostly configurable via Risk of Options. Here's the default arrangement. 

### You Are Weaker
Your mycelium form is compromised. Stats are penalised across the board at the start of every stage -
damage reduction, attack speed reduction, health reduction. 

### You Must Keep Running
Every second aren't sprinting costs **20% of your maximum health**. 

### Skills Have a Cost
Using any skill drains health proportional to how many items you're carrying. 

Primary and secondary are difficult to even fire off. Utility and Special tend to be reliable. 

### Everything You Kill Comes Back
After a brief delay, every creature you kill becomes the form of a new fungal minion. Flipped to your team, tinted void-purple. They are also slowly dying. 

A passive health drain consumes them over roughly a minute. 
They take damage for each attack. 
When they die, they don't get back up. They've served their purpose.

We finally answered the question: What if Happiest Mask worked 100% of the time but instead made them fragile purple mushrooms instead of ghosts? 

## Your Starting Kit Is Decent

You start each stage with a small guaranteed drone retinue and 800 gold to acquire more. Broken drones are seeded generously across every map. Equipmentwise you get a free Scanner, His Reassurance, functional coupler, a few fuel cells, and of course weeping fungus,  

At the start of every non-Bazaar stage, th

| Thing | Amount |
|---|---|
| Weeping Fungus (Void) | 1 | 6
| Fuel Cells | 3 (configurable) |
| Starting gold | 800 (configurable) |
| Functional Coupler | 1 (if DLC installed) |
| Scanner (equipment slot 1) | — |
| His Reassurance (equipment slot 2) | — |
| Minimum starting drones | 3 (configurable) |
| Extra broken drones on map | 15 (configurable) |

---

## CFG File // Risk of Options Options

All values are tunable in-game via [Risk of Options](https://thunderstore.io/package/Rune580/Risk_Of_Options/).

| Setting | Default | Description |
|---|---|---|
| Damage Reduction | 80% | How much of player damage is removed |
| Attack Speed Reduction | 70% | How much attack speed is removed |
| Health Reduction | 50% | How much max health is removed |
| Enemy Damage Boost | 15% | How much harder enemies hit |
| Skill Health Cost | 0.5% per item | Health cost per item per skill use |
| Sprint Damage Percent | 20% | Health lost per tick when not sprinting |
| Sprint Damage Interval | 1s | How often the not-sprinting tick fires |
| Extra Drones Per Stage | 15 | Extra broken drones spawned at stage start |
| Starting Money | 800 | Gold given at stage start |
| Minimum Drones Per Player | 3 | Guaranteed drones at stage start |
| Starting Equipment Charges | 3 | Fuel Cells given at stage start |
| Drone Health Drain Multiplier | 50% | How aggressively healing depletes drone max health |

Colours for player overlays, drone overlays, and resurrected minions are all separately configurable as `R,G,B,A` strings (values 0–1).
https://gogogadgetjustice.github.io/unity-color-picker.html - You can use this thing I made to find the code for the Unity color. 

---

## Dependencies

- [BepInEx](https://thunderstore.io/package/bbepis/BepInExPack/)
- [R2API](https://thunderstore.io/package/tristanmcpherson/R2API/) (core + Networking + RecalculateStats)
- [Risk of Options](https://thunderstore.io/package/Rune580/Risk_Of_Options/)
---  

I nearly called this Wolf Fart, after the Lycoperdon mushroom whose name derived from Greek roots lycos (wolf) and perdon (to break wind).

