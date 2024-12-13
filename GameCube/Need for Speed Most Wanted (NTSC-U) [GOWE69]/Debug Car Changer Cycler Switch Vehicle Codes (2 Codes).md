## Debug Car Changer Cycler/Switch Vehicle Codes

Codes related to the Debug feature that allows changing vehicles in game with a press of a button.

<details>
<summary>Debug Car Changer Cycler/Switch Vehicle</summary>

Press XXXXXX buttons to switch vehicle live, modified debug car changer that is nativally in the game. XXXXX cycles to the previous vehicle, XXXXX) cycles to the next vehicle. The code below ("Cop Vehicle Cycler") allows you to cycle thru 
all cop vehicles. You can customize the vehicle list to any vehicle you want, all you need to do is change the vehicle hashes to the ones you want (First hash is "BB9B2938", last one is "7D8802A6"). To get a hash, use NFS Hasher v2.0 by nfsu360 and
input the vehicle string name and copy the value from "VLT Memory" to the code.

```powerpc
042C6374 60000000
042C6380 60000000
C22C6360 0000000F
48000009 00000000
7CE802A6 38000000
3D60804C 89270000
A18BBFE8 718B040C
2C0B0408 4182000C
2C0B0404 40820038
89670001 2C0B0000
40820024 38000001
718B0008 4082000C
3929FFFF 48000010
39290001 48000008
39200000 39C00001
48000008 39C00000
99C70001 99270000
60000000 00000000
```
</details>

<details>
<summary>Cop Vehicle Cycler (Use w/ Debug Car Changer Cycler)</summary>

This code only works with the code above ("Debug Car Changer Cycler/Switch Vehicle"). It allows you to cycle thru all cop vehicles. You can customize the vehicle list to any vehicle you want, all you need to do is change the vehicle hashes to the 
ones you want (First hash is "BB9B2938", last one is "7D8802A6"). To get a hash, use NFS Hasher v2.0 by nfsu360 and input the vehicle string name and copy the value from "VLT Memory" to the code. Extreme fun code, can add more vehicles to the
list but the code would be too big.
Hold XXXXXX and while still holding, pressXXXX to cycle to the previous vehicle, XXXX to cycle to the next vehicle. 

```powerpc
042C6674 7C7D1B78
284BBFE8 F7FF0800
C22C6674 00000010
4800002D BB9B2938
A3A1D182 CC985356
E9EC1DF6 54B10E38
38B38226 B2F32FE2
A4EB6688 D37C806D
06465EB2 7D8802A6
3D608000 3D40804C
A14ABFE8 890B1600
714A0004 4082000C
39080004 48000008
3908FFFC 2C08FFFF
41810008 39000024
2C080028 41800008
39000000 990B1600
7D8C4214 83AC0000
60000000 00000000
E0000000 00000000
```
</details>