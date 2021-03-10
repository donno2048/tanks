To build this you need to run:

`cc tanks.c -o tanks -lX11 -lm -DA=XK_Up:XK_w -DB=XK_Left:XK_a -DC=XK_Right:XK_d -DD=XK_Down:XK_s -DE=XK_BackSpace:XK_Tab "-DQ=XFillRectangle(W,X,Y,"`

To run it just run: `./tanks`

The green player moves using arrow keys and shoots using `Backspace`

The red one moves using `a`, `s`, `d` and `w` keys and shoots using `Tab`