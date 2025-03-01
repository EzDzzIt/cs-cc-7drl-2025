# cs-cc-7drl-2025
Citizen Squeaks and the Cosmic Cheese - 7DRL 2025

Entry for 7DRL 2025. Development started Friday, Feb 28 20:00 US CT. 

Goal: create a functional roguelike entry that has a set of levels and an end state.  

Premise: players will take the role of Citizen Squeaks, a mouse living in the vents
of a laboratory station on the surface of Europa. Squeaks will need to adapt, fight,
and evolve in order to eat as much cheese as possible. 

Engine: love2d

Starting Code: project will include some basic movement code from a grid-based
puzzle experiment I worked on previously, building on that basic incomplete framework.
All game assets will be built from scratch except where noted. 

This project will utilize several common open-source love2d lua libraries that will
be listed here; the starting list includes hump (timer lib), push, animate, serialize. 
Addtionally code for lua-based random dungeon generation and field of view will be used.
(links:)

ToDo:
    create tiles for enviornment, characters, enemies, items
        station, vents, surface
        mouse, bug, robot, trap
        cheese, stairs, vents
    tie level generation into codebase
    tie fov into codebase
    give the player stats and a fail state
    give enmeies basic ai and stats
    give the game a win state...
    show stats on side panel?
    add upgrades chosen based on cheese consumption?
    pause menu?
    game balance?
    ranged attacks?
    enemy loot?
    healing process?
    traps?
    music?
    sound effects?

Notes:
    Game resolution for graphics will be 480x270, similar to psp/picotron
    16x16 tile grid
    side panel overlay on the right side taking up 120px
    