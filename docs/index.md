![demo.gif](demo.gif)

# CoordsDB [![Java CI with Gradle](https://github.com/mxtt-mmxix/CoordsDB/actions/workflows/gradle.yml/badge.svg)](https://github.com/mxtt-mmxix/CoordsDB/actions/workflows/gradle.yml)
A Spigot & Paper Server plugin for saving coordinates in Minecraft.

Have you ever found yourself hitting F3 to get into that cluttered debug menu to save the coordinates of an important place such as your home base or nether portal? Maybe you have a whole album of screenshots or a Google Doc with all your coordinates. What if, there was a simpler in-game solution for saving your coordinates and getting easily all without leaving your game by using a few simple commands? 

That is why I created this plugin.

## Supported Platforms
- 1.19 Paper Minecraft Server
- 1.19 Spigot Minecraft Server

## How to use
### Set 
Sets and stores your current coordinate location with an optional label. 
#### Example
`/coords:set home` 

### Query
Gets all your coordinates.
#### Example
`/coords:get` 

### Query with Entry
Gets with coordinate with the label.
#### Example
`/coords:get end_portal` 

### Query with Entry Wildcard
Gets all your coordinates whose label begin with the prefix.
#### Example
`/coords:get i*` 

### Query another player's coordinates
Gets with coordinate with the label that belogs to that player.
#### Example
`/coords:get foo:bar` 

### Delete
Deletes the coordinate location with the specified label.
#### Example
`/coords:del spawn` 
