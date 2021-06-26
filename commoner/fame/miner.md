---
description: >-
  A page detailing the Miner role within Medieval Discord and their mine
  command.
---

# Miner ⛏️

## Description:

A Miner is someone who supplies Rosewood with valuable materials like stone, iron, silver, and gold. Their work is tiresome but provides the occasional reward since the Rosewood mines also have precious crystals within them.

## Mechanics:

{% code title="\#mines" %}
```javascript
r!mine
```
{% endcode %}

The `r!mine` command is used by the Miner in order to obtain stone and ore from the Rosewood Mines. 

#### Possible Outcomes:

| Ore | Amount | Drop Rate |
| :--- | :--- | :--- |
| Stone | Between 1 and 5 | 90% |
| Iron Ore | Between 1 and 3 | 50% |
| Silver Ore | Between 1 and 3 | 10% |
| Gold Ore | Between 1 and 3 | 5% |
| Crystals | 1 | 1% |

#### Additional requirements:

* **Necessary tool:** Pickaxe
  * **Location:** Primary slot
  * **Durability cost**: `5`
* **Minimum Stamina:** `50%`
  * **Raw Stamina Cost:** `15`
* **XP Reward:** `3`
  * **XP Reward Cooldown:** `24h`
  * **XP Reward While on Cooldown:** _30% chance at 1XP per `r!mine`_

## Relationship with the Market and other Users:

Miners gather stone and ores from the Mines in Rosewood. These ores can be then sold to Blacksmiths, Goldsmiths, Weaponsmiths, and Armorsmiths, and this is of course at a higher profit than if they were to be sold to the Market directly.

