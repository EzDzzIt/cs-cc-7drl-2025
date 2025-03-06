# cs-cc-7drl-2025
Citizen Squeaks and the Cosmic Cheese - 7DRL 2025

Entry for 7DRL 2025. Development started ~~Friday, Feb 28 20:00 US CT~~ _Saturday, March 1_ (I was pretty optimistic after the initial creation of this repo that I'd have time to work that Friday night). 

Goal: create a functional roguelike entry that has a set of levels and an end state.  

Premise: players will take the role of Citizen Squeaks, a mouse living in the vents
of a laboratory station on the surface of Europa. Squeaks will need to adapt, fight,
and evolve in order to eat as much cheese as possible. 

_Update for Thursday, March 6_: I spent a lot of time on getting basic RL mechanics integrated and working over the weekend, then troubleshooting bugs with those mechanics this week! Now have the level generation, enemy pathfinding, los and fov calculations relatively well integrated, not entirely bug-free, but at least kind of working.

The visuals for this game currently include only the bare essentials; there is only one enemy type; there are 4 potions that cause different special effects on pickup, some stat tracking, a game over screen. No music or really any art design, the code isn't organized or oop, there's no rpg mechanics or difficulty progression.

The goal is to get as many interesting mechanics integrated as possible before Saturday, but testing and balancing are almost certainly out of the question!

Engine: love2d

Starting Code: project will include some basic movement code from a grid-based
puzzle experiment I worked on previously, building on that basic incomplete framework.
All game assets will be built from scratch except where noted. 

This project will utilize several common open-source love2d lua libraries that will
be listed here; 

-[gamera](https://github.com/kikito/gamera)
-[push](https://github.com/Ulydev/push)
-[jumper](https://github.com/yuyistudio/love2d-engine/tree/master/thirdparty/jumper)
-[timer (hump)](https://github.com/vrld/hump/blob/master/timer.lua)
-[animation](https://github.com/patrixr/love-animation/tree/master)
-[lua dungeon generator](https://github.com/vronc/Lua-Dungeon-Generator)

ToDo:
    create tiles for enviornment, characters, enemies, items
        station, vents, surface
        mouse, bug, robot, trap
        cheese, stairs, vents
    tie level generation into codebase _3/6 level generation code is implemented and modified to add things like enemies and items randomly_
    tie fov into codebase _3/6 recursive shadowcasting is employed but currently buggy; it sort of works_
    give the player stats and a fail state
    give enmeies basic ai and stats _3/6 added pathfinding and some randomness to enemies_
    give the game a win state... _3/6 well we have a game over screen at least_
    show stats on side panel? _3/6 added some player stats into test boxes which can be toggled on, instead of always having a panel up_
    add upgrades chosen based on cheese consumption?
    pause menu?
    game balance?
    ranged attacks?
    enemy loot?
    healing process? _3/6 added potions that can heal the player_
    traps?
    music?
    sound effects?

Notes:
    Game resolution for graphics will be 480x270, similar to psp/picotron
    16x16 tile grid
    ~~side panel overlay on the right side taking up 120px~~ _3/6 scrapped this idea, putting info in basic text for now_
    
