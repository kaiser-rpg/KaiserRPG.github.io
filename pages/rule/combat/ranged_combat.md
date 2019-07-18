---
title: Ranged Combat
permalink: rule_combat_ranged.html
---

Combatants use projectiles in fights where their opponents are at some distance away. There are two kinds of projectiles -- Thrown and Fired. The Thrown type -- which includes daggers, axes, and most powers -- are launched from your hands, while Fired projectiles are launched from a device, such as a bow or crossbow. Each such projectile has a defined range.

## Range Specific States
Below are a list of special states that only apply in ranged combat.

{% include table-index.html table="state" index="500" %}

### Point-Blank
You are at Point-Blank range is your are within 5 feet of your target. While at [@state Point-Blank @] range, you have `A1` and you can be counterattacked and can counterattack.

### Changing Target
If you make multiple ranged attacks in a single round, you suffer a `-1` penalty each time your next attack targets a different creature than the previous. This penalty also applies if you were previously [@action Aiming @] but then switch targets (which still causes you to lose the Aim bonus).

### Target has Cover
If your target is mostly behind cover, you suffer a `-4` penalty to the Offensive Roll. If the target is completely behind cover, you cannot attack them until they exit cover. This can be done by preparing an offensive roll.

### Moving Shot
When you move more than 20 feet before shooting, you suffer `D1` on the Offensive Roll. If you move than your Dash Distance, you instead suffer `D2`.

### Moving Target
When your target has moved more than 50 feet this round before you make your shot, you suffer `D1` on the Offensive Roll. If they move more than 100 feet, you instead suffer `D2`.

### Large Target
Shooting at a target who is at least 8 feet tall gives you a `+4` bonus to the Offensive Roll. This bonus does not apply when shooting targets using the Rex or Ludus Damage Roles.

### Shooting Defensively
You can declare that you are [@state Shooting Defensively @] before making your Offensive Roll to prevent an opponent from taking the Attack an Opening reaction. But, doing so gives you `D1` on the Offensive Roll.

## Defense Against Projectiles
If you have not reached Mastery with [@skill Block @] or [@skill Dodge @], you may find it very difficult to defend against thrown or fired projectiles. When making your Defensive Roll against such attacks, you suffer a special penalty as described in the table below. 

{% include table-index.html table="combat" index="410" %}

## Effective and Maximum Range
Projectile weapons have two range values called effective range and maximum range. The effective range is about half of the maximum and represents the distance your projectile can accurately travel before it starts to lose some of its accuracy and strength. Within the effective range, your ranged Offensive Rolls suffer no penalty. The maximum range is the absolute farthest distance you can hit a target with your projectile, anything beyond and the attack falls flat and loses all its power. A target beyond your effective range and within your maximum range can be attacked, but you suffer a `-3` penalty to the Offensive Roll.

The strength of the thing that shoots the projectile, wether that be you or the arm of a crossbow, can increase the maximum range of a projectile (and thus also increase its effective range). Consult the table below to find the distance increase, or decrease, that a Strength value has. Remember, that this modifies the maximum range, so half of that value is added to the effective range.

{% include table-index.html table="combat" index="420" %}

## Rate of Throwing and Reload
Projectile weapons must be readied before they can be shot. You must draw back your bow, properly grab a knife, or reload a crossbow before you can shoot it again. Each thrown projectile has a value called Rate of Throwing while a Fired projectile has a Reload value. All projectiles Rate of Throwing or Reload are listed in the Equipment page.

The Rate of Throwing (RoT) indicated how much skill is required to throw an additional projectile in one round. A weapon with a RoT of 4 can be thrown one time and then one additional time for every 4 points in the sum of your Final [@skill Strike @] Value and Final [@skill Sleight of Hand @] Value. So a [@skill Strike @] of 12 and [@skill Sleight of Hand @] of 6 means you can throw a maximum of 5 of them; one for free and then 18/4 equals 4. You can always throw one projectile per round, no matter your skill and the projectiles Rate of Throwing. If you are trying to throw projectiles with different RoT, you can throw another as long as its RoT and the sum of all other projectiles RoT is less than or equal to your Throw Rate. Any weapon that is not designed to be thrown -- or does not have a listed RoT -- can be thrown with a RoT of 12 for small and medium weapons and 16 for large weapons. The Weapon Damage of an object not designed to be thrown is halved.

The Reload value indicates how many times you must take the [@action Reload @] action. Once you have performed a number of [@action Reload @] actions on a Fired weapon equal to its Reload value, it is ready and can be used as part of the [@attack Attack Action @]. For every 10 points you have in your Final [@skill Strike @] and [@skill Sleight of Hand @] Skills, you reduce the number of Reloads a weapon requires by one. If you reduce the Reload to zero, you can reload the weapon as part of an Offensive Roll and you do not need to perform the [@action Reload @] action on it.

## Limit to Offensive Roll
Without the talent of Presence Extrusion, an Offensive Roll with a projectile weapon is simply unable to achieve a result greater than the Impossible (28) Degree. This is because a projectile that is not infused with some sort of supernatural energy has a maximum velocity that it can travel before becoming unstable.