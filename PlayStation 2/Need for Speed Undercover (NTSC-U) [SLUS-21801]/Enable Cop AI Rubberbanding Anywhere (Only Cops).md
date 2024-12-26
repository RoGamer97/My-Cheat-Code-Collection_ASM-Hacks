## Enable Cop AI Rubberbanding Anywhere

Enables AI Rubberbanding from Highway Battle anywhere (any mode/event or Free Roam), for cops only, forcing them to always be rubberbanding. Cops are extremely crazy with this code. It's very fun!
Every other AI will behave as normal. If you want every AI to rubberband, use the other code, above this one.

Video explanation of the AI Rubberbanding behavior and the code in action: https://www.youtube.com/watch?v=2qrt8nCXslg

This is my first PlayStation 2 code (and my first time writing MIPS code, and it's hooks, nice!)

<details>
<summary>Codebreaker</summary>

```powerpc
2011D10C 0C0D555D
20355574 8C620054
20355578 8E43009C
2035557C 14600002
20355580 34020001
20355584 AE420130
20355588 03E00008
2011D24C 0C0D5563
2035558C 8E43009C
20355590 14600004
20355594 4615AD41
20355598 E6550138
2035559C 3C0142FA
203555A0 4481A000
203555A4 4602A834
203555A8 03E00008
20413D28 0C0D556B
203555AC 8CA30004
203555B0 8E2200F4
203555B4 10400002
203555B8 34020001
203555BC AFA200E0
203555C0 03E00008
```
</details>

<details>
<summary>PNACH (PCSX2)</summary>

```powerpc
patch=0,EE,2011D10C,extended,0C0D555D
patch=0,EE,20355574,extended,8C620054
patch=0,EE,20355578,extended,8E43009C
patch=0,EE,2035557C,extended,14600002
patch=0,EE,20355580,extended,34020001
patch=0,EE,20355584,extended,AE420130
patch=0,EE,20355588,extended,03E00008
patch=0,EE,2011D24C,extended,0C0D5563
patch=0,EE,2035558C,extended,8E43009C
patch=0,EE,20355590,extended,14600004
patch=0,EE,20355594,extended,4615AD41
patch=0,EE,20355598,extended,E6550138
patch=0,EE,2035559C,extended,3C0142FA
patch=0,EE,203555A0,extended,4481A000
patch=0,EE,203555A4,extended,4602A834
patch=0,EE,203555A8,extended,03E00008
patch=0,EE,20413D28,extended,0C0D556B
patch=0,EE,203555AC,extended,8CA30004
patch=0,EE,203555B0,extended,8E2200F4
patch=0,EE,203555B4,extended,10400002
patch=0,EE,203555B8,extended,34020001
patch=0,EE,203555BC,extended,AFA200E0
patch=0,EE,203555C0,extended,03E00008
```
</details>

