---
sidebar_position: 9
title: Content Compiler Parameters
hide_title: true
sidebar-label: 'Content Compiler Parameters'
---

### Content Compiler Parameters

The Scrap Mechanic Content Compiler is a program found in the Scrap Mechanic Release folder. <br></br>
It is used by the mod tool to generate part icons for mods, but it can do a bit more than that! <br></br>
These extra functions can be used by starting the compiler from a terminal and adding certain <br></br>
launch parameters, e.g. <code>ContentCompiler.exe --highres</code>. These parameters are documented below. <br></br>

### --ugc

``` title="Usage Example"
ContentCompiler.exe --ugc="00000000-0000-0000-0000-000000000000"
```
By default, the content compiler generates icons from the game's own files. <br></br>
Using this parameter, the compiler can be directed to a mod instead (the mod tool does this when generating icons). <br></br>
The given UUID is the content UUID (<code>localId</code> in the description.json) of the target mod.

### --voxelmesh

``` title="Usage Example"
ContentCompiler.exe --voxelmesh
```
Currently this parameter seems to do nothing. <br></br>
It is a valid parameter though, as the compiler recognizes it and behaves different. <br></br>
This parameter is probably related to Chapter 2's Voxel Terrain.

### --prefab

``` title="Usage Example"
ContentCompiler.exe --prefab
```
Generates icons for the prefabs in the game files. <br></br>
It might be possible to combine this parameter with the [--ugc](#--ugc) parameter, though this was not tested.

### --blueprint

``` title="Usage Example"
ContentCompiler.exe --blueprint
```
Generates icons for various blueprints in the game files. <br></br>
It might be possible to combine this parameter with the [--ugc](#--ugc) parameter, though this was not tested.

### --create-atlas

``` title="Usage Example"
ContentCompiler.exe --create-atlas --input="../...." --output="../...."
```
Generates an icon atlas.
This parameter requires the [--input](#--input) and [--output](#--output) parameters to be added as well. <br></br>
Further details on what exactly this does are not available as the compiler kept crashing <br></br>
while trying to test out this parameter and no proper result was generated. <br></br>

### --highres

``` title="Usage Example"
ContentCompiler.exe --highres
```
Generates a high-resolution icon image of each block, part and tool in the game's files. <br></br>
Each icon is saved as a separate 1024x1024p image in the <code>Scrap Mechanic/Cache/IconExport/</code> folder. <br></br>
It might be possible to combine this parameter with the [--ugc](#--ugc) parameter, though testing this was not successful.

### --dont-overwrite-icons

``` title="Usage Example"
ContentCompiler.exe --dont-overwrite-icons
```
Skips icons that were already generated. <br></br>
It is not confirmed whether this actually works, though it did seem to speed up the process a bit when testing.

### --input

``` title="Usage Example"
ContentCompiler.exe --create-atlas --input="../...." --output="../...."
```
The input folder parameter parameter for the [--create-atlas](#--create-atlas) parameter. <br></br>
This must be a path **relative to the ContentCompiler.exe**, pointing to a folder. <br></br>
During testing, pointing it to the game's <code>Gui</code> folder (<code>--input="../Data/Gui/</code>) generated <br></br>
the largest amount of activity before crashing.

### --output

``` title="Usage Example"
ContentCompiler.exe --create-atlas --input="../...." --output="../...."
```
The output file parameter parameter for the [--create-atlas](#--create-atlas) parameter. <br></br>
This must be a path **relative to the ContentCompiler.exe**, pointing to a file. <br></br>
During testing, pointing it to a <code>test.png</code> file was the only way the compiler <br></br>
would not immediately close or crash.

