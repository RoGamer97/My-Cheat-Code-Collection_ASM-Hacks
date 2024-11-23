## Small Items If Shocked

This code will make you throw/drop small items if shocked. Code has a filter for you to pick who to affect. Be aware, this code is VISIBLE ONLINE, meaning that OTHERS WILL SEE YOUR SMALL ITEMS! 

<details>
<summary>NTSC-U</summary>

XXXXXXXX (Who to affect part 1):
40820040 Affect only you
41820020 Affect only others
60000000 Affect everyone

YYYYYYYY (Who to affect part 2):
41820020 Affect only you
40820020 Affect only others
60000000 Affect everyone

```powerpc
C278D2B8 0000000C
3D60809C 818B8F68
816BD110 816B0020
898C0B84 7C1B6000
XXXXXXXX 1D8C0004
7D6B6214 816B0000
816B0000 816B0004
818B0014 718C0002
YYYYYYYY 818B000C
718C0080 41820014
819F0004 2C0C000E
41820008 60000400
3C60808A 00000000
```
</details>

<details>
<summary>PAL</summary>

XXXXXXXX (Who to affect part 1):
40820040 Affect only you
41820020 Affect only others
60000000 Affect everyone

YYYYYYYY (Who to affect part 2):
41820020 Affect only you
40820020 Affect only others
60000000 Affect everyone

```powerpc
C27962C4 0000000C
3D60809C 818BD728
816B18F8 816B0020
898C0B84 7C1B6000
XXXXXXXX 1D8C0004
7D6B6214 816B0000
816B0000 816B0004
818B0014 718C0002
YYYYYYYY 818B000C
718C0080 41820014
819F0004 2C0C000E
41820008 60000400
3C60808A 00000000
```
</details>

<details>
<summary>NTSC-J</summary>

XXXXXXXX (Who to affect part 1):
40820040 Affect only you
41820020 Affect only others
60000000 Affect everyone

YYYYYYYY (Who to affect part 2):
41820020 Affect only you
40820020 Affect only others
60000000 Affect everyone

```powerpc
C2795930 0000000C
3D60809C 818BC788
816B0958 816B0020
898C0B84 7C1B6000
XXXXXXXX 1D8C0004
7D6B6214 816B0000
816B0000 816B0004
818B0014 718C0002
YYYYYYYY 818B000C
718C0080 41820014
819F0004 2C0C000E
41820008 60000400
3C60808A 00000000
```
</details>

<details>
<summary>NTSC-K</summary>

XXXXXXXX (Who to affect part 1):
40820040 Affect only you
41820020 Affect only others
60000000 Affect everyone

YYYYYYYY (Who to affect part 2):
41820020 Affect only you
40820020 Affect only others
60000000 Affect everyone

```powerpc
C2784684 0000000C
3D60809B 816BBD68
816BFF38 816B0020
898C0B84 7C1B6000
XXXXXXXX 1D8C0004
7D6B6214 816B0000
816B0000 816B0004
818B0014 718C0002
YYYYYYYY 818B000C
718C0080 41820014
819F0004 2C0C000E
41820008 60000400
3C608089 00000000
```
</details>