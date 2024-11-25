## Coin Stack Adjust Height in Bullet Bill

This code will fix the issue where the Coin Runners coin stack is clipping inside of the Bullet Bill if a Bullet is used in Battle or if using Coin Stack in Race code. Because of where I hook the code, this will uncap the max amount of coins that can be seen. If you want to cap it, write a hook

<details>
<summary>Reveal Code</summary>

```armv7
E05125CC 00000008
E3100501 03100080
```
</details>