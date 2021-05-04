Termingus is a fork of [Terminus](http://terminus-font.sourceforge.net/).

I needed a bitmap font that has decent unicode support, and figured it'd be considerably easier to modify the glyphs I didn't like than it would have been to add basic unicode support to Tamzen, which I previously used.

Termingus doesn't use Terminus' build system, nor do I have compatible patch files.  
BDF files are plain ascii, I just needed to tweak a few characters and didn't care.

I have since tweaked a lot more characters, and I still don't really care. It's an unzip and a `fc-cache -fv` away from working on my box, which is just what I need.
On the other hand, I won't yell at you if you feel it deserves a proper build system and submit a pull request.

I have kept the old changelog attached, but all further modifications will be logged using `git`.

The 32px version is ugly ugly ugly, but I prefer bold characters that are actually **bold**.
It's also very incomplete. One day, maybe....

Termingus is licensed under the SIL Open Font License, Version 1.1. The license is included as OFL.TXT, and is also available with a FAQ at http://scripts.sil.org/OFL


[16px](pics/16px.png)
[20px](pics/20px.png)
[22px](pics/22px.png)
[24px](pics/24px.png)
[28px](pics/28px.png)
[32px](pics/32px.png)
