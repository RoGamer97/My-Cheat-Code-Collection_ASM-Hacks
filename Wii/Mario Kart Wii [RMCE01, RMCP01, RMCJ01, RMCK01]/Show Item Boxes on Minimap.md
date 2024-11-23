## Show Item Boxes on Minimap

This code will show item boxes on minimap as a dot. If an item box is destroyed, the icon will disappear until the item box respawns. You can also choose what color the icon will be. Unfortunately, there are two catches to this code: It will not affect moving item boxes (can only target one object at time, to be worked on a future version of the code) and the other one is that you MUST use the "Show Battle Map Icons" code by CLF78 (I did not include it in my code to not take any credits and to make sure people are aware of his code. "Show Battle Map Icons" code by CLF78: https://mariokartwii.com/showthread.php?tid=1840

This code can be modified to target any object of choice, this includes moving objects: Icons of the moving object will move on the minimap. It is possible that I will work on a v2 of this code where it affects all item boxes (both stationary and moving boxes) - 80887CDC call NTSC-U for reference.

I released a version of this code that shows EVERY object on the minimap: https://mariokartwii.com/showthread.php?tid=2211

<details>
<summary>NTSC-U</summary>

```powerpc
0405E0A8 48000020
```
</details>

<details>
<summary>PAL</summary>

```powerpc
0405E0A8 48000020
```
</details>

<details>
<summary>NTSC-J</summary>

```powerpc
0405E0A8 48000020
```
</details>

<details>
<summary>NTSC-K</summary>

```powerpc
0405E0A8 48000020
```
</details>