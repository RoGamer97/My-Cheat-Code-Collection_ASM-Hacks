## Cycle Through Debug Cameras

The game has debug cameras. This custom code allows cycling through them with D-Pad Left/Right. A debug text is shown in each camera indicating the mode and buttons

Four cameras: 
flycam (Free camera, you can't control your car when this camera is set. No code for camera movement is found, so you can't freely move the camera)
flycam (inv) [Same as flycam]
birdseye (Bird view camera, very high above your car pointing down. Text indicates that - changes height, but no code for it is found so height can't be changed)
sidecam (Side camera, camera is on the right side of the car, showing its side. Text indicates that - rotates camera but no code for it is found)

<details>
<summary>Reveal Code</summary>

```armv7
C210363C 00000011
7C651B78 3D808055
A18CEE20 886500E0
718B0003 41820060
888500E1 2C040000
4C820020 718B0001
4082000C 38630001
48000008 3863FFFF
2C03FFFF 40820008
38600012 2C030003
40820008 38600011
2C030010 40820008
38600002 2C030012
40810008 38600000
986500E0 38800001
48000008 38800000
988500E1 4E800020
60000000 00000000
```
</details>