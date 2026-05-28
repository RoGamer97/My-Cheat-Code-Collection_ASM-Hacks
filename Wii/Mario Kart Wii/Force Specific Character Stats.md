## Force Specific Character Stats

This code will force specific character stats, for example, you can play as any medium weight character with Daisy's stats. You can also play with any character stats regardless of weight, for example, Funky Kong stats on small weight characters. The code was designed so you can pick what character stat you want for each weight, also comes with a filter for you to pick who to affect. If you know ASM, you can modify the code to replace a specific character with another character stat, but for this current code, it will force a specific character stat for EVERY CHARACTER, however, you can choose THREE different stats FOR EACH WEIGHT, regardless if that character is from that weight.

<details>
<summary>NTSC-U</summary>

XXXXXXXX (Who to affect):
40820020 Affect only you
41820020 Affect others only
60000000 Affect everyone

SS: Small Weight
MM: Medium Weight
LL: Large Weight
Replace SS/MM/LL with desired character ID for each weight, example: Small Weight (Baby Characters) have Daisy stats: SS to 0F. Mario for all medium: MM to 00 etc.

```powerpc
C258B948 00000007
3C80809C 80848F68
88840B84 7C1C2000
XXXXXXXX 80830008
2C040001 3BE000SS
41800010 3BE000MM
41820008 3BE000LL
1C9F018C 00000000
```
</details>

<details>
<summary>PAL</summary>

XXXXXXXX (Who to affect):
40820020 Affect only you
41820020 Affect others only
60000000 Affect everyone

SS: Small Weight
MM: Medium Weight
LL: Large Weight
Replace SS/MM/LL with desired character ID for each weight, example: Small Weight (Baby Characters) have Daisy stats: SS to 0F. Mario for all medium: MM to 00 etc.

```powerpc
C259216C 00000007
3C80809C 8084D728
88840B84 7C1C2000
XXXXXXXX 80830008
2C040001 3BE000SS
41800010 3BE000MM
41820008 3BE000LL
1C9F018C 00000000
```
</details>

<details>
<summary>NTSC-J</summary>

XXXXXXXX (Who to affect):
40820020 Affect only you
41820020 Affect others only
60000000 Affect everyone

SS: Small Weight
MM: Medium Weight
LL: Large Weight
Replace SS/MM/LL with desired character ID for each weight, example: Small Weight (Baby Characters) have Daisy stats: SS to 0F. Mario for all medium: MM to 00 etc.

```powerpc
C2591AEC 00000007
3C80809C 8084C788
88840B84 7C1C2000
XXXXXXXX 80830008
2C040001 3BE000SS
41800010 3BE000MM
41820008 3BE000LL
1C9F018C 00000000
```
</details>

<details>
<summary>NTSC-K</summary>

XXXXXXXX (Who to affect):
40820020 Affect only you
41820020 Affect others only
60000000 Affect everyone

SS: Small Weight
MM: Medium Weight
LL: Large Weight
Replace SS/MM/LL with desired character ID for each weight, example: Small Weight (Baby Characters) have Daisy stats: SS to 0F. Mario for all medium: MM to 00 etc.

```powerpc
C25801C4 00000007
3C80809B 8084BD68
88840B84 7C1C2000
XXXXXXXX 80830008
2C040001 3BE000SS
41800010 3BE000MM
41820008 3BE000LL
1C9F018C 00000000
```
</details>