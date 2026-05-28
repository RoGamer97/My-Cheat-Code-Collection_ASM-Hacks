## Cop Spawn Codes

Cop spawning related codes

<details>
<summary>Cops Can Always Spawn</summary>

Allow cops to always be able to spawn, event/mode and limits in specific scenarios. This code is included in "Cops Consecutively Spawn Behind You" and both "Police Helicopter Consecutively Spawns" code when they're enabled by button activator

```powerpc
0400D16C 38600001 
0400D170 4E800020
```
</details>

<details>
<summary>Allow Multiple Helicopters Spawn</summary>

Allows more than one helicopter to spawn. This code is enabled when both "Police Helicopter Consecutively Spawns" codes are enabled by button activator

```powerpc
040102A4 38600000
```
</details>

<details>
<summary>Cops Consecutively Spawn Behind You</summary>

Force cops to consecutively spawn behind you. No new cops can spawn when the max limit of vehicles is reached at the moment (14). "Force Start Pursuit" and "Cops Can Always Spawn" are included in this code when it's enabled
by button activator. Can be used with "Slower Rate Police Helicopter Consecutively Spawns" to consecutively spawn helicopters too, use the slower rate one to prioritize cop cars (read explanation on the code itself).
Press Classic Controller D-Pad Down and R to enable it and disable it. If you want to make this code always enabled without the requirement of buttons, remove 1st line and then remove CC000000 00000000 
line and all lines below it. If you want to change the controller or button, read the "Button Activator.txt" file inside of the Code Pack RAR

```powerpc
28642A1A BDFF4200
0400D16C 38600001 
0400D170 4E800020
04013D0C 48000028
04013D38 60000000
04013F54 60000000
04014848 48000020
042E7254 2C03000F
042E725C 3BC3FFF1 
047068F0 00000000
CC000000 00000000
0400D16C 9421FFD0
0400D170 7C0802A6
04013D0C 41820028
04013D38 4182001C
04013F54 40820010
04014848 41820048
042E7254 2C03000E
042E725C 3BC3FFF2 
047068F0 43C80000
E0000000 00000000
```
</details>

<details>
<summary>Police Helicopter Consecutively Spawns</summary>

Force helicopters to consecutively spawn. If you want to use this with "Cops Consecutively Spawn Behind You", use the "Slower Rate Police Helicopter Consecutively Spawns" code instead because 
this code here will spawn helicopters at the same rate cop cars are spawned, therefore, both helicopters and cop cars will spawn at the same time and there will be less cop cars because there are 
helicopters active and the game has a max limit of vehicles (13, which I couldn't allocate more unfortunately, though I was able to add one more without crash, included in cop spawn code) so to have 
more cop cars but still have few helicopters, use the code below. "Allow Multiple Helicopter Spawn" is included in this code when it's enabld by button activator.
Press Classic Controller D-Pad Down and R to enable it and disable it. If you want to make this code always enabled without the requirement of buttons, remove 1st line and then remove CC000000 00000000 
line and all lines below it. If you want to change the controller or button, read the "Button Activator.txt" file inside of the Code Pack RAR

```powerpc
28642A1A BDFF4200
040102A4 38600000
04012E68 38A00000
04012E6C 48000024
0400FFDC 60000000
04014848 48000020
CC000000 00000000
040102A4 48030C59
04012E68 7C030000
04012E6C 40800030
0400FFDC 40820014
04014848 41820048
E0000000 00000000
```
</details>

<details>
<summary>Slower Rate Police Helicopter Consecutively Spawns</summary>

Force helicopters to consecutively spawn but with a slower rate still fast enough. Made this to be used with "Cops Consecutively Spawn Behind You" code. Explanation of why you should use
this code instead of the one above is on explanation of "Police Helicopter Consecutively Spawns" code. "Allow Multiple Helicopter Spawn" is included in this code when enabled by button activator.
No new helis can spawn when the max limit of pursuit vehicles is reached at the moment.
Rate delay is set to 3, the higher the value is, the slower the rate is. You can modify the rate by modifying "03" from "2C030003" to your desired value.
Press Classic Controller D-Pad Down and R to enable it and disable it. If you want to make this code always enabled without the requirement of buttons, remove 1st line and then remove CC000000 00000000 
line and all lines below it. If you want to change the controller or button, read the "Button Activator.txt" file inside of the Code Pack RAR

```powerpc
28642A1A BDFF4200
C200FFD8 00000004
3D808000 886C1858
38630001 2C030003
41800008 38600000
986C1858 00000000
040102A4 38600000
04012E68 38A00000
04012E6C 48000024
04014848 48000020
CC000000 00000000
0400FFD8 7C1F1840
040102A4 48030C59
04012E68 7C030000
04012E6C 40800030
04014848 41820048
E0000000 00000000
```
</details>



