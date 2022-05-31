---
layout: default
---

# General setup

* A folder with mod's files
* A `.mod` file

# Mod Folder
* Go to `Documents\Paradox Interactive\Crusader Kings III\mod`
* Create a folder named "CFP"
* Paste in this folder the files inside the zip you retrieved on [PDXMods archives](https://mods.paradoxplaza.com/mods/12560/Any)

![](https://i.imgur.com/RXlzZCy.png)

# Mod file
* create a txt file named "cfp.mod"
* Paste the following code inside the file and update the path to match the one of the folder you just created
* Save it and close it

```
version="3.1.0"
tags={
	"Historical"
	"Portraits"
	"Graphics"
}
name="Community Flavor Pack : Old Version"
picture="thumbnail.png"
supported_version="1.6.*"
path="E:/Documents/Paradox Interactive/Crusader Kings III/mod/CFP"
```

* `version` is irrelevant
* `supported_version` is the latest game version and will only trigger the outdated mod warning if it does not match
* `path` is your local mod path, it can be stored elsewhere, it can be a symlink

# Launch the mod
Reboot the launcher, your local build should show up. As you can see, I have Steam, Paradox and local builds detected at the same time.

![](https://i.imgur.com/uXp6WxS.png)

# Maintenance
You can now, at any time, remove all files and change your local version for another one, or make local edits that won't be affected by auto updates.

Enjoy!