## Lightning Only Shocks Players Ahead (Like POW and Mario Kart World)

This code makes it so the Lightning will only shock players ahead of you, like the POW Block. This is actually how the Lightning works in Mario Kart World. I don't like this change but I thought it would be a cool concept code, plus, I'm bored

<details>
<summary>NTSC-U</summary>

NOTE: Battle has original Lightning behavior. If you want to make it position based (Untested, I don't know if it works), change 818C0B70 to 39800000

```powerpc
C27A91F8 0000000B
819F8F68 818C0B70
2C0C0003 4182000C
2C0C0009 4180000C
7C1BC800 48000038
572B15BA 576915BA
819F8F70 818C000C
7D4C582E 7D8C482E
894A0020 898C0020
7C0A6000 38000000
40810008 38000001
2C000000 00000000
```
</details>

<details>
<summary>PAL</summary>

NOTE: Battle has original Lightning behavior. If you want to make it position based (Untested, I don't know if it works), change 818C0B70 to 39800000

```powerpc
C27B7C58 0000000B
819FD728 818C0B70
2C0C0003 4182000C
2C0C0009 4180000C
7C1BC800 48000038
572B15BA 576915BA
819FD730 818C000C
7D4C582E 7D8C482E
894A0020 898C0020
7C0A6000 38000000
40810008 38000001
2C000000 00000000
```
</details>

<details>
<summary>NTSC-J</summary>

NOTE: Battle has original Lightning behavior. If you want to make it position based (Untested, I don't know if it works), change 818C0B70 to 39800000

```powerpc
C27B72C4 0000000B
819FC788 818C0B70
2C0C0003 4182000C
2C0C0009 4180000C
7C1BC800 48000038
572B15BA 576915BA
819FC790 818C000C
7D4C582E 7D8C482E
894A0020 898C0020
7C0A6000 38000000
40810008 38000001
2C000000 00000000
```
</details>

<details>
<summary>NTSC-K</summary>

NOTE: Battle has original Lightning behavior. If you want to make it position based (Untested, I don't know if it works), change 818C0B70 to 39800000

```powerpc
C27A6018 0000000B
819FBD68 818C0B70
2C0C0003 4182000C
2C0C0009 4180000C
7C1BC800 48000038
572B15BA 576915BA
819FBD70 818C000C
7D4C582E 7D8C482E
894A0020 898C0020
7C0A6000 38000000
40810008 38000001
2C000000 00000000
```
</details>