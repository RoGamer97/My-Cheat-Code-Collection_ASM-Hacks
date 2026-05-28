## Fix CPU Slipstream Mission Scoring Bug

This code fixes a "bug" where when playing a Slipstream Mission, you'll score when a CPU slipstreams. With this code, it will now only score when you slipstream.

<details>
<summary>NTSC-U</summary>

```powerpc
C2580BAC 00000004
A0050B9E 819B0000
818C0004 818C0014
718C0002 40820008
38000000 00000000
```
</details>

<details>
<summary>PAL</summary>

```powerpc
C25873D0 00000004
A0050B9E 819B0000
818C0004 818C0014
718C0002 40820008
38000000 00000000
```
</details>

<details>
<summary>NTSC-J</summary>

```powerpc
C2586D50 00000004
A0050B9E 819B0000
818C0004 818C0014
718C0002 40820008
38000000 00000000
```
</details>

<details>
<summary>NTSC-K</summary>

```powerpc
C2575428 00000004
A0050B9E 819B0000
818C0004 818C0014
718C0002 40820008
38000000 00000000
```
</details>