## CPU Codes

CPU related codes

<details>
<summary>CPU Control Cycler (Offline Only)</summary>

This code allows playing as other CPUs, you can cycle the camera thru all CPUs and you will be able to play as the one that the camera is targetting, you can drive and throw items as if you were really them. 
This code is designed for OFFLINE ONLY, the online code is private.

Use D-Pad Left and Right to cycle camera & CPU control
Camera Cycler is made by Marioiscool246, not by me. Included with permission. Rest of the code is by me.

This code can probably be shortened, using only two hooks instead of having to load my kart controller pointer to the targetted CPU in both item input function and Tanooki input function. The problem is that storing my kart controller pointer to the
CPU vehicle pointer will not restore the CPU kart controller pointer so the CPU will be controlled forever, however, it is possible to store every CPU kart controller pointer in a table, storing my kart controller pointer to the CPU pointer and then if the
CPU is not the one that the camera is targetting, load the original CPU kart controller pointer from the table based on the player ID and store it. I can't think in a way to prevent item usage for myself but CPUs without hooks though, so it's better to
keep the code like this

If you want to move CPUs to specific planes for pictures, fun or debugging, you can use the CPUs Don't Move code. CPUs won't move but you can still control them. You can also use item cycler on the targetted CPU you're controlling by using the Item
Cycler for CPU Control Cycler, it will cycle the items for the CPU you're controlling. Codes below.
This is a remake of a Mario Kart 8 Deluxe code I made: https://www.youtube.com/watch?v=dohaT31M4ek

```armv7
002B9DE4 E5907000
002B9DEC E59700E4
002B9DF0 EB0F1A3C
002BE2C0 EB0F092D
002E4C4C EB0E6EBB
002EEC78 EB0E4639
00333548 EB0D3473
00339AB8 EA000011
00339B28 00000000
00444C64 00000000
E0680564 000000B0
E5940214 E59D9000
E92D40FF E59F7094
E59F6094 E5966000
E5994028 E2444001
E5D73000 E3C350F0
E59020D8 E5922000
E5921084 E1510005
03A01001 13A01000
E5C010D4 E5C010D5
E5895030 E3A00000
E3160080 13A00001
E3160040 13A00002
E3500000 0A00000C
E3130010 1A00000C
E3500001 0A000003
E2855001 E1550004
C3A05000 EA000002
E2455001 E3550000
B1A05004 E3855010
EA000000 E3C55010
E5C75000 E8BD80FF
006806E4 10002028
E06806E8 00000034
E59F8024 E5981000
E5977084 E3570000
1A000001 E3510000
159FF010 E1570001
05980094 E5900008
E1A0F00E 006806E4
002B9E6C 00000000
E068071C 00000024
E5907084 E5900C30
E3100501 059F800C
05988000 01580007
03A00060 E1A0F00E
006806E4 00000000
E0680740 00000038
E5941084 E3510000
058F0028 E59F8020
E5988000 1A000002
E3580000 1CBD8B06
18BD8070 E1580001
059F0008 E5901008
E1A0F00E 006806E4
E068077C 0000002C
E59F2020 E5921000
E3550000 1A000001
E3510000 18BD8FF8
E1550001 05929094
E5990008 E1A0F00E
006806E4 00000000
```
</details>

<details>
<summary>Item Cycler for CPU Control Cycler</summary>

Allows cycling thru all items, for the targetted CPU with CPU Control Cycler.
Use D-Pad Left and Right to cycle items

```armv7
002D1DF4 E35500FF
002D203C EB0EB9D9
E06807A8 000000B8
E1A04000 E92D403F
E5943028 E59F209C
E5922000 E1520003
1A000022 E59F3090
E28F4090 E5D41001
E5933000 E5D02038
E35200FF E3A05000
03A05001 0A000004
E3130030 0A000013
E5D42000 E3520000
1A000010 E3130030
13A05001 E3130010
12811001 E351000F
03A01011 E3130020
12411001 E3510010
03A0100E E3510000
B3A01013 E3510013
C3A01000 E5C41001
E59F2014 E12FFF32
E3A02001 03A02000
E5C42000 E5C45002
E8BD803F 002D1DD4
006806E4 10002028
00169D94 EB145AB2
E0680864 0000001C
E59F5010 E5D55002
E3550001 03A00001
E3500000 E1A0F00E
00680860 00000000
00169910 EB145BDA
E0680880 00000010
E59F5004 E5D55001
E1A0F00E 00680860
```
</details>

<details>
<summary>Force CPU Vehicle</summary>

Forces all CPUs to use specified vehicle. 

XX: Vehicle ID (https://tcrf.net/Notes:Mario_Kart_7#Karts)

```armv7
004D4BC8 E3A010XX
```
</details>

<details>
<summary>CPUs Don't Move</summary>

CPUs will not move. Bullets work as normal. "No CPU Rocket Start" code included

```armv7
E033354C 0000000C
E3100501 1A00000B
EA0001D0 00000000
0033BE38 E12FFF1E
```
</details>

<details>
<summary>CPU Speed Modifier</summary>

Changes speed CPUs drive on. Can make CPUs super fast as it doesn't have any limits. Original: 3F19999A

```armv7
0033A2A4 XXXXXXXX
```
</details>

<details>
<summary>CPU Always Rubberband</summary>

CPUs will always rubberband, driving at very fast speed as if they were very far behind

```armv7
00339A88 42980000

```
</details>

<details>
<summary>CPU Always Max Probability</summary>

CPUs will always use max probability table, they will always do rocket start, drift, trick, try to snipe etc...

```armv7
00333FE4 E3A01000

```
</details>

<details>
<summary>CPUs Use Your Mii</summary>

DEFINITELY can be done with one line. Didn't try improving it at all, just made the code for fun. Allows making CPUs miis be your mii instead of random generated mii. Might also affect the audience iirc. You need to use "Master Create Mii Heads" or 
else you'll crash!

```armv7
0028433C EBFFF7DD
002822D8 E3A01001

```
</details>
