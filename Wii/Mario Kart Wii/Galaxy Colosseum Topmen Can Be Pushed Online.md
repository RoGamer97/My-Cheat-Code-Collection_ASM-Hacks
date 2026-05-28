## Galaxy Colosseum Topmen Can Be Pushed Online

This code allows the topmen from Galaxy Colosseum to be pushed online, either by hitting them or boosting into them. It seems like the function that does these actions is never called online because there's a check that skips the call when online. I'm not sure exactly what the check is about, the value that it checks is loaded in an object collision function so I'll suppose it is something related to object collision types (similarly to how cataquacks continue walking in Time Trials when collided with?).
This code also makes the topmen chase other players if they hit him on your screen.

<details>
<summary>NTSC-U</summary>

```powerpc
0474F9D4 60000000
```
</details>

<details>
<summary>PAL</summary>

```powerpc
04757650 60000000
```
</details>

<details>
<summary>NTSC-J</summary>

```powerpc
04756CBC 60000000
```
</details>

<details>
<summary>NTSC-K</summary>

```powerpc
04745A10 60000000
```
</details>