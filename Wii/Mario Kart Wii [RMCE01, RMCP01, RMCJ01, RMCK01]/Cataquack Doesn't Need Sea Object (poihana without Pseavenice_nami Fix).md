##  Cataquack Doesn't Need Sea Object (poihana without Pseavenice_nami Fix)

Cataquacks (poihana) objects need GCN Peach Beach sea object (Psea) or Delfino Pier (venice_nami) for splash SFX when it walks, else the game freezes. This code fixes the freeze, removing the requirement of these objects.

<details>
<summary>NTSC-U</summary>

```powerpc
C28178CC 00000002
2C030000 4D820020
C0030034 00000000
```
</details>

<details>
<summary>PAL</summary>

```powerpc
C282B3E0 00000002
2C030000 4D820020
C0030034 00000000
```
</details>

<details>
<summary>NTSC-J</summary>

```powerpc
C282AA4C 00000002
2C030000 4D820020
C0030034 00000000
```
</details>

<details>
<summary>NTSC-K</summary>

```powerpc
C28197A0 00000002
2C030000 4D820020
C0030034 00000000
```
</details>