## Traffic Codes

Traffic related codes

<details>
<summary>No Traffic</summary>

Disables traffic entirely, cops will still spawn

```hex
0070AB78 00000001
```
</details>

<details>
<summary>Traffic Can Spawn Anywhere</summary>

Allows traffic to spawn anywhere, for example, in shortcut routes or routes that the traffic normally doesn't drive on. They will also spawn on the wrong direction of the road, causing a bit of mess and chaos

```powerpc
04017690 38600001
```
</details>

<details>
<summary>Traffic Vehicles are Car Semi Truck, Pickups and Sed (& Spawn on Any Zone)</summary>

Traffic vehicles will be car semi truck (which originally only spawns in a specific event), pickups and seds, plus, they'll spawn on any zone, including inside of the city

```powerpc
0400AA98 480000A0
```
</details>

<details>
<summary>Fast Traffic</summary>

Traffic vehicles will drive fast

```powerpc
0401A1CC 38000003
04024284 48000030
040242B4 FC201090
```
</details>

