## Item Cycler v2

Allows cycling through all items with buttons. You can cycle to the left (previous item) and to the right (next item). Items are infinite. Very simple to use, useful for debugging and for fun!

This is v2 of the code, remade from scratch. Like every item hack that writes the item ID and amount, spamming and dropping items in v1 caused issues. Another issue would cause CPUs to throw usable items instead of using them, causing the game to freeze sometimes (Could've been the Item Use Flash Fix).

This version calls a function instead, eliminating the triple item problems. Hook location was changed so item flashes when used (Hooking where I used to would make item not flash, too fast?). Had to make it only call when cycling or using items, if calling every frame, issues would occur when dropping items. All fixed now and I am satisfied with this version.

<details>
<summary>NTSC-U</summary>

If you don't want to make the item infinite, replace 41820048 with 60000000 - You will cycle through items but it will disappear once used, allowing you to obtain items from boxes normally. Pressing the cycle button again will give you the hacked item back.

Or if you want crazy item cycling every frame (items automatically changing, you will use a "random item"), replace 41820048 with 48000020

XXXX: Controller Address
P: For PAL only, 5 for GameCube controller, 4 else
YYYY: Both cycle to previous and next item buttons masked together. E.g: (Wiimote): D-Pad Left (0001) cycles item to the left < and D-Pad Right (0002) cycles item to the right >, therefore YYYY will be 0003 (0001 + 0002 = 0003). Be aware, there are TWO YYYY values, make sure you input both of them!
ZZZZ: Button to cycle item to previous item (cycle to the left <)

Button values: https://mariokartwii.com/archive/index.php?thread-44.html

```powerpc
C278E9B4 00000015
819D0000 818C0004
818C0014 718C0002
4182008C 3D808034
A16C<strong>XXXX</strong> 809D008C
2C040014 889D00B3
41820048 716CYYYY
41820058 899D00B2
2C0C0000 4082004C
716CZZZZ 41820018
2C040000 3884FFFF
4082001C 38800012
48000014 2C040011
38840001 40810008
38800000 989D00B3
387D0088 38A00000
3D80807A 618CDEE0
7D8903A6 4E800421
716BYYYY 39800001
40820008 39800000
999D00B2 807D0000
60000000 00000000
```
</details>

<details>
<summary>PAL</summary>

If you don't want to make the item infinite, replace 41820048 with 60000000 - You will cycle through items but it will disappear once used. Pressing the cycle button again will give you the item again.

Or if you want crazy item cycling every frame (items automatically changing, you will use a "random item"), replace 41820048 with 48000020

XXXX: Controller Address
YYYY: Both cycle to previous and next item buttons masked together. E.g: (Wiimote): D-Pad Left (0001) cycles item to the left < and D-Pad Right (0002) cycles item to the right >, therefore YYYY will be 0003 (0001 + 0002 = 0003). Be aware, there are TWO YYYY values, make sure you input both of them!
ZZZZ: Button to cycle item to previous item (cycle to the left <)

Button values: https://mariokartwii.com/archive/index.php?thread-44.html

```powerpc
C27979C0 00000015
819D0000 818C0004
818C0014 718C0002
4182008C 3D80803P
A16CXXXX 809D008C
2C040014 889D00B3
41820048 716CYYYY
41820058 899D00B2
2C0C0000 4082004C
716CZZZZ 41820018
2C040000 3884FFFF
4082001C 38800012
48000014 2C040011
38840001 40810008
38800000 989D00B3
387D0088 38A00000
3D80807B 618CC940
7D8903A6 4E800421
716BYYYY 39800001
40820008 39800000
999D00B2 807D0000
60000000 00000000
```
</details>

<details>
<summary>NTSC-J</summary>

If you don't want to make the item infinite, replace 41820048 with 60000000 - You will cycle through items but it will disappear once used. Pressing the cycle button again will give you the item again.

Or if you want crazy item cycling every frame (items automatically changing, you will use a "random item"), replace 41820048 with 48000020

XXXX: Controller Address
YYYY: Both cycle to previous and next item buttons masked together. E.g: (Wiimote): D-Pad Left (0001) cycles item to the left < and D-Pad Right (0002) cycles item to the right >, therefore YYYY will be 0003 (0001 + 0002 = 0003). Be aware, there are TWO YYYY values, make sure you input both of them!
ZZZZ: Button to cycle item to previous item (cycle to the left <)

Button values: https://mariokartwii.com/archive/index.php?thread-44.html

```powerpc
C279702C 00000015
819D0000 818C0004
818C0014 718C0002
4182008C 3D808034
A16CXXXX 809D008C
2C040014 889D00B3
41820048 716CYYYY
41820058 899D00B2
2C0C0000 4082004C
716CZZZZ 41820018
2C040000 3884FFFF
4082001C 38800012
48000014 2C040011
38840001 40810008
38800000 989D00B3
387D0088 38A00000
3D80807B 618CBFAC
7D8903A6 4E800421
716BYYYY 39800001
40820008 39800000
999D00B2 807D0000
60000000 00000000
```
</details>

<details>
<summary>NTSC-K</summary>

If you don't want to make the item infinite, replace 41820048 with 60000000 - You will cycle through items but it will disappear once used. Pressing the cycle button again will give you the item again.

Or if you want crazy item cycling every frame (items automatically changing, you will use a "random item"), replace 41820048 with 48000020

XXXX: Controller Address
YYYY: Both cycle to previous and next item buttons masked together. E.g: (Wiimote): D-Pad Left (0001) cycles item to the left < and D-Pad Right (0002) cycles item to the right >, therefore YYYY will be 0003 (0001 + 0002 = 0003). Be aware, there are TWO YYYY values, make sure you input both of them!
ZZZZ: Button to cycle item to previous item (cycle to the left <)

Button values: https://mariokartwii.com/archive/index.php?thread-44.html

```powerpc
C2785D80 00000015
819D0000 818C0004
818C0014 718C0002
4182008C 3D808033
A16CXXXX 809D008C
2C040014 889D00B3
41820048 716CYYYY
41820058 899D00B2
2C0C0000 4082004C
716CZZZZ 41820018
2C040000 3884FFFF
4082001C 38800012
48000014 2C040011
38840001 40810008
38800000 989D00B3
387D0088 38A00000
3D80807A 618CAD00
7D8903A6 4E800421
716BYYYY 39800001
40820008 39800000
999D00B2 807D0000
60000000 00000000
```
</details>
