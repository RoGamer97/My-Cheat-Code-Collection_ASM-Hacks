## Course Object Codes

Codes related to course objects

<details>
<summary>Damage/Destroy Objects on Command</summary>

Damage/Destroy objects with a press of a button.
XXXXXXXX: Button to damage/destroy objects

Button values: https://gist.github.com/Nanquitas/d6c920a59c757cf7917c2bffa76de860 ("SPECIAL KEYPAD CODE")

```armv7
0036DEB8 E1A05000
DD000000 XXXXXXXX
0036DEB8 EB0C4850
E0680000 00000018
E1A05000 E92D400F
E59F1004 E12FFF31
E8BD800F 0036C208
D2000000 00000000
```
</details>

<details>
<summary>Damage/Destroy Objects on Contact</summary>

Objects will be damaged/destroyed when touched

```armv7
003422D8 E3A02003
```
</details>

<details>
<summary>Objects Damage You</summary>

Changes object behavior to hit you when touched
XX: Damage Type
0-7: Go Thru
8-9: Wall
A: Spin Out (1 time)
B-C: Spin Out (2 times)
D: Fire Spin Out (2 times)
E: Spin Out (2 times)
F: Knockback Flip (1 time)
10: Side Knockback Flip (1 time)
11: Side Knockback Flip (2 times)
12: Side Knockback Flip (1 time)
13: Side Knockback Flip (2 times)
14-15: Crush
16-17: Reject Wall
18: Stronger Reject Wall
19+: Go Thru

```armv7
0034278C EB0CF621
E0680018 0000000C
E3A010XX E3510019
E1A0F00E 00000000
```
</details>

<details>
<summary>VS Objects in Time Trials</summary>

Enables VS Objects in Time Trials, for example, normal crates, item boxes etc

```armv7
0036C1A0 E3A00001
0036C1F8 E3A00000
```
</details>

<details>
<summary>Offline Only Objects Appear Online</summary>

Makes Offline Only Objects Appear Online, for example, Cheep Cheeps and Maw-Ray in Koopa Cape

```armv7
0036C044 E3A00000
```
</details>

<details>
<summary>Item Box Animation Speed Modifier</summary>

Changes Item Box Animation speed

```armv7
0035C62C E281100A
0035C640 E281100A
```
</details>

<details>
<summary>Moving Item Box Speed Modifier</summary>

Changes Moving Item Box speed

```armv7
003919D0 3F000000
```
</details>

<details>
<summary>Moving Coin Speed Modifier</summary>

Changes Moving Coin speed

```armv7
00412128 E28000FF
```
</details>

<details>
<summary>Glider Board Ramps Always Open</summary>

Makes all glider board ramps always open

```armv7
00367138 E3A00001
00367168 00000000
003671DC E3A01001
```
</details>

<details>
<summary>Glide Board Ramp Speed Modifier</summary>

Changes Glide Board Ramp speed

```armv7
003677C4 42000000
```
</details>

<details>
<summary>Toad Balloon Speed Modifier</summary>

Changes Toad Balloon speed

```armv7
00384EF8 45500000
```
</details>

<details>
<summary>Goat Speed Modifier</summary>

Changes goat speed

```armv7
00344864 40800000
```
</details>

<details>
<summary>Daisy Hills Hot Air Balloons Move Around</summary>

Makes Daisy Hills Hot Air Balloons move around

```armv7
0037DB70 44A00000
```
</details>

<details>
<summary>Daisy Hills Hot Air Balloons Up & Down Height Modifier</summary>

Changes how high and low Daisy Hills Hot Air Balloons will go

```armv7
0065FD08 44500000
```
</details>

<details>
<summary>Daisy Hills Hot Air Balloons Move Around in a Big Circle</summary>

Daisy Hills Hot Air Balloons will be moving around an area like a circle

```armv7
0037DB70 45000000
```
</details>

<details>
<summary>Daisy Hills Windmill Speed Modifier</summary>

Changes Daisy Hills Windmill speed

```armv7
00378B40 45000000
```
</details>

<details>
<summary>Crab Always Move</summary>

Crab is always moving and will never stop

```armv7
0065F610 00000000
```
</details>

<details>
<summary>Crab Speed Modifier</summary>

Changes Crab speed

```armv7
00343898 42500000
```
</details>

<details>
<summary>Cheep Cheep Speed Modifier</summary>

