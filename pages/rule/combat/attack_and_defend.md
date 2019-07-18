---
title: Attacking and Defending
permalink: rule_combat_attack_defend.html
---

When you make an attack or are the subject of one, follow the steps outlined below.
1. **Calculate the Final Offensive Roll**: This is equal to 2d6 + Offensive Skill + factors.
2. **Calculate the Final Defensive Roll**: This is equal to 2d6 + Defensive Skill + modifiers.
3. **Compare the Offensive Roll and Defensive Roll**: 
 - _If the Offensive Roll is Greater_: the attack was successful, move to the Successful Attack section.
 - _If the Defensive Roll is Greater_: the attack failed, move to the Failed Attack section.
 - _If there is a tie_: nothing happens as both the attacker and defender failed to find an opening in the other's movements.

#### Successful Attack
An attack is considered successful if the attacker has at least 1 Degree of Success (same as the defender having at least 1 Degree of Failure) on the Opposed Skill Check. The defender loses 1 AP this round as a result of being losing some tactical advantage. To calculate Units of Damage, take the Degree of Success and subtract the defender's Absorption and Armor Value against the Damage Type. Then for each Unit of Damage, the defender loses a number of Life Points equal to the attack's Base Damage. Lastly, if the attack has any additional effect, perform it now.

{% include equation-pop.html content="Damage Dealt = (DoS - Absorption - AV) × Base Damage"%}

{% include example.html content="Ceil is making an attack against a bandit with her long sword. She gains an Offensive Roll of 21 while the bandit only has a Defensive Roll of 14. Ceil has 7 DoS on the attack but must subtract the bandit's 2 Absorption and 3 AV against the Cut Damage Type – this gives her 2 Units of Damage. So, she deals 2 times the 7 -- the Base Damage of her long sword (5 + 2 from Strength Modifier). In the end, the bandit takes 14 points of damage."%}

#### Failed Attack
An attack is considered a failure if the defender has at least 1 Degree of Success (same as the attacker having at least 1 Degree of Failure) on the Opposed Skill Check. If the attack is hand-to-hand, then the attacker has left an opening that the defender can take advantage of. The defender gains a Counter bonus equal to half the DoS, round down, that can be used on certain Opposed Skill Check against the attacker, like Attack or Acrobatics. Additionally, the defender has the opportunity to take the Counterattack Reaction. 

If the attack is ranged then the attacker was unable to strike but, unless it was made at point-blank range, it does not provide any [@action Counter @] chance. Some powers allow a defender to act upon a failed ranged attack.

{% include meta.html content = "When Offensive and Defensive Rolls occur, it does not mean that the attacker has swung once with their sword and the defender raised a shield to block it. The rolls represent a possible series of moves and countermoves that all take place within a short period of time. It is up to the GM and the players to narrate what an attack looks like, whether that be many quick slashes with a dagger, a well-placed arrow, or quick back-and-forth between attacker and defender."%}