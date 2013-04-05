# Make Caps Lock work as Control and Escape

This handy script makes CapsLock emit Escape's keycode if pressed alone, but
when used in conjunction with another key it emits Ctrl.

(actually right now this makes CapsLock be like left-control and both
left-control and CapsLock now have the awesome dual roles of Escape and
Ctrl)

## Dependencies

  * xmodmap
  * [xcape](https://github.com/alols/xcape)

## TODO

Apparently xmodmap is deprecated.  I don't know how to use the new thing but it
is probably more portable.  Read this:
http://www.charvolant.org/~doug/xkb/html/index.html.
