material-combiner-addon
===========
#### An addon for Blender that allows to get lower draw calls in game engines by combining textures without quality loss and avoiding the problem of uv larger 0-1 bounds.

[![](http://webgrimes.com/patreon.png)](https://www.patreon.com/join/shotariya?)

## FEATURES
* Combining multiple materials, allow selection, compatible with multiple objects.
* Generation of textures by UV size (allow to pack UV to 0-1 bounds), allow selection.
* Moving UV close as possible to bounds.
* Packing UV into the selected scale bounds by splitting mesh faces, compatible with rigged models.


## USAGE
#### Combining multiple materials:
1. Generate materials list
2. Choose materials to combine
3. Choose ID of combined material, keep 1 to have only one combined material
4. Select a folder for combined texture
5. Combine
#### Generation of textures by UV size:
1. Generate textures list
2. Choose textures to generate
3. Select a folder for generated textures
4. Generate
#### Packing UV by splitting mesh:
1. Choose max scale for UV bounds
2. Pack


## INSTALLATION:
1. Download an addon: [Material-combiner](https://github.com/Grim-es/material-combiner-addon/archive/master.zip)
2. Go to File > User Preferences (Ctrl+Alt+U) > Addons
3. Click on Install Add-on from File
4. Choose material-combiner-addon-master.zip archive
5. Activate Shotariya-don


## PREVIEW
![](http://webgrimes.com/Preview.png#)

## CHANGELOG
#### 1.1.6-3
1. Some minor fixes
#### 1.1.6-2
1. Some minor fixes
#### 1.1.6
1. Some minor fixes
#### 1.1.5
1. Fixed same material combining
2. Some minor fixes
#### 1.1.4
1. Added combining materials by different IDs to be able to use different shaders but keep use one combined texture
2. Fixed Save Textures by UVs wrong material selection
3. Allow to work with multiple models, Hide models which you do not want to change
4. Some minor fixes
#### 1.1.3
1. Attention message on texture combining
2. Some description added
3. Some minor fixes
#### 1.1.2
1. Auto-assigning .blend path as save path
2. Materials with only color support
3. Checking for file existing
4. Other file formats support
5. Mac support
#### 1.1.1
1. New combined texture positioning logic
2. Checking for UV bounds before combining


## BUGS / SUGGESTIONS
If you have found a bug or have suggestions to improve the tool, you can contact me on Discord: [shotariya#4269](https://discordapp.com/users/275608234595713024)
