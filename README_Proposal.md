[![](https://www.getmangos.eu/images/primus/blue/misc/logo.png)](http://www.getmangos.eu)&nbsp;
[![](/icons/FORUM.gif)](https://www.getmangos.eu/forum.php)
[![](/icons/WIKI.gif)](https://github.com/mangoswiki/wiki/wiki)
[![](/icons/TOOLS.gif)](https://github.com/mangostools)
[![](/icons/TRACKER.gif)](https://www.getmangos.eu/project.php)

MangosThree World Database
===
This is a port of the YTDB Cata database. It will be maintained to work with mangos by the mangos devs. Fixes are welcome and will be shared with YTDB.
See the YTDB homepage for their license and copyright information.
The YTDB homepage: ytdb.ru

### A World Database for WoW: Cataclysm
----
A content database for [**MangosThree**][10], and [**World of Warcraft**][50] Client Patch 4.3.4a - [_WoW 4.3.4a_][51]

### How to Install
---------------
##### Linux
1. Enter **Tools** directory
2. Run: **/bin/sh make_full_db.sh**
3. Apply created file to mangos database, eg.: **mysql -u root -p mangos < full_db.sql**

##### Windows
1. Open File Explorer.
2. Navigate to your database directory where you cloned the database.
3. Right-click and go to Git Bash on the context menu.
4. Run: **./make_full_WorldDB.sh**
5. Apply created file to mangos database, eg.: **mysql -u root -p (the name of your mangos db) < full_db.sql**

##### ***Wiki Stuff?***
Alright. After we have installed the full_db.sql file, we need to go on with update c12729_01_mangos_playercreateinfo_spell.sql. This will be located in World/Updates/Rel21.

[10]: https://github.com/mangosthree/server "mangosThree"

[50]: http://blizzard.com/games/wow/ "World of Warcraft"
[51]: http://www.wowpedia.org/Patch_4.3.4a "WoW 4.3.4a"
