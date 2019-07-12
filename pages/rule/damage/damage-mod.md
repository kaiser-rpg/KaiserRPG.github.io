---
title: Damage Modifiers
permalink: rule_damage_mod.html
---

## Armor Value
Armor Value (AV) is the amount of protection you have from certain Damage Types. When determining your AV, you must find it for each Damage Type and it is composed of four parts. The first part is Natural Armor and the last three are Layer Armor.

For each Armor Value, the Final AV can be found by the following method:
1. Take the highest Natural Armor
2. Add the layer armor with the highest value
 - Note: you can only wear one Hard Armor. The other two must be Soft.
3. Add half the layer armor with the second highest value
4. Add half the layer armor with the third highest value
5. Ignore all other layer armors

{% include example.html content="TODO" %}

### Natural Armor
Natural armor is any kind of Armor Value that comes from hardened skin or mystical veils of protection. This value is added to the AV of layer armor to determine your final AV for each Damage Type. When you are subject to multiple natural armor effects, you apply the highest bonus for each Damage Type.

{% include example.html content="TODO" %}

### Layer Armor
Layer armor is any kind of Armor Value that comes from external worn protection. This value is added to the AV of natural armor to determine your final AV for each Damage Type. When you are wearing multiple layers of armor, you apply the highest AV plus half of the next two greatest Armor Values for that Damage Type. Additionally, only one Layer Armor you wear can be Hard, all other layers must be Soft. No matter if you are benefiting from a layer of armor or not, while you are wearing it, you are subject to any penalties it applies. Your Wear Armor Skill can reduce these penalties.

{% include example.html content="TODO" %}

## Damage Vulnerability
Damage Vulnerability (DV) is when you take additional damage from certain Damage Types. This value is added to the Units of Damage calculation. Some creatures naturally have Damage Vulnerability, like fire elementals and Cold Damage. When you are subject to multiple Damage Vulnerabilities, you add the highest vulnerability for each Damage Type to your natural Damage Vulnerability.

{% include example.html content="TODO" %}

## Base Damage Resistance
Base Damage Resistance (BDR) is when you reduce the Base Damage of an attack or source of damage. Some creatures naturally have BDR, like fire elementals and the heat damage type. When you are subject to multiple BDR sources, you add the highest BDR for each Damage Type to your natural BDR.

If the BDR reduces the Base Damage to zero, you cannot be injured by that attack. Some sources of BDR will list that the resistance is ignored when the attack is imbued or some other condition. If your greatest source of BDR is ignored but a lesser source is not, then you can use that lesser source instead.

{% include example.html content="TODO" %}

## Final Damage Resistance
Final Damage Resistance (FDR) is when you reduce the Final Damage of an attack or source of damage. Some creatures naturally have FDR, like greater earth elementals and physical damage. When you are subject to multiple FDR, you add the highest resistance for each Damage Type to your natural FDR.

If the FDR reduces the Final Damage to zero, you were not injured by that attack. Some sources of FDR will list that the FDR is ignored when the attack is imbued or some other condition. If your greatest source of FDR is ignored but a lesser source is not, then you can use that lesser source instead.

{% include example.html content="TODO" %}

## Base Damage Negate
Base Damage Negate (BDN) represents the minimum Base Damage necessary to harm you for a given Damage Type. This does not reduce the Base Damage of the attack, only negates the source of damage if the Base Damage is less than the BDN. When you are subject to multiple BDN, you apply the highest value for each Damage Type. Even if you naturally have a BDN, only the highest one will apply.

Some Base Damage Negate can be ignored by certain criteria. The most common is if the attack is imbued. If your greatest source of BDN is ignored but a lesser source is not, then you can use that lesser source instead.

If you are affected by both BDR and a BDN, the Base Damage of an attack must overcome the Base Damage Negate before it is reduced by the Base Damage Resistance. 

{% include example.html content="TODO" %}

## Final Damage Negate
Final Damage Negate (FDN) represents the minimum Final Damage necessary to harm you for a given Damage Type. This does not reduce the Final Damage of the attack, only negates the source of damage if the Final Damage is less than or equal to the BDN. When you are subject to multiple FDN, you apply the highest value for each Damage Type. Even if you naturally have a FDN, only the highest one will apply.

Some Final Damage Negates can be ignored by certain criteria. The most common is if the attack is imbued. If your greatest source of FDN is ignored but a lesser source is not, then you can use that lesser source instead.

If you are affected by both FDR and a FDN, the Final Damage of an attack must overcome the Final Damage Negate before it is reduced by the Final Damage Resistance. 

{% include example.html content="TODO" %}

## Damage Limit
Damage Limit (DL) determines how many Life Points you can lose in a single round. Any damage you suffer that would cause you to lose more than the Damage Limit in Life Points are instead ignored. Each Intention Phase resets the amount of Life Points you can lose. When you are subject to multiple DLs, you apply the lowest value.

Some Damage Limit sources can be ignored by certain criteria. The most common is if the attack is imbued. If your lowest source of DL is ignored but a greater source is not, then you can use that greater source instead.

{% include example.html content="TODO" %}

## Damage Shell
Damage Shell (DS) determines a value at which you do not lose any more Life Points until next round. Any damage you suffer that would cause you to lower your remaining Life Points below the DS value are instead ignored and you become immune to all damage until the Intention Phase of the next round. You cannot benefit from a DS again until two weeks have passed, or a listed amount of time.

Some Damage Shell sources can be ignored by certain criteria. The most common is if the attack is imbued. If it is ignored, you can still take damage in the same round that your are reduced to or below the DS value. If the attack that reduces you below your DS ignores your DS, but you later suffer an attack that does not, you still ignore that attack.

You can have multiple Damage Shells, each one must be at a different value. For each value, you become immune to damage when your Life Points hit that value.

{% include example.html content="TODO" %}