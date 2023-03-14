# WindowsGSM.NoOneSurvived
🧩WindowsGSM plugin that provides No One Survived server support!


# The Game
https://store.steampowered.com/app/1963370/No_One_Survived

# Important
Please Install Microsoft Visual C++ https://aka.ms/vs/17/release/vc_redist.x64.exe

# Config
Open .\NoOneSurvivedServer\WRSH\Saved\Config\WindowsServer\Game.ini



# Description Config
[ServerSetting]
SaveName: the name of the archive, which is also the archive loaded by default

ServerName: indicates the name of the server searched

NeedPassword: True indicates that the server needs a password, and False indicates that it does not need a password

Password: the password required to access the server

MaxPlayers: maximum number of servers (2-50)

NumOfZombie Spawn: number of zombies generated by the wave of corpse tide (25-100)

Region: server region setting, All means non-registered region, AF means Africa, AS means Asia, EU means Europe, NA means North America, OC means Oceania, SA means South America

AdminPassword: server administrator password

[GameSettings]
ZombieAttack: Whether to start the corpse tide

GiftBagForNovices: Whether to open the gift package for novices

Zombie Attack Day: Corpse Tide Attack Day (1-30)

Attack ZombieNum: scale of attack corpse tide (1-5)

ZombieNum: number of lost generation on the map (1-3)

RunZombiePercent: percentage of running corpses (0.0-1.0)

ZombieStreng: strength of zombies (0-3)

YearDay: one year

PermanentDead: whether to turn on permanent death

MaterialNum: material quantity (0-3)

ItemSpawn: material refresh date

VirusFatalyRate: virus fatal rate (0.0-1.0)

NPCItemSpawn: merchant item refresh date

PVP: False indicates PVE mode, and True indicates PVP mode

Every time you change the game settings, you need to restart the server

# Installation
1. Download the latest release
2. Move NoOneSurvived.cs folder to plugins folder
3. Click [RELOAD PLUGINS] button or restart WindowsGSM
