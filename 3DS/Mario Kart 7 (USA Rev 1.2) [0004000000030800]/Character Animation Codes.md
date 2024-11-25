## Character Animation Codes

Codes related to character animations

<details>
<summary>Always Damage Animation</summary>

Forces the character damage animation

```armv7
002F3718 EA000004
```
</details>

<details>
<summary>Damage Animation Modifier</summary>

Changes the damage animation. If used with Always Damage Animation, almost all anims don't loop (I believe less than 4 loop) - if the code is set on and off, constantly, it should loop

XX: Animation
1: Character is higher in the kart, sholders up (trick?)
2: Character is holding on the wheel and heads down (Splitstream)
3: Turning left
4: Turning right
5: Looking behind
6: Throwing item backwards
7: Throw
8: Looking backwards (reverse)
9: HAPPY comemoration (Victory)
A: Sad crying (Defeat)
B: Item Hit Success 1
C: Item Hit Success 2
D: Item Hit Success 3
E: Item Hit Success 4
F: Item Hit Success 5
10: Throwing item Forward
11: Throwing item Backwards
12: Damage (original)
13+: No Animation 

```armv7
002F37C0 E3A010XX
```
</details>

<details>
<summary>Character Animation Cycler</summary>

This code will allow you to cycle thru all character animations.
Use D-Pad Left and Right to cycle character animations. Only works in game

```armv7
002F3708 EB0E32E3
E068029C 00000078
E5900000 E92D407F 
E28F6068 E59F3060 
E5933000 E5D61001 
E3130030 0A00000B 
E5D65000 E3550000 
1A000008 E3130010 
12811001 E3130020 
12411001 E3510009 
B3A01013 E3510013 
C3A01009 E5C61001 
E3A05001 03A05000 
E5C65000 E1A00004 
E3A0200A E59F3004 
E12FFF33 E8BD807F 
002F4348 10002028 
```
</details>

<details>
<summary>CSS Menu Character Facial Animation Cycler</summary>

This code will allow you to cycle thru all character facial animations on the character selection screen.
Use R and L to cycle character facial animations

```armv7
00407500 E3A00001
00407550 EB09E3C0
E0680458 00000060
E92D4038 E28F4054 
E5D41001 E59F3048 
E5933000 E3130C03 
0A00000B E5D45000 
E3550000 1A000008 
E3130C01 12811001 
E3130C02 12411001 
E3510000 B3A01009 
E3510009 C3A01000 
E5C41001 E3A05001 
03A05000 E5C45000 
E8BD8038 10002028 
```
</details>