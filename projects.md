---
layout: default
title: Projects
---

# Projects

This page shows some of my personal software projects.

## Game Implementation

### OpenBiohazard2

OpenBiohazard2 is open source re-implementation of the original Resident Evil 2 engine written in Go and OpenGL. You must own a copy of the original game to run this game.

<div style="display:inline-block;">
<img src="https://github.com/OpenBiohazard2/OpenBiohazard2/raw/master/screenshots/beginning.png" alt="beginning" width="400" height="300" />
<img src="https://github.com/OpenBiohazard2/OpenBiohazard2/raw/master/screenshots/inventory.png" alt="inventory" width="400" height="300" />
</div>

Links: [Github](https://github.com/OpenBiohazard2/OpenBiohazard2)

### Online Junqi

An open source Junqi app that can be played directly in your browser. This app was developed with Node.js and Websockets. The objective of the game is to capture your opponent's flag. Whoever captures the opponent's flag first wins the game.

<div style="display:inline-block;">
<img src="https://github.com/samuelyuan/online-junqi/raw/master/images/menu.png" alt="Menu" width="400px" height="200px" />
<img src="https://github.com/samuelyuan/online-junqi/raw/master/images/game.png" alt="Gane" width="400px" height="200px" />
</div>

Links: [Github](https://github.com/samuelyuan/online-junqi)

## Game Utilities

### PolytopiaMapEditor

This project is an open source map editor for The Battle of Polytopia. The game generates random maps for each game, but there is no way to edit the maps. This editor solves this problem by giving users the ability to modify the save state containing the map and customize it to their liking.

<div style="display:inline-block;">
<img src="https://raw.githubusercontent.com/samuelyuan/PolytopiaMapEditor/master/screenshots/mapeditor.png" alt="earth" width="600" height="500" />
</div>

Links: [Github](https://github.com/samuelyuan/PolytopiaMapEditor)

### Bio2ScriptIde

You can view the script files in the original Resident Evil 2 / Biohazard 2 as pseudocode next to the original bytecode. Every function is placed in a separate file to make it easier to switch between functions.

<div style="display:inline-block;">
<img src="https://github.com/OpenBiohazard2/Bio2ScriptIde/raw/master/screenshots/ScriptViewer.png" alt="ScriptViewer" width="400" height="300" />
</div>

Links: [Github](https://github.com/OpenBiohazard2/Bio2ScriptIde)

## Game Map to Image

These programs read map files from various strategy games and render them into images.

### Civ5MapImage

Most custom maps designed for Civ 5 will usually provide screenshots of the map, but they will either only show a portion of the map in the game or a zoomed out image which shows all of the cities but not the terrain. This program is designed to provide you a detailed view of the entire map in one single image.

You have the option of generating a physical map or a political map. The physical map focuses on generating the terrain, while the political map shows the civilization boundaries and major cities. This program will convert a Civ 5 map with the file extension .Civ5Map to a PNG image.

<div style="display:inline-block;">
<img src="https://raw.githubusercontent.com/samuelyuan/Civ5MapImage/master/screenshots/earth.png" alt="earth" width="550" height="300" />
<img src="https://raw.githubusercontent.com/samuelyuan/Civ5MapImage/master/screenshots/europe1939.png" alt="europe" width="400" height="300" />
</div>

Links: [Github](https://github.com/samuelyuan/Civ5MapImage)

### PolytopiaMapImage

The Battle of Polytopia only allows one save file to be saved. If a new game is started, the old save files are discarded. There is no way to view a snapshot of the game at any time or any replay system that allows you to view past games.

This program extracts the map from the save file and converts it into an image or replay file that you can preserve and share.

Map Image
<div style="display:inline-block;">
<img src="https://raw.githubusercontent.com/samuelyuan/PolytopiaMapImage/master/examples/map.png" alt="map" width="300" height="300" />
</div>

Replay
<div style="display:inline-block;">
<img src="https://raw.githubusercontent.com/samuelyuan/PolytopiaMapImage/master/examples/replay.gif" alt="replay" width="300" height="300" />
<img src="https://raw.githubusercontent.com/samuelyuan/PolytopiaMapImage/master/examples/pangea.gif" alt="pangea" width="300" height="300" />
</div>

Links: [Github](https://github.com/samuelyuan/PolytopiaMapImage)

### HexEmpireMap

Procedurally generated maps for Hex Empire. This program will generate the same map that can be found in game as a static image.

<div style="display:inline-block;">
<img src="https://raw.githubusercontent.com/samuelyuan/HexEmpireMap/master/screenshots/generated.png" alt="generated map" width="400" height="300" />
</div>

Links: [Github](https://github.com/samuelyuan/HexEmpireMap)

### AgeOfHistory2Map

This program will render various maps found in Age of History 2, formerly known as Age of Civilizations 2.

<div style="display:inline-block;">
<img src="https://raw.githubusercontent.com/samuelyuan/AgeOfHistory2Map/master/screenshots/modernworld.png" alt="modernworld" width="510" height="300" />
<img src="https://raw.githubusercontent.com/samuelyuan/AgeOfHistory2Map/master/screenshots/1440.png" alt="1440" width="510" height="300" />
</div>

Links: [Github](https://github.com/samuelyuan/AgeOfHistory2Map)

### TOAWMap

There have been many maps generated for The Operational Art of War (TOAW) series, but there isn't much information on the file formats and there is no way to parse the data. This project analyzes the different games and you can see how there is a lot of overlap between the various file formats. This program will read scenario files (.sce) and render the maps.

<div style="display:inline-block;">
<img src="https://raw.githubusercontent.com/samuelyuan/TOAWMap/master/screenshots/korea50.png" alt="korea50" width="145" height="300" />
<img src="https://raw.githubusercontent.com/samuelyuan/TOAWMap/master/screenshots/manchuria.png" alt="manchuria" width="300" height="300" />
</div>

Links: [Github](https://github.com/samuelyuan/TOAWMap)

## 3D Rendering

### go-quake2

Quake 2 Map Renderer written in Go and OpenGL. Loads any BSP file from Quake 2 and lets you free roam around the environment.

<div style="display:inline-block;">
<img src="https://github.com/samuelyuan/go-quake2/raw/master/screenshots/map.png" alt="wireframe" width="400" height="300" />
</div>

Links: [Github](https://github.com/samuelyuan/go-quake2)
