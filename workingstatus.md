# Working Status

Here is the list that will compile and work sucessfully

- [x] Can Compile Game
- [x] Tools
  - [x] Rage Script Editor
    - It's working for me but somehow your virtual machine needs to be **Single Core** for script editor to work.   
  - [x] Rag UI and Interface
  - [x] Map Viewer
  - [x] ShortcutMenu 
  - [x] Other Tools
    - Note that Some Perforce login required tools will not work, they need some modifications and Perforce.
      - Perforce Download Links:
        1. Helix Core: https://www.perforce.com/downloads/helix-core-free-small-teams
        2. Helix Visual Client: https://www.perforce.com/downloads/helix-visual-client-p4v
- [x] Can Compile Game Scripts
- [x] Can Compile Shaders
- [x] Can Compile Tools
   - You need modify some of the tools to compile it. 

## Known Bugs and Errors

> B = Bug - E = Error - F = Fix

**B:** When I create "Vehicles" Widgets, the game crashes.<br>
**F:** Before Opening The Save Game, just enter the game normally and dont load the save, create vehicle widgets then load the game.

**E:** Fatal Error:  Unable to create default effect 'common:/shaders/im', cannot continue.<br>
**F:** If u didnt compiled and put the low shaders, then this error may appear.

#### Solution 1: 
Just Compile the low quality shaders by following tutorial.

#### Solution 2:
Just make your shaders quality "High" and dont lower that.<br>
To do this, Follow this steps:

1. Go To **\Documents\Rockstar Games\GTA V**
2. Open *settings.xml*
3. Change  `<ShaderQuality value="0" />` To `<ShaderQuality value="1" />`
4. Save the file and Done!

**E:** Couldn't connect to RAG.exe. Keep trying?<br>
**F:** Just Simply Open the RAG Manually, then start **launch.bat**
