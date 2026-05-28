## Minimap Codes

Minimap related codes

<details>
<summary>Zoomed Out Extended Map</summary>

Zooms out the minimap like in Battle

```armv7
0016DFA8 E3A00003
```
</details>

<details>
<summary>Start Line in Battle Minimap</summary>

Shows start line on minimap in Battle

```armv7
00475FA8 E3A00000
```
</details>

<details>
<summary>Zoom Extended Map w/ 3D Slider</summary>

Allows zooming the extended map with the 3D slider. Unfortunately, character and item icons are not affected therefore they display the wrong location, breaking the purpose of the code. Change 40800000 (4f) to modify how much you can zoom out.
It is possible to fix this issue, it seems like I am missing some stuff

```armv7
0016DEF8 EB144848
0016DF0C EB144843
E0680020 00000024
ED940A2B E59F1010 
ED915A00 ED9F8A03 
EE285A05 EE350A00 
E1A0F00E 1FF81080 
40800000 00000000
```
</details>

<details>
<summary>Minimap Character Icon Rotates with Kart Direction</summary>

Minimap character icons will rotate based on the direction the kart is facing. Similar to how the searchlight/arrow rotates to point in the kart’s direction, the same behavior will apply to the character icons. Includes a fix for damage animation to work

```armv7
00173818 EB14320E
E0680058 00000014
E5951C30 E3110801
15D010A2 03A01001
E1A0F00E 00000000
```
</details>