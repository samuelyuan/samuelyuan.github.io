---
layout: default
title: Projects
---

# Projects

This page shows some of my personal software projects.

## OpenBiohazard2

OpenBiohazard2 is open source re-implementation of the original Resident Evil 2 engine written in Go and OpenGL. You must own a copy of the original game to run this game.

<div style="display:inline-block;">
<img src="https://github.com/OpenBiohazard2/OpenBiohazard2/raw/master/screenshots/beginning.png" alt="beginning" width="400" height="300" />
<img src="https://github.com/OpenBiohazard2/OpenBiohazard2/raw/master/screenshots/inventory.png" alt="inventory" width="400" height="300" />
</div>

Links: [Github](https://github.com/OpenBiohazard2/OpenBiohazard2)

## Civ5MapImage

Most custom maps designed for Civ 5 will usually provide screenshots of the map, but they will either only show a portion of the map in the game or a zoomed out image which shows all of the cities but not the terrain. This program is designed to provide you a detailed view of the entire map in one single image.

You have the option of generating a physical map or a political map. The physical map focuses on generating the terrain, while the political map shows the civilization boundaries and major cities. This program will convert a Civ 5 map with the file extension .Civ5Map to a PNG image.

<div style="display:inline-block;">
<img src="https://raw.githubusercontent.com/samuelyuan/Civ5MapImage/master/screenshots/earth.png" alt="earth" width="550" height="300" />
<img src="https://raw.githubusercontent.com/samuelyuan/Civ5MapImage/master/screenshots/europe1939.png" alt="europe" width="400" height="300" />
</div>

Links: [Github](https://github.com/samuelyuan/Civ5MapImage)

## Online Junqi

An open source Junqi app that can be played directly in your browser. This app was developed with Node.js and Websockets.

You can create a new game or join an existing one. When you join a game, you are given the inital layout of pieces and you can setup your board. To swap pieces, you click on the first location you want to swap and click on the second location to confirm the swap. The game will enforce the rules and prevent you from doing an invalid swap like placing a flag outside of the headquarters.

The objective of the game is to capture your opponent's flag. Whoever captures the opponent's flag first wins the game.

For a more detailed version of the game's rules, you can refer to [this page](https://en.wikipedia.org/wiki/Luzhanqi).

<div style="display:inline-block;">
<img src="https://github.com/samuelyuan/online-junqi/raw/master/images/menu.png" alt="Menu" width="400px" height="200px" />
<img src="https://github.com/samuelyuan/online-junqi/raw/master/images/game.png" alt="Gane" width="400px" height="200px" />
</div>

Links: [Github](https://github.com/samuelyuan/online-junqi)

## go-quake2

Quake 2 Map Renderer written in Go and OpenGL.

<div style="display:inline-block;">
<img src="https://github.com/samuelyuan/go-quake2/raw/master/screenshots/map.png" alt="wireframe" width="400" height="300" />
</div>

### Features

* Loads any BSP file from Quake 2
* Free roam around the environment
* Renders only a small sector of the map depending on player location
* Supports static lightmapping

Links: [Github](https://github.com/samuelyuan/go-quake2)
