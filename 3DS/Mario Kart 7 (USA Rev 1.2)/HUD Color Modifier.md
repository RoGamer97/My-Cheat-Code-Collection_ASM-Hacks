## HUD Color Modifier

Changes color of most HUDs

<details>
<summary>Reveal Code</summary>

RR: Red (0-FF)
GG: Green (0-FF)
BB: Blue (0-FF)
XXXXXXXX: Type of Modification
0A000026 = Only Color Modification
00000000 = Entire HUD Color Modification

```armv7
00267A20 E3A060RR
00267A3C E3A060GG
00267A50 E3A060BB
00267A1C XXXXXXXX
```
</details>