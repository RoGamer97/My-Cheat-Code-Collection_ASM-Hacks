## Heat Level Cycler (Override)

Allows cycling through heat levels (1-10) with C-Stick Left and C-Stick Right. You can increment and decrement the heat level.

Level 9 and 10 are unused and only acessible with hacks. Heat 9 cops are regular Cruisers but they can do spike roadblocks, Heat 10 cops are Cross. 

Heat won't naturally change when using this code, only by command. Heat 10 combo bounty is zero. Won't be fixed.

Credits to Need for Speed Carbon Extra Options mod, I saw their source and found out what function to call

<details>
<summary>Reveal Code</summary>

```powerpc
040346B0 60000000
C2143740 00000014
7C7F1B78 9421FF80
BC610008 3D80804C
896CBFEC 2C0B00A0
4080000C 2C0B0044
40800068 89830060
2C0C0000 40820054
C0230010 3D808040
C00C7C88 2C0B0044
4081001C EC21002A
C00C79CC FC010040
4081001C C02C7C88
48000014 EC210028
FC010040 40800008
C02C79CC D0230010
3D80801C 618C68C0
7D8903A6 4E800421
39800001 48000008
39800000 999F0060
B8610008 38210080
60000000 00000000
```
</details>