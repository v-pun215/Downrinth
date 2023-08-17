# Downrinth
![image](https://github.com/v-pun215/Downrinth/assets/67716965/f507c2df-3aab-4a8e-bf73-1ad17a49083d)





A Python utility to download mods from [Modrinth](https://modrinth.com). 

Check this package out at [PyPI](https://pypi.org/project/downrinth/).
## Known Bugs
In linux, it does not automatically install the module ```wget```. 

To do this, do ```pip install wget``` in the terminal.

## Quickstart
To download this package:
```command
pip install downrinth
```

## Usage

To import ModrinthDown:
```python
from downrinth import *
```

To download mod from Modrinth
```python
downloadMod(modSlug, modloader, gameversion, minecraftdirectory)
```

## Example
```python
from downrinth import downloadMod

downloadMod("sodium", "fabric", "1.17.1", "C:\users\username\appdata\roaming\.minecraft")
```
That downloads Sodium into the mods folder in the Minecraft directory.


## Upcoming features
> Resource Pack downloads

> Shader downloads

> Proper mod manager with GUI
