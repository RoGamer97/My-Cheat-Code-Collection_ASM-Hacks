## Change Camera Perspective in Race (Like Live View/Replay)

This code allows you to change the camera perspective in race/battle as if you were watching Live View or Ghost Replay. Just press -/C/X/Z to toggle the camera perspective.

If you use 2nd line alone, you won't be able to change camera perspective in race, but you will be able to change camera perspective after race.

<details>
<summary>NTSC-U</summary>

```powerpc
04597894 3800000C
04597910 38600001
```
</details>

<details>
<summary>PAL</summary>

```powerpc
045A28CC 3800000C
045A2948 38600001
```
</details>

<details>
<summary>NTSC-J</summary>

```powerpc
045A224C 3800000C
045A22C8 38600001
```
</details>

<details>
<summary>NTSC-K</summary>

```powerpc
04590924 3800000C
045909A0 38600001
```
</details>