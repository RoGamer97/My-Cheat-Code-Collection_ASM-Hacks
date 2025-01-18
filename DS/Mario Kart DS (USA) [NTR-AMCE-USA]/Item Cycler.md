## Item Cycler

Allows cycling through items with D-Pad Left and D-Pad Right while holding SELECT. You can cycle to the left (previous item) and to the right (next item). Items are infinite. Very simple to use, useful for debugging and for fun!

<details>
<summary>Reveal Code</summary>

"Item Box" item from Battle is included in the cycle only in Battle mode. It crashes in race if used. If you want it in race for some reason, change 13A02010 to E3A02011

```armv7
020BAB7C EBFD1D1F
E2002000 0000006C
E5930000 E92D400F
E2800030 E5901024
E59F204C E5922000
E3120701 0A00000E
E3120020 12411001
E3120010 12811001
E59F2030 E5922000
E5922008 E3520002
03A02011 13A02010
E3510000 B1A01002
E1510002 C3A01000
E5801024 EB03C9E0
E8BD800F 021758E8
021759A0 00000000
```
</details>