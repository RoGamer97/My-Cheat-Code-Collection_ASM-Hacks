In order to load the Test Tracks, you need the patch and you also need to add the track files to the game. They will be available in the Debug Menu Test course list.
For emulator, paste the "Course" folder in the romfs mods directory. For console, that crashes atmosphere so the game NSP must be modified to add the track files. I will not distribute my modified NSP.

#test_Customizer#
A track that is used in Customizer scene. While we never had files for this track, the game has skybox for it. Judging how the skybox looks like and the fact that the Customizer scene has the spawn point hardcoded to 0,0,0, it is likely that this track has
no model and is just "Gu_Menu with "VRCustomizer" skybox. This is a recriation of the track and this is VERY LIKELY how it looks like, exactly like this. Load this track in VS, then load the Customizer scene.
The "No Customizer Crash" patch I made is already included in the Test Tracks patches.

#test_DanceFloor# 
A track found in this Prototype and first versions of Deluxe that only includes a lightning environment file. I decided to include it, since it has no collision, model or mapping file, I made it load Mario Circuit but with test_DanceFloor 
lightning environment.

#test_WiFiTest1#
A track found in the Kiosk Demo version of Mario Kart 8 Wii U. The MK8DX port of this track is by CallyHam, with crash and particle fixes by me. In the original version, it is 2 laps because all Kiosk Demo tracks are 2 laps, in here, it's
set to 3 laps. By default, this course is loaded online if the room has an unknown variable set to true (likely a Debug Menu script or something set via Squirrel).
You can use this patch I made to remove the variable check so it always loads it online (everyone in the room must use the code to play this track): 005FD364 00000000 [You can make it an IPS Patch or use it as an EdiZon code by adding 04000000 
before the code].

The tracks can be played in both Race and Battle.

Please, for better understanding and more information about test tracks, read https://tcrf.net/Proto:Mario_Kart_8_Deluxe#Test_Tracks
For more patches, read https://tcrf.net/Proto:Mario_Kart_8_Deluxe/Patches

-Ro (@RoGamer97)