## Disable Rocket Start & Burn Out in Specific Slots

This code allows disabling the rocket start & burn out in specific slots. Originally in the game the rocket start & burn out are disabled in Funky Stadium & Chain Chomp Wheel. This code can be useful to be used in Custom Tracks that start with boost pannels. The code comes with one slot but it can be modified for many different slots, just edit the source below (which is very simple). Made for Custom Track creators & Custom Track Distributions.

<details>
<summary>NTSC-U</summary>

XX: Course ID

```powerpc
C258F1F0 00000003
80030B68 2C0000XX
40820008 38000022
60000000 00000000
```
</details>

<details>
<summary>PAL</summary>

XX: Course ID

```powerpc
C2595A14 00000003
80030B68 2C0000XX
40820008 38000022
60000000 00000000
```
</details>

<details>
<summary>NTSC-J</summary>

XX: Course ID

```powerpc
C2595394 00000003
80030B68 2C0000XX
40820008 38000022
60000000 00000000
```
</details>

<details>
<summary>NTSC-K</summary>

XX: Course ID

```powerpc
C2583A6C 00000003
80030B68 2C0000XX
40820008 38000022
60000000 00000000
```
</details>