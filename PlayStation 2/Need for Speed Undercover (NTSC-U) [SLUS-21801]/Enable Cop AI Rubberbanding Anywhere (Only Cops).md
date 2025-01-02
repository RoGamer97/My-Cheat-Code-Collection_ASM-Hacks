## Enable Cop AI Rubberbanding Anywhere

Enables AI Rubberbanding from Highway Battle anywhere (any mode/event or Free Roam), for cops only. Forces them to always be rubberbanding. Cops are extremely crazy with this code. It's very fun!
Every other AI will behave as normal, including Chinese mobs from Outrun Carmen event (They use cop AI but I added a check to exclude rubberbanding in that event). If you want every AI to rubberband, use the other code, above this one.

Video explanation of the AI Rubberbanding behavior and the code in action: https://www.youtube.com/watch?v=2qrt8nCXslg

This is my first PlayStation 2 code (and my first time writing MIPS code, and it's a hook, nice!). MIPS is so tricky that code that’s supposed to be short ends up long because of MIPS weirdness. LOOONG code

<details>
<summary>Codebreaker</summary>

```mips
2011CF04 0C0D555C
2011D24C 0C0D5570
20415D94 0C0D5579
20355570 8E43009C
20355574 14600010
20355578 00000000
2035557C 3C010068
20355580 8C245E70
20355584 8C840F90
20355588 10800009
2035558C 00000000
20355590 001F1821
20355594 0C0CFF54
20355598 00000000
2035559C 0003F821
203555A0 3C0107BB
203555A4 3423F3A6
203555A8 10430003
203555AC 00000000
203555B0 34030001
203555B4 AE430130
203555B8 4600A034
203555BC 03E00008
203555C0 8E43009C
203555C4 14600005
203555C8 00000000
203555CC 4615AD41
203555D0 E6550138
203555D4 3C0142FA
203555D8 4481A000
203555DC 4602A834
203555E0 03E00008
203555E4 00001021
203555E8 8E250068
203555EC 8CA30094
203555F0 14600003
203555F4 00000000
203555F8 34020001
203555FC AFA20000
20355600 03E00008
```
</details>

<details>
<summary>PNACH (PCSX2)</summary>

```mips
patch=0,EE,2011CF04,extended,0C0D555C
patch=0,EE,2011D24C,extended,0C0D5570
patch=0,EE,20415D94,extended,0C0D5579
patch=0,EE,20355570,extended,8E43009C
patch=0,EE,20355574,extended,14600010
patch=0,EE,20355578,extended,00000000
patch=0,EE,2035557C,extended,3C010068
patch=0,EE,20355580,extended,8C245E70
patch=0,EE,20355584,extended,8C840F90
patch=0,EE,20355588,extended,10800009
patch=0,EE,2035558C,extended,00000000
patch=0,EE,20355590,extended,001F1821
patch=0,EE,20355594,extended,0C0CFF54
patch=0,EE,20355598,extended,00000000
patch=0,EE,2035559C,extended,0003F821
patch=0,EE,203555A0,extended,3C0107BB
patch=0,EE,203555A4,extended,3423F3A6
patch=0,EE,203555A8,extended,10430003
patch=0,EE,203555AC,extended,00000000
patch=0,EE,203555B0,extended,34030001
patch=0,EE,203555B4,extended,AE430130
patch=0,EE,203555B8,extended,4600A034
patch=0,EE,203555BC,extended,03E00008
patch=0,EE,203555C0,extended,8E43009C
patch=0,EE,203555C4,extended,14600005
patch=0,EE,203555C8,extended,00000000
patch=0,EE,203555CC,extended,4615AD41
patch=0,EE,203555D0,extended,E6550138
patch=0,EE,203555D4,extended,3C0142FA
patch=0,EE,203555D8,extended,4481A000
patch=0,EE,203555DC,extended,4602A834
patch=0,EE,203555E0,extended,03E00008
patch=0,EE,203555E4,extended,00001021
patch=0,EE,203555E8,extended,8E250068
patch=0,EE,203555EC,extended,8CA30094
patch=0,EE,203555F0,extended,14600003
patch=0,EE,203555F4,extended,00000000
patch=0,EE,203555F8,extended,34020001
patch=0,EE,203555FC,extended,AFA20000
patch=0,EE,20355600,extended,03E00008
```
</details>

