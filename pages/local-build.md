---
layout: default
---

# General setup

* A folder with mod's files
* A `.mod` file

# Mod Folder
* Go to `Documents\Paradox Interactive\Crusader Kings III\mod`
* Create a folder named "CFP"
* Paste in this folder the files inside the zip you retrived in PDXMods archives
![](https://i.imgur.com/RXlzZCy.png)

# Mod file
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
`version` is irrelevant
`supported_version` is the latest game version and will only trigger the outdated mod warning if it does not match
`path` is your local mod path, it can be stored elswhere, it can be a symlink

# Launch the mod
Reboot the launcher, your local build should show up. As you can see, I have Steam, Paradox and local builds detected at the same time.
![](https://i.imgur.com/uXp6WxS.png)