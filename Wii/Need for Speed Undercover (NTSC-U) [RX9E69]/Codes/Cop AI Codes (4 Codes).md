## Cop AI Codes

Codes related to cop AI

<details>
<summary>Patrol Cops Always Spawn with Goal AI</summary>

For some reason patrol cops spawn with goal AI randomly if your heat level is 2 and above (Likely to happen at Heat 3, happens 95% of the time at Heat 4). It makes them drive erratically and very fast. This code makes it so they always spawn with Goal AI.

This code is very fun when used with the "Enable Cop AI Rubberbanding Anywhere" code as makes patrol cops rubberband.

```powerpc
0400F158 60000000
```
</details>

<details>
<summary>Patrol Cops Never Spawn with Goal AI</summary>

For some reason patrol cops spawn with goal AI randomly if your heat level is 2 and above (Likely to happen at Heat 3, happens 95% of the time at Heat 4). It makes them drive erratically and very fast. This code makes it so they never spawn with Goal AI.

This code can be used with the "Enable Cop AI Rubberbanding Anywhere" code so cops only rubberband when in a pursuit.

```powerpc
0400F158 4800002C
```
</details>

<details>
<summary>Patrol Cops in Goal AI Always Chases and Rams You</summary>

For some reason patrol cops in goal AI follow you in specific events, they will redirect their route to follow and chase you, ramming you most of the time. This code makes it so they always chase and ram you.

This code is very fun (but scary) when used with "Enable Cop AI Rubberbanding Anywhere". Be aware that it isn't as aggressive as "Rubberbanding AI Chases and Rams You" but it's definitely more scary because of how the cops behave.

```powerpc
040260E4 480007EC
040268E4 38000001
```
</details>

<details>
<summary>Patrol Cops in Goal AI Never Chases and Rams You</summary>

For some reason patrol cops in goal AI follow you in specific events, they will redirect their route to follow and chase you, ramming you most of the time. This code makes it so they never chase and ram you.

```powerpc
040268A0 38600000
```
</details>

