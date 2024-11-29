## Future Fly (Copter Mover) Codes (2 Codes)

Allows you to freely fly your car with great control. It's a recreation of a 15+ year old hack (Copter Mover) that people would use in Most Wanted to fly the Police Helicopter (copheli) when they selecting it to play. 

My version of the code behaves the same way as Copter Mover, however, you can fly cars exactly like the helicopter without problems, unlike Most Wanted's version. Copter Mover also exists for Carbon but it is extremely bad and you can barely control your helicopter.

For some reason, helicopter can no longer move if going under the ground. I couldn't figure out why this problem happens. Also, code is not toggleable because of a problem that I also couldn't fix and don't bother to fix

Extra separated code included to remove wall collision (only affects you)

<details>
<summary>Future Fly (Copter Mover)</summary>

you can Fly... Flight controls are the same as driving, with addition of going up (Nitro button) and going down (Handbrake button)

```powerpc
C203B848 00000017
7C7B1B78 FFC00890
3D608062 C0030104
C022B538 819B02D0
2C0C0000 41820008
FC200850 EC200072
D02BD94C EC000028
D00BD950 D00BD948
D00BD944 D00BD960
D00BD95C D00BD958
899B011C 2C0C0000
41820008 C002BCD0
819B0110 2C0C0000
41820008 C002BCD8
C02BD92C EC21002A
D02BD92C EC210828
819B02CC 2C0C0000
41820008 C022B600
819B02D0 2C0C0000
41820008 C02293C4
807B0048 3D80802D
618C4178 7D8903A6
4E800421 FC20F090
60000000 00000000
```
</details>

<details>
<summary>Go Through Walls for FF/CM (Only You)</summary>

Allows going through walls when using Future Fly (Copter Mover). Only affects you.

Code is not well made and walls might be solid for few frames. Nothing I can do, but it doesn't really affect in anything, you'll still go through them

```powerpc
0408C348 4E800020
C22DE124 00000003
3D808061 618CD928
7C0C2800 4D820020
9421FE70 00000000
04308648 4800000C
```
</details>