# Harem Announcer Dota 2 Mod

This was an old Dota 2 mod from https://github.com/saylith/harem-announcer made by u/saylith. It was not working anymore as he stopped updating it to the current patch and I tried to revive it for my own usage. Works like a charm and thought it must be great to share his updated great work here.

Might add some more lines for missing female heroes here in the future (Mirana, Legion Commander, Dark Willow, Snapfire)

## Installation
1. Download the zip file and unzip it.
2. Find and locate your Dota 2 installation folder, e.g. most of the time located at `C:\Program Files (x86)\Steam\steamapps\common\dota 2 beta`.
3. Open the `game` folder.
4. Create a new folder called `dota2mods`.
5. Place the `pak01_dir.vpk` file in this folder.
6. Go back to the `game` folder, open the `dota` folder.
7. Copy the `gameinfo.gi` file to your desktop as an backup when something goes wrong.
8. Now open the original `gameinfo.gi` file in game/dota folder by using text editor (e.g. Notepad).
9. Make changes as below. Further changes as not mentioned will break your game and this is where the backup file will be needed.
10. Find a line that looks like:
<pre>Game    dota</pre>
11. ABOVE this line, add a new line:
<pre>Game    dota2mods</pre>
12. Save the file and keep the backup somewhere save.
13. Launch Dota 2 and change your announcer pack to default.
13. Open up a game in practice mode to try the Harem Announcer Packs and heroes lines.

## FAQ
Q : My game broke :( what should I do to make it go back to normal??? ( or you just get annoyed by the anime bithces screaming)

1. Open the `gameinfo.gi` file again and remove the line you added earlier. Or you can use your backup files that you saved on Desktop and replace the edited ones.
2. Delete the `dota2mods` folder from your Dota folder.

Q: What animu character are available now?

1. You can find the sample of the announcer and heroes lines here https://github.com/saylith/harem-announcer (Don't download the file there as it's not updated)
