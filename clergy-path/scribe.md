---
description: >-
  A page detailing the Scribe role within Medieval Discord and their transcribe
  and alm commands.
---

# Scribe ✍️

## Description

When someone joins the Clergy, they will start out as a Scribe. Scribes will spend their day transcribing and translating certain texts for buckles. Additionally, they are ordered around by the higher ranks in order to accomplish menial tasks.

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

_Used to trade coins for piety_

**Piety gain:** `[amount of buckles] / 5`  
**Piety bonus:** `10% for every 4th of your character's total wealth`

{% hint style="info" %}
_The Alm command's piety output scales with the amount of buckles sacrificed. However, this also scales with your overal wealth. Meaning a Scribe donating 100 buckles, while he only has 150 will have a hier conversion ratio than an Archbishop who donates 100, while he has 10k buckles._
{% endhint %}

## In-depth guide:

When joining the clergy, everyone starts off as a Scribe. Scribes are the lowest rank within the Clergy and as such have the least duties. When in the Clergy, people are given access to `r!transcribe` and `r!alm`, allowing them to work for gold, and for piety, respectively. Piety is what the Clergy uses in order to both progress through the ranks, but also as a type of "spiritual currency" expended in order to use some of their exclusive commands. Their work is mostly done within the confines of the Cathedral, where they have a Scriptoria. They command no one, and can offer little religious guidance.

## Piety:

Explain piety here and how to progress through the clergy

