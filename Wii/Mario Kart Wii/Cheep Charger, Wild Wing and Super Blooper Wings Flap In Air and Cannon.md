## Cheep ChargerWild WingSuper Blooper Wings Flap In AirCannon

This code will make the wings from Cheep Charger, Wild Wing and Super Blooper (hands) flap when in cannon or air like how the Biddybuggy does in MK8/D (inspiration). For reference, the wing flap animation normally happens when you boost, and now also happens in the air with this code (actually, for Cheep Charger and Super Blooper, they do the flap animation in cannon normally, with exception of Wild Wing, so this code changes Wild Wing to flap in cannon too). 

<details>
<summary>NTSC-U</summary>

If you prefer the wings to open and not flap (gliding anim) in the air (like how it normally happens when in cannon) instead of flap, change 38800004 2C080009 to 38800006 2C080009 and 40820008 38800006 to 40820008 38800004 - and if you also prefer the Wild Wing to have the normal cannon animation (open and not flap (gliding anim) instead of flap, remove second C2 hook code [Delete from C2XXXXXX 00000004 to 38800004 00000000])

```powerpc
C25677D0 00000015
9421FF80 BC610008
7C7F1B78 38A00000
38C00001 83A30000
811D0000 81080004
2C080007 41820014
2C080009 4182000C
2C08000A 40820064
819D0004 816C001C
2C0B0014 41810030
818C000C 758CC800
41820048 8183007C
806C0028 38800009
3D808089 C04C002C
3D808055 618C3304
48000020 7FE3FB78
38800004 2C080009
40820008 38800006
3D808056 618C7BF8
7D8903A6 4E800421
B8610008 38210080
7C7D1B78 00000000
C257E4AC 00000004
38800000 81830000
818C0000 818C0004
2C0C0007 40820008
38800004 00000000
```
</details>

<details>
<summary>PAL</summary>

If you prefer the wings to open and not flap (gliding anim) in the air (like how it normally happens when in cannon) instead of flap, change 38800004 2C080009 to 38800006 2C080009 and 40820008 38800006 to 40820008 38800004 - and if you also prefer the Wild Wing to have the normal cannon animation (open and not flap (gliding anim) instead of flap, remove second C2 hook code [Delete from C2XXXXXX 00000004 to 38800004 00000000])

```powerpc
C256C620 00000015
9421FF80 BC610008
7C7F1B78 38A00000
38C00001 83A30000
811D0000 81080004
2C080007 41820014
2C080009 4182000C
2C08000A 40820064
819D0004 816C001C
2C0B0014 41810030
818C000C 758CC800
41820048 8183007C
806C0028 38800009
3D808089 C04C63CC
3D808055 618C7684
48000020 7FE3FB78
38800004 2C080009
40820008 38800006
3D808056 618CCA48
7D8903A6 4E800421
B8610008 38210080
7C7D1B78 00000000
C2584CD0 00000004
38800000 81830000
818C0000 818C0004
2C0C0007 40820008
38800004 00000000
```
</details>

<details>
<summary>NTSC-J</summary>

If you prefer the wings to open and not flap (gliding anim) in the air (like how it normally happens when in cannon) instead of flap, change 38800004 2C080009 to 38800006 2C080009 and 40820008 38800006 to 40820008 38800004 - and if you also prefer the Wild Wing to have the normal cannon animation (open and not flap (gliding anim) instead of flap, remove second C2 hook code [Delete from C2XXXXXX 00000004 to 38800004 00000000])

```powerpc
C256BFA0 00000015
9421FF80 BC610008
7C7F1B78 38A00000
38C00001 83A30000
811D0000 81080004
2C080007 41820014
2C080009 4182000C
2C08000A 40820064
819D0004 816C001C
2C0B0014 41810030
818C000C 758CC800
41820048 8183007C
806C0028 38800009
3D808089 C04C5A10
3D808055 618C7004
48000020 7FE3FB78
38800004 2C080009
40820008 38800006
3D808056 618CC3C8
7D8903A6 4E800421
B8610008 38210080
7C7D1B78 00000000
C2584650 00000004
38800000 81830000
818C0000 818C0004
2C0C0007 40820008
38800004 00000000
```
</details>

<details>
<summary>NTSC-K</summary>

If you prefer the wings to open and not flap (gliding anim) in the air (like how it normally happens when in cannon) instead of flap, change 38800004 2C080009 to 38800006 2C080009 and 40820008 38800006 to 40820008 38800004 - and if you also prefer the Wild Wing to have the normal cannon animation (open and not flap (gliding anim) instead of flap, remove second C2 hook code [Delete from C2XXXXXX 00000004 to 38800004 00000000])

```powerpc
C255A678 00000015
9421FF80 BC610008
7C7F1B78 38A00000
38C00001 83A30000
811D0000 81080004
2C080007 41820014
2C080009 4182000C
2C08000A 40820064
819D0004 816C001C
2C0B0014 41810030
818C000C 758CC800
41820048 8183007C
806C0028 38800009
3D808088 C04C4CF4
3D808054 618C56DC
48000020 7FE3FB78
38800004 2C080009
40820008 38800006
3D808055 618CAAA0
7D8903A6 4E800421
B8610008 38210080
7C7D1B78 00000000
C2572D28 00000004
38800000 81830000
818C0000 818C0004
2C0C0007 40820008
38800004 00000000
```
</details>