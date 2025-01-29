## Fully Controllable Bullet Bill

This code will allow you to fully control a Bullet Bill as if you weren't in one. You can wheelie, trick, accelerate, reverse, drive as if you were a normal vehicle, hop, drift and more. It is a very fun code to mess around at times. I made it so during this state, the Bullet is infinite. In order to end the Bullet, set the activator which will be the button that will end the Bullet.

<details>
<summary>NTSC-U</summary>

If you don't want the Bullet being infinite, remove activator (2834XXXX until E0000000) and the last line before the 2834XXXX, which ends with instruction 38600000)

XXXX: Controller Address
YYYY: Button to end Bullet

Button values: https://mariokartwii.com/archive/index.php?thread-44.html

```powerpc
045B1D7C 40800078
04572594 48000018
045794C8 38A00000
04578B80 38C00000
04577604 60000000
0457762C 48000028
0458E104 60000000
0458E1BC 60000000
04575350 4800002C
04577704 60000000
045AEF6C 60000000
045B24E4 38600000
045B0D54 48000070
045B1D68 38600000
2834XXXX YYYYZZZZ
045B1D7C 60000000
045B1D68 A87F0000
E0000000 80008000
```
</details>

<details>
<summary>PAL</summary>

If you don't want the Bullet being infinite, remove activator (283QXXXX until E0000000) and the last line before the 2834XXXX, which ends with instruction 38600000)

Q: 5 for GameCube controller, 4 for all other controllers
XXXX: Controller Address
YYYY: Button to end Bullet

Button values: https://mariokartwii.com/archive/index.php?thread-44.html


```powerpc
0459CD94 40800078
04578DF8 48000018
0457FD2C 38A00000
0457F1DC 38C00000
0457DE68 60000000
0457DE90 48000028
04594928 60000000
045949E0 60000000
0457BBB4 4800002C
0457DF68 60000000
045743E4 60000000
0459D4FC 38600000
0459BD6C 48000070
0459CD80 38600000
283QXXXX YYYYZZZZ
0459CD94 60000000
0459CD80 A87F0000
E0000000 80008000
```
</details>

<details>
<summary>NTSC-J</summary>

If you don't want the Bullet being infinite, remove activator (2834XXXX until E0000000) and the last line before the 2834XXXX, which ends with instruction 38600000)

XXXX: Controller Address
YYYY: Button to end Bullet

Button values: https://mariokartwii.com/archive/index.php?thread-44.html

```powerpc
0459C714 40800078
04578778 48000018
0457F6AC 38A00000
0457EB5C 38C00000
0457D7E8 60000000
0457D810 48000028
045942A8 60000000
04594360 60000000
0457B534 4800002C
0457D8E8 60000000
04573D64 60000000
0459CE7C 38600000
0459B6EC 48000070
0459C700 38600000
2834XXXX YYYYZZZZ
0459C714 60000000
0459C700 A87F0000
E0000000 80008000
```
</details>

<details>
<summary>NTSC-K</summary>

If you don't want the Bullet being infinite, remove activator (2834XXXX until E0000000) and the last line before the 2834XXXX, which ends with instruction 38600000)

XXXX: Controller Address
YYYY: Button to end Bullet

Button values: https://mariokartwii.com/archive/index.php?thread-44.html

```powerpc
0458ADEC 40800078
04566E50 48000018
0456DD84 38A00000
0456D234 38C00000
0456BEC0 60000000
0456BEE8 48000028
04582980 60000000
04582A38 60000000
04569C0C 4800002C
0456BFC0 60000000
0456243C 60000000
0458B554 38600000
04589DC4 48000070
0458ADD8 38600000
2835XXXX YYYYZZZZ
0458ADEC 60000000
0458ADD8 A87F0000
E0000000 80008000
```
</details>