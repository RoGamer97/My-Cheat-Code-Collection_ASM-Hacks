## Multiplayer Codes

Experimental Multiplayer related codes

<details>
<summary>One Controller Multiplayer</summary>

Allows playing multiplayer with one controller. You'll be controlling all of the other splitscreen player cars. Can play 2, 3 or 4 players at once, very cool

```powerpc
044560F0 60000000
044564E8 38600001
04451ED4 38000001
```
</details>

<details>
<summary>Free Roam Multiplayer - Splitscreen Skip Front End (SkipFESplitScreen)</summary>

Free Roam Multiplayer - Splitscreen Skip FE, boot directly to the game in splitscreen, skipping menus and stuff as well as no traffic and ability to pause. HUD is disabled because it causes crashes.
You can only control the first car, if you use the other code below, you can make the second car be driven by AI (Auto Pilot).
Included "Disable Controller Disconnect Screen"

```powerpc
041A634C 38600000
041A61FC 38600000
0437A024 4E800020
0470C068 00000001
0070C070 00000001
```
</details>

<details>
<summary>Player 2 Auto Pilot for SkipFESplitScreen</summary>

Player 2 car will automatically be driven by AI. Only works with SkipFESplitScreen, else, it affects all of the other splitscreen player cars in Multiplayer

```powerpc
C203D2F8 00000005
8983FFE3 2C0C0001
41820014 39800001
9983028C 7D836378
4E800020 8863028C
60000000 00000000
```
</details>