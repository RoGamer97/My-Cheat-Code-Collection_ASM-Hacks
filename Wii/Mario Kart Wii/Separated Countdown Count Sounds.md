## Separated Countdown Count Sounds

This code will separate the countdown count sounds to allow the user to play different sounds (and any) on each count number. This is useful for modders who want to customize their countdown sounds to have a voice saying the number (inspired on the old classic starting music song edit). This will work in Battle as well. The values are the revo_kart.brsar index of the song - adding new entries should work for this. 

<details>
<summary>NTSC-U</summary>

XXXX/YYY/ZZZZ: 3, 2, 1 Sound (Revo Index ID)

```powerpc
C2835D50 00000004
38800XXX 2C060001
41800000 4181000C
38800YYY 48000000
38800ZZZ 00000000
```
</details>

<details>
<summary>PAL</summary>

XXXX/YYY/ZZZZ: 3, 2, 1 Sound (Revo Index ID)

```powerpc
C28577E0 00000004
38800XXX 2C060001
41800000 4181000C
38800YYY 48000000
38800ZZZ 00000000
```
</details>

<details>
<summary>NTSC-J</summary>

XXXX/YYY/ZZZZ: 3, 2, 1 Sound (Revo Index ID)

```powerpc
C2856E4C 00000004
38800XXX 2C060001
41800000 4181000C
38800YYY 48000000
38800ZZZ 00000000
```
</details>

<details>
<summary>NTSC-K</summary>

XXXX/YYY/ZZZZ: 3, 2, 1 Sound (Revo Index ID)

```powerpc
C2845BA0 00000004
38800XXX 2C060001
41800000 4181000C
38800YYY 48000000
38800ZZZ 00000000
```
</details>