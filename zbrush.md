### General
|       |      |   |              |
|-------|------|---|--------------|
| Ctrl  | o    |   | Open Project |
| Ctrl  | s    |   | Save Project |
| Ctrl  | z    |   | Undo         |
| Shift | Ctrl | z | Redo         |

#### Popup selection (on PC only)
|                                  |                  |                  |                                                                       |
|----------------------------------|------------------|------------------|-----------------------------------------------------------------------|
| F1                               |                  |                  | Tools                                                                 |
| F2                               |                  |                  | Brushes                                                               |
| F3                               |                  |                  | Strokes                                                               |
| F4                               |                  |                  | Alphas                                                                |
| F5                               |                  |                  | Textures                                                              |
| F6 (with cursor off canvas area) |                  |                  | Materials                                                             |
| Spacebar or RMB                  |                  |                  | Show QuickMenu                                                        |
| Tab                              |                  |                  | Show/hide floating palettes                                           |
| Ctrl                             | Cursor over item |                  | Show item description (when Popup Info is switched on)                |
| Ctrl                             | Alt              | Cursor over item | Show alternative item description                                     |
| Ctrl                             | Alt              | LMB on item      | Assign custom hotkey (store hotkeys in Preferences > Hotkeys submenu) |
| g                                |                  |                  | Projection Master                                                     |

### Lightbox and Spotlight
|                                    |   |                                                                                   |
|------------------------------------|---|-----------------------------------------------------------------------------------|
| ,                                  |   | Show/hide Lightbox                                                                |
| Double-click on Lightbox thumbnail |   | Load selected item (texture/alphas will be loaded into Spotlight if it is active) |
| Shift                              | z | Turn on/off Spotlight                                                             |
| z                                  |   | Show/hide Spotlight Dial                                                          |

#### With a 3D mesh in Edit mode
|       |                 |                 |                 |                                 |
|-------|-----------------|-----------------|-----------------|---------------------------------|
| LMB   | Drag Background |                 |                 | Free Rotate                     |
| Alt   | LMB             | Drag Background |                 | Move                            |
| LMB   | Drag            | Press Shift     |                 | Constrain to 90-degree rotation |
| Alt   | LMB             | Release Alt     | Drag Background | Scale                           |
| Shift | LMB             | Release Shift   | Drag            | Rotate around Z-axis            |

(For best results turn off Right Click Navigation in the Preferences > Interface menu.)

#### RMB Navigation
(Turn on RMB Navigation in the Preferences > Interface menu.)

|      |                              |                              |        |
|------|------------------------------|------------------------------|--------|
| Alt  | RMB                          | Drag (can be over the model) | Move   |
| Ctrl | RMB                          | Drag (can be over the model) | Scale  |
| RMB  | Drag (can be over the model) |                              | Rotate |

### Transpose
|                             |                                        |   |   |                                                       |
|-----------------------------|----------------------------------------|---|---|-------------------------------------------------------|
| With a 3D mesh in Edit mode | LMB                                    | w | e | r draw the orange action line                         |
| LMB on the mesh             |                                        |   |   | Reposition the action line aligned the surface normal |
| LMB the end of the red      | Green or blue axis line                |   |   | Align an axis                                         |
| Hold Spacebar               |                                        |   |   | Move action line while drawing                        |
| LMB                         | Drag orange line or center orange ring |   |   | Move action line after drawing                        |
| LMB                         | Drag orange end ring                   |   |   | Change action line end point position                 |

Quick tip: in Move/Scale mode, Alt, LMB, drag on the mesh (not on action line) to move or scale mesh

#### Inner (red/white) ring actions
These actions apply to the inner red or white rings of the action line. The terms center or end refer to the position on the line.

