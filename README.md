# fonline-linux-easysetup

## This repo is for people who need to quickly launch a FOnline server on linux without recompiling all files manually

### Requirements : 
- Linux (Debian 9+, Ubuntu, etc)
- Mysql
- Xvfb
- Wine 

### Files to modify :
- Get Mapper files from http://www.fonline-reloaded.net/files/source/FOnlineReloaded2ndSeasonPart1.zip
- Get Client files from http://www.fonline-reloaded.net/files/source/FOnlineReloaded2ndSeasonPart2.zip
- /Server/config/GetAccess.cfg => set the admin password
- /Server/FOnlineServer.cfg => set your sql user (don't forget to create the database)
- /Server/FOnlineServer.cfg => you can set server port (default is 4040)
- /Server/FOnlineServerStart.sh => modify path if needed
- /Server/FOnlineServerStop.sh => modify path if needed
- /Client/FOnline.cfg => set host adress and port

### Use :
- /Server/FOnlineServerStart.sh to start server
- /Server/FOnlineServerStop.sh to stop server
- /Client/*.exe to play

### Server content is from https://forum.fonline-reloaded.net/index.php?topic=9080.0