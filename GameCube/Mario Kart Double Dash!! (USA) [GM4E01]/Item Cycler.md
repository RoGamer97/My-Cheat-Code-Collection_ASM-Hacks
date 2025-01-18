## Item Cycler

Allows cycling through items with D-Pad Left and D-Pad Right. You can cycle to the left (previous item) and to the right (next item). Items are infinite. Very simple to use, useful for debugging and for fun!

Only the second character (the second one you select in character selection, who starts on the back of the kart and uses items) will have items, to avoid item limits from filling up faster and to avoid a problem with the item roulette HUD (HUD was modified and included, working perfectly).

When the given item limit is reached (maximum items in play), you can't get and use it until there's room for it to be in play.

I had difficulty finding a reliable way to clear items, but after lots of experiments, I finally found a way. However, it has a side effect of keeping the shadow and particle of the item where it was cleared. I can't find a fix or a way to clear it without problems, but it's no big deal

<details>
<summary>Reveal Code</summary>

```armv7
0414FA9C 60000000
0414FAAC 60000000
041500E4 38600000
C2150144 00000003
38600010 2C1B0000
41820008 8879FF90
90610008 00000000
C2189DA8 00000017
806DAB20 9421FF80
BC610008 7C7F1B78
8B5FFF90 3D808037
A14C6280 714B0003
41820068 899FFF8F
2C0C0000 4082005C
807F02D0 2C030000
41820014 3D808021
618CE368 7D8903A6
4E800421 714B0001
41820020 3B5AFFFF
2C1A0010 4182FFF8
2C1A0000 40800024
3B400013 4800001C
3B5A0001 2C1A0010
4182FFF8 2C1A0013
40810008 3B400000
9B5FFF90 935F0254
3B400010 935F024C
714A0003 39800001
40820008 39800000
999FFF8F B8610008
38210080 00000000
C21FBE9C 00000004
3BE00001 2C1E0000
40820014 3D80801F
618CBED0 7D8903A6
4E800420 00000000
```
</details>