## Damage Objects on Command

This code will damage most objects (only ones that are affected by Lightning) with a press of a button.

<details>
<summary>NTSC-U</summary>

XXXX: Controller Address (1462 for NTSC-U Wiimote for example)
YYYY: Button value (1000 for Wiimote Minus [-] for example)

Button values: https://mariokartwii.com/archive/index.php?thread-44.html

```powerpc
C2816E1C 00000008
3C80808A 3D808034
A18CXXXX 718CYYYY
41820028 9421FF80
BC610008 38800006
3D808081 618C7780
7D8903A6 4E800421
B8610008 38210080
60000000 00000000
```
</details>

<details>
<summary>PAL</summary>

XXXX: Controller Address (1462 for NTSC-U Wiimote for example)
YYYY: Button value (1000 for Wiimote Minus [-] for example)

Button values: https://mariokartwii.com/archive/index.php?thread-44.html

```powerpc
C282A930 00000008
3C80808B 3D808034
A18CXXXX 718CYYYY
41820028 9421FF80
BC610008 38800006
3D808081 618C7780
7D8903A6 4E800421
B8610008 38210080
60000000 00000000
```
</details>

<details>
<summary>NTSC-J</summary>

XXXX: Controller Address (1462 for NTSC-U Wiimote for example)
YYYY: Button value (1000 for Wiimote Minus [-] for example)

Button values: https://mariokartwii.com/archive/index.php?thread-44.html

```powerpc
C2829F9C 00000008
3C80808B 3D808034
A18C14C2 718C1000
41820028 9421FF80
BC610008 38800006
3D808081 618C7780
7D8903A6 4E800421
B8610008 38210080
60000000 00000000
```
</details>

<details>
<summary>NTSC-K</summary>

XXXX: Controller Address (1462 for NTSC-U Wiimote for example)
YYYY: Button value (1000 for Wiimote Minus [-] for example)

Button values: https://mariokartwii.com/archive/index.php?thread-44.html

```powerpc
C2818CF0 00000008
3C80808A 3D808035
A18CXXXX 718CYYYY
41820028 9421FF80
BC610008 38800006
3D808081 618C7780
7D8903A6 4E800421
B8610008 38210080
60000000 00000000
```
</details>