# ModrinthDown
![image](https://github.com/v-pun215/ModrinthDown/assets/67716965/061762bb-8459-45b1-99f2-e9ee5d1572fd)


A Python utility to download mods from modrinth. 

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
