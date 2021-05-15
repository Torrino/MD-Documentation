---
description: >-
  A page detailing the Thief role within Medieval Discord and their pickpocket
  command.
---

# Thief 🤏

## Description:

Thieves are part of Rosewood's criminal underworld and make a living by stealing the buckles and items of others. They are the least dangerous criminals in Rosewood.

## Mechanics:

```javascript
r!pickpocket [user] [item name]
```

`r!pickpocket` - _Used to pickpocket NPCs in Rosewood_

`r!pickpocket user` - _Used to pickpocket other characters_

`r!pickpocket user item name` - _Used to steal a specific item from another character's inventory_

#### Additional requirements:

* **Channel:** Any
* **Necessary tool:** None
* **Minimum Stamina:** 10%
  * **Raw Stamina Cost:** 5 ****
* **XP Reward:** 3
  * **XP Reward Cooldown:** 24h
  * **XP Reward While on Cooldown:** 30% chance at 1XP per `r!pickpocket`

## Relationship with the Market and other Users:

Thieves make a living by lifting buckles off of unsuspecting NPCs and other Characters. The easiest command to use, with the least consequences, is `r!pickpocket` without the mention of any user. It will provide the Thief with 10-50 buckles per use, and has the highest success chance out of all of its variations. Additionally, it has a chance of providing the Thief with the "Stolen Goods" item, which can be sold on the Black Market. The punishment for failing this command is a fine of 100 buckles, applied immediately.

While the base pickpocket command is available to everyone, pickpocket that mentions other users are strictly reserved for Thieves. Only mentioning another user means the coin balance of the user mentioned will be targeted, and if successful, will transfer 25% of it to your coin balance, without anyone noticing. Failing this command will cost the Thief their fingers. Each time a Thief is caught using the `r!pickpocket user` command, they will be arrested by the Watch and taken to the \#dungeons, where they will lose one finger. When the fourth attempt fails, a Thief does not lose a fourth finger, instead they are Outlawed and teleported to the \#forest.

Finally, Thieves have the ability to steal a specific item from another user's inventory by mentioning both them and the item. This variant of the pickpocket command is the hardest. If Thieves mention a user and then state an item that is not in their inventory, or is equipped, the command will fail and they will be caught. Failing works the same way as with using just `r!pickpocket user`.