|                                   |                                  |                                             |                                     | 
|-----------------------------------|----------------------------------|---------------------------------------------|-------------------------------------| 
| w                                 |                                  |                                             | Move mode                           | 
| LMB                               | Drag center                      |                                             | Move                                | 
| Ctrl                              | LMB                              | Drag center                                 | Duplicate mesh                      | 
| Alt                               | LMB                              | Drag center or end point                    | Bend mesh                           | 
| Drag end point furthest from mesh |                                  |                                             | Stretch mesh                        | 
| Drag end point next to mesh       |                                  |                                             | Flatten mesh                        | 
| RMB                               | Drag end ring furthest from mesh |                                             | Inflate                             | 
| With partially masked mesh        | Hold Ctrl and LMB                | Drag center point                           | Create Edgeloop & extrude           | 
| e                                 |                                  |                                             | Scale                               | 
| LMB                               | Drag end point in line direction |                                             | Scale                               | 
| LMB                               | Drag center point                |                                             | Scale along axis                    | 
| With partially masked mesh        | Hold Ctrl and LMB                | Drag center point                           | Create Edgeloop and deflate/inflate | 
| r                                 |                                  |                                             | Rotate                              | 
| LMB                               | Drag other end point             |                                             | Rotate around end point             | 
| LMB                               | Drag center                      |                                             | Rotate around action line           | 
| Alt                               | LMB                              | Drag end point (rotation around same point) | Joint bend                          | 

