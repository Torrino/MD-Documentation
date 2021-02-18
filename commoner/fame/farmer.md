---
description: A page detailing the Farmer role within Medieval Discord.
---

# Farmer 🐖

## Description:

Farmers make up the foundation of feudal society. They use tools to grow rye and wheat, which they can sell as grain once harvested, various vegetables, and they also practice animal husbandry growing various farm animals which they slaughter seasonally for their meat and materials. They are the peasantry.

## Mechanics:

```javascript
r!harvest
```

The `r!harvest`command is used by Farmers in order to gather grain and vegetables in their inventory.

#### Possible Outcomes:

* **Grain**
* **Cabbage**
* **Lettuce**
* **Onions**
* **Carrots**
* **Field Peas**

#### Additional requirements:

* **Channel:** \#farmlands
* **Necessary tool:** Hoe
  * **Location:** Primary slot
* **Minimum Stamina:** 50%
  * **Raw Stamina Cost:** 10
* **XP Reward:** 3
  * **XP Reward Cooldown:** 24h
  * **XP Reward While on Cooldown:** 1

```javascript
r!slaughter
```

_`<amount>`_ _- The amount of leather from your inventory that you want to tan. Example:_ _`r!tan 4`_

The `r!tan`command is used by the Butcher in order to successfully tan ordinary Leather and turn it into Tanned Leather. Depending on how much Tanned Leather you want, you will have to have the exact number of Leather in your inventory.

#### Additional requirements:

* **Channel:** \#workshops
* **Necessary tool:** Slaughter Knife
  * **Location:** Primary slot
* **Minimum Stamina:** 25%
  * **Raw Stamina Cost:** 5
* **XP Reward:** 1
  * **XP Reward Cooldown:** 24h
  * **XP Reward While on Cooldown:** 1

## Relationship with the Market and other Users:

Tanned Leather is used in the Tailoring of many clothes, and in the Cobbling of most footwear. As such, the Butcher can sell their Tanned Leather to Tailors and Cobblers, or alternatively, they can sell directly to the Market, but for a smaller profit.

Regarding the Butcher's main command, it enables them to purchase hunted or slaughtered animals from Farmers and Hunters, at a discount when compared to the Market, and sell the materials and meat they get from their Butchering. Meat is a valuable food item, and can be sold to other characters for a profit, or to the Market directly.

