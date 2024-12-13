## Debug Car Changer Cycler/Switch Vehicle Codes

Codes related to the Debug feature that allows changing vehicles in game with a press of a button.

<details>
<summary>Debug Car Changer Cycler/Switch Vehicle</summary>

Press Minus (-) and D-Pad Up/D-Pad Down (Horizontal Wiimote) buttons to switch vehicle live, modified debug car changer that is nativally in the game. Minus and D-Pad Down (D-Pad Left for vertical Wiimote) cycles to the previous vehicle, Minus and D-Pad Up (D-Pad Right for vertical Wiimote) cycles to the next vehicle. The code below ("Cop Vehicle Cycler") allows you to cycle thru 
all cop vehicles. You can customize the vehicle list to any vehicle you want, all you need to do is change the vehicle hashes to the ones you want (First hash is "BB9B2938", last one is "7D8802A6"). To get a hash, use NFS Hasher v2.0 by nfsu360 and
input the vehicle string name and copy the value from "VLT Memory" to the code.

```powerpc
04394338 60000000
C2394314 0000000F
48000009 00000000
7CE802A6 38000000
3D608062 88C70000
A18B6B32 718B1003
2C0B1002 4182000C
2C0B1001 40820038
89070001 2C080000
40820024 38000001
716B0002 4082000C
38C6FFFF 48000010
38C60001 48000008
38C00000 39000001
48000008 39000000
99070001 98C70000
60000000 00000000
```
</details>

<details>
<summary>Cop Vehicle Cycler (Use w/ Debug Car Changer Cycler)</summary>

This code only works with the code above ("Debug Car Changer Cycler/Switch Vehicle"). It allows you to cycle thru all cop vehicles. You can customize the vehicle list to any vehicle you want, all you need to do is change the vehicle hashes to the 
ones you want (First hash is "BB9B2938", last one is "7D8802A6"). To get a hash, use NFS Hasher v2.0 by nfsu360 and input the vehicle string name and copy the value from "VLT Memory" to the code. Extreme fun code, can add more vehicles to the
list but the code would be too big.
Hold B and while still holding, press Minus and D-Pad Up (Horizontal) to cycle to the previous vehicle, Minus and D-Pad Down (Horizontal) to cycle to the next vehicle. 
You can change button by replacing FBFF0400 by YYYYZZZZ, where ZZZZ is button and YYYY is ZZZZ - FFFF

Button Values: https://mariokartwii.com/archive/index.php?thread-44.html

```powerpc
0439459C 7FA4EB78
28626B32 FBFF0400
C239459C 00000010
4800002D BB9B2938
A3A1D182 CC985356
E9EC1DF6 54B10E38
38B38226 B2F32FE2
A4EB6688 D37C806D
06465EB2 7D8802A6
3D608000 3D408062
A14A6B32 890B1600
714A0001 4082000C
39080004 48000008
3908FFFC 2C08FFFF
41810008 39000024
2C080028 41800008
39000000 990B1600
7D8C4214 808C0000
60000000 00000000
E0000000 00000000
```
</details>