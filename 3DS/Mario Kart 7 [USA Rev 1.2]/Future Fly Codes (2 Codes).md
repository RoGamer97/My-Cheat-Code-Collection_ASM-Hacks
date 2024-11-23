## Future Fly Codes

Two Future Fly codes, one is the real code (Same flight from MKW version) other one is artificial (no coordinate manipulation, "native" flight, focused on Koopa Clown Kart being flyable with realistic physics)

<details>
<summary>Future Fly Lite</summary>

Real Future Fly. Allows you to fly freely. You can also rotate and go up and down with the stick. Flight is exactly like MKW version. Lite version because no Up/Down/Left/Right strafe. Code only affects you

```armv7
69696969 69696969
```
</details>

<details>
<summary>"Native Future Fly (Flyable Koopa Clown/Cloud Kart)"</summary>

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