---
description: >-
  A page detailing the High Inquisitor role within Medieval Discord and their
  investigate command.
---

# High Inquisitor 🔥

## Description:

High Inquisitors are members of the Inquisitor General's close circle. They are experienced members of the Inquisition and are widely known by an alternative name which is usually part of Abrahamic angel tradition. High Inquisitors are more cunning and can investigate an area to pick up clues regarding someone's religion, be those physical clues or eyewitness accounts. 

## Mechanics:

### Investiagte

{% code title="\#any" %}
```javascript
r!investigate
```
{% endcode %}

_Used to force someone into confessing their heresy. If successful, it will give the target the Confessor role. If unsuccessful, will inflict damage to the target equal to half of their max health._

* **Minimum Stamina:** `50%`
  * **Raw Stamina Cost:** `10`
* **Base Reward:** `30-50 piety`

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
_The Confessor role is overt and means that someone was converted to Catholicism, although they may still retain their previous beliefs. If a Confessor is caught again by the Inquisition, they will be executed._
{% endhint %}

## In-depth guide:

Inquisitors are the lowest rank of the Inquisition and as such, they work under the orders of other High Inquisitors, the Inquisitor General, or even the Archbishop of Rosewood. They cannot openly question every character, or arrest people based on OOC \(out of character\) knowledge. They may persecute a character if they have been reported by another PC \(player character\), if they have personally heard/witnessed heresy/paganism in action, or if they are commanded by their superiors. Their job is not to kill the enemies of the Church, but to arrest them. However, no one will look twice if they kill a heretic in trying to defend their own lives. Once they have a prisoner, they may offer them the chance to confess their sins and convert to Catholicism. If they accept or are forced, they will become a Confessor and will be let go. If they refuse to confess, the prisoner will be tried at a Morality Trial.

