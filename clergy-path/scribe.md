---
description: >-
  A page detailing the Scribe role within Medieval Discord and their transcribe
  and alm commands.
---

# Scribe ✍️

## Description

When someone joins the Clergy, they will start out as a Scribe. Scribes will spend their day transcribing and translating certain texts for buckles. Additionally, they are ordered around by the higher ranks in order to accomplish menial tasks. In order to become a Scribe, you will need to talk to the Pastor NPC and request to join. He is also who you talk to in order to rank up within the Clergy.

## Mechanics

{% code title="\#cathedral" %}
```javascript
r!transcribe
```
{% endcode %}

_Used to transcribe/translate texts to or from latin for coin. Using this commands earns you slightly less coin than the basic `work` command due to the `transcribe` command not having an immediate cooldown._

* **Income:** `2-4 coin`
* **Minimum stamina:** `40%`
* **Stamina cost:** `10`

{% code title="\#cathedral" %}
```javascript
r!alm [amount of buckles]
```
{% endcode %}

_Used to trade coins for piety by giving your money to the less fortunate of Rosewood, basically making you seem more pious and charitable._

**Piety gain:** `[amount of buckles] / 5`  
**Piety bonus:** `10% for every 4th of your character's total wealth`

{% hint style="info" %}
_The Alm command's piety output scales with the amount of buckles sacrificed. However, this also scales with your overall wealth. For every 4th of your wealth given, you receive an additional 10% piety._
{% endhint %}

* 25-49% of your wealth gives you a 10% increase on piety
* 50-74% of your wealth gives you a 20% increase on piety
* 75-99% - 30% piety bonus
* 100% - 40% piety bonus

## In-depth guide:

When joining the clergy, everyone starts off as a Scribe. Scribes are the lowest rank within the Clergy and as such have the least duties. When in the Clergy, people are given access to `r!transcribe` and `r!alm`, allowing them to work for gold, and for piety, respectively. Piety is what the Clergy uses in order to both progress through the ranks, but also as a type of "spiritual currency" expended in order to use some of their exclusive commands. Their work is mostly done within the confines of the Cathedral, where they have a Scriptoria. They command no one, and can offer little religious guidance.

## Piety:

Explain piety here and how to progress through the clergy

Explain ratio impact on price of joining each route LIGMA

