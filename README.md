## WARNING: Do not use this program

This program has a major logic error, which causes it to consume a signifigant amount of resources. I, not knowing how to use sdl2 properly, put graphics update code in a while loop. This means it updates much more frequently than the display refresh rate, which is a huge waste of resources. I cannot recommend *anyone* use this program. This could be fixed, but I do not consider it worth the effort, as this program is pretty much useless anyways.

# z80screentest

z80screentest is a simple program I used to help design and test the character font I am planning on using in the [chibi-pc80 project](https://github.com/amberisvibin/chibi-pc80). It's capabilities are limited to only white on black text. It will likely be updated and expanded for my design needs.

### Dependencies:

- SDL2

- Linux (tested on Ubuntu 20.04)

### Possible Improvements:

- Move char array and maps to a seperate file

- Add colour

- Add a way to make custom sprites
