Common errors
------------- 
___________________________________________________________________________________________________

Issue: Big wall of error text when joining the server.

Problem: Mods are not loaded correctly (A) or/
The wrong mods are loaded (B)

Fix (A): Check which version of minecraft is launched, to correctly load the mods the version
has to be fabric loader 1.19.2.

Fix (B): If you have previously installed mods inside of your mods folder, delete them and
only have the mod pack files inside of the folder.

___________________________________________________________________________________________________

Issue: Minecraft is launching but won't make it past the loading screen.

Problem: Minecraft isn't allocated enough resources to load (A) or/
Wrong mods are loaded (B)

Fix (A): Edit installation of Fabric-Loader 1.19.2, open more options:
In JVM arguments change the number value inside of '-Xmx2G' to a range between 8-16.

Fix (B): If you have previously installed mods inside of your mods folder, delete them and
only have the mod pack files inside of the folder.

___________________________________________________________________________________________________

I'm not aware of other issues, DM me if there's something else going wrong.