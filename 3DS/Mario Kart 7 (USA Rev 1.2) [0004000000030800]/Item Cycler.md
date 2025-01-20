## Item Cycler

Allows cycling through items with D-Pad Left and D-Pad Right. You can cycle to the left (previous item) and to the right (next item). Items are infinite. Very simple to use, useful for debugging and for fun!

Use with "Infinite Items" if you want to spam items very fast (e.g: Rapid Fire) as it has few frames of delay without it, and to avoid item receive SFX every time you use an item (will still play when cycling to another item). 

You can use "No Item Roulette SFX" to remove item receive SFX entirely. You can also use "Replace Item Receive Anim with Item Use Anim" to replace item receive flash animation on the roulette with the item use flash which is faster and makes it look like Mario Kart Wii!

<details>
<summary>Reveal Code</summary>

If you don't want to make the item infinite, replace 0A000004 with 00000000 - You will cycle through items but it will disappear once used. Pressing the cycle button again will give you the item again

```armv7
002D1DF4 E35500FF
002D203C EB0EB810
E0680084 000000A8
E1A04000 E92D403F 
E590202C E5922000 
E5D23098 E3530001 
05D2309E 03530000 
1A00001D E59F3078 
E28F4078 E5D41001 
E5933000 E5D02038 
E35200FF 0A000004 
E3130030 0A000011 
E5D42000 E3520000 
1A00000E E3130010 
12811001 E3130020 
12411001 E3510000 
B3A01013 E351000F 
03A01011 E3510010 
03A0100E E3510013 
C3A01000 E5C41001 
E59F2010 E12FFF32 
E3A02001 03A02000 
E5C42000 E8BD803F 
002D1DD4 10002028 
```
</details>