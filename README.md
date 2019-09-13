# GameMap
A minimap UMG system for Unreal Engine

↓↓↓ TERMS OF USE AT THE BOTTOM OF THIS SECTION ↓↓↓

Videos: 
https://youtu.be/3X2Y57beJrw
https://youtu.be/lhGwEGeAoKA

A mini map system inspired by most popular video games. It offers point, area and path rendering with lots of customization settings changeable at runtime. Renders in circular, rectangular or any shape defined by vertices.

POINT RENDERING:

    Simple / advanced
    Point classes - can be used to define the look of multiple actor classes
    Opacity changes by vertical distance
    Sweeping points close to player
    Hiding points close to player
    Docking points
    Option to use actor rotation to point's rotation
    Rotating docked points by the angle between them and the player
    Size blending between the size of a docked point and a normal point
    Deflating points going out of range

PATH RENDERING:

    Auto subdivison
    separate points OR connected lines
    Width and color settings
    Precision parameter
    Path following surveillance (if player ignores the path, a message listener will be called)
    Removal of old path points and complete path removal once player reaches its end

COMMUNICATION:

    Both areas and points can tell the mini map if they want to look differently
    Recognition of local and global points can be defined at runtime (e.g. you can tell mini map to recognize banks, bars and other buildings once player approaches the city)
    You can stop the recognition of certain actors (e.g. stop recognizing banks, bars etc. when player goes to countryside)
    An actor (or pawn) can behave both as local or as global (can tell mini map what it wants to be and change it any time) . If a player sets bank as a destination - bank can tell minimap to stay docked
    Path can be redefined anytime
    Sending click messages to actors and listener

Adjustable minimap and point material

=========================================================================================

You are free to use this project in your commercial games as long as you mention the author of the original version of this system and its following contributors. Selling the system itself is not allowed. Selling any kind of a similar system built upon this system is not allowed. The system may still remain monetized on the official Unreal Engine marketplace by the original author (for the people willing to support the project despite it being free already). Please keep in mind that for the people willing to support the project buying it on the UE marketplace, the Unreal Engine marketplace terms of use still apply.
