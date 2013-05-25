vimedit
=======

`vimedit` is a set of settings for yamy
to use windows with vim like key bindings.

## Yet Another Mado tsukai no Yuutsu (yamy)
[yamy](http://sourceforge.jp/projects/yamy/) is keybind customize software
for  windows.
For basic settings, you can refer
[the manual of Mado Tukai no Yuutsu](http://mayu.sourceforge.net/mayu/doc/README-ja.html), which is a base of yamy

There are some posts in my blog about [yamy](http://rcmdnk.github.com/blog/categories/yamy/) (Japanese only), too.


### [vimedit.mayu](./vimedit.mayu)
In this file, the settings for vim-like move/edit are extracted from .mayu file.
It can work standalone.
[This page](http://rcmdnk.github.com/blog/2013/03/16/yamy4/) also explains this setting.

Following features are available.

#### Vim-like cursor move with Alt+Control (or CapsLock)
You can move a cursor with `Alt-Ctrl-`+`h`,`j`,`k`,`l` to left, down, up, and right
like vim in anytime. (It just sends eacy cursor key command.)

In addition, if `CapslLock` is set, `h`,`j`,`k`,`l` can be used standalone to move around.

    * Cursor Move (`A-C-` can be removed when `CapsLock` is set)
      * A-C-h: Cursor Left
      * A-C-j: Cursor Down
      * A-C-k: Cursor Up
      * A-C-l: Cursor Right

#### Vim-like mouse move with Alt+Control (or CapsLock)
A mouse cursor also can be moved by a keyboard.

`A-C-y` moves a mouse cursor to the left, and `A-C-`+`u`,`i`,`o`
moves to the up, down and right, respectively.
(`yuio` are on the `hjkl`.)

Capslock can be used in this case, too.
Such `y` moves a mouse cursor to the left when Capslock is set.

In addition, click/mouse wheel also can be used from the keyboard as followings.
