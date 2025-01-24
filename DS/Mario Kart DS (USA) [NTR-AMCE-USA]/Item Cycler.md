## Item Cycler

Allows cycling through items with D-Pad Left and D-Pad Right while holding SELECT. You can cycle to the left (previous item) and to the right (next item). Items are infinite. Very simple to use, useful for debugging and for fun!

<details>
<summary>Reveal Code</summary>

"Item Box" item from Battle is included in the cycle only in Battle mode. It crashes in race if used. If you want it in race for some reason, change 13A02010 to E3A02011

If you don't want to make the item infinite, replace 0A000012 with 00000000 - You will cycle through items but it will disappear once used, allowing you to obtain items from boxes normally. Pressing the cycle button again will give you the hacked item again

```armv7
020BAB7C EBFD1824
E2000C14 00000080
E5930000 E92D400F
E2800030 E5901000
E3510013 E5901024
0A000012 E59F2050
E5922000 E3120701
0A000010 E3120020
12411001 E3120010
12811001 E59F2034
E5922000 E5922008
E3520002 03A02011
13A02010 E3510000
B1A01002 E1510002
C3A01000 E5801024
E59F200C E12FFF32
E8BD800F 021758E8
021759A0 020F47E4
```
</details>