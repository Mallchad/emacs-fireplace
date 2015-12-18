emacs-fireplace
================
.. image:: https://raw.github.com/johanvts/emacs-fireplace/master/img/fireplace.gif

About
-----
A cozy fireplace for emacs.

Installation
------------

Download the ''fireplace.el'' and ''fireplace.elc'' files and place them somewhere in your ''.emacs.d'' directory, say in ''.emacs.d/fireplace/''.
Put ''(load "~./.emacs.d/fireplace/fireplace") in your init file ('.emacs').

You can start the fire using ''M-x fireplace''.
The fireplace will try to fill the current window with a new buffer.
To put the fire out use ''M-x fireplace-off''.


========================= ================================
Key bind                  Function
========================= ================================
``C-+``                   Move fire up
``C--``                   Move fire down
``C-s``                   Toggle smoke
========================= ================================

All varaibles starting with ''fireplace-'' can be customized. Use ''C-h v'' to  read thier documentation. 

Acknowledgment
--------------

A big thanks to Dan Torop for his `emacs animation guide
<http://dantorop.info/project/emacs-animation/>` and Vasilij Schneidermann for the 'xbm-life<https://github.com/wasamasa/xbm-life' package.
The code relies heavily on these two sources.

Contribution
------------

Please feel free to do whatever you want with this code.
Ideas and pull requests are very welcome. I can be reached through johanvts@gmail.com
or on twitter @johanvts.


To-Do
-----
Get the package into MELPA.
Group up variables for easier customization.