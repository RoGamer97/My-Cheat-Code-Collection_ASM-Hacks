## Restore Unused Thwomp Damage Sound

This code restores (custom code) an unused sound that would when damaging Thwomps.

Someone by the name of "DBlaze" found out that there's an unused sound referred to as "SE_CC_DOSSUN_V_DMG" internally (ID 0x246) that would play when a thwomp was hit (star, bomb or anything that hurts them). This code restores this behaviour.

<details>
<summary>NTSC-U</summary>

```powerpc
C2753178 00000006
7FE3FB78 9421FF80
BC610008 38800246
3D808080 618CCA48
7D8903A6 4E800421
B8610008 38210080
60000000 00000000
```
</details>

<details>
<summary>PAL</summary>

```powerpc
C27600C4 00000006
7FE3FB78 9421FF80
BC610008 38800246
3D808082 618C055C
7D8903A6 4E800421
B8610008 38210080
60000000 00000000
```
</details>

<details>
<summary>NTSC-J</summary>

```powerpc
C275F730 00000006
7FE3FB78 9421FF80
BC610008 38800246
3D808081 618CFBC8
7D8903A6 4E800421
B8610008 38210080
60000000 00000000
```
</details>

<details>
<summary>NTSC-K</summary>

```powerpc
C274E484 00000006
7FE3FB78 9421FF80
BC610008 38800246
3D808080 618CE91C
7D8903A6 4E800421
B8610008 38210080
60000000 00000000
```
</details>