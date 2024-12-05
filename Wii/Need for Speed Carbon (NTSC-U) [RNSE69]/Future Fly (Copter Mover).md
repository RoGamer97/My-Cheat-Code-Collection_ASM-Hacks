## Future Fly (Copter Mover)

Allows you to freely fly your car with great control. It's a recreation of a 15+ year old hack (Copter Mover) that people would use in Most Wanted to fly the Police Helicopter (copheli) when they selecting it to play. 

My version of the code behaves the same way as Copter Mover, however, you can fly cars exactly like the helicopter without problems, unlike Most Wanted's version. Copter Mover also exists for Carbon but it is extremely bad and you can barely control your helicopter.

For some reason, helicopter can no longer move if going under the ground. I couldn't figure out why this problem happens. Also, code is not toggleable because of a problem that I also couldn't fix and can't be bothered to

Flight controls are the same as driving, with addition of going up (Nitro button) and going down (Handbrake button)

Use with "Drive Through Walls (Only You)" code, which can be found in this same folder

<details>
<summary>Reveal Code</summary>

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