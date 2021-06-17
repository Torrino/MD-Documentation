---
description: >-
  A page detailing the Priest role within Medieval Discord and their mass,
  marry, and absolve commands.
---

# Priest 🙏

## Description:

The Priest is the second rank of the threefold Christian ministry and is the governor of their respective parish, the standard subdivision of the Catholic authority. While in some settlements a parish and a diaconate may be synonymous due to their size, in Rosewood, the Capital City, the rule is that one church building presides over its own parish, consisting of multiple diaconates usually. As such, a Priest is the leader of a church, its parish, and the Deacons that are a part of it. 

When you reach the Priest rank, your character will gain the Father/Mother title.

* **Weekly Paycheck:** `60 coin`
* **Rank-up Cost:** `500 piety`
* **Rank-up Rewards:** `Bible`

## Mechanics:

### Mass

{% code title="\#cathedral" %}
```javascript
r!mass <sermon>
```
{% endcode %}

_Used to hold a sermon, however, specifically during Sundays. Notably more difficult to perform successfully, but offers greater rewards.  
  
`<sermon>` - The words that you character preaches. The length of the sermon bonus/penalty on your preach success chance._

* **Minimum Stamina:** `50%`
  * **Raw Stamina Cost:** `15`
* **Base Reward:** `90-110 piety`
* **Cooldown**: `24h`
  * _Used **ONLY** on **Sundays**_

    \*\*\*\*

**Success chance**

* \(+\)**Intelligence:** `int`
* \(+\)**Charisma:** `char`
* \(+\)**Random dice:** `0-4`
* **Sermon character count:**
  * _&lt;500:_ `-3`
  * _500-999:_ `0`
  * _&gt;1000:_ `+3`
* **Age:**
  * _Teenage\(16-19\):_ `-4`
  * _Young\(20-30\):_ `-1`
  * _Middle age\(31-45\):_ `+1`
  * _Old\(46-50\):_ `+3`
  * _Elder\(51-60\):_ `+5`

**Success Threshold:**

* _**&lt;10** Fail:_ `0 piety`
* _**10-14** No change:_ `Base Reward`
* _**&gt;14** Success:_ `Base Reward + 10 piety`

### Marry

{% code title="\#cathedral" %}
```javascript
r!marry <@first user> <@second user>
```
{% endcode %}

_Used to marry two characters of the opposite gender and Catholic faith. The Man must have a wedding ring in his inventory for the command.  
`<@first user>` - Mentioned discord user with @ that is being married  
`<@second user>` - Hmmmm_

* **Piety cost:** `80`
* **Buckles Reward:** `40`
* **Command cooldown**: `2h`

_The **marry** command represents an **official marriage**, meaning that characters **can get married** without the command, but their union is **not recognized** before government or Church._

The married characters both receive the **Married** role.

{% hint style="info" %}
_Clergy members can **not** get married._
{% endhint %}

{% hint style="warning" %}
_If a character's spouse dies, the widow/widower inherits their entire bank balance._
{% endhint %}

### Absolve

{% code title="\#cathedral" %}
```javascript
r!absolve <@user>
```
{% endcode %}

_Used to absolve a character of sin.  
`<@user>` - Mentioned discord user whose sins are being forgiven._

* **Reward:** `10 piety`
  * _**Reward cooldown:**_ ****`1 piety | 24hr cooldown`

_The **absolve** command is purely for RP purposes, and it does not guarantee forgiveness in the eyes of the Law. It is to be done at the end of a session of Catholic **confession**._

## In-depth guide

Priests guide deacons, while they are instructed by the Archbishop. They have control over a specific church within Rosewood and are the de facto administrators of the building itself. They inherit all the abilities of Deacons and Scribes but also gain access to new ones since they have been ordained. They can administer all the Holy Sacraments, but cannot ordain, unlike Bishops. They will be often called upon to marry characters and to absolve their sins. Only Rosewoodian Priests can become the next Archbishop of Rosewood. Priests are valued for their knowledge of the Bible, and of Latin. More often than not, wealthy members of society will hire Priests to write official documents for them in Latin, as they are the educated few that know the language. Arguably their biggest task is to deliver the Gospel to the people of Rosewood and teach them the Bible.

