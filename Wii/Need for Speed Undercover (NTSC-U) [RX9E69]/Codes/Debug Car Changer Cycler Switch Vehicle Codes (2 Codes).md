## Debug Car Changer Cycler/Switch Vehicle Codes

Codes related to the Debug feature that allows changing vehicles in game with a press of a button.

<details>
<summary>Debug Car Changer Cycler/Switch Vehicle</summary>

Press Classic Controller ZL/ZR buttons to switch vehicle live, modified debug car changer that is nativally in the game. ZL cycles to the previous vehicle, ZR cycles to the next vehicle. The code below ("Cop Vehicle Cycler") allows you to cycle thru 
all cop vehicles. You can customize the vehicle list to any vehicle you want, all you need to do is change the vehicle hashes to the ones you want (First hash is "BB9B2938", last one is "7D8802A6"). To get a hash, use NFS Hasher v2.0 by nfsu360 and
input the vehicle string name and copy the value from "VLT Memory" to the code.


```powerpc
043CDA84 60000000
C23CDA60 00000010
48000009 00000000
7CE802A6 38000000
3DC08064 88C70000
818E2A18 718B0084
41820048 89070001
2C080000 4082003C
38000001 2C0600E7
4182002C 2C060028
41820024 718B0080
4182000C 38C6FFFF
48000018 718B0004
41820010 38C60001
48000008 38C00000
39000001 40820008
39000000 99070001
98C70000 00000000
C224A0FC 00000003
2C030000 40820008
4E800020 80030000
60000000 00000000
```
</details>

<details>
<summary>Cop Vehicle Cycler (Use w/ Debug Car Changer Cycler)</summary>

This code only works with the code above ("Debug Car Changer Cycler/Switch Vehicle"). It allows you to cycle thru all cop vehicles. You can customize the vehicle list to any vehicle you want, all you need to do is change the vehicle hashes to the 
ones you want (First hash is "BB9B2938", last one is "7D8802A6"). To get a hash, use NFS Hasher v2.0 by nfsu360 and input the vehicle string name and copy the value from "VLT Memory" to the code. Extreme fun code, can add more vehicles to the
list but the code would be too big. Unfortunately, because of how I coded the "Controllable Police Helicopter", you cannot control it when changing to it or can control it but it's all messed up and can't go thru walls. I noticed this too late and it's
extra long work to get it all fixed (would have to do lots of modifications on the Helicopter code), so I'll leave it like this for now, maybe another time. Sorry! You can still fly it if you select the helicopter and go to world then changing vehicles.
Don't worry though, you don't need to use the helicopter code if you don't want, plus, I added a failsafe to avoid crashing if the code is not enabled.
Hold Classic Controller D-Pad Up and while still holding, press ZR to cycle to the previous vehicle, ZR to cycle to the next vehicle. 
If you want to change the controller or button, read the "Button Activator.md" file (LINK)

```powerpc
043CDCE8 7FA4EB78
04342E68 38600001
28642A1A FFFE0001
C2342E68 00000005
38600001 3D808000
890C1840 2C08001C
40820010 3D808000
986C1880 38600000
60000000 00000000
C23CDCE8 0000000F
48000025 BB9B2938
A3A1D182 B7DDD68A
38B38226 3592DDB1
6F872A59 5E5C4A90
06465EB2 7D8802A6
3D608000 3D408064
A14A2A1A 890B1840
714A0080 4082000C
39080004 48000008
3908FFFC 2C08FFFF
41810008 3900001C
2C080020 41800008
39000000 990B1840
7D8C4214 808C0000
60000000 00000000
E0000000 00000000
```
</details>