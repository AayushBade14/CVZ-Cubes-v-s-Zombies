# -----------CVZ-Cubes-v-s-Zombies-----------
CVZ: Cube vs Zombies is an interactive shooting game built from scratch using C and the SDL2 library. Test your skills with a working menu system, a full-fledged health system, shooting with ammo count, random loot drops, a variety of enemies, and an area unlock system. Dive into this action-packed survival challenge! I built this as a Major Project in my introduction to computer-science course (ICS-1010) in IIT Jodhpur.

# -----------REQUIREMENTS-----------

1) You must have a gcc/mingw installed on your system.
2) You must have SDL2 library installed and linked properly. GET SDL2: https://wiki.libsdl.org/SDL2/Installation
3) Clone this repo on your system.

# -----------RUNNING_THE_GAME-----------

## Use this command to compile and create an executable of this program: 

### gcc main.c -o game -lSDL2 -lSDL2_image -lSDL2_mixer -lSDL2_ttf

# -----------FIX-----------

If you're facing linker issues , include sdl- mixer,ttf and image libraries within the game folder with the main.c file

# -----------GAME_INSTRUCTIONS-----------

1) Game starts by giving player 100 ammo and 0 points initially.
2) There are 3 types of enemies : white(skeleton), purple(witch),red(boss)-> their stats and points vary from lowest to highest.
3) you'll get random treasure drops , Press 'F' to claim: It might give you some damage , health , ammo or points.
4) If you're in any room , and you need a breathing space and want to escape the enemies you can escape the room by unlocking the new one -> go at centre of any side of the screen and Press 'G' a 1000 points will be deducted from you and you'll be in another room.
5) This game is an infinite shooter , so it goes on till you survive.
