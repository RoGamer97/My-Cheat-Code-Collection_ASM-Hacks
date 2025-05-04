## Prevent Item Usage in Bullet Bill

This code prevents using items in Bullet Bill. It's useful because in most packs, "No Bullet Icon" is present, allowing you to get items in Bullet, however, there are two problems with this:

* It may be unfair at times and out of place. By preventing the usage, you can get items, but you cannot use them until the Bullet ends.
* Using status items will just waste them, for example: Using a Star or a Mushroom will just do nothing and you'll lose your item. This is the main reason why I made this code

There are two versions of this code:

Code 1 prevents all item usage in Bullet.

Code 2 only prevent status items only (Mushroom, Golden, Star, Mega, Bullet), all other items are still usable.

### Code 1 (Prevent all item usage in Bullet)

<details>
<summary>NTSC-U</summary>

```powerpc
0478EC38 3C600A0C
```
</details>

<details>
<summary>PAL</summary>

```powerpc
04797BB0 3C600A0C
```
</details>

<details>
<summary>NTSC-J</summary>

```powerpc
0479721C 3C600A0C
```
</details>

<details>
<summary>NTSC-K</summary>

```powerpc
04785F70 3C600A0C
```
</details>

### Code 2 (Prevent status items only)

<details>
<summary>NTSC-U</summary>

```powerpc
C278EC38 00000008
3C60020C 4800000D
0405090A 0F0BFF00
7D6802A6 809D008C
898B0000 2C0C00FF
41820018 7C046000
4182000C 396B0001
4BFFFFE4 64630800
60000000 00000000
```
</details>

<details>
<summary>PAL</summary>

```powerpc
C2797BB0 00000008
3C60020C 4800000D
0405090A 0F0BFF00
7D6802A6 809D008C
898B0000 2C0C00FF
41820018 7C046000
4182000C 396B0001
4BFFFFE4 64630800
60000000 00000000
```
</details>

<details>
<summary>NTSC-J</summary>

```powerpc
C279721C 00000008
3C60020C 4800000D
0405090A 0F0BFF00
7D6802A6 809D008C
898B0000 2C0C00FF
41820018 7C046000
4182000C 396B0001
4BFFFFE4 64630800
60000000 00000000
```
</details>

<details>
<summary>NTSC-K</summary>

```powerpc
C2785F70 00000008
3C60020C 4800000D
0405090A 0F0BFF00
7D6802A6 809D008C
898B0000 2C0C00FF
41820018 7C046000
4182000C 396B0001
4BFFFFE4 64630800
60000000 00000000
```
</details>

