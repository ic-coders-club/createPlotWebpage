createPlotWebpage
=================

Makes a nicely formatted webpage from a directory of plots stored as .eps files.
Have your favourite plotting code ROOT, matplotlib or whatever output as an a bunch of eps files in a folder at (say):

    /home/hep/bob/public_html/myplots

Then run the script as

    ./path/to/createPlotWebpage/makePlotWebpage.sh /hep/home/bob/public_html/myplots

It creates an index.html and formats the plots as clickable thumbnails.

I didn't write this myself, I nicked it from Kostas.
