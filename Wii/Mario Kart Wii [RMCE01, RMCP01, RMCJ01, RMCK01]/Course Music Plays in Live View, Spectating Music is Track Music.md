## Course Music Plays in Live View/Spectating Music is Track Music

These codes will play the music of the course of the race that you're spectating. 

There are three different versions of this code:

Code 1: Both Live view and course music starts playing immediately when entering Live View "Please wait a moment..." screen. Course music will always be normal volume while live view music will always be lower volume, creating a cool mashup and giving priority to the course music. 
if you don't want live view music in the background, only course music (and with volume changing correctly), use Code 2.

Code 2: Live view music won't play at all, only course music, which starts playing immediately when entering Live View "Please wait a moment..." screen. Differently from Code 1 where the course music volume is always normal volume, this version here has volume changing correctly; the course music volume will be lower during "Please wait a moment..." screen and then normal once the message disappears and spectating starts.

Code 3: Live view music starts playing immediately when entering Live View "Please wait a moment..." while course music will only start playing once the message disappears and spectating starts.

YOU MUST USE ONLY ONE OF THESE.


### Code 1 (Both live view and course music plays together, immediately)

<details>
<summary>NTSC-U</summary>

If you don't want live view music in the background, only course music (and with volume changing correctly), use Code 2

```powerpc
04617B3C C0252074
C2600FB4 00000005
7FE802A6 3C60809C
8063DBB0 3D808070
618C8750 7D8903A6
4E800421 7FE803A6
60000000 00000000
```
</details>

<details>
<summary>PAL</summary>

If you don't want live view music in the background, only course music (and with volume changing correctly), use Code 2.

```powerpc
0464A34C C02597A4
C2631E68 00000005
7FE802A6 3C60809C
806327F0 3D808071
618C01F4 7D8903A6
4E800421 7FE803A6
60000000 00000000
```
</details>

<details>
<summary>NTSC-J</summary>

If you don't want live view music in the background, only course music (and with volume changing correctly), use Code 2.

```powerpc
046499B8 C0258904
C26315B4 00000005
7FE802A6 3C60809C
80631850 3D808070
618CF860 7D8903A6
4E800421 7FE803A6
60000000 00000000
```
</details>

<details>
<summary>NTSC-K</summary>

If you don't want live view music in the background, only course music (and with volume changing correctly), use Code 2.

```powerpc
04638664 C0257BDC
C2620260 00000005
7FE802A6 3C60809B
80630E30 3D80806F
618CE59C 7D8903A6
4E800421 7FE803A6
60000000 00000000
```
</details>

### Code 2 (Only course music plays, volume changes correctly)

<details>
<summary>NTSC-U</summary>

Live view music will not play, only course music. Differently from Code 1 where the course music volume is always normal volume, this version here has volume changing correctly; the course music volume will be lower during "Please wait a moment..." screen and then normal once the message disappears and spectating starts

```powerpc
C2617B20 00000005
7C1C0378 8063DBB0
3D808070 618C8750
7D8903A6 4E800421
7C641B78 7F80E378
3C60809C 00000000
C2617B7C 00000005
7C1C0378 8063DBB0
3D808070 618C8750
7D8903A6 4E800421
7C641B78 7F80E378
3C60809C 00000000
```
</details>

<details>
<summary>PAL</summary>

Live view music will not play, only course music. Differently from Code 1 where the course music volume is always normal volume, this version here has volume changing correctly; the course music volume will be lower during "Please wait a moment..." screen and then normal once the message disappears and spectating starts

```powerpc
C264A330 00000005
7C1C0378 806327F0
3D808071 618C01F4
7D8903A6 4E800421
7C641B78 7F80E378
3C60809C 00000000
C264A38C 00000005
7C1C0378 806327F0
3D808071 618C01F4
7D8903A6 4E800421
7C641B78 7F80E378
3C60809C 00000000
```
</details>

<details>
<summary>NTSC-J</summary>

Live view music will not play, only course music. Differently from Code 1 where the course music volume is always normal volume, this version here has volume changing correctly; the course music volume will be lower during "Please wait a moment..." screen and then normal once the message disappears and spectating starts

```powerpc
C264999C 00000005
7C1C0378 80631850
3D808070 618CF860
7D8903A6 4E800421
7C641B78 7F80E378
3C60809C 00000000
C26499F8 00000005
7C1C0378 80631850
3D808070 618CF860
7D8903A6 4E800421
7C641B78 7F80E378
3C60809C 00000000
```
</details>

<details>
<summary>NTSC-K</summary>

Live view music will not play, only course music. Differently from Code 1 where the course music volume is always normal volume, this version here has volume changing correctly; the course music volume will be lower during "Please wait a moment..." screen and then normal once the message disappears and spectating starts

```powerpc
C2638648 00000005
7C1C0378 80630E30
3D80806F 618CE59C
7D8903A6 4E800421
7C641B78 7F80E378
3C60809B 00000000
C26386A4 00000005
7C1C0378 80630E30
3D80806F 618CE59C
7D8903A6 4E800421
7C641B78 7F80E378
3C60809B 00000000
```
</details>

### Code 3 (Live view music plays immediately, course music plays once "Please wait a moment..." message disappears; spectating start)

<details>
<summary>NTSC-U</summary>

If you don't want live view music in the background (silent during "Please wait a moment...", only course music once message disappears, change first line value from "9421FFF0" to "4E800020" 

```powerpc
04617B60 9421FFF0
C2617B20 00000005
7C1C0378 8063DBB0
3D808070 618C8750
7D8903A6 4E800421
7C641B78 7F80E378
3C60809C 00000000
```
</details>

<details>
<summary>PAL</summary>

If you don't want live view music in the background (silent during "Please wait a moment...", only course music once message disappears, change first line value from "9421FFF0" to "4E800020" 

```powerpc
0464A370 9421FFF0
C264A330 00000005
7C1C0378 806327F0
3D808071 618C01F4
7D8903A6 4E800421
7C641B78 7F80E378
3C60809C 00000000
```
</details>

<details>
<summary>NTSC-J</summary>

If you don't want live view music in the background (silent during "Please wait a moment...", only course music once message disappears, change first line value from "9421FFF0" to "4E800020" 

```powerpc
046499DC 9421FFF0
C264999C 00000005
7C1C0378 80631850
3D808070 618CF860
7D8903A6 4E800421
7C641B78 7F80E378
3C60809C 00000000
```
</details>

<details>
<summary>NTSC-K</summary>

If you don't want live view music in the background (silent during "Please wait a moment...", only course music once message disappears, change first line value from "9421FFF0" to "4E800020" 

```powerpc
04638688 9421FFF0
C2638648 00000005
7C1C0378 80630E30
3D80806F 618CE59C
7D8903A6 4E800421
7C641B78 7F80E378
3C60809B 00000000
```
</details>