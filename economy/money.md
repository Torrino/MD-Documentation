---
description: Details on how money is handled in MD.
---

# Money

## _The Currency_

The currency used in **Medieval Discord** and the **in-character** world which is acknowledged by all characters within **Rosewood** is **1 Buckle** or many **Buckles.**

The money your character owns can either be in `Coin`or in your `Bank`.

## _Money in Coin_

This is the money your character has **on them**, meaning, this is literally the coin your character is carrying in their pockets. Your character always has access to money in coin and can use them at any time for whatever reason. 

Here's an overview of what you can do with your **money in coin**:

* _Used for spending when buying items, doing quests, etc._ 
* _Can be stolen by other players_ 
* _Can be lost as punishment when making wrong decisions, random events, etc._ 
* _Can be stored in the bank at any time using the command `deposit` in the bank channel._ 

## _Money in Bank_

* _Usually safe from being stolen or lost...usually._
* _Automatically taxed by the government \(unless you're avoiding taxes\)_
* _Any amount can be withdrawn using the command `withdraw`_

## _Commands_

Every single character can `deposit` to and `withdraw` from their bank "account" whenever they want to. Both `deposit` and `withdraw` can **only** be used in the **\#bank** text channel.

### _Checking your Balance_

{% code title="Any channel \(or \#bank\)" %}
```javascript
r!money
```
{% endcode %}

_All the commands above to the same. They show you the amount of money you have in **coin.**  
To check the amount of money your character has in the **bank**, type the same command in the **\#bank** text channel._

### _Depositing Coin to the Bank_

{% code title="\#bank" %}
```javascript
r!deposit <amount>
```
{% endcode %}

_`<amount>`- Number of buckles you want to put in to your bank._

### _Withdrawing Coin from the Bank_

{% code title="\#bank" %}
```javascript
r!withdraw <amount>
```
{% endcode %}

_`<amount>`- Number of buckles you want to withdraw from your bank._

{% hint style="success" %}
Typing `all`for the `<amount>`will deposit/withdraw all of your coin to/from the bank.
{% endhint %}

### _Sending money_

{% code title="Any channel" %}
```javascript
r!pay <amount> <@user>
```
{% endcode %}

_`<amount>` - Number of buckles \(**in coin**\) you want to give to the mentioned user.  
`<@user>` - Mentioned discord user \(with @\) to whom you're sending your coin._

