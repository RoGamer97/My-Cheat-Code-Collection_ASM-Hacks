## Fix Online Players Stuck in Halfpipe (Halfpipe Warp Fix)

This code fixes the issue where online players get stuck in halfpipe state on your screen for a very long time or for the rest of the race when falling ion the void, usually on Rainbow Road.

This happens because the game prevents the player from warping if in halfpipe state. Removing this condition isn't recommended as it can change gameplay aspect, such as players warping and lagging in regular halfpipes.

I've thought a lot about this problems and I came to the conclusion that it only happen when the player is stuck in the void because I don't see a scenario where the player is stuck in air for so long (even in problematic Custom Tracks) - if the player touches the ground, they warp, so for me that's the only scenario where it happens.
So, I decided to fix it based on out of bounds timer and not in air timer while in halfpipe. So, the halfpipe state will be cleared 130 frames after touching out of bounds (2:10 seconds, which is actually the time lakitu takes to put you back on the track).

This is a remake of a code that is in the Wiimmfi payload - shorter version

<details>
<summary>NTSC-U</summary>

If you want to make it based on air time in halfpipe instead, replace A81F0056 with 8004001C and change the time (2C000052 to 2C00XXXX). 

Additionally, because of where I hook the code, you can have the warp happen in halfpipe without clearing the state, just replace 91640008 with 60000000. Be aware that it will only warp based on the timer

```powerpc
C2585734 00000005
81640008 556C056B
41820018 A81F0056
2C000052 4180000C
556B05A8 91640008
7D645B78 00000000
```
</details>

<details>
<summary>PAL</summary>

If you want to make it based on air time in halfpipe instead, replace A81F0056 with 8004001C and change the time (2C000052 to 2C00XXXX). 

Additionally, because of where I hook the code, you can have the warp happen in halfpipe without clearing the state, just replace 91640008 with 60000000. Be aware that it will only warp based on the timer

```powerpc
C258BF58 00000005
81640008 556C056B
41820018 A81F0056
2C000052 4180000C
556B05A8 91640008
7D645B78 00000000
```
</details>

<details>
<summary>NTSC-J</summary>

If you want to make it based on air time in halfpipe instead, replace A81F0056 with 8004001C and change the time (2C000052 to 2C00XXXX). 

Additionally, because of where I hook the code, you can have the warp happen in halfpipe without clearing the state, just replace 91640008 with 60000000. Be aware that it will only warp based on the timer

```powerpc
C258B8D8 00000005
81640008 556C056B
41820018 A81F0056
2C000052 4180000C
556B05A8 91640008
7D645B78 00000000
```
</details>

<details>
<summary>NTSC-K</summary>

If you want to make it based on air time in halfpipe instead, replace A81F0056 with 8004001C and change the time (2C000052 to 2C00XXXX). 

Additionally, because of where I hook the code, you can have the warp happen in halfpipe without clearing the state, just replace 91640008 with 60000000. Be aware that it will only warp based on the timer

```powerpc
C2579FB0 00000005
81640008 556C056B
41820018 A81F0056
2C000052 4180000C
556B05A8 91640008
7D645B78 00000000
```
</details>