Changes Cheep Cheep speed

```armv7
003A2280 3F800000
```
</details>

<details>
<summary>Cheep Cheep Delimiter</summary>

Changes amount of Cheep Cheeps to 100. Might lag in VS. If so, use 0x32 instead of 0x64

```armv7
0039E7AC E3A00064
```
</details>

<details>
<summary>Snake Pot Speed Modifier]</summary>

Changes Snake Pot speed

```armv7
00373314 3F000000
```
</details>

<details>
<summary>Snake Pot Always Move</summary>

Snake Pot is always moving and will never stop

```armv7
00372E70 E3A000FF
```
</details>

<details>
<summary>Carpet Shy Guy Speed Modifier</summary>

Changes Carpet Shy Guy speed

```armv7
0037D788 40000000
```
</details>

<details>
<summary>Wuhu Loop Car Speed Modifier v1</summary>

Changes Wuhu Loop Car speed

```armv7
003A9EEC 3F500000
```
</details>

<details>
<summary>Wuhu Loop Car Speed Modifier v2</summary>

Changes Wuhu Loop Car speed

```armv7
0034C488 E2820050
```
</details>

<details>
<summary>Goomba Speed Modifier</summary>

Changes Goomba speed

```armv7
00351444 42500000
```
</details>


<details>
<summary>Goomba Always Move</summary>

Goomba is always moving and will never stop

```armv7
00389724 E3A00001
```
</details>

<details>
<summary>Tempo-Kun Note Jump Height Modifier</summary>

Changes how high Tempo-Kun Note from Music Park jumps

```armv7
006608FC 44000000
```
</details>

<details>
<summary>Crazy Wario Shipyard Anchor Spin</summary>

Makes Wario Shipward Anchor spin crazy

```armv7
003497FC 42000000
```
</details>

<details>
<summary>Neo Bowser City Airship Speed Modifier</summary>

Changes Bowser City Airship speed

```armv7
003976F8 40400000
```
</details>

<details>
<summary>Seagull Speed Modifier</summary>

Changes Seagull speed

```armv7
003AFC14 3F800000
```
</details>

<details>
<summary>Seagull Delimiter</summary>

Changes amount of Seagulls to 100. Might lag in VS. If so, use 0x32 instead of 0x64

```armv7
00660654 00000064
```
</details>

<details>
<summary>Fish Bone Speed Modifier</summary>

Changes Fish Bone speed

```armv7
0039A8B8 3F800000
```
</details>

<details>
<summary>Tiki Goon Speed Modifier</summary>

Changes Tiki Goon from DK Jungle speed

```armv7
003778A0 42500000
```
</details>

<details>
<summary>Tiki Goon Always Move</summary>

Tiki Goon from DK Jungle is always moving and will never stop

```armv7
003774AC E3A010FF
```
</details>

<details>
<summary>DK Jungle Airship Speed Modifier</summary>

Changes DK Jungle Airship speed

```armv7
00379838 40400000
```
</details>

<details>
<summary>Penguin Speed Modifier</summary>

Changes Penguin speed

```armv7
003638F4 3FC00000
```
</details>

<details>
<summary>Penguin Delimiter</summary>

Changes amount of penguins to 16

```armv7
003AE998 E3A00010 
```
</details>

<details>
<summary>Ice Platform Never Disappear</summary>

Ice Platform from Rosalina's Ice World will never disappear

```armv7
003608EC E3A00000
```
</details>

<details>
<summary>No Ice Platform</summary>

Ice Platform from Rosalina's Ice World will disappear instantly

```armv7
003608EC E28000FF
```
</details>

<details>
<summary>Thwomp Speed Modifier</summary>

Changes Thwomp speed

```armv7
0065F8E8 49000000
0065F8EC 49000000
006607D8 49000000
006607DC 49000000
```
</details>

<details>
<summary>Thwomp Always Thwomping (Rapid Fire)</summary>

Thwomps will always be thwomping (Rapid Fire)

```armv7
0034E058 13A00000
0034E08C E3A00000
0034E124 13A00000
0038BF70 13A00000
0038BFA4 E3A00000
0038C044 13A00000
```
</details>

<details>
<summary>Frogoon Speed Modifier</summary>

Changes Frogoon speed

```armv7
0064FC2C 40000000
```
</details>

