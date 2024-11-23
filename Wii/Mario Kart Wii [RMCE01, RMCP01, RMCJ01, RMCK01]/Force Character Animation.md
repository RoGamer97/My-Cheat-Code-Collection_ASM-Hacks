## Force Character Animation

This code will force every character to a desired animation. Replace XX with the animation ID. Can be modified to affect specific character(s), code example here: https://mariokartwii.com/showthread.php?tid=2209

<details>
<summary>NTSC-U</summary>

00 = Turning
01 = Boosting/Splitstream
02 = Drift left
03 = Drift right
04 = Wheelie
05 = Accelerating/Driving
06 = Reversing/Looking Backwards
07 = Idle
08 = Win (two arms, 1st)
09 = Win (one arm, => 2nd)
0A = Lose
0B-0E = Freeze
0F = Another idle
10-13 = Freeze
14 = Hit Success/Cheer
15 = Throwing Item Forward
16 = No animation (Multiplayer/LOD?)
17 = Throwing Item Backward
1A = Damage/Out of Bounds
1B-1C = No animation (Multiplayer/LOD?)
1D = In air
1E = Trick

```powerpc
047BD5D8 3BE000XX
```
</details>

<details>
<summary>PAL</summary>

00 = Turning
01 = Boosting/Splitstream
02 = Drift left
03 = Drift right
04 = Wheelie
05 = Accelerating/Driving
06 = Reversing/Looking Backwards
07 = Idle
08 = Win (two arms, 1st)
09 = Win (one arm, => 2nd)
0A = Lose
0B-0E = Freeze
0F = Another idle
10-13 = Freeze
14 = Hit Success/Cheer
15 = Throwing Item Forward
16 = No animation (Multiplayer/LOD?)
17 = Throwing Item Backward
1A = Damage/Out of Bounds
1B-1C = No animation (Multiplayer/LOD?)
1D = In air
1E = Trick

```powerpc
047CC038 3BE000XX
```
</details>

<details>
<summary>NTSC-J</summary>

00 = Turning
01 = Boosting/Splitstream
02 = Drift left
03 = Drift right
04 = Wheelie
05 = Accelerating/Driving
06 = Reversing/Looking Backwards
07 = Idle
08 = Win (two arms, 1st)
09 = Win (one arm, => 2nd)
0A = Lose
0B-0E = Freeze
0F = Another idle
10-13 = Freeze
14 = Hit Success/Cheer
15 = Throwing Item Forward
16 = No animation (Multiplayer/LOD?)
17 = Throwing Item Backward
1A = Damage/Out of Bounds
1B-1C = No animation (Multiplayer/LOD?)
1D = In air
1E = Trick

```powerpc
047CB6A4 3BE000XX
```
</details>

<details>
<summary>NTSC-K</summary>

00 = Turning
01 = Boosting/Splitstream
02 = Drift left
03 = Drift right
04 = Wheelie
05 = Accelerating/Driving
06 = Reversing/Looking Backwards
07 = Idle
08 = Win (two arms, 1st)
09 = Win (one arm, => 2nd)
0A = Lose
0B-0E = Freeze
0F = Another idle
10-13 = Freeze
14 = Hit Success/Cheer
15 = Throwing Item Forward
16 = No animation (Multiplayer/LOD?)
17 = Throwing Item Backward
1A = Damage/Out of Bounds
1B-1C = No animation (Multiplayer/LOD?)
1D = In air
1E = Trick

```powerpc
047BA3F8 3BE000XX
```
</details>