## AI Rubberbanding Codes

Codes related to AI Rubberbanding from Highway Battle

<details>
<summary>Enable AI Rubberbanding Anywhere (Every AI)</summary>

Enables AI Rubberbanding from Highway Battle anywhere (any mode/event or Free Roam), for every AI. Forces them to always be rubberbanding. 
Racers are unbeatable with this code. If you want only cops to rubberband, use the other code, below this one.

Video explanation of the AI Rubberbanding behavior and the code in action: https://www.youtube.com/watch?v=2qrt8nCXslg

```powerpc
04022DF8 60000000
04022E24 48000018
0402729C 60000000
04027514 48000028
04333EE4 48000040
```
</details>

<details>
<summary>Enable Cop AI Rubberbanding Anywhere (Only Cops)</summary>

Enables AI Rubberbanding from Highway Battle anywhere (any mode/event or Free Roam), for cops only. Forces them to always be rubberbanding. Cops are extremely crazy with this code. It's very fun!
Every other AI will behave as normal. If you want every AI to rubberband, use the other code, above this one.

Video explanation of the AI Rubberbanding behavior and the code in action: https://www.youtube.com/watch?v=2qrt8nCXslg

```powerpc
C2027158 00000003
881900C8 81990048
2C0C0000 40820008
38000001 00000000
C202723C 00000004
81990048 2C0C0000
40820010 EF7BD828
D37900D0 C062A904
FC1B0040 00000000
C2333EA0 00000003
8001000C 899B006E
2C0C0000 41820008
38000001 00000000
```
</details>

<details>
<summary>Enable AI Rubberbanding for Player AI</summary>

Player AI can rubberband. To work in everywhere, use with "Enable AI Rubberband Anywhere (Every AI)", else, it will only work in Highway Battle

Do NOT use this with "Cops Can't Rubberband in Highway Battle (Game Fix)"!

```powerpc
04022E14 60000000
```
</details>

<details>
<summary>Highway Battle Rubberbanding AI Simulator (Player AI Rubberbanding Speed Control & Auto Pilot Toggle)</summary>

This code allows your vehicle to "simulate" the Highway Battle Rubberbanding AI. This code is for Classic Controller only: Press ZL to enable and disable auto pilot and rubberbanding for your car, you MUST use "Enable AI Rubberbanding Anywhere (Every AI)" and
"Enable AI Rubberbanding for Player AI" in order for your car to be able to rubberband. Push left stick up/down to increase/decrease your rubberbanding speed. Press L to completely reset the speed back to zero.

Here's a video showing this code: https://www.youtube.com/shorts/0net710FLR0

```powerpc
28642A1A FF7F0080
C20274FC 0000000B
818C00A8 3D608064
616AF880 7C1E5000
40820040 A14B2A1A
714A2000 EC210828
4082002C C03F0060
C3EB2A28 EFFF0032
EC21F82A A14B2A28
280A3F80 40810010
817F0060 2C0B0000
40810008 D03F0060
60000000 00000000
0403D2F8 38600001
CC000000 00000000
040274FC 818C00A8
0403D2F8 8863028C
E0000000 00000000
```
</details>

<details>
<summary>Force Rubberbanding AI Speed</summary>

Forces Rubberbanding AI to always be at set speed rather than having speed based on player speed, it is currently set to be very fast (460kmh~). You can modify the speed by modifying the float on the first line (43000000)

```powerpc
04001894 43000000
040274F0 3D608000
040274F8 C02B1894
```
</details>

<details>
<summary>Rubberbanding AI Chases & Rams You</summary>

Rubberbanding AI will chase and ram you, very crazy and fun. Recommended to use with the "Force Rubberbanding AI Speed" code so the AIs are always moving at a constant speed, else, their speed will be based
on your speed and they won't move if you don't move. 

Recommended to use with "Indestructive Cop Cars (No Damage)"

```powerpc
C20272A0 00000004
3D808065 C02CF880
D02101C4 C0ECF884
D0E101C8 C02CF888
D02101CC 00000000
```
</details>

<details>
<summary>Rubberbanding AI Flies in the Air</summary>

Rubberbanding AI will be flying in the air rather than being on the ground. You can modify the height they fly at by modifying the float on the first line (420C0000)

```powerpc
04001898 420C0000
C202715C 00000004
C0E101C8 3D808000
C00C1898 ECE7002A
D0E101C8 C10101C4
60000000 00000000
```
</details>

<details>
<summary> Unlimited AI Rubberband Amount (Highway Battle)</summary>

The game has an amount of how many times the AI can rubberband. After that amount is passed the AI can't rubberband anymore, allowing you to win. 

Highway Battle only. Outrun one is included after this code. Both can be used together

```powerpc
04022E28 38607FFF
```
</details>

<details>
<summary>Unlimited AI Rubberband Amount (Outrun)</summary>

The game has an amount of how many times the AI can rubberband. After that amount is passed the AI can't rubberband anymore, allowing you to win. 

Outrun only. Highway Battle one is included above this code. Both can be used together, can also be used with Unlimited Rubberband Time

```powerpc
04027E78 38607FFF
```
</details>

<details>
<summary> Unlimited AI Rubberband Time (Highway Battle)</summary>

The game has a race time elapsed limit. After that time is passed the AI can't rubberband anymore, allowing you to win. 

Highway Battle only. Outrun one is included after this code. Both can be used together, can also be used with Unlimited Rubberband Amount

```powerpc
04027254 60000000
```
</details>

<details>
<summary>Unlimited AI Rubberband Time (Outrun)</summary>

The game has a race time elapsed limit. After that time is passed the AI can't rubberband anymore, allowing you to win. 

Outrun only. Highway Battle one is included before this code. Both can be used together, can also be used with Unlimited Rubberband Amount

```powerpc
0402AFC4 60000000
```
</details>

<details>
<summary>Cops Can't Rubberband in Highway Battle (Game Fix)</summary>

This code fixes an issue where cops can rubberband in Highway Battle, meaning that cops will no longer be crazy in Highway Battles. This is basically a fix that the developers should have done but forgot or they never saw cops
rubberbanding and forgot that they also use the same function as the AI racer. Rushed game, I guess they didn't test every aspect in gameplay. Do NOT use this with "Enable AI Rubberband for Player AI"!

```powerpc
C2022E10 00000003
801E0048 2C000000
40820008 38600001
2C030000 00000000
```
</details>
