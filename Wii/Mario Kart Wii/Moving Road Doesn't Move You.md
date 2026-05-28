## Moving Road Doesn't Move You

When standing in a moving road, it won't move you. Moving roads are Toad's Factory conveyor belts, Coconut Mall escalators and Koopa Cape last turn waterfall. Be aware that they will still behave as normal (You will gain speed from them). This is actually in the game; when in a star (and mega I suppose), these objects won't move you. Code has a filter to pick who to affect.

<details>
<summary>NTSC-U</summary>

XXXXXXXX (Who to affect):
41820008 Affect only you
41820008 Affect only others
60000000 Affect everyone

```powerpc
C2591608 00000003
80A3000C 81830014
718C0002 XXXXXXXX
38A00000 00000000
C2591344 00000003
80040008 81840014
718C0002 XXXXXXXX
3C008000 00000000
```
</details>

<details>
<summary>PAL</summary>

XXXXXXXX (Who to affect):
41820008 Affect only you
41820008 Affect only others
60000000 Affect everyone

```powerpc
C2597E2C 00000003
80A3000C 81830014
718C0002 XXXXXXXX
38A00000 00000000
C2597B68 00000003
80040008 81840014
718C0002 XXXXXXXX
3C008000 00000000
```
</details>

<details>
<summary>NTSC-J</summary>

XXXXXXXX (Who to affect):
41820008 Affect only you
41820008 Affect only others
60000000 Affect everyone

```powerpc
C25977AC 00000003
80A3000C 81830014
718C0002 XXXXXXXX
38A00000 00000000
C25974E8 00000003
80040008 81840014
718C0002 XXXXXXXX
3C008000 00000000
```
</details>

<details>
<summary>NTSC-K</summary>

XXXXXXXX (Who to affect):
41820008 Affect only you
41820008 Affect only others
60000000 Affect everyone

```powerpc
C2585E84 00000003
80A3000C 81830014
718C0002 XXXXXXXX
38A00000 00000000
C2585BC0 00000003
80040008 81840014
718C0002 XXXXXXXX
3C008000 00000000
```
</details>