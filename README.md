# maxmatrix for the Max7219 and similar multiplexing LED drivers.

This is based on Xantohara's character editor:

https://xantorohara.github.io/led-matrix-editor/

which wasn't presented as an easy download, though I've been able to reconstruct it here with my modifications and a minimal-viable JQuery (upon which it depends). I never actually bothered to learn JQuery (and now it's dead).

The main change in this version is that I've added some Adobe-Photoshop-style tools allowing rotation and flipping of character images. All such operations can now also 
be applied in bulk on all the characters in a character set.  This system assumes an eight by eight pixel grid (just like in the good
old days of Commodore 64 characters), though MaxMatrix devices support grids of any rectangular size.  I'd like to add such support (at least to dimensions less than eight) to 
this editor at some point.  This reminds me of my VIC-20 character editor reconstruction project: https://github.com/judasgutenberg/vic20_character_editor

To see this working live, see here: http://asecular.com/maxmatrix/
