---
description: >-
  A page detailing the Butcher role within Medieval Discord and their butcher
  and tan commands.
---

# Butcher 🥩

## Description:

Butchers are professionals who know how to skin and butcher animals brought by Hunters or by Farmers and turn their corpses into raw meat and materials.

## Mechanics:

{% code title="\#workshops" %}
```javascript
r!butcher <animal name>
```
{% endcode %}

_`<animal name>`_ _- The name of the animal corpse you're trying to butcher._ 

_Examples:_   
_`r!butcher rabbit`  - requires 1x rabbit corpse in your inventory  
`r!butcher cow` - requires 1x slaughtered cow in your inventory_ 

The `r!butcher`command is used by the Butcher in order to successfully gather meat and materials off of hunted or slaughtered animals. You must have the appropriate corpse of the animal in your inventory in order to butcher it for materials and meat.

#### Animal Corpses:

| Animal Corpse | Resulting Resources |
| :--- | :--- |
| **Slaughtered Pig** | _Raw Pork and Leather_ |
| **Slaughtered Cow** | _Raw Beef/Veal and Leather_ |
| **Slaughtered Chicken** | _Raw Chicken and Feathers_ |
| **Slaughtered Sheep** | _Raw Lamb and Wool_ |
| **Deer Corpse** | _Raw Venison and Leather_ |
| **Boar Corpse** | _Raw Boar and Leather_ |
| **Rabbit Corpse** | _Raw Hare and Fur_ |
| **Pheasant Corpse** | _Raw Pheasant and Feathers_ |

#### Additional requirements:

* **Necessary tool:** Slaughter Knife
  * **Location:** Primary slot
  * **Durability cost:** `5 per use`
* **Minimum Stamina:** `50%`
  * **Raw Stamina Cost:** `5` ****
* **XP Reward:** `3`
  * **XP Reward Cooldown:** `24h`
  * **XP Reward While on Cooldown:** _30% chance at 1XP per `r!butcher`_

{% code title="\#workshops" %}
```javascript
r!tan <amount>
```
{% endcode %}

_`<amount>`_ _- The amount of leather from your inventory that you want to tan. Example:_ _`r!tan 4`_

The `r!tan`command is used by the Butcher in order to successfully tan ordinary Leather and turn it into Tanned Leather. Depending on how much Tanned Leather you want, you will have to have the exact number of Leather in your inventory.

#### Additional requirements:

* **Necessary tool:** Slaughter Knife
  * **Location:** Primary slot
  * **Durability cost:** `5 per use`
* **Minimum Stamina:** `25%`
  * **Raw Stamina Cost:** `5`
* **XP Reward:** `1 per Leather tanned`
  * **XP Reward Cooldown:** `24h`
  * **XP Reward While on Cooldown:** _30% chance at 1XP per `r!tan`_

## Relationship with the Market and other Users:

Tanned Leather is used in the Tailoring of many clothes, and in the Cobbling of most footwear. As such, the Butcher can sell their Tanned Leather to Tailors and Cobblers, or alternatively, they can sell directly to the Market, but for a smaller profit.

Regarding the Butcher's main command, it enables them to purchase hunted or slaughtered animals from Farmers and Hunters, at a discount when compared to the Market, and sell the materials and meat they get from their Butchering. Meat is a valuable food item, and can be sold to other characters for a profit, or to the Market directly.

