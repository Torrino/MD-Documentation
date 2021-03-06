---
description: >-
  A page detailing the Farmer role within Medieval Discord and their harvest and
  slaughter commands.
---

# Farmer 🐖

## Description:

Farmers make up the foundation of feudal society. They use tools to grow rye and wheat, which they can sell as grain once harvested, various vegetables, and they also practice animal husbandry growing various farm animals which they slaughter seasonally for their meat and materials. They are the peasantry.

## Mechanics

### Harvest

{% code title="\#farmlands" %}
```javascript
r!harvest
```
{% endcode %}

The `r!harvest`command is used by Farmers in order to gather grain and vegetables in their inventory.

#### Possible Outcomes:

* **`Grain`**
* **`Cabbage`**
* **`Lettuce`**
* **`Onions`**
* **`Carrots`**
* **`Field Peas`**

#### Additional requirements:

* **Necessary tool:** Hoe
  * **Location:** Primary slot
  * **Durability cost:** `5`
* **Minimum Stamina:** `50%`
  * **Raw Stamina Cost:** `10`
* **XP Reward:** `3`
  * **XP Reward Cooldown:** `24h`
  * **XP Reward While on Cooldown:** _30% chance at 1XP per `harvest`_

### Slaughter

{% code title="\#farmlands" %}
```javascript
r!slaughter <animal name>
```
{% endcode %}

The `r!slaughter`command is used by Farmers to gather Slaughtered Farm Animals, which can then be sold to the Market or to Butcher characters.

**Possible Outcomes:**

* **`Slaughtered Cow`**
* **`Slaughtered Pig`**
* **`Slaughtered Chicken`**
* **`Slaughtered Sheep`**

#### Additional requirements:

* **Necessary tool:** Slaughter Knife
  * **Location:** Primary slot
  * **Durability cost:** `5`
* **Minimum Stamina:** `50%`
  * **Raw Stamina Cost:** `15`
* **XP Reward:** `3`
  * **XP Reward Cooldown:** `24h`
  * **XP Reward While on Cooldown:** _30% chance at 1XP per `r!slaughter`_

## Relationship with the Market and other Users:

Farmers are the primary source of food for the Market and for other Characters. Since they are the only role that can produce locally-grown food, they have a pivotal role to play in Rosewood. Plus the added fact that they can slaughter their farm animals means they are also the primary source of meat, and other animal-originated materials like leather and feathers.  
  
Farmers have the choice to sell their produce directly to the Market, or to other characters for a notable profit. Ideally, a Farmer would sell their vegetables and grain to any characters, while they should sell Slaughtered Animals to Butchers.

