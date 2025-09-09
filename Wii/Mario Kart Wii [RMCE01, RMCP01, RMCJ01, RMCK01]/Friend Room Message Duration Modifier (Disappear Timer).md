## Friend Room Message Duration Modifier (Disappear Timer)

This code allows you to modify how long a message stays prompted in a friend room. By default, messages disappear after 1 minute. 

This can be considered an upgrade to Vega's "Private Room Messages Stay Prompted Forever" code because his code makes it so friend rooms cannot start. If you want to make messages NEVER disappear, subtract 4 from the address and change 2C00XXXX to 38000000 (Example for NTSC-U: 0462AE08 38000000)

<details>
<summary>NTSC-U</summary>

XXXX: Seconds in Frames (Original is 0x0E10 -> 3600 frames -> 1 minute)

```powerpc
0462AE0C 2C00XXXX
```
</details>

<details>
<summary>PAL</summary>

XXXX: Seconds in Frames (Original is 0x0E10 -> 3600 frames -> 1 minute)

```powerpc
045DA898 2C00XXXX
```
</details>

<details>
<summary>NTSC-J</summary>

XXXX: Seconds in Frames (Original is 0x0E10 -> 3600 frames -> 1 minute)

```powerpc
045DA174 2C00XXXX
```
</details>

<details>
<summary>NTSC-K</summary>

XXXX: Seconds in Frames (Original is 0x0E10 -> 3600 frames -> 1 minute)

```powerpc
045C8A34 2C00XXXX
```
</details>