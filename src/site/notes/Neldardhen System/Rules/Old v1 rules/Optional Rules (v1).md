---
{"dg-publish":true,"permalink":"/neldardhen-system/rules/old-v1-rules/optional-rules-v1/"}
---

# Optional Rules (v1)
Optional Rules for [[Neldardhen System/Rules/Old v1 rules/The Neldardhen System (v1)\|The Neldardhen System (v1)]], up to date version of the system can be found here : [[Neldardhen System/Neldar System\|Neldar System]].


## THIS IS AN OUTDATED VERSION see [[Neldardhen System/Rules/Optional Rules\|Optional Rules]]
## Pushing Through

This optional rule allows a creature to spend double of a resource to compensate for an other one.

> Example
> 
> Arinya has 0 resilience but still wants to try to convince the innkeeper to let her eat at a reduced price. A Persuasion task would usually cost 2 resilience, but that would increase her stress level. She however still has almost all of her focus left today.
> 
> So she decide to try the Persuasion task while pushing through, paying 4 focus instead of the 2 resilience.

## Addictions

Some Resourcing Activities might have a risk of #Addiction. The Addiction risk must be defined at the creation of the Activity by the player and the GM.

If a character indulge in such an activity at a frequency equal or above the _risk frequency_ of the activity, they must roll an addiction check.

The player roll **1d100** and if the result is higher than the _addiction threshold_ of the activity - the number of days they have been partaking in the activity, they fail the check and become addicted.

> success if **1d100** < =addiction threshold - number of day

When a character is addicted to an activity, this activity stops being a _Resourcing Activity_ for them (they gain no benefice, but still have to pay the cost) and it becomes an additional _Needs_. (The player and the GM determines together which part of the _Being_ the activity affects if unmet.)

As long as the addiction counts as a _Need_ for a character, that character is considered Addicted and all the Addicted supplementary effects of the activity applies to them.

### Curing an Addiction

Mainly, an addiction is cured by refraining from indulging it for a sufficient amount of time. When a _Needs_ originating from an addiction is not met two days in a row the character is considered in Withdrawal, if the character then manage to not partake in the activity for a period of time equal or greater than the _withdrawal period_ they are considered in remission and the addiction is removed from their _Needs_.

During the withdrawal period the character must make relapse checks under certain circumstances and with more a less of a malus depending on the specific circumstance. The player rolls **1d100** if the result is higher than the addiction potential minus the number of days they have been in withdrawal then they fail the check and must seek out the fastest way to partake in the addictive activity again.

> 1d100 <= addiction threshold + number of day in withdrawal

The circumstances and their modifiers on a relapse check are as follow :

|   |   |   |
|---|---|---|
||**Description**|**Penalty**|
|Periodical check|Some activities ask for a periodical relapse check during withdrawal.|0|
|Idea check|When something in the environment of the character reminds them of the activity|-10|
|Temptation check|When the opportunity to partake in the activity is directly presented to the character.|-30|

Of course the GM and players are encouraged to find creative alternative ways to cure a character's addiction. They might want to try to get rid of their drinking habit by instead going for a walk with a friend or finding a new hobby. As a GM consider giving bonus on the relapse checks when players come up with alternatives way to manage or heal their character's addiction.

## Additional Effect of Damage

Every time a creature take damage of a certain type, there is a chance that it will suffer an additional effect. To resist the additional effect, the player must roll a **1d100** and get a result lower or equal to 80 + their resistance - their vulnerability to that damage type.

> [1d100] <= 80 + damage resistance - damage vulnerability

