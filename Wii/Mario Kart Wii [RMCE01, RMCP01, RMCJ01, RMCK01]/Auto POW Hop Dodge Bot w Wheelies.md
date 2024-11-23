## Auto POW Hop Dodge Bot w Wheelies

This code will make you automatically hop dodge POWs, it will also make you wheelie before the POW hits to ensure you will gain enough air to dodge the POW, it will also wheelie after you land from the hop dodge to avoid losing speed. The code also makes sure that you're able to dodge the POW, else, it will avoid trying to dodge it (won't auto hop/wheelie). 
Circumstances that will avoid auto hop/wheelie:

* If the player is not fast enough to be able to perform a wheelie
* If the player is in a Star or Mega and has enough time to dodge POW (if not enough time, e.g: About to end, hop and wheelie will be executed to ensure you are in the air the moment the item ends or will end)
* If the player is in the air
* If the player is not wheeling
The code is not perfect, you can always fail a hop dodge if you are turning, the floor is not that flat and few other scenarios. Some of them can likely be improved. If you want to change or remove some action, check the code source below. I recommend using Seeky's "Automatic POW Dodging" code (https://mariokartwii.com/showthread.php?tid=1393) which makes you always have the less punishing POW damage in case the hop dodge fails.

Unfortunately, this code didn't go as planned, I had many difficulties setting the input bits for wheelie and hop and even if it worked, hop seems to happen even not acceleration (thus why I opted doing all the checks). I couldn't stress it any more and decided to call the functions to do the wheelie and hop instead. I am aware this is not the way to go and that this code is unoptimized, long and ugly. It is painful to see.

I have NOT tested this online and it is a code made FOR FUN AND PRACTICE. I understand it's a very "cheaty" code that can be abused but I am releasing anyways, there are many others codes that can be abused online. I'd not suggest using this code online as it causes unfair advantage and will get you banned. I am not responsible with what you do with this code.

Feel free to modify or recreate this code as you wish.

This code includes Fishguy's "Store Player Index/Slot" code (https://mariokartwii.com/showthread.php?tid=1511) with the index slot value being stored at 0x81500000. 

NOTE: This code makes use of memory addresses 0x81500000 thru 0x81500001 Make sure no other codes in your GCT/Cheat-Manager are using those addresses!

<details>
<summary>NTSC-U</summary>

```powerpc
C2574398 0000001E
9421FF80 BC610008
81830014 718C0002
418200D0 3D80808B
C39D00B0 C3AC1220
FC1CE840 418000BC
81830004 55800631
408200B0 5580035B
418200A8 81630004
81830004 558B00C6
518B0739 40820094
A19D018A 2C0C0032
41810088 A19D0194
2C0C0032 4181007C
3D80809C 818CF798
896C005D 2C0B00B0
41820068 3D408150
880A0000 896A0001
7C005800 41820054
818C0000 2C0C0049
4182000C 2C0C001D
40820018 7FA3EB78
3D808058 618C1B2C
7D8903A6 4E800421
2C0C002E 40820024
8183000C 718C0010
41820018 7FA3EB78
3D808057 618C71F8
7D8903A6 4E800421
B8610008 38210080
A80300A4 00000000
C27D9818 00000002
3D808150 988C0000
80030000 00000000
C252BA08 00000002
9BBF0B84 3EC08150
9BB60001 00000000
```
</details>

<details>
<summary>PAL</summary>

```powerpc
C257ABFC 0000001E
9421FF80 BC610008
81830014 718C0002
418200D0 3D80808B
C39D00B0 C3AC1220
FC1CE840 418000BC
81830004 55800631
408200B0 5580035B
418200A8 81630004
81830004 558B00C6
518B0739 40820094
A19D018A 2C0C0032
41810088 A19D0194
2C0C0032 4181007C
3D80809C 818CF798
896C005D 2C0B00B0
41820068 3D408150
880A0000 896A0001
7C005800 41820054
818C0000 2C0C0049
4182000C 2C0C001D
40820018 7FA3EB78
3D808058 618C1B2C
7D8903A6 4E800421
2C0C002E 40820024
8183000C 718C0010
41820018 7FA3EB78
3D808057 618C71F8
7D8903A6 4E800421
B8610008 38210080
A80300A4 00000000
C27B1DC4 00000002
3D808150 988C0000
80030000 00000000
C252E3D0 00000002
9BBF0B84 3EC08150
9BB60001 00000000
```
</details>

<details>
<summary>NTSC-J</summary>

```powerpc
C257A57C 0000001E
9421FF80 BC610008
81830014 718C0002
418200D0 3D80808B
C39D00B0 C3AC1220
FC1CE840 418000BC
81830004 55800631
408200B0 5580035B
418200A8 81630004
81830004 558B00C6
518B0739 40820094
A19D018A 2C0C0032
41810088 A19D0194
2C0C0032 4181007C
3D80809C 818CF798
896C005D 2C0B00B0
41820068 3D408150
880A0000 896A0001
7C005800 41820054
818C0000 2C0C0049
4182000C 2C0C001D
40820018 7FA3EB78
3D808058 618C1B2C
7D8903A6 4E800421
2C0C002E 40820024
8183000C 718C0010
41820018 7FA3EB78
3D808057 618C71F8
7D8903A6 4E800421
B8610008 38210080
A80300A4 00000000
C27B1430 00000002
3D808150 988C0000
80030000 00000000
C252DD50 00000002
9BBF0B84 3EC08150
9BB60001 00000000
```
</details>

<details>
<summary>NTSC-K</summary>

```powerpc
C2568C54 0000001E
9421FF80 BC610008
81830014 718C0002
418200D0 3D80808B
C39D00B0 C3AC1220
FC1CE840 418000BC
81830004 55800631
408200B0 5580035B
418200A8 81630004
81830004 558B00C6
518B0739 40820094
A19D018A 2C0C0032
41810088 A19D0194
2C0C0032 4181007C
3D80809C 818CF798
896C005D 2C0B00B0
41820068 3D408150
880A0000 896A0001
7C005800 41820054
818C0000 2C0C0049
4182000C 2C0C001D
40820018 7FA3EB78
3D808058 618C1B2C
7D8903A6 4E800421
2C0C002E 40820024
8183000C 718C0010
41820018 7FA3EB78
3D808057 618C71F8
7D8903A6 4E800421
B8610008 38210080
A80300A4 00000000
C27A0184 00000002
3D808150 988C0000
80030000 00000000
C251C428 00000002
9BBF0B84 3EC08150
9BB60001 00000000
```
</details>