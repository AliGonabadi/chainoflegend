# 🪖 Troops

In [Barracks](buildings.md#barracks), you can train units. Some of the units are not trainable in barracks, but you can find them on [adventures](battles.md).

![Warrior](<../.gitbook/assets/10 (2).png>) ![Archer](../.gitbook/assets/archer.png)

![Lieutenant](../.gitbook/assets/Lieutenant.png) ![Cavalry Knight](../.gitbook/assets/Knight.png)

![Royal Mage](../.gitbook/assets/32.png) ![Catapult](../.gitbook/assets/Catapult.png)

![Dragon](../.gitbook/assets/59.png) ![Goblin](../.gitbook/assets/Goblin.png)

### Base Stats

| Name       | Damage                                                             | Defence                                                    | Resources                         |
| ---------- | ------------------------------------------------------------------ | ---------------------------------------------------------- | --------------------------------- |
| Warrior    | <p>50 Physical Damage<br>Attack Range: 1</p>                       | <p>Armor: 100<br>HP: 200</p>                               | CLEG: 100, Iron: 30               |
| Archer     | <p>30 Physical Damage<br>Attack Range: 2</p>                       | <p>Armor: 30<br>HP: 120</p>                                | CLEG: 80, Iron: 10                |
| Lieutenant | <p>40 Physical Damage<br>Attack Range: 1</p>                       | <p>Armor: 200<br>HP:300<br>+ 10% team armor</p>            | CLEG: 150, Iron: 60               |
| Knight     | <p>80 Physical Damage<br>Attack Range: 1</p>                       | <p>Armor: 150<br>HP: 400</p>                               | CLEG: 300, Iron: 100              |
| Mage       | <p>50 Magical Damage<br>Attack Range: 3,<br>20 Healing to team</p> | <p>Armor: 20<br>HP: 100<br>+ 100 team Magic Resistance</p> | CLEG: 100, Iron 5                 |
| Catapult   | <p>150 AOE** Physical Damage<br>Range: 4</p>                       | <p>Armor: 300<br>HP: 500</p>                               | CLEG: 1000, Iron: 300, Stone: 300 |
| Dragon     | <p>100 AOE Magical Damage<br>Range: 2</p>                          | <p>Armor: 200<br>HP: 500</p>                               | 1% Drops in dungeons              |
| Goblin     | <p>20 Physical Damage<br>Range: 1</p>                              | <p>Armor: 50<br>HP: 200</p>                                | 10% Drops in dungeons             |

\*\* AOE (Area of effect): Deals damage to units within 1 range distance of the target unit.

### Unit Levels

Units earn experience (XP) in battles. When they get enough XP, they will upgrade to the next Level. by upgrading to new levels, units' HP, Attack Damage, and Healing will increase by 50%. For ranged units, they will get 1 more attack range every 3 levels. For example, the table below shows the stats of Archer at each Level.

| Level | XP required | Attack | HP      | Attack Range |
| ----- | ----------- | ------ | ------- | ------------ |
| 1     | -           | 30     | 120 HP  | 2            |
| 2     | 10,000      | 45     | 180 HP  | 2            |
| 3     | 20,000      | 68     | 270 HP  | 2            |
| 4     | 40,000      | 101    | 405 HP  | 3            |
| 5     | 80,000      | 152    | 608 HP  | 3            |
| 6     | 160,000     | 228    | 911 HP  | 3            |
| 7     | 320,000     | 342    | 1367 HP | 4            |
| 8     | 640,000     | 513    | 2050 HP | 4            |
| 9     | 1,280,000   | 769    | 3075 HP | 4            |
| 10    | 2,560,000   | 1153   | 4613 HP | 5            |

The amount of XP that each unit earns in a battle is:\
**Unit's** **Battle XP** = **Total Damage Dealt** + **Total Damage Received** + **Total Healing Done**

### Combining Unit

You can combine 2 units with the same level to get 1 stronger unit with one level higher. The XP of the new unit is equivalent to the sum of previous units.

Example: if you combine two warriors with Level 3 and the first one has 10000 XP and the second one has 15000 XP, then you will get a new warrior with level 4 and 25000 XP
