# TL;DR at the bottom.

-------------------------------------------------------------------------------------

To install this mod pack, you will need to download and install fabric loader.

Inside the MC Server drive in Main Mod Files > Installers there is an current
up to date version of the loader: *fabric-installer-0.11.2.exe*

Alternatively you can download the installer from:
https://fabricmc.net 

**Install for game version 1.19.2.**

This should create a launch option in your launcher.

This will be the launch version used for the mod pack so edit the installation to 
use more RAM than the default application:

Open more options in the edit installation menu,

In JVM arguments change the number value inside of '-Xmx2G' to a range between 8-16.
8 can be used for lower settings, up to 16 for higher. The pack shouldn't require 
higher than 16gb of ram.

Note: The fabric API and Architecture are included in the mod pack.

-------------------------------------------------------------------------------------

Also inside of the Installers folder of the drive there is Optifine installer.
This file is INCLUDED in the *CobbleMon MC Pack.zip*
This is for convenience when installing the mod pack since it also needs to be inside
of your mods folder.

You can launch the *OptiFine_1.19.2_HD_U_I1.jar* from inside the .zip or download the
file from the drive and run it.

You can also download the file from: 
https://optifine.net/adloadx?f=OptiFine_1.19.2_HD_U_I1.jar

// To correctly install this version of Optifine,
you may need to install and launch a vanilla 1.19.2 version of minecraft.
(This step isn't required but may be neccassery if your optifine isn't installing)

To do that open the minecraft launcher, click into the installations tab,
click new installation, open the version table and look for the release version
of 1.19.2. and press create once you have selected it.
Launch and close it. //

Run the optifine file and it should create a launch option in your launcher.

-------------------------------------------------------------------------------------

Once Fabric and Optifine are installed, un-zip all of the mods inside of 
CobbleMon MC Pack inside of your mods folder in '.minecraft'. 

// If there isn't a mod folder inside of your .minecraft, 
create a folder and name it 'mods' and place the mods in there. //

To navigate to this folder by default it should be in 
*C:\Users\"your user"\AppData\Roaming\.minecraft*

// If you can't see your AppData folder, if you're using windows 11 click view at top
hover show in the table, click 'hidden items.'

Alternatively, press windows + R, type: %appdata% , and press okay, explorer should
launch inside of the appdata folder, then navigate from there. //

-------------------------------------------------------------------------------------

Included in the mod pack is a zip file called 'Emotecraft-emotes-master'
these need to be placed in your .minecraft in a folder labelled 'emotes'

Navigate inside of the zip folder, place all .json files inside of the folders
'emotes' and 'NSFW' and place them in *\Roaming\.minecraft\emotes* if the folder does 
not exist, create a folder inside of .minecraft and label is emotes, and place the
.json files in there. 

-------------------------------------------------------------------------------------

The mod pack should be fully functional at this point and the server should be
joinable.

Though I would recommend shader packs, for a better look to the game.

Inside of MC Server there is a folder labeled Shader Pack, and it includes the shader
pack I use. Shaders are resource intensive so if these shaders are too taxing, 
you can look online for shaders that are less taxing.

To install shaders you only need to place the zip file of the shaders inside of a 
folder labelled 'shaderpacks' inside of your .minecraft, if it's not there create it.

// Note: If you do use shaders I would recommend a few changes in your video settings
to improve fps.
In performance:
enable render regions
enable smart animations
enable fast math
enable smooth fps
enable smooth world

do not enable fast render as it seems to cause crashes.

if you're still not getting consistent fps you can try these options.

In shaders:
Decrease Shadow Quality to 0.5x
Decrease Render Quality to 0.9x

This should up fps without sacrificing much quality. //

-------------------------------------------------------------------------------------

TL;DR

Install Fabric Loader and create an install for MC patch 1.19.2.

Install a 1.19.2 Optifine version.

Unpack mods from CobbleMon MC Pack.zip into .minecraft\mods\ folder.

Unpack emotes from Emotecraft-emotes-master.zip into .minecraft\emotes\ folder.

Optional Shader pack included.


