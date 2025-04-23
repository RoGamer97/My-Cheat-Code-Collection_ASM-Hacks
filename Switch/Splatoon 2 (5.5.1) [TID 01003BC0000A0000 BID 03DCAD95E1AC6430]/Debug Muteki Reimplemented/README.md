## Debug Muteki Reimplemented

Debug Muteki is a debug feature found in a leaked QA team build of Splatoon 2 v1.1.0. This patch reimplements the feature in the latest version of the game, v5.5.1.

To toggle Debug Muteki, hold Minus and press L.

Features include:
* God Mode Invincibility
* Full Special Charge
* Ignore Enemy Ink
* Infinite Ink (Never Consume Ink)
* Instantly Recover Umbrella by Pressing D-Pad Up
* On-Screen Debug Text Indicating When It’s Active

---

## IPS and PCHTXT

You can use the .ips file by creating a folder in `atmosphere/exefs_patches/` directory and placing the file inside it.

Example: `atmosphere/exefs_patches/Debug Muteki Reimplemented/*.ips file*` 

Note that the path may vary if you're using an emulator.


Alternatively, you can generate the `.ips` file yourself using **IPSwitch** by creating a folder in `switch/ipswitch/` directory, placing the `DebugMuteki5.5.1.pchtxt` file inside, and then building it with **IPSwitch**.

Example: `switch/ipswitch/Debug Moving Reimplemented (you can Fly)/DebugMuteki5.5.1.pchtxt`.


You can also copy the patch from the `.pchtxt` file and paste it into your own `.pchtxt` if you want to combine it with other patches.