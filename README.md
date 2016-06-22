imagine-crawl
=============

Image catalog: make archives of photographs more accessible.

This is the crawler, which creates and updates archives (or galleries, if you
wish). It builds on top of [imagine-core](https://github.com/aquatix/imagine-core),
which contains the models. A web frontend (or gallery) is available as
[imagine-web](https://github.com/aquatix/imagine-web).


## Why an image archiver?

As a (hobby) photographer, you might have years and many gigabytes of material
on your drives which you only rarely watch back. To make it more easy to find
certain pictures or just provide a fun trip down memory lane, use imagine to
make an overview of your archives.

The goal is not to import the images into a (new) archive and manage collections
from there, but to provide an easy-to-use overview of your work. This can even
be used standalone (think on a different machine with no access to your library).

src/cr2tojpg.sh
---------------
apt-get install libimage-exiftool-perl pvrg-jpeg dcraw
