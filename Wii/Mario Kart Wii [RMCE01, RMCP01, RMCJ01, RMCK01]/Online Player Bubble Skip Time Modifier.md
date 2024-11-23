## Online Player Bubble Skip Time Modifier

Allows changing how long until the bubble skips to the next player when finding someone in a Worldwide or Regional. Can be made instant to skip viewing players and going directly to live view/player screen. You can also use "No "All opponents have been found" Text / Skip" (https://mariokartwii.com/showthread.php?tid=2127) to skip the wait after all opponents are shown and "Skip / Instant Bubble Formation"  (https://mariokartwii.com/showthread.php?tid=2126) to skip the bubble animation to get in place before it shows the players.

<details>
<summary>NTSC-U</summary>

Time in Frames:
XX: How long until bubble skips to next player (original is 0x78)
YY: How long until bubble skips to next player when pressing A (original is 0x3C)

```powerpc
005E4D73 000000XX
005E4D7B 000000YY
```
</details>

<details>
<summary>PAL</summary>

Time in Frames:
XX: How long until bubble skips to next player (original is 0x78)
YY: How long until bubble skips to next player when pressing A (original is 0x3C)

```powerpc
00609647 000000XX
0060964F 000000YY
```
</details>

<details>
<summary>NTSC-J</summary>

Time in Frames:
XX: How long until bubble skips to next player (original is 0x78)
YY: How long until bubble skips to next player when pressing A (original is 0x3C)

```powerpc
00608DBB 000000XX
00608DC3 000000YY
```
</details>

<details>
<summary>NTSC-K</summary>

Time in Frames:
XX: How long until bubble skips to next player (original is 0x78)
YY: How long until bubble skips to next player when pressing A (original is 0x3C)


```powerpc
005F7A67 000000XX
005F7A6F 000000YY
```
</details>