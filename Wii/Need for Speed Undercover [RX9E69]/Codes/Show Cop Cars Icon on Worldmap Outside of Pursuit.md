## Show Cop Cars Icon on Worldmap Outside of Pursuit

Shows cop car icons on worldmap outside of pursuit. I coded them to be red when not in pursuit. I have no idea why but my attempts to call functions to return pointer of each cop car would crash, I couldn't get it to work at 
all and the arguments were correct, therefore, I had no choice but to call a function that returns if you're in a pursuit, so, if you're not in a pursuit, cop cars icon will be red, however, if you're in a pursuit and there's a cop that
isn't in the pursuit (not chasing), the icon will still blink. Weird issue: AI cars (racers for example) will have red color like cops, this doesn't make sense because these functions only execute for cops - maybe it's a game bug or
conflict with other code?

<details>
<summary>Reveal Code</summary>

```powerpc
04195EF4 38600001
04196BEC 38600001
C2194218 00000008
9421FF80 BC610008
3C608071 8063B994
3D808019 618CA9A4
7D8903A6 4E800421
2C030001 B8610008
38210080 41820008
3C80FFA0 7CA32B78
60000000 00000000
```
</details>