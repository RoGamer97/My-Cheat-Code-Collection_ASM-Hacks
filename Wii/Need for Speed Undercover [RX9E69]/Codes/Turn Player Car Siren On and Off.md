## Turn Player Car Siren On/Off

Allows turning your car's siren on and off.
Press Classic Controller D-Pad Up and R to enable and disable your car's siren. If you want to make it always enabled, remove the 3rd line then remove CC000000 00000000 line and all lines below it.
If you want to change the controller or button, read the "Button Activator.txt" file inside of the Code Pack RAR

<details>
<summary>Reveal Code</summary>

```powerpc
0403E38C 48000080
0403E99C 48000010
28642A1A FDFE0201
0403E920 48000028
CC000000 00000000
0403E920 41820180
E0000000 00000000
```
</details>