NOTE: Do NOT use './Data/...', use 'Data/...'

Marker Types
    name: the class
    displayName: What the class displays as in game
    iconFile: image of the markers icon
     
Markers
    All markers are a <POI />
    MapID: what map the marker is in https://api.guildwars2.com/v2/maps?ids=all
    xpos
    ypos    Height
    zpos
    GUID: unique identifier
    iconSize: (default 1), float
    info: text on screen
    inforange: distance that it's visible (default 2)
    Mount="jackal,springer,etc" (only shows if on the mount)
    tip: allows tooltips when hovering on map or categories in the dropdown
        
    rotate: 
        x tilt back and forth
        y tilt left/right
        z actually rotate the way you want it to. positive Z: counter-clockwise
   
Trails
    All trails are a <Trail />
    type="", what markercategory class is it.
    trailData="", what file the trail uses.
    color: 8digit hex RRGGBBAA
    
    Note: COLOR is actually AARRGGBB
    I do not know why, but it's consistent between taco and blish at least.

      
Trail Types
    name: the class
    displayName: What the class displays as in game
    texture: the actual image of the trail
    fadeNear: when the trail starts to fade
    fadeFar: when the trail is completely faded
    use fades so you dont see them from across the entire map.