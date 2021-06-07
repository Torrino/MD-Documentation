---
description: >-
  A page detailing the Priest role within Medieval Discord and their mass,
  marry, and absolve commands.
---

# Priest 🙏

## Description:

The Priest is the second rank of the threefold Christian ministry and is the governor of their respective parish, the standard subdivision of the Catholic authority. While in some settlements a parish and a diaconate may be synonymous due to their size, in Rosewood, the Capital City, the rule is that one church building presides over its own parish, consisting of multiple diaconates usually. As such, a Priest is the leader of a church, its parish, and the Deacons that are a part of it. 

When you reach the Priest rank, your character will gain the Father/Mother title.

## Mechanics

### Mass

{% code title="\#cathedral" %}
```javascript
r!mass <sermon>
```
{% endcode %}

_Used to hold a sermon, however, specifically during Sundays. Notably more difficult to perform successfully, but offers greater rewards.  
  
`<sermon>` - The words that you character preaches. The length of the sermon bonus/penalty on your preach success chance._

* **Minimum Stamina:** 50%
  * **Raw Stamina Cost:** 15
* **Base Reward:** `90-110 piety`
* **Cooldown**: 24h
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

```javascript
r!marry [first user] [second user]
```

`r!marry` - _Used to marry two characters._

#### Additional requirements:

* **Channel:** \#cathedral
* **Necessary tool:** Piety
* **Minimum Stamina:** None
* **Buckles Reward:** 200

{% hint style="warning" %}
_A priest cannot marry themselves, and neither can they marry characters of the same gender. Additionally, if both characters are not Catholic, the command will fail. The man must have a wedding ring in his inventory for the command to work._
{% endhint %}

{% hint style="info" %}
_If a character's spouse dies, the widow/widower inherits their entire bank balance._
{% endhint %}

```javascript
r!absolve [user]
```

`r!absolve` - _Used to absolve a character of sin._

#### Additional requirements:

* **Channel:** \#cathedral
* **Necessary tool:** None
* **Minimum Stamina:** None
* **XP Reward:** 
  * **XP Reward Cooldown:** 24h

## In-depth guide:

Priests guide deacons, while they are instructed by the Archbishop. They have control over a specific church within Rosewood and are the de facto administrators of the building itself. They inherit all the abilities of Deacons and Scribes but also gain access to new ones since they have been ordained. They can administer all the Holy Sacraments, but cannot ordain, unlike Bishops. They will be often called upon to marry characters and to absolve their sins. Only Rosewoodian Priests can become the next Archbishop of Rosewood. Priests are valued for their knowledge of the Bible, and of Latin. More often than not, wealthy members of society will hire Priests to write official documents for them in Latin, as they are the educated few that know the language. Arguably their biggest task is to deliver the Gospel to the people of Rosewood and teach them the Bible.

