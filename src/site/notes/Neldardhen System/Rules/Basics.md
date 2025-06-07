---
{"dg-publish":true,"permalink":"/neldardhen-system/rules/basics/"}
---

# Basics
Rrules for the [[Neldardhen System/Neldar System\|Neldar System]].

Every character and creature in the game has three Fundamental values representing their Being: Mind, Body and Spirit.

For each of those, there are three Attributes.

### Attributes

|                       | **Mind**           | **Body**       | **Spirit**             |
| --------------------- | ------------------ | -------------- | ---------------------- |
| Active / Raw Strength | Memory / Knowledge | Physic         | Charisma               |
| Reactive / Finesse    | Wits               | Reaction Speed | Manipulation / Insight |
| Defensive             | Composure          | Pain Tolerance | Volition               |

The value of an attribute is a type of die (d4, d6, d8, d10, d12). An increase in the die category (from d6 -> d8) can be bought with points at character creation or after a level up (see [[Neldardhen System/Character Creation/Character Creation - Points Distribution\|Character Creation - Points Distribution]])
## Resources
Each task will cost a creature one of three resources. _focus_ which is the resource of the _Mind_, _endurance_, the resource of the _Body_ and _resilience_, the resource of the _Spirit_. The maximum of each resource cannot be higher than three times its corresponding Fundamental Value.

## Skills{ #75d8a0}

There are 18 skills separated in three catagories linked to Mind, Body and Spirit.

| **Mind**              | **Body**    | **Spirit**      |
| --------------------- | ----------- | --------------- |
| Arcane Magic          | Athletics   | Animal Affinity |
| Rhetoric / Linguistic | Craft       | Deception       |
| Culture / History     | Fighting    | Intimidation    |
| Investigation         | Performance | Persuasion      |
| Research / Sciences   | Stealth     | Insight/Empathy |
| Mysticism / Occultism | Thievery    | Raw Magic       |

Three of the skills are Defense skills, **Aracane Magic**, **Fighting** and **Raw Magic** are taken into account when defending against attacks or damage affecting the corresponding part of the being. 

Each skill as a rank - ranks can be bought with points at character creation or after a level up (see [[Neldardhen System/Character Creation/Character Creation - Points Distribution\|Character Creation - Points Distribution]]).
A rank in a skill cannot be higher than the score in the Fundamental value (Mind, Body or Spirit).

> If Ayrina has a Mind score of 4 and Spirit score of 2, she can buy up to 4 ranks in Arcane Magic, but only 2 ranks in Persuasion.

### Skill Checks
A skill check is done by combining a skill with an attribute. The rank of the skill determine the number of dice that can be bought and the attribute determine the type of the dice.

The first die is always free, each additional die costs **1** point of resource (either _focus_, _endurance_ or _resilience_ depending on the skill used)
Additionally, if the skill check is linked to a speciality of the character, then the character gains 1 additional free die for the check.

> Example :
> 
> Arinya wants to translate a stone tablet written in Ancient Laugsuil.
> The GM asks for a roll of Linguistic on Memory / Knowledge.
> She has a **rank 2** in Rhetoric / Linguistic and **d6** in Memory / Knowledge.
> She has a **specialisation** in _Ancient Laugsuil_.
> 
> She gets **2d6** for free thanks to **1** free die and her specialisation. However, the GM told her that the check would be quite hard. She decides to spend **2** _focus_ points to get **2** additional dice.
> 
>She can now roll **4d6** at the cost of **2** _focus_ 

#### Specialities
A character can choose a free specialisation when they reach rank **3** in a particular skill.

Additionally, some skills let you choose a speciality at ranks **1**. Those are Rhetoric/Linguistic, Culture/History, Research/Science, Athletics, Fighting and Performance.

#### Pushing past your limits
If a character has a rank high enough in a skill to buy more dice, but not enough resources to do so, they can choose to buy dice of a category less (d6 -> d4) for twice as much of one other resource.

>From our example before, let's say that Arinya has only **1** point of _focus_ left. She would not be able to buy the **2** additional dice.
>She could buy **1** additional **d6** for **1** _focus_, then decide to spend **2** points of _resilience_ to buy an additional **d4**.
>
>She now would be able to roll **3d6 + 1d4** for **1** _focus_ and **2** _resilience_.

### Helping on a skill check
Some skill checks can benefit from the help of one or more other characters.
To help on a skill checks, every character that want to help must make a check with the same skill and attribute as the main check, but with a set Difficulty of **10**.
For every success, the person making the main check will be able to re-roll a die in there pool.
If the roll for helping was a critical success, a die can be re-roll until it is no longer a 1.

### Fatigue, Exhaustion and Stress
It is still possible to do a task with no resources left, but this will instead increment the _Fatigue_, _Exhaustion_ or _Stress_ level and prompt a roll on the corresponding Injury table. (see [[Neldardhen System/Rules/Old v1 rules/Combat and Injuries (v1)#^5a0385\|Injuries]]).

It is also the case if a creature takes damage on a resource (_focus_, _endurance_ or _resilience_) which is already at 0.

If the cost of the task or the damage received is greater than **9** then the _Fatigue_, _Exhaustion_ or _Stress_ level increments by **2**, similarly if the cost or damage is greater than **19** then the level increment by **3**, and so on and so forth.

The _Fatigue_, _Exhaustion_ or _Stress_ level is subtracted from any roll made with the corresponding resources.

> Example 
> 
> Arinya has a _Stress_ level of **2**. She wants to make a Deception check, lying to her friends pretending that everything is ok.
> 
> She assembles her pool of dice and get to roll **2d6**, but she will have to subtract her _Stress_ level from the total.
> 
> She rolls **2d6 - 2** ;  she gets a **3** and a **4** on the dice for a total of  **3 + 4 - 2 = 5** !


### Critical Success and Failure
A critical success occurs when the total of the dice is double or more than the set difficulty.
A critical failure on the other hand happens when the total roll is less than half of the set difficulty.

## Perception Checks
Perception checks are always free. They use dice pools determined by the species of the character. (see [[Neldardhen System/Character Creation/Character Creation - Species#^443e3a\| Character Creation - Species - Senses]])

>[!gm] GM : Setting a difficulty
 To set the difficulty of a skill, you can use this table :
>
| Difficulty | **score** | notes                                                                                                                                                                                                                                                  |
| ---------- | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Trivial    | 2+        | Garanteed succeess when either having a specialty or buying 1 die.                                                                                                                                                                                     |
| Very Easy  | 4+        |                                                                                                                                                                                                                                                        |
| Easy       | 6+        |                                                                                                                                                                                                                                                        |
| Medium     | 8+        | Roughly 50% chance of succees with 2d6 or 2d8 (at least 1 buy should be bought, signifying that a bit of effort must be put into the task. Alternatively, can sometimes be done effortlessly - without buyind dice - if the character has a specialty) |
| Hard       | 12+       | Required to have at least 1 rank in the skill to succeed (or be very lucky with a d12 attribute)                                                                                                                                                       |
| Very Hard  | 16+       |                                                                                                                                                                                                                                                        |
| Impossible | 20+       |                                                                                                                                                                                                                                                        |

