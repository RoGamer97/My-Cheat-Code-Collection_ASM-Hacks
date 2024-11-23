## Item Cycler

This code will allow cycling through items. You can cycle to the left (decrement) or to the right (increment). The items are infinite but you can make a deactivator to disable the code at will. It is coded from Bully's Always Have Item code.
Useful for debugging purposes. Only NTSC-U has been tested.

<details>
<summary>NTSC-U</summary>

XXXX: Controller Address
YYYY: Both buttons values that will cycle items left and right, masked together (LLLL + RRRR = YYYY). E.g (Wiimote): D-Pad Left (0001) cycles item to the left < and D-Pad Right (0002) cycles item to the right >, therefore YYYY will be 0003 (0001 + 0002 = 0003)
LLLL: Button value that will cycle items to the left < (decrement) 
RRRR: Button value that will cycle items to the right > (increment)

Button values: https://mariokartwii.com/archive/index.php?thread-44.html

```powerpc
C27E4B88 00000013
48000009 00000000
7CC802A6 3CE08034
89460000 A187XXXX
718BYYYY 41820040
8BE60001 2C1F0000
40820034 718BLLLL
41820014 2C0A0000
394AFFFF 40820020
39400013 718BRRRR
41820014 2C0A0012
394A0001 40810008
39400000 3BE00001
40820008 3BE00000
9BE60001 99460000
9144008C 38C00001
2C0A0005 4182000C
2C0A0010 41800008
38C00003 90C40090
60000000 00000000
C278894C 00000002
3BE00001 9BFD0238
83E3008C 00000000
047E4E00 60000000
```
</details>

<details>
<summary>PAL</summary>

XXXX: Controller Address
YYYY: Both buttons values that will cycle items left and right, masked together (LLLL + RRRR = YYYY). E.g (Wiimote): D-Pad Left (0001) cycles item to the left < and D-Pad Right (0002) cycles item to the right >, therefore YYYY will be 0003 (0001 + 0002 = 0003)
LLLL: Button value that will cycle items to the left < (decrement) 
RRRR: Button value that will cycle items to the right > (increment)

Button values: https://mariokartwii.com/archive/index.php?thread-44.html

```powerpc
C27EEE98 00000013
48000009 00000000
7CC802A6 3CE08034
89460000 A187XXXX
718BYYYY 41820040
8BE60001 2C1F0000
40820034 718BLLLL
41820014 2C0A0000
394AFFFF 40820020
39400013 718BRRRR
41820014 2C0A0012
394A0001 40810008
39400000 3BE00001
40820008 3BE00000
9BE60001 99460000
9144008C 38C00001
2C0A0005 4182000C
2C0A0010 41800008
38C00003 90C40090
60000000 00000000
C2791958 00000002
3BE00001 9BFD0238
83E3008C 00000000
047EF110 60000000
```
</details>

<details>
<summary>NTSC-J</summary>

XXXX: Controller Address
YYYY: Both buttons values that will cycle items left and right, masked together (LLLL + RRRR = YYYY). E.g (Wiimote): D-Pad Left (0001) cycles item to the left < and D-Pad Right (0002) cycles item to the right >, therefore YYYY will be 0003 (0001 + 0002 = 0003)
LLLL: Button value that will cycle items to the left < (decrement) 
RRRR: Button value that will cycle items to the right > (increment)

Button values: https://mariokartwii.com/archive/index.php?thread-44.html

```powerpc
C27EE504 00000013
48000009 00000000
7CC802A6 3CE08034
89460000 A187XXXX
718BYYYY 41820040
8BE60001 2C1F0000
40820034 718BLLLL
41820014 2C0A0000
394AFFFF 40820020
39400013 718BRRRR
41820014 2C0A0012
394A0001 40810008
39400000 3BE00001
40820008 3BE00000
9BE60001 99460000
9144008C 38C00001
2C0A0005 4182000C
2C0A0010 41800008
38C00003 90C40090
60000000 00000000
C2790FC4 00000002
3BE00001 9BFD0238
83E3008C 00000000
047EE77C 60000000
```
</details>

<details>
<summary>NTSC-K</summary>

XXXX: Controller Address
YYYY: Both buttons values that will cycle items left and right, masked together (LLLL + RRRR = YYYY). E.g (Wiimote): D-Pad Left (0001) cycles item to the left < and D-Pad Right (0002) cycles item to the right >, therefore YYYY will be 0003 (0001 + 0002 = 0003)
LLLL: Button value that will cycle items to the left < (decrement) 
RRRR: Button value that will cycle items to the right > (increment)

Button values: https://mariokartwii.com/archive/index.php?thread-44.html

```powerpc
C27DD258 00000013
48000009 00000000
7CC802A6 3CE08035
89460000 A187XXXX
718BYYYY 41820040
8BE60001 2C1F0000
40820034 718BLLLL
41820014 2C0A0000
394AFFFF 40820020
39400013 718BRRRR
41820014 2C0A0012
394A0001 40810008
39400000 3BE00001
40820008 3BE00000
9BE60001 99460000
9144008C 38C00001
2C0A0005 4182000C
2C0A0010 41800008
38C00003 90C40090
60000000 00000000
C277FD18 00000002
3BE00001 9BFD0238
83E3008C 00000000
047DD4D0 60000000
```
</details>