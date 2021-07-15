# st (simple terminal)

Original: [simple terminal (st)](https://st.suckless.org/)

## functionality

Copy and paste: `alt-c` and `alt-v`

Follow links: `alt-l`
copy links: `alt-y`
copy output: `alt-o`

Change of colour scheme: edit config.h to change the 8 normal and 8 bright colours; remember to compile the programme again after editing


## added patches

Alpha: transparency (make sure to have a compositor such as [picom](https://github.com/yshui/picom))

Any size: allows st to resize to any pixel size, makes the inner border size dynamic, and centres the content of the terminal so that the left/right and top/bottom borders are balanced

Bold is not bright: makes bold text rendered simply as bold, leaving the colour unaffected

Box draw: nicer graphic lines and blocks characters

Dynamic cursor colour: swaps the colours of your cursor and the character you're currently on

Externalpipe: reading and writing st's screen through a pipe

Font2: allows to add spare font besides default

Right click paste: pressing right-click pastes from the primary-selection

Scroll back: scroll back through terminal output using `alt-j` and `alt-k`; faster scrolls are done with `alt-d` and `alt-u`; mouse scrolls are also supported