<details>
<summary>Frogoon Always Move</summary>

Frogoon is always moving and will never stop

```armv7
0035B438 EA00002F
0035B418 E3A070FF
0035B35C 00000000
0035B2B8 00000000
```
</details>

<details>
<summary>Fire Geyser Speed Modifier</summary>

Changes Fire Geyser speed

```armv7
00389524 44000000
```
</details>

<details>
<summary>Fire Geyser Rapid Fire</summary>

Makes Fire Geyser rapid fire

```armv7
00388D50 E3A01000
00388DDC E3A01000
00388C0C E3A02000
E065FB20 0000000C
000000FF 000000FF
00000000 00000000 
0065FB34 00000000
```
</details>

<details>
<summary>Mii Audience Speed Modifier</summary>

Changes Mii Audience speed

```armv7
0034CC48 E3A02204
```
</details>

<details>
<summary>Cannon Animation Speed Modifier</summary>

Changes Cannon Animation speed

```armv7
00386A40 40000000
```
</details>

<details>
<summary>Cannon Always Kaboom</summary>

Makes Cannoons always kaboom

```armv7
003868CC E3A00001
```
</details>

<details>
<summary>Wuhu Island Windmill Speed Modifier</summary>

Changes Wuhu Island Windmill speed

```armv7
00660E84 41000000
```
</details>

<details>
<summary>Pipe Speed/Gravity Modifier</summary>

Changes Pipe Speed/Gravity

```armv7
0065F8AC 40800000
```
</details>

<details>
<summary>Noshi Dinosaur Speed Modifier</summary>

Changes Noshi Dinosaur speed

```armv7
0065F6B0 49000000
```
</details>

<details>
<summary>Note Jump Area Floor Always Jump</summary>

Makes you (and CPUs) always jump on Music Park Note Jump Area Floor

```armv7
00391D38 00000000 
```
</details>

<details>
<summary>Crazy Rainbow Road Wavy Road</summary>

Makes Rainbow Road Wavy Road crazy

```armv7
00389BF8 40000000
0038A51C 40000000
```
</details>

<details>
<summary>Rainbow Road Wavy Road Speed Modifier</summary>

Changes Rainbow Road Wavy Road speed

```armv7
00389BF4 3E500000
00389518 3E500000
```
</details>

<details>
<summary>Chomp Speed Modifier</summary>

Changes Chain Chomp speed

```armv7
00352EA0 3F000000
00352D9C 3F000000
```
</details>

<details>
<summary>Chomp Jump Height Modifier</summary>

Changes how high Chain Chomp jumps

```armv7
00660B38 3F000000
```
</details>

<details>
<summary>N64 Luigi Raceway Balloon Speed Modifier</summary>

Changes Balloon Blimp speed

```armv7
0035900C 41500000
```
</details>

<details>
<summary>N64 Luigi Raceway Balloon Height Modifier</summary>

Changes how high in the sky the balloon blimp will be

```armv7
00359004 44000000 
```
</details>

<details>
<summary>Crazy Mushroom Animation</summary>

Makes Mushrooms from Mushroom Gorge have crazy animation

```armv7
0066003C 000F0005
00660044 BF800000
00660048 3FC00000
```
</details>

<details>
<summary>Walking Tree Speed Modifier</summary>

Changes Walking Tree from DS Luigi Mansion speed

```armv7
0039A1B4 3F800000
```
</details>

<details>
<summary>Walking Tree Always Move</summary>

Walkig Tree from DS Luigi Mansion is always moving and will never stop

```armv7
0065FA54 00000000
```
</details>

<details>
<summary>Coconut Mall Car Speed Modifier</summary>

Changes Coconut Mall Car speed

```armv7
00354E90 3FC00000
00660D18 49000000
```
</details>

<details>
<summary>Coconut Mall Car Always Move</summary>

Coconut Mall Cars are always moving and will never stop

```armv7
0038D2D8 E3A00001
```
</details>

<details>
<summary>Coconut Mall Car Big Mii</summary>

Changes Coconut Mall Car Mii size

```armv7
00660D3C 41000000 
```
</details>

<details>
<summary>Pinball Speed Modifier</summary>

Changes Pinball speed

```armv7
0065FF24 43000000
0065FF28 43000000
```
</details>

<details>
<summary>Red Bumper Speed Modifier</summary>

Changes Red Bumper speed

