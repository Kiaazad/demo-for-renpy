# demo-for-renpy
A pre-made demo for renpy GUI design and test

While designing a GUI for renpy games you need to test all screens, most of screens are accessable through navigation but there are few that need some gameplay to be added before tested, like menus, input, say, history, skip indicator and character positions.
This demo is created to make the testing possible with minimum effort.

To use it, copy the demo folder into your game folder and add the line: `jump demo` or `call demo` to your script.rpy after the start label. launch the game and navigate your way through menus to the screen you want to test or design.
```
label start:
    jump demo

    return
```

the current sections in the demo are added for these purposes are:
1- how the choices(menus) look
2- how long text fit inside the menus
3- how the input looks
4- how the say window looks with a bigger block of text
5- a long conversation to fill the history and make it ready for testing
6- holding the ctrl button on a menu will show you the skip indicator
7- two characters and a background are added to simulate a finished game environment



Credits for images used in this demo:

bg.jpg

Uncle Mugen from: https://lemmasoft.renai.us/forums/viewtopic.php?f=52&t=17302

Ayame Errkk.png

Hana Impressed m.png

Mayonaise Angry.png

Nana Confident.png

Mugかぶり from: https://lemmasoft.renai.us/forums/viewtopic.php?f=52&t=39049
