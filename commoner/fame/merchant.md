---
description: >-
  A page detailing the Merchant role within Medieval Discord and their shipment
  mechanic.
---

# Merchant 📦

## Description:

Merchants walk the roads of the Kingdom and of the known World in order to buy and sell exotic and luxury goods in City Markets. They are possibly the most affluent members of the Citizenry.

## Mechanics:

{% code title="\#any outside settlement" %}
```javascript
r!shipment
```
{% endcode %}

The `r!shipment` command is used by the Merchant in order to obtain a Shipment within their inventory which can then be opened with the `r!open-shipment`. 

#### Local Shipment Types:

* **Common Shipment** `[Obtainable in Frey]` _\(may contain lemons, oranges, pears, apples, plums, cheese, beer, ale, wine, spirit, dyes, salt, grain\)_
* **Uncommon Shipment** \[Obtainable in Forechester\]

  _\(may contain crystals, lemons, oranges, pares, apples, plums, cheese, beer, ale, wine, spirit, dyes, salt, grain\)_

* **Rare Shipment** `[Obtainable in Shelby]` _\(may contain crystals, lemons, oranges, pares, apples, plums, wine, spirit, dyes, salt, grain\)_
* **Unique Shipment** `[Obtainable in Kington]` _\(may contain crystals, lemons, oranges, pares, apples, plums, wine, spirit, dyes, salt, grain\)_
* **Extraordinary Shipment** `[Obtainable in Kington]` ****_\(may contain crystals, lemons, oranges, plums, wine, dyes, salt, silk, spices, grain\)_

#### Exotic Shipment Types:

* **Venice Shipment** `[Obtainable in Venice]` _\(may contain silk, spices, salt, amethyst, perfumes, paper, olive oil, vintage wine\)_
* **Constantinople Shipment** `[Obtainable in Constantinople]`

  _\(may contain silk, spices, salt, amethyst, pearl, paper, written book, olive oil, vintage wine, incense\)_

* **Alexandria Shipment** `[Obtainable in Alexandria]` _\(may contain silk, spices, salt, emerald, pearl, written book, perfumes, dried murex, vintage wine, incense\)_
* **Baghdad Shipment** `[Obtainable in Baghdad]` _\(may contain silk, spices, salt, emerald, ruby, written book, lapis lazuli, dried murex, vintage wine, damascus steel bar\)_
* **Cambay Shipment** `[Obtainable in Cambay]` ****_\(may contain silk, spices, salt, emerald, ruby, pearl, written book, lapis lazuli, vintage wine, ivory\)_
* **Cathay Shipment** `[Obtainable in Cathay]` ****_\(may contain silk, spices, salt, emerald, ruby, pearl, crystals, written book, paper, vintage wine, ivory, tilsent\)_

#### Additional info:

* **XP Reward:** `3`
  * **XP Reward Cooldown:** `24h`
  * **XP Reward While on Cooldown:** _30% chance at 1XP per `r!shipment`_

## Relationship with the Market and other Users:

The Merchant has direct access to the most valuable items one could legally acquire through the Market. Merchants must make use of the `r!travel` command in order to acquire different types of shipments which contain varying items, from grain to tilsent. Once they obtain one or more shipments they are free to return to Rosewood and open them in order to discover the contents and then sell them directly to the Market or to other characters.

