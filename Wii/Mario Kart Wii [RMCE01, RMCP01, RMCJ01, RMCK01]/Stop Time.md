## Stop Time

This code will "stop time" with a press of a button, quite literally. In other words, when this code is enabled, "everything" will "freeze", EXCEPT YOU - Items, CPUs, objects, timer,, UI animations and other elements will completely freeze/stop, EXCEPT FOR YOUR KART! You will be able to control your kart and throw stationary items while everything is frozen, since CPUs will be frozen you can abuse them by placing items in front of them or hitting or bumping them then unfreezing time, all actions done while frozen will be done after unfreezing.

Unfortunately, this code is incomplete, there are elements I wanted to implement that I couldn't find or had issues and I have no more time or interest to look into these. These elements are:
Freeze FIB Anim (One that freezes it at the current rotation rather than forcing a specific one)
Freeze Character Anim That is In Play (Freezing character animation while one is playing, for CPUs)
Freeze Object Animation (Some objects are still animated, even though they are frozen)
Freeze Course Texture Animation (Found but instead of freezing it was currently, breaks it as if there was no anim present)
Freeze Explosion (So explosions are frozen during stop)
Better Freeze Items (Unfortunately, it doesn't seem like this game has a main calc function that handles multiple item stuff, including the explosion as well, so it's done in a bad way)
Freeze Kart Animation (Karts are still animated during stop)
No Engine Sound (One that changes live. Actually forgot to look into this)

Credits to JoshuaMK for Kill Lakitu address, 1superchip for Remote Object Freeze address and Vega for POW Check address.

<details>
<summary>NTSC-U</summary>

XXXX: Controller Address
YYYY: FFFF - ZZZZ
ZZZZ: Button value

Button values: https://mariokartwii.com/archive/index.php?thread-44.html

```powerpc
2834XXXX YYYYZZZZ
04530DBC 4E800020
04589870 2C030001
0458989C 2C030001
0460B39C 4E800020
04678700 4E800020
046898E0 38600000
04701934 4E800020
0471A290 4E800020
04790870 48000010
047960E8 480003A4
04796494 48000038
0479F034 60000000
047C3144 60000000
047C3E04 C025FFB4
047E4CC0 38030000
04816DE0 4E800020
048604E4 4E800020
048A1A04 00000000
CC000000 00000000
04530DBC 9421FFC0
04589870 7C030040
0458989C 7C030040
0460B39C 9421FFE0
04678700 9421FFE0
046898E0 3867FF38
04701934 9421FFC0
0471A290 9421FFE0
04790870 48045801
047960E8 408203A4
04796494 40820018
0479F034 90810054
047C3144 4BFFA475
047C3E04 C0231A00
047E4CC0 38030001
04816DE0 9421FF80
048604E4 9421FFD0
048A1A04 3F800000
E0000000 00000000
```
</details>

<details>
<summary>PAL</summary>

803Q: Change Q to 5 for GameCube controller, 4 for all other controllers
XXXX: Controller Address
YYYY: FFFF - ZZZZ
ZZZZ: Button value

Button values: https://mariokartwii.com/archive/index.php?thread-44.html

```powerpc
283QXXXX YYYYZZZZ
04535904 4E800020
04590094 2C030001
045900C0 2C030001
0463C7BC 4E800020
0467CB88 4E800020
0468DD68 38600000
047082D8 4E800020
0471E6C0 4E800020
0479987C 48000010
0479F0F4 480003A4
0479F4A0 48000038
047A8040 60000000
047D1BA4 60000000
047D2854 C025FFB4
047EEFD0 38030000
0482A8F4 4E800020
04864914 4E800020
048A6734 00000000
CC000000 00000000
04535904 9421FFC0
04590094 7C030040
045900C0 7C030040
0463C7BC 9421FFE0
0467CB88 9421FFE0
0468DD68 3867FF38
047082D8 9421FFC0
0471E6C0 9421FFE0
0479987C 4800FA35
0479F0F4 408203A4
0479F4A0 40820018
047A8040 90810054
047D1BA4 4BFFA475
047D2854 B01E00FC
047EEFD0 38030001
0482A8F4 9421FF80
04864914 9421FFD0
048A6734 3F800000
E0000000 00000000
```
</details>

<details>
<summary>NTSC-J</summary>

XXXX: Controller Address
YYYY: FFFF - ZZZZ
ZZZZ: Button value

Button values: https://mariokartwii.com/archive/index.php?thread-44.html

```powerpc
2834XXXX YYYYZZZZ
04535284 4E800020
0458FA14 2C030001
0458FA40 2C030001
0463BE28 4E800020
0467C1F4 4E800020
0468D3D4 38600000
04707944 4E800020
0471DD2C 4E800020
04798EE8 48000010
0479E760 480003A4
0479EB0C 48000038
047A76AC 60000000
047D1210 60000000
047D1EC0 C025FFB4
047EE63C 38030000
04829F60 4E800020
04863F80 4E800020
048A5894 00000000
CC000000 00000000
04535284 9421FFC0
0458FA14 7C030040
0458FA40 7C030040
0463BE28 9421FFE0
0467C1F4 9421FFE0
0468D3D4 3867FF38
04707944 9421FFC0
0471DD2C 9421FFE0
04798EE8 4800FA35
0479E760 408203A4
0479EB0C 40820018
047A76AC 90810054
047D1210 4BFFA475
047D1EC0 B01E00FC
047EE63C 38030001
04829F60 9421FF80
04863F80 9421FFD0
048A5894 3F800000
E0000000 00000000
```
</details>

<details>
<summary>NTSC-K</summary>

XXXX: Controller Address
YYYY: FFFF - ZZZZ
ZZZZ: Button value

Button values: https://mariokartwii.com/archive/index.php?thread-44.html

```powerpc
2835XXXX YYYYZZZZ
0452395C 4E800020
0457E0EC 2C030001
0457E118 2C030001
0462AAD4 4E800020
0466AF30 4E800020
0467C110 38600000
046F6680 4E800020
0470CA68 4E800020
04787C3C 48000010
0478D4B4 480003A4
0478D860 48000038
04796400 60000000
047BFF64 60000000
047BA480 C025FFB4
047DD390 38030000
04818CB4 4E800020
04852CD4 4E800020
04894B94 00000000
CC000000 00000000
0452395C 9421FFC0
0457E0EC 7C030040
0457E118 7C030040
0462AAD4 9421FFE0
0466AF30 9421FFE0
0467C110 3867FF38
046F6680 9421FFC0
0470CA68 9421FFE0
04787C3C 4800FA35
0478D4B4 408203A4
0478D860 40820018
04796400 90810054
047BFF64 4BFFA475
047BA480 C0231A00
047DD390 38030001
04818CB4 9421FF80
04852CD4 9421FFD0
04894B94 3F800000
E0000000 00000000
```
</details>