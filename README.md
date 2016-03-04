# AnatomicPlanes
Blender 3D models of the main anatomical planes, applied to a human body.

The model AnatomicPlanes.blend has scripted drivers, so to get it into the
standard anatomical position, you need to "reload trusted".

Commands to create webm and animated gif using libav:

avconv -framerate 24 -f image2 -i %02d.png -pix_fmt rgb24 -s 320x320 -r 10 -f image2pipe -vcodec ppm - | convert -delay 5 -loop 0 - output.gif

avconv -framerate 24 -f image2 -i %02d.png -c:v libvpx -c:a libvorbis -b:v 4M -qmin 0 -qmax 63 output.webm


[Rendered version on Wikimedia Commons][https://commons.wikimedia.org/wiki/File:Human_anatomy_planes.jpg]

Contributing
------------

Contributions to these models are welcome. 

When you submit new content to this repository, you agree to license it under:

* Creative Commons Attribution-ShareAlike 3.0 Unported License (“CC BY-SA”), and

* GNU Free Documentation License (“GFDL”) (unversioned, with no invariant
  sections, front-cover texts, or back-cover texts).

Copyright / License
-------------------

These models are copyright © 2015 David Richfield and Contributors.

It is licensed under both

* [Creative Commons Attribution-ShareAlike 3.0 Unported License][cc-by-sa] (“CC BY-SA”), and

* [GNU Free Documentation License][gfdl] (“GFDL”) (unversioned, with no invariant
  sections, front-cover texts, or back-cover texts).


    Permission is granted to copy, distribute and/or modify this document
    under the terms of the GNU Free Documentation License, Version 1.3
    or any later version published by the Free Software Foundation;
    with no Invariant Sections, no Front-Cover Texts, and no Back-Cover Texts.
    A copy of the license is included in the section entitled "GNU
    Free Documentation License".

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/3.0/
[gfdl]: http://www.gnu.org/copyleft/fdl.html
