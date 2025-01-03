## Cops Have Health Bar (Car Damage Indicator)

Cop cars will have health bar above their car (The one from Takedown, Chasedown and other events that involves destroying cars). You can see the damage level. 
During a pursuit, the health bar may appear in some traffic vehicles, don't know how to fix. 
Cops spawned by the "Cops Consecutively Spawn Behind You" code will not have health bar

<details>
<summary>Reveal Code</summary>

```powerpc
C200D86C 0000000E
9421FF80 BC610008
2C030000 41820050
81830000 818C0010
7D8903A6 4E800421
2C030000 7C6B1B78
41820034 38600001
3D408020 614C6A5C
7D8903A6 4E800421
7D645B78 38A00000
38C00000 38E00000
614C6B60 7D8903A6
4E800421 B8610008
38210080 BB61009C
60000000 00000000
C2012370 00000006
38600001 3D408020
614C6A5C 7D8903A6
4E800421 2C030000
41820010 614C74A8
7D8903A6 4E800421
807F0004 00000000
C221CC80 00000006
7C7F1B78 38600001
3D408020 614C6A5C
7D8903A6 4E800421
2C030000 41820010
614C74A8 7D8903A6
4E800421 00000000
```
</details>