First release, is eKraKen. Enjoy!

**Install**
icon cache is pre-generated, but you have no action icons for a brief peroid of time. You can solve this by either 
editing the index.theme file, under the field inherits, list your favorite icon theme that is complete. Depending on 
the method you update your icon-cache file, it might bug you to create some size folders to reflect whats in the 
index.theme file. Or, you can remove the offending fields from the theme file and all will be well again. 

A third option, for the more adventerous, is to sym-link action icons into the eKraKen directory tree into the 
apropriate folders, either by editing the index.theme file to reflect the changes, or by mirroring the outline
laid out by the theme file. The benefit of this, is you don't have to inherit extra icons that might clash 
with the overall look of eKraKen, since eKraKen does have nearly all the generic icons assigned they should
be able to find an icon (app's), or at least revert to their own pixmap if the launch file doesn't include
fallback designations.

Beyond this, eKraKen requires no compilation, it is slotted into several png sizes, comes with an icon-cache, and 
provided you take the eKraKen folder and drop it in your system or user icon folder, should work out of the box.

******SPECIAL NOTE*******
I believe xfce is fully supported, but gnome and kde are not. It does follow all the requirements set out by Linux,
and a good many of the programs used by either standard have icon representation. But I don't use any desktop 
environment to test this, since I create my own desktop environment. I only know xfce works, because I leverage 
a few apps in my window manager, namely in menu creation that follow xfce standards. eKraKen will fully support
at the least Gnome, xfce, lxqt, and lxde. And will mostly support kde (folders and animations are different and
will not likely get created by me, you are welcome to make those changes for yourself should you desire that).



******Boring Technical Note*******
All icons were vector, they have been trimmed, color corrected, embedded where need be, and should be to html 
standards. They have been color corrected to material ranges, or at the very least, used material guidelines to
remove unsafe or wonky colors, opacity, etc. This process is carried out by several scripts, and leverages scour.py
and inkscape at the command line to do the neccesary corrections, using material reccomendations for a slew
of svg settings. Icons are then sized in vector format to ensure
clean, crisp images, and convereted to the appropriate .png file format. This is done again, in shell script and
leverages imagemagick with nearly every feature imagemagick has, turned on. Except those features that conflict with
compiling imagemagick with openmp or fftw support enabled for imagemagick.

All icons are proudly made with Inkscape, however, all Inkscape peculiars are stripped and corrected; for those
of you that are familar with icons and Inkscape. So no trace remains at all, from using inkscape and should pose
no concern.
