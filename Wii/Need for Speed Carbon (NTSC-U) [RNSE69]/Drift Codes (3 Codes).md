## Drift Codes

Drift related codes

<details>
<summary>Augmented Drift with Handbrake</summary>

You will drift after using the handbrake

```hex
042EEA84 38000001
```
</details>

<details>
<summary>Toggle Drift Mode On/Off</summary>

You can toggle drift mode on and off by pressing 2 and A

You can change toggle button by replacing F6FF0900 by YYYYZZZZ, where ZZZZ is button and YYYY is ZZZZ - FFFF

Button Values: https://mariokartwii.com/archive/index.php?thread-44.html

```hex
28626B32 F6FF0900
042C9A74 38600002
CC000000 00000000
042C9A74 8063014C
E0000000 00000000
```
</details>

<details>
<summary>Toggle Drift Camera On/Off</summary>

You can toggle drift camera (zoomed out cam) on and off by pressing 2 and A. 

You can change toggle button by replacing F6FF0900 by YYYYZZZZ, where ZZZZ is button and YYYY is ZZZZ - FFFF

Button Values: https://mariokartwii.com/archive/index.php?thread-44.html

```powerpc
28626B32 F6FF0900
04093D40 38000001
CC000000 00000000
04093D40 880DCE37
E0000000 00000000
```
</details>