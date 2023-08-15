# Downrinth
![image](https://github.com/v-pun215/ModrinthDown/assets/67716965/f5ef80a3-e469-46b1-a883-614221d22e11)




A Python utility to download mods from [Modrinth](https://modrinth.com). 

## Quickstart
Download it from here.

Place download.py into your Python project's folder.

## Usage
Main goal is to download mods from modrinth.

To import ModrinthDown
```python
from download import downloadMod
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
That downloads sodium into the mods folder in the minecraft directory.

## Upcoming features
> Resource Pack downloads

> Shader downloads

> Proper mod manager with GUI
