# Downrinth
![image](https://github.com/v-pun215/Downrinth/assets/67716965/f507c2df-3aab-4a8e-bf73-1ad17a49083d)





A Python utility to download mods from [Modrinth](https://modrinth.com). 

## Quickstart
To download this package:
```
pip install downrinth
```

## Usage

To import ModrinthDown
```python
from modrinth import *
```

To download mod from Modrinth
```python
downloadMod(modSlug, modloader, gameversion, minecraftdirectory)
```

## Example
```python
from download import downloadMod

downloadMod("sodium", "fabric", "1.17.1", "C:\users\username\appdata\roaming\.minecraft")
```
That downloads Sodium into the mods folder in the Minecraft directory.

## Upcoming features
> Resource Pack downloads

> Shader downloads

> Proper mod manager with GUI
