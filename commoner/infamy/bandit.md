---
description: A page detailing the Bandit role within Medieval Discord.
---

# Bandit 🤺

## Description:

Bandits stalk the roads of the Kingdom and prey upon the weak and unprotected. Their most common target for robberies are merchants, but they won't shy away from attacking anyone if an opportunity presents itself.

## Mechanics:

```javascript
r!rob
```

`r!rob` - _Used to steal from NPCs, be that items or buckles._

#### Additional requirements:

* **Channel:** \#forest or \#walls
* **Necessary tool:** Any weapon
  * **Location:** Primary slot
* **Minimum Stamina:** 50%
  * **Raw Stamina Cost:** 10
* **XP Reward:** 3
  * **XP Reward Cooldown:** 24h
  * **XP Reward While on Cooldown:** 30% chance at 1XP per `r!rob`

## Relationship with the Market and other Users:

Bandits are highly sought-after criminals, as the punishment for their crimes is usually death. They make a living by robbing NPC merchants, but may also rob other Characters if they believe the profit will be larger.

{% hint style="info" %}
_Bandits deal more damage against other characters with the Merchant role. Additionally, they have a buff when using the `r!run` command during combat._
{% endhint %}

If the `r!rob` command is successful, they will receive a number of buckles that scales with their experience. Additionally, there is also a small chance that a successful rob will drop a random local shipment, which can then be opened and its contents sold.

If the command fails, the Bandit will be pursued by the Watch, and will have a chance to escape or be caught. If they escape, they will avoid punishment. However, if they are caught, they will be arrested and tried for banditry.

