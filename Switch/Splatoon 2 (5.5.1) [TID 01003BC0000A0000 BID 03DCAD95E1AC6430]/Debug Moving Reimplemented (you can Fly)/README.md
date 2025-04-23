## Debug Moving Reimplemented (you can Fly)

Debug Moving is a debug feature found in a leaked QA team build of Splatoon 2 v1.1.0. This patch reimplements the feature in the latest version of the game, v5.5.1.

To toggle Debug Moving, press Minus.

Feature includes:
* Levitating
* Free Movement in the Air
* Flying (Ascend/Descend) by Pushing Right Stick U/D
* Move/Fly Faster when in Squid
* Ignore Collision
* Ignore Deathzones
* God Mode (Invincibility)
* On-Screen Debug Text Indicating When It’s Active, Inputs and Coordinates
* And few other minor things...

### Fun Fact

Back in 2015, two months before Splatoon 1 was released, the GameXplain YouTube channel team was invited to Nintendo of America's HQ to try the game early and record gameplay footage for YouTube.

In one of the gameplay videos, they accidentally activate Debug Moving for one second, causing their character to quickly move left and right in the air before disabling it. This confirms that the build they were playing on included debug features, including Debug Moving. Realizing the mistake, they quickly turned it off. It’s surprising that this part wasn’t cut, or that they simply didn’t notice and remove it.

You can see the moment this happens here: https://youtu.be/aEpl1LQ3k0M?t=75 (1:15)

---

## IPS and PCHTXT

You can use the .ips file by creating a folder in `atmosphere/exefs_patches/` directory and placing the file inside it.

Example: `atmosphere/exefs_patches/Debug Moving Reimplemented (you can Fly)/*.ips file*` 

Note that the path may vary if you're using an emulator.


Alternatively, you can generate the `.ips` file yourself using **IPSwitch** by creating a folder in `switch/ipswitch/` directory, placing the `DebugMoving5.5.1.pchtxt` file inside, and then building it with **IPSwitch**.

Example: `switch/ipswitch/Debug Moving Reimplemented (you can Fly)/DebugMoving5.5.1.pchtxt`.


You can also copy the patch from the `.pchtxt` file and paste it into your own `.pchtxt` if you want to combine it with other patches.