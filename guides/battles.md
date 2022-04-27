---
cover: ../.gitbook/assets/Screenshot 2022-04-27 103552.jpg
coverY: -28.155642023346303
---

# ⚔ Battles

Fights are automated turn-based. user can set the formation of heroes before a fight. and watch the replay. Also, the user can set the target priority of units in this case unit will attack to highest priority target in its range.&#x20;

Priorities:

* Closest
* Highest HP
* Lowest HP
* Highest Damage

![Army Formation Page](<../.gitbook/assets/image (2).png>)

Units lose HP in battles and it takes time (depending on [Barracks ](broken-reference)level) to recover their HP.

## Damage and Resistance

Armor and Magic Resistance help units to receive less damage.

Here is how Armor affects Physical Damage:

Physic Resistance = 1 - ( 1 / ( Armor / 100 + 1))

Example: A unit with 50 Armor will receive **33%** less physycal Damage:

Physic Resistance = 1 - ( 1 / ( 50 / 100 + 1)) =  **33%**

Magic Resistance has same formula:

Magic Resistance = 1 - ( 1 / ( Magic Resistance / 100 + 1))
