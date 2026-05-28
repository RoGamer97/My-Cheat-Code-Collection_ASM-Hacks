## Display Mushroom Gorge Clouds in Specific Slots

This code allows displaying the Mushroom Gorge clouds in any selected slot(s). The code comes with one extra slot to pick other than Mushroom Gorge to have the clouds display, however it can be modified to many different slots. This was made for Custom Track creators and Custom Track Distributions. To add more slots edit the source code, which is very simple.

<details>
<summary>NTSC-U</summary>

XX: Course ID

```powerpc
C2676EB8 00000003
80030B68 2C0000XX
40820008 38000002
60000000 00000000
C2676F5C 00000003
80040B68 2C000001
40820008 38000002
60000000 00000000
```
</details>

<details>
<summary>PAL</summary>

XX: Course ID

```powerpc
C267B340 00000003
80030B68 2C0000XX
40820008 38000002
60000000 00000000
C267B3E4 00000003
80040B68 2C000001
40820008 38000002
60000000 00000000
```
</details>

<details>
<summary>NTSC-J</summary>

XX: Course ID

```powerpc
C267A9AC 00000003
80030B68 2C0000XX
40820008 38000002
60000000 00000000
C267AA50 00000003
80040B68 2C000001
40820008 38000002
60000000 00000000
```
</details>

<details>
<summary>NTSC-K</summary>

XX: Course ID

```powerpc
C26696E8 00000003
80030B68 2C0000XX
40820008 38000002
60000000 00000000
C266978C 00000003
80040B68 2C000001
40820008 38000002
60000000 00000000
```
</details>