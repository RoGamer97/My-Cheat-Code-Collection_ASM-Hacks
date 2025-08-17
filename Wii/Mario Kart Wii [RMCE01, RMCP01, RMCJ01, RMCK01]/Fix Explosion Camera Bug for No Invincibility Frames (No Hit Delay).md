## Fix Explosion Camera Bug for No Invincibility Frames (No Hit Delay)

This code fixes an issue where the explosion camera is stuck even after the explosion damage ends, caused by getting hit by a damage type different than explosion while in explosion damage when using No Invincibility Frames code (aka No Hit Delay).

This happens because the game only clears the explosion camera after the explosion damage ends, however, if getting hit by another damage type replaces the damage, so the explosion damage end never gets to happen, causing the camera to not be cleared.

The fix simply clears the explosion camera after any damage type is cleared. 

<details>
<summary>NTSC-U</summary>

```powerpc
C256313C 00000005
807F0000 80630024
2C030000 41820010
A0830334 5484003C
B0830334 3860FFFF
60000000 00000000
```
</details>

<details>
<summary>PAL</summary>

```powerpc
	
Fix Explosion Camera Bug for No Invincibility Frames (No Hit Delay) [Ro]

This code fixes an issue where the explosion camera is stuck even after the explosion damage ends, caused by getting hit by a damage type different than explosion while in explosion damage when using No Invincibility Frames code (aka No Hit Delay).

This happens because the game only clears the explosion camera after the explosion damage ends, however, if getting hit by another damage type replaces the damage, so the explosion damage end never gets to happen, causing the camera to not be cleared.

The fix simply clears the explosion camera after any damage type is cleared. 

NTSC-U
C256313C 00000005
807F0000 80630024
2C030000 41820010
A0830334 5484003C
B0830334 3860FFFF
60000000 00000000

PAL
C25674BC 00000005
807F0000 80630024
2C030000 41820010
A0830334 5484003C
B0830334 3860FFFF
60000000 00000000
```
</details>

<details>
<summary>NTSC-J</summary>

```powerpc
C2566E3C 00000005
807F0000 80630024
2C030000 41820010
A0830334 5484003C
B0830334 3860FFFF
60000000 00000000
```
</details>

<details>
<summary>NTSC-K</summary>

```powerpc
C2555514 00000005
807F0000 80630024
2C030000 41820010
A0830334 5484003C
B0830334 3860FFFF
60000000 00000000
```
</details>