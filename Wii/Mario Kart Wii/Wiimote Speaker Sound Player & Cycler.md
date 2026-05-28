## Wiimote Speaker Sound Player & Cycler

This code is an idea i had earlier today - it allows cycling thru every sound & music of the game and have it play on the wiimote speaker. Most of the sounds do play in game too, but some don't, only playing on the wiimote itself. This is just an experimental code, thus it isn't ported for other regions and more of a proof of concept. JoshuaMK's millisecond timer modifier code is used to display the current sound index ID that is selected. The code only works in game.

This code makes uses address 0x800016FC thru 0x800016FE. Make sure no other codes use these addresses.

Here's a small demonstration of the code: https://www.youtube.com/shorts/aiNJ7njQfS4

NTSC-U only (not ported yet)

<details>
<summary>NTSC-U</summary>

```powerpc
C2705C0C 00000011
81830000 9421FF80
BC610008 3CA08034
A0C51462 3FE08000
70CB000C 41820058
889F16FE 2C040001
41820044 A09F16FC
70CB0008 4082000C
38840001 48000008
3884FFFF B09F16FC
3D808070 618C1934
7D8903A6 4E800421
38800003 3D808070
618CC1DC 7D8903A6
4E800421 39600001
41820008 39600000
997F16FE B8610008
38210080 00000000
C27ED9F8 00000002
3D808000 A38C16FC
60000000 00000000
```
</details>