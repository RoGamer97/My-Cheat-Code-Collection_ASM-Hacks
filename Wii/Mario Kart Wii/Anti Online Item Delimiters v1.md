## Anti Online Item Delimiters v1

This code will prevent you from seeing hacked delimited Lightning, POW and Bloopers. For explanation, during online play there's a timed delay for showing the items mentioned previously, for example, a Lightning can only be seen every ~26 seconds, even if a hacker is spamming it non-stop, however, there's a way to circumvent the delay by using delimiter codes which will show all of the items mentioned previously without any delay. Delimiters work in a way that three said items have a "throw" behavior rather than "use", by this, the item will be used normally, but will also be thrown (dropped), because of the throw, a dragged item event is sent as one of these three items and for some reason that causes the game to use the item on the recieved client. Curiously enough, when one of the three said items are used, they are called by a different function if used by an online player rather than the general one that is called when a player or CPU uses a shock, however, delimited items have the general one get called instead of the online player one. 
I compared the different from a normal shock and a delimited shock and noticed some registers had differences that would not happen if the lightning was fired by myself or a CPU, so I did a check for one of the differences (and made sure it was not a mistake) and if it is in the state that it is when delimited, the function for the item effects will return and never happen.

Unfortunately, this isn't a good approach and not what I planned for, but it's what I was able to do - for now. I wanted to find where the online opponent dragged items was loaded and if it was one of the three items above, return no item (0x14). I found several stuff about these but none of them worked at all. If anyone has it and wants to share, feel free, and thanks.

<details>
<summary>NTSC-U</summary>

```powerpc
C27A91C0 00000002
2C070001 4D820020
9421FFD0 00000000
C27D9580 00000002
2C070001 4D820020
9421FFF0 00000000
C27D4F74 00000002
2C070001 4D820020
9421FFB0 00000000
```
</details>

<details>
<summary>PAL</summary>

```powerpc
C27B7C20 00000002
2C070001 4D820020
9421FFD0 00000000
C27B1B2C 00000002
2C070001 4D820020
9421FFF0 00000000
C27A81B4 00000002
2C070001 4D820020
9421FFB0 00000000
```
</details>

<details>
<summary>NTSC-J</summary>

```powerpc
C27B728C 00000002
2C070001 4D820020
9421FFD0 00000000
C27B1198 00000002
2C070001 4D820020
9421FFF0 00000000
C27A7820 00000002
2C070001 4D820020
9421FFB0 00000000
```
</details>

<details>
<summary>NTSC-K</summary>

```powerpc
C27A5FE0 00000002
2C070001 4D820020
9421FFD0 00000000
C279FEEC 00000002
2C070001 4D820020
9421FFF0 00000000
C2796574 00000002
2C070001 4D820020
9421FFB0 00000000
```
</details>