## Future Fly Codes

Two Future Fly codes, one is the real code (Same flight from MKW version) other one is artificial (no coordinate manipulation, "native" flight, focused on Koopa Clown Kart being flyable with realistic physics)

<details>
<summary>Future Fly Lite</summary>

Real Future Fly. Allows you to fly freely. You can also rotate and go up and down with the stick. Flight is exactly like MKW version. Lite version because no Up/Down/Left/Right strafe. Code only affects you

XXXXXXXX: you can Fly... (Enable code)
YYYYYYYY: Cancel (Disable code)

Button values: https://gist.github.com/Nanquitas/d6c920a59c757cf7917c2bffa76de860 ("SPECIAL KEYPAD CODE")

```armv7
DD000000 XXXXXXXX
002F01B8 EB0E3F90
002D3688 EB0EB263
002D368C EA000003
D0000000 00000000
DD000000 YYYYYYYY
002F01B8 E1A04000
002D3688 E59D2000
002D368C E5812000
D0000000 00000000
E0680000 0000001C
E1A04000 E5D48098 
E3580001 05D4809E 
03580000 08BD8030 
E1A0F00E 00000000
E068001C 000000C8
E5D48098 E3580001 
05D4809E 03580000 
1C9D0A03 1C810A03 
112FFF1E ED2D0A07 
E5948C30 E3888301 
E5848C30 E2848B03 
EE711AE1 EDC81ACB 
EDC41A0E EDC41A0F 
EDC41A10 EDD41A40 
E59470FC E3170002 
ED9F2A1A 0EB12A42 
EE611A82 EDC81AC9 
EDD41A42 ED9F2A16 
EE611A82 E2849018 
EC992A03 EE210A82 
EE610A83 ED880A5B 
EDC80A5D EC910A03 
0DDF1A0A 1DDF1A0A 
E3170003 1E222A21 
1E300A02 1E622AA1 
1E700AA2 1E233A21 
1E311A03 EC810A03 
ECBD0A07 E1A0F00E 
41B80000 C1500000 
40600000 3F000000
```
</details>

<details>
<summary>"Native" Future Fly (Flyable Koopa Clown/Cloud Kart)</summary>

This code allows you to fly. You can move freely in the air like a plane, go up, down, turn, forward and back. Differently from regular Future Fly, this code doesn't mess with coordinates or stuff like this, the game does the physics itself, up and down is
the gravity being replaced with the controller stick up and down, and doing a hook to make it less strong (else it would go up and down very fast) and make it go up/down stronger when accelerating - if you want it to go up and down fast, a hook 
isn't even necessary; this entire code doesn't need hooks but I did a single hook for that reason. Like some other codes included in this release, this is a remake of a code I made in Mario Kart 8 Deluxe and it is exactly how it is in Deluxe, which a small
exception which is that brakes will not be stronger, but releasing accel will make you instant stop. I found brake strenght but it makes reversing slow and I couldn't bother to look for a fix.
The way physics work in MK7 doesn't make it 100% accurate to Deluxe's version but Deluxe version of the code is done the same way as this, but with few more patches for things that aren't in MK7.
The code also modifies some physics such as speed, acceleration, deacceleration, turning speed etc, as well as minimal sound and visual changes to make it accurate to Deluxe and give a feel that the kart is a flyable vehicle rather than a drivable
vehicle - thus, why the code name is Flyable Koopa Clown Kart, because if you use the Koopa Clown Kart, it looks like it's flyable by default, like other Mario games, or maybe even the Cloud Kart because it's a cloud!
Deactivator is not included and code affects everyone rather than only you - did for fun because I love making specific codes for multiple Mario Kart games, such as this and few other codes, which some are even included here. I didn't even test in
VS

```armv7
002D36B0 E3A01008
002D4C10 E3A02008
002D9E84 13A01001
002D9208 E3A00000
002D9678 EA000010
002D96D0 EA00000B
002D972C EA000028
002D97F0 EA0000B6
E02D42F0 0000000C
EDDF0A00 EA000000
41500000 00000000
00304A18 EA0DEF9C
E0680890 00000024
ED900A31 E590C0B8
E31C0001 1DDF0A02
0DDF0A02 EE200A20
EAF2105B BEB33333
BE200000 00000000
002D395C 3D23D70A
006655B0 3F19999A 
006657B4 3F666666 
003CCCE4 E3A0C003
003E314C E3A00001
```
</details>