---
description: >-
  A page detailing the Deacon role within Medieval Discord and their convert and
  preach commands.
---

# Deacon 📿

## Description

The Deacon is the first rank of the threefold Christian ministry and is the governor of their respective diaconate, the smallest subdivision of the Catholic authority. Within larger settlements like Rosewood, a single church might have multiple diaconates, all presided by a Deacon, in service to their Parish Priest. However, in smaller settlements, like ones that only have one, a diaconate is synonymous with a parish, and the title is a transitionary period between Scribes and Priests. Deacons are not considered fully ordained priests and therefore their abilities are limited by law.

**Paycheck:** `20 coin`

## Mechanics

### Convert

{% code title="\#cathedral" %}
```javascript
r!convert <@user>
```
{% endcode %}

_Used by Deacons to convert characters to Catholicism.  
`<@user>` - The mentioned discord user whose character you want to convert._

* **Cost:** `20 piety`
* **Reward**: `10 coin`
* **Cooldown:** `2h`

{% hint style="success" %}
_The convert command is accessible to **anyone** with at least **4 Intelligence**, meaning anyone can convert people to the **faith of their own character.** However, only the **Clergy** can convert people to **Catholicism**._
{% endhint %}

* _When converted by the Clergy, a user would get an overt `Baptized` role._ 
* _When a character from an **Abrahamic** religion is converted to a **non-Abrahamic** faith, they gain the covert `Apostate` role._ 

{% hint style="danger" %}
_Users who are `Baptized` or `Apostates` cannot be converted again._
{% endhint %}

### Preach

{% code title="\#cathedral" %}
```javascript
r!preach <sermon>
```
{% endcode %}

_Used to earn Piety  
`<sermon>` - The words that you character preaches._

* **Minimum Stamina:** 50%
  * **Raw Stamina Cost:** 10
* **Reward:** `?piety`
  * **Reward Cooldown:** 24h
  * **Command Cooldown:** 1h

{% hint style="danger" %}
_Every use of r!preach must be accompanied by an original sermon along with it IC, preferably before the command is used._
{% endhint %}

{% hint style="warning" %}
_r!preach has a chance to fail, depending on your luck, Intelligence, and Charisma._
{% endhint %}

## In-depth guide:

Deacons are the lowest rank within the Preachment route. They inherit every Scribe command and earn a couple of new ones as well. They are basically unordained priests with a few responsibilities including administering the sacraments of Baptism and the Eucharist, while also delivering sermons, excluding Mass, and they oversee burials and funerals.

