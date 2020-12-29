--------------------------------------------
Date: 2020/dec/29

using unity 2017.4.26f1
# FastRandomEnclosedVoxelTerrainLevel
The random terrain function to select a position for a tile to be setup is coming from a youtuber. The chunk vertices/triangles/indexes is coming from Craig Perko's old minecraft tutorial. The walls texture, i have figured out how to do it with help from stackoverflow and the unity3d forums.

i built this in my free time.
steve chassé

It takes a slow 10 seconds to generate this enclosed terrain:

<img src="https://i.ibb.co/9grgr80/enclosed-Voxel-Terrain.png" alt="enclosed-Voxel-Terrain" border="0">

chunk script parameters
<img src="https://i.ibb.co/SdCyG8v/chunk-Script-Settings.png" alt="chunk-Script-Settings" border="0">

scene terrain object with script parameters
<img src="https://i.ibb.co/BqWyjVw/editor-Mono-Behavior-Scripts.png" alt="editor-Mono-Behavior-Scripts" border="0">

The minecraft tile atlas, i was using for tests but it belongs to someone else and its a beautiful tile. Im gonna remove that tomorrow if i have the time. The tile is 16x16 for a 1024x1024 resolution. Im not sure if ive got the license for that tileset thought so download at your own risks because normally i make my tiles in the gimp software. So no MIT license for the minecraft tileset as it belongs to someone else. The first person controller is the unity3d 2017.4.26f1 first person controller. Drop that crap in unity3d 2017.4.26f1 and follow the settings i have put. The terrain is slow to generate but the idea of this ""random right/left/forward/backward comes from a youtuber that i will find the name tomorrow give him credits for his tutorials. The voxel chunks are practically a copy paste of the Craig Perko's youtuber old minecraft tutorials. Ive not changed much in the perko chunk.cs script. The walls building process, you will notice how shitty i was in 2016-2017 when coding this.

Please also note, this is an old project almost left untouched and i still have my backups of the original files and video recordings of me scripting and recording my screen while programming everydays for this shit. Someone probably figured out a while ago anyway in games like age of empire or warcraft/starcraft and command and conquer and hellgate london and even the minecraft games on how to make walls... Basically you build the floor tiles and once you have them in a list, you bang your head against a godamn scripting frenzy for hours and hours trying to figure out how to envelopp this godamn voxel terrain with walls, while listening to some synthwave on youtube. My scripting music youtube playlist is here https://youtube.com/playlist?list=PLKlaUriRRX5MzplLm0eBqzMVyPJwNCp1g . 

Those types of scripts are the best i could do back then when i coded this in 2017...Programming is lame when it takes ages to make something work, but when scripts i thought were deemed of being a "complete project" of a total floor+wall level terrain generator achieved, i would rather keep those projects/scripts instead of scrapping them even though they arent perfect and missing tons of things like clouds and trees... but i am sure i left a working pathfind included version somewhere...

I learned how pathfinding was done in C# from the youtuber Sebastien Lague with his pathfind series on youtube. I used his pathfind tutorial as reference and translated it to javascript ecma5 when doing mods on the game void expanse. Void expanse is a game made by the Atomic Torch video game studios. I have been progressing in programming, but one has gotta admit where he learned from. And Javascript Ecmascript 5 https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Strict_mode when scripting void expanse mods, was tough. My 9smods for void expanse, available on the Steam Workshop, has a working pathfind for the miner drone but not all objects are accounted for yet to make the pathfind work on all obstacles and it is a 2d pathfind. But i banged my head on obstacles after obstacles in order to make a pathfind work in ecmascript 5. I invented my own way of understanding and scripting a 2d spiral index fetch function for javascript. I worked my head on walls of scripting fatigue and trial and error and trial and error and trial and error... took me days... weeks... but some very lame working projects like this sometimes took me 3 months in 2017 when i started programming and learning some voxel terrain in unity.

I took 1 month of team treehouse online paid programming education prior to scripting my own tiny little projects in unity3d and scripting on javascript ecmascript 5. After a month i got tired of teamtreehouse, i wanted more and more and faster and fuck the diploma i want to make a game now, and i thought that was a good idea to stop studying at teamtreehouse. The teachers i had the chance to learn from the courses at teamtreehouse were Dave macfarlane (javascript) and Andrew Chalkley(c#) and Treasure Porth(html). i couldnt find a team treehouse program for a C# degree there. I regret never finishing my degree at teamtreehouse. I couldve had a godamn programming job by now and make cash for my family dog, mother and father. 

I quit teamtreehouse 1 month after paying the basic membership. I wasnt even enrolled in a tech degree because i wanted to try teamtreehouse and i loved my 1 month still. i was tired of javascript already though, as i had already tried a few things in unity3d C# and i loved C#...

But then i got bored after a couple weeks/months of unity3d, and i played void expanse with my bro for a couple minutes and after a couple minutes, i wanted to start modding that game void expanse. I was hooked.

thank you for reading me,
steve chassé 