```armv7
0065F93C 43000000
```
</details>

<details>
<summary>Train Speed Modifier</summary>

Changes Train speed

```armv7
00354E90 3F800000
```
</details>

<details>
<summary>Giant Growing Snowball</summary>

Changes Snowball growing size

```armv7
0037515C 3F000000 
```
</details>

<details>
<summary>Moving Table Speed Modifier</summary>

Changes GCN Daisy Cruiser Moving Table speed

```armv7
0065FCB8 42A00000
0065FCBC 42A00000
```
</details>

<details>
<summary>Moving Table Always Move</summary>

GCN Daisy Cruiser Moving Table is always moving and will never stop

```armv7
0065FCAC 0000000A
0065FCB0 00000000
```
</details>

<details>
<summary>Maw-Ray Eel Speed Modifier</summary>

Changes Maw-Ray Eel speed

```armv7
003C09E8 40400000
```
</details>

<details>
<summary>Wiggler Speed Modifier</summary>

Changes Wiggler speed

```armv7
0036FE7C 3F500000
```
</details>

<details>
<summary>Wiggler Always Move</summary>

Wigglers will always be walking and will never stop

```armv7
0037062C 00000000
```
</details>

<details>
<summary>Gas Fire Burner Speed Modifier</summary>

Changes DS Airship Fortress Fire speed

```armv7
0035BCE4 40000000
```
</details>

<details>
<summary>SNES Rainbow Road Wavy Road Speed Modifier</summary>

Changes SNES Rainbow Road Wavy Road speed

```armv7
0039EE0C 42000000
0039EE10 42C00000
```
</details>

<details>
<summary>Crazy Stingby Bees</summary>

Makes Stingby Bees crazy

```armv7
0065F4B0 43000000
0065F4B4 43000000
```
</details>

<details>
<summary>Stingby Bee Delimiter</summary>

Changes amount of Stingy Bees to 50

```armv7
00359694 E3A00032 
```
</details>

<details>
<summary>Banzai Bill Speed Modifier</summary>

Changes Banzai Bill speed

```armv7
0065FFFC 42000000
```
</details>

<details>
<summary>Always Small Banzai Bill</summary>

Only shoot small Banzai Bills

```armv7
0036EF10 E3A03000
```
</details>

<details>
<summary>Always Big Banzai Bill</summary>

Only shoot big Banzai Bills

```armv7
0036EF10 E3A03001
```
</details>

<details>
<summary>Big Banzai Bill Size Modifier</summary>

Changes size of Big Banzai Bill

```armv7
0065FFF4 41000000
```
</details>

<details>
<summary>Banzai Bill Delimiter</summary>

Changes amount of Banzai Bills to 100. Might lag in VS. If so, use 0x32 instead of 0x64
Particle Anti Crash v2 by H4x0rSpooky. Thank you! 
EDIT: v2 also causes drift particle issue, v1 is one line (BX LR), therefore, wouldn't v1 be better? Kept v2 for "clean code" but in terms of functionality, same thing

```armv7
003AA598 E3A00064
004DF738 EB068294
E0680190 00000014
E590401C E3540000
E1A04000 112FFF1E
E8BD8010 00000000 
```
</details>

<details>
<summary>DS Airship Fortress Cannon Rapid Fire / Banzai Bill Shoot Rate Modifier (Rapid Fire)</summary>

Makes DS Airship Fortress always be shooting Banzai Bills, you need to configure the rate of how fast they shoot.
Edit rate (XX) based on if you use Banzai Bill Delimiter and if you use Banzai Bill Speed Modifier. I recommend using around 0x50 with Banzai Bill Speed of 0x41000000 or 0x42000000 and using Banzai Bill Delimiter. Experiment values and speed.

```armv7
0036EDEC EA000003
00660004 000000XX
```
</details>

<details>
<summary>Swoop Bat Speed Modifier</summary>

Changes Swoop bat speed

```armv7
0039789C 3F000000
```
</details>

<details>
<summary>Swoop Bat Delimiter</summary>

Changes amount of swoop bats to 100. Might lag in VS. If so, use 0x32 instead of 0x64

```armv7
003978F8 E3A00064
```
</details>

<details>
<summary>Consecutively Spawn Swoop Bats</summary>

Spawn swoop bats without delay

```armv7
00397AB8 00000000
```
</details>