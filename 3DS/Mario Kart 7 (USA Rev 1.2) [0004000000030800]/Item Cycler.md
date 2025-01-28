## Item Cycler

Allows cycling through items with D-Pad Left and D-Pad Right. You can cycle to the left (previous item) and to the right (next item). Items are infinite. Very simple to use, useful for debugging and for fun!

Use with "Infinite Items" or "Rapid Fire" if you want to spam items very fast, without it, it has few frames of delay when spamming. It also avoids item receive SFX every time you use an item (will still play when cycling to another item) and item flash in the roulette will be item use flash instead of item receive flash, just like Mario Kart Wii!

These occur because when you use an item, the item disappears so another one is given to you - with Infinite Item, it doesn't disappear, so it isn't giving you a new item, instead you have infinite use of the item.

You can also use the "Replace Item Receive Anim with Item Use Anim" to replace receive flash with use flash and "No Item Roulette SFX" to avoid item receive SFX

<details>
<summary>Reveal Code</summary>

If you don't want to make the item infinite, replace 0A000010 with 00000000 - You will cycle through items but it will disappear once used, allowing you to obtain items from boxes normally. Pressing the cycle button again will give you the hacked back

```armv7
002D203C EB0EB810
E0680084 000000A8
E1A04000 E92D402F
E590202C E5922000
E5D23098 E3530001
05D2309E 03530000
1A00001D E5D0105A
E59F5074 E5955000
E5D02038 E35200FF
0A000010 E3150030
0A000012 E5D0205B
E3520000 1A00000E
E3150010 12811001
E3150020 12411001
E3510000 B3A01013
E351000F 03A01011
E3510010 03A0100E
E3510013 C3A01000
E5C0105A E59F2014
E12FFF32 E3150030
13A02001 03A02000
E5C4205B E8BD802F
002D1DD4 10002028
```
</details>