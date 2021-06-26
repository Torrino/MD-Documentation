---
description: >-
  A page detailing the Thief role within Medieval Discord and their pickpocket
  command.
---

# Thief 🤏

## _Description_

Thieves are part of Rosewood's criminal underworld and make a living by stealing the buckles and items of others. They are the least dangerous criminals in Rosewood.

## _Command_

```javascript
r!pickpocket [@user] [item name]
```

`r!pickpocket` - _Used to pickpocket NPCs in Rosewood\(anyone\)_

`r!pickpocket @user` - _Used to pickpocket other characters\(anyone\)_

`r!pickpocket @user item name` - _Used to steal a specific item from another character's inventory \(Thieves only\)_

#### Additional requirements:

* **Channel:** Any
* **Necessary tool:** None
* **Minimum Stamina:** `10%`
  * **Raw Stamina Cost:** `5`
* **XP Reward:** `3`
  * **XP Reward Cooldown:** `24h`
  * **XP Reward While on Cooldown:** _30% chance at 1XP per `r!pickpocket`_

## _Pickpocketing an Item \(Only for THIEVES\)_

```javascript
r!pickpocket @user item
```

* **Base success** **chance**: `20%`, `30%`, `50%`, `70%`, `80%` \(increase with level\)
* **Positive modifiers:**
  * _Stamina point ****`+S%`_
  * _Hooded robes ****`+10%`_
* **Negative modifiers:**
  * _Gambeson \| Chainmail `-10%`_
  * _Brigandine \| Rosewoodian plate `-25%`_
  * _@user's Intelligence `-I%`_

### _**Success**_

**Reward:** `chosen item`  
_Thieves have the ability to steal a specific item from another user's inventory by mentioning them and typing the full name of the item \(with spaces\). This variant of the `pickpocket` command is the **hardest.**_

{% hint style="success" %}
_If the chosen item has `durability`and there are multiple instances of that item in the @user's inventory, then the exact item will be picked at random._
{% endhint %}

### _**Failure**_

_**Effect:**_ `Loss of finger`

_Failing this command will cost the Thief their fingers. Each time a Thief is caught using the `r!pickpocket user` command, they will be arrested by the Watch and taken to the \#dungeons, where they will lose one finger. When the fourth attempt fails, a Thief does not lose a fourth finger, instead they are Outlawed and teleported to the \#forest._

Mechanic where thieves have three strikes before they get outlawed. If a person is caught trying to pickpocket another player then they lose their finger. If they lose a finger three times, then they are given the **Outlaw role** and are outlawed in Rosewood.

{% hint style="danger" %}
_If the item exists but **isn't** the @user's inventory, the command **fails!**_
{% endhint %}

{% hint style="info" %}
_If you make a typo while typing the name of the item, meaning, the item with that exact name **doesn't** exist in MD then the command is **cancelled**, meaning, nothing happens._
{% endhint %}

## _Relationship with the Market and other Users_

Thieves make a living by lifting buckles off of unsuspecting NPCs and other Characters. The easiest command to use, with the least consequences, is `r!pickpocket` without the mention of any user. It will provide the Thief with 10-50 buckles per use, and has the highest success chance out of all of its variations. Additionally, it has a chance of providing the Thief with the "Stolen Goods" item, which can be sold on the Black Market. The punishment for failing this command is a fine of 100 buckles, applied immediately.

Only mentioning another user means the coin balance of the user mentioned will be targeted, and if successful, will transfer 25% of it to your coin balance, without anyone noticing. 

