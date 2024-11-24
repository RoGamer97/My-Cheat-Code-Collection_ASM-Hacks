## Save Slot Dokan Warp

Dokan Warp is the jump from Honeybee Hive that launches you to the air to a specific location. These codes allow you to press a button to save your location and press another button to dokan warp to that location - you will be launched to the air to the direction of the location you saved and will land there

<details>
<summary>Save Slot Dokan Warp</summary>

This code allows saving a location by pressing your selected button while standing on that location and then allows doing warping to that location via Dokan Warp (The jump from Honeybee Hive). I have designed the code so during the jump you can
go thru walls and ground. After restarting or quitting the course the saved location will remain, therefore, if you change the course and doing warp without saving a new location you'll likely jump to an OOB area. In order to resolve this, use the "Reset Dokan Warp Saved Slot Every Race" code to reset the saved location to start line everytime you restart or quit a course.

XXXXXXXX: Button save location
YYYYYYYY: Button to dokan warp to location

Button values: https://gist.github.com/Nanquitas/d6c920a59c757cf7917c2bffa76de860 ("SPECIAL KEYPAD CODE")

```armv7
002DC034 EB0E9059
002D4A78 EB0EADF4
002D64F4 EB0EA75A
002D6998 EB0EA631
002D64F8 0B0659F2
002D699C 0B0658C9
00396960 ED9C0A00
E06801A0 000000A0
E5841F68 E92D41FF
ED2D0A04 E5D40098
E3500001 05D4009E
03500000 1A000019
E28F6078 E5D6500C
E3A08000 E3580000
0A00000B E3550000
1A000009 E59400DC
E59F1050 E3A02000
E59F3044 E12FFF33
E2848024 EC980A03
EDDF1A0F EE700AE1
EC860A03 E3A05001
03A05000 E5C6500C
E1A00004 E3A01005
E1A02006 E1A03007
E59F4008 00000000
ECBD0A04 E8BD81FF
002D5214 003CC660
01000517 41E00000
E0680250 00000014
E584003C E5840040
E5840F2C E5940074
E1A0F00E 00000000
E0680264 00000010
E5941DA8 E35100FF
E1A0100A E1A0F00E
DD000000 XXXXXXXX
006801C8 E3A08001
D0000000 00000000
DD000000 YYYYYYYY
00680224 E12FFF34
D0000000 00000000
```
</details>

<details>
<summary>Reset Dokan Warp Saved Slot Every Race</summary>

This code will reset the saved location to the start line after restarting or quitting a course to avoid warping to a location saved in another course or in a previous race. If you don't want it to reset so you can warp back to a saved location
done in a previous race, don't use this code

```armv7
00396CD8 EA0BA565
E0680274 00000028
E59F8014 EC9C0A03 
EDDF1A04 EE700AE1 
EC880A03 ED9C0A00 
E59FF004 0068024C 
41C80000 00396CDC 
```
</details>