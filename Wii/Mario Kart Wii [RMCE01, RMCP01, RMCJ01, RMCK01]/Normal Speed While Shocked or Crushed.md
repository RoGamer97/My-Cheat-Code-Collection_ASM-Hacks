## Normal Speed While Shocked/Crushed

You won't drive slower when shocked or crushed, you'll drive the normal speed. Code has a filter for you to pick who to affect.

<details>
<summary>NTSC-U</summary>

XXXXXXXX (Who to affect):
41820008 Affect only you
40820008 Affect only others
60000000 Affect everyone

```powerpc
C2575570 00000003
81840014 718C0002
XXXXXXXX FF60F090
819D000C 00000000
```
</details>

<details>
<summary>PAL</summary>

XXXXXXXX (Who to affect):
41820008 Affect only you
40820008 Affect only others
60000000 Affect everyone

```powerpc
C257BDD4 00000003
81840014 718C0002
XXXXXXXX FF60F090
819D000C 00000000
```
</details>

<details>
<summary>NTSC-J</summary>

XXXXXXXX (Who to affect):
41820008 Affect only you
40820008 Affect only others
60000000 Affect everyone


```powerpc
C257B754 00000003
81840014 718C0002
XXXXXXXX FF60F090
819D000C 00000000
```
</details>

<details>
<summary>NTSC-K</summary>

XXXXXXXX (Who to affect):
41820008 Affect only you
40820008 Affect only others
60000000 Affect everyone

```powerpc
C2569E2C 00000003
81840014 718C0002
XXXXXXXX FF60F090
819D000C 00000000
```
</details>