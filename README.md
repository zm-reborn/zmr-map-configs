Custom map configuration files for ZMR.

This includes:
- Navigation meshes
- Map configs

**Only servers are required to have these.**


Simply place the custom folder inside the game directory.

Structure should then look like this:
- zombie_master_reborn/custom/configs
- zombie_master_reborn/custom/navs


A restart is required for the game to recognize the new search paths.


**Easy updating**

- Download Git
- Clone the repository with: `git clone -c core.symlinks=true https://github.com/zm-reborn/zmr-map-configs/ <somefolder>`
- Create symlinks for the custom folder (ie. `<somefolder>/custom/configs <---> <gamefolder>/custom/configs`)
- Whenever there is an update, run `git pull` in the repository folder to download the changes.

