# ski-area-annotation

### Instructions for annotating ski areas: ###

Run a local web server:

    python -m SimpleHTTPServer 8008

Go to a continent (i.e. Europe). Click on one of the areas on the right. If there's nothing
in the text field next to the area, then that area hasn't been annotated. If you know it's
name, enter it in the text field.

If you know the name of a different ski area, you can find it on the map, and click on it.
This will highlight it in the list on the right. If it lacks a name or the name is wrong,
feel free to update it. 

When you're finished, click `Export Json` and save the resulting file in the:

    jsons/ski-areas/[continent-name]/uids-to-names.json

Where `continent-name` is the continent in which the ski area is.

The end.
