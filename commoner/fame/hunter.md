---
description: >-
  A page detailing the Hunter role within Medieval Discord and their hunt
  command.
---

# Hunter 🦌

## Description:

Hunters are given a license that allows them to hunt within the Rosewood forest. They use bows and spears to hunt the surrounding wildlife; which includes rabbits, pheasants, deer, and boars.

## Mechanics:

{% code title="\#forest" %}
```javascript
r!hunt <animal name>
```
{% endcode %}

_`<animal name>`_ _- The name of the animal you're trying to hunt. Example:_ _`r!hunt rabbit`_

The `r!hunt`command is used by the Hunter in order to successfully hunt and capture wild game in exchange for using spears and arrows. Depending on the size of the animal, it will require more to successfully hunt down.

#### Animals:

| Animal Target | Requirements |
| :--- | :--- |
| **Rabbit** | _Bow + 1 Arrow_ |
| **Pheasant** | _Bow + 2 Arrows_ |
| **Deer** | _Bow + 3 Arrows_ |
| **Boar** | _Bow + 1 Spear_ |

#### Additional requirements:

* **Necessary tool:** 
  * Bow & Arrows

    * **Location:** Primary slot\(bow\), Inventory\(arrows\) 

    **OR**

  *  Spear
    * **Location:** Primary slot
    * **Durability cost:** `20`
* **Minimum Stamina:** `50%`
  * **Raw Stamina Cost:** `5`
* **XP Reward:** `3`
  * **XP Reward Cooldown:** `24h`
  * **XP Reward While on Cooldown:** _30% chance at 1XP per `r!hunt`_

## Relationship with the Market and other Users:

The Hunter is the only person, besides Knights and Lords, that can hunt in the forest. For their command to work, they need to have an equipped bow/spear \(depending on what they are hunting\). If they are using the bow, they will need a number of arrows in their inventory. If they are using the spear, then it will be used up in the hunt attempt. 

{% hint style="info" %}
_The higher the level, the higher the chances that the spear will be dropped instead of lost upon using the `r!hunt`command._ 
{% endhint %}

As such, the Hunter will often need to replace their weapons and they can do that through the Market \(Arrows\), or through a Weaponsmith \(Spears\).  
  
Once they have successfully caught an animal, Hunters will be given its corpse in the inventory. This valuable material can then be sold directly to the Market, or to a Butcher player for a higher profit. 

