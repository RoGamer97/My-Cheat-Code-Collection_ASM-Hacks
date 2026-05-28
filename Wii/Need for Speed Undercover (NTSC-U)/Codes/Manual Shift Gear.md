## Manual Shift Gear

Makes the car manual shift instead of automatic shift. This option is present in the PS2 version of the game but not on Wii. Gear shifting code is selfmade so isn't perfect but it works. 
Press Classic Controller ZL to downshift, ZR to upshift. Also included code to prevent speedbreaker from activating if ZR is pressed. 
If you want to change the controller or button, read the "Button Activator.txt" file inside of the Code Pack RAR

<details>
<summary>Reveal Code</summary>

```powerpc
0403D5F0 60000000
0403D6A0 4800000C
C203D6EC 0000000E
3D808064 3D408000
A16C2A1A 716C0084
41820040 898A1851
2C0C0000 40820034
8BCA1850 8BEA1852
716C0080 40820014
7C1EF800 4181001C
3BDE0001 48000010
2C1E0002 4180000C
3BDEFFFF 9BCA1850
39600000 41820008
39600001 996A1851
7FC4F378 60000000
60000000 00000000
C22FDAE0 0000000A
7C031838 2C130000
41820040 81930004
818C0000 818C002C
818C0030 2C0C0000
41820028 818C0000
3D608064 616BF870
7C0C5800 40820014
3D808000 986C1852
39600002 996C1850
60000000 00000000
C237A6C8 00000004
3D808064 A18C2A1A
718C0004 41820008
38600000 2C030000
60000000 00000000
0070AC69 00000001
```
</details>