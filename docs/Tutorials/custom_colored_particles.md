---
sidebar_position: 4
title: Custom Colored Particles via Lua
hide_title: true
sidebar-label: 'Custom Colored Particles via Lua'
---

### Custom Colored Particles via Lua
Writen by Natejoestev, you can find me in the guild on discord.

This tutorial will show you how to make a custom particle that can be colored via the [effect script](https://scrapmechanictools.com/lua/Game-Script-Environment/Userdata/Effect)

Note that this tutorial assumes that you already know some things about <br></br>
modding SM and the particle system.

### Table of Contents

 - [Required Resources](#required-resources) - Things you need to follow this tutorial
 - [Creating the Effect and Particle](#Create-the-Effect-and-Particle)
 - [Adding the Particle Properties](#Adding-the-Particle-Properties) - Creating an effect to play the sound
 - [Changing color via Lua](#Changing-color-via-Lua) - Playing the sound effect with Lua

### Required Resources

 - [Scrap Mechanic](https://store.steampowered.com/app/387990/)
 - *Scrap Mechanic Mod Tool* you can find for free in the steam library
 - [VS Code](https://code.visualstudio.com/) or any other code editor that can handle JSON and Lua files.

### Creating the Effect and Particle


### Adding the Particle Properties


### Changing color via Lua

```lua
effect = sm.effect.createEffect('Your - Effect')
effect:setParameter('Color', sm.color.new(--[[Your Color]]))
effect:start()
```

this will start your effect with the particle <br></br>
underlay the given color beneath the transparent parts of the diff texture.