### Sculpting and Painting
|   |                                 |
|---|---------------------------------|
| s | Draw Size                       |
| o | Focal Shift                     |
| i | RGB Intensity                   |
| u | z Intensity                     |
| ] | Increase Draw Size by set units |
| [ | Decrease Draw Size by set units |

(Set increment in the Zplugin > Misc Utilities > Brush Increment slider)

|                 |                      |
|-----------------|----------------------|
| t               | Edit mode on/off     |
| q               | Draw                 |
| w               | Move                 |
| e               | Scale                |
| r               | Rotate               |
| Alt (hold down) | Toggle ZAdd and ZSub |

#### Sculpting Brushes
|   |   |   |                   |
|---|---|---|-------------------|
| b |   |   | Show Brush pop-up |
|   | s |   |                   |
|   |   | s | Smooth Stronger   |
|   |   | t | Standard Brush    |
|   | m |   |                   |
|   |   | e | Move Elastic      |
|   |   | p | MPolish           |
|   | c |   |                   |
|   |   | c | ClipCurve         |
|   |   | l | ClayLine          |

#### InsertMultiMesh brushes
|   |                          |
|---|--------------------------|
| m | Show all meshes in brush |

#### Color
|   |                           |
|---|---------------------------|
| c | Select Color under cursor |
| v | Switch Color              |

#### Stroke
|   |            |
|---|------------|
| l | Lazy mouse |

|   |                             |
|---|-----------------------------|
| 1 | Replay last Stroke          |
| 3 | Record stroke               |
| 2 | Replay all Recorded Strokes |

#### Curves
|     |                   |                |
|-----|-------------------|----------------|
| 6   |                   | Smooth curve   |
| 5   |                   | Snapshot curve |
| Alt | Draw across curve | Delete a curve |

### 3D Models
|       |      |   |                                  |
|-------|------|---|----------------------------------|
| Shift | Ctrl | t | Save Tool                        |
| f     |      |   | Fit Mesh to view                 |
| p     |      |   | Perspective                      |
| Shift | p    |   | Floor Grid                       |
| x     |      |   | Activate Symmetry                |
| Shift | f    |   | Show/hide Polyframe & polygroups |
| Shift | Ctrl | p | Point Selection Mode             |
| Ctrl  | p    |   | Set Pivot Point                  |
| Shift | p    |   | Clear Pivot Point                |
| Shift | s    |   | Snapshot a version to canvas     |

#### SubTools
|                        |                        |                           |                                                                                                                                                                     |
|------------------------|------------------------|---------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| n                      |                        |                           | List all SubTools                                                                                                                                                   |
| Alt                    | LMB on SubTool         |                           | Select that SubTool                                                                                                                                                 |
| Shift                  | Alt                    | Click on selected SubTool | Frame that SubTool (Note this option can be set in the Preferences > Edit > Enable Auto Center slider; 0 = off; 1 = Alt[comma]LMB; 2 = Shift[comma]Alt[comma]click) |
| LMB on paintbrush icon |                        |                           | Toggle Polypaint Colorize                                                                                                                                           |
| Shift                  | LMB on paintbrush icon |                           | Toggle Polypaint Colorize for all SubTools                                                                                                                          |

#### Geometry
|       |                           |            |
|-------|---------------------------|------------|
| Ctrl  | d                         | Divide     |
| Shift | d                         | Lower Res  |
| d     |                           | Higher Res |
| Ctrl  | e (partially hidden mesh) | Edge Loop  |

#### Dynamesh
In Edit > Draw mode

|      |                 |                        |
|------|-----------------|------------------------|
| Ctrl | Drag Background | Remesh Dynamesh sculpt |

#### HD Geometry
|                            |                                    |
|----------------------------|------------------------------------|
| a (cursor over mesh)       | Toggle in/out of HD Sculpting mode |
| a (cursor over background) | Render all HD Geometry             |

#### Masking
|                                            |                 |                 |                              |                                                        |
|--------------------------------------------|-----------------|-----------------|------------------------------|--------------------------------------------------------|
| Ctrl                                       | h               |                 |                              | View Mask                                              |
| Ctrl                                       | i               |                 |                              | Invert Mask                                            |
| Ctrl                                       | a               |                 |                              | Mask All                                               |
| Hold Ctrl while selecting brush from popup |                 |                 |                              | Select Masking Brush                                   |
| Ctrl (hold down)                           |                 |                 |                              | Paint mask on object (alphas/strokes can be used)      |
| Ctrl                                       | Alt (hold down) |                 | Delete or paint reverse mask |                                                        |
| Ctrl                                       | LMB Background  |                 |                              | Reverse mask                                           |
| Ctrl                                       | LMB             | Drag Background |                              | Clear Mask                                             |
| Ctrl                                       | LMB             | Release Ctrl    | Drag (starting off mesh)     | Constant-intensity mask                                |
| Ctrl                                       | LMB             | Drag            |                              | Alpha-intensity mask (using MaskPen or MaskRect brush) |
| (select alpha while holding Ctrl)          |                 |                 |                              |                                                        |
| Ctrl                                       | LMB on mesh     |                 |                              | Blur mask                                              |
| Ctrl                                       | Alt             | LMB on mesh     |                              | Sharpen mask                                           |

#### Topological Masking
|      |     |                                   |         |                       |
|------|-----|-----------------------------------|---------|-----------------------|
| Ctrl | LMB | Drag the action line on the model | In Move |  Scale or Rotate mode |

#### Polygroups
|      |   |                             |
|------|---|-----------------------------|
| Ctrl | w | Group Masked and Clear Mask |

#### Partial Mesh Visibility & Clip Brushes
|                                             |                                       |                |                               |                             |                                                      |
|---------------------------------------------|---------------------------------------|----------------|-------------------------------|-----------------------------|------------------------------------------------------|
| Hold Shift                                  | Ctrl while selecting brush from popup |                |                               |                             | Select Selection or Clip Brush                       |
| Shift                                       | Ctrl                                  | LMB            |  release keys                 | Drag (green selection area) | Show mesh portion                                    |
| Press Alt (red selection area)              | Hide mesh portion                     | Shift          | Ctrl                          | LMB                         |  release keys & drag                                 |
| Ctrl                                        | Shift                                 | x              |                               |                             | Grow mesh portion                                    |
| Ctrl                                        | Shift                                 | s              |                               |                             | Shrink mesh portion                                  |
| Ctrl                                        | Shift                                 | a              |                               |                             | Grow all mesh portion                                |
| Ctrl                                        | Shift                                 | o              |                               |                             | Outer Ring visibility                                |
| Press Spacebar without releasing mouse/pen  |                                       |                |                               |                             | Move selection or clip area                          |
| Shift                                       | Ctrl                                  | LMB Background |                               |                             | Show entire mesh                                     |
| Shift                                       | Ctrl                                  | LMB            |                               |                             | Show only selected Polygroup (on fully visible mesh) |
| Shift                                       | Ctrl                                  | LMB            | LMB                           |                             | Hide selected Polygroup (on fully visible mesh)      |
| Shift                                       | Ctrl                                  | LMB            |                               |                             | Hide selected Polygroup (on partially visible mesh)  |
| Shift                                       | Ctrl                                  | LMB            | Drag Background               |                             | Reverse visibility                                   |
| With Lasso option selected                  | Shift                                 | Ctrl           | LMB on edge that crosses loop |                             | Hide edge loop                                       |
| LMB Alt once                                |                                       |                |                               |                             | ClipCurve add soft direction change                  |
| LMB Alt twice                               |                                       |                |                               |                             | ClipCurve add sharp direction change                 |
| Alt (hold down)                             |                                       |                |                               |                             | Reverse clip area                                    |

#### Stencil
|           |   |                   |
|-----------|---|-------------------|
| Alt       | h | Stencil On        |
| Ctrl      | h | Hide/Show Stencil |
| Spacebar  |   | Coin Controller   |

### ZSpheres
|   |                       |
|---|-----------------------|
| a | Preview Adaptive Skin |

#### Draw mode
|                 |                          |             |      |                                            |
|-----------------|--------------------------|-------------|------|--------------------------------------------|
| Drag ZSphere    |                          |             |      | Add a child ZSphere                        |
| Alt             | LMB ZSphere              |             |      | Delete ZSphere                             |
| LMB             | Drag                     | Press Shift |      | Add a child ZSphere at same size           |
| LMB             | Drag to size new ZSphere | Press Ctrl  | Drag | Add a child ZSphere and scale Link Spheres |
| LMB Link-Sphere |                          |             |      | Insert ZSphere                             |

(With Tool > Adaptive Skin > Use ClassicSkinning on:)

|     |                 |                                 |
|-----|-----------------|---------------------------------|
| Alt | LMB Link-Sphere | Sphere Define magnet/break mesh |

#### Move mode
|                  |     |                            |
|------------------|-----|----------------------------|
| Drag ZSphere     |     | Move ZSphere               |
| Drag Link-Sphere |     | Pose (Natural-linked move) |
| Move Chain       | Alt | Drag Link-Sphere           |

#### Scale mode
|                       |     |                  |
|-----------------------|-----|------------------|
| Drag ZSphere          |     | Scale Zsphere    |
| Inflate/deflate chain | Alt | Drag Link-Sphere |
| Drag Link-Sphere      |     | Scale chain      |

#### Rotate mode
|                  |                  |               |
|------------------|------------------|---------------|
| Drag ZSphere     |                  | Spin chain    |
| Alt              | Drag Link-Sphere | Control twist |
| Drag Link-Sphere |                  | Rotate chain  |

### ZSketch
|       |                                          |                            |
|-------|------------------------------------------|----------------------------|
| Shift | a (with a ZSphere armature in Edit mode) | Activate ZSketch Edit mode |
| a     |                                          | Preview Unified Skin       |

### Canvas and 2.5D
|                 |      |   |                            |
|-----------------|------|---|----------------------------|
| Alt (hold down) |      |   | Reverse 2.5D brush effect  |
| Shift           | Ctrl | f | Crop And Fill              |
| Shift           | Ctrl | g | Grab Texture From Document |

#### Document Layers
|       |     |                    |                          | 
|-------|-----|--------------------|--------------------------| 
| Ctrl  | n   |                    | Clear Layer              | 
| Ctrl  | f   |                    | Fill Layer               | 
| Ctrl  | b   |                    | Bake Layer               | 
| Shift | LMB | On Layer thumbnail | Toggle all layers on/off | 

(US)

|   |            |                                             | 
|---|------------|---------------------------------------------| 
| ~ | LMB canvas | Select layer on which clicked pixol resides | 

(UK)

|   |              |                                             | 
|---|--------------|---------------------------------------------| 
| @ | Click canvas | Select layer on which clicked pixol resides | 

(US)

|   |      |                                              | 
|---|------|----------------------------------------------| 
| ~ | Drag | Move layer contents up/down/sideways (X & Y) | 

(UK)

|   |      |                                              | 
|---|------|----------------------------------------------| 
| @ | Drag | Move layer contents up/down/sideways (X & Y) | 

#### Markers
Markers will only show when Edit is turned off

|      |   |               |
|------|---|---------------|
| Ctrl | m | Remove Marker |

#### Canvas Zoom
|      |   |                       |
|------|---|-----------------------|
| 0    |   | Actual Size           |
| Ctrl | 0 | Antialiased Half Size |
| +    |   | Zoom In               |
| ,    |   | Zoom Out              |

#### Timeline
|                               |                                                          |                          |                    |                                      |
|-------------------------------|----------------------------------------------------------|--------------------------|--------------------|--------------------------------------|
| LMB on the Timeline           |                                                          |                          |                    | Place a new key frame                |
| LMB on the key frame dot      |                                                          |                          |                    | Select an existing key frame         |
| LMB on selected key frame dot |                                                          |                          |                    | Zoom Timeline in/out                 |
| LMB                           | Drag dot to new position (dragging off end will delete)  |                          |                    | Move selected key frame              |
| Shift                         | Ctrl                                                     | LMB on the key frame dot |                    | Store new data in existing key frame |
| LMB                           | Drag dot off the Timeline                                |                          |                    | Delete a key frame                   |
| Shift                         | LMB on the Timeline at the point where you want the copy |                          |                    | Copy selected key frame              |
| Shift                         | LMB on all the key frames dots to be copied              |  then Shift              | Click the Timeline | Copy multiple key frames             |

At the point where you want the copies

|       |                                  |                               |                                         |
|-------|----------------------------------|-------------------------------|-----------------------------------------|
| Ctrl  | LMB on an existing key frame dot |                               | Create Transition key frame             |
| Alt   | LMB on an existing key frame dot |                               | Create Rigid key frame                  |
| ←     |                                  |                               | Go to Previous Camera key frame         |
| →     |                                  |                               | Go to Next Camera key frame             |
| Shift | LMB on the Timeline cursor       |                               | Play the Timeline (will play as a loop) |
| LMB   | Esc                              |                               | Stop the Timeline playing               |
| Shift | Ctrl                             | LMB on the Timeline cursor    | Record Timeline as a Movie              |

(set the cursor to the start first using the ←)

#### Movie
|       |       |        |                   |
|-------|-------|--------|-------------------|
| Ctrl  | Shift |        |                   |
|       |       | !      | Snapshot to Movie |
|       |       | PageUp | Snapshot to Movie |

### Render
|       |      |   |                           |
|-------|------|---|---------------------------|
| Shift | r    |   | Best Preview Render (BPR) |
| Shift | Ctrl | r | Render all                |
| Ctrl  | r    |   | Cursor Selective Render   |

### Custom UI and Configuration
|       |      |                                              |   |                                            |
|-------|------|----------------------------------------------|---|--------------------------------------------|
| Ctrl  | Alt  | Drag (when Enable Customize is switched on)  |   | Move item to custom interface position     |
| Ctrl  | Alt  | Drag to Canvas (when Enable Customize is on) |   | Remove item from custom interface position |
| Shift | Ctrl | i                                            |   | Store Configuration File                   |
| Ctrl  | l    |                                              |   | Load User Interface Configuration File     |
| Shift | Ctrl | Alt                                          | i | Save User Interface Configuration File     |

#### ZScripts
|       |      |   |                          |
|-------|------|---|--------------------------|
| Shift | Ctrl | l | Load ZScript             |
| Ctrl  | u    |   | Reload ZScript           |
| h     |      |   | Show/Hide ZScript window |

### Notes
Thanks to http://docs.pixologic.com/user-guide/keyboard-shortcuts/ :)

Feel free to request ownership of this repository
