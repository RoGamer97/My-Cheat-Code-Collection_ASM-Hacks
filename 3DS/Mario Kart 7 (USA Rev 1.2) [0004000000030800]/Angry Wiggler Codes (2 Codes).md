## Angry Wiggler Codes

Codes that will make Wiggler angry and related

<details>
<summary>Always Angry Wiggler</summary>

Wiggler will always be angry. Works in menus too.
If you don't like Wiggler anger being cancelled during the selection, you will need rewrite the code and will likely need two hooks

```armv7
002F4D84 E3A00001
004074F4 EA09E2D2
E0680044 00000018
E5D4008C E5945010 
E3550010 03A0100A
0AF61D31 EAF61D26
```
</details>


<details>
<summary>No Angry Wiggler Cancel During Star/Trick/Happy Animation</summary>

This code will make it so Wiggler angriness doesn't go away when you are in a Star, Tricking or doing Happy Animation. Made to be combined with Always Angry Wiggler 

```armv7
002F4DF8 00000000
002F4E30 00000000
```
</details>