|   |   |   |
|---|---|---|
|**Mind (reduces focus)**|**Body (reduces endurance)**|**Spirit (reduces resilience)**|
|Confusion (Light / Radiant)<br><br>_Bewildered  <br>_|Piercing / Slashing<br><br>_Bleeding_|Fear<br><br>_Afraid_|
|Oblivion (Dark / Necrotic)<br><br>_Oblivious_|Bludgeoning / Force<br><br>_Broken bones  <br>_|Charm<br><br>_Charmed_|
|Psychic<br><br>_Irrational_|Fire / Heat / Lightning<br><br>_Burning  <br>_|Despair<br><br>_Depressed_|
||Cold / Ice<br><br>_Freezing_|Anxiety<br><br>_Panicked_|
||Acid<br><br>_Corroding_||
|Poison<br><br>_Poisoned_|Poison<br><br>_Poisoned_|Poison<br><br>_Poisoned_|
### #Conditions

|               |                                                                                                                                                                                                                                                                                                                                                |                                                                                                                                                                                                                  |
| ------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Effect**    | **Description  <br>**At the start of their turn the target                                                                                                                                                                                                                                                                                     | **Ends  <br>**                                                                                                                                                                                                   |
| #Bewildered   | Needs to spend **2** focus points or they are too confused to be able to take a decision and don't act on their turn.                                                                                                                                                                                                                          | Regains at least 1 focus point.                                                                                                                                                                                  |
| #Bleeding     | Looses 1 endurance at the start of their turn. (untyped bleeding damage)                                                                                                                                                                                                                                                                       | Takes an action to stop the bleeding with some appropriate materials (bandages).                                                                                                                                 |
| #Afraid       | Needs to spend 2 resilience points or run away from the source of the fear.                                                                                                                                                                                                                                                                    | Regains at least 1 point of resilience.                                                                                                                                                                          |
| #Oblivious    | Needs to spend 1 focus point or forget what they intended to do. If the focus point is not paid, the character does something different than what their initial intentions were.  <br>In addition, if the character is sustaining a spell, they need to spend **1** additional focus point.                                                    | Regains at least 1 focus point.                                                                                                                                                                                  |
| #Broken_Bones | Any movement speed is halved.                                                                                                                                                                                                                                                                                                                  | Regains at least 1 point of endurance.                                                                                                                                                                           |
| #Charmed      | Needs to spend 1 resilience when attacking the source of the charm or take any action against them.                                                                                                                                                                                                                                            | When taking any endurance damage from the source of the charm.                                                                                                                                                   |
| #Irrational   | Rolls **1d4**, different effects apply depending on the result :   <br>**1** : The target can act normally.<br><br>2 : The target must spend **1** focus or do nothing this turn.<br><br>3 : The target must spend **1** focus or take **1d4** resilience damage.<br><br>4 : The target must spend **2** focus or attack the closest creature. | Last until someone else spend a full turn to calm you down.  <br>Can only be done if they witnessed you acting irrationaly (ie. Can only be done after you roll something else than a 1 on your irrational die.) |
| #Burning      | Takes 1d4 fire damage at the start of their turn.                                                                                                                                                                                                                                                                                              | Gets into water / snow or takes an action to extinguish the flames or the effect goes away on its own after 1min.                                                                                                |
| #Depressed    | Needs to spend 1 resilience to do any action other than moving.                                                                                                                                                                                                                                                                                | Regains at least 1 point of resilience.                                                                                                                                                                          |
| #Freezing     | Takes 1d4 cold damage at the start of their turn.                                                                                                                                                                                                                                                                                              | Exposed to warmth or the effect goes away on its own after 1min.                                                                                                                                                 |
| #Panicked     | Needs to spend 2 resilience points or attack the nearest creature, whether or not they are friend or foe.                                                                                                                                                                                                                                      | Takes a full turn to breath and/or ground yourself. (No attack, spell or parry/dodge action possible)                                                                                                            |
| #Corroding    | Takes 1d4 acid damage at the start of their turn.                                                                                                                                                                                                                                                                                              | Takes a full turn to wash off the acid or the effect goes away on its own after 1min.                                                                                                                            |
| #Poisoned     | Any movement speed is halved.  <br>Additionaly, takes 1d4 focus/endurance/resilience depending on the poison type.                                                                                                                                                                                                                             | Drinks/consumes/applies an apropriate antidote. Some poison only last for a certain number of turns.                                                                                                             |
