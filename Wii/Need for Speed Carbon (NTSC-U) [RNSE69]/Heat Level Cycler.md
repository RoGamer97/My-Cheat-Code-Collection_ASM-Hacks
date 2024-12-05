## Heat Level Cycler

Allows cycling through heat levels (1-10) by command. Level 9 and 10 are only acessible with hacks, Heat 9 cops are regular Cruisers but they can do spike roadblocks, Heat 10 cops are Cross

Heat won't naturally change when using this code, only by command

Heat 10 combo bounty is zero. Won't be fixed

Credits to Need for Speed Carbon Extra Options mod, I saw their source and found out what function to call

<details>
<summary>Reveal Code</summary>

Press A and D-Pad Up (horizontal Wiimote, D-Pad Right if Wiimote is vertical) to increase heat level, A and D-Pad Down (horizontal, D-Pad Left if Wiimote is vertical) to decrease heat level

```powerpc
04051240 60000000
C21D4C34 00000014
7C7D1B78 9421FF80
BC610008 3D808062
A16C6B32 717E0803
2C1E0802 4182000C
2C1E0801 4082005C
89830060 2C0C0000
41820050 C0029CC4
C0230010 716C0001
4082001C EC21002A
C002B5FC FC010040
4081001C C0229CC4
48000014 EC210028
FC010040 40800008
C022B5FC D0230010
3D808025 618CACAC
7D8903A6 4E800421
39800000 41820008
39800001 999D0060
B8610008 38210080
60000000 00000000
```
</details>