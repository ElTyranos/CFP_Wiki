---
layout: default
---

## General setup

* A folder with mod's files
* A `.mod` file

## /CFP Mod Folder
* Go to `Documents\Paradox Interactive\Crusader Kings III\mod`
* Create a folder named "CFP"
* Paste in this folder the files inside the zip you retrieved on [PDXMods archives](https://mods.paradoxplaza.com/mods/12560/Any) or from [Direct Download](/pages/releases)

![](https://i.imgur.com/RXlzZCy.png)

## .mod file
* Go to `Documents\Paradox Interactive\Crusader Kings III\mod`
* Create a txt file and rename it "cfp.mod"

_**Warning**: be sure to show file name extensions so your file is not named "cfp.mod.txt"_
![](/assets/images/extensions.jpg)

* Open it with notepad (right click > open with > notepad.exe)
* Paste the following code inside the file and update the path to match the one of the folder you just created
* Save it and close it

```
version="3.1.5"
tags={
	"Historical"
	"Portraits"
	"Graphics"
}
name="Community Flavor Pack : Old Version"
picture="thumbnail.png"
supported_version="1.7.*"
path="C:/Documents/Paradox Interactive/Crusader Kings III/mod/CFP"
```

* `version` is irrelevant
* `supported_version` is the latest game version and will only trigger the outdated mod warning if it does not match
* `path` is your local mod path, it can be stored elsewhere, it can be a symlink or a junction

_**Warning**: `path` only supports `/` and not `\` so be careful when copy pasting your path from explorer._

## Checking your install
* You both have `Documents\Paradox Interactive\Crusader Kings III\mod\CFP.mod` which contains the path to CFP folder and `Documents\Paradox Interactive\Crusader Kings III\mod\CFP` which contains CFP files

## Launch the mod
Reboot the launcher, your local build should show up. As you can see, I have Steam, Paradox and local builds detected at the same time.

![](https://i.imgur.com/uXp6WxS.png)

## Troubleshooting
In the launcher go to "All Installed mods" tab and hit "Reload installed mods" button. In case of issue, verify previous steps.

## Maintenance
You can now, at any time, remove all files and change your local version for another one, or make local edits that won't be affected by auto updates.

Enjoy!