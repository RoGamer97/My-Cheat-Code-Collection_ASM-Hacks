## Force Pursuit End

Forces pursuit to end by command

<details>
<summary>Reveal Code</summary>

Press A and D-Pad Left (horizontal Wiimote, D-Pad Up if Wiimote is vertical) to end pursuit

You can change toggle button by replacing F7F70808 by YYYYZZZZ, where ZZZZ is button and YYYY is ZZZZ - FFFF

Button Values: https://mariokartwii.com/archive/index.php?thread-44.html

```powerpc
04052D1C 38600000
28626B32 F7F70808
04052D1C 38600001
E0000000 00000000
```
</details>