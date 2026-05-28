## Fix Offroad Affecting Star After Cannon Glitch

This code fixes a game "glitch" that causes you to be affected by the offroad while in a star if the star was used before the cannon. What happens is that the game checks for a speed flag which is set when using the star, however, this flag is cleared when entering a cannon, causing offroad to affect the player. A fix was to check for both speed flag and star flag, resolving the issue.

<details>
<summary>NTSC-U</summary>

```powerpc
C2575B94 00000002
700B0080 740C8000
7D606379 00000000
```
</details>

<details>
<summary>PAL</summary>

```powerpc
C257C3F8 00000002
700B0080 740C8000
7D606379 00000000
```
</details>

<details>
<summary>NTSC-J</summary>

```powerpc
C257BD78 00000002
700B0080 740C8000
7D606379 00000000
```
</details>

<details>
<summary>NTSC-K</summary>

```powerpc
C256A450 00000002
700B0080 740C8000
7D606379 00000000
```
</details>