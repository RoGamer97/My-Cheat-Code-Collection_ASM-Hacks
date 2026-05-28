## Force Unused Error When Selecting Nintendo WFC (Can't Enter)

This code will force an unused error saying "There is no save data, so you cannot use this mode. You can manage your savedata in the Data Management screen of your Wii system" when trying to select Nintendo WFC. It will not allow you to connect online. First line is for 1P button and second line is for 2P button.

<details>
<summary>NTSC-U</summary>

```powerpc
04831CCC 38000001
04831DC0 38000001
```
</details>

<details>
<summary>PAL</summary>

```powerpc
048512E0 38000001
048513D4 38000001
```
</details>

<details>
<summary>NTSC-J</summary>

```powerpc
0485094C 38000001
04850A40 38000001
```
</details>

<details>
<summary>NTSC-K</summary>

```powerpc
0483F6A0 38000001
0483F794 38000001
```
</details>