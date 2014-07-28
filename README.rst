MirrorBoardOSX
==============
Enable left-handed typing by mirroring right-hand keys to left hand when SPACE is held down. Uses the Karabiner keyboard customizer.

Based on XKCD's Mirrorboard and Mirror-QWERTY with custom modifications (for OS X).

Primarily supports QWERTY. Some support for Dvorak layouts remains from a prior github fork.

Original XKCD blog post:
http://blog.xkcd.com/2007/08/14/mirrorboard-a-one-handed-keyboard-layout-for-the-lazy/

Mirror-QWERTY:
https://itunes.apple.com/us/app/mirror-qwerty-one-hand-typing/id496021762

INSTALL
=======
1. Install Karabiner from:
   https://pqrs.org/osx/karabiner/index.html.en
2. Replace the file 'private.xml' with this one (or Copy the <modifierdef> and <item> code from 'private.xml' into yours if you already have some personal settings saved).
   To find your 'private.xml,' launch Karabiner, click it in the top bar, go to Preferences -> Misc & Uninstall -> Custom Setting: Open private.xml
3. Switch back to the Change Key tab and ReloadXML. Type Mirrorboard into the
   search box: MirrorBoardOSX and DvorakMirrorBoardOSX should be in the list. 
   Activate one and start typing left handed.


FEATURES
========
If you check QWERTY mode then holding down SPACE changes the QWERTY keyboard to::

 DEL = - 0 9 8 7 7 8 9 0 - =
 RET p o i u y y u i o p [ ] \
    ' ; l k j h h j k l ; '
     \ . , m n n m , . /

Holding down COMMAND and SPACE changes
   Q W E
to be
   [ ] \


This fork does not alter the prior dvorak mode, except for changing the mode-shift key from CAPS LOCK to SPACE
If you check dvorak mode then SPACE changes the dvorak keyboard to::

 ` z 9 8 7 6 5 7 8 9 0 [ ]
    l r c g f y G C R L / = \
    s n t h d i H T N S -
     v w m b x B M W V Z

Space bar becomes Return and Tab becomes Delete.