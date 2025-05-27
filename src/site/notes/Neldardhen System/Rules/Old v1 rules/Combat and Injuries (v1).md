---
{"dg-publish":true,"permalink":"/neldardhen-system/rules/old-v1-rules/combat-and-injuries-v1/"}
---

# Combat and Injuries (v1)
Combat rules for  [[Neldardhen System/Rules/Old v1 rules/The Neldardhen System (v1)\|The Neldardhen System (v1)]] up to date version of the system can be found here : [[Neldardhen System/Neldar System\|Neldar System]].

## THIS IS AN OUTDATED VERSION see [[Neldardhen System/Rules/Combat and Injuries\|Combat and Injuries]]

## Combat

Combat start when a PC or an NPC does any action that the other party considers to be hostile. There are no surprised round, instead if the target is _unaware_ of its attacker, the attack gain a **+30** unaware bonus. If the target tries to parry or dodge, it will also suffer a malus of **-30**.

A target may be _unaware_ of an attacker if it doesn't physically perceive it or if it doesn't think the attacker as potentially hostile.

### Initiative

Before the #initiative is rolled, the #readiness of each creature is calculated. On the VTT the formula is the following.

#### **Readiness**

> Readiness = ((your current focus / your max focus ) + ( your current endurance/ your max endurance) + (your current resilience /your max resilience) ) / 3 )* 100 rounded down.

However it is a daunting calculation to do by hand every time a combat start.

An alternate formula for _readiness_ is to simply add your current focus, endurance and resilience together.

#### **Readiness Alternate**

> Readiness = current focus + current endurance + current resilience

To get your _initiative score_, roll a **1d100** and substract to result from your _readiness_. Also substract your _fatigue_, _exhaustion_ and _stress_ levels.

#### **Initiative score**

> Readiness - [1d100] - fatigue level - exhaustion level - stress level

### Combat Turn 

Combatants take their turn in order of initiative. On their turn a combatant can :

- #Attack
- Cast a spell (see [[Neldardhen System/Rules/Old v1 rules/Spells (v1)\|Spells (v1)]])
- Use a special ability
    

When a defendant is attacked they can choose to #Parry or #Dodge once before their next turn.

**Attack**

An attack is almost like a normal check using the competence appropriate for the weapons the combatant is currently wielding. Additionally, the armour value of the target is substracted from the competence value.

**Dodge**

Similarly, dodging uses the Dodge competence to which the doge malus of any equipped shield or armour is substracted.

**Parry**

Parrying simply uses the competence associated with the weapons the combatant is currently wielding.

### Dual Wielding
#dual_wielding
You can have one weapon in each hand, doing so allows you to attack with both your weapons during you turn however you suffer a penalty of **-30** on both attacks and can not use the specials capacities of your weapons linked to the One Handed Weapon Competence. You can however use the specials capacities of your weapons linked to the Dual Wielding Competence.

### Damage Type
#damage_type
Each damage type affects one part of the _Being_ except for _poison_ who can affect all three.

|   |   |   |
|---|---|---|
|**Mind (reduces focus)**|**Body (reduces endurance)**|**Spirit (reduces resilience)**|
|Confusion|Piercing / Slashing|Fear|
|Oblivion|Bludgeoning / Force|Charm|
|Psychic|Fire / Heat / Lightning|Despair|
||Cold / Freezing|Anxiety|
||Acid||
|Poison|Poison|Poison|

## Injuries
#Injuries, #injury, #Fatigue, #Exhaustion , #Stress { #5a0385}


Every times someone does a task without the necessary resources to pay the cost of said task their _Fatigue_, _Exhaustion_ or _Stress_ level increments by **1**, depending on the part of their _Being_ the competence is associated with.  
It is also the case if a creature takes damage on a resource (_focus_, _endurance_ or _resilience_) which is already at 0.

If the cost of the task or the damage received are greater than **9** then the _Fatigue_, _Exhaustion_ or _Stress_ level increments by **2**, similarly if the cost or damage is greater than **19** then the level increment by **3**, and so on and so forth.

Every time the _Fatigue_, _Exhaustion_ or _Stress_ level of a creature increments it must roll on the corresponding Injury table.

### Temporary Injuries

Temporary injuries either heal with time or are easily healed with a commonly available treatment. They impart some maluses on the creature until they are healed.

### Permanent Injuries

Permanent injuries are either very hard to heal or cannot be healed at all. There maluses are permanent and the creature must learn to live with them the best they can.

### Note on Creatures

To simplify combat, creature don't get injuries. They will instead die as soon as etheir their _focus, endurance_ or _resilience_ reach 0. To compensate for this fact, creature have **3** time their Fubdamental score in resource maximum. (ie. a creature with a Body score of **6** will have **18** _endurance max_ instead of the **12** that a character would get.)

## Death

At any moment, if the _Fatigue_, _Exhaustion_ or _Stress_ level of a character goes above **6** the character dies.

Death is permanent, resurrection magic doesn't exist in this world.