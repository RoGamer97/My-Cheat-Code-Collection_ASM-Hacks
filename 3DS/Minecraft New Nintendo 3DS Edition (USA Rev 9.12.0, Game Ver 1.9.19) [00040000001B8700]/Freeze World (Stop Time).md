## Freeze World (Stop Time)

You can freeze the world/stop time with a press of a button. Everything around you will freeze; mobs, items, damage and other things that update etc. Manipulates online while offline and I guess there's no "server" so things can't update

<details>
<summary>Reveal Code</summary>

Press ZL to freeze everything, ZR to unfreeze. You can change 00004000 to change enable button, 00008000 to change disable button.

Button values: https://gist.github.com/Nanquitas/d6c920a59c757cf7917c2bffa76de860

```armv7
DD000000 00004000
0072090C E3A00001
D0000000 00000000
DD000000 00008000
0072090C E1D007D4
D0000000 00000000
```
</details>