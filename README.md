# ski-area-annotation

### Instructions for annotating ski areas: ###

Run a local web server:

    python -m SimpleHTTPServer 8008

Go to a continent (i.e. Europe). Click on one of the numbers on the right. Each
of these numbers refers to the size of a particular ski area. If there's
nothing in the text field next to the number, then that area hasn't been
annotated. If you know its name, enter it in the text field.

If you know the name of a different ski area, you can find it on the map and
click on it.  This will highlight it in the list on the right. If it lacks a
name or the name is wrong, feel free to update it. 

When you're finished, click `Export Json` and save the resulting file here:

    jsons/ski-areas/[continent-name]/uids-to-names.json

Where `continent-name` is the continent in which the ski area is.

This data will eventually be added back to OSM and used to all kinds of fun
projects like [comparing the sizes of ski
areas](http://emptypipes.org/largest-ski-areas).

You're welcome to use this data for your own devices, but it would be nice
if you would mention that it came from here.

The end.
