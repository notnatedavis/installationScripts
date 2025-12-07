# Minecraft

### Installation Process

_Windows_ 

- Create a new base minecraft installation for modded version
    - open the minecraft launcher , go to `installations` and click `new installation` , name it something obvious like `1.20.1 vanilla` , now run and launch newly created installation , then save and close
- Fabric installation for modded client
    -  [Fabric](https://fabricmc.net/) + (required for mods) [Api](), and download corresponding files of the same version `1.20.1` , run and follow built in instructions
    - open minecraft launcher, run and launch `Fabric` (if not should be under installations) , save and close
    - Open `Windows Key`, type `%appdata%`, open `.minecraft/` folder , (if hidden enable under option View->Show->hidden) , open `mods/` folder , (if not there create `mods`/ folder), drag downloaded `Fabric Api` to this mods folder
    - open minecraft launcher, run and launch `Fabric` (if not should be under installations) , save and close
- Install [Essential Mod](https://essential.gg/en)
    - follow built in instructions (select fabric 1.20.1) , rename installation to something obvious like `EssentialMultiplayerFabric 1.20.1`
    - open minecraft launcher, run and launch `Essential...` installation
    - (you would add any friends online at this point and get this out of the way to make sure it works)
- Installing Git and minecraft mods
    - (open)[https://git-scm.com/install/windows] and install corresponding version 
    - open terminal , type `git --version` to validate installation
    - type `cd + "space"` , now open file explorer mid typing and travel to desired paste location of mod downloads `Desktop/games/minecraft/mods/or/some/shit/`
    - copy and paste file explorers location address at the top `C:\Users\you\smell` into terminal and hit enter , type `ls` to validate current terminal location
    - now in the terminal copy and paste the command `git clone https://github.com/notnatedavis/PewPy.git` and you should now see it in your file explorer (refresh)
- Getting mods into minecraft & running
    - open the download in file explorer, open the mods folder for your version
    - Open `Windows Key`, type `%appdata%`, open `.minecraft/` folder , (if hidden enable under option View->Show->hidden) , open `mods/` folder , (if not there create `mods`/ folder), drag downloaded mods to this `mods/` folder
    - launch minecraft `EssentialFabric` installation and test by creating a single player world and test inviting someone
