## Cycle Through Debug Cameras

The game has debug cameras left over from the Wii version. This custom code allows cycling through them with D-Pad Left/Right. A debug text is shown in each camera indicating the mode and buttons

Four cameras: 
flycam (Free camera, you can't control your car when this camera is set. No code for camera movement could be found [Not even on Wii], so you can't freely move the camera)
flycam (inv) [Same as flycam]
birdseye (Bird view camera, very high above your car pointing down. Text indicates that DOWN changes height, but no code for it could be found [not even on Wii] so height can't be changed)
sidecam (Side camera, camera is on the right side of the car, showing its side. Text indicates that - rotates camera, MINUS button is not present in 3DS and no code for it could be found [not even on Wii])

<details>
<summary>Reveal Code</summary>

```armv7
00355958 00000000
00355984 EA07E9A2
E0550014 00000070
E3A01000 E1A02000 
E5D200D4 E59F3058 
E5933000 E3130030 
0A00000E E5D210D5
E3510000 1A00000B 
E3130020 12400001
02800001 E3700001 
03A00013 E3500003 
03A00011 E3500010 
03A00002 E3500013 
C3A00000 E5C200D4 
E3A01001 03A01000 
E5C210D5 E1A0F00E 
0051B40C 14981518 
```
</details>