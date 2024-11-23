## Ice Cube Always Visible in N64 Sherbet Land/Everyone is Frozen

Can't decide a code name. This code will make the ice cube that appears when respawning in N64 Sherbet Land always visible (only in N64 Sherbet Land), as well as making the character/vehicle frozen color. Checks added to not work outside of N64 Sherbet Land because the game freezes, else, it would be only 3 lines. 
For reference, first line removes ice break when respawned (not necessary, ice is still visible with other parts of the code, but thought it would be cool, wouldn't make sense to have ice
break particle and sound while the ice itself doesn't break). Hook checks if course is N64 Sherbet Land and applies two booleans to true, thus, causing some branches to not happen and
executing the part of the code wanted (can be done one line but works in every course; crash). Last line is to fix an issue where respawning will remove the frozen color.

Code affects every player. Silly idea that I had Tongue

<details>
<summary>NTSC-U</summary>

```powerpc
0457B69C 60000000
C269A6E4 00000005
7C7F1B78 3D80809C
818C8F68 818C0B68
2C0C001B 40820010
39800001 999F0069
999F007B 00000000
0469AF24 38000000
```
</details>

<details>
<summary>PAL</summary>

```powerpc
04581F00 60000000
C269EB6C 00000005
7C7F1B78 3D80809C
818CD728 818C0B68
2C0C001B 40820010
39800001 999F0069
999F007B 00000000
0469F3AC 38000000
```
</details>

<details>
<summary>NTSC-J</summary>

```powerpc
04581880 60000000
C269E1D8 00000005
7C7F1B78 3D80809C
818CC788 818C0B68
2C0C001B 40820010
39800001 999F0069
999F007B 00000000
0469EA18 38000000
```
</details>

<details>
<summary>NTSC-K</summary>

```powerpc
0456FF58 60000000
C268CF14 00000005
7C7F1B78 3D80809B
818CBD68 818C0B68
2C0C001B 40820010
39800001 999F0069
999F007B 00000000
0468D754 38000000
```
</details>