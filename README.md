# TouchBattleTankEnglishVita

Hello! This is an English patch for Touch Battle Tank SP for PlayStation Vita.
The patches are in xdelta format and you'll need a couple of things to get started.

First, you need xDelta: https://www.romhacking.net/utilities/598/
You'll also need VitaShell (https://github.com/TheOfficialFloW/VitaShell/releases) and rePatch (https://github.com/dots-tb/rePatch-reDux0/releases) installed on your Vita.

Open VitaShell, navigate to your app folder where the game is installed and find a directory called "PCSG00593", press Triangle, and then select "Open decrypted" on the side panel.

Hit Select on your Vita inside that directory to start an FTP server, and FTP into your Vita and copy the "Media" folder onto your PC.

Extract the zip provided, and copy the following files from your Media folder from the dumped game to rePatch/PCSG00593/Media:
"sharedassets0.assets","sharedassets1.assets","sharedassets2.assets","sharedassets3.assets","sharedassets4.assets"

Use xDelta to apply the patches to the appropriately named file (sharedassets0.assets.xdelta for sharedassets0.assets etc)

You can delete the .xdelta files when they've all been applied.

FTP back into your Vita, and copy the rePatch folder into ux0 (Directory paths should end up being ux0:rePatch/PCSG00593/Media and ux0:rePatch/PCSG00593/sce_sys)

If you've done everything correctly, the manual in LiveArea should now be in English and so will the game. The assets were ported directly from the Nintendo Switch version of the game which included an official English localization.

Enjoy!
