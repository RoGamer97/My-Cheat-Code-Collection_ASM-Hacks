## Debug Free Movement

This code enables the Debug Free Movement Mode. I did not make this code, I just ported the N64 code to the Wii VC version but I think it's worth adding here. For some reason, modifying it live does not work, therefore the code will be active at all times. I believe the game's code only runs once on boot, making it not togglable in game.

TCRF Info: This function enables a free-movement mode that lets Mario zoom about freely, though not pass through obstacles because floor checks and wall checks are still done. When holding B, you go fast enough to clip through the hitboxes though. Labelled as FREEMOVE in the source code.

Controls:
* Joystick: Move Mario horizontally.
* D-Up: Move Mario up.
* D-Down: Move Mario down.
* B: Multiply movement speed by 4.
* L: Multiply movement speed by 0.01.

<details>
<summary>Reveal Code</summary>

```powerpc
050D3D58 0C095FAB
```
</details>