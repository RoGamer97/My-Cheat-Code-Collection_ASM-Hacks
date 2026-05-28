## Fancy MSPT Antifreeze

The following code prevents the game from crashing if a track does not have valid MSPT entries. Useful to play VS tracks in battle mode and mission mode.
My version of the code is fancier than Bean's (in my opinilon) because it's way shorter and instead of teleporting you to 0,0,0, it teleports you to the start point instead!

<details>
<summary>NTSC-U</summary>

```powerpc
C25146B8 00000004
81830040 818C0000
2C0C0000 4082000C
81830008 91830040
80630040 00000000
```
</details>

<details>
<summary>PAL</summary>

```powerpc
C2518B2C 00000004
81830040 818C0000
2C0C0000 4082000C
81830008 91830040
80630040 00000000
```
</details>

<details>
<summary>NTSC-J</summary>

```powerpc
C25184AC 00000004
81830040 818C0000
2C0C0000 4082000C
81830008 91830040
80630040 00000000
```
</details>

<details>
<summary>NTSC-K</summary>

```powerpc
C2506B4C 00000004
81830040 818C0000
2C0C0000 4082000C
81830008 91830040
80630040 00000000
```
</details>