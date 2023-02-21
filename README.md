# FrostyToolsuite_Light_Theme
Light Theme for the FrostyToolsuite

why am i doing this?

simple really, i've never been a fan of dark themes, whether it's in photoshop, visual studio, office, windows or any other software. I just can't look at a black or very dark grey window for lengthy periods as it gives me a headache. I've always been comfortable using the default light theme in most software.
If there is no light theme available in a piece of software i either look for an alternative or use it for short periods.

The reason here for making a light theme for the frosty tool suite is because a few years back i asked if a light theme could be implemented as an option and instead
of being accommodating or open to suggestions the creators and other members of the community on the discord server for this software suite were rude and dismissive and even resorted to trolling saying dumb things like "why would you want that?" and other silly reasons why it wouldn't ever be added and that no one wants a light theme. :(

I've been thinking about taking a bash at this for a while, i wasn't sure it was possible after being laughed at for my "stupid sugguestion" but it turns out it was possible all along, which brings me to now. See what happens when you blow someone off thinking you know better? Just because some users on the internet have decided dark themes rule, doesn't make it set in stone forever. I guess these people have forgotten that Windows had default light themes from 1.0 through to 11. I don't remember anyone calling those themes crap throughout their use. The only times i myself use a dark theme is on my phone to save battery power and to sometimes read at night. In the day i just find it counter productive as i have to close my curtains or blinds when the sun is streaming in or it's just a bright day as even with a matte screen you get shadows on it when using a dark theme. Some argue it's easy on the eyes but honestly i find it dull and depressing to look at. I like brightness and colour. To each his own i guess. I remember i had no issue with MS-DOS being black with white text back in the late 80's to 90's because for it's uses it worked fine. moviing to windows didn't make me pine for dos.

Anyway, rant aside...we now move on to the good stuff...

currently, my light theme is compatible with v1.0.6.1 release @ https://github.com/CadeEvs/FrostyToolsuite/releases
as that is the latest official non alpha or beta release. i don't recommend building the wip branches as they tend to be buggy and can crash.
next full release should be v1.0.6.2 as that is in alpha at the moment.

I take no credit for any of the files stored in this repository. The included modified files are from the freely available open-source code (found at the above link)
which i've used to convert the current dark theme into a suitable light theme for the following items;

- frosty editor - game selector window, main window ui, options screen, menus, title bar etc.
- mod manager - game selector window, main window ui, options screen, menus, title bar etc. 
- plugins ui (what you see when editing game content in the editor, the central window boxes)

Only the modified / edited files are shared here, not the full source code!
which consist of a bunch of .png and .xaml files as i only edited files relating to the user interface theme(s) of the above softwares. I can't stress that enough!

the .xaml files are the code for the user interface elements which contains the hex letters and digits for the various colours. only the colours have been changed, nothing else.
the .png files being used for toolbar and menu icons and other ui icons etc. these have not been resized only the colours have been changed. 
(because they were white to begin with, they would not be suitable in their current form, so i simply inverted the colours on each one to make them visible on the light them)

The theme is inspired by vs 2019's light theme. which consists mostly of very light greys and some blue strips and almost black text.

Instructions for making use of the new theme:

1. download source code from the above link and extract somewhere suitable.
2. download the edited files from this repo and replace the files in the extracted 1.0.6.1 source code.
3. make sure you have visual studio 2019 installed (you can find the community edition as it's free) see selection of screenshots for required installation configuration.
4. set configuration in visual studio 2019 (with solution loaded) to match the "vs_2019_build_configuration.png" screenshot file on this repo.
5. download and install .net sdk 5.0.408 @ https://dotnet.microsoft.com/en-us/download/dotnet/5.0
6. you should now be setup and able to build each project one by one.
7. make mods! :)

Because there is no option for theme switching in the frosty tool suite (grumble) you will have to build two seperate copies of the frosty tool suite if you wish to use either themes. If you are like me and don't care for the dark them, you won't be that bothered about it.

I hope you like it! but if you find anything you find difficult to see, please open an issue and i'll take a look, it's possible i've missed something but i'm pretty
confident i've covered all the ui elements and text, making things as clear as possible. (in my eyes anyway)

- Slarlac249
