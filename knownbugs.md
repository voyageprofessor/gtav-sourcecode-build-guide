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
