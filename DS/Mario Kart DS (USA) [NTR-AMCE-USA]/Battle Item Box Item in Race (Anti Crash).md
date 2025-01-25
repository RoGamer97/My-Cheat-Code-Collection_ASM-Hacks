## Battle Item Box Item in Race (Anti Crash)

Fixes the "Item Box" item from Battle crashing in race - it can be thrown and works as intended. 

You can only obtain this item outside of Battle with hacks, use and modify "Item Cycler" so the Item Box item is in the cycle in race (Details in the Item Cycler code file) 

<details>
<summary>Reveal Code</summary>

Limit is set to 8 (default Battle limit). If you want to increase it, change 08 to the limit you want and increase 29, 0F and 0B with your new limit value + 1 (Example: For limit value 0B, values are 35, 1B and 17)

```armv7
02105234 48262129
0210523C 4824210F
02105244 4822210B
0215A4C0 00000001
0215A4E0 00000008
0215A4E4 00000008
```
</details>