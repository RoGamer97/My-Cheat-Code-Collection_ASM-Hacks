## Enable AI Rubberband Anywhere

Enables AI Rubberband from Highway Battle anywhere (any mode/event or Free Roam). Two codes are included, one will affect every AI and one will only affect cops.

Video explanation of the AI Rubberband behavior and the code in action: https://www.youtube.com/watch?v=2qrt8nCXslg

<details>
<summary>Every AI</summary>

Affects every AI (racer, cops and few other AIs). Since it affects rival AI, they will be rubberbanding every frame and they're unbeatable. Use the code below if you want it to only affect cops.

```powerpc
04022DF8 60000000
04022E24 48000018
0402729C 60000000
04027514 48000028
04333EE4 48000040
```
</details>

<details>
<summary>Only Cops</summary>

Only affect cops. Every other AI (racer and few other AIs) will not be affected and will behave as normal. Use this for better experience!

```powerpc
C2027158 00000004
881900C8 81990048
2C0C0000 4082000C
38000001 901900CC
60000000 00000000
C2027234 00000004
EC61E828 81990048
2C0C0000 40820010
C062B3D0 D07900D8
C062A45C 00000000
C2333EA0 00000003
8001000C 899B006E
2C0C0000 41820008
38000001 00000000
```
</details>

## Enable AI Rubberband for Player AI

Player AI can rubberband. Do NOT use this with "Cops Can't Rubberband in Highway Battle (Game Fix)"!

<details>
<summary>Reveal Code</summary>

```powerpc
04022E14 60000000
```
</details>

## Player AI Rubberbands Against Highway Battle AI

Player AI will rubberband based on distance from rival in Highway Battle and based on rival's speed. Do NOT use with "Enable AI Rubberband for Player AI" or "Enable AI Rubberband Anywhere" and "Auto Pilot"!
<<<<<<< HEAD:Wii/Need for Speed Undercover [RX9E69]/Codes/AI Rubberband Codes.md

=======
 
>>>>>>> 2cb0f49 (Added codes for MK7):Wii/Need for Speed Undercover [RX9E69]/Codes/AI Rubberband Codes (11 Codes).md
This code is bad and should be remade in the CORRECT WAY. It crashes before going to Highway Battle and can be remade in a better way.

<details>
<summary>Reveal Code</summary>

```powerpc
04022E14 4182003C
04027164 3D808065
04027170 806CBF0C 
040271B0 60000000
```
</details>

## Highway Battle AI Rubberband Simulator (Player AI Rubberband Speed Control & Auto Pilot Toggle)

This code allows your vehicle to "simulate" the Highway Battle AI Rubberband. This code is for Classic Controller only: Press ZL to enable and disable auto pilot for your car, you MUST use "Enable AI Rubberband Anywhere (Every AI)" and
"Enable AI Rubberband for Player AI" in order for your car to be able to rubberband. Push left stick up/down to increase/decrease your rubberband speed. Press L to completely reset the speed back to zero.

Here's a video showing this code: https://www.youtube.com/shorts/0net710FLR0

<details>
<summary>Reveal Code</summary>

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

## Force Rubberbanding AI Speed

Forces Rubberbanding AI to always be at set speed rather than having speed based on player speed, it is currently set to be very fast (460kmh~). You can modify the speed by modifying the float on the first line (43000000)

<details>
<summary>Reveal Code</summary>

```powerpc
04001894 43000000
040274F0 3D608000
040274F8 C02B1894
```
</details>

## Rubberbanding AI Chases & Rams You

Rubberbanding AI will chase and ram you, very crazy and fun. Recommended to use with the code below, "Force Rubberbanding AI Speed" so the AIs are always moving at a constant speed, else, their speed will be based
on your speed and they won't move if you don't move. It does actually work for non-rubberbanding AIs too, if you want rather a more normal gameplay while cops and AIs still follow you

Should make two versions of the code, one for all AIs and one for cops only

<details>
<summary>Reveal Code</summary>

```powerpc
06026DF0 00000010
3D808065 C0ACF880
C06CF884 C00CF888
04027298 3D808065
040272A0 C0ECF884 
040272A4 C10CF880
040272AC C0CCF888
```
</details>

## Rubberbanding AI Flies in the Air

Rubberbanding AI will be flying in the air rather than being on the ground. 

Code should be updated to increase Y height rather than setting it

<details>
<summary>Reveal Code</summary>

```powerpc
04001890 45000000
C2026E04 00000002
3E408000 C0721890
D06101C8 00000000
C20272A0 00000002
3E408000 C0F21890
60000000 00000000
```
</details>

## Unlimited AI Rubberband Amount

The game has an amount of how many times the AI can rubberband. After that amount is passed the AI can't rubberband anymore, allowing you to win. 
This code will make the AI always able to rubberband, therefore you can never  escape and win because it will always catch you up and never leave you alone

<details>
<summary>Highway Battle</summary>

```powerpc
04022E28 38607FFF
```
</details>

<details>
<summary>Outrun</summary>

```powerpc
04027E78 38607FFF
```
</details>

## Cops Can't Rubberband in Highway Battle (Game Fix)

This code fixes an issue where cops can rubberband in Highway Battle, meaning that cops will no longer be crazy in Highway Battles. This is basically a fix that the developers should have done but forgot or they never saw cops
rubberbanding and forgot that they also use the same function as the AI racer. Rushed game, I guess they didn't test every aspect in gameplay. Do NOT use this with "Enable AI Rubberband for Player AI"!

<details>
<summary>Outrun</summary>

```powerpc
C2022E10 00000003
801E0048 2C000000
40820008 38600001
2C030000 00000000
```
</details>
