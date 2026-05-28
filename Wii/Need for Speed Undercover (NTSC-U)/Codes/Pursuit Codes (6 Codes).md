## Pursuit Codes

Pursuit related codes

<details>
<summary>Cops Pursue You on Sight</summary>

Cops will always start a pursuit when they see you, even if your heat level is low

```powerpc
04039010 38A00004
```
</details>

<details>
<summary>Cops Never Chase on Sight</summary>

Cops will never start a pursuit when seeing you, even if your heat level is high

```powerpc
04039010 38A00000
```
</details>

<details>
<summary>Hitting Cop Cars Won't Start Pursuit</summary>

Hitting cop cars will not start a pursuit

```powerpc
0431F9E8 38600001
```
</details>

<details>
<summary>Force Start Pursuit</summary>

Forces pursuit to start. This code is included in "Cops Consecutively Spawn Behind You" when it's enabled by button activator.
Press Classic Controller D-Pad Up and L to instantly start a pursuit. If you want to make it always enabled, just use this code: 04014840 48000028. 
If you want to change the controller or button, read the "Button Activator.txt" file inside of the Code Pack RAR

```powerpc
04014840 880300B0
28642A1A DFFE2001
04014840 48000028
E0000000 00000000
```
</details>

<details>
<summary>Force End Pursuit</summary>

Forces pursuit to end. 
Press Classic Controller D-Pad Down and L while in a pursuit to instantly end it. If you want to make it always enabled, just use this code: 04050934 38600001. 
If you want to change the controller or button, read the "Button Activator.txt" file inside of the Code Pack RAR

```powerpc
04050934 38600000
28642A1A 9FFF6000
04050934 38600001
E0000000 00000000
```
</details>

<details>
<summary>Pursuit Can Always End</summary>

Allow pursuits to always end, even if the event/mode has a escape condition (example: Avoid 7 Spikes then Evade) or in specific pursuit scenarios. You can change the last byte to 01 if you want a pursuit to last forever

```hex
0070BB59 00000000
```
</details>