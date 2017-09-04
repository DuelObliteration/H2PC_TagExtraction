# H2PC_TagExtraction_DUELS_EDIT
My foul attempt at editing himanshus tag extractor. I dont know how to build the project because he was pretty vague on the processes after messing with visual studio, (sorry himanshu!) and that is mainly installation & project building.
The changes are uncommenting on perfectly set up code that normally would not have been changed in programs such as H2_tool.exe, Sapien & etc... The biggest change is that the Halo 2 pathfinding model data for pathfinding spheres and other things relating to that have been uncommented.
So as a send off I hope whomever comes across this will actually build the project and really see if these changes help towards the progression of making AI work in Halo 2 Vista and Halo 2: Project Cartographer.

## COMPILATION / CONTRIBUTE

In order to build the project, you need 2 SDKs, which are boost_1_55_0 and SlimDX.
- [Link:](https://drive.google.com/file/d/0B2ezZImuw5cpMGQwcmpLeE53Rlk/view?usp=sharing)
boost_1_55_0 folder needs to be copied in C:\Program Files (x86)\boost\ .
The application is wrote using C#, and C++ is used for LowLevel project.
Any contribution is welcome.

If it throws That LowLevel.dll is missing,Hit Compile on LowLevel project 1st Then Build the Solution
You will also need to use Xbox Chaos Assembly Halo 2 Plugins https://github.com/XboxChaos/Assembly/tree/master/src/Assembly/Plugins/Halo2
Put all the Halo 2 xml plugins inside Plugins folder and Place it in the Application Directory

For any issue you may find using it, feel free to use "Issues" tab.
If you have more questions about the project, ask me on discord : Himanshu01#3268 .

## Known issues:
1.After extract, references need to be set manually in the tags.
2.Shaders don't extract properly.
3.You can't open shared.map, but you still can extract multiplayer maps.
4.

## I'd like to thank them for testing:
Twinreaper,NukeULater and UF Beazt.
