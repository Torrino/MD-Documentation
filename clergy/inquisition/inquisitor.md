---
description: >-
  A page detailing the Inquisitor role within Medieval Discord and their
  extract-confession command.
---

# Inquisitor ✊

## Description:

Inquisitors are the soldiers of the French Inquisition. The institution is supported by the Roman Church, while its presence is not appreciated by most within the Kingdom. Inquisitors are chosen from among the local clergy and trained in the art of torture and combat in order to fight against the Pope's enemies and any perversions of the Catholic faith. They wear black robes and are feared by many within the Capital. While their main purpose is the extermination of heresy and apostasy, they also enforce the Church's moral laws upon the City of Rosewood.

When you reach the Inquisitor rank, your character will gain the Brother/Sister title.

{% hint style="success" %}
Inquisitors can use the r!arrest command.
{% endhint %}

* **Weekly Paycheck:** `20 coin`
* **Rank-up Rewards:** `Inquisitor Robes, Club`

## Mechanics:

### Extract Confession

{% code title="\#dungeons" %}
```javascript
r!extract-confession <@user>
```
{% endcode %}

_Used to force someone into confessing their heresy. If successful, it will give the target the Confessor role. If unsuccessful, will inflict damage to the target equal to half of their max health._

* **Minimum Stamina:** `50%`
  * **Raw Stamina Cost:** `10`
* **Base Reward:** `40-80 piety`

  * **Reward Cooldown:** 24h

  \*\*\*\*

**Success chance:**

* \(+\)**Strength:** `str`
* \(-\)**Target's Strength:** `str`
* \(+\)**Stamina:** `stm`
* \(-\)**Target's Stamina:** `stm`
* \(+\)**Random dice:** `0-2`

**Success Threshold:**

* _**&lt;1** Fail:_ `Target loses 1/2 max hp`
* _**1-12** Success:_ `Base Reward`

{% hint style="warning" %}
_The Confessor role is overt and means that someone was converted to Catholicism, although they may still retain their previous beliefs. If a Confessor is arrested again by the Inquisition, they will be executed._
{% endhint %}

## In-depth guide:

Inquisitors are the lowest rank of the Inquisition and as such, they work under the orders of other High Inquisitors, the Inquisitor General, or even the Archbishop of Rosewood. They cannot openly question every character, or arrest people based on OOC \(out of character\) knowledge. They may persecute a character if they have been reported by another PC \(player character\), if they have personally heard/witnessed heresy/paganism in action, or if they are commanded by their superiors. Their job is not to kill the enemies of the Church, but to arrest them. However, no one will look twice if they kill a heretic in trying to defend their own lives. Once they have a prisoner, they may offer them the chance to confess their sins and convert to Catholicism. If they accept or are forced, they will become a Confessor and will be let go. If they refuse to confess, the prisoner will be tried at a Morality Trial.

