random-colored-xterm
====================

This is a simple bash script I use to call colored xterms.

Why is this useful ?
--------------------

I work with lots of screen real estate and a tiling window manager. So I usually
have lot's of terminals running.

Some of them can contain important stuff (console to a development server,
production server, etc..). This can be dangerous, so I use colored xterms to
avoid making silly mistakes.


How to use ?
--------------------

Copy script to a directory in your PATH, name it any way you like (I use "x"),
you can now call colored terminals by typing "x". Read the script to tune
the color's brightness settings to your liking (dark and bright backgrounds
both should be usable).


Almost random colors ?
--------------------

The script accepts some parameters to guid it's choice of color (r/red, b/blue,
g/green, y/yellow, m/magenta, c/cyan). It'll still be randomized, but heavily
towards your color of choice.
 - "x r" for reddish console,
 - "x b" for blueish, etc...
