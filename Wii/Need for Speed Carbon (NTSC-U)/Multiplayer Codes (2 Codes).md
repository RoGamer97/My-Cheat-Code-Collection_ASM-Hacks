## Multiplayer Codes

Experimental Multiplayer related codes

<details>
<summary>Free Roam Multiplayer - Splitscreen Skip Front End (SkipFESplitScreen)</summary>

Free Roam Multiplayer - Splitscreen Skip FE, boot directly to the game in splitscreen, skipping menus and stuff as well as no traffic and ability to pause. HUD is disabled because it causes crashes.
You can only control the first car, if you use the other code below, you can make the second car be driven by AI (Auto Pilot).
Included "Disable Controller Disconnect Screen"

```powerpc
04198C68 38600000
04338580 4E800020
046F9CF0 00000001
006F9CF8 00000001
```
</details>

<details>
<summary>Player 2 Auto Pilot for SkipFESplitScreen</summary>

Player 2 car will automatically be driven by AI. Only works with SkipFESplitScreen, else, it affects all of the other splitscreen player cars in Multiplayer

```powerpc
C203AA3C 00000005
8983FFE3 2C0C0001
41820014 39800001
99830298 7D836378
4E800020 88630298
60000000 00000000
```
</details>