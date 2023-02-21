# FrostyToolsuite_Light_Theme
Light Theme for the FrostyToolsuite

why am i doing this? (TL;DR the essay if you just want to skip to the theme)

simple really, i've never been a fan of dark themes, whether it's in photoshop, visual studio, office, windows or any other software. I just can't look at a black or very dark grey window for lengthy periods as it gives me a headache. I've always been comfortable using the default light theme in most software.
If there is no light theme available in a piece of software i either look for an alternative or use it for short periods.

The reason here for making a light theme for the frosty tool suite is because a few years back i asked if a light theme could be implemented as an option and instead
of being accommodating or open to suggestions the creators and other members of the community on the discord server for this software suite were rude and dismissive and even resorted to trolling saying dumb things like "why would you want that?" and other silly reasons why it wouldn't ever be added and that no one wants a light theme. :(

I've been thinking about taking a bash at this for a while, i wasn't sure it was possible after being laughed at for my "stupid sugguestion", but it turns out it was possible all along, which brings me to now. 

See what happens when you blow someone off thinking you know better? Just because some users on the internet have decided dark themes rule, doesn't make it set in stone forever. I guess these people have forgotten that Windows had default light themes from 1.0 through to 11.

I don't remember anyone calling those themes crap throughout their use. The only times i myself use a dark theme is on my phone to save battery power and to sometimes read at night. In the day i just find it counter productive as i have to close my curtains or blinds when the sun is streaming in or if it's just a bright day as even with a matte screen you get shadows on it when using a dark theme. 

Some argue it's easy on the eyes but honestly i find it dull and depressing to look at. I like brightness and colour but to each his own i guess. 

I remember I had no issue with MS-DOS being solid black screen with white text back in the late 80's to 90's, because for it's main uses it worked fine, it didn't need to be anything more than a readout of text. When moviing to windows I didn't suddenly pine for the DOS only experience, as it's always been included in all windows versions, tucked away, ready to use when needed. 

The only reason this obsession with "dark themes" or "dark mode" has come about in recent times is because ever since social media became the largest information / media sharing platform on computers and mobile devices we have also had "trends" which is when someone or a group of people start posting about something online via social media platforms that they think everyone else should follow / do or take part in as they believe it's amazing or come up with some cringe reasoning why we've gone on so long without said "awesome thing they only just discoverd" even though it's existed for 20+ years in the form of "high contrast themes" and thus a new "trend" is born and everyone starts following it.

so now it seems everyone with a computer swears by "dark themes" or "dark mode" that it's the best "new" thing ever and wouldn't even dream of using any other themes and proceed to list all the reasons why they think it's so good.

and thus it becomes the latest in the list of things online that are "trending". you know, the annoying crap you see on the youtube front page or your twitter feed or any other social media platform. READ, CONSUME, ASSIMILATE, OBEY HUMAN!

See, now i've convinced you that "dark themes" are awesome right? guess you don't need to continue reading right? huh? oh? you're still here? good. Well, do read on...

So, anyway, now that i've finished rambling and arguing my case...we now move on to the good stuff...the reason why you are here.

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
(because they were white to begin with, they would not be suitable in their current form, so i simply inverted the colours on each one to make them visible on the light theme)

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
