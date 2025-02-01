## Drop Items on Command

Drops your item by pressing SELECT and R. There's two configurations you can use: Consecutively drop items when the button is held or drop the item once when the button is pressed until it's pressed again.

<details>
<summary>Reveal Code</summary>

To choose the mode, replace XXXXXXXX with one of the values below:
01040000 - Consecutively drop items when the button is held
00040100 - Drop the item once when the button is pressed until it's pressed again

```armv7
020BAB80 EBFD184A
E2000CB0 00000034
E5921000 E92D400F 
E59F101C E5911000 
E59F2010 E0111002 
E1510002 059F100C 
012FFF31 E8BD800F 
XXXXXXXX 021758E8 
020EFF40 00000000
```
</details>